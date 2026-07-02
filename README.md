# ASTA — Landing Page

A responsive landing page for **ASTA**, a voice-in, voice-out AI chatbot powered by Groq's Llama 3.3 70B model.

🔗 **Try ASTA live:** https://llm-chatbot-asta-production.up.railway.app
🔗 **ASTA backend repo:** https://github.com/Sakanavenkat/LLM-Chatbot-ASTA

## About

This is a standalone marketing/showcase page for the ASTA project — built separately from the backend to keep the two concerns clean (product code vs. presentation).

## Built with

- HTML5
- CSS3 (no frameworks — hand-written, mobile-first, responsive)
- Vanilla JS-free hamburger menu (pure CSS checkbox toggle)

## Features

- Fully responsive layout (breakpoints at 640px, 768px, 1024px)
- Animated waveform hero visual (CSS keyframes)
- Dark theme with teal/coral accent palette
- Zero build step — plain static HTML/CSS

## Run locally

git clone https://github.com/Sakanavenkat/asta-landing-page.git
cd asta-landing-page
python -m http.server 5500

Then open http://localhost:5500 in your browser.

