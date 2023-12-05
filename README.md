# campus_area_network

## Campus Area Network Overview

### Network Topology Creation

1. **Creating a Topology:** Design a topology that mirrors your campus structure.
2. **Network Segmentation:** Establish three networks based on campus requirements.
3. **Multilayer Switch:** Connect multiple networks to a router via a multilayer switch.
4. **Internet Connection:** Connect the router to a wireless router for internet access.


<center>
    <p>
        <img src="https://github.com/Krish9575/campus_area_network/assets/107667057/7281d325-e6d5-4ffc-9c7a-152839df1f57" alt="image">
    </p>
</center>



### Configuration

5. **Device Configuration:** Set up each device with IP addresses and default gateways.
   - Essential configurations for SRMIST Delhi NCR Campus networks: LAB, LIBRARY, LABS.

## Data Access to External Network

- Access external networks, like Google.com, by typing the IP address in the web browser or using the ping command. 
- IP addresses are used for communication, and the application redirects the user to the respective webpage.

## Packet Transmission and Header Information

1. **Flow of Packet from Source to Destination:**
   - Example: User (PC with IP 192.168.1.6) wants to access Google.com (IP 192.168.0.100).
   - Packet path: PC -> Switch -> Router -> Wireless Router (Internet) -> Google.com.
   - Successful response from destination back to the source.

2. **Packet Transmission and Header Information:**
   - Refer to the TCP/IP model for encapsulation and decapsulation of data.
   - Layers: Application, Transport, Internet, Network Access.

## Packet Sniffer

- Use packet sniffer to retrieve header information without affecting packet transmission.
- Sniffing between the multilayer switch and router to analyze incoming and outgoing data.
- Retrieve information about protocol headers (UDP, TCP, SMTP, etc.).
- Essential information includes source/destination addresses, version, header length, flags, checksum, TTL, and fragment fields.

### Outcome of Packet Sniffer

- Packet sniffing does not affect transmission but can expose crucial information.
- Attacker may use this information to pose as a legitimate device, request sensitive data, and potentially compromise security.
- The goal is to highlight the importance of securing data transmission to prevent unauthorized access and potential threats.

------------************************************--------------
