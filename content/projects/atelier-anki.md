---
title: "L'Atelier Anki: AI French Flashcard Generator"
date: 2026-06-02
draft: false
description: "An AI-powered web application that automatically generates comprehensive French Anki flashcard data from words in Spanish, English, or French."
tags: ["react", "typescript", "gemini-ai", "tailwindcss", "education", "language-learning"]
external_link: "https://agarciasoria.github.io/Tarjetas-Anki/"
---

## 🇫🇷 Overview

L'Atelier Anki is a streamlined tool designed to supercharge the flashcard creation process for French language learners. By integrating Google's Gemini AI model, the application eliminates the tedious manual work of looking up translations, phonetics, and contextual sentences, generating a perfect Anki card in seconds.

## ✨ Key Features

- **Smart Generation:** Input a word in Spanish, English, or French and instantly get all the structured data needed for an Anki flashcard.
- **Comprehensive Fields:** 
  - 🗣️ **Pronunciation (IPA):** Accurate International Phonetic Alphabet transcription.
  - 🌍 **Translations:** Direct Spanish and English translations.
  - 📚 **Natural Context:** A cohesive French example sentence with its Spanish translation.
  - 💡 **Clarifications:** Short semantic explanations to distinguish subtle nuances.
- **Bring Your Own Key (BYOK) Architecture:** Users input their own free Gemini API Key, which is securely saved in the browser's local storage, allowing for a zero-cost static deployment.
- **Productivity-Driven Design:** Clean, minimalist bento-box UI with one-click copy buttons and built-in instructions for setting up audio via AwesomeTTS in Anki.

## 🛠️ Technologies Used

- **Frontend:** React, TypeScript, and Vite for blazing-fast performance.
- **Styling:** TailwindCSS for a modern, responsive, and highly polished interface.
- **Artificial Intelligence:** Google GenAI SDK (Gemini 3 Flash Preview) configured with strict JSON schema system instructions.
- **Deployment:** GitHub Actions and GitHub Pages for static hosting and continuous integration.

## Live Application

🚀 **[Launch L'Atelier Anki](https://agarciasoria.github.io/Tarjetas-Anki/)**