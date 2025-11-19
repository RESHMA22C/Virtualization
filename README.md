# Virtualization

# Name : Reshma C
# Register Number : 212223040168
# Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

# 3.a) Installation and Configuration of Oracle VirtualBox
# Aim:
To install and configure Oracle VM VirtualBox.

# Pre-requisites:
Machine with Internet access

Minimum 4 GB RAM

Sufficient storage space

# Steps:
1.Download Oracle VM VirtualBox:

Visit Oracle VirtualBox Official Site

Download installer for your OS (Windows/macOS/Linux).

2.Install Oracle VM VirtualBox (Example: Windows):

Launch Installer → Allow Changes → Click Next.

Choose Installation Options → Click Next.

Accept Network Interface Warning → Click Yes.

Click Install.

Finish Installation and Launch VirtualBox.

3.Configure VirtualBox:

Open VirtualBox.

Click New → Name VM → Select Type (Linux/Windows) and Version.

Allocate:

Minimum 2 GB RAM

Create Virtual Hard Disk (20 GB recommended).

Start Virtual Machine and provide ISO to install OS.

# Result:
Thus, Oracle VM VirtualBox was installed successfully.

# 3.b) Installation and Configuration of Kali Linux
# Aim:
To install and configure Kali Linux in Oracle VirtualBox.

# Pre-requisites:
Oracle VM VirtualBox Installed

4 GB RAM and 20 GB Storage Minimum

Kali Linux ISO image

# Steps:
1.Download Kali Linux ISO:

Visit Kali Linux Official Site

Download 64-bit ISO (Installer version).

2.Create a New Virtual Machine:

Open VirtualBox → Click New.

Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).

3.Allocate Memory:

Minimum 2 GB RAM (recommended 4 GB).

4.Create Virtual Hard Disk:

Select VDI (VirtualBox Disk Image).

Choose Dynamically allocated.

Set Disk size to 20 GB or more.

5.Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.

6.Start Installation:

Boot Virtual Machine → Choose Graphical Install.

Set Language, Region, Keyboard.

Configure Network → Set Hostname (e.g., kali).

Set root password.

Disk Partitioning: Use entire disk → All files in one partition.

Install System → Install GRUB Bootloader → Finish Installation.

7.Login to Kali Linux:

Use root credentials.

8.(Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Kali.

# Snapshots:
AWS Account Creation Snapshot

# Snapshot 1: Installing Oracle VirtualBox image

<img width="927" height="497" alt="image" src="https://github.com/user-attachments/assets/4448c3e3-274f-498d-98c0-6d98f58e07a7" />

# Snapshot 2: Kali Running in Virtual image

<img width="935" height="573" alt="image" src="https://github.com/user-attachments/assets/1b19b982-cdbd-43e8-a0ab-89f4d0e5eb01" />


# Result:
Thus, Kali Linux guest OS was installed and configured successfully.

# 3.c) Execution of Linux Commands in Kali
# About Linux:
Open-source operating system.

Kernel manages communication between hardware and software.

Commands are case-sensitive.

# Commands:
1.ls Command
The ls command is used to display a list of content of a directory.

Syntax: ls

<img width="855" height="68" alt="image" src="https://github.com/user-attachments/assets/1a7c53b0-b084-4508-a1de-40ba7e9d8e27" />


2.pwd Command
The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="250" height="67" alt="image" src="https://github.com/user-attachments/assets/c4b14248-1646-47d1-9349-c4c51f0d7f50" />


3.mkdir Command
The mkdir command is used to create a new directory under any directory.

Syntax: mkdir


<img width="930" height="116" alt="image" src="https://github.com/user-attachments/assets/8877def3-7a65-477c-84bd-b4d72435e9e2" />

4.rmdir Command
The rmdir command is used to delete a directory.

Syntax: rmdir


<img width="888" height="127" alt="image" src="https://github.com/user-attachments/assets/0f468a10-8865-4ef6-84fc-592f4c60146c" />

5.cd Command
The cd command is used to change the current directory.

Syntax: cd

<img width="354" height="158" alt="image" src="https://github.com/user-attachments/assets/cf8aba3f-3a65-4c2d-8c77-e342110f27d2" />


6.cat Command
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..


<img width="405" height="216" alt="image" src="https://github.com/user-attachments/assets/93dd1d49-92fe-4524-a33e-c2f0ac9caebe" />

7.cp Command
The cp command is used to copy a file or directory.

Syntax: cp

<img width="394" height="160" alt="image" src="https://github.com/user-attachments/assets/f00ef61d-6303-479b-8e47-dcd03678b129" />

8.gedit Command
The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name


<img width="543" height="40" alt="image" src="https://github.com/user-attachments/assets/d70419ca-671c-4e72-a3fe-40f9eb1b8af9" />


9.su Command
The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su

<img width="351" height="108" alt="image" src="https://github.com/user-attachments/assets/013e358c-3e06-41e1-918d-5b120ff23d46" />

10.mv Command
The mv command is used to move a file or a directory form one location to another location.

Syntax: mv

<img width="439" height="312" alt="image" src="https://github.com/user-attachments/assets/3791f29d-fc65-4d15-b0c2-dc7d725e67b0" />

11.rename Command
The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="516" height="210" alt="image" src="https://github.com/user-attachments/assets/a01d7053-5c12-432b-a346-1c48acc4b8a2" />

12.head Command
The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head


<img width="475" height="651" alt="image" src="https://github.com/user-attachments/assets/6f405872-4c3f-46ca-a4d0-a5c721b7c6c8" />

13.tail Command
The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail

<img width="352" height="286" alt="image" src="https://github.com/user-attachments/assets/5759b4b1-3191-4bb9-8215-0a2823a39cf8" />

14.id Command
The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="850" height="40" alt="image" src="https://github.com/user-attachments/assets/1f250973-9a6a-4e36-a61f-07ad396b6c5e" />

15.grep Command
The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep


<img width="484" height="96" alt="image" src="https://github.com/user-attachments/assets/cc8b0dd9-71d6-41f0-8b17-d07f67b13b7c" />

16.tr Command
The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>


<img width="663" height="434" alt="image" src="https://github.com/user-attachments/assets/d0291faf-7a94-4285-82af-a72e37e3d13c" />

17.chmod Command
The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<file_name>


<img width="640" height="168" alt="image" src="https://github.com/user-attachments/assets/bb280f8d-0982-4539-b548-5f8918370d82" />

18.tar Command
The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved] $ tar xvzf file.tar *.c


<img width="490" height="222" alt="image" src="https://github.com/user-attachments/assets/ec798a34-44c1-4dac-b36d-0e1532cd37ca" />

19.chown Command
The chown command is used to change ownership.

Syntax: chown owner_name file_name


<img width="658" height="190" alt="image" src="https://github.com/user-attachments/assets/373658e5-f077-4bc9-9b4d-fbf9142b8d8c" />

20.make Command
The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….


<img width="317" height="93" alt="image" src="https://github.com/user-attachments/assets/0e61d433-83fe-466a-a34e-2508e17794bf" />

21.ifconfig Command
The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]


<img width="849" height="106" alt="image" src="https://github.com/user-attachments/assets/5e208fdc-927a-4dea-8910-a7e00d00cccb" />

22.chmod 777 Command
The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name $chmod -R 777 /path/to/file/or/folder


<img width="654" height="159" alt="image" src="https://github.com/user-attachments/assets/f3524ac3-d61c-413d-8ed3-7abc949ed6e0" />

23.host Command
The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host or

<img width="807" height="140" alt="image" src="https://github.com/user-attachments/assets/45705de7-3d14-4fee-bafe-13b942cff8aa" />

24.gzip Command
The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip ..


<img width="831" height="144" alt="image" src="https://github.com/user-attachments/assets/a33bbb5f-f291-47ec-a95d-371e0a15fa09" />

25.sort Command
The sort command is used to sort files in alphabetical order.

Syntax:sort


<img width="305" height="436" alt="image" src="https://github.com/user-attachments/assets/8cb81f50-14b4-4a84-bb80-75969521ab87" />

26.cal Command
The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="734" height="403" alt="image" src="https://github.com/user-attachments/assets/01019b0f-fe3f-4ba6-94ea-b3e6eb3954b4" />

27.clear Command
Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="247" height="159" alt="image" src="https://github.com/user-attachments/assets/56448465-0d54-4ebc-b109-12302502f962" />


<img width="159" height="81" alt="image" src="https://github.com/user-attachments/assets/1dc5998c-a044-4c96-add2-5ab81e200713" />

28.mail Command
The mail command is used to send emails from the command line.

Syntax: mail -s "Subject"


<img width="638" height="75" alt="image" src="https://github.com/user-attachments/assets/59760473-5749-434d-a998-98d78a812b97" />

29.df Command
The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df


<img width="847" height="287" alt="image" src="https://github.com/user-attachments/assets/47b587d2-b10a-4c49-a255-bc3bb88631ad" />


30.find Command
The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="417" height="118" alt="image" src="https://github.com/user-attachments/assets/fb1ad0ee-367f-4579-a44c-b6b4f0349277" />


<img width="458" height="94" alt="image" src="https://github.com/user-attachments/assets/a3028ae9-f165-4cd8-8f97-b6e6773637a6" />


# Result:
Thus, the execution of various Linux commands is executed successfully using Kali Linux.
