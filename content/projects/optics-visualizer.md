---
title: "Optics & Photography Simulator"
date: 2025-10-13
description: "Interactive tool to explore geometric optics, image formation, optical aberrations, and photography principles."
tags: ["physics", "optics", "photography", "diffraction", "lenses", "visualization", "streamlit", "python"]
external_link: "https://optics-visualizer.streamlit.app/"
---

# 🔍 Optics & Photography Simulator

## Explore the Fascinating World of Light and Images

Interactive application providing **dynamic visualizations** of fundamental concepts in geometric optics, image formation, and photography. From basic thin lens equations to quantum limits of resolution imposed by diffraction.

### 🎯 What We Explore

- **🔭 Lenses and Ray Tracing**: Image formation with three principal rays
- **📸 Camera Model**: Depth of field, aperture, bokeh, and FOV
- **🌈 Optical Principles**: Snell's law, refraction, Airy disk, and diffraction limit
- **⚙️ Optical Aberrations**: Five Seidel aberrations and chromatic correction
- **🔬 Resolution Criteria**: Rayleigh, Dawes, and Sparrow with astronomical simulations

Each visualization is **interactive**: adjust parameters and observe how the system responds in real time.

---

## 📖 Main Features

### 🔭 Lenses and Ray Tracing

Implements the thin lens equation: $\frac{1}{f} = \frac{1}{s} + \frac{1}{s'}$

- Converging and diverging lenses with dynamic ray tracing
- Automatic classification: real/virtual, upright/inverted, magnified/reduced
- Limit cases: object at focus, magnifying glass (s < f)

### 📸 Camera Simulator

- **Depth of field**: hyperfocal distance and sharpness limits calculation
- **Bokeh simulation**: shape according to diaphragm blade count
- **Sensor comparison**: Full Frame, APS-C, Micro 4/3, smartphone
- Graphs showing sharp zones and aperture-diffraction relationship

### 🌈 Optical Principles

**Snell's Law**:
- Interactive refraction with total internal reflection detection
- Pre-configured common materials

**Airy Disk and Diffraction**:
- Dynamic diffraction pattern with fixed axes
- First and second minimum visualization
- Radial intensity profile $I(r) = I_0[2J_1(kr)/kr]^2$

**Resolution Criteria**:
- Rayleigh (1.22 λ/D), Dawes (116/D mm), Sparrow (0.95 λ/D)
- Double star experiment with 6 separation cases
- Real examples: Albireo, α Centauri

### ⚙️ Advanced Analysis

**Seidel Aberrations**:
1. Spherical, 2. Coma, 3. Astigmatism, 4. Field curvature, 5. Distortion

**Chromatic Correction**:
- Achromatic doublet calculator with validation
- Visual comparison: simple lens vs doublet (R, G, B rays)
- Abbe number and achromatic condition: $\frac{P_1}{V_1} + \frac{P_2}{V_2} = 0$

**Quality Criteria**:
- Strehl ratio (>0.8 = diffraction-limited)
- Wavefront error (λ/4 Maréchal criterion)
- MTF (Modulation Transfer Function)

---

## 🎓 Educational Approach

**Level**: Advanced high school / University (Physics)

Educational features:
- Rigorous yet accessible explanations
- Over **30 mathematical formulas** with visualizations
- Comparative tables of real instruments (Hubble, VLT, microscopes)
- Quantum connection: diffraction and Heisenberg's uncertainty principle
- Practical cases: astronomy, microscopy, photography

---

## 🛠️ Technical Implementation

- **Streamlit**: interactive web interface
- **Plotly**: 2D graphics with zoom, pan, and hover
- **NumPy**: numerical calculations and diffraction patterns
- **4 tabs** with logical learning flow
- Real-time calculation with parameter validation

---

## 🌟 Purpose

Optics is fundamental in science (telescopes, microscopes), technology (cameras, fiber optics), and art (photography). This application bridges the gap between **mathematical theory** and **intuitive understanding**, allowing you to:

- See in real time how images change when varying parameters
- Understand the aperture-diffraction-aberrations trade-off
- Appreciate the fundamental resolution limit of light
- Comprehend chromatic correction in professional instruments

---

[**🚀 Launch Interactive Simulator >>**](https://optics-visualizer.streamlit.app/)