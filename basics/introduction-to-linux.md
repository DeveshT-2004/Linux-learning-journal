
## What is an Operating System?
An **Operating System (OS)** is software that manages hardware and resources, while also allowing interaction with hardware to perform useful tasks.  

## Types of Operating Systems (Popular Categories)

1. **Windows OS**  
   - Developed by Microsoft  
   - User-friendly interface, widely used in personal and enterprise systems  

2. **macOS**  
   - Developed by Apple  
   - Known for stability, design, and tight integration with Apple hardware  

3. **Linux**  
   - Open-source and free  
   - Highly customizable, secure, widely used in servers, cloud, and supercomputers  

4. **Unix**  
   - One of the oldest OS families  
   - Mostly used in servers, workstations, and mainframes  

5. **Android**  
   - Linux-based OS for smartphones and tablets  
   - Most popular mobile OS  

6. **iOS**  
   - Apple’s mobile OS for iPhone and iPad  
   - Known for security and ecosystem integration  


## What is Unix?
**Unix** is a family of operating systems created in the 1960s.  

## What is Linux?
**Linux** is a family of Unix-like operating systems developed in 1991 to create a free and open-source version of Unix.  
It is based on the **Unix kernel** but available under an open-source license.  

### Features of Linux:
1. Free and Open Source  
2. Secure  
3. Multitasking  
4. Portable  

### Use Cases:
- Android OS  
- Supercomputers  
- Data Centers and Cloud Services  
- Personal Computers (PCs)  

## What is a Kernel?
The **Kernel** is the core component of an OS that enables communication between hardware and software.  

## Understanding Linux Distributions
A **Linux distribution (distro)** is a specific version of Linux that bundles the kernel with utilities, applications, and package managers.  
Distributions differ in:  
- Graphical user interfaces  
- Command support  
- Community or commercial support  

## Popular Linux Distributions
1. **Debian** (server environments)  
2. **Ubuntu** (desktop, server, and core)  
3. **Red Hat Linux** (enterprise customers)  
4. **Fedora**  
5. **Arch Linux** (customizable approach)

# Linux Architecture

## Layers in Linux systems
1. **UI** – allows user interaction through devices like keyboards and mouse.  
2. **Application tools** – includes software tools and user applications.  
3. **OS** – manages system stability, job scheduling, and file management, operating on top of the Linux Kernel.  
4. **Kernel** – responsible for memory management, process management, and hardware interaction.  
5. **Hardware** – includes the hardware components: screen, CPU, mouse, keyboard, processors, etc.  

# Linux Filesystem 📂

It is a collection of files on your machine. It includes the files that are needed to run machines and applications.  
It is a **tree-like structure** that starts with:
- **Root Directory `/`** – contains many other directories and files.  

## What is a Directory?  

A **directory** is a special type of file that contains references (links) to other files and directories.  
Think of it as a **folder** in Windows, but more powerful in Linux. 

### 📂 Following Directories come under **Root Directory `/`**

1. **`/bin`** – Contains essential binary files (programs and commands).  
2. **`/usr`** – Stores user programs, libraries, and documentation.  
3. **`/home`** – Personal working directories for each user.  
4. **`/boot`** – Contains boot loader files (vital for system startup).  
5. **`/media`** – Mount point for removable media (USBs, CDs, etc.).  
6. **`/etc`** – Configuration files for the system and applications.  
7. **`/var`** – Variable files such as logs, mail, and temporary data.  
8. **`/tmp`** – Temporary files created by applications.  
9. **`/dev`** – Device files representing hardware (e.g., disks, terminals).  
10. **`/proc`** – Virtual filesystem providing process and kernel information.  


