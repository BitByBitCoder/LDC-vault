[[00 Computer Vault Index]]

# DOS, Windows & Operating System

#computer #dos

**Part 1: learn the topic** (tables). **Part 2: past questions** (31: 🟢 15 · 🟡 12 · 🔴 4). Read Part 1 first, then test yourself in Part 2.

# Part 1: Learn the topic

## 1. Internal and external commands

| Internal (in COMMAND.COM, loaded at boot) | External (file on disk) |
|---|---|
| COPY, DIR, DATE, TIME | EDIT, SYS |
| VER, VOL, TYPE | CHKDSK, FORMAT |
| DEL, CLS, PROMPT | DISKCOPY, XCOPY, TREE |

Only **internal** commands are in memory after boot. Max command length = **127** characters.

## 2. Important commands

| Command | Does |
|---|---|
| TREE | folder structure of a drive |
| TREE /F | folders **and files** |
| TYPE file | show a text file |
| DIR | list files |
| DIR /B | **bare** names only, no size or date |
| DIR /W | wide list |
| DIR /S | include sub-directories |
| COPY | copy files |
| DISKCOPY | copy a **whole disk** |
| SYS | copy system files so disk can boot |
| CHKDSK | check disk, find errors, report status |
| FORMAT | prepare disk: tracks and sectors |
| DEL | delete |

Wildcards: `*` = any characters, `?` = one character.

## 3. Boot process

```mermaid
graph LR
A[Power on] --> B[POST self test] --> C[BIOS] --> D[Boot loader] --> E[OS loaded]
```

| Key | Used for |
|---|---|
| **F8** | Safe Mode (during boot) |
| **F2** (or Del) | BIOS setup |
| AUTOEXEC.BAT | batch file read at DOS boot (with CONFIG.SYS) |

## 4. File systems

| System | Notes |
|---|---|
| FAT | **File Allocation Table** (old DOS/Windows) |
| NTFS | **New Technology File System**, Windows NT onwards |
| exFAT | pen drives |
| EXT2/3/4 | Linux |

**Fragmentation**: file stored in scattered pieces. **Defragmentation** or compaction joins them, but only **temporarily**.

## 5. File extensions

| Extension | Type |
|---|---|
| .exe .com | executable |
| .bat | batch file |
| .sys | system file |
| .bak | **backup** |
| .txt | Notepad text |
| .rtf | **WordPad** |
| .docx | Word |
| .xlsx | Excel |
| .pptx | PowerPoint |
| .jpg .gif | images |
| .wav .mid | sound |

## 6. Operating system

| Function | Meaning |
|---|---|
| Process management | each process has its own **address space**, open files, alarms |
| Memory management | allocate RAM |
| File management | files and folders |
| Device management | drivers, **Plug and Play** detection |
| Resource management | the OS manages and optimises resources |

| OS type | Example |
|---|---|
| Batch | early mainframes |
| Multiprogramming | several jobs in memory |
| Time-sharing | many users share CPU time |
| Real-time | missile, ATM |
| Network / server | Windows 2000 server, Linux |

Loader = system program that puts an executable program into main memory. Order: compile, link, **load**, run.

## 7. Windows shortcuts

| Keys | Action |
|---|---|
| Win + D | show desktop, minimise all |
| Win + E | File Explorer |
| Win + L | lock |
| Alt + Tab | switch window |
| Ctrl + Alt + Del | security screen, Task Manager |
| Win + R | Run |

**Windows (File) Explorer** manages files and folders. Modifier keys = **Alt, Shift, Ctrl** (change what another key does).

# Part 2: Past questions with answers

Answer in your head first, then open the callout. Level is shown before the answer. 🔁 = repeated in your paper. ⚠️ = doubtful key ([[12 Doubtful Keys]]).

### Q115 · Q410 · Q519 🔁 · 🟢 Easy
**Q.** Command to see the sub-directory structure of a drive ____

> [!success]- Answer
> **Tree**
> TREE. Draws the folder tree. (TREE /F also shows files.)
> Don't confuse with: List; Subdir; Subtree

### Q116 · 🟢 Easy
**Q.** DOS command to see contents of a file ____

> [!success]- Answer
> **Type**
> TYPE filename.txt displays a text file.
> Don't confuse with: Copy; Ed; None

### Q121 · 🟢 Easy
**Q.** System program that sets up an executable program in main memory ready for execution ____

> [!success]- Answer
> **Loader**
> Order: compile, link, LOAD, run. Loader puts it in memory.
> Don't confuse with: Assembler; Linker; Compiler

### Q188 · 🟢 Easy
**Q.** File system supported by Windows ____

> [!success]- Answer
> **NTFS**
> NTFS (Windows). EXT2 = Linux.
> Don't confuse with: Kernel File System; Virtual File System; Second Extended File System (EXT2)

### Q406 · 🟢 Easy
**Q.** Function key pressed during reboot to enter Safe Mode ____

> [!success]- Answer
> **F8**
> F8 for Safe Mode. F2/Del = BIOS setup.
> Don't confuse with: F2; F1; F9

### Q407 · 🟢 Easy
**Q.** FAT stands for ____

> [!success]- Answer
> **File Allocation Table**
> File Allocation Table.
> Don't confuse with: File Accommodation Table; File Access Tape; File Activity Table

### Q518 · 🟢 Easy
**Q.** Command to duplicate an entire disk ____

> [!success]- Answer
> **Diskcopy**
> DISKCOPY = whole disk, COPY = files.
> Don't confuse with: Copy; Chkdsk; Format

### Q520 · 🟢 Easy
**Q.** Extension suggesting a backup copy ____

> [!success]- Answer
> **.bak**
> .bak = backup. .bas = BASIC, .com = command file.
> Don't confuse with: .bas; .com; .txt

### Q566 · 🟢 Easy
**Q.** Key combination to minimise all open windows ____

> [!success]- Answer
> **Windows key + D**
> Win+D = show desktop.
> Don't confuse with: Alt+M; Shift+M; Ctrl+D

### Q660 · 🟢 Easy
**Q.** Process of dividing the disk into tracks and sectors ____

> [!success]- Answer
> **Formatting**
> Formatting.
> Don't confuse with: Tracking; Crashing; Allotting

### Q701 · 🟢 Easy
**Q.** Devices automatically detected by Windows ____

> [!success]- Answer
> **Plug & Play**
> Plug and Play (PnP).
> Don't confuse with: Automatic; Serial; Installed

### Q734 · 🟢 Easy
**Q.** Element used to manage computer files and folders ____

> [!success]- Answer
> **Windows Explorer**
> Windows (File) Explorer.
> Don't confuse with: Control Panel; Windows Accessories; Internet Explorer

### Q818 · 🟢 Easy
**Q.** How many different documents can be opened at once?

> [!success]- Answer
> **As many as memory can hold**
> Limited only by RAM.
> Don't confuse with: Not more than ten; As many as taskbar can display; None

### Q826 · 🟢 Easy
**Q.** 'NTFS' stands for ____

> [!success]- Answer
> **New Technology File System**
> New Technology File System.
> Don't confuse with: New Type File System; Transfer; Terminal

### Q907 · 🟢 Easy
**Q.** Programs that control the activities of various components ____

> [!success]- Answer
> **Operating system**
> Operating system.
> Don't confuse with: Device driver; Application software; DBMS

### Q117 · 🟡 Medium
**Q.** DOS command displaying only file/directory names without size/date/time ____

> [!success]- Answer
> **Dir /b**
> /b = bare format. /w = wide, /s = include sub-directories.
> Don't confuse with: Dir/w; Dir a:; Dir /s

### Q122 · 🟡 Medium
**Q.** Loaded into main memory when the computer is booted ____

> [!success]- Answer
> **internal command instructions**
> Internal commands (COPY, DIR, TYPE, DEL) live in COMMAND.COM which loads at boot. External commands stay on disk.
> Don't confuse with: external command instructions; utility programs; word processing instructions

### Q123 · Q413 🔁 · 🟡 Medium
**Q.** Fragmentation of the file system ____

> [!success]- Answer
> **can be temporarily removed by compaction**
> Defragmentation/compaction removes it temporarily; it comes back with use.
> Don't confuse with: can always be prevented; is a characteristic of all file systems; None

### Q345 · 🟡 Medium
**Q.** OS better for implementing client-server network ____

> [!success]- Answer
> **Windows 2000**
> Windows 2000 had server editions and domain support. 95/98 were desktop OS.
> Don't confuse with: Windows 95; Windows 98; All

### Q392 · 🟡 Medium
**Q.** In an operating system each process has its own ____

> [!success]- Answer
> **all of these**
> Each process gets its own address space, open files, alarms, etc.
> Don't confuse with: address space; open files; pending alarms

### Q411 · 🟡 Medium
**Q.** CHKDSK command is used to ____

> [!success]- Answer
> **All of the above**
> CHKDSK checks the disk, finds errors and reports status.
> Don't confuse with: Analyze error; Diagnose error; Report status

### Q417 · 🟡 Medium
**Q.** Command displaying directory list including files in tree structure ____

> [!success]- Answer
> **Tree /f**
> TREE /F = tree + files.
> Don't confuse with: Dir /s/f; Tree /s/f; Dir /f

### Q469 · 🟡 Medium
**Q.** Which can be called modifiers?

> [!success]- Answer
> **Alt, Shift or Ctrl**
> Modifier keys change what another key does: Alt, Shift, Ctrl.
> Don't confuse with: Tab, Caps lock; Page Up/Down; Num Lock, Backspace

### Q513 · 🟡 Medium
**Q.** Batch file read while booting a computer ____

> [!success]- Answer
> **Autoexec.bat**
> AUTOEXEC.BAT (with CONFIG.SYS).
> Don't confuse with: Auto-batc; Autoexecutive.bat; Auto.bat

### Q515 · 🟡 Medium
**Q.** SYS command is used to ____

> [!success]- Answer
> **Copy system files to disk**
> SYS copies the system (boot) files to make a disk bootable.
> Don't confuse with: Copy config files; Update files; None

### Q630 · 🟡 Medium
**Q.** Function key held for entering the BIOS setup menu ____

> [!success]- Answer
> **F2**
> F2 (also Del/F10/F12 depending on make). F8 = Safe Mode.
> Don't confuse with: F9; F5; F3

### Q687 · 🟡 Medium
**Q.** Extension of WordPad ____

> [!success]- Answer
> **.rtf**
> WordPad = .rtf (Rich Text Format). Notepad = .txt.
> Don't confuse with: .ttf; .txt; None

### Q415 · 🔴 Hard
**Q.** External commands in DOS are ____

> [!success]- Answer
> **Edit, sys, chkdsk**
> Internal: COPY, DIR, DATE, TIME, VER, VOL, PROMPT, TYPE, DEL, CLS. External: EDIT, SYS, CHKDSK, FORMAT, DISKCOPY, XCOPY, TREE.
> Don't confuse with: Copy, edit; Chkdsk, prompt, date; Sys, ver, vol

### Q416 · 🔴 Hard
**Q.** Maximum length of DOS commands ____

> [!success]- Answer
> **127 chars**
> 127 characters.
> Don't confuse with: 80 chars; 100 chars; 8 chars

### Q635 · 🔴 Hard
**Q.** Disk defragmentation means ____

> [!success]- Answer
> **stored in several locations** ⚠️
> Option (b) describes FRAGMENTATION (file scattered); the question is badly worded but (b) is the usual key.
> Don't confuse with: file stored across disks; crashed; none

### Q820 · 🔴 Hard
**Q.** System software that aims to maintain and make best use of computer resources ____

> [!success]- Answer
> **None** ⚠️
> Managing and optimising resources is the job of the operating system, which is not listed. Check your key.
> Don't confuse with: Utility; Application; Reservation

> [!warning] Exam Trap ⚠️
> - Internal commands load at boot. External do not.
> - Safe Mode = **F8**. BIOS setup = **F2**.
> - COPY = files. **DISKCOPY** = whole disk.
> - Fragmentation is removed only *temporarily*.
> - .rtf = WordPad, .txt = Notepad.

## Self-check
- [ ] Round 1: __ / 31
- [ ] Round 2 (next day): __ / 31
- [ ] Round 3 (3 days later): __ / 31
- Close the topic at **85%**. Log it in [[15 Progress Tracker]].
