---
tags: [storage, cloud, nas, san, das]
aliases: [Cloud Storage, NAS, SAN, DAS, Object Storage]
---
← [[00 Storage Index]] | ← [[08 Tape and Legacy]] | Next → [[10 RAID]]

# 09 · Cloud, DAS, NAS, SAN

## Network storage models
```
DAS : [Computer]──cable──[Disk]                  (one machine only)
NAS : [PC][PC][PC]──LAN──[NAS box = file server] (shared FILES)
SAN : [Servers]──fibre network──[Storage array]  (shared BLOCKS, fast)
```
| Type | Full form | Shares | Typical use |
|------|-----------|--------|-------------|
| **DAS** | Direct Attached Storage | Nothing (one host) | Internal HDD, external USB drive |
| **NAS** | Network Attached Storage | **Files** over LAN | Home/office file server |
| **SAN** | Storage Area Network | **Blocks** over dedicated network | Data centres, databases |

## Three data storage types
| Type | Unit | Example |
|------|------|---------|
| **Block** | Fixed blocks | SAN, HDD, databases |
| **File** | Files in folders | NAS, local disk |
| **Object** | Object + metadata + ID | Amazon S3, photos, backups |

## Cloud storage
- Data kept on remote servers in **data centres**, accessed over the **Internet**.
- Pros: access anywhere, backup, scalable, pay-as-you-use.
- Cons: needs Internet, privacy and security concerns, subscription cost.
- **Models:** Public, Private, Hybrid cloud. **Service:** IaaS, PaaS, SaaS.

| Service | Company | Typical free tier* |
|---------|---------|--------------------|
| Google Drive | Google | 15 GB (shared with Gmail, Photos) |
| OneDrive | Microsoft | 5 GB |
| iCloud | Apple | 5 GB |
| Dropbox | Dropbox | 2 GB |
| Amazon S3 | Amazon | Object storage (IaaS) |

*Free tiers change. Verify before an exam if the notification asks for current data.

**Other terms:** **Backup** (copy for recovery), **Archive** (long-term, rarely used), **Data centre** (facility of servers), **Sync** (keep copies identical).

## 🧪 Self-test
| Question | Answer |
|----------|--------|
| NAS full form | \|\|Network Attached Storage\|\| |
| SAN full form | \|\|Storage Area Network\|\| |
| DAS full form | \|\|Direct Attached Storage\|\| |
| NAS shares at what level | \|\|File level\|\| |
| SAN shares at what level | \|\|Block level\|\| |
| Amazon S3 is what kind of storage | \|\|Object storage\|\| |
| Cloud data is stored in | \|\|Data centres (remote servers)\|\| |
| Cloud needs | \|\|Internet connection\|\| |
| Google Drive free storage | \|\|15 GB\|\| |
| Copy kept for recovery | \|\|Backup\|\| |

> [!warning] Exam Trap ⚠️
> **NAS = files, SAN = blocks.** An external USB drive is **DAS**, not NAS.
