# Start-Here

What is all this?  

These repositories contain the necessary code and documentation for progressing through the Microprocessor Systems course at Rensselaer Polytechnic Institute (course ECSE-4790). The course is a lab-focused course in which students are to complete in-depth labs in ordered sequence, and it has been newly revamped and updated (as of 2017) to migrate from the venerable 8051 to STM32F7s (specifically STM32F769NI).

In order to work through the content of these repositorites, the materials in the file BOM.txt are needed. Mac and Linux users should download BOM_LF.txt (Unix uses different style line-endings/"enter-spaces" from Windows: Windows uses CRLF, while Linux and Mac use LF). 

The book "Mastering STM32" by Carmine Noviello is extremely highly recommended.

This course now also supports Linux, Mac, and Windows, and provided within these repositories are 2 build systems for each. The first is an Eclipse-based IDE ("STM32 Workbench") with a built-in step-by-step debugger and all the bulk that comes with Eclipse-based IDEs, and the second is a custom scripts-based system that was made by stripping down STM32 Workbench into simple "Compile," "Upload," and "Cleanup" scripts. The build scripts system is meant for those who prefer a more minimal environment and using their own IDE, e.g. vim or Atom, and does not have a debugger. As such, to get started one only needs the contents of certain repositories hosted here depending on the build system desired.

The repositories are as follows:

**Start-Here** <- This repo.  
**References** <- Documentation needed (required by all)  
**Workbench-Labs** <- Clone or download this to use STM32 Workbench  
**Scripts-Linux-Binaries** <- Scripts-based build system for Linux  
**Scripts-Mac-Binaries** <- Scripts-based build system for Mac  
**Scripts-Windows-Binaries** <- Scripts-based build system for Windows  
**Scripts-Labs** <- The lab folders for the script-based system  

In short, for each build system (you only need one or the other), the repositories to download are as follows:

**STM32 Workbench (Eclipse-based  IDE)**  
-References  
-Workbench-Labs *(OS-independent; STM32 Workbench install guide is in the Lab01 folder AND in References)*  

**Build Scripts**  
-References *(Ignore the STM32 Workbench install guide)*  
-Scripts-Labs  
-Scripts-[OS]-Binaries *(pick the one for your OS)*  

The recommended course text is "Mastering STM32" by Carmine Noviello on Leanpub:  
https://leanpub.com/mastering-stm32  
It's $30, and once you own it there's no silly expiration dates or anything like that--you just buy the PDF and that's it. Note: There's no physical version.

Date last updated: 11/13/2017
