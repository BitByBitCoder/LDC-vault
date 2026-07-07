# 08 — Networking
[[💻 Computer Knowledge — INDEX|← Back to Index]]

---

## Questions From Your Papers

| Question | Answer |
|----------|--------|
| HUB is a | **Broadcast device** |
| DSL (Digital Subscriber Line) is | **Broadband connection** |
| Protocol is | **Set of rules governing communication between peers** |
| Client-server — server does | **Stores and manages shared resources** |
| In inventory control, computers mainly | **Monitor stock levels and manage reordering** |

---

## Network Types

| Type | Full Form | Coverage |
|------|-----------|---------|
| **LAN** | Local Area Network | Building / Campus |
| **MAN** | Metropolitan Area Network | City |
| **WAN** | Wide Area Network | Country / World |
| **PAN** | Personal Area Network | Personal devices — Bluetooth |
| **Internet** | — | Global |

---

## Network Topologies

| Topology | Shape | Key Feature |
|---------|-------|-------------|
| **Bus** | Single cable | All devices on one line |
| **Star** | Hub at center | All connect to central hub |
| **Ring** | Circle | Data travels in one direction |
| **Mesh** | All interconnected | Most reliable — most cable |
| **Tree** | Hierarchical | Mix of bus and star |

---

## Network Devices

| Device | Function |
|--------|---------|
| **HUB** | **Broadcasts to ALL devices** (dumb — no filtering) |
| **Switch** | Sends data to SPECIFIC device (smarter than hub) |
| **Router** | Connects different networks — routes packets |
| **Modem** | Converts digital ↔ analog for telephone lines |
| **NIC** | Network Interface Card — connects device to network |
| **Bridge** | Connects two similar networks |
| **Gateway** | Connects two different types of networks |
| **Repeater** | Amplifies/regenerates signal over long distances |
| **Access Point** | Wireless connection point (WiFi) |

### Hub vs Switch vs Router
| Hub | Switch | Router |
|-----|--------|--------|
| Broadcasts to all | Sends to specific device | Connects different networks |
| Layer 1 device | Layer 2 device | Layer 3 device |
| Unicast/Multicast/Broadcast | Unicast | Routes between networks |

---

## Network Models

| Model | Layers | Purpose |
|-------|--------|---------|
| **OSI Model** | 7 layers | Reference model |
| **TCP/IP Model** | 4 layers | Internet model |

### OSI 7 Layers (Top to Bottom)
```
7 — Application
6 — Presentation
5 — Session
4 — Transport
3 — Network
2 — Data Link
1 — Physical
```
Memory trick: **All People Seem To Need Data Processing**

---

## Connection Types

| Type | Description |
|------|-------------|
| **Broadband** | High-speed internet (DSL, Cable, Fiber) |
| **DSL** | Digital Subscriber Line — **broadband over phone line** |
| **WiFi** | Wireless LAN (IEEE 802.11) |
| **Bluetooth** | Short-range wireless (PAN) |
| **Ethernet** | Wired LAN connection |
| **Dial-up** | Old — slow — uses phone line |
| **Fiber Optic** | Fastest — uses light |

---

## Protocols

| Protocol | Port | Purpose |
|---------|------|---------|
| HTTP | 80 | Web pages |
| HTTPS | 443 | Secure web |
| FTP | 21 | File transfer |
| SMTP | 25 | Send email |
| POP3 | 110 | Receive email |
| IMAP | 143 | Receive email (server-based) |
| DNS | 53 | Domain to IP |
| DHCP | 67/68 | IP address assignment |
| SSH | 22 | Secure remote login |

---

## Network Models

| Model | Type | Description |
|-------|------|-------------|
| **Client-Server** | — | **Server stores and manages shared resources** |
| **Peer-to-Peer (P2P)** | — | All devices equal — share directly |

---

## Exam Traps ⚠️
> HUB = **broadcast** — sends to ALL — Switch sends to specific device
> DSL = **broadband** — NOT wireless or narrow-band
> Protocol = **rules for communication** — NOT hardware or software
> Server = **stores and manages shared resources** — NOT requests services (client does that)
> Router = connects **different networks** — Switch = connects devices in same network
> WiFi = wireless LAN — Bluetooth = personal area network (very short range)
