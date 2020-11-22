# FreeDOS Tips

-----

{: style="text-align:center"}
For installation instructions, please [return to General Index](README.md)

-----

These are just a few tricks that I figured out to make my life in FreeDOS a little easier.

**1. Fix the floppy drive blues.**

Who still has a computer with a floppy drive? But old DOS apps assume that it is there and will throw up error messages if you accidentally select that drive. Here's the fix:
````
MKDIR C:\FDOS\DRIVEA
MKDIR C:\FDOS\DRIVEB
````
Now include the following lines in your AUTOEXEC.BAT

````
SWSUBST A: C:\FDOS\DRIVEA
SWSUBST B: C:\FDOS\DRIVEB
````

**2. Bare-ass booting**

If you are developing a program or trying to figure out why that downloaded application does not work, it can be useful to boot FreeDOS with **no drivers at all**. The default FreeDOS boot menu is misleading: it does include some memory drivers even on option 3. So let's pretend it's 1981 and boot FreeDOS with just 640Kb, COMMAND.COM taking up some of that, and absolutely nothing else!  

**IN FDCONFIG.SYS or FDCONF.SYS**  

Add the following line at the beginning of the MENU block:  

    menu 0 - Load FreeDOS with NOTHING AT ALL

or whatever text description you prefer. Here's where it gets tricky. According to the documentation, a MENU line will only be selectable if there are lines starting with things like 12? or 324? further down that actually reference that number, [EXCEPT if it is 0](http://help.fdos.org/en/hhstndrd/cnfigsys/menu.htm). But in fact, that does not work and if you reboot now, option 0 will appear on screen but will not actually work. So let's cheat and give option 0 something to "do". Add the line:  

    0?REM

with **no spaces**. REM is technically a command. It just happens not to do anything.  

**In AUTOEXEC.BAT or FDAUTO.BAT**  

Right at the end, on the very last line (open up a new last line if you have to), add the following:  

    :THEVERYEND

Now we need to GOTO that line if we selected option 0. Ideally we want to do that after the system variables like FILES, PATH and COMSPEC have been set, but before we load any .COM or .EXE into memory. There usually is a whole block of SET statements. Just after those, create this line:  

    IF "%config%"=="0" GOTO THEVERYEND

Reboot and run MEM /c to admire your pristine, primitive memory setup.

**3. Built-in screen blanker**

No need to install an obscure TSR if all you want to do is turn off your screen after a while. Instead, just put this line in your AUTOEXEC.BAT:

````
LH IDLEDPMS 5
````
It uses up just 464 bytes of high memory.

-----

{: style="text-align:center"}
For installation instructions, please [return to General Index](README.md)

-----
