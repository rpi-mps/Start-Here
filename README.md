# Start-Here

**Overview**

These repositories contain the necessary code and documentation for progressing through the Microprocessor Systems course at Rensselaer Polytechnic Institute (course ECSE-4790). The course is a lab-focused course in which students are to complete in-depth labs in ordered sequence, and it has been newly revamped and updated (as of 2017) to migrate from the venerable C8051s to STM32F7s (model STM32F769NI).

In order to work through the content of these repositorites, the materials in the file BOM.txt are needed. Mac and Linux users should download BOM_LF.txt, as Unix uses different style line-endings/"enter-spaces" from Windows (Windows uses CRLF, while Linux and Mac use LF).  

**Recommended Text**

The book "Mastering STM32" by Carmine Noviello is extremely highly recommended, as it elaborates on topics that are given only brief treatment in ST Micro's own documentation. It can be bought from Leanpub for $30: https://leanpub.com/mastering-stm32. A nice thing about this book is that, once you own it, there are no silly expiration dates or anything like that: you just buy the PDF and that's it. Note that there is no physical version.

**Getting Started**

This course supports Linux, Mac, and Windows, and provided within these repositories are two development environments for each. The first is an Eclipse-based IDE ("SysytemWorkbench for STM32") with a built-in step-by-step debugger and all the bulk that comes with Eclipse-based IDEs. The second is a custom built, scripts-based system that was made by stripping down STM32 Workbench into simple "Compile," "Upload," and "Cleanup" scripts. The scripts system is meant for those preferring a minimalistic environment and using their own IDE, e.g. vim or Atom, but it does not have a live debugger. Depending on the environment desired, you only need the contents of a subset of the repositories hosted here.

The repositories are as follows:

- **Start-Here** - This repository  
- **References** - Required documentation  
- **Workbench-Labs** - The lab folders for use with SystemWorkbench   
- **Scripts-Labs** - The lab folders for use with the scripts-based system  
- **Scripts-Windows-Binaries** - Scripts-based development environment for Windows  
- **Scripts-Mac-Binaries** - Scripts-based development environment for Mac  
- **Scripts-Linux-Binaries** - Scripts-based development environment for Linux  

**Getting the Labs and Development Environments***

These are the repositories needed for each development environment:

***SystemWorkbench (Eclipse-based):***  
- References  
- Workbench-Labs  

The "STM32 Workbench Install and Usage Guide" is located in the Lab01 folder, and a copy of it is also in References.  

***Custom Compile Scripts:***  
- References ***(1)***  
- Scripts-Labs  
- Scripts-[OS]-Binaries ***(2)***   

The "Before you start" file will be located in the MPS folder, which will be created when you extract the archive containing your OS's compile scripts environment.

***(1)*** *Ignore the STM32 Workbench install guide.*  
***(2)*** *Pick the one for your OS.*  

It is possible to have both development environments, e.g. if you want the live debugger provided by SystemWorkbench in addition to the flexibility of the script system, but this configuration can be particularly annoying to set up. You are on your own if you want to do this.
