 # VIRTUAL MACHINE CREATION IN LINUX
  ## AIM
       To Install Virtualbox / VMware Workstation with different flavours of linux.
## PROBLEM STATEMENT
    This experiment involves setting up a virtual machine with CentOS, a popular Linux distribution. This setup allows users to practice Linux commands, test applications, and develop software in a virtualized environment without affecting      the host system.

## ALGORITHM
 ### Steps 1:
 Open VirtualBox or VMware Workstation
 ### Steps 2:
 Go to File -> New to create a new virtual machine.
 ### Steps 3:
 Enter a name for your CentOS VM.Choose Linux as the type and CentOS as the version (or select the closest option available if CentOS is not listed).
 ### Steps 4:
 Select the CentOS ISO image you downloaded.
Set the base memory to 1024 MB (1 GB)
Allocate 1 processor core
Set the disk size to at least 20 GB
Complete the configuration by clicking Finish to create the virtual machine
 ### Steps 5:
 Select the created VM, go to Details (or Settings), and navigate to the Network tab.
Configure Adapter 1 as NAT (for internet access through the host).
Configure Adapter 2 as Bridged Adapter (for direct access to the local network, if needed).
Click OK to save network settings.
### Step 6:
Click Start to boot up the newly created virtual machine.
During installation, set a password for the root user.
After logging in to CentOS, open a terminal to start using the command line.

## COMMANDS
Switch to User:
```
su username
```
View IP Address:
```
ip a
```
Create a Directory:
```
mkdir <directory_name>
```
Change to the New Directory:
```
cd <directory_name>
```
Edit the Hostname File:
```
vi /etc/hostname
```
View the Content of the Hostname File:
```
cat /etc/hostname
```
```
REG NUMBER: 212222110021
NAME: LAVANYA M
```


## OUTPUT
![image](https://github.com/user-attachments/assets/e841fddf-9677-46a3-a779-c74d297b7a8b)
![image](https://github.com/user-attachments/assets/2df30d8f-3352-40d1-8c1e-df6f4d0e79a7)

## RESULT
Successfully installed CentOS on a virtual machine using VirtualBox or VMware, providing a fully functional CentOS environment for testing and development.
