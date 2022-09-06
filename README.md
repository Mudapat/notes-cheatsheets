# **Notes & CHEATSHEET**

## TABLE OF CONTENT


1.  Markdown     :arrow_right:   [*here*](#md) 
   
2. GIT/GITHUB   :arrow_right:  [*here*](#git)
3. SSH         :arrow_right:     [*here*](#ssh) 
4. TCP/IP    :arrow_right:      [*here*](#tcp)
5. Linux system monitoring tools  :arrow_right:     [*here*](#moni)
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


[![git-cheat-sheet-education-1.png](https://i.postimg.cc/yNwWzT8T/git-cheat-sheet-education-1.png)](https://postimg.cc/wtQ9XLJt)


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



 
.