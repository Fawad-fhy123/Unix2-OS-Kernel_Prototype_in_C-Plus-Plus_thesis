# UNIX 2 – Computer Operating System Kernel Prototype in C++

Undergraduate Bachelor's Thesis: Design and Implementation of a 32-bit Monolithic Unix-like Operating System Kernel Prototype Using Assembly and C++.

# Overview

This repository contains the technical documentation, implementation materials, and final bachelor's thesis for the UNIX 2 Operating System Kernel Prototype, a 32-bit monolithic operating system kernel developed using  Assembly and C++.

**Full Thesis**: UNIX_2_OS_Kernel_Thesis.pdf
**Institution**: Indus University, Faculty of Computing and Information Technology (FCIT), Pakistan.
**Project Area** : Operating Systems, Computer Architecture, Systems Programming, and Software Engineering.


## 🏛️ Individual Contribution and Project Scope

**Nature of the Project**

This undergraduate final-year project was formally registered and submitted as a collaborative group project involving three team members, in accordance with the institutional requirements of Indus University.

Within this collaborative framework, I undertook individual responsibilities in kernel architecture, low-level systems implementation, research, system design, and technical evaluation. The following sections describe my contributions to the overall project.

**1. Technical Development and Systems Programming**

My primary technical responsibilities involved the design and implementation of core components of the monolithic kernel using Assembly and freestanding Object-Oriented C++.

My contributions included:

Developing the system initialization sequence using the GRUB Multiboot bootloader.
Implementing the transition to 32-bit protected-mode execution.
Configuring the Interrupt Descriptor Table (IDT) and implementing Interrupt Service Routines (ISRs).
Configuring the Programmable Interrupt Controllers (PIC) for hardware interrupt handling.
Developing memory-mapped VGA text-mode display functionality.
Implementing process management functionality using a Round-Robin (RR) scheduling algorithm and hardware timer interrupts.
Contributing to the development of a graphical interface framework for kernel-level display operations.

**2. Research Methodology and System Design**

My research responsibilities included examining established operating system architectures and analysing design approaches associated with monolithic kernels, microkernel architectures, and Unix-like operating systems.

My contributions included:

Conducting a literature review of relevant operating system architectures and design principles.
Analysing kernel organisation, memory management, interrupt handling, and process scheduling.
Contributing to the architectural design and structural organisation of the proposed kernel.
Preparing system architecture diagrams, Activity Diagrams, and Sequence Diagrams to document system components and execution workflows.
Defining relevant data structures and documenting system design decisions.

**3. Development Management, Testing and Evaluation**

My responsibilities also included development and evaluation activities associated with the kernel implementation.

These activities included:

Working with a GNU GCC cross-compilation toolchain and GNU Assembler.
Conducting functional testing in virtual machine and emulator environments.
Evaluating kernel initialisation, interrupt handling, process scheduling, and system functionality.
Performing bare-metal deployment tests on physical hardware using bootable storage media.
Documenting implementation behaviour, testing procedures, and evaluation observations.

**4. Individual Contribution Statement**

Although the project was formally completed as a collaborative undertaking involving three team members, the technical development, research, system design, and evaluation responsibilities described above identify my individual contributions within the overall project.

The final thesis documents the collective project, while this statement identifies my specific academic and technical responsibilities.

###  🛠️ System Specifications and Development Environment
**Target Architecture**: 32-bit x86 (i386)
**Programming Languages**: C++ and Assembly
**Bootloader**: GRUB Multiboot
**Development Toolchain**: GNU GCC cross-compiler and GNU Assembler
**Interrupt Management**: IDT, ISRs, and PIC configuration
**Process Scheduling**: Round-Robin scheduling
**Testing Environments**: Virtual machine emulators and physical x86 hardware

**Academic Documentation**

The complete bachelor's thesis is provided in this repository as UNIX_2_OS_Kernel_Thesis.pdf.

It documents the project's objectives, architectural design, implementation approach, technical development, and evaluation.
