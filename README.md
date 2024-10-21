# NorthInterface
> v1.0.0

> [!NOTE]
> This product is at developing version. Bugs and errors are not certicated and fixed yet.

> [!CAUTION]
> Mainly you need to install Linux (No Distribution Version). That is going to be important to launch this interface.

> [!WARNING]
> We need Visual Studio Code and Git installed.

# Installation

## How to install Using Winget

Winget tool by Windows manages installation and upgrade of application packages in Windows 10 and 11. To use this tool, you need to have at least Windows 10 or later installed on your PC.

Press `Win + R`

Type `cmd` and press Enter to bring up the Command Prompt.

Type the command `Winget install GnuWin32.make` and press Enter

Type Y to agree to source agreements.

After installation, press `Win + R` again

Type `systempropertiesadvanced` and press Enter.

Select Environment Variables under the Advanced tab

Under System variables, select New.

Under the variable name, enter `make`

Under Variable value, enter `C:\Program Files(x86)\GnuWin32\bin\make.exe`

Press on OK.

## How to install Visual Studio Code

Go to this link.

https://code.visualstudio.com/Download

And press download button. Install Visual Studio Code as other applications.

## How to install Git 

Please go to this link.

https://git-scm.com/downloads/win

And install git depending on your device.

Install Git as other applications.

## How to install this project

Press `Win + R`

First, we are going to need Visual Studio Code and Git installed at our PC. After this we can open a new terminal and type the next command.

`git clone https://github.com/Koriita0/KerneLinuxInterface.git`

After this command we should get all the code. We only are going to need get in the folder so we are going to use.

`cd kernel`

# Development

## New features

First you are going to need to compile your kernel. So after install this project on your device, please go to kernel folder and type the next command

# Lasted Updates

Linux Kernel have been uploaded. We can start working at our interface.
