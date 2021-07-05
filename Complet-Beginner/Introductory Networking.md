# Introductory Networking.
###### This is writeup For Nakerah Exam On TryHackMe.
* This **Room** designed to provide a beginner's ***introduction to the basic principles of networking.*** 
    ## Task 1 - Intro 
    Just Read all that is in the task.            
            `No answer Needed`
    ## Task 2 - The OSI Model: An Overview .
    ##### This Task Cover What OSI (Open Systems Interconnection) Model And Layers, The Osi Model Consist of 7 layers (Application,Presentation,Session,Transport,Network,Data Link ,and Physical)

    1. Which layer would choose to send data over TCP or UDP?
        - `4`
    2. Which layer checks received packets to make sure that they haven't been corrupted?
        - `2`
    3. In which layer would data be formatted in preparation for transmission?
        - `2`
    4. Which layer transmits and receives data?
        - `1`
    5. Which layer encrypts, compresses, or otherwise transforms the initial data to give it a standardised format?
        - `6`
    6. Which layer tracks communications between the host and receiving computers?
        - `5`
    7. Which layer accepts communication requests from applications?
        - `7`
    8. Which layer handles logical addressing?
        - `3`
    9. When sending data over TCP, what would you call the "bite-sized" pieces of data? 
        - `Segements`
    10. [Research] Which layer would the FTP protocol communicate with?
        - `7`
    11. Which transport layer protocol would be best suited to transmit a live video?
        - `UDP`
    ## Task 3 - Encapsulation 
    ##### I suggest you watch this video to understand what is Encapsulation [Eng-Abeer Hosni](https://www.youtube.com/watch?v=hnnkjY7t-O8&list=PLCIJjtzQPZJ9-4WfmQlY7vspEMcmKf8yR&index=4)
    
    1. How would you refer to data at layer 2 of the encapsulation process (with the OSI model)?
        - `Frames`
    2. How would you refer to data at layer 4 of the encapsulation process (with the OSI model), if the UDP protocol has been selected?
        - `Datagrams`
    3. What process would a computer perform on a received message?
        - `De-encapsulation`
    4. Which is the only layer of the OSI model to add a trailer during encapsulation?
        - `Data Link`
    5. Does encapsulation provide an extra layer of security (Aye/Nay)?
        - `Aye`
    ## Task 4 - The TCP/IP Model 
    ##### Very Similar to the OSI model But Just Consist of 4 Layers (Application, Trasnport, Internet, Newtork Interface)
    1. Which model was introduced first, OSI or TCP/IP?
        - `TCP/IP`
    2. Which layer of the TCP/IP model covers the functionality of the Transport layer of the OSI model (Full Name)?
        - `Transport`
    3. Which layer of the TCP/IP model covers the functionality of the Session layer of the OSI model (Full Name)?
        - `Application`
    4. The Network Interface layer of the TCP/IP model covers the functionality of two layers in the OSI model. These layers are Data Link, and?.. (Full Name)?
        - `Physical`
    5. Which layer of the TCP/IP model handles the functionality of the OSI network layer?
        - `Internet`
    6. What kind of protocol is TCP?
        - `Connection-based`
    7. What is SYN short for?
        - `Synchronise`
    8. What is the second step of the three way handshake?
        - `SYN/ACK`
    9. What is the short name for the "Acknowledgement" segment in the three-way handshake?
        - `ACK`
    ## Task 5 - Networking Tools Ping 
    ##### The ping command is used when we want to test whether a connection to a remote resource is possible,Ping works using the ICMP protocol,The basic syntax for ping is `ping <target>`
   
    1. What command would you use to ping the bbc.co.uk website?
        - `ping bbc.co.uk`
    2. Ping muirlandoracle.co.uk
       What is the IPv4 address?
        - `217.160.0.152`
    3. What switch lets you change the interval of sent ping requests?
        - `-i`
    4. What switch would allow you to restrict requests to IPv4?
        - `-4`
    5. What switch would give you a more verbose output?
        - `-v`
    ## Task 6 - Networking Tools Traceroute1
    #####  Traceroute can be used to map the path your request takes as it heads to the target machine, The basic syntax for traceroute on Linux is this:` traceroute <destination>`
    
    1. Use traceroute on tryhackme.com ,Can you see the path your request has taken?
        - `No Answer Needed`
    2. What switch would you use to specify an interface when using Traceroute?
        - `-i`
    3. What switch would you use if you wanted to use TCP SYN requests when tracing the route?
        - `-T`
    4. [Lateral Thinking] Which layer of the TCP/IP model will traceroute run on by default (Windows)?
        - `internet`
    ## Task 7 - Networking Tools WHOIS 
    ##### Whois essentially allows you to query who a domain name is registered to, Just use `whois domain` to get a list of available information about the domain registration:
    1. Perform a whois search on facebook.com
        - `No Answer Needed`
    2. What is the registrant postal code for facebook.com?
        - `94025`
    3. When was the facebook.com domain first registered?
        - `29/03/1997`
    4. Perform a whois search on microsoft.com
        - `No Answer Needed`
    5. Which city is the registrant based in?
        - `Redmond`
    6. [OSINT] What is the name of the golf course that is near the registrant address for microsoft.com?
        - `Bellevue Golf Course`
    7. What is the registered Tech Email for microsoft.com?
        - `msnhst@microsoft.com`
    ## Task 8 - Networking Tools Dig 
    ##### Dig Tool Like ping and traceroute,Dig allows us to manually query recursive DNS servers of our choice for information about domains, ` dig <domain> @<dns-server-ip>` It is a very useful tool for network troubleshooting.
    
    1. What is DNS short for?
        - `Domain Name System`
    2. What is the first type of DNS server your computer would query when you search for a domain?
        - `Recursive`
    3. What type of DNS server contains records specific to domain extensions (i.e. .com, .co.uk*, etc)*? Use the long version of the name.
        - `Top-Level Domain`
    4. Where is the very first place your computer would look to find the IP address of a domain?
        - `Local Cache`
    5. [Research] Google runs two public DNS servers. One of them can be queried with the IP 8.8.8.8, what is the IP address of the other one?
        - `8.8.4.4`
    6. If a DNS query has a TTL of 24 hours, what number would the dig query show?
        - `86400`
    ## Task 9 - Further Reading
    ##### Networking is one of those things that you just need to learn. 
    1. Read the final thoughts
        - `No answer Needed`
