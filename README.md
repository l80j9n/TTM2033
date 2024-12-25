java c
TTM2033
TECHNOLOGY PLATFORM
SEMESTER 3 2023/2024
LAB 2LAB # 2Introduction to BIOS and LINUX Environment
OBJECTIVS:
1.   Understanding of BIOS
2.   Understanding of LINUX
3.   Installation of LINUX (UBUNTU) on VIRTUAL BOX
4.   Introduction to UBUNTU Platform
5.   Learning Basic Commands
** Evaluation: This lab 1 and Lab 2 material will be tested in Lab Test 1.
1.   Understanding of BIOS
A.   What is BIOS?
BIOS is the first software that runs when you power on your system, performing an initial pack of diagnostic tests (POST, or Power On Self-Test) to see if there are any issues with the hardware. POST is the first step in your hardware’s boot sequence. The machine won't continue with the boot sequence if the POST fails.
BIOS is firmware (in other words, software embedded in a piece of hardware) stored on a ROM chip that lets you access and set up your system at its most basic level.
B.   What is a BIOS and What’s Included?
A BIOS contains the instructions your computer needs to load its basic hardware, including the POST mentioned above. If your system fails the POST, you will hear a series of beeps; different beep sequences indicate various issues.
BIOS firmware is non-volatile, meaning that the settings are saved and can be recovered even if the machine no longer has power.
C.   What are the types of BIOS
Legacy BIOS: Legacy BIOS is used in older motherboards to turn on the computer, and it controls how the CPU and different computer components talk to each other. Unfortunately, the Legacy BIOS has limitations. For example, it can’t handle or recognize data drives larger than 2.1 TB.
UEFI: The acronym stands for Unified Extensible Firmware Interface. Unlike the Legacy BIOS, the UEFI can accommodate 2.2 TB or larger drives. In addition, UEFI handles drives with the aid of the Master Boot Record rather than GPT technology.
D.   How do you introduce a BIOS?
In order to access BIOS on a Windows PC, you must press your BIOS key set by your manufacturer which could be F10, F2, F12, F1, or DEL.      Task 1:From BIOS, show (take picture) the details for following components:a)   Processorb)   Hard drivec)   Graphic cardd)   RAMe)   Power supply/ Batteriesf)   Network Interfaceg)   PC temperatureh)   Boot devices2.   Understanding of LINUX
A.   What is Linux OS used for?
Linux is used in the following ways: Server OS for web servers, database servers, file servers, email servers and any other type of shared server. Designed to support high-volume and multithreading applications, Linux is well-suited for all types of server applications.
B.   What is different Linux OS?
Common Linux distributions include Ubuntu, Debian, and Fedora. A few other types of Linux are based on Debian or Red Hat and are designed to perform. specific functions based on a user's needs.
   
Task 2:a)   What are the advantages and disadvantages of Linux? (at least 3)b)   Where is Linux mostly used?c)   Why is Linux faster than Windows?d)   What is the difference between Linux, Windows and Mac? (at least 3)
3.   Introduction to UBUNTU Platform
To print screen in Linux:
·   PrtSc   –   Save a screenshot of the entire screen to the "Pictures" directory.
·   Shift + PrtSc   –   Save a screenshot of a specific region to Pictures.
·   Alt + PrtSc    –   Save a screenshot of the current window to Pictures.
·   Ctrl + PrtSc   –   Copy the screenshot of the entire screen to the clipboard.
·   Shift + Ctrl + PrtSc   –   Copy the screenshot of a specific region to the clipboard
·   Ctrl + Alt + PrtSc   –   Copy the screenshot of the current window to the clipboard.
Shell in LinuxA shell is a program that allows you to interact within a terminal window. Shell is a UNIX term for the interactive user interface with an operating system. The shell is the layer of programming that understands and executes the commands a user enters.
1. Shell :A shell is an environment or a special user program which provide an interface to user to use operating system services. It executes programs based on the input provided by the user.2. Kernel :Kernel is the heart and core of an Operating System that manages operations of computer and hardware. It acts as a bridge between the user and the resources of the system by accessing various computer resources like the CPU, I/O devices and other resources.
Task 3:There are three (3) ways to open a terminal;a.   Click on the icon at the bottom left of the screen, then type Terminal" in the search   toolbar.a.   Ctrl+Alt+Tb.   Search" Terminal" in search   toolbarc.   Right-click on Desktop, then choose 'Open   terminal'b.   Type the following code. Write your observation   below:$ whoami -(is used to display the username of the currently logged-in user)$ clear-(is used to clear the terminal screen, removing all previous command output and text from view)$ ip addr show -(is used to display detailed information about the network interfaces and their IP addresses on your system)-"lo" is the loopback interface used for local communication within the same device, and "enp0s3" is a typical Ethernet network interface used for external network communication.
·   man : system reference manuals
-   It is used to display the manual pages (documentation) for various commands and utilities installed on your system.
-   It provides detailed information about how to use a specific command, its options, and its functionality.   Observations (Show the output)$ whoami$ clear$ ip addr show$ man whoami
THE DETAILED EXPLANATION OF “ip addr show” COMMAND RESULT IS SHOWN IN APPENDEX A
Lea代 写TTM2033 TECHNOLOGY PLATFORM SEMESTER 3 2023/2024 LAB 2
代做程序编程语言rning basic commands
Linux FilesystemLike other modern operating systems, Linux organizes files in a hierarchical tree of directories. The directory at the top of the tree is called the root directory (/). The directories shown directly beneath the root are typically a part of the hierarchy on all Linux file systems. User directories typically have names that identify actual users.
Root directory and home directory
It   is   also   referred   to   as   the   root   user's   home   directory   (and   not   as   the   root   directory). The root   directory   is   the   top-level   directory   on   any   Unix-like   operating   system,   i.e.,   the   directory that contains all other directories and their subdirectories. It is designated by a forward slash ( /   )Home directory - It is also the directory that a user is first in after logging into the system Ubuntu       creates a       /home/username directory for that user with their username.       The /home/username directory is often referred to as just "home   directory."A home directory, also called a login directory, is the directory on Unix-like operating systems   that serves as the repository for a user's personal files, directories, and programs. It is also the directory that a user is first in after logging into the system.   Figure 1. Linux file system structure.
Source: https://www.tecmint.com/linux-directory-structure-and-important-files-paths-explained   
·   pwd : print working directory
-   It displays the absolute path of the current working directory.
-   This is the directory in which your terminal session is currently "located."
·   cd   .. : change current directory to parent   directory
-   It is used to change the current working directory to its parent directory. It allows you to move one level up in the directory hierarchy.
-   This is useful for navigating your file system and moving between directories.   
·   cd   / : takes you back to the root   directory
-   It is used to change the current working directory to the root directory. The root directory is the top-level directory in a Unix file system, represented by the forward slash ("/").
-   Changing the working directory to the root directory effectively puts you at the very beginning of the directory hierarchy.
·   ls ( ls- I ) : list directory contents
-   It is used to list the files and directories in the current working directory.
-   It provides a convenient way to view the contents of a directory from the command line.
THE DETAILED EXPLANATION OF “ls” COMMAND RESULT IS SHOWN IN APPENDEX B
Task 4:a.   What does the pwd command's output represent with respect to the location of the   root directory in the Linux file system   hierarchy?b.   What is the result of the cd .. command represent with respect to the location of the   previous directory location in the Linux file system   hierarchy?c.   Which directory in the Linux file system does the cd / command take you   to?d.   Which directory in the Linux file system does the cd command take you   to?e.   Show the results of ls in /   folder.f.   How many files and folders are there on your   Desktop?Observations (Show the output)
Task 5:·   ping		-	Test Network Connections·   hostname 	-	Host/Domain name and IP address   
a)   ping-   It is used to test the reachability and round-trip time (latency) between your computer and a target host or network device.-It sends packets of information to the user-defined source. If the packets are received, the destination device sends packets back.Ping can be used for two purposes.1.   Network connection can be established.2.   Speed of the connection.
- If you do “ping google.com”, it will display its IP address. (Use CTRL+C to stop the test)
-When you use "ping google.com," you are pinging a host by its domain name, which in this case is "google.com."
-When you use "ping 8.8.8.8," you are pinging a host directly by its IPv4 address which in this case, "8.8.8.8").
Command·   ping ukmfolio.ukm.my
Output
   
Command·   ping 8.8.8.8
Output
   


b)   hostname·   It is used to display or set the system's hostname, which is the name assigned to a computer or device on a networkEvery host receives a hostname, often placed in a DNS name space forming the Fully Qualified Domain Name (fqdn).·   hostname	-	displays the machine host name·   hostnamectl	-	displays and control the system hostname with details
changing hostname ·   You should be at root (/)·   You should be super user to change the hostnameo   type: sudo su   [super user do]o   type: passwordo   ‘#’   represents super user·   type: hostname ‘helloworld’   (any name) [hostname will change to new name]·   check by typing: ‘hostnamectl’·   only Transient (temporarily) hostname has been changed, static (permanent) hostname still not change·   type: hostnamectl set-hostname helloworld   [static hostname will also change]·   check by typing: ‘hostnamectl’·   close and reopen the terminal to confirm the change in hostname.
Command
hostname
Output
   


Command·   Change hostname Temporary   
Output         
Command·   Change hostname permanently    
Output         
BONUS Tasks:a)   What is the difference between Shell and Kernel?   (at least 3)
b)   What is the difference between Root and Home Directory?   (at least 3)
c)   What are the different Ubuntu Desktop Environments? (at least 3)
d)   What is the difference between Ubuntu Desktop and Ubuntu Server?   (at least 3)
e)   What language is Ubuntu written in?
   

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
