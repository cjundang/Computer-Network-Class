## __Network OS Administration__
### __Aims__
- install linux OS
- understand linux command
### __Resources__
- [Linux Ubuntu Live Server AMD64 ISO file](http://mirrors.bangmod.cloud/ubuntu-release/18.04.1/ubuntu-18.04.1-live-server-amd64.iso)
- [Bash shell cheat sheet](https://learncodethehardway.org/unix/bash_cheat_sheet.pdf)
- [Linux Toolsboox](http://cb.vu/unixtoolbox.pdf)
- __Pretest__ [Network OS Administration](https://tinyurl.com/network-os-pretest)

### __Activity 1.1__: Linux Installation

1. Install Linux
- download the iso file of [Linux Ubuntu Live Server AMD64 ](http://mirrors.bangmod.cloud/ubuntu-release/18.04.2/ubuntu-18.04.2-live-server-amd64.iso)
- download and install virtualbox [link](https://www.virtualbox.org/wiki/Downloads)
- If your labtop have any virtual machine application such as VMWare, Hyper-V, or parallall desktop, you can use their applications.
2. Create virtual machine with their specification: [Youtube](https://youtu.be/3gvuz9tD85c?t=35)
- 1024GB RAM, 
- 16 GB Disk as dynamic growth
- 2 NIC cards: attach with NAT and Host only network
3.  Install Ubuntu OS based on these information: 
- [install linux 64bit](https://youtu.be/3gvuz9tD85c?t=414)
-  optional, [install linux 64bit](https://youtu.be/3gvuz9tD85c?t=600)
- set username/password to __demo/demo__
- set hostname with your student id such as your student id is 60111111. Your sepecific your hostname as __s60111111__
- set name and other information with your infomation
- finally reboot and login with __username/password__

### __Activity 1.2__ : Linux Command

1. User/Admin Linux Command   
- login via console with username/password (__demo/demo__)
- check ip address with any command : to find 192.168.56.101 or other IP address
    ``` shell 
    $ ifconfig
    $ ip a 
    ````
- start putty.exe and select ssh or assign IP address 192.168.56.101 port 22
- Let write down the linux command and its parameter and arguments in file named __activity-1.2.txt__:
    + Find the present Directory
    + Write the / directory structure
    + Write a few commands available in /bin and /sbin directory
    + Find the demo directory
    + Write the permissions of demo directory
    + Create a new Directory test in demo directory
    + Write the permissions of test directory
    + Copy the file /etc/resolv.conf in test directory
    + Rename the test directory to testing
    + Delete the testing directory
    + Change the permissions of guest directory to 775
    + Change the permissions of /tmp directory to 700
    + chane to root permission user
    + Change the permissions of guest directory to 700
    + The location of kernel files in Unix File System is /boot and by looking at the kernel file, write the kernel version you are using in your system.
    + Change directory to /
    + List the contents of /home directory
    + Find the group to which demo belongs
    + Create a file sidbi in the home area of demo (hint: use touch command)
    + Find the permissions of the file sidbi
    + Find the inode number of file sidbi (hint: ls –li)
    + Copy the file sidbi to sidbi1
    + Find the inode number of file sidbi1 (hint: ls –li)
    + Move the file sidbi to sidbi2
    + Find the inode number of file sidbi2 (hint: ls –li)
    + Move sidbi2 to sidbi
    + Login as root
    + Create a new user guest1 with same group as guest  
    + Create a new user guest2 with a different group than the group of guest  
    + Find, what permissions should the file sidbi have, so that both guest1 and guest2 can write into this file.

More information of this workshop, your can follow this clip [youtube](https://youtu.be/SYwuwlWauJI)
