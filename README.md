# QEMU-Micro-Kernel

A lightweight, custom-built microkernel designed to run on QEMU. This microkernel features image rendering and a basic VIM-style text editor. Built entirely in C, it is fully self-contained with no external library dependencies.

## 🧠 Features

- **Microkernel Architecture**  
  Minimalist core handling low-level operations, with modular classes for specific functionality.

- **Image Display**  
  Load and render images directly within the QEMU virtual environment.

- **VIM-style Text Editor**  
  Navigate and edit text using familiar VIM keybindings within the kernel environment.

- **No External Dependencies**  
  All necessary libraries are included—no additional installs required.

## 📁 File Overview
- Place Holder Overview
| File Name         | Description |
|------------------|-------------|
| `kernel.c`        | Entry point and core logic for microkernel boot and runtime scheduling. |
| `display.c`       | Handles image loading, rendering, and screen refresh cycles. |
| `editor.c`        | VIM-style text editor implementation, including insert, normal, and visual modes. |
| `drivers.c`       | Low-level hardware interfacing (keyboard, video memory, timers). |
| `utils.c`         | Helper functions and internal utilities shared across modules. |

> 🔧 All class files are modular and can be expanded with new features as needed.

## 🚀 Getting Started

### Requirements

- QEMU (any recent version)
- GCC or Clang (for building)
- Make (if using provided Makefile)
