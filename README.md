# **Notes & CHEATSHEET**

## TABLE OF CONTENT


1.  Markdown     :arrow_right:   [*here*](#md) 
   
2. GIT/GITHUB   :arrow_right:  [*here*](#git)
3. SSH         :arrow_right:     [*here*](#ssh) 
4. TCP/IP    :arrow_right:      [*here*](#tcp)
5. Linux system monitoring tools  :arrow_right:     [*here*](#moni)
6. Virtualization  :arrow_right: [*here*](#vir)
7. DevOps :arrow_right: [*here*](#dev)
---
<br>




## <mark> MARKDOWN</mark> :arrow_down: <a id="md"></a>


*Markdown is also the sweet spot between the simplicity of WYSIWYG editors (What You See Is What You Get)—think Google Docs or Microsoft Word—and the flexibility of HTML and CSS. It’s the best tool for anybody who wants to write for the web.* (creator John Gruber)

<br>

>The cheatsheet is split into two, basic markdown & extended

<br>


```Basics ``` 






[![markdowncheatsheet1.png](https://i.postimg.cc/j2tCKwBF/markdowncheatsheet1.png)](https://postimg.cc/5YKfS04B)

<br>

```Exented```

[![markdown-cheat-sheet-2.png](https://i.postimg.cc/yNDZrRzh/markdown-cheat-sheet-2.png)](https://postimg.cc/PLkJCPJN)



[PDFtoPNG](https://pdf2png.com)

<br>



## <mark> GIT/GIHUB </mark>    :arrow_down: <a id="git"></a>
***Git** is a free and open source distributed version control system(DVCS) designed to handle everything from small to very large projects with speed and efficiency*
 created by ```Linus Torvalds in 2005```.
 

<br>

***GitHub** is a website and cloud-based service that helps developers store and manage their code, as well as track and control changes to their code.*

> Version control helps developers track and manage changes to a software project’s code. As a software project grows, version control becomes essential.

<br>


[git-cheat-sheet-education-1.png](https://i.postimg.cc/yNwWzT8T/git-cheat-sheet-education-1.png)](https://postimg.cc/wtQ9XLJt)


[![git-cheat-sheet-education-2.png](https://i.postimg.cc/jjNtyYRz/git-cheat-sheet-education-2.png)](https://postimg.cc/QBX2rP9t)




[source](https://education.github.com)

<br>


## <mark>**SSH**</mark> :arrow_down: <a id="ssh"></a>

*Secure Shell, sometimes referred to as Secure Socket Shell, is a protocol which allows you to connect securely to a remote computer or a server by using a text-based interface.
*The two protocols use the client and server applications to establish a remote connection.*

 > - Secure Shell (SSH) for Linux-based machines
 > - Remote Desktop Protocol (RDP) for Windows-based machines

<br>

 [![ssh-cheat-sheet-common-commands-and-secure-config-1.png](https://i.postimg.cc/ZYd9cnLd/ssh-cheat-sheet-common-commands-and-secure-config-1.png)](https://postimg.cc/9zcFXWKm)

 <br>

 ## <mark>**TCP/IP**</mark> <a id="tcp"></a>

 TCP:

    TCP/IP stands for Transmission Control Protocol/ Internet Protocol. It is specifically designed as a model to offer highly reliable and end-to-end byte stream over an unreliable internetwork.

    OSI:
    The Open System Interconnection (OSI Model) also defines a logical network and effectively describes computer packet transfer by using various layers of protocols.  
  
 <br/>
 
 ## The differences between the OSI and TCP/IP model


  <mark> *OSI model* : </mark>
- has been developed by ISO (International Standard Organization).
  
- In the OSI model, the transport layer provides a guarantee for the delivery of the packets.
- This model is based on a vertical approach.
- It consists of 7 layers.
- The usage of this model is very low.
- It provides standardization to the devices like router, motherboard, switches, and other hardware devices.
  
  

<mark> *TCP/IP* </mark>

  - It was developed by ARPANET (Advanced Research Project Agency Network).
  - The transport layer does not provide the surety for the delivery of packets. But still, we can say that it is a reliable model.
  - This model is based on a horizontal approach.
  - It consists of 4 layers.
  - This model is highly used.
  - It does not provide the standardization to the devices. It provides a connection between various computers


🔨 Build and packaging tools






![img](https://fiberbit.com.tw/wp-content/uploads/2013/12/TCP-IP-model-vs-OSI-model.png)



<br/>

## What is TCP Three-Way HandShake?

- TCP 3-way handshake or three-way handshake or TCP 3-way handshake is a process which is used in a TCP/IP network to make a connection between server and client.
- Syn use to initiate and establish a connection
- ACK helps to confirm to the other side that it has received the SYN.
- SYN-ACK is a SYN message from local device and ACK of the earlier packet.
- FIN is used for terminating a connection.
- TCP handshake process, a client needs to initiate the - conversation by requesting a communication session with the Server
- In the first step, the client establishes a connection with a server
- In this second step, the server responds to the client request with SYN-ACK signal set
- In this final step, the client acknowledges the response of the Server
- TCP automatically terminates the connection between two separate endpoints.

![i.e](https://www.guru99.com/images/1/092119_0753_TCP3WayHand1.png)


<br/>

![i.e](https://f002.backblazeb2.com/b2api/v1/b2_download_file_by_id?fileId=4_za8a2358db1d7f91b68b30916_f109804476cef7824_d20190911_m064720_c002_v0001127_t0001)

<br/>

## What's  the " 4 way- disconnect"

- The client sends a request to stop the TCP connection request
- The server closes this socket after receiving the request
- The server sends a reverse request, requesting the client to close the socket connection
- The client confirms the server request and closes the socket connection.
  
  ![img](https://i.stack.imgur.com/JjMcf.png)




 ## Sequence and Acknowledgment Numbers
The client on either side of a TCP session maintains a <mark>32-bit </mark> sequence number it uses to keep track of how much data it has sent. This sequence number is included on each transmitted packet, and acknowledged by the opposite host as an acknowledgement number to inform the sending host that the transmitted data was received successfully.

When a host initiates a TCP session, its initial sequence number is effectively random; it may be any value between 0 and 4,294,967,295, inclusive. However, protocol analyzers like Wireshark will typically display relative sequence and acknowledgement numbers in place of the actual values. These numbers are relative to the initial sequence number of that stream. This is handy, as it is much easier to keep track of relatively small, predictable numbers rather than the actual numbers sent on the wire.


## Difference between TCP and UDP ?
    What is UDP?
UDP is a Datagram oriented protocol. It is used for broadcast and multicast type of network transmission. The full form of UDP is User Datagram Protocol (A datagram is a transfer unit associated with a packet-switched network<sup>1</sup>


<sup>1 </sup>*packet switching is a method of grouping data into packets that are transmitted over a digital network. Packets are made of a header and a payload*


|TCP	   UDP 

 
It is a connection-oriented protocol.

| TCP  	|  UDP 	|   	|   	| 	|
|---	|---	|---	|---	|---	|
| It is a connection-oriented protocol.|It is a connectionless protocol.
 TCP reads data as streams of bytes, and the message is transmitted to segment boundaries. | UDP messages contain packets that were sent one by one. It also checks for integrity at the arrival time.
 TCP messages make their way across the internet from one computer to another.|It is not connection-based, so one program can send lots of packets to another.
 TCP rearranges data packets in the specific order.  | UDP protocol has no fixed order because all packets are independent of each other  
|The speed for TCP is slower.   	| UDP is faster as error recovery is not attempted.  	|   	  	
|Header size is 20 bytes	| Header size is 8 bytes.  	|   	   	 	
|CP does error checking and also makes error recovery.   	|UDP performs error checking, but it discards erroneous packets.   	  	   	
| Using handshake protocol like SYN, SYN-ACK, ACK 	|No handshake    	
|TCP is reliable as it guarantees delivery of data to the destination router.  |The delivery of data to the destination can’t be guaranteed in UDP.   

<br>
[GURU99](https://www.guru99.com/tcp-vs-udp-understanding-the-difference.html)

<br/> 



## Classification of port numbers
<br>

The port numbers are divided into <mark>three categories:

    Well-known ports
    Registered ports
    Dynamic ports

<br>

## Well-known ports

The range of well-known port is <mark>0 to 1023.

    20 - FTP
    22 - SSH
    80 - HTTP
    443 - HTTPS

## Registered ports

The range of registered port is <mark>1024 to 49151</mark>. The registered ports are used for the user processes. These processes are individual applications rather than the common applications that have a well-known port.


## Dynamic ports

The range of dynamic port is <mark>49152 to 65535.</mark> Another name of the dynamic port is ephemeral ports. 

 ### *IANA : Internet Assigned Numbers Autorithy

*is a standards organization that oversees global IP address allocation, autonomous system number allocation, root zone management in the Domain Name System, media types, and other Internet Protocol-related symbols and Internet numbers.*

<br/>

## How the TCP/IP Protocols Handle Data Communications
<br>
When a user issues a command that uses a TCP/IP application layer protocol, a series of events is initiated. The user's command or message passes through the TCP/IP protocol stack on the local system. Then, the command or message passes across the network media to the protocols on the remote system. The protocols at each layer on the sending host add information to the original data.

![img](https://docs.oracle.com/cd/E18752_01/html/816-4554/figures/ipov.fig88.png)

<br>

# IPv4 Addresses and Structure

IPv4 uses 32 bits for addressing. The 32 bits are split into 4 bytes and each byte is separated by a dot(.)

Where the value  is between 0-255 decimal. A typical IP address appears like this:

            192.168.0.1

## IP4 Address Classes

The address classes divide the address space into addresses that support:

Large numbers of nodes – Intended for a large organisation – Class A addresses
Medium number of nodes- Class B addresses
Small number of nodes- Intended for a small organisation –Class C addresses

![img](https://miro.medium.com/max/1400/1*wbYRk65-lnwsWYSFJ656xw.png)

**127.0.0.1** is commonly known as the loopback address, and is used for testing the local IP address stack. A packet addressed to 127.0.0.1 is not sent onto the network but only the IP software stack.

*Classless Inter-Domain Routing (CIDR)**

# What is a subnet?

There are millions of networks around the world, and they all vary in size. However, the larger a network is, the harder it is to manage and maintain. When a network is divided into smaller pieces, those pieces are called subnets. A subnet is a small network.

## Subnetting is beneficial in many ways:

    - Easier maintenance;
    - Advanced network security so that one subnet can’t access the other one;
    - Reduced network traffic;
    - When you can subnet your network, you don’t need to acquire additional IP addresses from ISPs (internet service providers).
    - However, subnetting often requires additional hardware such as routers, so it also comes with a cost.

![img](https://nordvpn.com/wp-content/uploads/2020/11/subnet-infographic.jpg)

For example, consider the IP address 207.61.16.119 and the subnet mask 255.255.255.0. Converting these two numbers to binary and ANDing them gives the host’s Network ID:

    Host = 11001111 00111101 00010000 01110111
    Mask = 11111111 11111111 11111111 00000000
    AND = 11001111 00111101 00010000 00000000
        = 207.61.16.0 = network ID
        <br/>

Taking the logical NOT of the subnet mask and ANDing it with the host’s IP address gives the host’s Host ID:

    Host = 11001111 00111101 00010000 01110111
NOT Mask = 00000000 00000000 00000000 11111111
     AND = 00000000 00000000 00000000 01110111
         = 0.0.0.119 = host ID

[vidéo 1](https://youtu.be/0d1CFWXGYbA)






## **Linux System Monitoring Tools**<a id="moni"></a>

1. top: It allows you  to see through all your system, all the processes.  **NOTE** : *B-*
     

2. Htop: pro's much more clearer than "*top*" command ( with colors) with  filters ( apt install) **NOTE** :A

3. glances : cross plateform - much infos more than htop       ( apt install) **NOTE** : A+

4. Whowatch : list of logos & more **NOTE**  A+

5. bpytop : “bpytop” tool is also one such tool. Its functionality  is very much similar 
            to  “top” and “Htop" (python3 install)





 ## **Storage Space Utilization**

There are 2 well-known commands in Linux that are used to inspect storage space usage:

    # df 
    # du

The first one, df (which stands for disk free), is typically used to report overall disk space usage by file system.

    Example 1: Reporting disk space usage in bytes and human-readable format
    # df
    # df -h

    Without options, "*df*" reports disk space usage in bytes. With the -h flag it will display the same information using MB or GB instead. Note that this report also includes the total size of each file system (in 1-K blocks), the free and available spaces, and the mount point of each storage device.


    Example 2: Inspecting *inode usage by file system in        human-readable  
    # df -hTi

**The inode (index node) is a data structure in a Unix-style file system that describes a file-system object such as a file or a directory. Each inode stores the attributes and disk block locations of the object's data.*

Example 3: Finding and / or deleting empty files and directories

     to find empty files or directories:
        # find  /home -type f -empty
        # find  /home -type d -empty
Also, you can add the -delete flag at the end of each command if you also want to delete those empty files and directories:

    # find  /home -type f -empty --delete
    # find  /home -type f -empty

    Example 4: Examining disk usage by directory




    # du -sch /home/*


 




## **Memory and CPU Utilization**


The classic tool in Linux that is used to perform an overall check of CPU / memory utilization and process management is "top" command. In addition, top displays a real-time view of a running system. There other tools that could be used for the same purpose, such as "htop"

 ![image](https://www.tecmint.com/wp-content/uploads/2015/01/List-of-Running-Linux-Processes.png)

1. The current time 

2. Currently there are 121 processes running

3. us (time running user processes with unmodified priority), sy (time running kernel processes), ni (time running user processes with modified priority), wa (time waiting for I/O completion), hi (time spent servicing hardware interrupts), si (time spent servicing software interrupts), st (time stolen from the current vm by the hypervisor – only in virtualized environments).

4. Physical memory usage.

5. Swap space usage.

6. Inspecting physical memory usage

         you can also use free command.
        # free




you can also use the -m (MB) or -g (GB) switches to display the same information in human-readable form:

               # free -m



There are two tools that we will use to monitor processes closely:
                         
                # ps and pstree.

Using the *-e* and *-f* options combined into one (-ef) you can list all the processes that are currently running on your system. You can pipe this output to other tools, such as grep

![image](https://www.tecmint.com/wp-content/uploads/2015/01/Monitor-Linux-Processes.png)


#ps -eo user,comm,pid,ppid,%mem --sort -%mem

![image](https://www.tecmint.com/wp-content/uploads/2015/01/Monitor-Linux-Processes-by-Memory-Utilization.png)







## **How to View & Read Linux Log Files**




The "w" command is a built-in tool that allows administrators to view information about users that are currently logged in. This includes their username, where they are logged in from, and what they are currently doing.

   
the first thing to be done, when a problem arises, is to view the logs.


        # cd /var/log
    


"*whowatch*" is a simple, easy-to-use interactive who-like command line program for monitoring processes and users on a Linux system. It shows who is logged on to your system and what they are doing, in a similar fashion as the w command in real-time.





## Network Configuration, Troubleshooting, and Debugging Tools


Linux based distributions have featured set of commands which provide way to configure networking in easy and powerful way through command-line. These set of commands are available from net-tools package which has been there for a long time on almost all distributions, and includes commands like: 

- ifconfig
- route
- nameif
- iwconfig
- iptunnel,
- netstat
- arp
- mtr
- ping...

# VIRTUALIZATION <a id="vir"></a>



## What is a virtual machine (VM)? </br>


Virtualization is the process of running a virtual instance of a computer system in a layer abstracted from the actual hardware. Most commonly, it refers to running multiple operating systems on a computer system simultaneously.

## There are two primary types of hypervisors.
____
</br>

**Type 1 hypervisors:** <mark>run directly on the physical hardware (usually a server)</mark>, taking the place of the OS. Typically, you use a separate software product to create and manipulate VMs on the hypervisor. Some management tools, like  *VMware’s vSphere*, let you select a guest OS to install in the VM.

    A hypervisor is similar to an emulator; it is computer software, firmware or hardware that creates and runs virtual machines.

**Type 2 hypervisors:** <mark>run as an application within a host OS</mark> and usually target single-user desktop or notebook platforms. With a Type 2 hypervisor, you manually create a VM and then install a guest OS in it. You can use the hypervisor to allocate physical resources to your VM, manually setting the amount of processor cores and memory it can use. Depending on the hypervisor’s capabilities, you can also set options like 3D acceleration for graphics.

 <img src="https://pediaa.com/wp-content/uploads/2019/04/Difference-Between-Type-1-and-Type-2-Hypervisor-Comparison-Summary-e1556635404303.jpg" width="500" height ="500">


 </br>

![hyp2](https://www.serverwatch.com/wp-content/uploads/2020/09/what-is-a-hypervisor-server_5f5ed47e2d2aa.jpeg)

</br>



## What Are Namespaces?
___
When you’re running many different processes and applications on a single server, as is the case with deployment tools like Kubernetes, it’s important to have each process isolated, mostly for security.

Namespaces achieve <mark>this isolation at a kernel level </mark>(fundamental aspect of containers on Linux.). Similar to how the application ` chroot ` *(is an operation that changes the apparent root directory for the current running process and its children)* works, which <mark>**jails a process**</mark> in a different root directory, namespaces separate other aspects of the system. There are seven namespaces available (pid,net,mnt,uts,ipc,user,cgroup)
<img src= https://blog2opstree.files.wordpress.com/2018/10/0b413-blank2bdiagram2b252842529.png width=500 height="400">
</br>

## Control group (cgroup)
The cgroup namespace type hides the identity of the control group of which process is a member. A process in such a namespace, checking which control group any process is part of, would see a path that is actually relative to the control group set at creation time, hiding its true control group position and identity.

</br>

<img src= https://www.lightnetics.com/assets/uploads/files/1548929463534-cgroups.jpg width="500" height="400">

</br>

    1. Server resources, disk, memory, cpu, and network.
    2. The resources as show in 1, allocated in this example to 3 cgroups.
    3.  Hierarchically ordered groups of processes running on the system.
   
</br>



## What are Application Containers
 It is an application, service, or even microservice centric solution that usually runs just a single process inside. As a result, application containers promote creating immutable and ephemeral infrastructure. If an application or service needs to be updated, a whole new container is built (with the required adjustments) from the appropriate image. Then, it is provisioned to replace the existing running container instance.

<img src= https://www.cloudsigma.com/wp-content/uploads/Application-container-01.png>







Cont.APPS            |  VM'S
:-------------------------:|:-------------------------:
<img src= https://www.docker.com/wp-content/uploads/2021/11/docker-containerized-appliction-blue-border_2.png.webp width="400" >   |  <img src= https://www.docker.com/wp-content/uploads/2021/11/container-vm-whatcontainer_2.png.webp width="400">




### *Vagrant*:

Vagrant is a tool for building and managing virtual machine environments in a single workflow. With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time, increases production parity, and makes the “works on my machine” excuse a relic of the past. — (Vagrant Intro)

</br>


<img src= https://miro.medium.com/max/1400/1*DcnQa5yO6QQVNdtpIaymAQ.png width="400" >

</br>

### *Docker*
Docker is a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers. The service has both free and premium tiers. The software that hosts the containers is called Docker Engine.

### *Proxmox* 
Proxmox Virtual Environment is an open-source software server for virtualization management. It is a hosted Type-1 hypervisor that can run operating systems including Linux and Windows on x64 hardware. 

 allows deployment and management of virtual machines and containers. Proxmox VE includes a web console and command-line tools, and provides a REST API for third-party tools. Two types of virtualization are supported: container-based with LXC and full virtualization with KVM (Kernel Virtual Machine)<sup>*</sup>. It includes a web-based management interface.


 <sup>*</sup> Like Xen, KVM (Kernel-based Virtual Machine) is an open source hypervisor technology for virtualizing compute infrastructure running on x86 compatible hardware. 


 <img src= https://miro.medium.com/max/1400/1*yxCnS2vWiyE7SZWOUy1rBA.png>

</br>



 ## *Podman*

 Podman is an open-source project that is available on most Linux platforms and resides on GitHub. Podman is a daemonless container engine for developing, managing, and running Open Container Initiative (OCI) containers and container images on your Linux System.

 ![img](https://media-exp1.licdn.com/dms/image/C4E22AQFwP9ecfBb81g/feedshare-shrink_2048_1536/0/1636952989092?e=1654732800&v=beta&t=Zq2-WZ22elFSx7n-h6SD7TOhtH6aqkyhXSr0gqAzTEo)

 
 </br>



 ## *LXC*

 Linux Containers is an operating-system-level virtualization method for running multiple isolated Linux systems on a control host using a single Linux kernel.

<img src= https://www.researchgate.net/profile/David_Beserra4/publication/321297465/figure/fig1/AS:685171598688263@1540369047859/KVM-and-LXC-see-online-version-for-colour.ppm>

</br>

## *Kubernetes*
Kubernetes is an open-source container orchestration system for automating software deployment, scaling, and management. Google originally designed Kubernetes, but the Cloud Native Computing Foundation now maintains the project.

A Kubernetes cluster consists of a set of worker machines, called nodes, that run containerized applications. Every cluster has at least one worker node.

The worker node(s) host the Pods that are the components of the application workload. The control plane manages the worker nodes and the Pods(Pods are the smallest deployable units of computing that you can create and manage in Kubernetes.) in the cluster. In production environments, the control plane usually runs across multiple computers and a cluster usually runs multiple nodes, providing fault-tolerance and high availability.

This document outlines the various components you need to have for a complete and working Kubernetes cluster.


</br>

## *ESXi*

VMware ESXi is an enterprise-class, type-1 hypervisor developed by VMware for deploying and serving virtual computers. As a type-1 hypervisor, ESXi is not a software application that is installed on an operating system; instead, it includes and integrates vital OS components, such as a kernel.

</br>

<img src=https://www.iperiusbackup.net/wp-content/uploads/2017/11/VM.jpg>

</br>

# DevOps <a id=dev></a>

    DevOps focuses on ways to allow code to be deployed more regularly. If software is deployed more regularly, it means that new features can be added to an app faster.

> <mark>Automating everything:</mark> By automating the process of building and deploying software, so that you don’t need to do so many manual tasks.

> <mark>Adding automated tests:</mark>  If you can test your software, you will have more confidence in it. Even better if those tests can be automated! (So a person doesn’t need to perform manual steps to test the software)

> <mark>Working together:</mark>  By encouraging developers and operations to work more closely together. (This may sound strange if you’re new to coding, but it hasn’t always been the case that developers & ops teams work closely together!)

> <mark>Deploying software reliably:</mark> Sometimes software gets deployed which hasn’t been tested, or which takes a lot of tricky manual work to get running. This can cause a lot of stress and unpredictability. 

</br>

## What is the difference between CI and CD?

    The "CD" in CI/CD refers to continuous delivery and/or continuous deployment, which are related concepts that sometimes get used interchangeably. Both are about automating further stages of the pipeline, but they’re sometimes used separately to illustrate just how much automation is happening.

   ![img](https://www.redhat.com/cms/managed-files/styles/wysiwyg_full_width/s3/ci-cd-flow-desktop.png?itok=2EX0MpQZ)

</br>

## The 7 essential stages of a CI/CD pipeline

</br>


> - <mark>The trigger:</mark> The best pipelines are triggered automatically when new code is committed to the repository.

> - <mark>Code checkout:</mark> In this first stage, the CI server will check out the code from the source code repository, such as GitHub or Bitbucket.

> - <mark>Compile the code:</mark> This means that your CI tool needs to have access to whatever build tools you need to compile your app. For example, if it’s Java, you’ll use something like Maven or Gradle.

> - <mark>Run unit tests: </mark> where you configure your CI/CD tool to execute the tests that are in your codebase.



> - <mark>Package the code:</mark> If you’re using Java, you might build a JAR file. If you’re using Docker containers, you might build a Docker image.build the binary only once. Don’t build a different binary for each environment, because this will cause your pipeline to become very complex.

> - <mark>Run acceptance tests:</mark> Acceptance tests generally cover the functional parts of the application. For example, on a shopping website, an acceptance test might ensure that a user can add a product to their basket.

> - <mark>Delivery or Deployment:</mark> you have an artifact ready to be deployed (continuous delivery). Or, you can continue to CI/CD heaven and automatically deploy your software (continuous deployment).

</br>

## 🔨 Build and packaging tools
---
<mark>Git</mark> is a tool for managing, sharing and tracking changes in source code files.

<mark>Docker</mark> is a toolkit for building and running software in containers.

</br>

## 🎺 Application orchestration
---
</br>
<mark>Kubernetes</mark> is an orchestration tool for managing your applications running in containers.

</br>

## 🏗 Infrastructure automation
---
</br>

<mark>Terraform</mark> is a tool for creating and managing cloud resources with code.

<mark>Ansible</mark> is a tool for automatic configuration of infrastructure - e.g. installing packages, configuring web servers, creating user accounts, and so on.

</br>

## ⛳ CI/CD
---
<mark>GitLab</mark> is a tool for managing application source code and automating the build and release of your application.
GitLab’s built-in CI/CD feature lets you create workflows to build, test and deploy your applications.

<mark>Jenkins</mark> is an automation server for running software build and testing jobs, and much more.

<br>

## 🛂 Testing & quality
---
<mark>Sonarqube</mark> is a code-quality checking tool.

</br>

## 📈 Logging & monitoring
---

<mark>Prometheus</mark> is a monitoring and alerting toolkit.

<mark>Grafana</mark> is a dashboarding tool. It’s often used to show system and application stats, to make it easier to visualise what’s happening in a system.



