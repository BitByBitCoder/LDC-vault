---
tags: [storage, summary, comparison]
aliases: [Storage Cheat Sheet, One Page Summary]
---
← [[00 Storage Index]] | ← [[13 Exam Traps and Rapid Fire]]

# 14 · Master Comparison Table (one page)

| Device | Class | Technology | Volatile? | Access | Typical capacity | Note |
|--------|-------|-----------|-----------|--------|------------------|------|
| [[03 Primary Memory\|Register]] | Primary | CPU logic | Yes | Direct | Bytes | Fastest |
| [[03 Primary Memory\|Cache]] | Primary | SRAM | Yes | Direct | KB to MB | L1, L2, L3 |
| [[03 Primary Memory\|RAM]] | Primary | DRAM | Yes | Random | GB | Main memory |
| [[04 ROM and Types\|ROM]] | Primary | Chip | **No** | Read only | KB to MB | Boot, BIOS |
| [[04 ROM and Types\|Flash]] | Secondary | NAND/NOR | No | Direct | GB to TB | Pen drive, SSD |
| [[05 HDD Magnetic Disk\|HDD]] | Secondary | Magnetic | No | Direct | GB to TB | Cheap per GB |
| [[06 SSD and Flash\|SSD]] | Secondary | NAND flash | No | Direct | GB to TB | Fast, no moving parts |
| [[07 Optical Discs\|CD]] | Secondary | Laser, pits | No | Direct | 700 MB | Infrared |
| [[07 Optical Discs\|DVD]] | Secondary | Laser, pits | No | Direct | 4.7 / 8.5 GB | Red laser |
| [[07 Optical Discs\|Blu-ray]] | Secondary | Laser, pits | No | Direct | 25 / 50 GB | Blue-violet |
| [[08 Tape and Legacy\|Tape]] | Tertiary | Magnetic | No | **Sequential** | TB (LTO) | Backup, cheapest |
| [[08 Tape and Legacy\|Floppy]] | Secondary | Magnetic | No | Direct | 1.44 MB | Obsolete |
| [[09 Cloud DAS NAS SAN\|Cloud]] | Tertiary/Remote | Servers | No | Network | Huge | Needs Internet |

## Speed ranking (fast → slow)
`Register > Cache > RAM > SSD > HDD > Optical > Tape`

## Capacity ranking (small → large)
`Register < Cache < RAM < SSD/HDD < Tape/Cloud`

## Cost per GB (high → low)
`Register > Cache > RAM > SSD > HDD > Optical > Tape`

## Memory trick chains
- **ROM:** *M*any *P*eople *E*at *E*ggs *F*ast → MROM, PROM, EPROM, EEPROM, Flash
- **Disc capacity:** *C*ats *D*ream *B*ig → CD 700 MB, DVD 4.7 GB, BD 25 GB
- **RAID min disks:** 0→2, 1→2, 5→3, 6→4, 10→4
