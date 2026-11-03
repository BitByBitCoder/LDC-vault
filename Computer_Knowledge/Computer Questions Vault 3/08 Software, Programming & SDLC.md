[[00 Computer Vault Index]]

# Software, Programming & SDLC

#computer #sw

**Part 1: learn the topic** (tables). **Part 2: past questions** (17: 🟢 9 · 🟡 7 · 🔴 1). Read Part 1 first, then test yourself in Part 2.

# Part 1: Learn the topic

## 1. Software types

| Type | Examples |
|---|---|
| System software | OS, compiler, assembler, interpreter, drivers |
| Application software | Word, Excel, browsers |
| Utility software | antivirus, backup, disk tools |

Software = set of programs / instructions. Hardware = physical parts. OS = program controlling and coordinating components.

## 2. Language levels

| Level | Language | Note |
|---|---|---|
| 1GL | machine | 0 and 1, fastest |
| 2GL | assembly | needs assembler |
| 3GL | high-level (C, Java) | **must be translated** to machine language |
| 4GL | SQL | |
| 5GL | AI (PROLOG) | |

| Translator | Works |
|---|---|
| Assembler | assembly to machine |
| Compiler | whole program at once |
| Interpreter | line by line |

## 3. Programming languages

| Language | Use |
|---|---|
| FORTRAN | science, maths |
| COBOL | business. **Common Business Oriented Language** |
| BASIC | beginners |
| C | system programming (Dennis Ritchie) |
| C++ | OOP (Bjarne Stroustrup) |
| Java | portable apps (James Gosling) |
| Python | general (Guido van Rossum) |
| LISP, PROLOG | **artificial intelligence** |
| SQL | databases |
| HTML | markup for web pages |

## 4. C basics

| Rule | Detail |
|---|---|
| Variable start | letter or underscore. **Never a digit** |
| Allowed | letters, digits, underscore |
| Not allowed | spaces, keywords |

| Specifier | Type |
|---|---|
| %d and **%i** | int |
| %f | float |
| %lf | double |
| %c | char |
| %s | string |

Valid: `_a3`, `a_3`, `_3a`. Invalid: `3_a`.

## 5. OOP concepts

| Concept | Meaning |
|---|---|
| Class | blueprint |
| Object | instance of a class |
| Encapsulation | bundling data and methods, **data hiding** |
| Abstraction | show only essentials |
| **Inheritance** | child reuses parent. Goal = **reusability** |
| **Polymorphism** | **many forms** |

## 6. SDLC

| Phase | Question answered |
|---|---|
| Requirement gathering / analysis | **WHAT** information is needed |
| Design | **HOW** it will be provided |
| Coding | write code |
| Testing | find errors (large effort) |
| Deployment | go live |
| Maintenance | fix and update |

CASE tools = Computer Aided Software Engineering, support SDLC stages.

## 7. Database terms

| Term | Meaning |
|---|---|
| Field / column | one attribute |
| Record / row | one entry |
| Cell | **intersection of a row and column** |
| Table | rows + columns |
| DBMS | software managing databases |
| Data mining | extracting useful information from large data |
| Metadata | data about data |
| Database server | computer providing database services |

| Misc | Fact |
|---|---|
| DDE | Dynamic Data Exchange, transfer data between applications |
| Binary file | content not readable by humans (images, exe) |
| Text file | readable in Notepad |
| Data size units | 1 keystroke = **1 byte** |

# Part 2: Past questions with answers

Answer in your head first, then open the callout. Level is shown before the answer. 🔁 = repeated in your paper. ⚠️ = doubtful key ([[12 Doubtful Keys]]).

### Q173 · 🟢 Easy
**Q.** Compiler is an example of ____

> [!success]- Answer
> **System software**
> Translators (compiler, assembler, interpreter) are system software.
> Don't confuse with: Utility software; Application software; None

### Q236 · 🟢 Easy
**Q.** Language used for artificial intelligence ____

> [!success]- Answer
> **PROLOG**
> PROLOG (and LISP) for AI. FORTRAN = science, COBOL = business.
> Don't confuse with: FORTRAN; COBOL; INDEXING

### Q354 · 🟢 Easy
**Q.** Process of extracting previously useful information from large data ____

> [!success]- Answer
> **Data Mining**
> Data mining.
> Don't confuse with: Data Management; Database; Meta Data

### Q366 · 🟢 Easy
**Q.** Intersection of columns and rows ____

> [!success]- Answer
> **Cell**
> Cell (in a table/spreadsheet).
> Don't confuse with: Data; Table; Schema

### Q401 · 🟢 Easy
**Q.** COBOL is an acronym for ____

> [!success]- Answer
> **Common Business Oriented Language**
> Common Business Oriented Language.
> Don't confuse with: Computer Business Oriented; Common Business Operated; Common Business Organized

### Q403 · 🟢 Easy
**Q.** Not a valid variable name declaration ____  
(choose from: a) int _a3; b) int a_3; c) int 3_a; d) int _3aNames cannot start with a digit. Underscore start is fine.)

> [!success]- Answer
> **int 3_a**
> 

### Q500 · 🟢 Easy
**Q.** Tools supporting different stages of SDLC ____

> [!success]- Answer
> **CASE tools**
> CASE = Computer Aided Software Engineering.
> Don't confuse with: CAME; CAQE; CARE

### Q505 · 🟢 Easy
**Q.** Polymorphism refers to ____

> [!success]- Answer
> **more than one form**
> Poly = many, morph = form.
> Don't confuse with: inheritance; data hiding; All

### Q506 · 🟢 Easy
**Q.** Main objective of inheritance in OOP ____

> [!success]- Answer
> **Reusability**
> Reusability.
> Don't confuse with: Recoverability; Data abstraction; Security

### Q108 · 🟡 Medium
**Q.** Major goal of requirement determination phase of system development ____

> [!success]- Answer
> **WHAT information is needed**
> Requirements = WHAT. Design = HOW.
> Don't confuse with: whether information is needed; HOW it can be provided; WHEN to give it

### Q339 · 🟡 Medium
**Q.** What is software?

> [!success]- Answer
> **A set of instructions** ⚠️
> Software = instructions that tell hardware what to do. (b) is also close; (a) is the commoner key.
> Don't confuse with: Set of programs; Set of information; None

### Q374 · Q449 🔁 · 🟡 Medium
**Q.** Valid statement about a computer program ____

> [!success]- Answer
> **HLL must be converted to machine language**
> High-level language needs a compiler/interpreter. HLL is slower than machine code and easier to debug.
> Don't confuse with: HLL programs are faster; Errors harder to find in HLL; All

### Q404 · 🟡 Medium
**Q.** Format identifier %i is also used for ___ data type ____

> [!success]- Answer
> **Int**
> %i = int (like %d). %c char, %f float.
> Don't confuse with: Char; Float; Double

### Q499 · 🟡 Medium
**Q.** First phase in SDLC ____

> [!success]- Answer
> **Requirement gathering** ⚠️
> SDLC: Planning/Requirements, Design, Coding, Testing, Deployment, Maintenance. Some books begin with feasibility; verify your key.
> Don't confuse with: Feasibility analysis; Design; Coding

### Q730 · 🟡 Medium
**Q.** Transfer of data from one application to another ____

> [!success]- Answer
> **Dynamic Data Exchange**
> DDE.
> Don't confuse with: Dogmatic; Dynamic Disk; Dodgy

### Q731 · 🟡 Medium
**Q.** A binary file in contrast to a text file ____

> [!success]- Answer
> **content not read by humans**
> Binary files (exe, images) look like gibberish in Notepad.
> Don't confuse with: Any file stored; only 0s and 1s; processed using Notepad

### Q502 · 🔴 Hard
**Q.** Phase typically consuming maximum effort among development phases ____

> [!success]- Answer
> **Testing** ⚠️
> Testing takes the most effort among development phases (maintenance takes the most over the whole life). Check your key.
> Don't confuse with: Requirements; Design; Coding

> [!warning] Exam Trap ⚠️
> - Requirement = **what**. Design = **how**.
> - High-level programs are *slower* than machine code and easier to debug.
> - Variable names can start with underscore, **not** digit.
> - Compiler = system software.

## Self-check
- [ ] Round 1: __ / 17
- [ ] Round 2 (next day): __ / 17
- [ ] Round 3 (3 days later): __ / 17
- Close the topic at **85%**. Log it in [[15 Progress Tracker]].
