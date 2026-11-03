---
tags: [computer, ldc, memory, hexadecimal, dos]
aliases: [Memory Address, Conventional Memory, Memory Map]
---
# Memory Addressing & Hexadecimal

> **Q92:** Memory addresses (conventional memory in DOS) range from **00000 to 9FFFF (hex)** → answer **(a)**. That is 640 KB. (9FFFF = 655,359 decimal; 0 to 655,359 = 655,360 bytes = 640 × 1024.)

## 1. Memory map of the original PC (real mode, DOS)
| Area | Address range (hex) | Size | Use |
| --- | --- | --- | --- |
| **Conventional memory** | **00000 – 9FFFF** | **640 KB** | DOS, programs, data |
| Video memory | A0000 – BFFFF | 128 KB | Display adapter |
| Adapter ROM | C0000 – EFFFF | 192 KB | Expansion card ROMs |
| System BIOS ROM | F0000 – FFFFF | 64 KB | BIOS |
| **Upper memory area (UMA)** | A0000 – FFFFF | 384 KB | Video + ROM (A0000–FFFFF together) |
| High memory area (HMA) | 100000 – 10FFEF | about 64 KB | Just above 1 MB, DOS can be loaded here |
| Extended memory | Above 100000 (1 MB) | – | Needs 286 or newer |
| Total real-mode memory | 00000 – FFFFF | 1 MB | 8086 / 8088 limit |

**Remember:** 640 KB (conventional) + 384 KB (upper) = 1024 KB = 1 MB.

## 2. Address bus width and memory size
Memory size = 2^n (n = number of address lines)

| Processor | Address lines | Max memory |
| --- | --- | --- |
| 8085 | 16 | 64 KB |
| 8086 / 8088 | 20 | 1 MB |
| 80286 | 24 | 16 MB |
| 80386 and later (32-bit) | 32 | 4 GB |
| 64-bit processors | 64 (theoretical) | 16 EB (theoretical) |

| Address lines | Locations |
| --- | --- |
| 10 | 1 KB (1,024) |
| 16 | 64 KB (65,536) |
| 20 | 1 MB (1,048,576) |
| 32 | 4 GB |

## 3. Hexadecimal basics
| Decimal | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Hex | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | A | B | C | D | E | F |

| Number system | Base | Digits used |
| --- | --- | --- |
| Binary | 2 | 0, 1 |
| Octal | 8 | 0 – 7 |
| Decimal | 10 | 0 – 9 |
| Hexadecimal | 16 | 0 – 9, A – F |

| Hex | Binary (4 bits) |
| --- | --- |
| 1 | 0001 |
| 5 | 0101 |
| 9 | 1001 |
| A | 1010 |
| F | 1111 |

- 1 hex digit = **4 bits**; 2 hex digits = **1 byte**
- The "(16)" in `9ffff(16)` means **base 16**
- FF (hex) = 255; FFFF (hex) = 65,535; 9FFFF (hex) = 655,359

## 4. Memory units
| Unit | Size |
| --- | --- |
| 1 Nibble | 4 bits |
| 1 Byte | 8 bits |
| 1 KB | 1,024 bytes |
| 1 MB | 1,024 KB |
| 1 GB | 1,024 MB |
| 1 TB | 1,024 GB |

## 5. Memory types in DOS
| Term | Meaning |
| --- | --- |
| Conventional memory | First 640 KB, DOS programs run here |
| Upper memory | 640 KB to 1 MB, reserved for hardware |
| Expanded memory (EMS) | Bank-switched memory used to get past the 1 MB limit |
| Extended memory (XMS) | Memory above 1 MB |
| HMA | First 64 KB of extended memory |

## 6. Practice questions (written by Claude, with answers)
| # | Question | Answer |
| --- | --- | --- |
| 1 | Conventional memory size | 640 KB |
| 2 | Conventional memory address range | 00000 to 9FFFF (hex) |
| 3 | Upper memory area starts at | A0000 (hex) |
| 4 | Memory limit of 8086 | 1 MB |
| 5 | Address lines of 8086 | 20 |
| 6 | Address lines of 8085 | 16 |
| 7 | Maximum memory with 16 address lines | 64 KB |
| 8 | Maximum memory with 32 address lines | 4 GB |
| 9 | Base of hexadecimal system | 16 |
| 10 | Hex digits used | 0–9 and A–F |
| 11 | Hex F equals decimal | 15 |
| 12 | Hex FF equals decimal | 255 |
| 13 | 1 hex digit equals how many bits | 4 |
| 14 | Binary of hex A | 1010 |
| 15 | Memory above 1 MB is called | Extended memory |
| 16 | Memory between 640 KB and 1 MB is called | Upper memory |
| 17 | Where is the BIOS ROM located | F0000 – FFFFF |
| 18 | Video memory address range | A0000 – BFFFF |
| 19 | 1 Byte equals | 8 bits |
| 20 | 1 Nibble equals | 4 bits |
| 21 | 1 KB equals | 1,024 bytes |
| 22 | Total memory in real mode | 1 MB |

## 7. Exam tip
If the options are the same except for the starting address, pick the one that starts at **00000** and ends at **9FFFF**. It is the 640 KB conventional memory area.
