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
  > ds
