Quote for the mind:  
Our prime purpose in this life is to help others.   
- And if you can't help them, at least don't hurt them. 
- Dalai Lama

# OS-install-on-external-HD
https://learning.lpi.org/en/learning-materials/101-500/

Introduction: 
Hi everyone, 
I just want to let everyone know that most of my deep multi-layer Linux Administrator knowledge comes from two books. 
This is one of them: https://learning.lpi.org/en/learning-materials/101-500/. Most of the topics and skills used on this project,
are studied, learned, and practiced from Linux Professional Institute (LPI). Also, I highly recommend learning Linux from the beginning. 
Start from the buttom ground and learn up. You maybe surprised on what you know verse how the book clearly break down technologies.

Description: 
This project installs a Linux operating system (OS) on a external hard drive (HD).
This project should help your understand, Basic Input/Output System (BIOS), 
Master Boot Record (MBR) vs GUID Partition Table (GPT), Unified Extensible Firmware Interface (UEFI), 
Logical Volume Manager (LVM), and OS file system types.
We will be manually configuring the OS that is being install to the HD. 
Again, topic can be better understood by using LPI's book: 
https://learning.lpi.org/en/learning-materials/101-500/

Features:
I am using Windows Subsystem for Linux (WSL2), which runs beside Windows 11 OS.
WSL2 acts as a virtual machine (VM) that mounts Linux kernal to use
Linux's distributions. Depending on how the Linux kernal is being used,
Windows OS will give you errors, hardship, and compatibilities problems
because Linux kernal cannot see outside of WSL2; therefore, leading you 
to find a work around. WSL2 adds a different trail by fire type of learn; however, 
I also believe that once you have conquered the trails (software and hardware errors or non-compatibilities) 
one should opt on the side of effciency and performance. Now I have Rocky Linux 10 installed
on my 5TB external HD because Linux has a wide-range of compatibility with
different hardwares and softwares.

Technologies Used: This is what I am using to install Linux OS.
- Window 11 OS on a laptop 
- Linux kernal (WSL2 )with distribution 
- Distributions: Debian (Package Manager) and Ubuntu (File & System file management) 
- A second monitor screen 
- I recommend using a Linux native OS vs WSL2 

Prerequisites: List things the user needs before they can run or install your project
- Rocky Linux 10: https://rockylinux.org/download
- AMD and Intel 64-bit architectures for x86-64
- Balena Etcher downloaded: https://balena.io/etcher
- External HD (100GB or more for add features)
- USB flash drive (10GB or more)

Installation:
Use my Step-by-Step OS installation for added information:
https://github.com/axruffin2055/OS-Install-on-External-HD/blob/main/Step-by-Step
Use Rocky Linux for straightforward installation:
https://docs.rockylinux.org/guides/installation/

Usage: Show how to use the project after installation
