 
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
Right Click to SipClient Project and open Properties

Paths: VC++ Directories: Add Path

Executable Directories:
C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\bin;$(ExecutablePath)

Include Directories:
$(IncludePath);C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\VC\include;C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\VC\atlmfc\include;

Reference Directories:
C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\atlmfc\lib;$(ReferencePath)

Library Directories:
C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\VC\lib;C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\lib;$(LibraryPath); $(SolutionDir)..\..\binaries\lib;C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\VC\atlmfc\lib;

C\C++Directories:
$(SolutionDir)..\..\include\xmlAddOns;$(SolutionDir)..\..\include\xdm;$(SolutionDir)..\..\include\vmediaDev;$(SolutionDir)..\..\include\sip;$(SolutionDir)..\..\include\simpleClient;$(SolutionDir)..\..\include\sdp;D:\$(SolutionDir)..\..\include\rvVideoCodec;$(SolutionDir)..\..\include\pthread;$(SolutionDir)..\..\include\mtf;$(SolutionDir)..\..\include\media;$(SolutionDir)..\..\include\management;$(SolutionDir)..\..\include\h323;$(SolutionDir)..\..\include\h245;$(SolutionDir)..\..\include\common;$(SolutionDir)..\..\include\asn1;$(SolutionDir)..\..\include\asf;$(SolutionDir)..\..\include\artp;$(SolutionDir)..\..\include\ads;$(SolutionDir);$(SolutionDir)..\..\include\voipEngine;%(AdditionalIncludeDirectories)

Convo Project Structure

Create folder in structure and check the file/put it.
C:\Program Files (x86)\Windows Kits\10\bin\x86\signtool.exe C:\CONVO\Certificados\ConvoWindows.pfx C:\CONVO\github\appl\DesktopConvo\bin\Debug\Convo.exe
