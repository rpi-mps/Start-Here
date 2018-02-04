# Start-Here

**Overview**

These repositories contain the necessary code and documentation for progressing through the Microprocessor Systems course at Rensselaer Polytechnic Institute (course ECSE-4790). The course is a lab-focused course in which students are to complete in-depth labs in ordered sequence, and it has been newly revamped and updated (as of 2017) to migrate from the venerable C8051s to STM32F7s (model STM32F769NI).

In order to work through the content of this course, the materials in the file BOM.txt are needed. Mac and Linux users should download BOM_LF.txt, as Unix/Linux uses different style line endings than Windows (Windows uses a format called CRLF to denote the end of a line of text, while Linux and Mac use LF).  

A desciption of each repository is provided below:

- **Start-Here** - This repository  
- **References** - Required documentation  
- **Workbench-Labs** - The lab folders for use with SystemWorkbench   
- **Scripts-Labs** - The lab folders for use with the scripts-based system  
- **Scripts-Windows-Binaries** - Scripts-based development environment for Windows  
- **Scripts-Mac-Binaries** - Scripts-based development environment for Mac  
- **Scripts-Linux-Binaries** - Scripts-based development environment for Linux  

**Recommended Text**

The book "Mastering STM32" by Carmine Noviello is extremely highly recommended, as it elaborates on topics that are given only brief treatment in ST Micro's own documentation. It can be bought from Leanpub for $30: https://leanpub.com/mastering-stm32. A nice thing about this book is that, once you own it, there are no silly expiration dates or anything like that: you just buy the PDF and that's it. Note that there is no physical version.

**Getting Started**

This course supports Linux, Mac, and Windows, and provided within these repositories are two development environments for each. The first is an Eclipse-based IDE ("SystemWorkbench for STM32") with a built-in step-by-step debugger and all the bulk that comes with Eclipse-based IDEs. The second is a custom built, scripts-based system that was made by stripping down STM32 Workbench into simple "Compile," "Upload," and "Cleanup" scripts. The scripts system is meant for those who prefer a minimalistic environment and using their own IDE, e.g. vim or Atom, but it does not have a live debugger. Depending on the environment desired, you only need the contents of a subset of the repositories hosted here.

The repositories needed for each development environment are listed below:

***SystemWorkbench (Eclipse-based):***  
- References  
- Workbench-Labs  

Once downloaded and extracted to a suitable location (avoid spaces in folder names), the "STM32 Workbench Install and Usage Guide" can be found in the Lab01 folder. A copy of it is also in References.  

***Custom Compile Scripts:***  
- References ***(1)***  
- Scripts-Labs  
- Scripts-[OS]-Binaries ***(2)***   

Once downloaded and extracted to a suitable location (avoid spaces in folder names), you will need to further extract your OS's Scripts Binaries archive (the file named MPS_[OS].zip) per the instructions given in its repository. Also, make sure the Scripts Labs are put into the MPS folder that gets created upon extraction of the Scripts Binaries archive. 

After that, you will find the "Before you start" file in the MPS folder, and that's it for setting up this system!

***(1)*** *Ignore the STM32 Workbench Install and Usage Guide. It does not apply to this environment.*  
***(2)*** *Pick the one for your OS.*  

NOTE: It is possible to have both development environments, e.g. if you want the live debugger provided by SystemWorkbench in addition to the flexibility of the compile script system, but this configuration can be particularly annoying to set up. You are on your own if you want to do this.
