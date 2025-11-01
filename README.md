# 🌌 The Fountain-Inspired Shader Experience

👉 **Live, forkable version on Rosebud AI:**  
[Fountain Experience](https://rosebud.ai/p/8080f392-906b-4f5a-9e8f-55187a3f6f34)

A **Fountain-inspired** volumetric nebula shader — a derivative of [Duke’s “Supernova”](https://www.shadertoy.com/view/MdKXzc) — rebuilt for **Three.js** and **WebXR**.  
Implements a custom **spiral FBM noise field**, **adaptive ray-marching**, **golden emission palette**, and **interactive camera controls**, producing an ethereal, Aronofsky-style cosmic scene.



🎥 **Shader breakdown video:**  
[Watch here](https://screen.studio/share/sIim9KcE?private-access=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzaGFyZWFibGVMaW5rSWQiOiJhODgzZDNhOC00ZGRiLTQ4MmEtODI0Ny0xYjk2OTk4NjkzYjkiLCJpYXQiOjE3NjIwMzEwOTl9.WEtnicyO1Wr8oN0yXNhvqouDf0fi_8VWlxSUtq3N6iU)

---

## 🧠 Technical Overview

- **Language:** GLSL (fragment shader)  
- **Runtime:** Three.js + WebXR (VR-ready)  
- **Techniques:**  
  - Volumetric ray-marching with adaptive step size  
  - Spiral + FBM procedural noise field  
  - Disk-based nebula density shaping  
  - Filmic tonemapping (Hable curve)  
  - Dithering and bloom for cinematic contrast  
  - Mouse/touch + VR interaction via uniform inputs  
- **Performance:** Optimized marching (48 iterations, distance-adaptive steps)  
- **Visual Goal:** evoke the *birth-death-rebirth* motifs of *The Fountain* through light and dust motion

---

## 🧩 Credits

- **Original base shader:** [Duke — “Supernova remnant” (ShaderToy)](https://www.shadertoy.com/view/MdKXzc)  
- **Hosting & live editor:** [Rosebud AI](https://rosebud.ai)

---

## 📜 License

This project is a derivative of Duke’s “Supernova remnant” (ShaderToy) and is released under the  
**Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported (CC BY-NC-SA 3.0)** license.

---

### 🚀 Quick Start
You can remix on [Fountain Experience](https://rosebud.ai/p/8080f392-906b-4f5a-9e8f-55187a3f6f34)
