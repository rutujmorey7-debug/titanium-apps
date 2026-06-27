# 🛠️ Titanium Apps

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![KDE Frameworks](https://img.shields.io/badge/Frameworks-KDE%206-blue)](https://kde.org/products/frameworks/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

Titanium Apps is a custom, high-performance suite of core desktop applications built by cloning and deeply modifying verified KDE components. Designed to drop seamlessly into a modern, minimalist desktop environment, this suite bridges the legendary stability of KDE frameworks with a unified, cyber-minimalist user experience.

---

## 🚀 Core Suite

The ecosystem replaces standard desktop utilities with completely reimagined, lightweight alternatives:

*   **📂 Titanium File Manager:** A dual-pane, ultra-responsive file navigator featuring integrated Git status indicators, instant folder indexing, and a modern sidebar layout.
*   **💻 Titanium Terminal:** A GPU-accelerated terminal emulator leveraging core `Konsole` tech, optimized with built-in split-pane support, customizable blur physics, and zsh profiling.
*   **📝 Titanium Text Editor:** A sleek code and prose editor powered by `KTextEditor`, augmented with lightning-fast auto-completion, multi-cursor editing, and live markdown preview panels.
*   **🧮 Titanium Calculator:** An advanced scientific tool supporting inline expression evaluation, custom variables, and structural history logging.

---

## ✨ Features

### 🎨 Unified Cyber-Minimalist Aesthetic
*   **Glassmorphic Accents:** Leverages modern compositor capabilities to implement subtle blur and translucent UI layers without degrading rendering performance.
*   **Strict Dark Mode Native:** Custom stylesheets override native Qt/KDE rendering to enforce a consistent, distraction-free color palette across all applications.

### ⚡ Performance & Core Overhauls
*   **De-Cluttered Architecture:** Stripped out legacy dependencies and niche configuration panels to prioritize cold-start speed and minimal RAM overhead.
*   **Advanced KIO Subsystem Tuning:** The file manager directly optimizes asynchronous I/O loops via custom `KIO` workers for rapid searching and file transfer.
*   **Integrated Dev Workflows:** The terminal and text editor communicate via a shared IPC (Inter-Process Communication) layer, allowing instant terminal nesting within active code directories.

---

## 🛠️ Getting Started

### Prerequisites

Ensure your system has the required Qt6 and KDE development packages installed:

```bash
# On Arch Linux
sudo pacman -S extra-cmake-modules qt6-base kio konsole ktexteditor
