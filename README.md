## Ex.3 Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands

# NAME :GOPIKRISHNAN M 
# REGNO:212223043001


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
Allocate Memory:
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

<img width="927" height="497" alt="image" src="https://github.com/user-attachments/assets/53e6af3c-da82-4b69-b855-f9e2861eace3" />

# Snapshot 2: Kali Running in Virtual image

<img width="935" height="573" alt="image" src="https://github.com/user-attachments/assets/a64b7cf9-97fe-4f1a-9e0b-398501a42359" />

# Result:
Thus, Kali Linux guest OS was installed and configured successfully.

# 3.c) Execution of Linux Commands in Kali
# About Linux:
Open-source operating system.
Kernel manages communication between hardware and software.
Commands are case-sensitive.

# Commands:

# 1) ls Command
The ls command is used to display a list of content of a directory.

Syntax: is

<img width="855" height="68" alt="image" src="https://github.com/user-attachments/assets/5443c261-954a-4e19-a97c-fbf298f39fb9" />

# 2) pwd Command
The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="250" height="67" alt="image" src="https://github.com/user-attachments/assets/7f4d58f9-98d4-49b0-8725-40c51b475468" />

# 3) mkdir Command
The mkdir command is used to create a new directory under any directory.

Syntax: mkdir

<img width="930" height="116" alt="image" src="https://github.com/user-attachments/assets/4fa3e730-ff60-4583-ae20-5825bba3d1db" />

# 4) rmdir Command
The rmdir command is used to delete a directory.

Syntax: rmdir

<img width="888" height="127" alt="image" src="https://github.com/user-attachments/assets/7f403a97-9856-4583-aef9-2ebe3c7b3655" />

# 5) cd Command
The cd command is used to change the current directory.

Syntax: cd

<img width="354" height="158" alt="image" src="https://github.com/user-attachments/assets/9132c533-534a-48ea-aa9f-72fd7fdab6ed" />

# 6) cat Command
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="350" height="183" alt="image" src="https://github.com/user-attachments/assets/c1f48b0f-8418-4493-8dfb-7a46684b9ce1" />

# 7) cp Command
The cp command is used to copy a file or directory.

Syntax: cp
<img width="334" height="133" alt="image" src="https://github.com/user-attachments/assets/e35b3f0e-c4db-4139-a5dc-6b21eb44fea4" />


# 8) gedit Command
The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="501" height="40" alt="image" src="https://github.com/user-attachments/assets/49462a59-0475-4a13-9598-8e259b32cc15" />

# 9) su Command
The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su
<img width="296" height="88" alt="image" src="https://github.com/user-attachments/assets/05e1b2c4-e686-4af8-86e5-874fa45c59b8" />


# 10) mv Command
The mv command is used to move a file or a directory form one location to another location.

Syntax: mv
<img width="363" height="265" alt="image" src="https://github.com/user-attachments/assets/94fbd23d-54c0-4e73-9304-91e24042d6da" />


# 11) rename Command
The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
<img width="462" height="171" alt="image" src="https://github.com/user-attachments/assets/00b2b162-f3b9-4646-80ab-abefc0d379ab" />


# 12) head Command
The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head

<img width="394" height="528" alt="image" src="https://github.com/user-attachments/assets/eab4d0ea-4c65-428e-afff-53d2f3efd055" />

# 13) tail Command
The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail

<img width="299" height="238" alt="image" src="https://github.com/user-attachments/assets/48211032-dcec-440e-a8a3-bf51960619a5" />

# 14) id Command
The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="931" height="48" alt="image" src="https://github.com/user-attachments/assets/d683221e-3f9f-4b60-b891-7f024a73e835" />


# 15) grep Command
The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep

<img width="349" height="74" alt="image" src="https://github.com/user-attachments/assets/50f45e6b-9612-43c1-8f99-7a3cfa4b01af" />


16) tr Command
The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="465" height="299" alt="image" src="https://github.com/user-attachments/assets/a147754e-a8a4-48ed-a1fd-01f6d8809168" />


# 17) chmod Command
The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<file_name>

<img width="450" height="118" alt="image" src="https://github.com/user-attachments/assets/15041ae4-41f7-4926-a3f6-32859f22a48c" />


# 18) tar Command
The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved] $ tar xvzf file.tar *.c

<img width="369" height="159" alt="image" src="https://github.com/user-attachments/assets/482431b5-9776-4883-8a3a-54e09e7e9e7e" />

# 19) chown Command
The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="472" height="132" alt="image" src="https://github.com/user-attachments/assets/dbd7763e-ac50-42ae-8f9a-ceb9c91c9249" />

# 20) make Command
The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="233" height="67" alt="image" src="https://github.com/user-attachments/assets/7862900e-1722-47a6-9951-3bf49119dafc" />

# 21) ifconfig Command
The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="861" height="104" alt="image" src="https://github.com/user-attachments/assets/f374feef-f393-4db1-9299-ca2a7962022d" />


# 22) chmod 777 Command
The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name $chmod -R 777 /path/to/file/or/folder

<img width="493" height="118" alt="image" src="https://github.com/user-attachments/assets/60ed7678-9bcc-4f5d-9fc8-53accf5a88b0" />

# 23) host Command
The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host or

<img width="605" height="101" alt="image" src="https://github.com/user-attachments/assets/607c3704-d9cb-4e8c-9855-b3302ab36d7b" />

# 24) gzip Command
The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip ..

<img width="926" height="148" alt="image" src="https://github.com/user-attachments/assets/c00796f4-91a9-4f08-8954-0705ed587717" />

# 25) sort Command
The sort command is used to sort files in alphabetical order.

Syntax:sort

<img width="246" height="303" alt="image" src="https://github.com/user-attachments/assets/1c93a877-a984-4f5f-a905-737dbd588f99" />



# 26) cal Command
The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="515" height="294" alt="image" src="https://github.com/user-attachments/assets/ac55c8a1-fe62-473c-a123-2cad4d0de1ec" />


# 27) clear Command
Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="1920" height="1165" alt="image" src="https://github.com/user-attachments/assets/88afa94b-cf2b-4414-a595-c8f8661a72a4" />
<img width="1920" height="1165" alt="image" src="https://github.com/user-attachments/assets/ededf1de-11c6-408d-b113-be4400c4309f" />


# 28) mail Command
The mail command is used to send emails from the command line.

Syntax: mail -s "Subject"

<img width="743" height="67" alt="image" src="https://github.com/user-attachments/assets/9f8b9532-6f30-4ffb-81d6-ea0e81604fa7" />

# 29) df Command
The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="930" height="298" alt="image" src="https://github.com/user-attachments/assets/fc201712-c883-4579-8048-7bc2b3045845" />

# 30) find Command
The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="293" height="85" alt="image" src="https://github.com/user-attachments/assets/730bd67a-0a54-47a0-ba68-354619ebb19b" /> 


Result:
Thus, the execution of various Linux commands is executed successfully using Kali Linux.

