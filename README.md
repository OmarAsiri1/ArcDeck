# 🎮 ArcDeck

<p align="center">
  <strong>The only all-in-one emulator frontend you will ever need on iOS. Optimized for sideloading.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Under_Development-orange?style=for-the-badge&logo=github" alt="Status">
</p>

---

> ⚠️ **Notice:** This project is currently **under active development**. Features, UI layouts, and sub-systems are being built and optimized daily. Stay tuned for the first alpha release!

---

## 🚀 Overview

**ArcDeck** is a powerful, lightweight, and deeply customizable all-in-one emulation frontend built entirely in **SwiftUI** for the modern UI layer, powered by optimized backend engines via Objective-C++ bridging. 

Instead of cluttering your iOS device with a dozen different standalone emulator apps, ArcDeck consolidates everything into a single, unified console launcher interface with a modular backend architecture. Designed from the ground up to take full advantage of iOS ProMotion (120Hz) and native metal rendering pipelines.

---

## 🕹️ Massive Console Support (All-in-One)

ArcDeck is engineered to be the ultimate multi-system frontend, bringing a massive library of retro, classic, and modern handheld/home consoles under one single roof. No more switching between multiple apps or handling messy configurations. Everything runs smoothly inside a single unified binary via optimized custom backend engines.

Here is the complete, realistic list of supported hardware architectures currently active on iOS:

| Generation / Category | Supported Consoles & Systems | Architecture & Integration |
| :--- | :--- | :--- |
| **Modern Handhelds** | 🎮 Nintendo Switch (NSW) | Native 64-bit ARM Execution & Memory Mapping |
| **Generation 6 Giants** | 👾 PlayStation 2 (PS2) <br> 🌪️ Nintendo GameCube | High-Performance Graphic Pipeline & Vector Unit Bridging |
| **Sony Handhelds** | 🏎️ PlayStation Portable (PSP) | Native UI Translation *(with dynamic XMB layout support)* |
| **Nintendo Handhelds**| 📱 Nintendo 3DS <br> 📱 Nintendo DS <br> 🕹️ Game Boy Advance (GBA) | Dual-Screen Layout Optimization & Low-Latency Custom Renderers |
| **Classic Home Consoles**| 🌪️ Nintendo Wii <br> 🎮 Nintendo 64 (N64) <br> 🌀 Sega Dreamcast | High-Fidelity Geometry Engine & Floating-Point Optimization |
| **16-Bit / 32-Bit Era** | 👾 PlayStation 1 (PS1) <br> 🕹️ Sega Saturn <br> 🕹️ SNES / Super Famicom <br> 🕹️ Sega Genesis / Mega Drive / CD / 32X | Dynamic Recompilation & Shared State Management |
| **8-Bit Retro Classics** | 🕹️ NES / Famicom <br> 🕹️ Game Boy / Game Boy Color (GBC) <br> 🕹️ Sega Master System / Game Gear <br>  Atari 2600 / 7800 | Pixel-Perfect Integer Scaling & Low-Latency Input Processing |
| **Niche & Cult Handhelds**| 🪙 Neo Geo Pocket / Color <br> 🐧 Bandai WonderSwan / Color <br> 📱 Atari Lynx | Optimized Sprite Rendering & Form-Factor Display Scaling |
| **Arcade & Computers** | 🎰 MAME (Arcade Classics) <br> 🕹️ Neo Geo AES/MVS <br> 💾 Commodore 64 (C64) <br> 💻 DOSBox (Classic PC Games) | Vector Graphic Rendering & Virtual Keyboard/Mouse Mapping |

> 💡 *All emulation engines are deeply integrated directly into ArcDeck's core binary, sharing system resources to maintain an incredibly lightweight application footprint, maximizing fluid performance with zero configuration hassle.*

---

## ✨ Key Features

* **Unified Console Frontend:** Experience your ROM library through stunning, fluid console layouts (XMB, Switch OS, and custom grid themes).
* **Deep Cloud Customization:** Fully integrated with a remote GitHub repository to fetch custom themes, HD textures, CRT Shaders, and box art on the fly.
* **Metal API Rendering:** Maximum performance and zero thermal throttling by leveraging Apple's Metal framework for low-level graphic pipelines.
* **Native iOS Integration:** Smooth 120Hz ProMotion animations, CoreHaptics integration for physical controller vibration replication, and Live Activities support.
* **JIT Enabled out of the box:** Built to fully utilize Just-In-Time compilation through modern sideloading tools for heavy systems like PS2, GameCube, and Switch.

---

## 🛠️ System Architecture

ArcDeck bridges the gap between high-level SwiftUI design and low-level C++ execution performance.
