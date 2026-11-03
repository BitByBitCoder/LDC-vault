[[00 Computer Vault Index]]

# DOS Commands, Windows & Operating System

#computer #dos

**31 questions** · 🟢 15 · 🟡 12 · 🔴 4

## Concept core

| Internal (in COMMAND.COM, loaded at boot) | External (separate file on disk) |
|---|---|
| COPY, DIR, DATE, TIME, VER, VOL, TYPE, DEL, CLS, PROMPT | EDIT, SYS, CHKDSK, FORMAT, DISKCOPY, XCOPY, TREE |

| Command | Does |
|---|---|
| TREE / TREE /F | folder structure / plus files |
| TYPE | show a text file |
| DIR /B, /W, /S | bare names / wide / include subfolders |
| DISKCOPY | whole disk |
| SYS | copy system files (make bootable) |
| CHKDSK | check disk errors and status |

- Program order: compile, link, **load**, run (loader puts it in memory).
- Boot keys: **F8** = Safe Mode, **F2** (or Del) = BIOS setup. **Win + D** = show desktop.
- File systems: FAT = File Allocation Table, **NTFS** = New Technology File System (Windows), EXT2 = Linux.
- Extensions: .bak backup, .rtf WordPad, .txt Notepad.


## Q&A: cover the Answer column, answer, then reveal

Ordered easy to hard. Level is shown **before** the answer. 🔁 = repeated in your paper. ⚠️ = doubtful key, see [[12 Doubtful Keys]].

| Question | Level | Answer + why |
|---|---|---|
| **Q115 · Q410 · Q519** 🔁<br>Command to see the sub-directory structure of a drive:<br>a) Tree  ·  b) List  ·  c) Subdir  ·  d) Subtree | 🟢 Easy | ||**a) Tree** — TREE. Draws the folder tree. (TREE /F also shows files.)|| |
| **Q116**<br>DOS command to see contents of a file:<br>a) Type  ·  b) Copy  ·  c) Ed  ·  d) None | 🟢 Easy | ||**a) Type** — TYPE filename.txt displays a text file.|| |
| **Q121**<br>System program that sets up an executable program in main memory ready for execution:<br>a) Assembler  ·  b) Linker  ·  c) Loader  ·  d) Compiler | 🟢 Easy | ||**c) Loader** — Order: compile, link, LOAD, run. Loader puts it in memory.|| |
| **Q188**<br>File system supported by Windows:<br>a) Kernel File System  ·  b) Virtual File System  ·  c) Second Extended File System (EXT2)  ·  d) NTFS | 🟢 Easy | ||**d) NTFS** — NTFS (Windows). EXT2 = Linux.|| |
| **Q406**<br>Function key pressed during reboot to enter Safe Mode:<br>a) F8  ·  b) F2  ·  c) F1  ·  d) F9 | 🟢 Easy | ||**a) F8** — F8 for Safe Mode. F2/Del = BIOS setup.|| |
| **Q407**<br>FAT stands for:<br>a) File Accommodation Table  ·  b) File Access Tape  ·  c) File Allocation Table  ·  d) File Activity Table | 🟢 Easy | ||**c) File Allocation Table** — File Allocation Table.|| |
| **Q518**<br>Command to duplicate an entire disk:<br>a) Copy  ·  b) Diskcopy  ·  c) Chkdsk  ·  d) Format | 🟢 Easy | ||**b) Diskcopy** — DISKCOPY = whole disk, COPY = files.|| |
| **Q520**<br>Extension suggesting a backup copy:<br>a) .bak  ·  b) .bas  ·  c) .com  ·  d) .txt | 🟢 Easy | ||**a) .bak** — .bak = backup. .bas = BASIC, .com = command file.|| |
| **Q566**<br>Key combination to minimise all open windows:<br>a) Alt+M  ·  b) Windows key + D  ·  c) Shift+M  ·  d) Ctrl+D | 🟢 Easy | ||**b) Windows key + D** — Win+D = show desktop.|| |
| **Q660**<br>Process of dividing the disk into tracks and sectors:<br>a) Tracking  ·  b) Formatting  ·  c) Crashing  ·  d) Allotting | 🟢 Easy | ||**b) Formatting** — Formatting.|| |
| **Q701**<br>Devices automatically detected by Windows:<br>a) Plug & Play  ·  b) Automatic  ·  c) Serial  ·  d) Installed | 🟢 Easy | ||**a) Plug & Play** — Plug and Play (PnP).|| |
| **Q734**<br>Element used to manage computer files and folders:<br>a) Control Panel  ·  b) Windows Accessories  ·  c) Windows Explorer  ·  d) Internet Explorer | 🟢 Easy | ||**c) Windows Explorer** — Windows (File) Explorer.|| |
| **Q818**<br>How many different documents can be opened at once:<br>a) Not more than ten  ·  b) As many as memory can hold  ·  c) As many as taskbar can display  ·  d) None | 🟢 Easy | ||**b) As many as memory can hold** — Limited only by RAM.|| |
| **Q826**<br>'NTFS' stands for:<br>a) New Type File System  ·  b) New Technology File System  ·  c) Transfer  ·  d) Terminal | 🟢 Easy | ||**b) New Technology File System** — New Technology File System.|| |
| **Q907**<br>Programs that control the activities of various components:<br>a) Device driver  ·  b) Application software  ·  c) Operating system  ·  d) DBMS | 🟢 Easy | ||**c) Operating system** — Operating system.|| |
| **Q117**<br>DOS command displaying only file/directory names without size/date/time:<br>a) Dir/w  ·  b) Dir a:  ·  c) Dir /b  ·  d) Dir /s | 🟡 Medium | ||**c) Dir /b** — /b = bare format. /w = wide, /s = include sub-directories.|| |
| **Q122**<br>Loaded into main memory when the computer is booted:<br>a) internal command instructions  ·  b) external command instructions  ·  c) utility programs  ·  d) word processing instructions | 🟡 Medium | ||**a) internal command instructions** — Internal commands (COPY, DIR, TYPE, DEL) live in COMMAND.COM which loads at boot. External commands stay on disk.|| |
| **Q123 · Q413** 🔁<br>Fragmentation of the file system:<br>a) can always be prevented  ·  b) can be temporarily removed by compaction  ·  c) is a characteristic of all file systems  ·  d) None | 🟡 Medium | ||**b) can be temporarily removed by compaction** — Defragmentation/compaction removes it temporarily; it comes back with use.|| |
| **Q345**<br>OS better for implementing client-server network:<br>a) Windows 95  ·  b) Windows 98  ·  c) Windows 2000  ·  d) All | 🟡 Medium | ||**c) Windows 2000** — Windows 2000 had server editions and domain support. 95/98 were desktop OS.|| |
| **Q392**<br>In an operating system each process has its own:<br>a) address space  ·  b) open files  ·  c) pending alarms  ·  d) all of these | 🟡 Medium | ||**d) all of these** — Each process gets its own address space, open files, alarms, etc.|| |
| **Q411**<br>CHKDSK command is used to:<br>a) Analyze error  ·  b) Diagnose error  ·  c) Report status  ·  d) All of the above | 🟡 Medium | ||**d) All of the above** — CHKDSK checks the disk, finds errors and reports status.|| |
| **Q417**<br>Command displaying directory list including files in tree structure:<br>a) Dir /s/f  ·  b) Tree /f  ·  c) Tree /s/f  ·  d) Dir /f | 🟡 Medium | ||**b) Tree /f** — TREE /F = tree + files.|| |
| **Q469**<br>Which can be called modifiers:<br>a) Tab, Caps lock  ·  b) Page Up/Down  ·  c) Alt, Shift or Ctrl  ·  d) Num Lock, Backspace | 🟡 Medium | ||**c) Alt, Shift or Ctrl** — Modifier keys change what another key does: Alt, Shift, Ctrl.|| |
| **Q513**<br>Batch file read while booting a computer:<br>a) Autoexec.bat  ·  b) Auto-batc  ·  c) Autoexecutive.bat  ·  d) Auto.bat | 🟡 Medium | ||**a) Autoexec.bat** — AUTOEXEC.BAT (with CONFIG.SYS).|| |
| **Q515**<br>SYS command is used to:<br>a) Copy system files to disk  ·  b) Copy config files  ·  c) Update files  ·  d) None | 🟡 Medium | ||**a) Copy system files to disk** — SYS copies the system (boot) files to make a disk bootable.|| |
| **Q630**<br>Function key held for entering the BIOS setup menu:<br>a) F9  ·  b) F2  ·  c) F5  ·  d) F3 | 🟡 Medium | ||**b) F2** — F2 (also Del/F10/F12 depending on make). F8 = Safe Mode.|| |
| **Q687**<br>Extension of WordPad:<br>a) .ttf  ·  b) .rtf  ·  c) .txt  ·  d) None | 🟡 Medium | ||**b) .rtf** — WordPad = .rtf (Rich Text Format). Notepad = .txt.|| |
| **Q415**<br>External commands in DOS are:<br>a) Copy, edit  ·  b) Edit, sys, chkdsk  ·  c) Chkdsk, prompt, date  ·  d) Sys, ver, vol | 🔴 Hard | ||**b) Edit, sys, chkdsk** — Internal: COPY, DIR, DATE, TIME, VER, VOL, PROMPT, TYPE, DEL, CLS. External: EDIT, SYS, CHKDSK, FORMAT, DISKCOPY, XCOPY, TREE.|| |
| **Q416**<br>Maximum length of DOS commands:<br>a) 80 chars  ·  b) 127 chars  ·  c) 100 chars  ·  d) 8 chars | 🔴 Hard | ||**b) 127 chars** — 127 characters.|| |
| **Q635**<br>Disk defragmentation means:<br>a) file stored across disks  ·  b) stored in several locations  ·  c) crashed  ·  d) none | 🔴 Hard | ||**b) stored in several locations** ⚠️ — Option (b) describes FRAGMENTATION (file scattered); the question is badly worded but (b) is the usual key.|| |
| **Q820**<br>System software that aims to maintain and make best use of computer resources:<br>a) Utility  ·  b) Application  ·  c) Reservation  ·  d) None | 🔴 Hard | ||**d) None** ⚠️ — Managing and optimising resources is the job of the operating system, which is not listed. Check your key.|| |

> [!warning] Exam Trap ⚠️
> - Only **internal** commands are loaded at boot.
> - Safe Mode = **F8**, BIOS = **F2**.
> - Copy = files, **Diskcopy** = whole disk.
> - Fragmentation can only be *temporarily* removed.

## Self-check
- [ ] Round 1 score: __ / 31
- [ ] Round 2 (next day): __ / 31
- [ ] Round 3 (after 3 days): __ / 31
- Close topic at **85%**. Log in [[15 Progress Tracker]].
