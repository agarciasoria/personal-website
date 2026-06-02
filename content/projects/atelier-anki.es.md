---
title: "L'Atelier Anki: Generador de Tarjetas de Francés con IA"
date: 2026-06-02
draft: false
description: "Una aplicación web impulsada por IA que genera automáticamente contenido completo para tarjetas de Anki de francés a partir de palabras en español, inglés o francés."
tags: ["react", "typescript", "gemini-ai", "tailwindcss", "educación", "idiomas"]
external_link: "https://agarciasoria.github.io/Tarjetas-Anki/"
---

## 🇫🇷 Resumen

L'Atelier Anki es una herramienta diseñada para agilizar el proceso de creación de tarjetas de memoria (flashcards) para estudiantes de francés. Integrando el modelo de lenguaje de Google Gemini, la aplicación elimina el tedioso trabajo manual de buscar traducciones, fonética y contextos, generando una tarjeta perfecta en cuestión de segundos.

## ✨ Características Principales

- **Generación Inteligente:** Introduce una palabra en español, inglés o francés y obtén instantáneamente todos los datos necesarios para tu tarjeta de Anki.
- **Campos Completos:** 
  - 🗣️ **Pronunciación (IPA):** Transcripción fonética exacta del francés.
  - 🌍 **Traducciones:** Traducción directa al español e inglés.
  - 📚 **Contexto Natural:** Una oración de ejemplo en francés con su respectiva traducción al español.
  - 💡 **Aclaraciones:** Breves explicaciones semánticas para distinguir matices.
- **Arquitectura "Bring Your Own Key" (BYOK):** Los usuarios introducen su propia clave API gratuita de Gemini, la cual se guarda de forma segura en el almacenamiento local del navegador, permitiendo un despliegue estático a coste cero.
- **Diseño Orientado a la Productividad:** Interfaz limpia y minimalista con botones de copia en un clic e instrucciones integradas para configurar el audio con AwesomeTTS en Anki.

## 🛠️ Tecnologías Utilizadas

- **Frontend:** React, TypeScript y Vite para un rendimiento ultrarrápido.
- **Estilos:** TailwindCSS para una interfaz moderna, responsiva y de diseño tipo "bento-box".
- **Inteligencia Artificial:** Google GenAI SDK (gemini-3-flash-preview) configurado con instrucciones de sistema (system prompts) estructuradas en JSON.
- **Despliegue:** GitHub Actions y GitHub Pages para alojamiento estático e integración continua.

## Aplicación en Vivo

🚀 **[Lanzar L'Atelier Anki](https://agarciasoria.github.io/Tarjetas-Anki/)**