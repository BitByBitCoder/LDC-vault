[[00 Computer Vault Index]]

# Networking & Internet

#computer #net

**Part 1: learn the topic** (tables). **Part 2: past questions** (36: 🟢 20 · 🟡 14 · 🔴 2). Read Part 1 first, then test yourself in Part 2.

# Part 1: Learn the topic

## 1. Types of networks

| Type | Area | Example |
|---|---|---|
| PAN | about 10 m | Bluetooth |
| HAN | home | home Wi-Fi |
| LAN | building, campus | office |
| MAN | one **city** | cable TV network |
| WAN | country or world | Internet. Used to link **city to city** |
| VPN | private network over a public one | company remote access |

## 2. Topologies

| Topology | Shape | Fact |
|---|---|---|
| Bus | one cable | cheap, one failure breaks it |
| Star | central hub/switch | common today |
| Ring | circle | token passing |
| Mesh | all connected | very reliable, costly |
| Tree | hierarchy | mix of star and bus |

## 3. Network devices

| Device | Job |
|---|---|
| NIC | card giving physical network connection |
| Modem | MOdulator + DEModulator, digital to analog on phone line |
| Hub | broadcasts to all ports |
| Switch | sends only to target device **inside a LAN** |
| Router | chooses path for packets **between networks** |
| Bridge | joins two LANs |
| Gateway | joins different protocols |
| Repeater | boosts signal |
| Access Point (AP) | connects wireless devices to the wired network |
| Node | any device on a network |

## 4. Transmission media and modes

| Medium | Signal | Note |
|---|---|---|
| Twisted pair (UTP) | electrical | cheap, **prone to interference** |
| Coaxial | electrical | cable TV |
| Optical fibre | **light** | fastest, **no electrical interference** |
| Microwave / satellite | radio | wireless |

| Mode | Direction | Example |
|---|---|---|
| Simplex | one way | TV |
| Half duplex | both, one at a time | walkie-talkie |
| **Full duplex** | both **at once** | phone |

Modulation = putting digital data onto an **analog** carrier wave.

## 5. Switching

| Switching | Used by |
|---|---|
| Circuit | old telephone lines |
| **Packet** | **Internet** |

## 6. Protocols and ports

| Protocol | Purpose | Port |
|---|---|---|
| HTTP | web pages (**stateless**) | 80 |
| HTTPS | secure web | 443 |
| FTP | file transfer | 21 |
| SMTP | send email | 25 |
| POP3 / IMAP | receive email | 110 / 143 |
| DNS | name to IP | 53 |
| TCP / IP | reliable delivery / addressing | n/a |

## 7. IP address

| Fact | Detail |
|---|---|
| IPv4 | 32 bits, four numbers like 192.168.1.1 |
| IPv6 | 128 bits |
| Static IP | does **not** change |
| Dynamic IP | changes, given by DHCP |
| Meaning | name = what we seek, address = where it is, route = how to get there |

## 8. OSI model (7 layers)

Application, Presentation, Session, Transport, Network, Data Link, Physical.
Hook: **P**lease **D**o **N**ot **T**hrow **S**ausage **P**izza **A**way (bottom to top).

## 9. Internet terms

| Term | Meaning |
|---|---|
| Email address | **username@domain** |
| Spam | unsolicited email |
| Blog / Vlog | written log / **video blog** |
| Micro-blogging | short limited posts (Twitter/X) |
| Podcast | audio series |
| VoIP | voice calls over Internet |
| P2P | Peer to Peer |
| M2M | Machine to Machine, no humans (IoT) |
| Virtual Reality | fully computer-generated immersive scene |
| Augmented Reality | digital overlay on the real world |
| Network congestion | too much traffic (overloading) |
| DSL | internet over telephone wires |

## 10. Standards bodies and wireless

| Item | Fact |
|---|---|
| W3C | sets **WWW** standards |
| IETF | internet protocols and standards |
| InterNIC | domain name registration |
| Wi-Fi | IEEE 802.11 |
| WPA | **Wi-Fi Protected Access** (WEP is weaker) |
| Bluetooth | 2.4 GHz, **frequency hopping spread spectrum** |

## 11. Cloud

| Deployment | Who uses it |
|---|---|
| Public | many users share (serves multiple users) |
| Private | one organisation |
| Hybrid | mix |

| Service model | Delivers |
|---|---|
| SaaS | software |
| PaaS | platform |
| IaaS | infrastructure |

E-governance = delivering government services through ICT and the Internet.

# Part 2: Past questions with answers

Answer in your head first, then open the callout. Level is shown before the answer. 🔁 = repeated in your paper. ⚠️ = doubtful key ([[12 Doubtful Keys]]).

### Q267 · 🟢 Easy
**Q.** Technology giving internet over telephone wires ____

> [!success]- Answer
> **DSL**
> DSL = Digital Subscriber Line.
> Don't confuse with: Transmitter; Diodes; HHL

### Q288 · 🟢 Easy
**Q.** Network Interface Card (NIC) is ____

> [!success]- Answer
> **board providing physical connection to a network**
> NIC = LAN card; gives your PC a network connection and MAC address.
> Don't confuse with: peripheral device; device to connect over phone line; device that reads a disk

### Q305 · 🟢 Easy
**Q.** Device allowing computers to communicate over telephone lines ____

> [!success]- Answer
> **Modem**
> Modem = MOdulator + DEModulator.
> Don't confuse with: Microprocessor; Network; Assembler

### Q315 · 🟢 Easy
**Q.** Computer providing database services to others is a ____

> [!success]- Answer
> **Database server**
> Database server.
> Don't confuse with: Web server; Application server; FTP server

### Q350 · 🟢 Easy
**Q.** Technology for telephone calls over computer networks ____

> [!success]- Answer
> **VoIP**
> VoIP = Voice over Internet Protocol (WhatsApp calls, Skype).
> Don't confuse with: GSM; Modem; CDMA

### Q456 · 🟢 Easy
**Q.** Full form of P2P ____

> [!success]- Answer
> **Peer to Peer**
> Peer to Peer.
> Don't confuse with: Packet to Packet; Page to Page; Path to Path

### Q459 · 🟢 Easy
**Q.** A system or device connected to a network ____

> [!success]- Answer
> **Node**
> Node.
> Don't confuse with: Runtime; Router; Jumper

### Q588 · 🟢 Easy
**Q.** IP address that doesn't change every day ____

> [!success]- Answer
> **Static**
> Static IP.
> Don't confuse with: Dynamic; Unique; All

### Q592 · 🟢 Easy
**Q.** Network that extends a private network across public networks ____

> [!success]- Answer
> **VPN**
> VPN.
> Don't confuse with: LAN; SAN; Enterprise

### Q596 · 🟢 Easy
**Q.** Internet works on ____

> [!success]- Answer
> **Packet switching**
> Packet switching. Telephone (old) = circuit switching.
> Don't confuse with: Circuit switching; Both; Data switching

### Q597 · 🟢 Easy
**Q.** Record of your thoughts or experiences filmed and published online ____

> [!success]- Answer
> **Video blog**
> Vlog = video blog.
> Don't confuse with: Video log; Selfie; Podcast

### Q602 · 🟢 Easy
**Q.** Supports bi-directional flow in both directions simultaneously ____

> [!success]- Answer
> **Full Duplex**
> Full duplex = phone call. Half duplex = walkie-talkie. Simplex = TV.
> Don't confuse with: Half Duplex; Simplex; All

### Q611 · 🟢 Easy
**Q.** Computer-generated scenes that make the user feel immersed ____

> [!success]- Answer
> **Virtual reality**
> VR immerses you; AR overlays on real world.
> Don't confuse with: Augmented reality; Hologram reality; Video games

### Q698 · Q833 🔁 · 🟢 Easy
**Q.** Device that decides the path of data packets / redirects IP packets to destination ____

> [!success]- Answer
> **router**
> Router = chooses path between networks. Switch = connects devices inside a LAN.
> Don't confuse with: switch; hub; server

### Q711 · 🟢 Easy
**Q.** Unsolicited emails are known as ____

> [!success]- Answer
> **spam**
> Spam.
> Don't confuse with: junk; malicious; hoax

### Q712 · 🟢 Easy
**Q.** Network congestion occurs ____

> [!success]- Answer
> **traffic overloading**
> Too much traffic for the capacity.
> Don't confuse with: system terminates; connection terminates; all

### Q744 · 🟢 Easy
**Q.** What an email address contains?

> [!success]- Answer
> **User name followed by Domain**
> user@domain.
> Don't confuse with: Domain then User; User followed by Client; Domain followed by Client

### Q775 · 🟢 Easy
**Q.** Optical fiber uses ____

> [!success]- Answer
> **light signals**
> Light signals (pulses of light).
> Don't confuse with: electromagnetic radiation; electric current; both

### Q800 · 🟢 Easy
**Q.** Encoding using clear text to represent formatting ____

> [!success]- Answer
> **HTML**
> HTML tags are plain text.
> Don't confuse with: MS Word; FTP; HTTP

### Q904 · 🟢 Easy
**Q.** Cloud deployment used to serve multiple users ____

> [!success]- Answer
> **Public**
> Public cloud = shared by many customers.
> Don't confuse with: Private; Hybrid; none

### Q478 · 🟡 Medium
**Q.** Used to communicate from one city to another ____

> [!success]- Answer
> **WAN**
> Between cities = WAN. MAN covers inside one city. LAN = building.
> Don't confuse with: MAN; LAN; RAN

### Q594 · 🟡 Medium
**Q.** Access point (AP) in a wireless LAN is ____

> [!success]- Answer
> **device for connection** ⚠️
> AP connects wireless devices to the wired network. Doubtful wording but (a).
> Don't confuse with: wireless device itself; both; all

### Q599 · 🟡 Medium
**Q.** Transmission medium carrying data exposed to electrical interference ____

> [!success]- Answer
> **UTP**
> Unshielded twisted pair has no shield, so it picks up noise.
> Don't confuse with: Optical fiber; Coaxial; Microwave

### Q649 · 🟡 Medium
**Q.** E-governance uses ____

> [!success]- Answer
> **Internet** ⚠️
> E-governance delivers services over the Internet (ICT). Vague question.
> Don't confuse with: Government; Intranet; None

### Q652 · 🟡 Medium
**Q.** HTTP is a ____

> [!success]- Answer
> **Stateless Protocol**
> HTTP is stateless: each request is independent (cookies add state).
> Don't confuse with: Status Count Protocol; Status Transfer; Status Full

### Q661 · 🟡 Medium
**Q.** Main international organisation that sets standards for the WWW ____

> [!success]- Answer
> **W3C**
> W3C. IETF = internet protocols. InterNIC = domain registration.
> Don't confuse with: IETF; InterNIC; nota

### Q670 · 🟡 Medium
**Q.** Huge numbers of devices communicating automatically without humans ____

> [!success]- Answer
> **Machine to Machine**
> M2M (basis of IoT).
> Don't confuse with: Bot to Bot; Skynet; InterCloud

### Q682 · 🟡 Medium
**Q.** Fiber optics has the advantage of ____

> [!success]- Answer
> **no interference**
> Light signals are immune to electromagnetic interference.
> Don't confuse with: direct line-of-sight; easier to install; cheaper to install

### Q708 · 🟡 Medium
**Q.** Which does NOT use electrical signal for data transmission?  
(choose from: a) Optical fiber; b) Twisted pair; c) Coaxial; d) All use electrical signal)

> [!success]- Answer
> **Optical fiber**
> Fiber uses light.

### Q726 · 🟡 Medium
**Q.** NOT a one-to-many form of communication ____  
(choose from: a) Blogging; b) Personal Website; c) Email; d) Podcasting)

> [!success]- Answer
> **Email**
> Email is typically one-to-one (or few). The others broadcast.

### Q740 · 🟡 Medium
**Q.** 'Micro-blogging' means ____

> [!success]- Answer
> **limited individual posts**
> Short posts (Twitter/X).
> Don't confuse with: blogging from mobile; posted by companies; small scale devices

### Q797 · 🟡 Medium
**Q.** Modulation is the process of ____

> [!success]- Answer
> **encoding digital signal to analog**
> Modulation puts digital data onto an analog carrier wave (modem).
> Don't confuse with: analog to digital; sending a file; data description

### Q798 · 🟡 Medium
**Q.** Bluetooth uses ____

> [!success]- Answer
> **frequency hopping spread spectrum**
> Bluetooth = FHSS in the 2.4 GHz band.
> Don't confuse with: orthogonal; time division; none

### Q812 · 🟡 Medium
**Q.** Full form of WPA ____

> [!success]- Answer
> **Wi-Fi Protected Access**
> Wi-Fi Protected Access.
> Don't confuse with: Wireless Protected Access; Wired Process; Wi-Fi Process

### Q710 · 🔴 Hard
**Q.** An IP address identifies a device. Statement ____  
(choose from: a) name indicates seek; b) address indicates where; c) route indicates how; d) All)

> [!success]- Answer
> **All** ⚠️
> Name = what we seek, address = where it is, route = how to get there (RFC 791). All true.

### Q725 · 🔴 Hard
**Q.** The Internet is governed by ____

> [!success]- Answer
> **IETF** ⚠️
> IETF (written 'IEFT' in your set) sets internet standards. Related: W3C = web standards. Verify key.
> Don't confuse with: W3C; InterNIC; None

> [!warning] Exam Trap ⚠️
> - Router (between networks) vs Switch (inside LAN) vs Hub (broadcast).
> - W3C (web) vs IETF (internet) vs InterNIC (domains).
> - Fibre uses light. All copper cables use electricity.
> - Full duplex = both at once. Half duplex = one at a time.

## Self-check
- [ ] Round 1: __ / 36
- [ ] Round 2 (next day): __ / 36
- [ ] Round 3 (3 days later): __ / 36
- Close the topic at **85%**. Log it in [[15 Progress Tracker]].
