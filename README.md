# Setup instructions

## Text editor
We will not be making use of any specific IDE or text editor for these Demystifying C/C++ sessions. Therefore the choice of text editor is a personal one. Some recommended options are [Atom](https://atom.io/), [VSCode](https://code.visualstudio.com/) or then nano text editor if you wish to stick to the command line.

## Compiler
For the Demystifying C/C++ sessions we will be using the [GCC compiler](https://gcc.gnu.org/) to build our code. Install instructions for it can be found bellow. Select the platform that is relevant for you.

[Lab Machines](#lab-machines)  
[Windows](#windows)  
[MacOS](#macos)  
[Linux](#linux)  

### Lab Machines
The lab machines have GCC installed already. Full instructions on how to set it up for your user and how to use it on those machines will be added later.

### Windows
For windows a port of GCC is needed. The one we will be using is called [MinGW](http://www.mingw.org). The installer for it can be found [here](http://sysprogs.com/getfile/31/mingw64-gcc4.7.1.exe). Download and then run that file and you should get a window that looks like this: 

![screenshot](https://github.com/swanhack/Demystifying-C/blob/master/mingw.png)

Accept the license agreement and click install. Once this has finished you should be able to open PowerShell and run the command `gcc --version`. If it is not installed you will get a command not found error. If it has been correctly installed then you should get some basic information about the install.

### MacOS
GCC should already be installed with your system. To use it simply open a terminal. You can test that it is correctly installed by using the command `gcc --version` this should give some basic information about the version installed.

### Linux
GCC comes packaged on most linux distributions, you can test if it is installed on your system with the command `gcc --version`. If it is installed then you will get some information about the version. If it is not installed you should get a command not found error. If that is the case then you will need to install it via your package manager. Typically the package is called `gcc`.
