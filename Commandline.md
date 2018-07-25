# Command-line utilities

-----

{: style="text-align:center"}
[Return to General Index](README.md)

-----

Most of these will end up in C:\FDOS\BIN. **Please note** that there are only so many filenames available when you have just eight characters to play with. You may already have a utility with the same name. If UNZIP asks whether to overwrite a file, think very carefully whether you want to use this file rather than the default FreeDOS one. I have tried to weed them out, but I may have missed some, and future versions of FreeDOS will no doubt contain more UNIX CLI ports.

+ [ACD](./zip/acd.zip) - Another Change Directory.
    + Freeware by Kevin Solway.
    + ACD is used to switch quickly between directories across any drive. You simply invoke ACD and give it the full or partial name of the directory you wish to change to.
    + For example, if you have a directory named D:\COMM\KERMIT you could switch to this directory with the command ACD KER
    + ACD will first try to do an immediate change to the directory name that you specify.
    + If that change works, ACD simply exits immediately. If it fails, then ACD looks into your directory database and tries to figure out the directory name that you wanted.
    + If more than one directory existed with the same partial name that you gave to ACD, it will display a pop-up window on the screen containing all of the matches found.
    + Simply use the movementkeys (PgUp, PgDn, Home, End, Arrow keys) to highlight the directory that you want to change to, then hit ENTER.

![acd](./imgs/acd.png)

+ [ANTIWORD](./zip/antiword.zip) - Extract text and (hopefully) images from a Microsoft Word .doc (not .docx) file.
    + GNU GPL v2 licensed.
+ [BELIEF](./zip/belief.zip) - generate random religious beliefs.
    + Public Domain sofware (as far as could be ascertained) with additional data by Michel Clasquin-Johnson. See also [this page](https://clasqm.github.io/Belief/).
    + Compiled with *BCC* under *FreeDOS* 1.2
    + *Example output:*
````
The Arian Theosophist Sect suspects that Darwin's "Origin of Species"
if read backwards, reveals cryptic messages from the last practicing
medicine man of the Mohicans, and says that only the faithful will
achieve reincarnation.
````
+ [BFIND](./zip/bfind.zip) - Enhanced FIND command.
    + The BFIND.EXE program adds Boolean logic to DOS's FIND command.
    + Freeware for personal use by Bruce Guthrie.
    + See the LSM file for instructions.

+ [BLRMU](./zip/blrmu.zip) v22 - Bud L Rasmussen's Mini Utilities.
    + Freeware / Public Domain.
    + For more extensive descriptions of these utilities, see the appropriate .doc file for any specific utility.
    + Miscellaneous utilities
        + BCR - Batch Carriage Return
        + BEEP7 - Beep 7 times
        + BEEPN - Beep n times
        + BUK - Beep Until Keypress
        + CCC - Color Change Command
        + CLR - Clear the screen to color at x=0, y=0
        + CRSR - Cursor control
        + CRST - Cursor Reset
        + DAFEM - Display Available, Free, Extended Memory
        + DFM - Display Free Memory
        + DIV - Display Interrupt Vectors
        + DIVOP - Display Interrupt Vectors On Printer
        + FD - Find Directory
        + FF - Form Feed
        + GO - Go to drive + directory
        + JD - Jump Directory
        + LFD - Label Floppy Disk
        + PBM - Put Batch Message
        + PRT - Print multiple copies of text files
        + TO - change TO drive + directory
        + TONL - Turn Off Num Lock
        + TRAD - Typematic Rate And Delay
    + Tune playing utilities
        + BIRDCALL - Play 'Birds' call (intro to 'Parkers Mood')
        + ITAINT - Play 'It Aint Necessarily So'
        + KCBLUZ - Play 'KC Blues'
        + NEWBLUZ - Play 'New Blues'
        + OLDBLUZ - Play 'Old Blues'
        + RITES - Play intro to "Rites of Spring'
    + Screen color change utilities
        + BLUWHT - Clear screen to white on blue
        + BLUYLO - Clear screen to yellow on blue
        + BRNWHT - Clear screen to white on brown
        + BRNYLO - Clear screen to yellow on brown
        + CYNWHT - Clear screen to white on cyan
        + CYNYLO - Clear screen to yellow on cyan
        + GRNWHT - Clear screen to white on green
        + GRNYLO - Clear screen to yellow on green
        + MAGWHT - Clear screen to white on magenta
        + MAGYLO - Clear screen to yellow on magenta
        + REDWHT - Clear screen to wht on red
        + REDYLO - Clear screen to yellow on red
        + WHTBLK - Clear screen to black on white

+ [BLRUT](./zip/blrut.zip) - *Bud L Rasmussen's Utilities* 
    + 28 general purpose DOS utilities.
        + BD -- Backup Directory
        + BHD -- Backup Hard Disk
        + BLF -- Backup Large File
        + BLRUT -- Executable form of BLRUT55.DOC
        + CACF -- Copy And Convert File
        + CF -- Copy File
        + DBPB -- Display BIOS Parameter Block
        + DCM -- Directory Copy/Move
        + DDBT -- Display Disk Base Table
        + DKV -- Display Key Value
        + DPT -- Display Partition Table
        + DSE -- Disk Sector Edit
        + EADF -- Erase All Diskette Files
        + EBU -- Execute BLR Utilities (menu/shell)
        + FCM -- File Copy/Move
        + FFD -- Format Floppy Diskette
        + FRE -- File Record Edit
        + LPAF -- List/Print Any File
        + LPD -- List/Print Directory
        + LPS -- List/Print Sector
        + LPTF -- List/Print Text File
        + LTF -- List Text File
        + PSF -- Print Spooled File
        + QDL -- Quick Directory List
        + RLF -- Restore Large File
        + RSD -- Rename Sub Directory
        + SD -- Space Display
        + SLTF -- Split Large Text Files
        + TFC -- Two File Compare
        + VLCC -- Volume Label Change, Compare
+ [CHANGE](./zip/change.zip) - Find-and-replace from the command line.
    + Processes change commands in files.
    + Files can be of any size and type (binary or text) and are processed quickly.
    + Up to thirty change commands can be processed in a single pass.
    + Also provides ability to remove trailing spaces from text files.
    + Freeware by [Bruce Guthrie](bguthrie@doc.gov) / U.S. Dept of Commerce.

+ <a name="dospdf"></a>[DOSPDF](./zip/dospdf.zip) - PDF viewer.
    + An outragous hack by [Mateusz Viste "Fox"](http://mateusz.viste.free.fr/dos).
    + This crashes my DOSBox, but works (slowly!) on a real FreeDOS install.
    + Use it when the old Acrobat for DOS chokes on a modern PDF.
    + Requires the *CDD* command - everything else is included, even a working installation of Alladdin Ghostscript.
    + I've done the SETUP already and copied the resulting batch file into /FDOS/BIN, so it should be ready to run.

+ [Figlet](./zip/figlet.zip) - A program that creates large characters out of ordinary screen characters.

![figlet](./imgs/figlet.png)

+ [GUTREAD](./zip/gutread.zip) -  read texts from the Gutenberg Project (or any other text file) and remove all the newlines saving hours of editing in your word processor.
    + It will also produce the text in XML format.
    + See the LSM file for instructions.
    + Another utility that does the same thing is [WPPREP](./zip/wpprep.zip) by Les Leist.

+ [INKUTILS](./zip/inkutils.zip) - A collection of utilities.
    + DD - Allows a directory (and its contents) to be deleted. Much more friendly than DELTREE
    + DEDIT - A full-screen 4DOS/NDOS/TakeCommand file description editor.
    + CC - A control panel for the SmartDrv (or any compatible) disk cache.
    + EE - A flexible calculator than can be used three ways: Command line calculator, Desktop calculator or TSR popup calculator. 
    + CE -  eplaces the standard "Retry, Ignore, Fail or Abort" message with a popup window that gives much more information on the error that has occurred.
    + TM - Allows various text modes (including any VESA text mode that your video card supports) to be selected.
    + LE - Displays only the executable files (EXE, COM, BAT and, if you're using 4DOS or NDOS, BTM) in the current or specified directory.
    + MCD -  Performs the DOS commands MD and CD in one go.
        + MCD can also create multiple directories in one go (e.g. MCD \one\two\three will create the directories \ONE, \one\TWO and \one\two\THREE ).
        + It can also protect directories, so that Delete Directory cannot delete them.
        + MCD supports Windows 95 long filenames.
    + FM - Reduces the time taken for a program to reset the mouse.
    + DZ - Intercepts any "Divide overflow" errors.
        + PLEASE NOTE: DZ.COM has been renamed to DZ0.com for use in FreeDOS. This prevents a conflict with DosZip Commander.
    + IP - Provides a quick and easy way to see at once which TSR programs from the Inkutils are currently resident in memory.
    + INKUTILS -  A friendly, menu driven user guide covering each Inkutil with full instructions and examples.
    + Freeware by Mark Incley.

+ [OZPACK](./zip/ozpack.zip) 1.3 - Great Australian utilities.
    + Shareware by Kevin Solway (other programs by Solway on this page have been explicitly declared to be freeware. This one has not).
    + I have removed MOVE, since it is already in FreeDOS.
        + ASCII - Simple ascii table displaying the decimal and hexadecimal equivalents of all ascii characters.
        + BEAUTIFY - Beautify thine writing! (complete with sexist language).
        + BIGTYPE - Create large and fancy lettering using only ascii graphic characters.
        + CMOS - Saves and restores the CMOS information on AT type computers (286 and above). 
        + CONVERT - Convert Wordstar format files to standard Ascii, Ascii to Wordstar, and Wordperfect format files to standard Ascii
        + ECALC - CLI inline calculator.
        + EXEMENU - Makes a menu (sorted alphabetically) out of the .EXE files (other than itself) found in same directory as itself.
        + FILEFIND - Finds all files matching a search pattern over a whole disk drive, and optionally moves to the directory of the located file.
        + FINDIN - Search for a string of characters within a standard text file and return with a DOS errorlevel value indicating whether the text has been found in the file.
        + FREE - This program gives a quick report of disk usage.
        + INFO - Provides basic system information, computer speed index and disk space information with diagram. 
        + INSTALL - Software installation with optional execution and uninstallation.
        + LIFE - This program models the processes of competition and selection in natural systems in a colourful graphic format. It will run in CGA mode on any CGA or EGA/VGA system.
        + LZEXE - Compressor for EXE files.
        + MAKECOM - Convert ordinary text files into self-displaying .COM files.
        + MYLIFE - Get a rough idea how many seconds you have left and see your life whittling away. 
        + PCAL - A simple picture calendar program.
        + PCXLIFE - Converts .PCX format graphics files into self-displaying executable programs that can be further compressed with the fabulous LZEXE. 
        + PEEPBO - A short and simple program to encrypt and decrypt files of any type.
        + POPCALC - Calculator.
        + PVIEW - A simple program for previewing the expected page layout when a plain ascii text file is printed.
        + QG - A small and fast program for drawing graphs on an EGA or VGA system.
        + QMEM - Provides a quick report on memory usage, including expanded memory usage. 
        + SEEVIRUS - This program displays the first sector of the selected disk drive. Its primary purpose is to check for viruses that infect the boot sector.
        + SLOWTO - This TSR program provides a convenient way to slow down your computer when the need arises. 
        + STARS - Fly through stars on an EGA or VGA system. Travelling at PRODIGIOUS speed. 
        + STATES - This is a useful program for non-Americans, and perhaps even some Americans, when dealing with American state codes. 
        + TCAPTURE - A memory resident program that can capture text screen images - IN FULL COLOUR - from other programs.
        + TIMEIT - Program to time how long it takes to run other programs - with millisecond accuracy!
        + TITLE - Writes a message to the screen in big letters. Useful in batch files and to grab attention.
        + VGAFCAPT - Will capture the current VGA text font to a file. The file can then be used with the program VGATEXT (which loads VGA fonts into memory). You can use this program to build-up a library of fonts.
        + VGATEXT - This program will change the screen text font on VGA systems.
        + VIEWPCX - Program for displaying .PCX (PC Paintbrush format) pictures. 
        + VIEWSCR - Displays colour text screen images (with extension of .SCR) created by Text Paint or captured by the program TCAPTURE.

+ [OZWOZ](./zip/ozwoz.zip) - the OZWOZ Utilities.
    + A collection of 35 command-line utilities.
    + Freeware for personal, non-commercial use.
        + 3812PRN -- IBM 3812 Pageprinter driver.
        + ALARM -- TSR pop-up alarm clock.
        + CHANGE -- Change text in one or more files.   
        + CHECKTD -- Check current time and/or date and set errorlevel.
        + CLEARKEY -- Clear "n" keystrokes from the keyboard buffer.
        + CURSOR -- Set cursor shape and style.
        + ERRORLVL -- Set the DOS errorlevel (return code).
        + EXERCISE -- Exercise a local or network file system and show performance.
        + FF -- Find file/s and change to directory if required.
        + GETOID -- Return Novell Netware object ID for user, groups, etc.
        + LOCK -- Simple network single application lock.
        + LS -- List file directories with many many options.
        + MAIL -- Simple mail facility for Novell Netware with a delay send option.
        + MAKEMENU -- Self maintaining menu utility with no executing memory overhead.
        + NETTALK -- User talk/chat utility for Novell Netware.
        + PLAY -- Play music and write your own.
        + RESET -- Presses the reset button and/or CTRL+ALT+DEL.
        + SATTRIB -- Modify attributes including hidden, system and sub-directories.
        + SAVEDIR -- Save current directory to a self restoring batch file.
        + SAVEPATH -- Save current path setting to a self restoring batch file.
        + SAVESCR -- Save/restore current text screen contents and attributes.
        + SCOPY -- Copy, move, update, break, concatenate files. By name, date, etc.
        + SCRTYPE -- Return screen type in use. CGA, MCGA, HERC, VGA, EGA, MONO, etc.
        + SD -- Select directory via a menu. Goes well with MAKEMENU utility.
        + SDEL -- Delete files including hidden, protected, in sub-directories, etc.
        + SETVPINF -- Change default directory stored in Ventura Publisher's VP.INF file.
        + SHOWTD -- Show current time/date with many options including a clock.
        + SLEEP -- Sleep for specified period. Can set for keyboard to interrupt.
        + STUDY -- Study helper. Asks questions randomly & gives answers and scores.
        + STUFFKEY -- Stuff keys into the keyboard buffer. No overhead or TSR used.
        + STYPE -- Display files contents with many convert, filter, skip, options.
        + TESTFILE -- Test accessability of a file under many modes. Good network tool.
        + TPBEAUT -- Prepare Turbo Pascal 5.5 code for output to a printer.
        + TYPEBACK -- Type a text file line by line backwards. Good for listing logs.
        + TYPEDW4 -- Types the DisplayWrite 4 EBCDIC file specified.

+ [PEDIT](./zip/pedit.zip) 4.00 - Programming editor.
    + Similar to the FreeDOS EDIT program, but more powerful, and with many additional features for programmers.
    + It includes pop-up tables, column support, macro key, undo, copy & paste to Windows applications, long filenames, word wrap, spell checker & thesaurus (English only, as far as I can make out), HTML support, and much more.
    + Freeware by Goldshell Digital Media.
    + In the Pedit package there's a file called PEDITLGT.EXE. This is the Light version of Pedit.  It's Pedit stripped of several options.
    + The purpose for this is to offer an editor which can easily be included on rescue floppies and such.
    + The omitted options are:
        + Spell checker.
        + Thesaurus.
        + Printing through Windows.
    + The remaining functionality is the same.
    + Also includes INSPECT, a hex editor.

+ [RUTILS](./zip/rutils.zip) v4 - Ricki's little useful (?) DOS utilities is a collection of mainly UNIX-workalike CLI commands.
    + Freeware by Richard Breuer.
    + I have removed CAL and HEAD since they are already in FreeDOS.
        + ASET - Enhanced SET command
        + BANNER - Display strings in huge letters.
        + CAT - Append several outputs to stdout.
        + CHMOD - Change the attributes of files.
        + CUT - Remove selected fields from each line of a file.
        + DCALC - Date Calculations.
        + DCAT - Disk Catalogue maker.
        + DETAB - Change tabs to spaces in several files.
        + ENTAB - Change spaces to tabs in several files.
        + FILE - File type guesser.
        + FMT - ASCII text formatter.
        + GENOUT - Generate program fragments for textual output.
        + HD - Display hex dumps of several files
        + L - Display information about files and directories
        + LOCASE - Change chars in several files from upper to lower case.
        + MCOL - Arrange text in multiple columns.
        + NCONV - Number conversion utility.
        + NODUP - Remove successive equal lines from files.
        + STRINGS - Find printable strings in an object file or binary.
        + TAIL - Show the last lines of a file.
        + UPCASE - Change chars in several files from lower to upper case.
        + WC - Count words, lines, and chars of several text files.

+ [SHOW](./zip/show.zip) 1.4 -  Text file Viewer.
    + Freeware by Horst Schaeffer.
    + SHOW is a small DOS viewer for ASCII text files.
    + The program was primarily made for use in batch files, as it does not come with its own "Open" dialog and directory browser.
    + See the LSM file for instructions.

![Show](./imgs/show.png)

+ [VIEWHT](./zip/viewht.zip) - Quickie HTML viewer and converter.
    + Freeware by Kevin Solway.
    + A very useful tool for viewing web documents off-line, with hypertext linking and colours.
    + You can also use this program to simply convert HTML documents to standard text files.
    + Uses XMS for large files.
    + a similar program is [HLIST](./zip/hlist.zip).

----

{: style="text-align:center"}
[Return to General Index](README.md)

-----
