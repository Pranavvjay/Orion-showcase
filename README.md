# Jarvis: personal AI assistant (showcase)

A voice-first, agentic personal assistant for Android and the web that I built for my own
college life. It runs my calendar, calls me every morning with a briefing, tracks goals,
money and food, sorts my college email, and rings my phone when something urgent comes in.

**Site:** https://pranavvjay.github.io/jarvis-showcase/ · **Privacy policy:** [privacy.html](privacy.html)

The source code is private; this repo only holds the showcase page and privacy policy.

## Highlights
- Voice conversations, hands-free, on phone and laptop
- A team of AI agents (LangGraph): a router picks the skills each message needs; background
  agents prepare the morning briefing, sort college mail, log payments and read meal photos
- Real phone calls from the assistant (morning briefing, evening recap, "call me at 4"), even
  with the app closed (push via Expo + Firebase)
- Google Calendar / Tasks / Gmail integration, shown live in the real calendar app
- Runs entirely on free tiers: Groq, open neural voices, the laptop as the server

## Stack
Python · FastAPI · LangGraph · Groq · SQLite · Expo / React Native · Kotlin · Firebase · Tailscale
