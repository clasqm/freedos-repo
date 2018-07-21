# FreeDOS Tips

-----

{: style="text-align:center"}
[Return to General Index](README.md)

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

-----

{: style="text-align:center"}
[Return to General Index](README.md)

-----
