# Batch File Hunter
### What is Batch file Hunter?  
Batch file hunter is a program which find out dangerous commands into batch file and prevent user from opening batch file from untrusted source. (Recommended for those who don't have knowledge about batch file)

# Commands
BHunter.exe -s D:\test.bat

For creating log file  
BHunter.exe -s D:\test.bat>>D:\logfile.log

* BHunter always save a copy of report into your desktop.

# How does it works?
Batch file run over External or Internal Commands. Mean a batch file will be harmful if commands are written incorectly, Or the file is made for doing harmful activiry into PC. Batch File hunter reads batch file and find those codes which specially used into batch file for harmful activity.

# Requirements

Operating System : Windows XP, Vista, 7, 8, 10  
External Commands : FINDSTR.EXE

### How to check FINDSTR.EXE is installed or not?
Goto *START MENU*>*All Programs*>*Accessories*>*Cmd.exe* and then type *findstr*  

If you get below message then FINDSTR.EXE is not installed into your system.  
Take a help from google to install FINDSTR.EXE. Or you can [contact me](#Contact)  

****'findstr' is not recognized as an internal or external command, operable program or batch file.****

# Contact
If you still any issue then you can contact me at [STOPBACK](https://www.stopback.tk/p/contact-us.html)
