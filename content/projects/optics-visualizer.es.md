---
title: "Simulador de Óptica y Fotografía"
date: 2025-10-13
description: "Herramienta interactiva para explorar óptica geométrica, formación de imágenes, aberraciones ópticas y principios de fotografía."
tags: ["física", "óptica", "fotografía", "difracción", "lentes", "visualización", "streamlit", "python"]
external_link: "https://optics-visualizer.streamlit.app/"
---

# 🔍 Simulador de Óptica y Fotografía

## Explora el Fascinante Mundo de la Luz y las Imágenes

Aplicación interactiva que proporciona **visualizaciones dinámicas** de conceptos fundamentales en óptica geométrica, formación de imágenes y fotografía. Desde la ecuación básica de lentes delgadas hasta los límites cuánticos de resolución impuestos por la difracción.

### 🎯 Qué Exploramos

- **🔭 Lentes y Trazado de Rayos**: Formación de imágenes con los tres rayos principales
- **📸 Modelo de Cámara**: Profundidad de campo, apertura, bokeh y FOV
- **🌈 Principios Ópticos**: Ley de Snell, refracción, disco de Airy y límite de difracción
- **⚙️ Aberraciones Ópticas**: Cinco aberraciones de Seidel y corrección cromática
- **🔬 Criterios de Resolución**: Rayleigh, Dawes y Sparrow con simulaciones astronómicas

Cada visualización es **interactiva**: ajusta parámetros y observa cómo responde el sistema en tiempo real.

---

## 📖 Características Principales

### 🔭 Lentes y Trazado de Rayos

Implementa la ecuación de la lente delgada: $\frac{1}{f} = \frac{1}{s} + \frac{1}{s'}$

- Lentes convergentes y divergentes con trazado dinámico
- Clasificación automática: real/virtual, derecha/invertida, ampliada/reducida
- Casos límite: objeto en el foco, lupa (s < f)

### 📸 Simulador de Cámara

- **Profundidad de campo**: cálculo de hiperfocal y límites de nitidez
- **Simulación de bokeh**: forma según número de aspas del diafragma
- **Comparación de sensores**: Full Frame, APS-C, Micro 4/3, smartphone
- Gráficos de zonas nítidas y relación apertura-difracción

### 🌈 Principios Ópticos

**Ley de Snell**:
- Refracción interactiva con detección de reflexión total interna
- Materiales comunes preconfigurados

**Disco de Airy y Difracción**:
- Patrón de difracción dinámico con ejes fijos
- Visualización del primer y segundo mínimo
- Perfil radial de intensidad $I(r) = I_0[2J_1(kr)/kr]^2$

**Criterios de Resolución**:
- Rayleigh (1.22 λ/D), Dawes (116/D mm), Sparrow (0.95 λ/D)
- Experimento de estrellas dobles con 6 casos de separación
- Ejemplos reales: Albireo, α Centauri

### ⚙️ Análisis Avanzado

**Aberraciones de Seidel**:
1. Esférica, 2. Coma, 3. Astigmatismo, 4. Curvatura de campo, 5. Distorsión

**Corrección Cromática**:
- Calculadora de doblete acromático con validación
- Comparación visual: lente simple vs doblete (rayos R, G, B)
- Número de Abbe y condición acromática: $\frac{P_1}{V_1} + \frac{P_2}{V_2} = 0$

**Criterios de Calidad**:
- Ratio de Strehl (>0.8 = limitado por difracción)
- Error de frente de onda (λ/4 criterio de Maréchal)
- MTF (Función de Transferencia de Modulación)

---

## 🎓 Enfoque Educativo

**Nivel**: Bachillerato avanzado / Universidad (Física)

Características educativas:
- Explicaciones rigurosas pero accesibles
- Más de **30 fórmulas matemáticas** con visualizaciones
- Tablas comparativas de instrumentos reales (Hubble, VLT, microscopios)
- Conexión cuántica: difracción y principio de incertidumbre de Heisenberg
- Casos prácticos: astronomía, microscopía, fotografía

---

## 🛠️ Implementación Técnica

- **Streamlit**: interfaz web interactiva
- **Plotly**: gráficos 2D con zoom, pan y hover
- **NumPy**: cálculos numéricos y patrones de difracción
- **4 pestañas** con flujo lógico de aprendizaje
- Cálculo en tiempo real con validación de parámetros

---

## 🌟 Propósito

La óptica es fundamental en ciencia (telescopios, microscopios), tecnología (cámaras, fibra óptica) y arte (fotografía). Esta aplicación cierra la brecha entre **teoría matemática** y **comprensión intuitiva**, permitiendo:

- Ver en tiempo real cómo cambia una imagen al variar parámetros
- Entender el compromiso apertura-difracción-aberraciones
- Apreciar el límite fundamental de resolución de la luz
- Comprender corrección cromática en instrumentos profesionales

---

[**🚀 Lanzar Simulador Interactivo >>**](https://optics-visualizer.streamlit.app/)