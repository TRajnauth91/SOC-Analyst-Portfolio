# Computer Fundamental Notes

## CPU (Central Processing Unit)
The CPU is commonly known as the "Brains" of a computer. It's where the computer runs programs and processes data. Absolutely central to a computers function.

## GPU (Graphics Processing Unit)
The GPU is very similar to the CPU. A more recent creation in the computer world, it was created to handle the complex processes of showing graphics on a screen. It operates faster than a CPU and is becoming increasingly more interesting to scientists as a faster way to compute information. Things like Mining bitcoin and complex weather problems.

## RAM (Random Access Memory)
The RAM is commonly referred to as the "short-term memory" of the computer. It temporarily stores information and loses it when the computer turns off. Its like a temporary drop box the CPU can hold information in while performing tasks. Like when you're in a conversation with someone, and you think of a couple talking points or questions, you ask the first one, and hang on to the other 2 for a couple minutes, then mention the second point, talk about that, and so on. It's known as random because the CPU can think about anything stored in memory anytime it wants. Typically one of the most expensive parts of a computer. 

## Memory/Storage (HDD,SSD)
The Memory or storage is where information is stored that doesn't require the computer to be on. It's stored in a place that the computer can access when it turns back on, unlike RAM storage which wipes when there's no power. While there are many ways storage works, there are two main types of storage being Magnetic and Digital. Early computers used magnetic tape to store data, much like a recording tape, the main disadvantage this had was the fact that the computer couldn't randomly access any bit of this. They had to fast forward and rewind to get to the place they needed (Very slow and tedious). Then came Hard Disk Drives (HDD), which used spinning disks with an arm and a head to read and write directly off the discs like a record player, using little magnets similar to the magnetic tape. More recently, Solid-State drives have become increasingly more common. They store data on small circuits, have no moving parts, are physically smaller than HDDs, are being made to have more and more storage year after year, while also tending to use less power.

## Network Adapter
The Network Adapter is the part of the computer that allows it to communicate to other computers on the same network. Local networks (like your home) also need a network adapter to allow the computers on them to talk to each other. And then to talk to the larger Network from your Internet Service Provider. Because of this, a piece of hardware called the Modem is used and can be found in mobile phones as well as the kind of computer your ISP gives you to connect to the internet. So when you type in the name and password to connect to Wi-Fi, you connect to their network via the network adapter in your phone. The Wi-Fi then talks to the modem, and the modem talks to the internet. Because your phone has a network adapter and modem, when you use data, it only uses the modem to connect to your phone companies cell network.

## Motherboard
The Motherboard is commonly known as the "Central Nervous System" of the computer. It was what allows and is physically connecting every piece of hardware in the machine to talk to each other. Commonly connected to things like, a Processor socket (where the CPU goes), a Chipset (Controls how the CPU, memory, and other devices interact), RAM slots (where the RAM is put in), PCIe (dedicated hardware for GPUs, sound cards, and high speed storage), storage connectors (SATA ports or M.2 slots used to connect HDDs and SSDs), and BIOS/UEFI chip (a small memory chip that essentially handles the boot up sequence for your hardware before giving control to the operating system).

## Bits and Bytes
A Bit is a shortened version of Binary Digit. We know all computer functions read and process in bits (Either 1 or 0). Using American Standard Code for Information Interchange (ASCII) your computer groups these bits into 8 digit formats called Bytes, and can read and understand complex strings of these 1s and 0s, then correlate them into letters, numbers, and special characters. For example: Capital letter A in ASCII would look like 01000001.

## MAC (Your computer device ID)
MAC stands for Media Access Control. It is a 12 digit ID for your hardware, every computer has one, this is how your phone is distinguishable from your laptop, and is unique identifying characters that can't be shared between multiple computers. For example,  "00:1A:2B:3C:4D:5E"

## Signal Transmission
Once data is transformed into bits, it must travel across a physical media and has 3 different ways in which it can move across a network. 
Electrical signals - Represents data as electrical pulses along a copper wire
Optical signals - Converts electrical signals into pulses of light
Wireless signals - Uses infrared, microwave, and radio waves 

## Operating System (OS)
The Operating System is the software platform that manages everything in the computer. Without it, software developers would have to write custom code to interact with every different brand of graphics cards or hard drives. The Kernel is the absolute core of an OS, it remains in RAM the entire time, managing system memory, and scheduling CPU usage. The OS manages every byte of RAM and allocates memory blocks to applications when they launch, and then take it away when they close. The OS also dictates how data is structurally stored on drives. Device Drivers are small specialized software files that teach the OS how to interact with hardware devices. 

## Files and Folders
The files in a device can be thought of as the way things are stored in a computer. We know everything is stored as 1s and 0s, but the OS identifies how to handle files using their file extension (.jpeg, .txt, .exe), and using that data, the OS knows which application to run in order to read and give output from that files binary format. Folders are special index files maintained by the file system, which gives a list of pointers to where specific files exist on the storage drive. The Hierarchical structure of storage in a computer is as follows: Root directory > Folders > Files

## Applications
An Application is simply compiled software the User can use to execute tasks. They rely on Application Program Interfaces (APIs) provided by the operating system, like when a game wants to save a file, instead of going to the hard drive, it just calls on the OS's file-saving API. Apps present information using either Graphical User Interface (GUI), with nice buttons and menus the User can interact with, or a Command Line Interface (CLI), which is just text commands. 

## Processes 
A process is an active execution environment from code sitting on a hard drive. Every process is allowed its own memory space (So if it crashes it doesn't take down the rest of the OS) dictated by the OS, and is assigned a Process ID (PID) as well as a priority level. Worth noting that a single process can spawn multiple "threads" that are smaller sub tasks running with the main task to maximize resources in multi-core CPUs, this is called Multithreading.

## Services
A Service is a process that runs quietly in the background, they don't have user interfaces and usually launch before the user even logs in. Examples include network connectivity handlers, security scanners, and print spoolers.

## Users and Permissions
A user is the person using the computer, OSs are fundamentally multi-user systems designed to protect data from unauthorized access.
User accounts (User profiles associated with a User ID (UID)) are usually split into 2 categories. Standard Users with limited environments, and Administrators/Root with full unrestricted access across the system. Access Control Lists (ACLs) are the matrix of permissions assigned to files and folders in a system and are typically managed by 3 primary actions. Read (r) : Permission to read the contents of a file or the list of files in a folder. Write (w) : Permission to modify or delete a file, or add/delete a file in a folder. Execute (e) : Permission to run a file as a program or a script. 

## Hardware vs Software
Hardware is the physical component of a computer. Using physics, electricity, and silicon it provides the raw computing potential need to run software.

Software is the binary instructions that are stored digitally. The software dictates how electricity flows through the hardware in order to perform logic.

## OS vs Applications
The OS is what governs and provides the infrastructure needed to run applications. 
Applications follow the guidelines set by the OS and allow them to work independently from other apps.
(IOS,MacOS,Windows,Andriod)

## Virtual Machine (VM)
A Virtutal Machine uses software to "trick" an operating system into thinking its function on physical hardware. A Hypervisor is the software layer that manages the VM, and slices up your physical CPU, RAM, and storage, to which it presents to a virtualized version of another OS (providing complete isolation, making them fantastic for testing malware, setting up servers, and running old software. They come in 2 types. Bare-Metal which runs directly on the physical hardware, and Hosted, which runs as an application inside an existing OS.












