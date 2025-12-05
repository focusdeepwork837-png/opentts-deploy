# opentts-deploy
# OpenTTS Deploy (Render-ready)

This repo runs OpenTTS via Docker. It exposes the TTS server on port 5002.

Endpoints commonly available:
- GET /voices  -> list voices
- POST /api/tts or POST /tts -> accepts JSON { text, voice, format:'mp3' } and returns MP3 binary.

Use Render (or Railway) to deploy this docker-compose / Dockerfile repo.
