
# What is Networking?
  
  * Exchanging or Transporting the data between Nodes using the links
    * [nodes: Physical Devices]  [node: computer or mobile device]
    * [links: Path with data travels]  [links: data cable]


    # Types of Networking?
        
      * LAN [local area network : jio fibre]
      * MAN [MetroPolitan network: University wifi]
      * WAN [city network : Jio mobile internet]

# Network Topologies?

  * The Blueprint of the network connectivity.


    # Types of  Network Topologies?

      * Point to Point
      * Bus
      * Ring
      * Star
      * Tree [combination of bus and star]
      * Mesh 
      * Hybrid [combination of point and point and ring and star]
        
      
# What are Protocols?
  
  * An Established set of rules to determine how data is transmitted between different nodes in same link.
     

    # Types of Protocols:
    
      * TCP_IP Model: Transport Control Protocol - Internet Protocol  
          
        * refer learn_devops/TCP-IP.png  

      * OSI Model: Open System Interconnect   
          
        * refer learn_devops/OSI.png  
           
      *  Example of OSI layers in real life
        
        *  [Physical Layer - File in my c drive]
        *  [Data Link Layer - i have connected to Jio data]
        *  [Network Layer - i have connected to Jio Network]
        *  [Transport Layer - using above network file is transferring in transport layer]
        *  [Session Layer - We have joined Zoom session]
        *  [Presentation Layer - File is Getting presented]
        *  [Application Layer - We are using Zoom application]
              

    # How data is Connected and through which devices?
    
       *  [Physical Layer - Hubs [where data is transmitted to all the device it is connected] ]
       *  [Data Link Layer - Switches [where data is transmitted to only the info provided device] ]
       *  [Network Layer - Routers [IP address and ports] ]
       *  [Transport Layer - [TCP and UDP] ]
       *  [Session Layer - Session ID [where every session will have one each unique session id] ]
       *  [Presentation Layer - .mp4, .mp3, png, .jpg [converting the segmented data to presentable format, providing a shape for the data] ]
       *  [Application Layer - user interactive]



    # How data is Secured?
       * it is secured using Encryption and Decryption
       
       *  [Physical Layer - Bits [0/1]]
       *  [Data Link Layer - Frame]
       *  [Network Layer - Packet]
       *  [Transport Layer - Segments]
       *  [Session Layer - Data]
       *  [Presentation Layer - Data]
       *  [Application Layer - Data]
  

    # IPV4 and IPV6?

    # IPV4: a combination of 32 bits with 4 octets. 

       * 8*4 = 32 [192.168.29.230] [xxxxxxxx.xxxxxxxx.xxxxxxxx.xxxxxxxx] [0/1]
    
# Class of IPV4?
   
   * Class A : 1 to 126   [10.x.x.x=0-255] [these are the private address of IPV4 in class A]
   * Class B : 128 to 191 [172.(16-31).x.x=0-255] [these are the private address of IPV4 in class B]
   * Class C : 192 to 223 [192.168.x.x=0-255] [these are the private address of IPV4 in class C]
   * Class D : 224 to 239 [broad casting]
   * Class E : 240 to 255 [r&d purpose]
   * 127???? : Loop Back IP Address [when u ping it will re-direct back to our Ip address itself.]

# Public and Private IP address:
   * Ip address which are globally accessible.
  

# CIDR and Sub netmask:

   * CIDR: classless interdomain routing.
       * Ex: need 1000pc , with class A private IP address   
       * with the use of CIDR , 
       * step-1: class A 10.x.x.x=0-255 so we get only 255 computers, so we do
       * step-2: 2^10=1024, a near number of computers
       * step-3: 32-19=22
       * step-4: 10.1.0.0.0/22, keeps on going.. which gets us 1024 computers 
       
# Subnet Mask:

  * dividing the IP address by [network bit and host bit] 
   
    # how do we find the subnet mask address?

       *  for ex: 10.0.0.0/22 the subnet mask will be 22 means 22[1] and 10[0]
       *  22 = 11111111.11111111.11111100.00000000 = 255.255.252.0 [this is the subnet mask ]
       *  Now which is host and network name is 
       *  The number which is changing dynamically, is Host bit
       *  The number which is Constant, is Network bit
       *  10.x.x.x/22 [ [10]-network bit and [x.x.x]-host bit ]

# IPV6: 
   * Its just an Temporary address in case IPV4 gets over, 
   * it is an 128 bit address

# MAC address:
   * An physical address with 64 bit address. 
   * An Permanent address for every Machine, which doesn't change.

