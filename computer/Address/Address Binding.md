# Address Binding

Address binding is the process of **mapping a program’s logical addresses to physical addresses in memory**.

## Types of Address Binding

### 1. Compile-time Binding
- Address is fixed at compile time
- Physical address is known in advance
- If location changes, program must be recompiled

### 2. Load-time Binding
- Address is decided when the program is loaded into memory
- Uses relocatable code
- No need to recompile if location changes

### 3. Execution-time Binding
- Address is determined during program execution
- Uses hardware support (MMU)
- Allows dynamic memory allocation and movement

## Key Point
- Binding determines **when and how addresses are assigned** to memory locations