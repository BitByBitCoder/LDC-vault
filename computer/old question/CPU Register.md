
# CPU Registers

> **Q96:** The status register is also called the **Flag register** → answer **(d) Flags**. It holds single-bit flags (zero, carry, sign, overflow, etc.) that show the result of the last operation.

## 1. Main registers

|Register|Other name / short|Function|
|---|---|---|
|**Status register**|**Flag register**|Stores flags showing the result of an operation|
|Accumulator|AC / ACC|Holds the result of arithmetic and logic operations|
|Program Counter|PC / Instruction Pointer (IP)|Holds the address of the **next** instruction|
|Instruction Register|IR|Holds the instruction **currently** being executed|
|Memory Address Register|MAR|Holds the address of the memory location to read/write|
|Memory Data Register|MDR / MBR (Memory Buffer Register)|Holds data being read from or written to memory|
|Stack Pointer|SP|Points to the top of the stack|
|General purpose registers|GPR (e.g. AX, BX, CX, DX)|Temporary data storage|
|Index register|–|Used for array / address indexing|

## 2. Common flags

|Flag|Name|Set (1) when|
|---|---|---|
|Z|Zero|Result is zero|
|C / CY|Carry|Carry out of the highest bit|
|S|Sign|Result is negative|
|P|Parity|Result has even number of 1 bits|
|OV / O|Overflow|Result is too big for the register|
|AC|Auxiliary Carry|Carry from bit 3 to bit 4|
|I / IF|Interrupt|Interrupts are allowed|

## 3. Names that mean the same thing

|Name|Also called|
|---|---|
|Status register|Flag register, Condition code register|
|Program counter|Instruction pointer|
|MDR|Memory buffer register (MBR)|
|Accumulator|Main working register of the ALU|

## 4. Parts of the CPU

|Part|Function|
|---|---|
|ALU|Arithmetic and logical operations|
|CU|Controls and directs all operations|
|Registers|Small, fastest storage inside the CPU|
|Cache|Fast memory between CPU and RAM|

## 5. Memory speed order (fast to slow)

|Rank|Memory|
|---|---|
|1|Registers (fastest)|
|2|Cache|
|3|RAM|
|4|Hard disk / SSD|
|5|Optical disc / tape|

## 6. Instruction cycle

|Step|Action|
|---|---|
|Fetch|Get the instruction from memory (address from PC)|
|Decode|CU works out what the instruction means|
|Execute|ALU or other unit carries it out|
|Store|Result is written back|

## 7. Practice questions (written by Claude, with answers)

|#|Question|Answer|
|---|---|---|
|1|Status register is also called|Flag register|
|2|Register that holds the result of ALU operations|Accumulator|
|3|Register that holds the next instruction address|Program Counter|
|4|Register that holds the current instruction|Instruction Register|
|5|Register that points to the top of the stack|Stack Pointer|
|6|MAR stands for|Memory Address Register|
|7|MDR / MBR stands for|Memory Data (Buffer) Register|
|8|Fastest memory in a computer|Registers|
|9|Registers are located in|CPU|
|10|Zero flag is set when the result is|Zero|
|11|Carry flag is set when|There is a carry out of the top bit|
|12|Sign flag shows|Negative result|
|13|Another name of Program Counter|Instruction Pointer|
|14|Part of CPU that does arithmetic and logic|ALU|
|15|Part of CPU that controls operations|Control Unit|
|16|Order of instruction cycle|Fetch, decode, execute|
|17|Small, fast storage inside the CPU|Register|
|18|PC stands for (in CPU)|Program Counter|

## 8. Exam tip

Status = **Flags**. Next instruction = **Program counter**. Result of ALU = **Accumulator**. Current instruction = **Instruction register**.