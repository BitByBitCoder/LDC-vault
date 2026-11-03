
---

## tags: [computer, ldc, memory, cache, calculation] aliases: [Cache Mapping, Associative Mapping, Direct Mapping, Address Bits]

# Cache Mapping & Address-Bit Calculations

> **Q105:** Main memory 8K bytes, cache 2K words, **associative mapping** → each cache word = **21 bits** → answer **(b)**.

## 1. Solving Q105 step by step

|Step|Working|Result|
|---|---|---|
|Main memory size|8K bytes = 8 × 1024 = 2^13|**13 address bits**|
|Data per word|1 byte|**8 bits**|
|Associative mapping|A block can go in **any** cache line, so the **full address** is stored as the tag|Tag = **13 bits**|
|Each cache word|Tag + data = 13 + 8|**21 bits**|

**Rule:** associative mapping → tag = full address. So cache word = address bits + data bits.

## 2. Powers of 2 to remember

|Size|Power|Address bits|
|---|---|---|
|1K|2^10|10|
|2K|2^11|11|
|4K|2^12|12|
|8K|2^13|13|
|16K|2^14|14|
|32K|2^15|15|
|64K|2^16|16|
|1M|2^20|20|
|1G|2^30|30|

## 3. Three mapping methods

|Method|Where a block can go|Address split|Tag size|
|---|---|---|---|
|**Associative**|Any cache line|Tag + Word|**Full address** (largest)|
|**Direct**|One fixed line|Tag + Line + Word|Address − line bits − word bits|
|**Set-associative**|Any line in one set|Tag + Set + Word|Address − set bits − word bits|

|Method|Speed of search|Hardware cost|Conflict misses|
|---|---|---|---|
|Associative|Slowest search (compares all tags)|Highest|None|
|Direct|Fastest|Lowest|Most|
|Set-associative|Medium|Medium|Fewer|

## 4. Direct mapping example (for comparison)

Main memory 8K bytes (13 bits), cache 2K lines (11 bits), 1 byte per line:

|Field|Bits|
|---|---|
|Line (index)|11|
|Tag|13 − 11 = 2|
|Data|8|
|Each cache word|2 + 8 = **10 bits**|

## 5. Formulas

|Item|Formula|
|---|---|
|Address bits|log2(memory size in words/bytes)|
|Memory size|2^(address bits)|
|Hit ratio|Hits ÷ (Hits + Misses)|
|Average access time|h × Tc + (1 − h) × Tm|
|Cache lines|Cache size ÷ block size|

_h = hit ratio, Tc = cache access time, Tm = main memory access time._

## 6. Practice questions (written by Claude, with answers)

|#|Question|Answer|
|---|---|---|
|1|Address bits for 8K bytes|13|
|2|Address bits for 4K bytes|12|
|3|Address bits for 64K bytes|16|
|4|Address bits for 1M bytes|20|
|5|Memory in 2^11 locations|2K|
|6|Main memory 4K bytes, associative cache, 8-bit data: bits per cache word|12 + 8 = 20|
|7|Main memory 16K bytes, associative cache, 8-bit data: bits per cache word|14 + 8 = 22|
|8|Main memory 64K bytes, associative cache, 8-bit data: bits per cache word|16 + 8 = 24|
|9|Associative mapping tag stores|Full address|
|10|Mapping where a block goes to one fixed line|Direct mapping|
|11|Mapping where a block can go anywhere|Associative mapping|
|12|Mapping that combines both ideas|Set-associative mapping|
|13|Fastest to search|Direct mapping|
|14|Costliest hardware|Associative mapping|
|15|Hit ratio 0.9, Tc = 10 ns, Tm = 100 ns: average access time|0.9×10 + 0.1×100 = 19 ns|
|16|2K words cache, direct mapping from 8K memory, 1 byte data: bits per word|10|

## 7. Exam tip

Associative-mapping size question: convert memory size to **address bits**, add the **data bits**. 8K bytes → 13 + 8 = **21**.