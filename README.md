# 🏋️ Antigravity Desktop Gym

> **A Precision Sandbox for AI Desktop Agents**

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg) ![Status: Experimental](https://img.shields.io/badge/Status-Experimental-orange.svg)

The **Antigravity Desktop Gym** is a lightweight, controlled environment designed to verify and calibrate the precision of AI Desktop Agents. It solves the "Reality Gap" where testing on a chaotic live desktop (with real files) creates noisy, unreliable data.

**Stop guessing if your agent missed the click. Know for sure.**

## 🎯 Features

- **High-Contrast "Dark Mode" UI:** Optimized for computer vision; minimizes glare and visual noise.
- **Dynamic Targets:** Buttons spawn at randomized coordinates to prevent hard-coded "cheating."
- **Pixel-Perfect Logging:**
    - Tracks `ClientX/Y` vs `ScreenX/Y`.
    - Logs exact "Hit" or "Miss" status.
    - Calculates distance-from-center offset (e.g., `Offset: 0.0px`).
- **Zero-Install:** It's just a single HTML file you can run anywhere.

## 🚀 Quick Start

1.  **Clone** this repository.
2.  **Open** `index.html` in any modern web browser (Edge/Chrome recommended).
3.  **Maximize** the window (F11 for best results).
4.  **Point your Agent** at the screen and tell it to click the targets!

## 🧪 The "Fluidity" Experiment

This tool was created to validate **Project Fluidity**—an initiative to replace robotic "start-stop" mouse emulation with human-like interpolated movement.

> [Read the full Experiment Report](./docs/report.md)

## 🛠️ Usage for Agents

The Gym provides clear visual cues for Computer Vision models:
- **Target Color:** `rgba(0, 255, 157, 0.1)` (Neon Green)
- **Hit Feedback:** Target flashes solid Green.
- **Miss Feedback:** Logs "MISS" in Red text.

## 🧩 Compatible Driver

This Gym is designed to verify the **Antigravity Fluid Mouse** driver.
> **[Download the Fluid Mouse Driver (NewportRiver/nutjs-windows-control-fluid)](https://github.com/NewportRiver/nutjs-windows-control-fluid)**

## 🤝 Contributing

This is a research prototype. Pull requests for new "training modules" (e.g., Drag & Drop zones, Typing speed tests) are welcome!

## 🎖️ Credits & Acknowledgements

**Lead Systems Engineer & Architect:**
- **Mark Anthony Bartholomew** ([@NewportRiver](https://github.com/NewportRiver)) - *Newport River Company*

**AI Co-Developer:**
- **Gemini** ([Google DeepMind](https://deepmind.google/technologies/gemini/)) - *Algorithm design & implementation*

**Development Environment:**
- Built within the **Antigravity Workspace**, a specialized fork of **VS Code** by [Microsoft](https://github.com/microsoft/vscode).

**Core Technologies:**
- **NutJS:** The underlying automation engine. [https://nutjs.dev](https://nutjs.dev)
- **MCPControl:** Original server foundation by [Cheffromspace](https://github.com/Cheffromspace/MCPControl).

---
*Built with ❤️ at Newport River Company*
