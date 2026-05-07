---
title: "Simulador de Salidas de Atletismo"
date: 2026-04-15
draft: false
description: "Una aplicación web móvil que utiliza los sensores de movimiento del smartphone para simular un juez de salida y calcular tiempos de reacción con precisión de milisegundos."
tags: ["react", "typescript", "tailwind", "web-audio-api", "accelerometer", "atletismo", "vite"]
external_link: "YOUR_APP_https://agarciasoria.github.io/track-start-simulator/URL_HERE"
---

## Resumen

El Simulador de Salidas de Atletismo es una aplicación web diseñada específicamente para dispositivos móviles con el objetivo de ayudar a los velocistas a practicar sus tiempos de reacción en los tacos de salida. Imita la secuencia exacta de una competición real de atletismo ("A sus puestos. Listos. ¡YA!") y aprovecha los sensores de movimiento integrados del smartphone (acelerómetro) para detectar el momento preciso en que el atleta explota desde los tacos.

## ✨ Características Principales

- **Cronómetro de Alta Precisión:** Calcula los tiempos de reacción hasta la milésima de segundo utilizando `performance.now()`. Marca las reacciones inferiores a 0.100s como salidas nulas oficiales.
- **Detección de Movimiento y Salidas Nulas:** Colocando el teléfono contra el taco de salida, la app detecta si hay movimiento durante la fase de "LISTOS" ("Set") y dispara un sonido de doble disparo para indicar una salida falsa.
- **Audio Procedural:** Tiempos auténticos con voz sintetizada para los comandos del juez y un sonido de disparo sintético generado matemáticamente con cero latencia.
- **Retraso Variable del Disparo:** Imita a un juez humano disparando la pistola en un intervalo aleatorio dentro de una ventana de tiempo personalizable.
- **Medidor de Sensores en Vivo:** Muestra la actividad del sensor en tiempo real para ayudar a los atletas a calibrar el umbral de sensibilidad para sus tacos y tipo de pista.


## Pruébalo
*(Nota: ¡La mejor experiencia es en un dispositivo móvil!)*

🚀 **[Lanzar Simulador de Salidas](https://agarciasoria.github.io/track-start-simulator/)**