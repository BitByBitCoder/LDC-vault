# 11. Database Concepts

Back to [[00_Index]]

### Fundamentals
* **Data**: Unorganized, raw facts.
* **Information**: Processed, context-aware, structured data.
* **Database Models**:
  1. *Network Database*: Represented via interconnected records and links.
  2. *Hierarchical Database*: Tree-like structure connected via node links.
  3. *Relational Database*: Organized in structured tables containing rows and columns.

### DBMS Architecture
1. **Internal Level (Physical Level)**: Lowest level; defines how data is physically stored on storage media.
2. **Conceptual Level (Logical Level)**: Describes overall database relationships and data types stored without physical details.
3. **External Level (View Level)**: Highest level; customized views for individual users.

### DBMS Advantages & Disadvantages
* **Advantages**: Reduction of data redundancy, improved user interaction, enhanced security, enforced data integrity, easy application development, automated backup and recovery.
* **Disadvantages**: High hardware/software costs, complex software, staff training expense, technical dependency, single-point system failures.

### Relational Database Terminology
* **Relation**: A structured table.
* **Tuple**: A single row within a table.
* **Attribute**: A column header within a table.
* **Cardinality**: Total number of **tuples (rows)** in a relation.
* **Degree**: Total number of **attributes (columns)** in a relation.
* **Domain**: Set of all permissible values for a given column.

### Database Keys
* **Primary Key**: Uniquely identifies rows in a table; cannot be null or duplicated.
* **Candidate Key**: Minimal set of attributes capable of uniquely identifying tuples; one is selected as Primary Key.
* **Alternate Key**: Candidate keys that were not chosen as the primary key.
* **Foreign Key**: An attribute matching the primary key of another relation; establishes connections between tables.

### Database Languages
* **DDL (Data Definition Language)**: Defines structural database schemas (e.g., table creation).
* **DML (Data Manipulation Language)**: Handles retrieval, insertion, modification, and deletion of data.
* **DCL (Data Control Language)**: Manages permissions, security roles, and user access levels.

### Entity-Relationship (E-R) Diagram Components
* **Entity**: Real-world object (Represented by **Rectangles**).
* **Attribute**: Properties describing an entity (Represented by **Ellipses**).
* **Relationship**: Connection between entities (Represented by **Diamonds**).
* **Entity Sets**: Strong (possesses primary key) vs. Weak (lacks sufficient attributes to form a primary key).
