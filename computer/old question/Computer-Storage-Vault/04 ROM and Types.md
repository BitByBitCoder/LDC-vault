---
tags: [storage, rom, prom, eprom, eeprom, flash]
aliases: [ROM, PROM, EPROM, EEPROM, BIOS, CMOS]
---
← [[00 Storage Index]] | ← [[03 Primary Memory]] | Next → [[05 HDD Magnetic Disk]]

# 04 · ROM and Types

**ROM (Read Only Memory):** non-volatile primary memory. Keeps data without power. Stores permanent start-up instructions.

## Evolution chain (memorise in order)
```
MROM ──▶ PROM ──▶ EPROM ──▶ EEPROM ──▶ Flash
fixed    write     erase     erase       erase in
at       once by   with UV   electrically blocks
factory  user      light     (byte-wise) (fast)
```

| Type | Full form | Written by | Erased by | Re-writable? |
|------|-----------|-----------|-----------|--------------|
| **MROM** | Masked ROM | Manufacturer | Cannot | No |
| **PROM** | Programmable ROM | User, **once** (PROM burner) | Cannot | No |
| **EPROM** | Erasable PROM | User | **Ultraviolet light** | Yes |
| **EEPROM** | Electrically EPROM | User | **Electric signal**, byte level | Yes |
| **Flash** | (EEPROM variant) | User | Electric, **block level** | Yes |

## What lives in ROM
- **Bootstrap loader / POST** (Power-On Self-Test).
- **BIOS** (Basic Input Output System), nowadays held in flash so it can be updated.
- **CMOS:** small RAM that stores BIOS settings (date, time, boot order). Kept alive by a **battery**.

## Key facts
- Flash is used in pen drives, SD cards, SSDs, phones.
- Flash was invented by **Fujio Masuoka (Toshiba)** in the 1980s.
- ROM chips are **firmware** carriers.

## 🧪 Self-test
| Question | Answer |
|----------|--------|
| ROM full form | \|\|Read Only Memory\|\| |
| ROM is volatile? | \|\|No, non-volatile\|\| |
| ROM that cannot be changed after manufacture | \|\|MROM\|\| |
| ROM programmable once by user | \|\|PROM\|\| |
| ROM erased by UV light | \|\|EPROM\|\| |
| ROM erased by electricity | \|\|EEPROM\|\| |
| Block-erasable, used in pen drives | \|\|Flash memory\|\| |
| What stores BIOS settings with battery | \|\|CMOS\|\| |
| BIOS full form | \|\|Basic Input Output System\|\| |
| POST full form | \|\|Power-On Self-Test\|\| |
| Program that starts the computer | \|\|Bootstrap loader (in ROM)\|\| |

> [!warning] Exam Trap ⚠️
> **EPROM = UV light. EEPROM = electricity.** And **CMOS is RAM with a battery, not ROM.** BIOS is firmware in ROM/flash; CMOS only stores its settings.
