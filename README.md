# Oracle Database Architecture

This repository explains the **Oracle Database Architecture** with a diagram and clear explanation.

## Architecture Diagram
<img src="https://github.com/user-attachments/assets/74eb2d0e-aabf-450c-ac71-044affec5908" alt="Oracle DB Architecture Diagram" width="800"/>

## Main Components

### 1. Oracle Instance
An Oracle Instance consists of **Memory Structures** and **Background Processes**.

#### Memory Structures
- **SGA (System Global Area)**
  - Database Buffer Cache
  - Shared Pool
  - Redo Log Buffer
- **PGA (Program Global Area)**

#### Background Processes
- DBWn (Database Writer)
- LGWR (Log Writer)
- CKPT (Checkpoint)
- SMON (System Monitor)
- PMON (Process Monitor)

---

### 2. Database (Physical Structures)
- Datafiles
- Control Files
- Redo Log Files
- Archived Redo Logs

---

## Flow Summary
User → Oracle Instance → Database Files

---

## Tools & Version
- Oracle Database 19c
- Linux

---

## Purpose
This assignment is created as part of my **Oracle DBA learning journey**.

		















