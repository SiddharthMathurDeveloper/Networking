# Nothing in life is as simple as it seems sometimes there are gray areas
## Networks :
- A computer network is a digital telecommunications network for sharing resources between nodes which are computing devices that use a common telecommunications technology.

- Data transmission between nodes is supported over data links consisting of physical cable media such as twisted pair of fiber optic cables or by wireless methods such as Wi-Fi microwave transmission or free-space optical communication.

  ### Why do we have computer networks?
 -  Big reason to have a network as per this definition is to share resources. We want to share information or share some      kind of resource with someone else.

  ### What is a resource ?
 - In the old days. A common example of a resource would be a printer. If you had an office with 100 people in the office 
  you could buy a printer for every workstation or for every PC And that's what they had to do before the days of 
  networking.

 - They either had to have a printer for every computer or have no printers or what they had to do is do , something like 
  this where they copy a file onto a floppy disk and then go over to the printing station and then print it manually.

 - It's not cost-effective to buy a printer for every workstation or for every person. It makes much more sense to have a 
  centralized resource in this case a printing resource and share that resource amongst the people in the office.

- So rather than having let's say 100 printers for 100 people you only let's say have 10 printers. So you've reduced the 
 cost by creating a shared resource a resource that can be shared by what are called clients.

- Now today we still use this kind of technology by using USB thumb drives. So if I wanted to share a resource with you like a photograph or a file I could copy it onto this USB drive and then give it to you and then you'd copy it to your computer.

- So sneakernet the original type of networking if you like is where a human being would take a resource copy of file or a photograph into this USB drive. I'd walk to your computer and then give it to you and share the resource with you.
But that's not very effective. It's not scalable doesn't work that well. You, let's be honest, most humans would be too lazy to have to walk around the office to share files.

***It's much easier just to share files using a digital transmission mechanism or medium and they're different types of digital transmission mechanisms.***
  

  ### What is node ?
  - And there are many types of computing devices. We could have Windows laptops. We could have Mac books.We could have         phones.We could have servers.

- Those are often the devices that most consumers will think about.

- But in networking, we have specialized devices such as hubs, switches, routers and firewalls to name a few.

### Summary 

- Why do we have a computer network? 

- We want to share resources which could be a printer, could be a file, could be a video.

- So videos are very popular these days.

- You watching s video through a computer network I'm sharing  information with you using a data link

- In the Wikipedia definition. They talk about a data link being a physical cable such as twisted pair, fiber optic cables, Wi-Fi or some type of data link where I'm sharing information with you.

- So the big idea here is I'm sharing a resource with you and I need a way to get that to you. You need a device that can receive the resource, we need some kind of transmission media which could be physical cables or it could be wireless.

- So the idea is rather than having to physically transport a file on a USB drive or in the veryvery old days using a floppy disk we use a cable or some kind of mechanism to transmit data from one device to another or from one device to many devices.



## More About Networks :

- But a network doesn't have to be very big. A small network would simply consist of two computing device.
-  eg . So copy a file from this computer onto the drive and then put it into the second computer and then copy the file onto       this computer. So that's how I could share information from one computer to another without a network.


![Screenshot 2023-08-24 at 1 59 57 PM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/5f59c522-3ae9-470d-84d7-007b777d6c91)<br/>
  ***But in its most basic form a computer network will use something like a cable , copper Ethernet cable.This is what's   called UTP or Unshielded Twisted Pair copper cable.You've probably come across these types of connectors in the real world.     This is known as an RJ45 connector.***

- Newer laptop and like a lot of newer laptops and Mac books it doesn't have any RJ45 Network ,it has NIC (Network Interface Cards)


## Network Interface Cards (NIC) :
![Screenshot 2023-08-24 at 2 07 59 PM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/073c2c82-63bb-4de6-9cbb-fefe5f5d164b) ![Screenshot 2023-08-24 at 2 08 17 PM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/ab5fb931-86dd-427d-b51e-3d5940640d48)
<br/>

- Now a Network Interface Card or NIC is how we connect to the physical network or wireless network.It's basically a card that's either inserted into a laptop or is built into a laptop that has what's called a MAC address or Media Access Control address on Ethernet which is the technology that we generally use today or wireless devices are known by what's called a MAC address.

- If you don't have a Network Interface Card in your laptop you could use USB to Ethernet adapter like this.
![Screenshot 2023-08-25 at 9 19 32 AM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/b9d7b2bf-4573-48fd-95e3-4a21b265825b) Ethernet


![Screenshot 2023-08-25 at 9 20 47 AM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/7aba5a41-8056-47dc-9928-1a0fc5095699) Wireless </br>
So that would allow you to connect to the network using Ethernet or once again using wireless.

***You essentially need a way to get a node onto the network and a Network Interface Card is the way that you connect yourself to the Ethernet network. Remember we are transmitting data from one device to another using some kind of media which could be the air could be physical cabling.***





## MAC address or Media Access Control :

![Screenshot 2023-08-24 at 2 29 47 PM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/8e9e02a8-c607-4a2b-abd1-dcf0b92d9730) ![Screenshot 2023-08-24 at 2 32 54 PM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/f3f2702d-5785-4fd9-8ac0-f95dad2a0182)
<br/>

- A MAC address, or media access control address, is a 12-digit hexadecimal number assigned to each device connected to the network.
- They are physically attached to the  hardware device / burned into it
  
- It is primarily specified as a unique identifier during device manufacturing and is often found on a device's network interface card (NIC).
![Screenshot 2023-08-28 at 9 41 16 AM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/d1eb188c-9499-4955-bbf1-4bc095c1f449)

- The first half of this address is the vendor code. Second half is a unique identifier for the MAC address
  
- 48 bits in length

## Address Resolution Protocol (ARP) : 
- Arp entries are found arp is used to discover the MAC address of another device in ethernet devices have MAC addresses allocated to them by vendors
- If I want to talk to your device I need to know what your MAC address is to be able to send the traffic onto the ethernet network.
- So for example if the laptop pings the PC, it's basically going to send a broadcast into the network saying who has this IP address and then that PC will reply back.

## WiFi :
- Wi-Fi is an example of using the air for transmission of data from one device to the other makes life a lot easier
in many ways. People today expect that it's easy to share information from one device to another.

- They are used as a network address in communications within a network segment and are common in most IEEE 802 networking technologies, including Ethernet, Wi-Fi, and Bluetooth

***Apple Airdrop creates it's own WiFi network that allows two devices to shares files without the need for any other
Wifi networks.***




## Server :
![Screenshot 2023-08-25 at 9 50 19 AM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/1004576c-01e7-4972-b566-7cbcf7ad81b3) <br/>


- In computing a server is a computer program or a device that provides functionality for other programs or devices called clients.
  This architecture is called the client server model and a single overall computation is distributed across multiple processes or   
  devices.
  
- The whole idea of a server is to provide resources or functionality to clients. So this server is big because we want a lot of storage, we want a lot of computing power and a lot of memory in a server especially if we want to scale it up.

- If you've got thousands and thousands of queries from many many clients to a server you wanted to have the capacity so memory, CPU, storage to handle those queries. So hence big device. It needs to have the capacity to service the requests.

- So if only one or two people are requesting a web page from the server that's not a problem.But if we've got thousands and thousands of requests one server may not even be enough.

  ***And then we have distributed services. So we have a service such as a web page that's distributed across multiple servers.***

- Google as an example will have thousands upon thousands upon thousands of servers to service the requests from millions of clients. So they will have many many servers to service or provide a service to the clients. When you go to the Google Website and you type in a request that's querying databases and retrieving information from databases to give you a answer about some query that you've made.
  

- So the server is providing a service to a client.

- You don't need dedicated hardware like this to have a server a client device such as a laptop can act as a server.
  So the role will determine how that device is acting. A physical laptop such as this laptop could be a client requesting a service   from a server but it could also be hosting a service

- So it may be running some kind of server and then sharing a file as an example with a another PC, so it's hosting a file sharing   service. <br/>
![Screenshot 2023-08-25 at 9 53 15 AM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/8bdb6b04-906a-4b05-b294-77adff5f760c) <br/>

-  So clients access servers to make use of a service that the server is providing. A website will serve a web page to a client which is then displayed on your computer as an example.

- Server / Computing device / one physical computer will be listening on different port numbers for different protocols.

- A computer server is listening on specific port numbers. If you want to get a web page your browser is automatically configured or programmed to talk to port 80(Http) or to port for 443(Https).

 ***So notice a server is providing a service or functionality to clients in what's called a client server model.***


## Client :

- A client is a piece of computer hardware or software that accesses a service made available by a server.The server is often on another computer system in which case the client accesses the service by way of a network /across a network



## Client - Server Model :
![Screenshot 2023-08-25 at 10 12 53 AM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/84e59b05-2c63-4514-8569-73c8ff30e596)<br/>
- So a server can run multiple services and provide multiple services to clients / client requests something from a server the server provides the file or the service to the client this is called  client-server model 




## Protocols :
- In networking, a protocol is a set of rules for formatting and processing data. It's basically a set of rules used for communication between devices, 

- As an example I'm speaking English here.Hopefully, you can hear what I'm saying and hopefully, you can understand what I'm saying because I'm using a set of conventions in my speech. So in English we speak a certain way. As an example some languages will use numbers differently to English. The protocol that we are speaking here is English so I will say 21 but in a different language like
Afrikaans I'll say een-en-twintig which is basically saying one two to denote 21.So the way that words are pronounced or the way that numbers are pronounced is reversed in a different language to English.

- The point is you and I are using a specific protocol we are listening to English as the transmission and you can understand what I'm saying. But if I switched my language or my protocol and started saying goeie more uhanet fan da, you might struggle to understand me unless you understand South African.

***The point is is that a server doesn't just automatically switch like we do in our brains from one language to another.It has to listen on specific port numbers.***

- Your ears are listening on the same frequencies for both English and Afrikaans then your brain just switches from one language to     another

- A server is not as clever as that. It has to listen on specific port numbers for specific protocols.



## Ports :




## Attenuation :
![Screenshot 2023-08-27 at 3 56 43 PM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/ba0d62aa-57bb-47ed-900d-307637895b74)
<br/>
- Refer to the reduction in the strength or intensity of a signal . The longer the distance less strong a signal.


## Repeaters :
![Screenshot 2023-08-27 at 3 52 38 PM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/ead5a8bf-c542-46ac-b61f-01f95ca70861)
<br/>
- A repeater is an electronic device that revices a signal and retransmits it.
  
- Repeater are used to extend transmissions so that that signal can cover longer distance or be received on the other side of an   obstuction
  
- Doesn't have many ports on it. We've only got two ports.
  
- They then developed what was called a multiple port repeater.

- So a repeater here would amplify the signal amplified from one port to another.

  ### Multiple Port Repeater
  - Repeater with lots of ports

***There's no intelligence in the repeater.***


- Otherwise we get attenuation of signals and the signals degrade over a period of time which restricts the length of a cable.
  This allows me to increase the length of the cable.

***Wireless access point very modern wireless access point supports Wi-Fi 6 the Wi-Fi network or a wireless network is essentially
a hub in the air. We are sharing the air***



## Hub :
![Screenshot 2023-08-27 at 3 50 56 PM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/9f5cc341-1cbc-496b-918e-c3561a230f17)
<br/>
- Hub does is once again it simply repeats the signal without understanding what's going on.
  
- It works at what's called Layer 1
  
- So it doesn't understand the frames that it receives or the information that it receives. It simply amplifies it.
  
- Hub is essentially a multi port repeater.

- It's repeating the signal from one port to multiple other ports.

- So if traffic was received on port one on this hub it would simply amplify the signal out of all of those ports.
  So it repeats the signal out of every other port without understanding any of the details.

***There's no intelligence in the hub**




## Switch :

![Screenshot 2023-08-26 at 1 27 07 PM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/028a4202-2c92-413c-9c6b-7084fbf3bd41)

- The number of ports on your switch varies.You can have very small switches you could have larger switches

- It works at what's called Layer 2
  
- You don't necessarily have lots of ports but in an enterprise environment you typically will you'll have a lot of ports on a switch

- But the big difference between a switch and a hub is a switch has intelligence a switch actually reads what are called the frames received on Ethernet when you send data into Ethernet we're sending what's called a frame. So this device uses what's called a MAC address table.

- They basically receive frames and they have the intelligence to only forward the frames out of the correct ports.

- So if there was a device with a certain MAC address on a port and traffic was received on that port going to that MAC address it would only be sent out of that port rather than out of all ports a hub whereas multiple repeater is dumb when a, when traffic is received on one port it just simply amplifies it or floods it is the term out of all ports so everyone receives that frame here.

- A switch has a MAC address table it has some intelligence and it learns where MAC addresses are in the network and then it will only forward the traffic out of the relevant ports. Based on the destination MAC address and a frame.

- A switch has a MAC address table it has some intelligence and it learns where MAC addresses are in the network and then it will only forward the traffic out of the relevant ports. Based on the destination MAC address and a frame.

- So if traffic comes in  port A it's going to you based on your mac address it's learned that you're connected to port A when traffic arrives in this port B going to your mac address it's only going tobe sent out of this port A whereas if it arrived on a hub it would send it out of all ports.

- One of the features of switches they allow us to connect many devices in our local area network. They are essentially useful   sending traffic within a local area network or LAN. We're not going to try and send it from one network to another which is WAN wide address Network.

  
  ***So a big difference between a switch and a hub is a switch has intelligence.***


## Bridge :
- You can think of as an intermediate device between a switch and a hub

- Bridges which basically did things in software they learned where the MAC addresses were of devices in the network and then someone rebranded their devices as switches because they could learn MAC addresses in hardware.


**Bridge Learns MAC addresses in software ,Switch = Learns MAC addresses much more quickly by using hardware ASICs 
(Application Specific Integrated Circuits).**




## Application Specific Integrated Circuits (ASIC) :
- Used by switches and bridges


## Routers :
![Screenshot 2023-08-26 at 1 48 09 PM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/36da8163-2989-4f08-9f2f-cafe96e7535f)
<br/>

- It allows us to route from one network to another.

- Typically little routers like this allow us to go from our Ethernet LAN, local area network onto the Internet. So to what's   
  called a WAN, wide area network.

![Screenshot 2023-08-26 at 1 50 25 PM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/79bfbec3-709c-4828-8b01-f614cdc5f25f)

- So Ethernet ports this is how we connect our devices to the router (Yellow) and wireless are that sticking out bars (Wifi)
connection to the Internet (Blue port).

***How do you connect to the Internet.Maybe you've got an ADSL connection. service provide gives you this connnetion ,but  if you fiber then WAN connection is Ethernet.***





## Asymmetric Digital Subscriber Line (ADSL) :
- Is a communication technology that offers faster connection speeds over traditional telephone lines than dial-up internet   
  provides. It powers many internet connections worldwide and enabled the broadband internet speeds that drove Web 2.0 and beyond.





## Firewall :

![Screenshot 2023-08-26 at 11 55 41 PM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/3a095101-d62c-45b1-8cfa-cc3d64847b14)Hardware firewall] <br/>

- Firewalls allow us to stop bad people getting into our network so we can restrict who can access our network.
  
- They use what are called firewall rules to permit or deny traffic.
  
- In some ways but I could specify what's called the outside interface and the inside interface.And I do not allow or this firewall does not   allow traffic from the outside interface to the inside interface unless you explicitly allow.
  
- It maybe hardware or software

- You could connect your internet directly to the firewall if you have an Ethernet connection and then to the router and then to the switch where you're inside devices or, or your LAN is all you could connect to the router and then have the firewall behind the router so you either have the firewall in front of the router or behind the router
  
- In many cases you're going to have this behind the router because your ISP may manage the router, or you need a physical connection that's not Ethernet.These devices typically only support Ethernet, router will support other types of technologies such as ADSL or cable as an example.

***Internet connects to the router it connects to the firewall which then connects to your switch in your internal network.***


## Access point :
![Screenshot 2023-08-27 at 3 54 32 PM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/c6e09dcd-cb3a-47ba-b82f-d06d9e1446fe)
<br/>
- An access point is a device, such as a wireless router, that allows wireless devices to connect to a network.
  
- Most access points have built-in routers, while others must be connected to a router in order to provide network access. In either case, 
  access points are typically hardwired to other devices, such as network switches or broadband modems.


## Wireless LAN controller :

- This is used to manage access points.
  
- So the whole idea here is the wireless LAN controller will manage the access points rather than manually managing every one of the access points you manage them through the wireless LAN controller.

- So the wireless LAN controller will manage let's say 100, 500 access points depends on the controller. Depends what it can support.




## Autonomous access point:

-  Don't need a wireless LAN controller to manage it.
  
- If you've only got one access point it makes sense to manage the access point directly
  
- But if you've got 100 of these or 500 of these it's going to be a lot of work to manually configure every one of those access points.

- So rather than doing that you use what's called lightweight access points.



## Lightweight access points :
- Lightweight access points are devices that rely on an external wireless LAN controller (WLC) to work on the same network.




## Intrusion Detection System (IDS) :

- An intrusion detection system simply detects that there's a problem and then alerts you that there's a problem and then you have to do something about it.

- Intrusion Detection Systems typically sits out of band of network traffic so the traffic is going past them but they're not in the flow of 
  traffic they're just getting copies of the traffic to see if there's a problem

## Intrusion Prevention System (IPS) :

- An intrusion prevention system can alert you that there's a problem but also block the attack so it can prevent the attack.
 
- So if someone breaks into your network remotely let's say a hacker it can see that there's malicious activity on the network and then it   
   can block that attacker. So prevent that attacker from gaining access to your network.

- Intrusion Prevention System sits in line with the traffic.The traffic is going through the IPS or intrusion prevention system.When there's   an attack it blocks it so the attacker can't get into your network.

## Binary :

-  Binary is a fundamental building block in networks today.

-  Consists of either 0 or 1 , Binary value = 0 or 1

-  0 is Off and 1 is ON , OFF=0 ON=1

-  You need to know binary to work with access lists or access control lists that allow you to permit or deny traffic based on an IP address.When you configure devices in your network with various IP addresses, you may want to permit one deviceto talk to another device, but   
   then deny a third device from talking to that second device.

- To do that, you permit or deny traffic based on a IP address, whether that's a source IP address or a destination IP address. You're going to match specific IP addresses based on a binary representation.
  
- So determining what a subnet mask is for a specific network, you need to understand binary.

- you will see Binary in IP address like (192.168.1.0) -> 11000000.10101000.00000001.00000000
  

## Hexadecimal :
![Screenshot 2023-08-28 at 9 25 37 AM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/b8e72291-c003-4b4f-ab24-6259c845777a)

- Used in networking all over the place
  
- MAC address of a device it's written in hexadecimal.
  
- IP version 6 addresses are also written in hexadecimal.
  
- Base (16 -sixteen number) [0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F] 

<br/>
![Screenshot 2023-08-28 at 10 04 23 AM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/a52aaf38-6dc8-40a4-ae62-f7bf54868a7c)

![Screenshot 2023-08-28 at 10 04 31 AM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/1c8d34ae-48e6-43f5-b258-a03f8024b645)
<br/>


## Model :
- Reason we have a model is we're taking a complex problem and we're breaking it up into smaller components or smaller pieces.
  
- Divide a problem into smaller parts and then we conquer smaller parts rather than trying to do everything in one go.
  
- Models are used in many places as an example if you're building a house you typically have a blueprint or a model of what the House is going to look like.

- So before you even dig the foundations a model is created or a blueprint is created of what the House is going to look like.It makes a lot more sense to create a blueprint of a house and then have specific people work on specific parts of the building and do what they are good at.

- So as an example a plumber will work on the plumbing an electrician will concentrate on the electricity a bricklayer will concentrate on laying the bricks. But they all work together to correct to the end result which is the house that you want built.

- It's going to be much easier to have a blueprint or a model that everyone works towards to build something rather than them just arriving on site and then saying let's build this house but they don't actually know what the house looks like. You have an electrician working on the plumbing or a plumber working on bricklaying. That's not going to scale very well.

- So we have a model of a network and then we have specific layers or specific components or subunits if you like that people specialize in and concentrate on that layer.

- So manufacturer of fiber cables concentrates on building this to a specification. If you're a application developer you don't worry so much about the physical layer or how data is transmitted from let's say the US to Europe across the Atlantic using light under this ocean. You concentrate on building your application.













## Open Systems Interconnection Model (OSI MODEL) :
![Screenshot 2023-08-29 at 1 43 12 PM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/1694b324-439f-446c-9bf9-f318e9cee3ac)




## Transmission Control Protocol/Internet Protocol (TCP/IP Model) :





## IP Addressing (IPv4) :

- An IP address is a layer three logical address assigned by an administrator. Unlike MAC addresses, which are hard coded or burnt into network interface cards by the manufacturer, an IP address is configured by an administrator.
  
- The IP address may change within a subnet. For example, when using DHCP or dynamic host configuration protocol, an IP address resides at a layer

- Resides in layer of OSI Model

- An IP address is used to uniquely identify a device on the network and is used by routers to determinewhere that device is. So a router routes traffic to a destination IP address based on a hierarchy of network and host.

- Similar way to how houses are uniquely identified in a street. Houses in the street have a unique address. So, for example, ten Oxford Street, in the same way, a host in a network has a unique identifier on that network being its IP address.

- Every device on the Internet has a unique IP address, so there are millions of IP addresses out there and no two devices can have the same IP address for communication on the Internet.

- Move to IP version 6 these days because of IP version for address exhaustion.

- In a lot of organizations today, private IP addresses are used internally and then those addresses are netted or network address translated onto the internet.

- So be aware that in the real world multiple companies may use IP address 10.1 1.1. But those addresses are natted to unique IP addresses when those devices send traffic onto the Internet.
   <br/>
![Screenshot 2023-08-30 at 8 58 20 AM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/9266fbda-4693-44b4-9c6c-49315da51db7) [www.google.com translated to ip (142.250.194.4) by DNS]
<br/>

- DNS is used to convert easy to read names to IP addresses. It's much easier to remember a simple name such as Yahoo.com or Cisco or BBC.co.uk, rather than having to remember the IP address of those domain names.

- Connection less protocol. In other words, there are no sessions formed. When traffic is transmitted, the transmitter simply sends data without notification to the receiver. No status information is sent back from the receiver to the transmitter. It's totally connection.
  
- TCP IP or transmission control protocol, on the other hand is connection orientated.

- 3 way HandShake happens

- IP, on the other hand, doesn't do any of that.Each packet is treated independently of other packets. That's why traffic can take different paths to get to a destination.

- Routers will route the traffic via different paths based on options such as load balancing.Because each packet is independent and IP is a connection less protocol routers can also base routing decisions on different values, such as bandwidth or hop count, but it is possible that packets from one session take divergent or different paths to get to a destination.

- RIP will base its routing decisions on hop count, which is not good, and hence REP is not used that often anymore. OSPF will base it on bandwidth.Other routing protocols will use their own metrics to determine the best path.

- They are based on hierarchical addressing structure in IP version four and IP version six, where we have both a network and host portion as part of the address.

- IP also only gives best effort delivery of packets. There is no guarantee of packet delivery. Any packet could be misdirected, it could be duplicated, or it could be lost in transmission when sent to a destination.

- There is also no data recovery features in IP.If the packet, for example, gets corrupted, the end devices need to handle that and not the routers in between.

***So in summary, IP has no built in sessions, no data recovery, no transmissions.Higher layer protocols such as TCP IP will need to handle dropped packets, corrupted packets, misdirected packets and so forth.IP does not provide those features and relies on higher layer protocols to implement those features***

 ### Format
  - 32 bit address example 10.1 1.1.
    
  - Each of value such as ten is eight bits in size. So in other words, we have x x x x with each x being eight bits in length, also      known as an octet. The total size of the address is 32 bits.
    
  - IP addresses once again have a hierarchical structure to enable routing, which consists of two main parts. We have the network   
    portion of an address and the host portion


   - Network Address Portion also known as the Network ID this identifies a specific network, routers maintain routingtables that    
      contain Network Addresses it's important to realize that routers build their routing tables based on the NetworkAddress and not       on the host address, so they do not route packets from 1 interface to another interface based on IP Addressesthey do their             routing based on Network Addresses,

   - So they will look at the destination IP Address in a packet and match that to a Network Address in their routing table to   
       determine how traffic is routed.

   - So an IP Address consist of the Network portion as well as the host portion which is also called the Host ID,
     
   - This identifies specific end point on a Network such as a server, a printer, a PC, an iPhone, an iPad or some other type of device including IP Phones

   - 


       






## Network Address Translation (NAT):



## Domain Name Server (DNS) :


## UDP



## Ping :





















## Facts / History Lession

- The original ```Ethernet``` was 10 base 5 using this really big yellow cable. So this cable was restricted and distance the signal would attenuate from one end of the cable to the other.

![Screenshot 2023-08-26 at 9 21 31 AM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/d1ab3f63-584d-46c1-b0a9-7c79334e1c86)


- And what they developed were ```Repeaters```.

![Screenshot 2023-08-26 at 9 23 03 AM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/0f22b045-b412-45e8-90e7-4a83434cdc76) (Motorola Mototrbo DR3000 Digital Repeater (450 - 527 Mhz))

<br/>


- We are sharing the air now Wi-Fi 6 does try and implement some very clever stuff to allow multiple devices to talk at the same time. So it kind of approaches a switch but it's still acting as a hub.


- Repeater -> Hubs -> Bridge -> Switches

- Routers and switches, have specific types of chips known as `ASICs` or `Application Specific Integrated Circuits`
- Three numbering Decimal , Binary , HexaDecimal
  <br/>
![Screenshot 2023-08-28 at 10 06 39 AM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/9d5f218e-0693-42e8-b5b8-4a3f4f4670fc)
![Screenshot 2023-08-28 at 10 06 53 AM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/dcf0442d-34cd-49ee-a646-35e94b6238c7)
<br/>


<br/>
![Screenshot 2023-08-28 at 10 16 29 AM](https://github.com/SiddharthMathurDeveloper/Networking/assets/133037456/cdff8ada-8b90-48bb-800d-74e7982fa377)
<br/>




***The most common WAN technology and LAN technology tonight today is Ethernet***






