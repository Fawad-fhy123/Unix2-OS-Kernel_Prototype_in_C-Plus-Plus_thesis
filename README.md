# Unix2-OS-Kernel_Prototype_in_c++ Thesis
Undergraduate Bachelor's Thesis: Design and implementation of a 32-bit monolithic Unix-like operating system kernel prototype from scratch using x86 Assembly and C++.

# UNIX 2 COMPUTER OPERATING SYSTEM: Kernel Prototype in C++

# 📄 Overview
This repository hosts the comprehensive documentation, source code highlights and the final thesis publication for **UNIX 2 OS Kernel Prototype in C++**, a lightweight, secure, 32-bit monolithic operating system kernel prototype

* **Full Thesis Document:** Available in this repository as `UNIX_2_OS_Kernel_Thesis.pdf`.
* **Institution:** Indus University, Faculty of Computing and Information Technology (FCIT), Pakistan.

---

## 🏛️ Statement of Individual Contribution & Ownership

### **Nature of the Project**
Administratively, this final year capstone was registered and submitted as a group project to comply with institutional university regulations. However, the entire engineering lifecycle including all core architectural design, low-level codebase implementation, research was executed independently as a 100% individual technical contribution by Fawad Hameed Yousufi.

### **Core Competency Breakdown**

* **Technical Execution & Systems Programming:** 
  * **Engineered the monolithic kernel prototype completely from scratch** using a low-level hybrid architecture of x86 Assembly and Freestanding Object-Oriented C++ without relying on standard C/C++ runtime libraries.
  * Developed the system initialization pipeline ensuring strict **Multiboot compliance with the GRUB bootloader** to transition the CPU from real-mode into a stable 32-bit protected mode execution environment.
  * Configured independent low-level hardware abstraction subsystems, writing custom **Interrupt Service Routines (ISRs)**, mapping the **Interrupt Descriptor Table (IDT)**, remapping the Master/Slave Programmable Interrupt Controllers (PIC), and designing direct memory-mapped VGA video display text buffers.
  * Implemented a preemptive task manager driven by a **Round-Robin (RR) scheduling algorithm** over discrete time quantums via programmable hardware timer interrupt context switching.
  * Constructed an independent Graphical User Interface (GUI) framework capable of rendering composite pixel arrays directly to video memory spaces.

* **Methodology & Research Design:**
  * **Formulated the system methodology** and architectural design criteria, contrasting system metrics against classic Unix blueprints, open-source Linux distributions and microkernel layouts (Minix).
  * Authored the comprehensive literature review and engineered the **Comparative Anatomy** validating the custom kernel's physical memory isolation boundaries.
  * Modeled all software execution states and data pipelines through detailed system Activity Diagrams, Bootstrap Sequence Diagrams and Entity-Relationship topologies.

* **Project Management & Empirical Validation:**
  * Managed the end-to-end development cycle from initial definition to freestanding cross-compilation utilizing a custom GNU GCC toolchain.
  * **Conducted rigorous validation protocols** using virtual machine hypervisors and hardware emulators to verify kernel-space memory stability.
  * Deployed and benchmarked the final compiled binary directly onto live bare-metal physical x86 computer configurations using bootable local flash media, ensuring absolute platform independence.

---

## 🛠️ System Specifications & Prerequisites
* **Target Architecture:** Standard consumer or embedded x86 Microprocessor (Minimum Intel 80386 / i386)
* **Minimum Memory Bound:** 2 GB to 3 GB Volatile RAM
* **Minimum Local Storage Footprint:** 4 GB to 5 GB for verification deployment files
* **Development Toolchain:** GNU Compiler Collection (GCC) cross-compiler, GNU Assembler, GRUB bootloader environment
