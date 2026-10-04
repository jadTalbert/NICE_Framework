
### Department of Computer Programming & Development

---

## Welcome to CSC-115

This repository serves as the central hub for our course code examples, lab exercises, technical documentation, and capstone specifications.

Unlike traditional coding classes where assignments might feel like isolated homework exercises, this course is structured around **real-world programming readiness**. To bridge the gap between classroom syntax and industry employment, we are adopting an architectural framework modeled after the nationally recognized **NICE Framework**.

---

## What is the NICE Framework?

The **National Initiative for Cybersecurity Education (NICE) Framework** (NIST Special Publication 800-181) is a standardized blueprint developed by the U.S. National Institute of Standards and Technology. In both cybersecurity and defense environments, employers do not hire generic "degrees"—they hire individuals who can perform specific job functions. 

The NICE framework organizes professional roles using a structured hierarchy:

* **Work Categories:** Groupings of common technical functions.
* **Work Roles:** Specific operational job titles found in the market.
* **Competency Areas:** Blended clusters of applied technical capabilities.
* **Tasks (T):** The specific, actionable duties an engineer performs on the job.
* **Knowledge (K):** Foundational concepts, syntax rules, memory models, and CS principles.
* **Skills (S):** The practical ability to execute commands, debug, profile, and manipulate tools.

---

## How We Use This Framework in CSC-115

In this course, we adapt this exact model for **Software Development and Systems Automation**. Every topic, lab, and project in this repository is cross-referenced with standardized **TKS (Task, Knowledge, Skill)** statements.

When you complete an assignment, you aren't just getting a grade—you are building a **verifiable technical inventory** of what you can actually do on day one in an engineering environment.


```

```
   [ Work Role ]
         │
┌────────┴────────┐
▼                 ▼

```

[ Knowledge ]     [ Skills ]
│                 │
└────────┬────────┘
▼
[ Tasks Executed ]  ──► (Demonstrated via Labs & Projects)

```

### Target Work Roles for CSC-115
The competencies taught in this course map directly into entry-level industry positions:
1. **DEV-001: Junior Python Developer / Associate Software Engineer** (Core logic, modular functions, structured programs)
2. **AUT-001: Operations & Automation Technician (Junior DevOps / SysAdmin)** (System utility scripts, batch file automation)
3. **AUT-002: Entry-Level Data Associate / Telemetry Wrangler** (Data parsing, cleaning, CSV/JSON serialization)
4. **QA-001: Associate Automation Test Script Writer** (Input validation, exception handling, functional assertions)

---

## Course Competency Areas & Statement Catalog

Your assignments and code reviews will reference these specific competencies:

### 1. Algorithmic Logic & Control Flow (CA-PY01)
* **K0210:** Knowledge of primitive data types, dynamic typing, and explicit type casting in Python.
* **K0211:** Knowledge of operator precedence, Boolean logic, and conditional branching (`if/elif/else`).
* **S0314:** Skill in using defensive programming patterns (validating inputs, checking boundaries).
* **S0319:** Skill in decomposing complex Boolean expressions using truth tables and short-circuit evaluation.
* **T0110:** Implement basic algorithmic logic using sequence, selection, and iteration (`for`/`while`) structures.

### 2. Modular Architecture & Program Design (CA-PY02)
* **K0213:** Knowledge of scope resolution rules (LEGB: Local, Enclosing, Global, Built-in) for variables.
* **S0315:** Skill in writing structured, readable code compliant with PEP 8 standards (naming conventions, docstrings).
* **S0325:** Skill in writing structured docstrings with type annotations to document parameter contracts and return types.
* **T0111:** Write modular, reusable functions with explicit parameters, default arguments, and return values.

### 3. Collections & Data Transformation (CA-PY03)
* **K0212:** Knowledge of memory mutability vs. immutability (lists vs. tuples/strings).
* **S0312:** Skill in structuring and iterating through compound data structures (lists of dictionaries, nested arrays).
* **S0316:** Skill in writing list comprehensions to filter, transform, and map datasets without explicit accumulator loops.
* **S0317:** Skill in performing multi-field sorting using custom `key` functions and lambda expressions.
* **T0114:** Select, instantiate, and manipulate appropriate collection types (lists, dicts, sets, tuples).

### 4. Defensive File I/O & System Automation (CA-PY04)
* **K0214:** Knowledge of standard library modules (`pathlib`, `csv`, `json`, `sys`, `random`).
* **K0215:** Knowledge of standard exception classes (`ValueError`, `FileNotFoundError`, `KeyError`, `IndexError`).
* **S0318:** Skill in safely managing file streams using context managers (`with` statements).
* **S0320:** Skill in reading, writing, and transforming data using `json` and `csv` modules.
* **S0321:** Skill in implementing defensive input validation loops to sanitize data before processing.
* **T0112:** Ingest, parse, and serialize local flat-file datasets using built-in file operations.
* **T0113:** Implement robust error-handling routines utilizing `try/except` blocks to prevent unhandled runtime crashes.

---

## Repository Directory Structure

```text
├── labs/
│   ├── lab-01-billing-calculator/       # CA-PY01 (T0110, K0210, S0314)
│   ├── lab-02-inventory-manager/        # CA-PY03 (T0114, S0312, S0317)
│   ├── lab-03-log-parser/               # CA-PY04 (T0112, T0113, S0318)
│   └── ...
├── projects/
│   └── capstone-telemetry-engine/       # Comprehensive Assessment (All TKS)
├── templates/
│   └── submission-template.py           # Boilerplate with PEP 8 and docstrings
├── docs/
│   └── tks-reference-guide.md           # Master list of all Knowledge & Skill codes
└── README.md

```

---

## Deliverables & Git Workflow

All work in this class must be submitted via Git pull requests following enterprise standards:

1. **Clone the Repo:**
```bash
git clone <your-assigned-fork-url>
cd csc-115-coursework

```


2. **Branching:** Never commit directly to `main`. Create a feature branch named after the lab or task:
```bash
git checkout -b feature/lab-03-log-parser

```


3. **Commit Messages:** Write descriptive, imperative commit messages:
```bash
git commit -m "Implement try/except blocks to catch corrupt CSV records (T0113)"

```


4. **Code Quality:** All submissions must execute cleanly without unhandled exceptions and conform to PEP 8 standards (`flake8` / `black` friendly).

---

## Why This Matters for Your Career

When you interview for internships, apprenticeships, or junior software engineering positions, employers rarely ask: *"What grade did you get on Lab 3?"*

They ask:

* *"Can you read an imperfect CSV, parse it into structured JSON, and handle missing fields without crashing?"* (**T0112, T0113, S0320**)
* *"Can you explain the difference between modifying a list in-place versus returning a new copy?"* (**K0212**)
* *"Can you write clean functions with parameters rather than relying on global state?"* (**T0111, K0213**)

By aligning our work with this framework, every completed lab in your GitHub history serves as verifiable proof of your technical capabilities.

---

*Maintained by the Computer Programming and Development Faculty. Open an Issue for questions or technical discrepancies.*

```

```