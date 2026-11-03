
---

## tags: [computer, ldc, memory, cache] aliases: [Cache, Locality of Reference, Memory Hierarchy]

# Cache Memory

> **Answer: (d) all of the above.** Cache works because programs reuse the same data and instructions again and again. This is called **locality of reference**. The **90-10 rule** says a program spends about 90% of its time running about 10% of its code. Both mean that memory references **tend to cluster**, so keeping that small part in fast memory speeds everything up.

## 1. What is cache?

|Point|Detail|
|---|---|
|Definition|Small, very fast memory placed between the CPU and RAM|
|Purpose|Reduce the speed gap between fast CPU and slower RAM|
|Stores|Frequently used data and instructions|
|Type|Made of SRAM (Static RAM)|
|Nature|Volatile|
|Managed by|Hardware (automatic), not the user|
|Cost|Expensive, so small in size|

## 2. Locality of reference

|Type|Meaning|Example|
|---|---|---|
|Temporal locality|Recently used item is likely to be used again soon|Loop counter, loop instructions|
|Spatial locality|Items near a used item are likely to be used next|Array elements, sequential instructions|

## 3. Cache terms

|Term|Meaning|
|---|---|
|Cache hit|Data is found in the cache|
|Cache miss|Data is not in the cache, so it is fetched from RAM|
|Hit ratio|Hits ÷ total accesses|
|Miss penalty|Extra time to fetch data after a miss|
|Block / line|Unit of data moved into the cache|
|Write-through|Write to cache and RAM together|
|Write-back|Write to cache first, RAM later|

## 4. Cache levels

|Level|Location|Size|Speed|
|---|---|---|---|
|L1|Inside CPU core|Smallest (KB)|Fastest|
|L2|In or near CPU|Medium (KB–MB)|Fast|
|L3|Shared by cores|Largest (MB)|Slower than L1, L2|

## 5. Mapping methods

|Method|Idea|
|---|---|
|Direct mapping|Each memory block goes to one fixed cache line|
|Associative mapping|A block can go in any cache line|
|Set-associative mapping|A block goes to any line within a set|

## 6. Replacement algorithms

|Algorithm|Meaning|
|---|---|
|LRU|Least Recently Used|
|FIFO|First In First Out|
|LFU|Least Frequently Used|
|Random|A random block is replaced|

## 7. Memory hierarchy (fast to slow)

|Rank|Memory|Speed / cost|
|---|---|---|
|1|Registers|Fastest, costliest|
|2|Cache|Very fast|
|3|Main memory (RAM)|Fast|
|4|Secondary (HDD / SSD)|Slow|
|5|Tertiary (tape, optical)|Slowest, cheapest|

## 8. Other related memory

|Term|Meaning|
|---|---|
|Virtual memory|Part of the hard disk used as extra RAM|
|Buffer|Temporary holding area when speeds differ|
|Register|Tiny storage inside the CPU|
|Main memory|RAM, holds running programs|
|Secondary memory|Permanent storage (disk)|

## 9. Practice questions (written by Claude, with answers)

|#|Question|Answer|
|---|---|---|
|1|Cache memory is placed between|CPU and RAM|
|2|Cache memory is made of|SRAM|
|3|Cache memory is based on|Locality of reference|
|4|Data found in cache is called a|Cache hit|
|5|Data not found in cache is called a|Cache miss|
|6|Fastest memory after registers|Cache|
|7|Cache is faster than|RAM|
|8|Which cache level is fastest|L1|
|9|Which cache level is largest|L3|
|10|Purpose of cache memory|Speed up CPU access to data|
|11|Recently used data likely to be reused|Temporal locality|
|12|Nearby data likely to be used next|Spatial locality|
|13|LRU stands for|Least Recently Used|
|14|Cache memory is|Volatile|
|15|Which is costlier per byte: cache or RAM|Cache|
|16|Part of hard disk used as RAM|Virtual memory|
|17|Hit ratio is|Hits ÷ total accesses|
|18|Cache is managed by|Hardware|

## 10. Exam tip

"Cache works because of ..." → **locality of reference**. If the options list locality, the 90-10 rule and clustering of references, pick **all of the above**.