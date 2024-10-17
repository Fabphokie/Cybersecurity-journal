# Research Task: OSI Model and Network Topologies

## a) OSI Model and Its Layers

The **OSI (Open Systems Interconnection)** model is a conceptual framework used to standardize networking functions in seven layers. Each layer interacts with the one above and below it. Below is an outline of each layer:

### 1. Physical Layer (Layer 1)
- **Description**: Responsible for the physical connection between devices and the transmission of raw data.
- **Functions**: Transmits bitstreams over physical media.
- **Examples**: Ethernet cables, USB, Bluetooth.

### 2. Data Link Layer (Layer 2)
- **Description**: Manages node-to-node data transfer and error detection.
- **Functions**: Error correction, flow control, MAC addresses.
- **Examples**: Ethernet, MAC addresses.

### 3. Network Layer (Layer 3)
- **Description**: Handles data packet routing between different networks.
- **Functions**: Packet forwarding, addressing, routing.
- **Examples**: IP addresses, Routers.

### 4. Transport Layer (Layer 4)
- **Description**: Ensures reliable data delivery.
- **Functions**: Flow control, segmentation, error recovery.
- **Examples**: TCP, UDP.

### 5. Session Layer (Layer 5)
- **Description**: Manages sessions between devices.
- **Functions**: Establishes, maintains, and terminates communication sessions.
- **Examples**: NetBIOS, RPC.

### 6. Presentation Layer (Layer 6)
- **Description**: Translates data for the application layer.
- **Functions**: Data encryption, compression, and formatting.
- **Examples**: SSL, JPEG, GIF.

### 7. Application Layer (Layer 7)
- **Description**: Closest to the user, facilitates interaction with the network.
- **Functions**: Provides network services to end-user applications.
- **Examples**: HTTP, FTP, SMTP.

---

## b) Network Topologies: Types, Advantages, and Disadvantages

A network topology is the arrangement of nodes and links in a network. Below are the main types of topologies, along with their pros and cons.

### 1. Bus Topology
- **Description**: All devices share a single communication line.
- ![Bus Topology](https://upload.wikimedia.org/wikipedia/commons/e/e4/Bus_topology.png)
- **Advantages**:
  - Easy to install and extend.
  - Cost-effective for small networks.
- **Disadvantages**:
  - Troubleshooting is difficult.
  - A failure in the main cable can bring down the entire network.
  - Limited cable length and number of devices.

### 2. Star Topology
- **Description**: All devices are connected to a central hub.
- ![Star Topology](https://upload.wikimedia.org/wikipedia/commons/4/42/Star_network_topology.png)
- **Advantages**:
  - Easy to install and configure.
  - Centralized management.
  - Failure of one device doesn’t affect others.
- **Disadvantages**:
  - Hub failure can disrupt the entire network.
  - Higher costs due to more cables.

### 3. Ring Topology
- **Description**: Devices are connected in a circular pattern.
- ![Ring Topology](https://upload.wikimedia.org/wikipedia/commons/2/26/Ring_network.svg)
- **Advantages**:
  - Easier to isolate faults.
  - Handles high traffic better than bus topology.
- **Disadvantages**:
  - A break in the loop can bring down the network.
  - More complex to install.

### 4. Mesh Topology
- **Description**: Every device is connected to every other device.
- ![Mesh Topology](https://upload.wikimedia.org/wikipedia/commons/a/a4/Mesh_network_diagram.svg)
- **Advantages**:
  - High fault tolerance.
  - Simultaneous data transmission across multiple paths.
- **Disadvantages**:
  - Expensive due to lots of cabling.
  - Complex setup and maintenance.

### 5. Tree Topology
- **Description**: Combines star and bus topologies, with groups of star networks connected to a bus.
- ![Tree Topology](https://upload.wikimedia.org/wikipedia/commons/9/9d/Tree_Topology.png)
- **Advantages**:
  - Scalable and easy to add new devices.
  - Fault isolation.
- **Disadvantages**:
  - Failure of the backbone can bring down the network.
  - Complicated configuration and maintenance.

### 6. Hybrid Topology
- **Description**: Combination of two or more different types of topologies (e.g., star-bus, star-ring).
- **Advantages**:
  - Flexible and scalable.
  - Can overcome limitations of individual topologies.
- **Disadvantages**:
  - Complex to design and implement.
  - Expensive due to additional hardware.

### 7. Point-to-Point Topology
- **Description**: Direct connection between two devices.
- **Advantages**:
  - Simple and fast communication.
  - High-speed, reliable connection.
- **Disadvantages**:
  - Limited to two devices.
  - Not suitable for large networks.

---

**Note**: Diagrams and more details can be added in a final presentation format if required.
