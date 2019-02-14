# Setup instructions
For the Demystifying C/C++ sessions we will be using the GCC compiler to build our code. Install instructions for it can be found bellow. Select the platform that is relevant for you.

[Lab Machines](#lab-machines)  
[Windows](#windows)  
[MacOS](#macos)  
[Linux](#linux)  

## Lab Machines

## Windows
For windows a port of GCC is needed. The one we will be using is called [MinGW](http://www.mingw.org). The installer for it can be found [here](http://sysprogs.com/getfile/31/mingw64-gcc4.7.1.exe).

## MacOS
GCC should already be installed with your system. To use it simply open a terminal. You can test that it is correctly installed by using the command `gcc --version` this should give some basic information about the version installed.

## Linux
GCC comes packaged on most linux distributions, you can test if it is installed on your system with the command `gcc --version`. If it is installed then you will get some information about the version. If it is not installed you should get a command not found error. If that is the case then you will need to install it via your package manager. Typically the package is called `gcc`.
