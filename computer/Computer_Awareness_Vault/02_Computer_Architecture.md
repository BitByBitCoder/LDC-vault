# 02. Computer Architecture

Back to [[00_Index]]

### Main Functional Units
* **Input Unit**: Accepts user commands/data and converts them into an acceptable computer format (e.g., Keyboard, Mouse).
* **Output Unit**: Converts coded computer results into human-readable format (e.g., Monitor, Printer, Plotter).
* **Central Processing Unit (CPU)**: Fabricated as a single Integrated Circuit (IC) known as a **Microprocessor**; acts as the "brain" of the computer.

### Components of the CPU
1. **Arithmetic Logic Unit (ALU)**:
   * **Logical Operations**: AND, NOT, OR, XOR.
   * **Arithmetic Operations**: Addition, Subtraction, Multiplication, Division.
   * **Bit-Shifting & Comparisons**: Left/right shift, comparison operators ($=, <, >, \le, \ge$).
2. **Registers**: High-speed top-hierarchy memory used to quickly accept, store, and transfer CPU data.
3. **Control Unit (CU)**: Fetches instructions from main memory, identifies operations, coordinates I/O devices, and issues control signals.

### Microprocessor & Motherboard
* **First Microprocessor**: **Intel 4004** (1971), created by Ted Hoff and Frederico Faggin.
* **Motherboard (System Board / Logic Board)**: Main Printed Circuit Board (PCB) containing CPU, ROM, RAM, expansion slots, PCI slots, USB ports, and CMOS battery.
* **Motherboard Components**: CMOS Battery, BIOS Chip, Fan, Expansion Slot, SMPS, PCI Slot, Processor Chip, Buses.

### System Buses
* **Internal Bus (System Bus)**: Connects internal components on the motherboard.
  * *Control Bus*: Carries access commands.
  * *Address Bus*: Carries memory/device addresses.
  * *Data Bus*: Transfers actual data.
* **External Bus (Expansion Bus)**: Connects peripheral devices, expansion slots, and I/O ports.

### Architectural Tit-Bits
* **UPS**: Uninterruptible Power Supply provides emergency battery power during outages.
* **Buffer**: Temporary storage register holding data for I/O execution.
* **Accumulator**: Register storing intermediate arithmetic and logic results.
* **Time Slice**: Uniform time interval allocated by CPU for task execution.
* **Clock Speed**: Measured in Megahertz (MHz) or Gigahertz, representing millions of processing cycles per second.
* **DMA (Direct Memory Access)**: Allows I/O devices to transfer data directly to/from main memory without routing through the CPU.
