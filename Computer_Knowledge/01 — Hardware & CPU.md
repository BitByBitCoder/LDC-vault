# 01 — Hardware & CPU
[[💻 Computer Knowledge — INDEX|← Back to Index]]

> Biggest topic — 137 questions (26%). Your CS background covers most of this.

---

## Computer Generations

| Generation | Period | Technology | Example |
|------------|--------|-----------|---------|
| **1st** | 1940s–50s | **Vacuum Tubes** | ENIAC, UNIVAC |
| **2nd** | 1950s–60s | **Transistors** | IBM 1401 |
| **3rd** | 1960s–70s | **Integrated Circuits (IC)** | IBM 360 |
| **4th** | 1970s–now | **Microprocessors** | Intel, personal computers |
| **5th** | Now–future | **Artificial Intelligence** | — |

---

## Computer System — Basic Concepts

| Question                    | Answer                                       |
| --------------------------- | -------------------------------------------- |
| Computer works on principle | \|\|Input → Process → Output\|\|             |
| Processing happens in       | \|\|CPU (Central Processing Unit)\|\|        |
| CPU contains                | \|\|ALU + Control Unit + Registers\|\|       |
| ALU stands for              | \|\|Arithmetic Logic Unit\|\|                |
| Control Unit does           | \|\|Directs all computer operations\|\|      |
| Processor speed measured in | \|\|Hz (GHz)** = instructions per second\|\| |
| Main memory types           | \|\|RAM and ROM\|\|                          |
| RAM full form               | \|\|Random Access Memory\|\|                 |
| ROM full form               | \|\|Read Only Memory\|\|                     |
| RAM is                      | \|\|Volatile — loses data when power off\|\| |
| ROM is                      | \|\|Non-volatile — retains data\|\|          |
| Cache memory placed between | \|\|CPU and Main Memory\|\|                  |
| Fastest memory              | \|\|Cache memory\|\|                         |
| Firmware                    | \|\|Software embedded into hardware\|\|      |
| BIOS stored in              | \|\|ROM/CMOS\|\|                             |

---

## Memory Hierarchy (Fastest to Slowest)

```
Registers (fastest — inside CPU)
    ↓
Cache Memory (L1, L2, L3)
    ↓
RAM (Main Memory)
    ↓
Hard Disk / SSD
    ↓
Optical Disk / Magnetic Tape (slowest)
```

---

## Storage Devices

| Device              | Type      | Access                              |
| ------------------- | --------- | ----------------------------------- |
| **Magnetic Tape**   | Secondary | **Sequential** (must read in order) |
| **Hard Disk (HDD)** | Secondary | Random access                       |
| **SSD**             | Secondary | Random access (faster than HDD)     |
| **CD/DVD**          | Secondry  | Random access                       |
| **USB Flash Drive** | Secondary | Random access                       |
| **RAM**             | Primary   | Random access                       |

> ⚠️ **Sequential access = Magnetic Tape** — this appears directly in every paper

---

## Input Devices

| Device             | What it does                                                |
| ------------------ | ----------------------------------------------------------- |
| **Keyboard**       | \|\|Text input\|\|                                          |
| **Mouse**          | \|\|Pointing device\|\|                                     |
| **Scanner**        | \|\|Converts physical docs to digital\|\|                   |
| **Digitizer**      | \|\|Converts graphical drawings into digital form\|\|       |
| **Microphone**     | \|\|Audio input\|\|                                         |
| **Webcam**         | \|\|Video input\|\|                                         |
| **Barcode reader** | \|\|Reads barcodes\|\|                                      |
| **OCR**            | \|\|Optical Character Recognition — reads printed text\|\|  |
| **OMR**            | \|\|Optical Mark Recognition — reads marks (MCQ sheets)\|\| |
| **Joystick**       | \|\|Game input\|\|                                          |
| **Light pen**      | \|\|Draw on screen\|\|                                      |
| **Touch screen**   | \|\|Both input and output\|\|                               |

> ⚠️ **Digitizer = converts graphical drawings** — NOT scan printed text (that's Scanner/OCR)

---

## Output Devices

| Device | What it does |
|--------|-------------|
| **Monitor** | Display output |
| **Printer** | Hard copy output |
| **Plotter** | Large drawings/blueprints |
| **Speaker** | Audio output |
| **Projector** | Screen image projection — **output device** |
| **Headphones** | Audio output |

> ⚠️ **Projector = output device** — appeared directly in papers

---

## Printer Types

| Printer | How it works | Key Fact |
|---------|-------------|---------|
| **Inkjet** | Sprays ink | Home use, color |
| **Laser** | Toner + heat | Office use, fast |
| **Dot Matrix** | Pins hit ribbon | Oldest type — impact printer |
| **Plotter** | Pens on paper | Large engineering drawings |

---

## Data Storage Units

| Unit | Size |
|------|------|
| 1 Bit | Smallest unit (0 or 1) |
| 1 Nibble | **4 bits** |
| 1 Byte | **8 bits** |
| 1 KB (Kilobyte) | **1024 bytes** |
| 1 MB (Megabyte) | **1024 KB** |
| 1 GB (Gigabyte) | **1024 MB** |
| 1 TB (Terabyte) | **1024 GB** |
| 1 PB (Petabyte) | **1024 TB** |

---

## Number Systems (Computer)

| System | Base | Digits |
|--------|------|--------|
| **Binary** | 2 | 0, 1 |
| **Octal** | 8 | 0–7 |
| **Decimal** | 10 | 0–9 |
| **Hexadecimal** | 16 | 0–9, A–F |

| Decimal | Binary | Hex |
|---------|--------|-----|
| 0 | 0000 | 0 |
| 1 | 0001 | 1 |
| 10 | 1010 | A |
| 15 | 1111 | F |

---

## Software Classification

| Type | Examples |
|------|---------|
| **System Software** | OS (Windows, Linux), Device drivers, BIOS |
| **Application Software** | MS Word, Excel, Spreadsheet, Browser |
| **Utility Software** | Antivirus, Disk defragmenter, Backup |

> ⚠️ **Spreadsheet = Application software** — NOT system software

---

## Client-Server Model

| Role | What it does |
|------|-------------|
| **Server** | **Stores and manages shared resources** |
| **Client** | Requests services from server |

---

## Computer Uses in Industry

| Industry | Computer Used For |
|----------|-----------------|
| Inventory control | **Monitor stock levels and manage reordering** |
| Banking | Transaction processing |
| Healthcare | Patient records, diagnostics |
| Education | Learning management |

---

## Important Computer Terms

| Term | Meaning |
|------|---------|
| **Firmware** | Software embedded into hardware (ROM-based) |
| **Instruction set** | All instructions a processor can execute |
| **On-line storage** | Immediately available to CPU |
| **Off-line storage** | Not directly accessible — needs human action |
| **Bus** | Communication pathway between components |
| **Port** | Interface to connect external devices |
| **GUI** | Graphical User Interface |
| **CLI** | Command Line Interface |
| **Multitasking** | Running multiple programs simultaneously |
| **Multiprocessing** | Multiple CPUs working together |
| **Booting** | Starting up the computer |
| **Cold boot** | Starting from power off |
| **Warm boot** | Restarting while powered on |

---

## Exam Traps ⚠️
> First generation = **Vacuum Tubes** — NOT transistors
> Fastest memory = **Cache** — NOT RAM or hard disk
> Sequential access = **Magnetic Tape** — hard disk is random access
> Digitizer = **graphical drawings → digital** — NOT scan printed text
> Projector = **output device** — NOT input
> Spreadsheet program = **Application software** — NOT system software
> Server = **stores and manages** — NOT requests services (that's client)
> 1 KB = **1024 bytes** — NOT 1000 bytes





# 01 — Hardware & CPU
[[💻 Computer Knowledge — INDEX|← Back to Index]]

> 124 questions — biggest topic (23.5%). Pure memorization + basic concepts.

---

## Computer Basics

| Question                    | Answer                                                 |
| --------------------------- | ------------------------------------------------------ |
| Computer works on principle | \|\|Input → Process → Output\|\|                       |
| Processing takes place in   | \|\|CPU (Central Processing Unit)\|\|                  |
| Father of computers         | \|\|Charles Babbage\|\|                                |
| Father of computer science  | \|\|Alan Turing\|\|                                    |
| A computer is               | \|\|Electronic device that processes data\|\|          |
| Data vs Information         | \|\|Data = raw facts; Information = processed data\|\| |

---

## Generations of Computers

| **Generation** | **Period**     | **Core Technology**                 | **Examples**                            |
| -------------- | -------------- | ----------------------------------- | --------------------------------------- |
| **1st**        | 1940s–1950s    | \|\|Vacuum Tubes\|\|                | ENIAC, UNIVAC, EDVAC                    |
| **2nd**        | 1950s–1960s    | \|\|Transistors\|\|                 | IBM 1401, CDC 1604                      |
| **3rd**        | 1960s–1970s    | \|\|Integrated Circuits IC\|\|      | IBM 360, PDP-8                          |
| **4th**        | 1970s–Present  | \|\|Microprocessors (VLSI)\|\|      | IBM PC, Apple II                        |
| **5th**        | Present–Future | \|\|AI, ULSI, Quantum Computing\|\| | Supercomputers, AI Assistants, Robotics |

---

## CPU — Central Processing Unit

| Component                       | Function                                                |
| ------------------------------- | ------------------------------------------------------- |
| **ALU** (Arithmetic Logic Unit) | \|\|Performs calculations and logical operations\|\|    |
| **Control Unit (CU)**           | \|\|Directs operations — fetches, decodes, executes\|\| |
| **Registers**                   | \|\|Fastest temporary storage inside CPU\|\|            |
| **Cache Memory**                | \|\|Between CPU and RAM — fastest after registers\|\|   |

### CPU Cycle
```
Fetch → Decode → Execute → Store
```

### Processor Speed
- Measured in ||MHz or GHz||
- Which Means: **number of instructions executed per second**
- Higher GHz = faster ||processor||

### Cache Memory
- Located **||between CPU and Main Memory (RAM)||**
- Faster than RAM, smaller in size
- **L1 Cache** (fastest, smallest) → L2 → L3 (slowest of cache, largest)

---

## Memory Types

| Memory                         | Type                 | Key Fact                                |
| ------------------------------ | -------------------- | --------------------------------------- |
| **Registers**                  | \|\|Volatile\|\|     | \|\|Fastest — inside CPU\|\|            |
| **Cache**                      | \|\|Volatile\|\|     | \|\|Between CPU and RAM\|\|             |
| **RAM** (Random Access Memory) | \|\|Volatile\|\|     | \|\|Temporary — lost when power off\|\| |
| **ROM** (Read Only Memory)     | \|\|Non-volatile\|\| | \|\|Permanent — stores BIOS\|\|         |
| **Hard Disk**                  | \|\|Non-volatile\|\| | \|\|Permanent storage\|\|               |
| **Flash Drive / USB**          | \|\|Non-volatile\|\| | \|\|Portable storage\|\|                |
| **Magnetic Tape**              | \|\|Non-volatile\|\| | \|\|Sequential access\|\|               |
| **CD/DVD**                     | \|\|Non-volatile\|\| | \|\|Optical disk\|\|                    |

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

| Device                  | Type               | Access                           |
| ----------------------- | ------------------ | -------------------------------- |
| Hard Disk (HDD)         | \|\|Magnetic\|\|   | \|\|Random access\|\|            |
| SSD (Solid State Drive) | \|\|Electronic\|\| | \|\|Random access\|\|            |
| CD/DVD/Blu-ray          | \|\|Optical\|\|    | \|\|Random access\|\|            |
| USB Flash Drive         | \|\|Electronic\|\| | \|\|Random access\|\|            |
| **Magnetic Tape**       | \|\|Magnetic\|\|   | \|\|Sequential access ONLY\|\|   |
| Floppy Disk             | \|\|Magnetic\|\|   | \|\|Random access (obsolete)\|\| |

> 💡 **Sequential access** = must read from beginning to reach any point = **Magnetic Tape**
> 💡 **Random access** = can jump directly to any location = Hard Disk, RAM, CD

---

## Input Devices

| Device                          | What it does                                          |
| ------------------------------- | ----------------------------------------------------- |
| Keyboard                        | \|\|Text input\|\|                                    |
| Mouse                           | \|\|Pointing/clicking\|\|                             |
| Scanner                         | \|\|Digitizes paper documents\|\|                     |
| **Digitizer / Graphics Tablet** | \|\|Converts graphical drawings into digital form\|\| |
| Joystick                        | \|\|Gaming/control input\|\|                          |
| Microphone                      | \|\|Audio input\|\|                                   |
| Webcam                          | \|\|Video input\|\|                                   |
| Barcode Reader                  | \|\|Reads barcodes\|\|                                |
| OMR                             | \|\|Reads marked circles (exam answer sheets)\|\|     |
| OCR                             | \|\|Reads printed text\|\|                            |
| MICR                            | \|\|Reads magnetic ink (bank cheques)\|\|             |
| Light Pen                       | \|\|Input on screen\|\|                               |
| Touch Screen                    | \|\|Input by touch\|\|                                |

> 💡 **Digitizer** = converts graphical/drawing to digital — NOT text scanning (that's OCR)

---

## Output Devices

| Device      | Type             | Output                         |
| ----------- | ---------------- | ------------------------------ |
| Monitor/VDU | \|\|Softcopy\|\| | \|\|Visual display\|\|         |
| Printer     | \|\|Hardcopy\|\| | \|\|Printed paper\|\|          |
| Plotter     | \|\|Hardcopy\|\| | \|\|Large drawings/designs\|\| |
| Speaker     | \|\|Softcopy\|\| | \|\|Audio\|\|                  |
| Projector   | \|\|Softcopy\|\| | \|\|Projected display\|\|      |
|             |                  |                                |

### Printer Types
| Type           | Mechanism                                   |
| -------------- | ------------------------------------------- |
| **Laser**      | \|\|Best quality, fast, uses toner\|\|      |
| **Inkjet**     | \|\|Color photos, uses ink\|\|              |
| **Dot Matrix** | \|\|Impact printer — carbon copy — loud\|\| |
| **Thermal**    | \|\|Heat-sensitive paper\|\|                |

---

## Units of Storage

| Unit                    | Value                          |
| ----------------------- | ------------------------------ |
| \|\|1 Bit\|\|           | \|\|Smallest unit — 0 or 1\|\| |
| \|\|1 Nibble\|\|        | \|\|4 bits\|\|                 |
| \|\|1 Byte\|\|          | \|\|8 bits\|\|                 |
| \|\|1 KB (Kilobyte)\|\| | \|\|1024 Bytes\|\|             |
| \|\|1 MB (Megabyte)\|\| | \|\|1024 KB\|\|                |
| \|\|1 GB (Gigabyte)\|\| | \|\|1024 MB\|\|                |
| \|\|1 TB (Terabyte)\|\| | \|\|1024 GB\|\|                |
| \|\|1 PB (Petabyte)\|\| | \|\|1024 TB\|\|                |

### Size Order (Smallest → Largest)
```
Bit → Nibble → Byte → KB → MB → GB → TB → PB
```

---

## Number Systems

| System      | Base | Digits Used |
| ----------- | ---- | ----------- |
| Binary      | 2    | 0, 1        |
| Octal       | 8    | 0–7         |
| Decimal     | 10   | 0–9         |
| Hexadecimal | 16   | 0–9, A–F    |

### ASCII & Unicode
| Code | Purpose |
|------|---------|
| **ASCII** | 7-bit code — 128 characters — English |
| **Extended ASCII** | 8-bit — 256 characters |
| **Unicode** | Universal — supports all languages |

---

## Computer Types

| Type                 | Description                                  |
| -------------------- | -------------------------------------------- |
| **Supercomputer**    | Fastest, most powerful — weather forecasting |
| **Mainframe**        | Large organizations — banks                  |
| **Minicomputer**     | Mid-range                                    |
| **Microcomputer/PC** | Personal use                                 |
| **Embedded**         | Built into devices (washing machine, car)    |

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
