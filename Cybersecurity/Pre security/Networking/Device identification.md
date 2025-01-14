A device can be recognized using two things, its **IP adress (Internet Protocol)** or it's **MAC adress** (Media Access Control).

# IP - Internet Protocol
An IP address is a number divided into 4 octets, calculated using IP addressing & subnetting. It can change from device to device but can not be the same for two of them within the same network.
Devices on the same network can communicate with each other using their **private IP adresses**. But to communicate with internet you need a **Public IP addresses**, which is given by your **I**nternet **S**ervice **P**rovider (**ISP**).

Due to a lack of available public address using the IPv4 (2^32 address), we now have IPv6 allowing 2^128 which is also more efficient
![[ipv6.png]]
# MAC (Media Access Control)
Assigned at the build of the motherboard of your device, it is an unique identifier of it with 12 characters, 6 for your vendor, 6 for your unique network interface address. However a MAC address can be faked (or "**spoofed**") to break some security designs, making believe a firewall that it is a part of allowed devices.

# Ping
Ping is a fundamental network tool using **ICMP** (Internet Control Message Protocol) to determine the performance of a connection between devices
#tryhackme 