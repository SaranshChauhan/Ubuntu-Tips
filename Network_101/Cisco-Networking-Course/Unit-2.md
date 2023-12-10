## Module 5-7:

## 1. TCP/IP Model: `Protocol Model`
![image](https://github.com/IOxCyber/CyberEssentials/assets/40174034/8a2c282d-d03a-4912-8d23-6bc2aeb756df)

## 2. OSI Model: `Reference Model`
![image](https://github.com/IOxCyber/CyberEssentials/assets/40174034/3212eb9a-0af7-44d1-a617-38c2d71eefe8)

## 3. Ethernet Frame: `Solely used in LAN for communication`
Ethernet is technology commonly used in local area networks. Devices access the Ethernet LAN using an Ethernet Network Interface Card (NIC). Each Ethernet NIC has a unique address permanently embedded on the card known as a Media Access Control (MAC) address. The MAC address for both the source and destination are fields in an Ethernet frame.
![image](https://github.com/IOxCyber/CyberEssentials/assets/40174034/0be93456-ef9b-401d-a607-582a5a6b2c36)

**Note**: `Data is encapsulated Data which is IPv4 / IPv6 Packet.`

![image](https://github.com/IOxCyber/CyberEssentials/assets/40174034/066ae353-71fc-4341-b2f5-6ac52f87b2fa)

## 4. IP Packet Structure:
An IP packet consists of a header and a data payload. The IP header contains various fields that provide necessary information for routing and delivery. Here is a breakdown of the key fields within the IP header:
```
Version (4 bits):
Identifies the version of the IP protocol in use. For example, IPv4 uses version 4.

Header Length (4 bits):
Specifies the length of the IP header in 32-bit words.

Type of Service (8 bits):
Includes fields for Differentiated Services Code Point (DSCP) and Explicit Congestion Notification (ECN), allowing for quality of service and congestion management.

Total Length (16 bits):
Represents the total length of the IP packet, including both the header and the data.

Identification (16 bits), Flags (3 bits), Fragmentation Offset (13 bits):
Used for fragmentation and reassembly of IP packets if needed.

Time-to-Live (TTL) (8 bits):
Indicates the maximum number of hops the packet can take before being discarded.

Protocol (8 bits):
Identifies the higher-layer protocol (e.g., TCP, UDP) used in the data part of the IP packet.

Header Checksum (16 bits):
Ensures the integrity of the IP header during transmission.

Source IP Address (32 bits) and Destination IP Address (32 bits):
Specify the source and destination devices' IP addresses, respectively.

Options (Variable Length):
May include additional information or instructions related to the IP packet.

Padding (Variable Length):
Added to ensure that the total length of the IP header is a multiple of 32 bits.

Data (Payload):
Carries the actual data being transmitted. The size and format of the data part depend on the higher-layer protocol identified in the "Protocol" field.
```
![image](https://github.com/IOxCyber/CyberEssentials/assets/40174034/bb194251-2f8d-4a11-aabb-a175aee92325)
![image](https://github.com/IOxCyber/CyberEssentials/assets/40174034/e3e97d57-6423-4f48-bcfa-cbb6ad826f8b)
`4 Bytes x 6 = 24 Headers Bytes`
`Data Varies the Size`