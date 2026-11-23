# RetiFire Crosshair — Low Latency Gaming Overlay 🎯

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-blue?logo=windows)](https://github.com/Nitesh87409/RetiFire-Crosshair)
[![Framework](https://img.shields.io/badge/Framework-Flutter%20Desktop-02569B?logo=flutter)](https://flutter.dev)
[![Latency](https://img.shields.io/badge/Input%20Latency-Zero%20Overhead-success)](https://github.com/Nitesh87409/RetiFire-Crosshair)

> **RetiFire Crosshair** is a hardware-accelerated, customizable crosshair overlay utility for Windows gamers, offering zero input interference and pixel-perfect targeting.

---

## ✨ Key Features
- **Click-Through Transparent Overlay:** Utilizes native Windows `WS_EX_TRANSPARENT` and `WS_EX_LAYERED` window styles so mouse clicks pass directly into games without delay.
- **Extensive Reticle Library:** Multiple crosshair styles including Dot, Cross, Circle, Chevron, and Tactical HUD reticles.
- **Real-Time Customization:** Dynamic color picker, opacity slider, size scaling, and outline thickness adjustments.
- **Position Calibration:** Sub-pixel alignment controls to ensure the reticle aligns with any monitor resolution or aspect ratio.
- **Anti-Cheat Safe:** Pure external desktop overlay that does not inject code, hook game memory, or modify game files.

---

## 🛠️ Architecture & Tech Stack
- **Framework:** Flutter Desktop (Windows C++ Runner)
- **Windows APIs:** Win32 `SetWindowLongPtr`, `SetLayeredWindowAttributes`, `SetWindowPos`
- **Rendering:** Hardware-accelerated Canvas with custom vector shaders

---

## 🔒 Source Code & License Notice
> **Proprietary Software Notice:**  
> This repository is an official public portfolio showcase. The proprietary production source code is owned and maintained under **[NiteshCodes-Official](https://github.com/NiteshCodes-Official)**.