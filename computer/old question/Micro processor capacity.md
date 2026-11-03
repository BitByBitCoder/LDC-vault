
---

## tags: [computer, ldc, hardware, microprocessor, address-bus] aliases: [Addressing Capacity, Microprocessor, Address Bus Width]

# Microprocessor Addressing Capacity

> **Q107:** 16-bit data bus, 32-bit address bus → capacity = 2^32 = **4 GB** → answer **(b)**. Only the **address bus** decides how much memory can be addressed. The data bus only decides how many bits move at once (16 bits here), so the "64 K" option (a 16-bit address) is wrong.

## 1. Rule

|Item|Decided by|
|---|---|
|Maximum memory (addressing capacity)|**Address bus width**: 2^n locations|
|Bits transferred at a time|**Data bus width**|
|Word size / processing power|Internal registers and data bus|

## 2. Working for Q107

|Step|Value|
|---|---|
|Address lines|32|
|Locations|2^32 = 4,294,967,296|
|Each location|1 byte|
|Capacity|**4 GB**|
|Data bus|16 bits, so 2 bytes move per transfer (does not change capacity)|

## 3. Address lines → capacity

|Address lines|Locations|Capacity|
|---|---|---|
|8|2^8|256 bytes|
|10|2^10|1 KB|
|12|2^12|4 KB|
|16|2^16|64 KB|
|20|2^20|1 MB|
|24|2^24|16 MB|
|32|2^32|**4 GB**|
|36|2^36|64 GB|
|40|2^40|1 TB|
|64|2^64|16 EB (theoretical)|

## 4. Intel processors

|Processor|Data bus|Address bus|Memory|
|---|---|---|---|
|4004|4-bit|12|4 KB|
|8008|8-bit|14|16 KB|
|8080 / 8085|8-bit|16|64 KB|
|8086|16-bit|20|1 MB|
|8088|8-bit|20|1 MB|
|80286|16-bit|24|16 MB|
|80386|32-bit|32|4 GB|
|80486|32-bit|32|4 GB|
|Pentium|64-bit|32|4 GB|

## 4a. Reading a question

|Wording|Meaning|
|---|---|
|"n-bit data bus"|n bits move at a time|
|"n-bit address bus"|2^n locations|
|"n-bit processor"|Word size (registers / data)|
|"Addressing capacity"|2^(address bits)|

## 5. Formulas

|Item|Formula|
|---|---|
|Capacity|2^(address lines) × size of each location|
|Address lines needed|log2(memory size)|
|Number of locations (K)|2^10 = 1024|
|1 GB|2^30 bytes|
|4 GB|2^32 bytes|

## 6. Practice questions (written by Claude, with answers)

|#|Question|Answer|
|---|---|---|
|1|Capacity with 32-bit address bus|4 GB|
|2|Capacity with 16-bit address bus|64 KB|
|3|Capacity with 20-bit address bus|1 MB|
|4|Capacity with 24-bit address bus|16 MB|
|5|Address lines needed for 1 MB|20|
|6|Address lines needed for 4 KB|12|
|7|Address lines needed for 64 KB|16|
|8|What limits the maximum memory of a CPU|Address bus width|
|9|What does data bus width decide|Bits transferred at a time|
|10|Memory of 8085|64 KB|
|11|Memory of 8086|1 MB|
|12|Memory of 80286|16 MB|
|13|Memory of 80386|4 GB|
|14|32-bit systems can use up to about|4 GB RAM|
|15|Does a wider data bus increase memory capacity|No|
|16|2^30 bytes equals|1 GB|

## 7. Exam tip

"Maximum addressing capacity" → look only at the **address bits**. Ignore the data bus. 32 bits → **4 GB**; 16 bits → 64 KB; 20 bits → 1 MB.

Related: [[LDC_Computer_Vault/Study Notes/System_Buses]], [[LDC_Computer_Vault/Study Notes/Memory_Addressing_and_Hex]]