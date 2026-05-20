# Privacy-Preserving AI Assistant for Visually Impaired Users

A full-stack, offline-capable application built with React, Node.js, and SQLite, designed to be accessible and privacy-preserving.

## Features

- **Offline-First Security**: AES-256 encryption secures messages in a local SQLite database (`sql.js`).
- **Accessibility**: Built with WCAG 2.1 AA compliance (ARIA controls, Focus Rings, Keyboard Navigation).
- **Voice Capabilities**: Native browser Web Speech API for TTS and STT capabilities.
- **Offline Vision**: `Tesseract.js` executes image text recognition securely on the client side without sending images to external servers.
- **AI Integration**: Powered by Google Gemma 3 27B (`gemma-3-27b-it`) from Google AI Studio.

## Setup

1. Get FREE API key: https://aistudio.google.com/apikey
2. Add it to .env as GEMINI_API_KEY
3. Run: npm run install:all
4. Run: npm run dev
5. Open: http://localhost:5173
