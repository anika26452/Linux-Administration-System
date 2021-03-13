# Linux-Administration-System

## What is Shell?

Shell is a computer program that takes keyboards commands and passes them to the Operating System to carry out. There are several different shells available for Unix; the most popular are described here - sh, bash, zsh, csh, ksh. When using a graphical user interface, we need another program called a terminal emulator to interact with the shell which is simply called **Terminal**. To open terminal press ___Ctrl+Alt+T___. Once it comes up, we can see **shell prompt**. It shows current directory & the last character will be dollar sign(%).

> If the last Character is pound sign(#), it says, the terminal has the **Superuser Privilages**. This mean either we are logged in as the root user or the terminal is using **Superuser Privilages**.

<br>

## Directories Found On Linux Systems

<pre>
    /       :   The root directory. Where everything begins.
    /bin    :   Contains binaries (programs) that must be present for the system to boot and run.
    /boot   :   Contains the Linux kernel, initial RAM disk image and the boot loader.
    /dev    :   This is a special directory which contains device nodes. Here is where  the kernel maintains a list of all the devices it understands.
    /etc    :   The /etc directory contains all of the system-wide configuration files. It also contains a collection of shell scripts which start each of the system services at boot time. Everything in this directory should be readable text.
    /home   :   In normal configurations, each user is given a directory in /home.
    /lib    :   Contains shared library files used by the core system programs.
    /opt    :   The /opt directory is used to install “optional” software.
    /proc   :   It is a virtual file system maintained by the Linux kernel. The “files it contains are peepholes into the kernel itself. The files are readable and will give you a picture of how the kernel sees your computer.
    /root   :   This is the home directory for the root account.
    /sbin   :   This directory contains “system” binaries. These are programs that perform vital system tasks that are generally reserved for the superuser.
    /tmp    :   The /tmp directory is intended for storage of temporary, transient files created by various programs.
    /usr    :   The /usr directory tree is likely the largest one on a Linux system. It contains all the programs and support files used by regular users.
    /usr/bin    :   /usr/bin contains the executable programs installed by your Linux distribution.
    /usr/lib    :   The shared libraries for the programs in /usr/bin.
    /usr/local  :   The /usr/local tree is where programs that are not included with your distribution but are intended for systemwide use are installed. Programs compiled from source code are normally installed in /usr/local/bin.
    /usr/sbin   :   Contains more system administration programs.
    /usr/share  :   This contains all the shared data used by programs in /usr/bin. This includes things like default configuration files,icons,screen backgrounds,sound files, etc.
    /usr/share/doc  :   Most packages installed on the system will include some kind of documentation. Here, we will find documentation files organized by package.
    /var    :   With the exception of /tmp and /home, the directories we have looked at so far remain relatively static, that is, their contents don't change. The /var directory tree is where data that is likely to change is stored. Various databases, spool files, user mail, etc. are located here.
    /var/log    :   /var/log contains log files, records of various system activity. These are very important and should be monitored from time to time. The most useful one is /var/log/messages. Note that for security reasons on some systems, you must be the superuser to view log files.
</pre>

## All Commands:
- date &nbsp; : &nbsp; Displays the current time and date
- cal&nbsp; : &nbsp; Displays calendar
- df&nbsp; : &nbsp; Displays current amount of free spaces
- free&nbsp; : &nbsp; Displays the amount of free memory
- exit&nbsp; : &nbsp; Close Terminal
- pwd&nbsp; : &nbsp; Print the name of Current Working Directory
- cd&nbsp; : &nbsp; Change the directory

<pre>
cd shortcuts:
    cd     : Change the working directory to home directory
    cd -   : Change the working directory to previous directory
</pre>

- ls &nbsp; : &nbsp; List of directory contents

<pre>
ls option:
    -a    : List all files
    -ld   : to see details about the directory rather than its contents
    -F    : add an indicator character end of each listed name
    -h    : display in human readble format
    -l    : display in long format
    -r    : display in reverse
</pre>

- file &nbsp; : &nbsp;  Determine files type
- less &nbsp; : &nbsp; View file contents
