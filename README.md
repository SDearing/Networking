# Networking
## The Benefits and Constraints of Network Types and Standards
### The Different Types of Networks
There are different ways that computers can be connected over a network, this is called the type of network, the systems that require information are called clients and the systems that provide information are called servers and the type of network dictates how these systems communicate with each other.
#### Peer to peer
The first type of network is called a peer to peer network, this network has no single system that provides the role of the server, instead each computer on the network stores files and acts as the server. This means that each computer has equal responsibility for providng data. The purpose of a peer to peer to network is to allow computers to transfer files between eachother without the need of a server to control the data flow.

A benefit of peer to peer networks is that it is easy to set up as it requires, at minimum, only two systems and configuring new systems on the network is easy to do, as all systems on the network have the same permissions. Another benefit of peer to peer networks is that all resources and contents are shared by all the systems on the network. Additionally, this type of network is very reliable as there is no dependencies on a certain system to work, which means if one system on the network crashes it will not affect the integrity of the network and will function normally. The final benefit of a peer to peer network is that the overall cost to set up and maintain the network is relatively less than other networks.

However a contraint of peer to peer networks are the whole network is decentralized, therefore it is difficult to administer, this means that one person cannot determine the whole accessibility of the network. Another weakness, is that a peer to peer network has less security than other types of networks, meaning that malicious software such as spware, can easily be transmitted throughout the network infecting any other system on the network. A final constraint is that data recovery or backup is difficult as each system controls its own data, meaning each computer on the network will need to administer its own back up. 

Information on a peer to peer network is transferred through each peer system on the network and requires no server to manage the data transmission. Also as peer to peer networks are used for file sharing, you cannot use a peer to peer network to collaborate on the same documents or work together on the same projects. However the use of file sharing helps project groups share individual work between eachother and also software can be shared allowing all users on the network to have the same resources
#### Client-Server
The client-server model is the relationship between computers in which one computer acts as the server, in which the other computers makes service requests to. The clients are dependent on the server to provide and manage information. The purpose of this network is to hold all data of the network in one centralized location and to deal with multiple clients at once.

A benefit of client-server networks is that it easy to manage, this is because all files are stored at the same place allowing files to be easily found. Another benefit the this type of network, is that it is easy to back up and recover files, this is because all the data is stored on the server which makes it easy to make a back up of it. Also in the case of a break down if data is lost, it can be recovered from the server effeciently. Another benefit is that upgrades to the network can be easily made, as you would only need to upgrade the server system. The final benefit of client-server networks is that the security of the network can be easily implemented as you only need to apply security to the server.

A constraint of client-server networks is that too many requests to from clients to the server could lead to congestion, which would dramatically slow down the network and could lead to the break down of the server. Another weakness of the server is that this type of network is also very dependent on one system, the server, meaning if the server fails then the whole network will fail. Another constraint of this type of server is that it is very expensive to install and manage the server on the networkl. Finally, this type of network will need professionals to maintain the servers and other technical details of the network.

#### Cloud
A cloud network allows a user to access data and programs over the internet instead of using the computers hard drive. The purpose of this network is to allow multiple users to access the same software and data, and therefore work together on the same documents and allow the storage of data that all users can access.

A benefit of using a cloud network, is that it saves money, as you don't need to invest money in storage hardware as all data and software is stored in the cloud. Another benefit of using a cloud network is that it is more reliable than using storage hardware, as a cloud network is designed to automatically save data on the network so if user's system crashes, the data will still be intact.

However a constraint of using a cloud network is that if a cloud network fails it will affect a huge amount of users, meaning they will not be able to access their data from the network, therefore the cloud network is very dependent on the systems holding the cloud. Another weakness of the network is that, because it is accessed via the internet, a cloud network is very vulnerable to hackers as anyone can potentially access the network. Finally another contraint is that the maintanence and setting up of a cloud network is very expensive as the network has to be powerful enough to handle thousands of users accesesing it at the same time.


#### Cluster
A cluster network is a group of computers that work together so that they can be viewed as a single system. In a cluster network all computers are given the same tasks, which are controlled and regulated by software which would be the single system being viewed. THe purpose of this is that the network can be used for tasks which would require a high amount of processing power.

A benefit of cluster networks is that it is very robust, this is because even if one system fails in the cluster, the cluster will continue to function as normal, with the only drawback being a lower processing power. Another benefit of a cluster network is that configuring new systems to the cluster is very easy to do.

However a constraint of cluster networks is that the network is not protected from shared storage failures, meaning if the clusters storage fails there will be no way to safe the data unless a back up was made in advance. Another weakness of the network is that the whole cluster will usually be in one location, so if any incidents occur in that building (such as a fire) the whole network would be at risk of being damaged, costing the owner a huge amount of money.


#### Centralized
Centralized networks are when all systems are connected to a central server, which handles all storage and communcations of the network. This means that the central server is responsible for the integrity of the server and controls every aspect of the server. Most clients connected to the centralized server are usually limited in processing power, with only the processing power to connect to the centralized server, this is because the centralized server controls all processes on the network and therefore completes tasks for the client systems.

A benefit of a centralized network is that new client systems are very easy to add to the network as they only need to be able to connect to the centralized server. Also another benefit of a centralized network is that buying new client systems for the network would be very cheap as they require only a small amount of processing power, meaning they would not need to have very sophisticaced hardware. 

However a constraint of a centralized network is that the whole network is dependent on the centralized server, meaning if the server crashed then all systems connected would fail until the centralized server was fixed. Another constraint of a centralized server is that the central server will require a large amount of data storage and processing power, therefore being very expensive for the network owner to set up.

#### Virtualised
A virtualised network is a network that combines all available resources in a network, by splitting up the available bandwidth into channels. These channels are independent from each other and can be assigned or switched between different systems on the network. The assigning of channels is dependent on which systems require the most bandwidth at a given time. The purpose of virtualisation is to remove the need of hardware from the network.

A benefit of a virtualised network is that there is less of a demand for lots of different technical skills, this is because with the hardware eliminated from virtualisation, the need to have workers trained in the different brands and models of hardware is also eliminated. This means that the overall maintanence of the network would be lower than a physical network. Another benifet of virtualised networks is that they have improved recovery times after a hardware failure.

However a drawback of virtualised networks is that the upfront cost of setting up a virtualised network is very high, which some organisations may not be able to afford. Another constraint of virtualised networks is that they will require IT staff with an expertise in virtualisation, which could mean an organisation would need to hire new workers to account for the virtualisation costing them more money.


### Conceptual Models (OSI and TCP/IP)
These conceptual models are the rules that data must follow for it to be transmitted across the internet. Below are the run down for the protocols involved for TCP/IP and OSI models.
#### TCP/IP
TCP/IP stands for transmission control protocol/internet protocol, it follows 4 different layers that data is put through when it is being transmitted across the internet.
* Application: This layer controls the way data is represented when sent to the recipient of the data. It does this by specifying the protocols of application.
* Transport: This layer is responsible for maintaining the transmission of data across the internet. The two main protocols that control this layer are TCP and UDP. TCP is considered the more reliable protocol for transmission as it checks if the data has been recieved by the reciever, whereas UDP does not check to see if the data has been transmitted safely, however UDP is considered a quicker protocol for the same reason it is unrealiable.
* Internet: This layer constructs the packet of data. This layer is handled by the internet protocol (IP), this protocol dictates that a data packet must have the senders IP address, the recievers IP address and the actual data.
* Network Access: This layer describes how the data will be physically sent through the network, this means the way the sender's network is able to connect to the internet, this is usually by ethernet cabling.
#### OSI
The OSI model stands for Open Systems Interconnection and divides communication into seven layers. Layers 1-4 deal with the movement of data, while layers 5-7 control how the data is applied.
* Layer 7 Application: Similar to the TCP/IP model this layer deals with how the data is applied to receiver by selecting the application protocol.
* Layer 6 Presentation: This layer controls how the data is presented by translating the data into a format the application layer can work with. This layer also encrypts data so it can be sent through a network.
* Layer 5 Session: This layer establishes, manages and terminates the connection between the communicating systems. 
* Layer 4 Transport: This layer handles the transmission of data between the two communicating systems and is responsible for ensuring the data was sent completely.
* Layer 3 Network: This layer handles how the data gets to its destination. It does this by calculating the logical path between nodes on a network so that the data can travel to the destination in the most effecient way.
* Layer 2 Data Link: This layer handles hows the computer on a network gains access to the data and how the permissions the computer needs to follow to send it. The other purpose of this layer also handles checking for any errors in the data.
* Layer 1 Physical: Like TCP/IP the lowest layer handles how the data is sent through the network physically, which involves using the hardware associated with the senders network.
### Standards and Protocols
#### IEEE Standards
IEEE standards are the physical cabling used in data transmission on the physical layer. There are different types of IEEE standards that are used for different connections depending on the distance data has to travel.
* IEEE 802.3: This is the standard of ethernet cables. This type of cable is mostly used to connect systems on a Local Area Network. 802.3 specifies the characteristics of Ethernet.
* IEEE 802.7: This is the standard which covers broadband Local Area Networks. It specifies the design, installation and test parameters for broadband cables.
* IEEE 802.8: This is the standard which covers fiber optic cables, like the previous standards it specifies the design, installation and test parameters for fiber optic cables.
* IEEE 802.11: This is the standard which covers wireless connections, this standard outlines which frequencies are to be used by different wireless connections such as Wi-fi.
### Routed Protocols
Routed protocols are the rules that data must follow so it can be transmitted across networks. The most common routed protocol is IP and handles the address of systems on a network. Throughout the history of the internet IP has taken many different forms, first IP was in the form of IPV4 which was developed in the 1980s and is probably the most known version of IP (e.g. 192.89.2.1), however IPV4 could only be used by a maximum of 3.7 billion systems, at the time the creators thought that was more than enough for the world but as the amount of systems connected to the internet increased there needed to be a version of IP that would allow the use of more addresses. So, IPV4 was then developed into IPV6 which uses a 128-bit address space. This version of IP allows the use of 340 undecillion addresses, so its safe to say that we will not need another version of IP for awhile.
### Services and Network Applications
#### HTTP
HTTP stands for Hyper Text Transfer protocol, and is used to send data about webpages. HTTP is sent from a web server and involves the data needed for your computer system to re-create the desired webpage.
#### FTP
FTP stands for File Transfer Protocol. As the name suggests it is the protocol for sending and recieving files between a server and a client on a network. 
#### SSL
SSL stands for Secure Sockets Layer. This protocol ensures that data is sent in a secure matter by encrypting the data so it cannot be intercepted and stolen. This protocol is mostly used for sensitive data like credit card details.
#### SMTP
SMTP stands for Simple Mail Transfer Protocol. This protocol is used for sending and receiving emails and is used by most e-mailing services like Gmail.
#### POP3
POP3 stands for Post Office Protocol 3. This protocol is a client/server protocol which is used for sending emails on a network and holds the email that is being sent to he reciever while they are not logged into their email account and when you log into the account the emails are downloaded from that server.
## The Impact of Networking Topology, Communication and Bandwidth
### Logical Topology
A logical topology describes how systems on a network 
#### Ethernet
#### Token Ring
The computer with the token can communicate, benefit: no collisions when transmitting data
### Physical Topology
#### Star
#### Ring
#### Bus
#### Mesh
#### Tree
#### Ring
### Communication
### Bandwidth


## Operating Principles
### Networking Devices
#### Hubs
#### Routers
#### Switches
#### Multilayer Switch
#### Firewall
#### HIDS
#### Repeaters
#### Bridges
#### Wireless Devices
#### Access Points (Wireless/ Wired)
#### Content Filter
#### Load Balancer
#### Modem
#### Packet Shaper
#### VPN Concentrator
### Server Types
#### Web
#### File
#### Database
#### Combination
#### Virtualisation
#### Terminal Services

## The Interdepedence of Workstation Hardware with Networking Software
### Networking Software
#### Client Software
#### Server Software
#### Client Operating system
#### Server Operating System
#### Firewall
#### Proxies
### Differences between network card, wireless, mobile and cabling
### The need for permissions in networking

## Design and Implement a Network
### Network Specification
The task I have been given is to design a fully working network. I was given very specific guidelines of how to create this network, the first specification was that the network had to consist of two LANs (Local Area Network) that were connected together by two routers. The next specifcation was that both LANs had to have the structure of a star topology meaning that they all systems had to be connected to a central switch. The next specification was that each LAN had to comprise of three computer systems, one server and one switch (mentioned before), additionally on the WAN (Wide Area Network) there had to be one printer and one wireless access point. As a final specification I was also given the required IP addresses of all the systems on the network which are listed below:

#### LAN 1 IP Addresses
Computer Systems:
* 192.168.1.100
* 192.168.1.101
* 192.168.1.102

Server:
* 192.168.1.10

Router:
* 192.168.1.1
#### LAN 2 IP Addresses
Computer Systems:
* 192.168.10.100
* 192.168.10.101
* 192.168.10.102

Server:
* 192.168.10.10

Router:
* 192.168.10.1
### Concept Design
Below is the concept design for my network, this is so I could plan out the whole network before I implemented it. This is so I could obtain user feedback and therefore evaluate my network before I start implementing it.

![Design](https://github.com/SDearing/Networking/blob/master/NetworkDesign.PNG)

As you can see, from the design, I have designed 2 LAN networks. Both LAN networks contain 3 PC systems, 1 server, 1 switch and 1 router. The aspect that seperates the two LAN networks is that the LAN 1 has access to a printer and LAN 2 has access to a wireless access point. All these systems have been put into the design to fufill all the specifications stated at the beginning of this section. This design also fufills the specification as all systems on each LAN are connected to a central switch, which makes the topology of both LANs a star topology. Also this design fufills the specification as both LANs are connected via their routers to create a one WAN.
### User Feedback
To fully evaluate my design I asked multiple to peers to give their opinions on my design, this is so I could be fully sure that my design fufilled all the specifications before I moved onto implementation. Below is what they said:
##### Dan
"I think this design is fine, it seems to complete all the specifications, so I think its ready to be implemented. , I also like the naming format you used for each system" 

##### Luke
"I think the design is okay, however I would suggest changing the wiring between the routers as it makes the design look like it's just one LAN and to connect two LANs you need to use a Serial wiring"

Dan seemed to think my design was ready for implementation as it fufilled all the requirements and even complimented my naming format for the systems (i.e. PC 1-2). However Luke liked the design, but suggested that the connection between the two routers should represent a Serial wiring as it makes it look like my network is just one large LAN. I have taken this feedback into consideration and will add the Serial wiring when I fully implement my network.
### Evaluation of Design
From user feedback I would suggest that my design is ready to be implemented as a fully working system. This is because from all the user feedback I obtained they all said that it fufilled all the specifications of the task. Another strength of my design is the naming format I used for every system, this is because if I name a system from my design it tells you which LAN it is on and what the system is (for example PC 2-1 tells you its the first PC on LAN 2). However a weakness of my design is that the wiring is not fully complete on my design as the wiring between the two routers should be Serial wiring, so I should of changed the wire symbol connecting the routers to represent this.
### Implemented Network
![ImplementedNetwork](https://github.com/SDearing/Networking/blob/master/ImplementedNetwork.PNG)

### Testing the Network
Below is the test plan for my network, involved in the test plan is the outline of the test, expected and actual outcomes, and action needed to be taken after testing.

![Testplan](https://github.com/SDearing/Networking/blob/master/NetworkTestPlan.PNG)


### Evaluation of Implemented Network
