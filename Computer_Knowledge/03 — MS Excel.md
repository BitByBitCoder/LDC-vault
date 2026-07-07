# 03 — MS Excel
[[💻 Computer Knowledge — INDEX|← Back to Index]]

> 72 questions — 13.7%. Formulas, referencing, and specific features tested heavily.

---

## Questions From Your Papers

| Question | Answer |
|----------|--------|
| Every formula must begin with | **= (equals sign)** |
| Close worksheet keep Excel running | **File → Close** |
| Relative referencing example | A1 → A2 when copied down |
| Background color of cell | **Fill Color Tool** |
| Print selected portion only | **Select area → Set Print Area** |
| Display long text in multiple lines | **Wrap Text** |
| Merge and Center option | **Combines cells + centers content** |
| Count numeric entries in range | **COUNT()** |
| Two-variable data table | **Analyze effect of two inputs on formula** |
| Chart source data modified | **Chart updates automatically** |
| Slide layout determines | **Arrangement of placeholders** |

---

## Excel Basics

| Question | Answer |
|----------|--------|
| Extension of Excel file | **.xlsx** |
| Default sheet name | Sheet1, Sheet2, Sheet3 |
| Intersection of row and column | **Cell** |
| Cell address example | **A1** (column A, row 1) |
| Active cell | Currently selected cell |
| Workbook | File containing worksheets |
| Worksheet | Single spreadsheet tab |
| Name Box | Shows address of active cell |
| Formula Bar | Shows content of active cell |

---

## Every Formula Starts With =

| Formula | What it does | Example |
|---------|-------------|---------|
| **=SUM()** | Adds numbers | =SUM(A1:A10) |
| **=AVERAGE()** | Calculates average | =AVERAGE(B1:B5) |
| **=COUNT()** | **Counts NUMERIC entries only** | =COUNT(A1:A10) |
| **=COUNTA()** | Counts ALL non-empty cells | =COUNTA(A1:A10) |
| **=MAX()** | Finds largest value | =MAX(A1:A10) |
| **=MIN()** | Finds smallest value | =MIN(A1:A10) |
| **=IF()** | Logical test | =IF(A1>10,"Yes","No") |
| **=VLOOKUP()** | Vertical lookup | =VLOOKUP(value,range,col,0) |
| **=HLOOKUP()** | Horizontal lookup | — |
| **=CONCATENATE()** | Joins text | =CONCATENATE(A1," ",B1) |
| **=LEN()** | Length of text | =LEN(A1) |
| **=LEFT()** | Extract left characters | =LEFT(A1,3) |
| **=RIGHT()** | Extract right characters | =RIGHT(A1,3) |

---

## Cell Referencing — Most Tested

| Type | Example | Behavior when copied |
|------|---------|---------------------|
| **Relative** | A1 | **Changes automatically** — A1 → A2 → A3 |
| **Absolute** | **$A$1** | **Never changes** — always A1 |
| **Mixed (row fixed)** | A$1 | Row stays, column changes |
| **Mixed (col fixed)** | $A1 | Column stays, row changes |

```
To lock: add $ sign
$A$1 = both locked (absolute)
A$1 = row 1 locked (mixed)
$A1 = column A locked (mixed)
A1 = nothing locked (relative)
```

---

## Formatting Cells

| Feature | What it does |
|---------|-------------|
| **Fill Color** | **Background color of cell** |
| **Font Color** | Text color |
| **Borders** | Lines around cells |
| **Wrap Text** | **Shows long text in multiple lines within cell** |
| **Merge & Center** | **Combines cells into one + centers content** |
| **Number Format** | Currency, %, date, text etc. |
| **Conditional Formatting** | Changes format based on value |
| **Freeze Panes** | Keeps rows/columns visible while scrolling |

---

## Data Operations

| Feature | What it does |
|---------|-------------|
| **Sort** | Arrange data A→Z or Z→A or numerically |
| **Filter** | Show only rows meeting criteria |
| **Remove Duplicates** | Delete duplicate rows |
| **Text to Columns** | Split text in one column into multiple |
| **Consolidate** | Combine data from multiple ranges |
| **What-If Analysis** | Test different scenarios |
| **Data Validation** | Restrict what can be entered in a cell |

---

## Charts

| Question | Answer |
|----------|--------|
| Chart source data modified | **Chart updates automatically** |
| Types of charts | Bar, Column, Line, Pie, Scatter, Area |
| Pie chart best for | Showing parts of a whole (%) |
| Line chart best for | Trends over time |

---

## Printing

| Feature | How |
|---------|-----|
| Print selected area | Select → Page Layout → **Set Print Area** |
| Print entire workbook | File → Print → Print Entire Workbook |
| Print preview | File → Print (shows preview) |
| Page orientation | Landscape / Portrait — Page Layout tab |

---

## Shortcuts — Excel

| Shortcut | Action |
|---------|--------|
| Ctrl + N | New workbook |
| Ctrl + S | Save |
| **Ctrl + Home** | Go to cell A1 |
| Ctrl + End | Go to last used cell |
| Ctrl + Arrow | Jump to edge of data |
| F2 | Edit current cell |
| **Delete** | Clear cell contents |
| Ctrl + Z | Undo |
| Ctrl + C/V | Copy/Paste |
| **F12** | Save As |

---

## Exam Traps ⚠️
> Every formula = **= sign** — NOT + or # or @
> Relative reference = **changes** when copied — Absolute = stays fixed
> Wrap text = **multiple lines in same cell** — NOT merge cells
> Merge & Center = **combines cells** — NOT wrap text
> COUNT() = **numeric only** — COUNTA() = all non-empty
> Chart updates **automatically** when source data changes
> Close worksheet = **File → Close** (Excel stays open)
> Fill Color = **background** of cell — Font Color = text color
> Set Print Area = **print selected portion** — NOT hide rows
> $A$1 = **absolute** — A1 = **relative** — $A1 = **mixed**
