
---

## tags: [computer, ldc, memory, ram, dram, sram] aliases: [DRAM, SRAM, Dynamic RAM, Static RAM, RAM Types]

# RAM Types: DRAM vs SRAM

> **Q104:** DRAM is used as main memory because it **consumes less power** (and is cheap and has high cell density) → answer **(a)**. "Needs refreshing circuitry" is a **disadvantage** of DRAM, not a reason for using it. "Higher speed" and "lower cell density" describe SRAM and DRAM wrongly.

## 1. DRAM vs SRAM

|Point|DRAM (Dynamic RAM)|SRAM (Static RAM)|
|---|---|---|
|Storage element|Capacitor + 1 transistor|Flip-flop (about 6 transistors)|
|Refreshing|**Needed**|Not needed|
|Speed|Slower|**Faster**|
|Power use|**Lower**|Higher|
|Cell density|**Higher** (more bits per chip)|Lower|
|Cost|**Cheaper**|Costlier|
|Size per bit|Small|Large|
|Complexity|Needs refresh circuit|Simple to use|
|Used for|**Main memory (RAM)**|**Cache memory**|
|Volatile|Yes|Yes|

**Remember:** DRAM = Dense, cheap, Doesn't hold data without refresh. SRAM = Speedy, costly, used in cache.

## 2. Why DRAM for main memory

|Reason|Detail|
|---|---|
|Low power|Consumes less power per bit|
|High density|Many bits packed in a small chip, so large capacity|
|Low cost|Cheap per bit|
|Trade-off|Needs refreshing and is slower|

## 3. Types of DRAM

|Type|Full form / meaning|
|---|---|
|SDRAM|Synchronous DRAM, synchronised with system clock|
|DDR SDRAM|Double Data Rate SDRAM, transfers data on both clock edges|
|DDR2 / DDR3 / DDR4 / DDR5|Newer, faster generations of DDR|
|RDRAM|Rambus DRAM|
|FPM DRAM|Fast Page Mode DRAM|
|EDO DRAM|Extended Data Out DRAM|
|VRAM|Video RAM, used on graphics cards|

## 4. Types of SRAM

|Type|Meaning|
|---|---|
|Asynchronous SRAM|Not tied to the clock|
|Synchronous SRAM|Works with the system clock|
|Pipeline burst SRAM|Faster, used in cache|

## 5. RAM vs ROM

|Point|RAM|ROM|
|---|---|---|
|Full form|Random Access Memory|Read Only Memory|
|Read / write|Both|Mostly read only|
|Volatile|Yes|No|
|Use|Running programs|Boot instructions (BIOS)|

## 6. ROM types

|Type|Meaning|
|---|---|
|ROM|Programmed at the factory, cannot be changed|
|PROM|Programmable ROM, written once by user|
|EPROM|Erasable PROM, erased with UV light|
|EEPROM|Electrically Erasable PROM|
|Flash memory|Type of EEPROM, erased in blocks (USB drive, SSD)|

## 7. Practice questions (written by Claude, with answers)

|#|Question|Answer|
|---|---|---|
|1|Main memory of a computer uses|DRAM|
|2|Cache memory uses|SRAM|
|3|Which RAM needs refreshing|DRAM|
|4|Which RAM is faster|SRAM|
|5|Which RAM is cheaper|DRAM|
|6|Which RAM has higher cell density|DRAM|
|7|DRAM stores each bit in a|Capacitor|
|8|SRAM stores each bit in a|Flip-flop|
|9|Which consumes less power|DRAM|
|10|DRAM stands for|Dynamic Random Access Memory|
|11|SRAM stands for|Static Random Access Memory|
|12|SDRAM stands for|Synchronous DRAM|
|13|DDR stands for|Double Data Rate|
|14|VRAM is used in|Graphics cards|
|15|RAM is|Volatile|
|16|ROM is|Non-volatile|
|17|Disadvantage of DRAM|Needs refreshing, slower|
|18|EPROM is erased by|Ultraviolet light|
|19|Flash memory is a type of|EEPROM|
|20|Memory that loses data when power is off|RAM|

## 8. Exam tip

- "Why DRAM is used as main memory?" → **less power / high density / low cost**.
- "Needs refreshing" → **DRAM**. "Used in cache" → **SRAM**.