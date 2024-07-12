
# Day 3 - Networking Fundamentals

## Key Topics Covered:

### What is Networking?
Networking involves connecting multiple computers and devices to share resources and information. It's the backbone of modern communication, allowing devices to communicate and exchange data.

### What is the Internet?
The Internet is a global network of interconnected computers that communicate through a standardized set of protocols. It enables access to information, communication, and services across the world.

### Network Devices:

- **Switch:** A switch is a device that connects multiple devices on a local network and uses MAC addresses to forward data to the correct destination.
- **Router:** Routers connect different networks and direct data packets between them. They use IP addresses to determine the best path for data transmission.
- **Hub:** A hub is a basic networking device that connects multiple Ethernet devices. It broadcasts data to all connected devices, regardless of the intended recipient.

### IP Address:
An IP address is a unique identifier assigned to each device on a network. It allows devices to locate and communicate with each other over the Internet.

### MAC Address:
A MAC address is a hardware identifier assigned to network interfaces. It uniquely identifies a device on a local network and is used by switches to forward data.

### ICMP (Internet Control Message Protocol):
ICMP is used for diagnostic and error-reporting purposes. It helps manage and control the flow of data in a network by sending messages about network conditions.

### Types of Networks:

- **LAN (Local Area Network):** Covers a small geographic area, like a home or office.
- **WAN (Wide Area Network):** Covers a large geographic area, connecting multiple LANs, such as the Internet.
- **MAN (Metropolitan Area Network):** Spans a city or a large campus.

### Network Topology:
The layout or arrangement of devices in a network. Common topologies include star, bus, ring, and mesh, each with its advantages and disadvantages

## 1. Bus Topology

In a Bus topology, every computer and network device is connected to a single cable. When it has exactly two endpoints, it is called a Linear Bus topology.

### Advantages:
- Easy to install and maintain.
- Requires less cable length than a star topology.

### Disadvantages:
- The entire network shuts down if there is a break in the main cable.
- Difficult to troubleshoot.
- Not suitable for networks with heavy traffic.

![Bus Topology](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a2/Bus_network_topology.png/220px-Bus_network_topology.png)

## 2. Star Topology

In a Star topology, all the devices are connected to a single central hub. Each device has a dedicated point-to-point connection to the hub.

### Advantages:
- Easy to install and manage.
- Failure of one link does not affect other devices.
- Easy to add new devices.

### Disadvantages:
- Requires more cable length compared to bus topology.
- If the central hub fails, the entire network goes down.

![Star Topology](https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/Star_Topology.png/220px-Star_Topology.png)

## 3. Ring Topology

In a Ring topology, each device has exactly two neighbors for communication purposes. All messages travel through a ring in the same direction.

### Advantages:
- Data is transferred quickly without a collision.
- Easy to troubleshoot.

### Disadvantages:
- A failure in any cable or device breaks the loop and can take down the entire network.
- Difficult to reconfigure and add new devices.

![Ring Topology](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f7/Ring_network.svg/220px-Ring_network.svg.png)

## 4. Mesh Topology

In a Mesh topology, each device is connected to every other device in the network. Mesh networks can be fully connected or partially connected.

### Advantages:
- Highly reliable and redundant.
- Failure of one link does not affect the entire network.
- Data can be transmitted simultaneously.

### Disadvantages:
- Expensive due to the high number of cables and ports required.
- Complex and difficult to install and manage.

![Mesh Topology](https://upload.wikimedia.org/wikipedia/commons/thumb/2/20/Mesh_network_diagram.svg/220px-Mesh_network_diagram.svg.png)

## 5. Tree Topology

A Tree topology combines characteristics of both Star and Bus topologies. It consists of groups of Star-configured networks connected to a Linear Bus backbone.

### Advantages:
- Supports future expandability.
- Easy to manage and maintain.

### Disadvantages:
- If the backbone line breaks, the entire segment goes down.
- Difficult to configure and more expensive than other topologies.

![Tree Topology](https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/Tree_topology.svg/220px-Tree_topology.svg.png)

## 6. Hybrid Topology

A Hybrid topology is a combination of two or more different types of network topologies. It aims to leverage the advantages of the combined topologies.

### Advantages:
- Flexible and scalable.
- Can be designed as per the requirements.

### Disadvantages:
- Complex to design and implement.
- Expensive to maintain.

![Hybrid Topology](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7e/NetworkTopology-Combined.svg/220px-NetworkTopology-Combined.svg.png)

## Conclusion

Each network topology has its own set of advantages and disadvantages. The choice of topology depends on the specific needs and scale of the network, as well as considerations for cost, maintenance, and future scalability.

