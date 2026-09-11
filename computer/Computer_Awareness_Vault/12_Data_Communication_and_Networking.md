# 12. Data Communication and Networking

Back to [[00_Index]]

### Fundamentals of Data Communication
* **Signal Types**:
  * *Digital Signal*: Binary discrete form ($0$ or $1$).
  * *Analog Signal*: Continuous radio/voltage wave transmission.
  * *Hybrid Signal*: Combined properties of digital and analog signals.
* **Communication Channels**:
  * *Simplex*: Unidirectional communication (e.g., TV, Radio, Keyboard).
  * *Half Duplex*: Bidirectional communication, but only one direction at a time (e.g., Walkie-Talkie).
  * *Full Duplex*: Simultaneous bidirectional communication (e.g., Mobile Phones).

### Transmission Media
* **Guided (Wired)**:
  * *Twisted Pair (Ethernet)*: Insulated copper wires twisted together.
  * *Co-axial Cable*: Inner single conductor wrapped in PVC/Teflon insulator; used in Cable TV.
  * *Fibre Optic Cable*: Glass/plastic core transmitting light pulses at high speeds; unaffected by electromagnetic interference.
* **Unguided (Wireless)**:
  * *Radio Waves*: Omnidirectional sky/ground propagation.
  * *Microwaves*: Unidirectional high-frequency waves ($0.3 - 300\text{ GHz}$).
  * *Infrared*: Short-range line-of-sight signal; blocked by solid objects (e.g., TV remotes).
  * *Satellite Communication*: Long-distance global microwave relay systems.

### Network Categories
* **PAN**: Personal Area Network (Short range, e.g., Bluetooth, ZigBee).
* **LAN**: Local Area Network (Single site up to 1 km, e.g., Office, Home).
* **MAN**: Metropolitan Area Network (Spans a town or city, e.g., Cable TV networks).
* **WAN**: Wide Area Network (Spans countries/globally, e.g., The Internet).

### Network Hardware Devices
* **Repeater**: Amplifies signals over long distances to restore original strength.
* **Hub**: Multiport repeater broadcasting incoming packets to all connected ports.
* **Switch**: Multiport bridge forwarding packets directly to specific intended recipient ports.
* **Gateway**: Protocol converter connecting two dissimilar network protocols.
* **Router**: Analyzes, routes, converts, and directs data packets between networks.
* **Bridge**: Filters and splits traffic across two LAN segments.
* **Modem**: Modulates digital signals to analog for telephone lines, and demodulates back.

### Topologies
* **Bus**: Single central cable line connecting all nodes.
* **Star**: Peripheral nodes connected directly to a central hub/switch node.
* **Ring**: Nodes linked in a closed loop using tokens (FDDI, Token Ring).
* **Mesh**: Fully interconnected dedicated point-to-point links between all nodes.
* **Tree**: Hierarchical inverted structure with root central server nodes.

### The OSI 7-Layer Model
| Layer # | Layer Name | Key Functionalities |
| :---: | :--- | :--- |
| **7** | **Application Layer** | User interface, file transfer, login authentication, packet filtering. |
| **6** | **Presentation Layer** | Data formatting, translation, encryption, and decryption. |
| **5** | **Session Layer** | Establishes, synchronizes, manages, and terminates system sessions. |
| **4** | **Transport Layer** | End-to-end data segmentation, accuracy, and flow control (TCP). |
| **3** | **Network Layer** | Signal routing, IP addressing, packet switching. |
| **2** | **Data Link Layer** | Assembles frames, MAC addressing, physical error detection/correction. |
| **1** | **Physical Layer** | Converts raw data bits into physical electrical/optical signals. |
