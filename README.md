# Panda+ Operating System Project

This repository contains the implementation of **Phase 1** and **Phase 2** of the **Panda+ Operating System**, developed as part of the Operating Systems course.  
The goal of the project is to progressively build the internal components of the Panda+ OS — from basic data structures to a functioning kernel capable of process scheduling, exception handling, and system management.

---

## 🧩 Project Overview

The project is divided into two main phases:

### 🔹 Phase 1 – Level 2
Implementation of the **core OS data structures** used for process and semaphore management.

Main features:
- PCB (Process Control Block) allocation and deallocation  
- PCB queue and tree management  
- Active Semaphore Hash (ASH)  
- Namespace management  

---

### 🔹 Phase 2 – Level 3
Implementation of the **kernel level** of Panda+, including process scheduling, system initialization, and exception handling.

Main features:
- System initialization and first process creation  
- Scheduling mechanism (`scheduler.c`)  
- Exception management (`exceptions.c`) for:
  - Syscalls  
  - Interrupts  
  - Traps 

