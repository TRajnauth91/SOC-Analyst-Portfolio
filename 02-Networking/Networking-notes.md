# Network notes


## Network/Subnet/LAN
A network is simply a group of computers. The internet as a whole is a network, but smaller networks also exist and are called Subnets. There are state wide networks, city wide networks, and even networks as small as your home that could include your phone, laptop, televisions, or any computer that functions for the sake of your home. These subnets that encompass your home, or that corporations use are called a LAN (Local Area Network). 
One thing to note is that a unique device ID can be exposed at any level of these networks, while also being invisible to others.

## What is MAC? (Your computer device ID)
MAC stands for Media Access Control. Every computer has one, this is how your phone is distinguishable from your laptop, and is unique identifying characters that can't be shared between multiple computers.

## IP (Internet Protocol)
When you connect your device to a network or subnet, your computer gets another unique ID for THAT network. That unique ID for your device on that network is called an IP address. For example, when you want to connect your phone to your home network, you connect to your router, which assigns an IP address for your phone you connected, which is a separate ID than your phones MAC address. Also worth mentioning that your router also has its own IP address, which it gets from your Internet Service Provider (ISP). It is how you can send and receive information from the internet, while simultaneously acting as security guard not letting just any bit of information in.
A common IP address could look something like 192.168.1.1
Note that this IP address can be the same as someone else's if they are on a different subnet. So you and someone living down your block might both have a phone showing the same IP address, but because you are on different subnets, they don't conflict with each other.

## VPN (Virtual Private Network)
a VPN is a network of computers, but privatized in the same way as your home network (connected via a router). The key advantage of a VPN compared to your home network is that you don't need to be physically tethered to your router, meaning you can be somewhere remote, but still have that level of privacy from the internet. It functions quite the same as a router, sending and receiving information from a computer to another subnet, but is done virtually through a software program. Using programs and rules set up, it knows what information can be sent and received, while turning away unwanted traffic.

## Web Addresses
We know every router on the internet is assigned a special IP address, and the computers that run a companies website (web servers) also have routers that have their own IP address. So when you type in a domain like "Microsoft.com" into your browser, you are communicating with the internets "address book" which knows that the IP of Microsofts services is ___.__._._ and routes you to their servers. Using the Domain Name System (DNS) it is much easier for you to remember where you want to go rather than knowing the IP address for every website you want to go to. It's like creating a contact for a friend, you don't spend the time memorizing all of your friends numbers, you just call "Nathan". That's what DNS is in essence, a contact folder pairing IP addresses to web addresses.
