# 10 — Number Systems & Units
[[💻 Computer Knowledge — INDEX|← Back to Index]]

---

## Questions From Your Papers

| Question | Answer |
|----------|--------|
| Smallest unit of data | **Bit** |
| 1 Nibble = | **4 bits** |
| 1 Byte = | **8 bits** |
| Smallest memory size | **Kilobyte (KB)** |
| IP address size (IPv4) | **4 bytes** |
| Which has smallest storage? | **Megabyte** (smaller than GB/TB) |

---

## Data Units — Complete Table

| Unit | Value | Memory |
|------|-------|--------|
| **Bit** | 0 or 1 | Smallest unit |
| **Nibble** | **4 bits** | Half a byte |
| **Byte** | **8 bits** | Single character |
| **Kilobyte (KB)** | 1024 Bytes | Small text file |
| **Megabyte (MB)** | 1024 KB | Photo |
| **Gigabyte (GB)** | 1024 MB | Movie |
| **Terabyte (TB)** | 1024 GB | Hard drive |
| **Petabyte (PB)** | 1024 TB | Data center |
| **Exabyte (EB)** | 1024 PB | — |

### Size Order (Smallest → Largest)
```
Bit → Nibble → Byte → KB → MB → GB → TB → PB → EB
```

---

## Number Systems

| System | Base | Digits |
|--------|------|--------|
| **Binary** | 2 | 0, 1 |
| **Octal** | 8 | 0–7 |
| **Decimal** | 10 | 0–9 |
| **Hexadecimal** | 16 | 0–9, A–F |

### Binary Basics
```
Each binary digit = 1 bit
8 binary digits = 1 byte

Example:
1010 in binary = 10 in decimal
1111 in binary = 15 in decimal
1000 0000 = 128 in decimal
1111 1111 = 255 in decimal
```

### Decimal to Binary (Quick)
| Decimal | Binary |
|---------|--------|
| 0 | 0000 |
| 1 | 0001 |
| 2 | 0010 |
| 4 | 0100 |
| 8 | 1000 |
| 10 | 1010 |
| 15 | 1111 |
| 16 | 0001 0000 |

---

## Character Encoding

| Code | Bits | Characters |
|------|------|-----------|
| **ASCII** | 7 bits | 128 characters (English) |
| **Extended ASCII** | 8 bits | 256 characters |
| **Unicode (UTF-8)** | Variable | All world languages |
| **Unicode (UTF-16)** | 16 bits | — |

---

## IP Address

| Version | Size | Example |
|---------|------|---------|
| **IPv4** | **32 bits = 4 bytes** | 192.168.1.1 |
| **IPv6** | 128 bits = 16 bytes | 2001:db8::1 |

---

## Exam Traps ⚠️
> Smallest unit = **Bit** — NOT byte (byte = 8 bits)
> 1 Nibble = **4 bits** — NOT 8 bits
> 1 Byte = **8 bits** — very commonly tested
> KB < MB < GB < TB — smallest is **KB**
> IPv4 = **4 bytes (32 bits)** — NOT 2 bytes or 6 bytes
> Binary = base **2** — Hexadecimal = base **16**
> ASCII = **7-bit** (128 chars) — Extended ASCII = 8-bit (256 chars)
