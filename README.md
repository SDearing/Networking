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
A logical topology describes how data flows through a network, and how systems on a network communicate with eachother.
#### Ethernet
Ethernet is a logical topology of how systems communicate on a network, ethernet contains protocols that avoids data being simultaneously transmitted by two or more systems, this makes sure there is no congestion or collisions on the network, assuring that data is sent to a system on the network work effeciently and reliably.
#### Token Ring
Token Ring is another type of logical topology that governs data flow in a network. It does this by using a protocol that sends one or more 'tokens' to seperate systems in the network. Systems with the 'token' are the only systems on the network that are allowed to transmit out data. This topology assures that there will be no collisions in the network ensuring the integrity of data transmission in the network.
### Physical Topology
Physical topologies describe the actual layout of a network. Physical topologies govern where the hardware is placed in the network and what other systems they are connected to.
#### Star
A star topology focuses on having a central switch, in which all systems are connected to. The systems on the network are only connected to the switch meaning that all data that is transmitted in the network must go through the switch first before it can reach other systems. A benefit of this topology is that data transmission is controlled by the switch, so there is less of a chance of data collisions in the network. However a constraint of this topology is that the network is heavily reliant on the switch, so if the switch fails the whole network will crash, untill the switch is brought back online.
#### Ring
A ring topology is a network where all systems are connected to 2 other systems, this forms a ring-like formation. This means that data sent from one computer system has to go through every computer system untill it reaches the desired location on the network. A benefit of this topology is that it is reliable, this is because if one system fails or a connection is severed, the network can adapt and send data in the other direction of the ring. However a drawback of this topology is that it isn't an efficient topology, this is because if a computer wants to send data to a workstation on the network, the data will have to be sent through each workstation which slows down the data flow.
#### Bus
A bus topology is a network where all workstations are connected to the same central cable or the 'bus'. This means that all data sent through the network is carried by the central cable to the desired destination. On each end of the central cable is a terminator that stops data signals being reflected back into the 'bus'. A benefit of a bus topology is that it is cheap and easy to set up, this is because the intial set-up of a bus topology does not require much cabling. However, a constraint of this topology is that the network is very dependent on the central cable, so if the central cable was damaged the whole network would be damaged.
#### Mesh
A mesh topology is a network where all systems on the network are connected with each system on the network, allowing transmissions to be distributed, even if one connection goes down. This topology is also usually used for wireless networks. A benefit of this topology is that the network can handle the transmission of a high amounts of data, as multiple systems can be send data throughout the network simultaneously. A Disadvantage of this topology is that it is much more expensive to set up than other topologies, making it a less desirable topology.
#### Tree
A tree topology combines the characteristics of star and bus topologies, this means that the tree topology consists of groups of star formated workstations which are all connected to a central cable. A benefit of this topology is that it easy to expand, as all that needs to be done is add a new star formatted network to the central wire. However, like the bus topology, the network is reliant on the central cable as it is the only connection between the groups of work stations.


## Operating Principles
### Networking Devices
#### Hubs
A hub is a networking device that connects multiple computers or other systems together. The hub contains multiple ports of which systems can connect to. When the hub receives data it transmits it to all other systems connected to the hub as it contains no intelligence of where to send data exactly.
#### Routers
Routers are devices that transmits data to other networks. A router is connected to at least two networks, most commonly two LANs, and  and acts as the gateway for the networks, receiving and sending data out of the network. Any data packets recieved by the router will contain an IP address for the destination system so the router knows where to send the data on its network.
#### Switches
Switches, like hubs, are used to connect systems on a network. However a switch uses the method of packet switching to process data and transmit data to a specified system. Packet switching is where data is broken down and then sent independently to each destination system, the broken down data is then reassembled at the destination.
#### Multilayer Switch
A multilayer switch is a sophisticated piece of hardware that provides the role of a switch, controlling the transmition of data and connecting systems together. However a multilayer switch also provides the role of a router allowing it to transmit data throughout multiple networks.
#### Firewall
A firewall is a system which is designed to prevent unauthorized users from accessing a private network. A firewall can either be software or hardware and prevents external internet users from breaking into a network which is connected to the internet.
#### HIDS
HIDS stands for Host-based Intrusion Detection System, which is a device that monitors and analyses computer systems on a network aswell as the network packets sent through the network. The role of a HIDS is to make sure that computer systems on a network only contain software that only does what it's expected to do. 
#### Repeaters
Repeaters are a network device that are used to restore damaged data transmitted on a network. The role of a repeater is to regenerate data while it is travelling a large distance to a another network, as the further a data packet travels the higher the chance of data loss, so a repeater makes it possible to send data over a distance.
#### Bridges
A bridge is a device that is used to connect networks that use the same communication protocols. The bridge does this by using an internal database to determine the traffic that is allowed through each network.
### Wireless Devices
#### Access Points (Wireless/ Wired)
A access point is a device that can be implemented into a network that allows the use of Wi-Fi on the network. The access point can either be wireless or wired, a wireless access point will allow the use of Wi-Fi in the general area the access point is located. Where as, a wired access point will only allow Wi-Fi to systems connected to it, usually by an ethernet cable. Some access points will allow the systems to connect up to Wi-Fi using both a wireless or wired connection.
#### Content Filter
A content filter is a device that is used by a firewall to control what data is not allowed access through it. The content filter decides this by analysing the source and destination addresses of the data packet.
#### Load Balancer
A load balancer is a device that distributes the data traffic of a network across the systems on a server. The role of a load balancer is to increase the capacity of traffic on a network.  
#### Modem
A modem is a device that allows a network to transmit data through telephone or cable lines. A modem does this by translating the digital configuration of data, into a analog waves so they can be carried by telephone or cable lines.
#### Packet Shaper
A packet shaper is a device that is placed on the gateway of a network, that processes all incoming and outgoing data from the network. The packet shaper prioritizes what data is sent and recieved based on the protocols of the network.
#### VPN Concentrator
A VPN concentrator is a device that allows a VPN router to be accessed by multiple systems at the same time. It does this by creating and managing VPN tunnels to the VPN router, and then assigning each VPN tunnel to a system on the network.
### Server Types
#### Web
A web server stores information of webpages for a website. When a user tries to access a webpage over the internet a request is sent to the desired web server for that webpage. The webpage then sends over the data that makes up that webpage to the user, when the data has arrived to the user, the user's computer system then recreates the webpage using the data sent and displays the webpage to the user.
#### File
A file server stores the data of files for users to access. When the user requests a file from the server, the file is broken down into data packets so it can be sent effeciently through the internet/network. When the user's system recieves the data packets, it uses the packets to recreate the file so it can be viewed by the user.
#### Database
A database server stores records on a certain medium. Data for each record stored on this server are broken down into attributes (or fields). For example Amazon's database server would hold information on their products, such as price, stock and name. A database server is used to hold data and/or present data.
#### Combination
A combination server is a server that can provide all the purposes of the three previously mentioned servers.
#### Virtualisation
A virtualised server is a server that holds a physical server into a number of small devices which are the virtual servers. It does this with the assistance of virtualisation software. Each virtual server will run multiple instances of operating systems to provide services to multiple users at once.
#### Terminal Services
A terminal is a device on a network (i.e. PCs, servers). A terminal server is a common connection point for terminals on a network can connect to, to provide a path to another network.
## The Interdepedence of Workstation Hardware with Networking Software
### Networking Software
Networking software is used to help administrators of networks deploy and manage a network. 
#### Client Software
A client is general term for computer hardware that accesses the services provided by a server. Client software is a peice of software on a client that performs a certain task. For example Google Chrome is a client software that carrys requests to a web server to recieve data of webpages from the web server.
#### Server Software
Sever software is software that is designed to allow an administrator to use, operate and manage a server. Server software controls a server's hardware such as memory, storage and input/output. The configuration of the server's hardware dictates what purpose the server will serve, such as providing clients with webpages.
#### Client and Server Operating Systems
An operating system on a computing system (such as a client or server), is software used to manage software on a computing system. An OS can do this by prioritising the tasks requests made by the systems software to be ran by the systems CPU. An OS also provides a detailed user interface to allow the user to easily manage the systems on a client or server.
#### Firewall
A firewall is a system which is designed to prevent unauthorized users from accessing a private network. A firewall can either be software or hardware and prevents external internet users from breaking into a network which is connected to the internet. The firewall decides what data can or can't be passed through it, by setting up rules that data must uphold for it to be passed through so the data can enter the network.
#### Proxies
A proxy can be a computer sysetm or a peice of software. The role of a proxy is to act as a link from a clients request to another server. Proxies were invented to add structure to a network.
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
