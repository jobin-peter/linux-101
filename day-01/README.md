# Introdution to Operating Systems:

An Operating System (OS) is a software that acts as an interface between computer hardware components and the user. All other programs on a computer requires atleast  an operating system installed as a prerequisite. Applications like Web Browsers, Webex, VSCode, Games, etc., need some environment to run and perform its tasks.

In this article, we will dive into below mentioned topics based on Operating System. 

    1. What is an Operating System ? 
    2. Operating System types.
    4. Functions and Features of Operating System.
    5. What is a Kernel and its Types. 
    6. Difference between Firmware and an Operating System.
 
------

## 1. What is an Operating System ?

An Operating System (OS) is an interface between a user and computer hardware. An operating system is a software which performs all the basic tasks like file management, memory management, process management, handling input and output, and controlling peripheral devices such as disk drives,monitors,printers etc.

An operating system is software that enables applications to interact with a computer's hardware. Kernel is a set of softwares that are the core components of an OS.

The Main purpose of an Operating System is to enable applications (softwares) to interact with a computer's hardware and to manage a system's hardware and software resources.

Most popular Operating Systems are Linux Operating System, Windows Operating System, etc. In Modern Era, almost all devices which we use today functions with the help of Operating systems.

## 2. Operating System types.


<details><summary>1.Batch Operating System</summary>
    
    In Batch Operating System, the job preparations are fully manual as there is no direct interaction between user and computer. User will prepare Jobs and save into punch card or magnetic tape and will hand it over to computer operator. The Operator will sort the jobs and create batches like B1,B2 with similar types of jobs and provides to CPU to execute the batch jobs one by one. Output will be provided to the user by Operator after the execution.
</details>
    
<details><summary>2.Time-Sharing Operating System</summary>
    It is a logical extension of multiprogramming through which users can run multiple tasks concurrently. CPU time will be shared betweeen many user processes. 
</details>

<details><summary>3.Embedded Operating System</summary>
    Embedded Operating System are designed to work on dedicated devices like ATMs, IOT Devices etc.  
</details>

<details><summary>4.Multiprogramming Operating System</summary>
   Multiprogramming Operating System refers to executing two or more processes simultaneously to execute the processes one after anotherby the same computer system. It improves the use of system resources thereby increasing throughput.  
</details>
<details><summary>5.Network Operating System</summary>
     These kind of operating systems will be used in a network devices like routers, switches or firewall to handle data, applications and other network resoures. These are of two types :
        a. Peer-to-peer network operating system: 
        
        The type of network operating system allows users to share files, resources between two or more computer machines using a LAN.

        b.Client-Server network operating system: 
        
        This type of OS allows the users to access resources, functions, and applications through a common server or center hub of the resources. The client workstation can access all resources that exist in the central hub of the network. Multiple clients can access and share different types of the resource over the network from different locations.
</details>

<details><summary>6.Distributed Operating System</summary>
     These type of OS are used where we have multiple independet CPU or processor communicates with each other through physically seperate computational nodes. This is an extension of Network OS. 
</details>

<details><summary>7.Multiprocessing Operating System</summary>
      Multiprocessing OS will be having two or more than CPU in a single system which will be having increased system efficiency. In a multiprocessor system, they share computer bus,clock,memory, I/O devices for the concurrent execution of process and resource management in the CPU. 
</details>

<details><summary>8.Real-Time Operating System</summary>
     These are an important type of operating system used to provide services and data processing resources for applications in which the time interval required to process & respond to input/output should be so small without any delay real-time system. Real-time OS are mainly ised in weapon systems,robots,scientific research etc. 
</details>



# 4. Functions and Features of Operating System.

 Functions of an OS may include managing processes,memory,files,I/O system and devices, security etc. 

       - Process Management
       - Memory Management
       - File Management
       - Device Management
       - I/O System Management
       - Security and User Management 
       - Networking
       - Job accounting 
# 5. What is a Kernel and its Types. 

    Kernel is the heart of an Operating system which enables the communication between software and the hardware. Kernel is the innermost part of an OS and shell is the outermost part of an OS which is attached to the terminal where user interacts. 

    There are two types of kernel:
        a. Monolithic:

            Monolithic kernel is a single code or block and provides all required services offered by an OS

        b. Microkernels:

            In this type of kernel, services are implemented in different address space. User services are stored in user address space and kernel services are stored in kernel address space thereby reducing the size of both kernel and OS.

# 6. Difference between Firmware and an Operating System.

    Firmware:

    Firmware is a program that is embedded on a chip in a hardware device which can only control a specific device. Mostly Firmwares will be encoded by the manufacture of IC so that it cannot be changed and it will be stored in non-volatile memory 

    OS:

    OS can be installed by the user and can be changed. It has to be stored on the hard drive

