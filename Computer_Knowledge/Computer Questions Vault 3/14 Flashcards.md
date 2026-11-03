[[00 Computer Vault Index]]

# Flashcards

#flashcards

Format: `front::back` (Spaced Repetition plugin).

Q83: Samples/bit-depth in a DVD-audio digital sound system ____::24-bit. DVD-Audio supports 16, 20 and 24-bit. 24-bit is the maximum (CD audio is only 16-bit).

Q92: Memory location addresses are limited to the range ____::00000 to 9FFFF(16). Addresses start at 00000 (never 00001). 00000-9FFFF hex = 640 KB, the DOS-era conventional memory.

Q102: The idea of cache memory is based ____::all of the above. All three say the same thing: programs reuse nearby and recent data. If two or more options are true, pick 'all of the above'.

Q104: Generally Dynamic RAM is used as main memory because it ____::consumes less power. DRAM = 1 transistor + 1 capacitor per bit: dense, cheap, low power. Refreshing (d) is a drawback, 'lower density' (c) is false, and SRAM is faster (b). Keys differ on this one; (a) is the commonly accepted answer.

Q105: Main memory is 8K bytes, cache is 2K words, associative mapping. Each word of cache shall be ____::21 bits. See Math Corner. Address = 13 bits (8K = 2^13), data = 8 bits (byte). Associative mapping stores full address + data in each cache word: 13 + 8 = 21.

Q107: Maximum addressing capacity of a microprocessor with 16-bit data bus and 32-bit address bus ____::4 GB. Capacity depends on the ADDRESS bus only: 2^32 = 4 GB. The 16-bit data bus is a distraction (64K would be 16 address bits).

Q165: Which memory has equal time to access any location?::RAM. RAM = Random Access Memory: any location, same time.

Q167: 1Kb (1024 bit) memory organised as 1Kx1: number of address lines needed ____::10. 1K = 1024 = 2^10 locations, so 10 address lines. (x1 means 1 bit per location.)

Q168: Commonly used Pen Drive nowadays uses ____::NAND flash. NAND flash = pen drives, SSDs, memory cards (cheap, dense, block access). NOR flash = firmware/code storage.

Q169: Track organisation in an optical disk ____::Spiral. CD/DVD has ONE spiral track. Magnetic disks (HDD) use concentric circles.

Q232: Mainly used for checking objective-type answer papers ____::OMR. OMR = Optical MARK Recognition (bubbles). OCR = characters, MICR = magnetic ink (bank cheques).

Q358: Main memory of a computer is ____::Internal. Main memory (RAM) is internal/primary. Auxiliary = secondary storage (HDD etc.).

Q376 · Q486: In magnetic disks, data is organised on the platter in concentric rings called ____::Track. Rings = tracks. Tracks are cut into sectors (pie slices).

Q377: Performance of cache memory is measured by ____::hit ratio. Hit ratio = (hits / total accesses). Higher = better cache.

Q387: Printer using dry ink powder ____::Laser printer. Laser printers use toner (dry powder). Inkjet = liquid ink.

Q405: Medium to convert text into spoken sentences ____::Speech Synthesizers. Text-to-speech = speech synthesizer.

Q485: Non-volatile chip that stores date and configuration ____::CMOS. CMOS (battery-backed) stores BIOS settings, date and time.

Q493: ROM manufactured without initial storage is termed ____::PROM. PROM = blank chip the user programs ONCE. Plain ROM is programmed at the factory.

Q494: Optical storage can be defined as ____::laser used for retrieval. CD/DVD/Blu-ray: data read with a laser.

Q498: Memory that must be refreshed many times per second ____::Dynamic RAM. DRAM's capacitors leak, so they need refresh. Static RAM does not.

Q508: Popular type of handheld computer ____::smart phone. Smartphone is the modern answer (PDA is the older textbook answer). Older keys may say PDA.

Q553: IC chips are usually made of ____::Silicon. Silicon (semiconductor). 'Silicon Valley'.

Q571: Device providing communication between computer and outer world ____::Input/Output. I/O devices connect the computer to the outside world.

Q572: Each pixel on a screen is composed of how many colour dots ____::3. Red + Green + Blue = 3 sub-pixels (RGB).

Q573: Temporary storage to compensate for difference in data rate ____::Buffer. Buffer smooths speed mismatch (e.g., printer vs CPU, video streaming).

Q707: Memory type that can be erased by light ____::EPROM. EPROM = Erasable by UV light. EEPROM = Electrically erasable.

Q805: Lowest cost-per-bit storage ____::Magnetic Tape. Cost per bit rises as speed rises. Tape is cheapest and slowest (archival).

Q455: Reduced size version of a digital image ____::Thumbnail. Thumbnail = small preview image.

Q161: Fixed number of memory cells processed as a group ____::Word. Word = unit the CPU handles at once (word length: 8/16/32/64 bits).

Q95 · Q381: The address bus flows ____::Unidirection. Address bus is ONE-WAY: CPU to memory/I/O (CPU says where). Data bus is two-way. Hook: Address = Away.

Q96 · Q382 · Q495: Status register is also called ____::Flags. Holds condition flags (zero, carry, sign, overflow). Also called Flag register / PSW.

Q106: Communication between microcomputer components takes place via the address and ____::Data bus. Standard buses = address + data + control. 'Address' is already given and (c) repeats it, so the missing partner is Data bus.

Q164 · Q391: Register containing the address of the next instruction ____::Program counter. PC = address of NEXT instruction. IR = the instruction being executed now.

Q483: Output of ALU operations is stored in ____::Registers. ALU results go to a register (usually the accumulator). Flags only record status.

Q484: Data is distributed through the system in the order ____::Input, Processing, Memory, Storage, Output. The IPO cycle with storage: Input, Processing, Memory, Storage, Output.

Q487: Common bus specification with the fastest data transfer rate ____::PCI. PCI is fastest of the three. ISA is the oldest and slowest.

Q488: Bus used to connect the monitor to the CPU ____::PCI bus. Graphics cards sat on PCI (later AGP/PCIe). SCSI = disks, Rambus = RAM.

Q489: Built-in set of machine code instructions of a computer ____::instruction set. Instruction set = all machine instructions the CPU understands.

Q491: Which category of microprocessor instructions detect status conditions?::Operation. Arithmetic/logic 'operation' instructions set the status flags. Doubtful question; verify against your key.

Q497: Contains processing unit and a small amount of memory ____::Microcontroller. Microcontroller = CPU + small RAM/ROM + I/O on one chip. Microprocessor = CPU only.

Q504: A machine language instruction format consists of ____::Operation code and operand. Opcode (what to do) + operand (what to do it on).

Q554: Control unit's function in the CPU ____::decode instructions. CU fetches and decodes instructions and directs other parts. ALU does logic.

Q777: Internal memory in a processor consists of ____::set of registers. CPU's internal memory = registers.

Q902: ______ unit sends the processed results to the user ____::Output. Output unit.

Q86 · Q400: In an analog computer ____::Input is never converted to digital form. Analog computers work on continuous physical quantities (voltage, pressure) directly, no digital conversion.

Q159: First computer that used the stored program concept ____::EDSAC. EDSAC (1949) ran the first practical stored program. ENIAC was rewired by hand.

Q180: Performance of a supercomputer is measured in ____::Floating point operations per second. Supercomputers = FLOPS. PCs = MIPS/GHz.

Q254: The first printer was invented by ____::None of the above. Carlson = photocopier (xerography), Gestetner = stencil duplicator, Xerox = company. First printer concept is credited to Charles Babbage, so 'None'.

Q256: Inventor of Bluetooth technology ____::Jaap Haartsen. Jaap Haartsen (Ericsson). O'Sullivan = Wi-Fi.

Q258: Supercomputer developed in India ____::Saga-220. Saga-220 (ISRO). Titan, Mira, Vulcan are American.

Q269: NOT a supercomputer developed in India ____ (choose from: a) Eka; b) Mira; c) Saga-220; d) Param)::Mira. Indian: Param, Eka, Saga-220, Pratyush. Mira is IBM (USA).

Q271: Generation that introduced SMS in wireless communication ____::2G. 1G analog voice; 2G digital voice + SMS; 3G mobile internet/video; 4G broadband (LTE).

Q278: Android 9 (released 6 Aug 2018) name ____::Pie. Android 9 = Pie. Order: Oreo (8), Pie (9), then numbers from 10.

Q284: Layers a Photoshop image can have ____::8000. Up to 8000 layers (from CS6 onward).

Q285: The term morphing comes from Morphe, a ____::Greek word. Morphe = Greek for 'form/shape'.

Q287: Word length of mainframe computers ____::48-64 bits. Mainframe 48-64 bits (minicomputers around 16-32, micro 8-64).

Q291: In the IT world, m-business relates to ____::Mobile business. m = mobile.

Q292: Choose the odd one ____ (choose from: a) HAN; b) LAN; c) VPN; d) VSN)::VSN. HAN (Home Area), LAN and VPN are real network types; VSN is not a standard term. Verify against your key.

Q294: A standard Windows keyboard has how many keys ____::104. Old IBM enhanced keyboard = 101. Windows keyboard adds 3 keys (2 Win + 1 Menu) = 104.

Q308: IT company nicknamed 'The Big Blue' ____::IBM. IBM = Big Blue.

Q362: First Indian state to launch its official 'T-wallet' ____::Telangana. T-Wallet = Telangana (T for Telangana).

Q461: First calculating device ____::Abacus. Abacus (~2400 BC). Pascaline = first mechanical calculator.

Q468: First virus detected on ARPANET ____::Creeper. Creeper (1971). Reaper was the program written to delete it.

Q481: Batch processing was mainly used in which generation ____::Second. Second gen (transistors): batch processing, assembly language, COBOL/FORTRAN. Third gen: multiprogramming, OS.

Q557: Father of artificial intelligence ____::John McCarthy. McCarthy coined 'AI' (1956) and created LISP. Babbage = father of computer.

Q558: Vint Cerf is known as the father of the ____::Internet. Vint Cerf and Bob Kahn = TCP/IP, 'fathers of the Internet'.

Q562: 'O level' stands for ____::Ordinary level. O level = Ordinary level (NIELIT/DOEACC course).

Q574: Latest major release of Microsoft's Windows NT operating system ____::Windows 11. Every modern Windows (XP onward, up to 11) is built on the NT kernel, so the newest = Windows 11.

Q593: Name of the first network ____::ARPANET. ARPANET (1969, US DoD).

Q664: First person to use the internet ____::Charlie Kline. Charley Kline sent the first ARPANET message in 1969 ('LO', crashed before 'LOGIN').

Q669: Title of the first YouTube video ____::Me at the Zoo. 'Me at the zoo' (Jawed Karim, 2005).

Q672: Generation of computers that introduced connection to printers ____::Second. Printers (line printers) arrived with second-gen machines. Doubtful; check your key.

Q678: UNIVAC is ____::Universal Automatic Computer. UNIVAC = UNIVersal Automatic Computer (first commercial computer, 1951).

Q683: Fifth generation of computers is also known as ____::Knowledge Information Processing System. 5th gen = AI, KIPS, ULSI. VLSI is 4th gen.

Q875: First spreadsheet program ____::VisiCalc. VisiCalc (1979, Apple II).

Q718: First graphical browser for the WWW ____::Mosaic. Mosaic (1993). Lynx = text-only. WorldWideWeb was first browser overall.

Q655: Computer that processes both analog and digital data ____::Hybrid. Hybrid = analog + digital (used in hospitals ECG, petrol pumps).

Q115 · Q410 · Q519: Command to see the sub-directory structure of a drive ____::Tree. TREE. Draws the folder tree. (TREE /F also shows files.)

Q116: DOS command to see contents of a file ____::Type. TYPE filename.txt displays a text file.

Q117: DOS command displaying only file/directory names without size/date/time ____::Dir /b. /b = bare format. /w = wide, /s = include sub-directories.

Q121: System program that sets up an executable program in main memory ready for execution ____::Loader. Order: compile, link, LOAD, run. Loader puts it in memory.

Q122: Loaded into main memory when the computer is booted ____::internal command instructions. Internal commands (COPY, DIR, TYPE, DEL) live in COMMAND.COM which loads at boot. External commands stay on disk.

Q123 · Q413: Fragmentation of the file system ____::can be temporarily removed by compaction. Defragmentation/compaction removes it temporarily; it comes back with use.

Q188: File system supported by Windows ____::NTFS. NTFS (Windows). EXT2 = Linux.

Q826: 'NTFS' stands for ____::New Technology File System. New Technology File System.

Q392: In an operating system each process has its own ____::all of these. Each process gets its own address space, open files, alarms, etc.

Q406: Function key pressed during reboot to enter Safe Mode ____::F8. F8 for Safe Mode. F2/Del = BIOS setup.

Q407: FAT stands for ____::File Allocation Table. File Allocation Table.

Q411: CHKDSK command is used to ____::All of the above. CHKDSK checks the disk, finds errors and reports status.

Q415: External commands in DOS are ____::Edit, sys, chkdsk. Internal: COPY, DIR, DATE, TIME, VER, VOL, PROMPT, TYPE, DEL, CLS. External: EDIT, SYS, CHKDSK, FORMAT, DISKCOPY, XCOPY, TREE.

Q416: Maximum length of DOS commands ____::127 chars. 127 characters.

Q417: Command displaying directory list including files in tree structure ____::Tree /f. TREE /F = tree + files.

Q513: Batch file read while booting a computer ____::Autoexec.bat. AUTOEXEC.BAT (with CONFIG.SYS).

Q515: SYS command is used to ____::Copy system files to disk. SYS copies the system (boot) files to make a disk bootable.

Q518: Command to duplicate an entire disk ____::Diskcopy. DISKCOPY = whole disk, COPY = files.

Q520: Extension suggesting a backup copy ____::.bak. .bak = backup. .bas = BASIC, .com = command file.

Q630: Function key held for entering the BIOS setup menu ____::F2. F2 (also Del/F10/F12 depending on make). F8 = Safe Mode.

Q635: Disk defragmentation means ____::stored in several locations. Option (b) describes FRAGMENTATION (file scattered); the question is badly worded but (b) is the usual key.

Q660: Process of dividing the disk into tracks and sectors ____::Formatting. Formatting.

Q687: Extension of WordPad ____::.rtf. WordPad = .rtf (Rich Text Format). Notepad = .txt.

Q701: Devices automatically detected by Windows ____::Plug & Play. Plug and Play (PnP).

Q734: Element used to manage computer files and folders ____::Windows Explorer. Windows (File) Explorer.

Q818: How many different documents can be opened at once?::As many as memory can hold. Limited only by RAM.

Q820: System software that aims to maintain and make best use of computer resources ____::None. Managing and optimising resources is the job of the operating system, which is not listed. Check your key.

Q907: Programs that control the activities of various components ____::Operating system. Operating system.

Q345: OS better for implementing client-server network ____::Windows 2000. Windows 2000 had server editions and domain support. 95/98 were desktop OS.

Q566: Key combination to minimise all open windows ____::Windows key + D. Win+D = show desktop.

Q469: Which can be called modifiers?::Alt, Shift or Ctrl. Modifier keys change what another key does: Alt, Shift, Ctrl.

Q130: Not essential for mail merge in MS Word ____ (choose from: a) Main document; b) Data source; c) Merge fields; d) Word fields)::Word fields. Needed: main document, data source, merge fields. 'Word fields' are not required.

Q131: Small squares on selection rectangle used to change dimensions of a graphic ____::sizing handles. Sizing handles.

Q132: Minimum number of rows and columns in a Word table ____::1 and 1. A table can be 1 row x 1 column.

Q133: Word automatically moves text to next line at right edge ____::Word Wrap. Word wrap.

Q134: Thesaurus tool in MS Word is used for ____::Synonyms and Antonyms. Thesaurus = synonyms/antonyms. Spell check = spelling, Grammar = grammar.

Q135: To autofit the width of a column in MS Word ____::Double click right border. Double-click the RIGHT border of the column.

Q136: AutoCorrect was originally designed to replace ____ words as you type ____::Misspelled. Misspelled words.

Q273: Definition of FONT ____::Design of type. Font = design of type (typeface at a size/style).

Q418: Indentation in word processing is used to ____::readable. Indent moves paragraph text from the margin to improve readability/structure. Poorly worded; (a) is the only sensible option.

Q575: Tool to quickly apply the same formatting to multiple pieces of text ____::Format Painter. Format Painter (double-click to apply many times).

Q576: Whitespace used to place text in the left margin next to the main body ____::Margin notes. Margin notes. Doubtful wording; check your key.

Q579: Tool to mark a specific location within a document ____::Bookmark. Bookmark.

Q618 · Q665: Feature automating sending bulk mail / combining names and addresses with a standard document ____::mail merge. Mail merge = one letter + data list = many personalised letters.

Q627: An orphan line is created if ____::first line at bottom. ORPHAN = FIRST line of a paragraph left alone at the BOTTOM of a page. WIDOW = LAST line alone at the TOP of next page.

Q847: Character written slightly below another ____::Subscript. Subscript (H2O). Superscript = above (x2).

Q879: Text flow equally balanced between margins ____::Justified. Justified.

Q925: Correct 'centre' misspelt in whole document quickly ____::Find and replace. Ctrl+H Find and Replace.

Q583: Keyboard shortcut to insert AutoSum ____::Alt+=. Alt + = (equals).

Q591: PowerPoint view displaying only text (title and bullets) ____::Outline view. Outline view.

Q817: Top slide in hierarchy storing theme and layout information ____::Slide master. Slide Master.

Q941: Two kinds of sound effect files in PowerPoint ____::.wav and .mid. .wav and .mid (MIDI). gif/jpg are images.

Q840: A collection of worksheets is called ____::Workbook. Workbook = file with many worksheets.

Q267: Technology giving internet over telephone wires ____::DSL. DSL = Digital Subscriber Line.

Q288: Network Interface Card (NIC) is ____::board providing physical connection to a network. NIC = LAN card; gives your PC a network connection and MAC address.

Q305: Device allowing computers to communicate over telephone lines ____::Modem. Modem = MOdulator + DEModulator.

Q315: Computer providing database services to others is a ____::Database server. Database server.

Q350: Technology for telephone calls over computer networks ____::VoIP. VoIP = Voice over Internet Protocol (WhatsApp calls, Skype).

Q456: Full form of P2P ____::Peer to Peer. Peer to Peer.

Q459: A system or device connected to a network ____::Node. Node.

Q478: Used to communicate from one city to another ____::WAN. Between cities = WAN. MAN covers inside one city. LAN = building.

Q588: IP address that doesn't change every day ____::Static. Static IP.

Q592: Network that extends a private network across public networks ____::VPN. VPN.

Q594: Access point (AP) in a wireless LAN is ____::device for connection. AP connects wireless devices to the wired network. Doubtful wording but (a).

Q596: Internet works on ____::Packet switching. Packet switching. Telephone (old) = circuit switching.

Q597: Record of your thoughts or experiences filmed and published online ____::Video blog. Vlog = video blog.

Q599: Transmission medium carrying data exposed to electrical interference ____::UTP. Unshielded twisted pair has no shield, so it picks up noise.

Q602: Supports bi-directional flow in both directions simultaneously ____::Full Duplex. Full duplex = phone call. Half duplex = walkie-talkie. Simplex = TV.

Q611: Computer-generated scenes that make the user feel immersed ____::Virtual reality. VR immerses you; AR overlays on real world.

Q649: E-governance uses ____::Internet. E-governance delivers services over the Internet (ICT). Vague question.

Q652: HTTP is a ____::Stateless Protocol. HTTP is stateless: each request is independent (cookies add state).

Q661: Main international organisation that sets standards for the WWW ____::W3C. W3C. IETF = internet protocols. InterNIC = domain registration.

Q670: Huge numbers of devices communicating automatically without humans ____::Machine to Machine. M2M (basis of IoT).

Q682: Fiber optics has the advantage of ____::no interference. Light signals are immune to electromagnetic interference.

Q698 · Q833: Device that decides the path of data packets / redirects IP packets to destination ____::router. Router = chooses path between networks. Switch = connects devices inside a LAN.

Q708: Which does NOT use electrical signal for data transmission? (choose from: a) Optical fiber; b) Twisted pair; c) Coaxial; d) All use electrical signal)::Optical fiber. Fiber uses light.

Q775: Optical fiber uses ____::light signals. Light signals (pulses of light).

Q710: An IP address identifies a device. Statement ____ (choose from: a) name indicates seek; b) address indicates where; c) route indicates how; d) All)::All. Name = what we seek, address = where it is, route = how to get there (RFC 791). All true.

Q711: Unsolicited emails are known as ____::spam. Spam.

Q712: Network congestion occurs ____::traffic overloading. Too much traffic for the capacity.

Q725: The Internet is governed by ____::IETF. IETF (written 'IEFT' in your set) sets internet standards. Related: W3C = web standards. Verify key.

Q726: NOT a one-to-many form of communication ____ (choose from: a) Blogging; b) Personal Website; c) Email; d) Podcasting)::Email. Email is typically one-to-one (or few). The others broadcast.

Q740: 'Micro-blogging' means ____::limited individual posts. Short posts (Twitter/X).

Q744: What an email address contains?::User name followed by Domain. user@domain.

Q797: Modulation is the process of ____::encoding digital signal to analog. Modulation puts digital data onto an analog carrier wave (modem).

Q798: Bluetooth uses ____::frequency hopping spread spectrum. Bluetooth = FHSS in the 2.4 GHz band.

Q800: Encoding using clear text to represent formatting ____::HTML. HTML tags are plain text.

Q812: Full form of WPA ____::Wi-Fi Protected Access. Wi-Fi Protected Access.

Q904: Cloud deployment used to serve multiple users ____::Public. Public cloud = shared by many customers.

Q173: Compiler is an example of ____::System software. Translators (compiler, assembler, interpreter) are system software.

Q236: Language used for artificial intelligence ____::PROLOG. PROLOG (and LISP) for AI. FORTRAN = science, COBOL = business.

Q339: What is software?::A set of instructions. Software = instructions that tell hardware what to do. (b) is also close; (a) is the commoner key.

Q374 · Q449: Valid statement about a computer program ____::HLL must be converted to machine language. High-level language needs a compiler/interpreter. HLL is slower than machine code and easier to debug.

Q401: COBOL is an acronym for ____::Common Business Oriented Language. Common Business Oriented Language.

Q403: Not a valid variable name declaration ____ (choose from: a) int _a3; b) int a_3; c) int 3_a; d) int _3aNames cannot start with a digit. Underscore start is fine.)::int 3_a. 

Q404: Format identifier %i is also used for ___ data type ____::Int. %i = int (like %d). %c char, %f float.

Q108: Major goal of requirement determination phase of system development ____::WHAT information is needed. Requirements = WHAT. Design = HOW.

Q499: First phase in SDLC ____::Requirement gathering. SDLC: Planning/Requirements, Design, Coding, Testing, Deployment, Maintenance. Some books begin with feasibility; verify your key.

Q500: Tools supporting different stages of SDLC ____::CASE tools. CASE = Computer Aided Software Engineering.

Q502: Phase typically consuming maximum effort among development phases ____::Testing. Testing takes the most effort among development phases (maintenance takes the most over the whole life). Check your key.

Q505: Polymorphism refers to ____::more than one form. Poly = many, morph = form.

Q506: Main objective of inheritance in OOP ____::Reusability. Reusability.

Q354: Process of extracting previously useful information from large data ____::Data Mining. Data mining.

Q366: Intersection of columns and rows ____::Cell. Cell (in a table/spreadsheet).

Q730: Transfer of data from one application to another ____::Dynamic Data Exchange. DDE.

Q731: A binary file in contrast to a text file ____::content not read by humans. Binary files (exe, images) look like gibberish in Notepad.

Q837: One keystroke generates 1 ___ of data ____::Byte. 1 character = 1 byte (ASCII).

Q473: A bit stands for ____::Binary Digit. BInary digiT.

Q614: Unit of data eight binary digits long ____::Bytes. 8 bits = 1 byte.

Q694: Bytes equivalent to 12 GB ____ (choose from: a) 1024; b) 12 x 1024; c) 1024 x 1024 x 1024; d) 1024)::12 x 1024. Correct maths = 12 x 1024 x 1024 x 1024 = 12,884,901,888 bytes, which is not listed. (b) is the closest/usual key.

Q804: 8-bit binary can represent how many symbols ____::256. 2^8 = 256.

Q113: Intellectual Property Rights covers ____::All. All of these.

Q181: IT Act 2000 contains ____::13 chapters. Original IT Act 2000: 13 chapters, 90 sections, 2 schedules.

Q396: Measurement of fingerprints etc. used for security access ____::Biometrics. Biometrics.

Q458: Exploiting and experimenting a telephone system ____::Phreaking. Phreaking = phone hacking. Phishing = fake emails. Pharming = fake websites via DNS.

Q695: Stealing sensitive information by appearing trustworthy ____::Phishing. Phishing.

Q719: Virus designed to hide from antivirus software ____::Stealth virus. Stealth virus hides. Polymorphic virus CHANGES its code each time.

