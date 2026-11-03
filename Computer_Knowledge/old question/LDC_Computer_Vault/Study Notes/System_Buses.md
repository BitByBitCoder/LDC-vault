---
tags: [computer, ldc, hardware, bus, cpu]
aliases: [Address Bus, Data Bus, Control Bus, System Bus]
---
# System Buses (Address, Data, Control)

> **Q95:** The address bus is **unidirectional** (one way, CPU → memory / I/O) → answer **(b)**.

## 1. The three buses
| Bus | Direction | Carries | Width decides |
| --- | --- | --- | --- |
| **Address bus** | **Unidirectional** (CPU → memory / I/O) | Memory or I/O location address | Max memory size (2^n) |
| **Data bus** | **Bidirectional** (CPU ↔ memory / I/O) | Actual data | Word size / speed of transfer |
| **Control bus** | Bidirectional (mixed signals) | Read, write, clock, interrupt, reset signals | – |

**Memory trick:** Address = **A**lways one way. Data = **D**oes both ways.

## 2. Address bus width → memory
| Address lines | Max memory |
| --- | --- |
| 16 | 64 KB |
| 20 | 1 MB |
| 24 | 16 MB |
| 32 | 4 GB |

## 3. Data bus width
| Processor | Data bus |
| --- | --- |
| 8085 | 8-bit |
| 8086 | 16-bit |
| 8088 | 8-bit |
| 80386 DX | 32-bit |
| Pentium | 64-bit |

## 4. Examples of control signals
| Signal | Use |
| --- | --- |
| Read (RD) | CPU reads from memory / I/O |
| Write (WR) | CPU writes to memory / I/O |
| Clock | Timing for the system |
| Interrupt | Device asks CPU for attention |
| Reset | Restarts the CPU |

## 5. Types of bus
| Type | Meaning |
| --- | --- |
| Internal (local) bus | Connects parts inside the CPU |
| External (system) bus | Connects CPU, memory and I/O |
| Expansion bus | Connects add-on cards (PCI, ISA, AGP) |
| Serial bus | Sends bits one after another (USB) |
| Parallel bus | Sends many bits at once |

## 6. Related terms
| Term | Meaning |
| --- | --- |
| Bandwidth | Data moved per second |
| Word size | Bits the CPU processes at once |
| Unidirectional | One direction only |
| Bidirectional | Both directions |
| Motherboard | Main board that holds the buses and connects all parts |

## 7. Practice questions (written by Claude, with answers)
| # | Question | Answer |
| --- | --- | --- |
| 1 | Address bus direction | Unidirectional |
| 2 | Data bus direction | Bidirectional |
| 3 | Control bus direction | Bidirectional |
| 4 | Which bus carries memory addresses | Address bus |
| 5 | Which bus carries actual data | Data bus |
| 6 | Which bus carries read/write signals | Control bus |
| 7 | Address bus width decides | Maximum memory size |
| 8 | Data bus width decides | Amount of data moved at a time |
| 9 | 16-bit address bus can address | 64 KB |
| 10 | 20-bit address bus can address | 1 MB |
| 11 | 32-bit address bus can address | 4 GB |
| 12 | Data bus of the 8085 | 8-bit |
| 13 | Data bus of the 8086 | 16-bit |
| 14 | A group of wires carrying signals between parts | Bus |
| 15 | PCI, ISA and AGP are | Expansion buses |
| 16 | USB is a | Serial bus |
| 17 | Bus joining CPU, memory and I/O | System bus |
| 18 | Main board holding the buses | Motherboard |

## 8. Exam tip
Any question on bus direction: **Address = unidirectional; Data = bidirectional; Control = bidirectional**.
