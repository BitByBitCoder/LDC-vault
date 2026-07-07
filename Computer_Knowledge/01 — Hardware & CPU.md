# 01 — Hardware & CPU
[[💻 Computer Knowledge — INDEX|← Back to Index]]

> 124 questions — biggest topic (23.5%). Pure memorization + basic concepts.

---

## Computer Basics

| Question | Answer |
|----------|--------|
| Computer works on principle | **Input → Process → Output** |
| Processing takes place in | **CPU (Central Processing Unit)** |
| Father of computers | **Charles Babbage** |
| Father of computer science | **Alan Turing** |
| A computer is | Electronic device that processes data |
| Data vs Information | Data = raw facts; Information = processed data |

---

## Generations of Computers

| Generation | Period | Technology | Example |
|-----------|--------|-----------|---------|
| **1st** | 1940s–50s | **Vacuum Tubes** | ENIAC, UNIVAC |
| **2nd** | 1950s–60s | **Transistors** | IBM 1401 |
| **3rd** | 1960s–70s | **Integrated Circuits (IC)** | IBM 360 |
| **4th** | 1970s–now | **Microprocessors** | Intel, AMD |
| **5th** | Now–future | **AI / VLSI** | — |

---

## CPU — Central Processing Unit

| Component | Function |
|-----------|---------|
| **ALU** (Arithmetic Logic Unit) | Performs calculations and logical operations |
| **Control Unit (CU)** | Directs operations — fetches, decodes, executes |
| **Registers** | Fastest temporary storage inside CPU |
| **Cache Memory** | Between CPU and RAM — fastest after registers |

### CPU Cycle
```
Fetch → Decode → Execute → Store
```

### Processor Speed
- Measured in **MHz or GHz**
- Means: **number of instructions executed per second**
- Higher GHz = faster processor

### Cache Memory
- Located **between CPU and Main Memory (RAM)**
- Faster than RAM, smaller in size
- **L1 Cache** (fastest, smallest) → L2 → L3 (slowest of cache, largest)

---

## Memory Types

| Memory | Type | Key Fact |
|--------|------|---------|
| **Registers** | Volatile | Fastest — inside CPU |
| **Cache** | Volatile | Between CPU and RAM |
| **RAM** (Random Access Memory) | **Volatile** | Temporary — lost when power off |
| **ROM** (Read Only Memory) | **Non-volatile** | Permanent — stores BIOS |
| **Hard Disk** | Non-volatile | Permanent storage |
| **Flash Drive / USB** | Non-volatile | Portable storage |
| **Magnetic Tape** | Non-volatile | **Sequential access** |
| **CD/DVD** | Non-volatile | Optical disk |

### Memory Speed Order (Fastest → Slowest)
```
Registers → Cache → RAM → Hard Disk → Optical → Magnetic Tape
```

### Volatile vs Non-volatile
| Volatile (loses data on power off) | Non-volatile (keeps data) |
|------------------------------------|--------------------------|
| RAM, Cache, Registers | ROM, Hard Disk, USB, CD/DVD |

---

## Storage Devices

| Device | Type | Access |
|--------|------|--------|
| Hard Disk (HDD) | Magnetic | **Random access** |
| SSD (Solid State Drive) | Electronic | **Random access** |
| CD/DVD/Blu-ray | Optical | Random access |
| USB Flash Drive | Electronic | Random access |
| **Magnetic Tape** | Magnetic | **Sequential access ONLY** |
| Floppy Disk | Magnetic | Random access (obsolete) |

> 💡 **Sequential access** = must read from beginning to reach any point = **Magnetic Tape**
> 💡 **Random access** = can jump directly to any location = Hard Disk, RAM, CD

---

## Input Devices

| Device | What it does |
|--------|-------------|
| Keyboard | Text input |
| Mouse | Pointing/clicking |
| Scanner | Digitizes paper documents |
| **Digitizer / Graphics Tablet** | **Converts graphical drawings into digital form** |
| Joystick | Gaming/control input |
| Microphone | Audio input |
| Webcam | Video input |
| Barcode Reader | Reads barcodes |
| OMR | Reads marked circles (exam answer sheets) |
| OCR | Reads printed text |
| MICR | Reads magnetic ink (bank cheques) |
| Light Pen | Input on screen |
| Touch Screen | Input by touch |

> 💡 **Digitizer** = converts graphical/drawing to digital — NOT text scanning (that's OCR)

---

## Output Devices

| Device | Type | Output |
|--------|------|--------|
| Monitor/VDU | Softcopy | Visual display |
| Printer | Hardcopy | Printed paper |
| Plotter | Hardcopy | Large drawings/designs |
| Speaker | Softcopy | Audio |
| Projector | Softcopy | Projected display |

### Printer Types
| Type | Mechanism |
|------|-----------|
| **Laser** | Best quality, fast, uses toner |
| **Inkjet** | Color photos, uses ink |
| **Dot Matrix** | Impact printer — carbon copy — loud |
| **Thermal** | Heat-sensitive paper |

---

## Units of Storage

| Unit | Value |
|------|-------|
| **1 Bit** | Smallest unit — 0 or 1 |
| **1 Nibble** | **4 bits** |
| **1 Byte** | **8 bits** |
| **1 KB** (Kilobyte) | 1024 Bytes |
| **1 MB** (Megabyte) | 1024 KB |
| **1 GB** (Gigabyte) | 1024 MB |
| **1 TB** (Terabyte) | 1024 GB |
| **1 PB** (Petabyte) | 1024 TB |

### Size Order (Smallest → Largest)
```
Bit → Nibble → Byte → KB → MB → GB → TB → PB
```

---

## Number Systems

| System | Base | Digits Used |
|--------|------|------------|
| Binary | 2 | 0, 1 |
| Octal | 8 | 0–7 |
| Decimal | 10 | 0–9 |
| Hexadecimal | 16 | 0–9, A–F |

### ASCII & Unicode
| Code | Purpose |
|------|---------|
| **ASCII** | 7-bit code — 128 characters — English |
| **Extended ASCII** | 8-bit — 256 characters |
| **Unicode** | Universal — supports all languages |

---

## Computer Types

| Type | Description |
|------|-------------|
| **Supercomputer** | Fastest, most powerful — weather forecasting |
| **Mainframe** | Large organizations — banks |
| **Minicomputer** | Mid-range |
| **Microcomputer/PC** | Personal use |
| **Embedded** | Built into devices (washing machine, car) |

---

## Exam Traps ⚠️
> Sequential access = **Magnetic Tape** — NOT hard disk (hard disk = random access)
> Cache = **between CPU and RAM** — NOT between hard disk and monitor
> Processor speed = **instructions per second** — NOT memory size or hard disk size
> Digitizer = **converts drawings to digital** — NOT scans text (OCR does that)
> Smallest unit = **Bit** — NOT byte (byte = 8 bits)
> 1 Nibble = **4 bits** — NOT 8 bits (8 bits = 1 byte)
> Volatile memory = **RAM and Cache** — NOT ROM or Hard Disk
> ALU performs **calculations AND logic** — Control Unit does NOT calculate
