
---

## tags: [computer, ldc, software-engineering, sdlc] aliases: [SDLC, Software Development Life Cycle, Waterfall Model]

# SDLC (Software Development Life Cycle)

> **SDLC** = **Software Development Life Cycle**: the step-by-step process used to plan, build, test and maintain software.

## 1. Phases of SDLC

|#|Phase|What happens|Output|
|---|---|---|---|
|1|Planning / Feasibility study|Decide if the project is possible (cost, time, technical)|Feasibility report|
|2|Requirement analysis|Collect what the user needs|SRS (Software Requirement Specification)|
|3|Design|Plan architecture, database, screens|Design document (HLD, LLD)|
|4|Coding / Implementation|Programmers write the code|Source code|
|5|Testing|Find and fix bugs|Test reports|
|6|Deployment|Software is released to users|Live system|
|7|Maintenance|Fix bugs, update, improve after release|Updated software|

**Memory trick:** **P**lan → **A**nalyse → **D**esign → **C**ode → **T**est → **D**eploy → **M**aintain

## 2. SDLC models

|Model|Idea|Best for|Weakness|
|---|---|---|---|
|**Waterfall**|Phases done one after another, no going back|Small projects with fixed requirements|Hard to change; testing comes late|
|**V-Model**|Waterfall with a test phase matched to each development phase|Projects needing strong testing|Rigid|
|**Iterative**|Build in repeated cycles, improving each time|Projects where requirements grow|Needs good planning|
|**Incremental**|Build and deliver in small working parts|Early delivery of core features|Needs good design up front|
|**Spiral**|Iterative plus **risk analysis** in each loop|Large, risky projects|Costly, complex|
|**Prototype**|Build a sample first, user gives feedback|Unclear requirements|May lead to repeated rework|
|**Agile**|Short cycles (sprints), constant customer feedback|Changing requirements|Needs close teamwork|
|**RAD**|Rapid Application Development, fast build with prototypes|Short deadlines|Needs skilled team|
|**Big Bang**|Start coding with little planning|Very small projects|High risk|

## 3. Waterfall model

|Point|Detail|
|---|---|
|Also called|Classical / linear sequential model|
|Flow|Requirements → Design → Coding → Testing → Deployment → Maintenance|
|Feature|Each phase must finish before the next begins|
|Advantage|Simple, easy to manage, clear documentation|
|Disadvantage|No working software until late; changes are costly|

## 4. Agile

|Term|Meaning|
|---|---|
|Sprint|Short work cycle (usually 1–4 weeks)|
|Scrum|Popular agile framework|
|Product owner|Represents the customer|
|Scrum master|Helps the team follow scrum|
|Backlog|List of work to be done|
|Daily stand-up|Short daily team meeting|
|Other agile methods|Kanban, XP (Extreme Programming)|

## 5. Types of testing

|Type|Meaning|
|---|---|
|Unit testing|Tests a single module|
|Integration testing|Tests modules working together|
|System testing|Tests the whole system|
|Acceptance testing|User checks it meets requirements|
|Alpha testing|Done by the developer team in-house|
|Beta testing|Done by real users outside the company|
|Black-box testing|Tests without seeing the code|
|White-box testing|Tests with knowledge of the code|
|Regression testing|Re-tests after changes to check nothing broke|

## 6. Types of maintenance

|Type|Meaning|
|---|---|
|Corrective|Fix bugs|
|Adaptive|Adjust to a new environment (new OS, law)|
|Perfective|Add features or improve performance|
|Preventive|Prevent future problems|

## 7. Related terms

|Term|Meaning|
|---|---|
|SRS|Software Requirement Specification|
|Bug|Error in a program|
|Debugging|Finding and fixing bugs|
|Flowchart|Diagram showing steps of a process|
|Algorithm|Step-by-step method to solve a problem|
|Pseudocode|Algorithm written in plain, code-like language|
|DFD|Data Flow Diagram|
|ER Diagram|Entity Relationship Diagram, used for database design|
|UML|Unified Modeling Language|
|CASE tools|Computer Aided Software Engineering tools|
|Software crisis|Late, costly, buggy software, which led to software engineering|
|SDLC vs STLC|SDLC = whole development process; STLC = Software Testing Life Cycle|

## 8. Practice questions (written by Claude, with answers)

|#|Question|Answer|
|---|---|---|
|1|SDLC stands for|Software Development Life Cycle|
|2|First phase of SDLC|Planning / Feasibility study|
|3|Phase where user needs are collected|Requirement analysis|
|4|Output of requirement analysis|SRS|
|5|SRS stands for|Software Requirement Specification|
|6|Phase where code is written|Coding / Implementation|
|7|Phase where bugs are found|Testing|
|8|Phase after deployment|Maintenance|
|9|Simplest SDLC model|Waterfall|
|10|Model with risk analysis|Spiral|
|11|Model that builds a sample first|Prototype|
|12|Model using sprints|Agile|
|13|Waterfall model is also called|Linear sequential model|
|14|Testing by developers inside the company|Alpha testing|
|15|Testing by users outside the company|Beta testing|
|16|Testing without seeing the code|Black-box testing|
|17|Testing a single module|Unit testing|
|18|Fixing bugs after release is|Corrective maintenance|
|19|Process of finding and removing bugs|Debugging|
|20|DFD stands for|Data Flow Diagram|
|21|ER diagram is used for|Database design|
|22|UML stands for|Unified Modeling Language|
|23|RAD stands for|Rapid Application Development|
|24|CASE stands for|Computer Aided Software Engineering|
|25|Cost of fixing a bug is lowest in|Early phases (requirements / design)|

## 9. Exam tip

- Order to remember: **Plan → Requirements → Design → Code → Test → Deploy → Maintain**.
- **Spiral** = risk analysis. **Prototype** = user feedback on a sample. **Agile** = sprints.
- **Alpha** = in-house. **Beta** = outside users.