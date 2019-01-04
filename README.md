
# COMPONENT GUIDE


### Content
1. Instructions
2. General Information	
3. Required files	
4. Flows

### Instructions

**General Information For Development requirements**
 
Software Requirements | 
------------ | 
Visual Studio 2015 Professional 
Visual C++ 2015
Version InstallShield 2015 Limited Edition for Visual Studio

### Projects
Projects | Technology
------------ | ------------
Convo | Winforms + C#
InstallConvoWindows | InstallShield LE
MobileAPI | C#
SIPClient | Visual C++
Sparkle | Visual C++
ColorSlider | C#
SIPConvo | C#
MessageBoxManager | C#


### Structure of the project


Projects Description


Figure 1 Project in Visual Studio
Convo
Main project of the solution, integrates all the components and listens to SIPClient events


InstallConvoWindows
Installer of the application, it is important to note that it is the InstallShield 2015 Limited  Edition for Visual Studio version so some things can not be done easily (we must go to cmd or powershell)

MobileAPI
This project (assembly) contains all the integration with MobileAPI REST services and returns the results as objects

SIPClient
Project developed with Visual c ++ in which the entire framework of Spirent 3.5.0.64 is integrated


Figure 2: important configuration



### Sparkle (v.0.5.7)
https://winsparkle.org/

### ColorSlider
Custom control used to handle the advance status of videoMail

### SIPConvo
Project that has enumerations and structures to integrate SIPClient (some structures are mirror of SIPClient C ++ but in C #)

### MessageBoxManager
Custom control to standardize the messageBox according to the Convo format
#

# SipClient 

__Right Click to SipClient Project and open Properties__
![Image of ref](https://github.com/raj-d/GitSync/blob/master/ref_1.png)
#
__Paths: VC++ Directories: Add Path__
![Image of ref](https://github.com/raj-d/GitSync/blob/master/ref_3.png)



### Executable Directories: 

C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\bin;$(ExecutablePath)

### Include Directories:

$(IncludePath);C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\VC\include;C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\VC\atlmfc\include;

### Reference Directories:

C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\atlmfc\lib;$(ReferencePath)

### Library Directories:

C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\VC\lib;C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\lib;$(LibraryPath); $(SolutionDir)..\..\binaries\lib;C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\VC\atlmfc\lib;

### C\C++Directories:
$(SolutionDir)..\..\include\xmlAddOns;$(SolutionDir)..\..\include\xdm;$(SolutionDir)..\..\include\vmediaDev;$(SolutionDir)..\..\include\sip;$(SolutionDir)..\..\include\simpleClient;$(SolutionDir)..\..\include\sdp;D:\$(SolutionDir)..\..\include\rvVideoCodec;$(SolutionDir)..\..\include\pthread;$(SolutionDir)..\..\include\mtf;$(SolutionDir)..\..\include\media;$(SolutionDir)..\..\include\management;$(SolutionDir)..\..\include\h323;$(SolutionDir)..\..\include\h245;$(SolutionDir)..\..\include\common;$(SolutionDir)..\..\include\asn1;$(SolutionDir)..\..\include\asf;$(SolutionDir)..\..\include\artp;$(SolutionDir)..\..\include\ads;$(SolutionDir);$(SolutionDir)..\..\include\voipEngine;%(AdditionalIncludeDirectories)

### Convo Project Structure

Create folder in structure and check the file/put it.
C:\Program Files (x86)\Windows Kits\10\bin\x86\signtool.exe C:\CONVO\Certificados\ConvoWindows.pfx C:\CONVO\github\appl\DesktopConvo\bin\Debug\Convo.exe
