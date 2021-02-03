# Batch File Hunter
[![Open Source Helpers](https://www.codetriage.com/biltudas1/batchfilehunter/badges/users.svg)](https://www.codetriage.com/biltudas1/batchfilehunter)
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

# Sample Files

Safe.bat  
* md5    - 9e60c6126dfdfa9f3af0b58a766b8018
* Sha256 - 38a059893431ad8f34bfe9392240d773758b59071161c34fd619c20d2871bbe2

Noabatch.bat
* md5    - c113b865d2050013375f95cbd32a346b
* sha256 - ee822158937e0ae920573deea9e6eec71251ec2c01226c184b77f4ec156a8568

Unsafe.bat
* md5    - 8f112f449e0c5c7286cab5a9274548ca
* sha256 - b846521751a70ea58d2aba51d89e47040e50d1723d144b5827a9a8cef23d674e


Source : [How to detect a batch file is safe or not](https://www.stopback.tk/2020/11/how-to-know-that-batch-file-is-safe-or.html)

# Contact
If you still any issue then you can contact me at [STOPBACK](https://www.stopback.tk/p/contact-us.html)
