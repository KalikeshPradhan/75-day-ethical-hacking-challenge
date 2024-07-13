# Ports
A port is a virtual point where network connections start and end. They help distinguish different types of traffic coming in and out of a device. Ports are identified by port numbers, which range from 0 to 65535.

## Well-Known Ports
- **Range**: 0 to 1023
- These ports are reserved for well-known services and protocols. Some examples include:
  - **HTTP**: Port 80
  - **HTTPS**: Port 443
  - **FTP**: Port 21
  - **SSH**: Port 22
  - **DNS**: Port 53
- These ports are often used by system processes or by programs executed by privileged users.

## Registered Ports
- **Range**: 1024 to 49151
- These ports are registered by software developers to be used by specific applications. They are not as universally reserved as well-known ports, but they are standardized to prevent conflicts.
- Examples:
  - **MySQL**: Port 3306
  - **PostgreSQL**: Port 5432

## Dynamic or Private Ports
- **Range**: 49152 to 65535
- These ports are not assigned to any specific service and can be used freely by applications for temporary or private purposes. These are often used for ephemeral ports, which are temporary ports assigned by the operating system to client applications when they initiate outbound connections.

## Port Numbers Usage
- Organizations and network administrators assign ports to various services and applications to manage traffic effectively.
- For example:
  - Web servers typically use ports 80 (HTTP) and 443 (HTTPS).
  - Email servers might use ports like 25 (SMTP), 110 (POP3), and 143 (IMAP).
- Network devices such as routers and firewalls are configured to allow or block traffic based on port numbers to enhance security and control over data flow.

## Summary
Ports are crucial for network communication, providing the means to separate different types of traffic and services on a single device. Understanding and managing port numbers is essential for network security and efficient data transmission.

### Types of IP Address
- **Public**: An IP address that is accessible over the internet.
- **Private**: An IP address used within a private network, not accessible from the internet.
- **Static**: An IP address that remains constant and does not change.
- **Dynamic**: An IP address that can change periodically, assigned by a DHCP server.

### Firewalls
Firewalls are security systems that monitor and control incoming and outgoing network traffic based on predetermined security rules. They act as a barrier between a trusted network and an untrusted network.

### Port Forwarding
Port forwarding is a technique used to redirect communication requests from one address and port number combination to another. It allows external devices to access services on a private network.

### Data Packets and Frames
- **Data Packets**: Units of data formatted for transmission over a network.
- **Frames**: Data packets encapsulated with necessary header information, used in data link layer communication.

### Three-Way Handshake
The three-way handshake is a process used in TCP/IP networks to establish a connection between a client and a server. It involves three steps:
1. **SYN (Synchronize)**: The client sends a SYN packet to the server to initiate the connection.
2. **SYN-ACK (Synchronize-Acknowledge)**: The server responds with a SYN-ACK packet, acknowledging the client's request.
3. **ACK (Acknowledge)**: The client sends an ACK packet back to the server, confirming the connection is established.

