# learnLinux

## File System Hierarchy
![NEW_filesystem](https://github.com/user-attachments/assets/b11c6225-8074-47e6-bbaf-f86aced2618a)
![image](https://github.com/user-attachments/assets/80caafe1-b035-45a5-93b9-bc8c62bd0ee2)

## Commands
ls - The most frequently used command in Linux to list directories  
pwd - Print working directory command in Linux  
cd - Linux command to navigate through directories   
mkdir - Command used to create directories in Linux    
mv - Move or rename files in Linux  
cp - Similar usage as mv but for copying files in Linux  
rm - Delete files or directories  
touch - Create blank/empty files  
ln - Create symbolic links (shortcuts) to other files  
clear - Clear the terminal display  
cat - Display file contents on the terminal  
echo - Print any text that follows the command  
less - Linux command to display paged outputs in the terminal  
man - Access manual pages for all Linux commands  
uname - Linux command to get basic information about the OS  
whoami - Get the active username   
tar - Command to extract and compress files in linux  
grep - Search for a string within an output  
head - Return the specified number of lines from the top  
tail - Return the specified number of lines from the bottom  
diff - Find the difference between two files  
cmp - Allows you to check if two files are identical  
comm - Combines the functionality of diff and cmp  
sort - Linux command to sort the content of a file while outputting  
export - Export environment variables in Linux 
zip - Zip files in Linux  
unzip - Unzip files in Linux 
ssh - Secure Shell command in Linux  
service - Linux command to start and stop services  
ps - Display active processes  
kill and killall - Kill active processes by process ID or name  
df - Display disk filesystem information  
mount - Mount file systems in Linux  
chmod - Command to change file permissions  
chown - Command for granting ownership of files or folders  
ifconfig - Display network interfaces and IP addresses  
traceroute - Trace all the network hops to reach the destination  
wget - Direct download files from the internet  
ufw - Firewall command  
iptables - Base firewall for all other firewall utilities to interface with apt, pacman, yum, rpm - Package managers depending on the distribution
sudo - Command to escalate privileges in Linux   
cal - View a command-line calendar  
alias - Create custom shortcuts for your regularly used commands  
dd - Majorly used for creating bootable USB sticks  
whereis - Locate the binary, source, and manual pages for a command  
whatis - Find what a command is used for  
top - View active processes live with their system usage   
useradd and usermod - Add a new user or change existing user data  
passwd - Create or update passwords for existing users  

## Terminal Emulators
Terminal emulation is software that emulates the function of a terminal. It allows the use of text-based programs within a graphical user interface (GUI). There are also so-called command-line interfaces (CLI) that run as additional terminals in one terminal. In short, a terminal serves as an interface to the shell interpreter.

Imagine you're in a large office building where the shell is the main server room that processes all the company's data and commands. The terminal is like a receptionist's desk that serves as a point of communication to the server room. You go to the receptionist (terminal) to deliver instructions or requests to the server room (shell).

Now, suppose you're working remotely. Terminal emulation software acts like a virtual receptionist's desk on your computer screen (the GUI), allowing you to interact with the server room without being physically present in the office. It emulates the function of the actual receptionist's desk, enabling you to use text-based programs and commands within a graphical environment.

Additionally, command-line interfaces (CLI) that run as additional terminals within one terminal are like having multiple virtual receptionist desks open on your screen simultaneously. Each one allows you to send different instructions to the server room independently, but through the same main interface. In essence, the terminal serves as your gateway to communicate with and control the core operations managed by the shell.

Terminal emulators and multiplexers are beneficial extensions for the terminal. They provide us with different methods and functions to work with the terminal, such as splitting the terminal into one window, working in multiple directories, creating different workspaces, and much more. An example of the use of such a multiplexer called Tmux could look something like this:

