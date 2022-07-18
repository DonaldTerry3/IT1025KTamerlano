## Donald Terry / July 17, 2022

## Executive Summary 
Include your executive summary here...

## Lucidchart

## Introduction to Networking

### Data Transmission
#### Packet:Unit of data 
#### Packet-Switching:Technology that allows packets of data to be routed based on destination address 
#### IP Address:Unique identifying number 

#### DNS:Directory of IP address common names.

#### Protocol:Set of rules to allow devices to communicate 

### Networking Hardware
#### Switch vs. Hub
Switches are considered as intelligent devices. Switches sends packets to only that port which has the requirement for same. Switches identifies the device using their MAC address. Whereas hub sends packets to every ports, hence increasing unnecessary traffic. Switches maintain security whereas hubs lacks in maintaining the same.
#### Router vs. Switch and Hub
Hubs and switches allow the connection of multiple components to form a local area network while routers are needed for bridging computers and peripherals on a local network to another network or the Internet.
### Network Topologies
Single point of failure is where an array of servers is networked through a single network switch. If the switch failed or simply became disconnected from its power source, all of the servers connected to that switch would become inaccessible from the rest of the network. Topology defines the structure of the network of how all the components are interconnected to each other. There are two types of topology: physical and logical topology. Physical topology is the geometric representation of all the nodes in a network. A wireless mesh network is created through the connection of wireless access point (WAP) nodes installed at each network user's locale. An infrastructure topology is used to extend a wired LAN to include wireless devices. Wireless mesh is better because it manages high amounts of traffic, because multiple devices can transmit data simultaneously.
#### Single point of Failure
#### Infrastrucutre vs. Wireless Mesh
### Network Design
This diagram of infrastructure topology shows the devices communicating with the wired LAN via base stations called an AP, which acts as a bridge between wired and wireless LANs.
### NSA/CSS

###Protocol is an established set of rules that determine how data is transmitted between different devices in the same network. Essentially, it allows connected devices to communicate with each other, regardless of any differences in their internal processes, structure or design.

## Cybersecurity and Encryption

### Information Systems Security

#### Security Triad
Confidentiality is roughly equivalent to privacy. Confidentiality measures are designed to prevent sensitive information from unauthorized access attempts. It is common for data to be categorized according to the amount and type of damage that could be done if it fell into the wrong hands. More or less stringent measures can then be implemented according to those categories. Passwords and user names can be an exapmle.
Integrity involves maintaining the consistency, accuracy and trustworthiness of data over its entire lifecycle. Data must not be changed in transit, and steps must be taken to ensure data cannot be altered by unauthorized people (for example, in a breach of confidentiality). Multistep authentication is an example.
Availability means information should be consistently and readily accessible for authorized parties. This involves properly maintaining hardware and technical infrastructure and systems that hold and display the information. A website for the information to be stored is an example. 
#### Authentication
#### ACL and RBAC
#### Ciphertext, Public Key and Private Key
#### Public Key Cryptography
Only the owner of the private key can encrypt data so that the public key decrypts it; meanwhile, anyone can encrypt data with the public key, but only the owner of the private key can decrypt it.
### Cryptography
#### Encryption
#### Frequency Fingerprint
#### Polyalphabetic Cipher
Caesar method is encrypted by shifting 3 letters in message and the polyalphabetic cipher is encrypted by shifting letters according to position in alphabet and is repeated alongside message. 
#### Polyalphabetic Example

#### Brute-Force
How to prevent Brute Force:
-Use long, unique passwords. Brute forcing becomes exponentially harder with longer passwords. You can thwart dictionary attacks by making your passwords more unique. If in doubt, use a password manager to automatically generate and save random passwords for each site.

-Secure remote desktop connections as much as possible. Remote desktop is a popular way for attackers to get access to your computer. Leave remote desktop off as much as possible. When it’s on, use an extremely strong password.

-Use two-factor authentication. A brute-force attack is far more difficult when a correct password isn’t enough to log into an account. With 2FA, users need their phone or a physical security key to log into their accounts. This makes your account far more secure.

-Use rate limiting. If you run a server, make sure that hackers can’t try passwords very fast. They might get discouraged and give up if the delay is long enough.

-Don’t use account lockouts. If you own a website, it might make sense to lock accounts after a certain number of incorrect attempts. However, this lets an attacker perform a denial of service attack by locking out lots of accounts.

-Secure SSH appropriately. Enable fail2ban, disable password logins (in favor of SSH keys), and turn off root login from SSH.

-Hash and salt your passwords with modern algorithms. MD5 or another very basic hash algorithm is hardly better than nothing. Use a modern hash function and salt to prevent rainbow table attacks.
## Conclusion
Include your professional conclusion here...

