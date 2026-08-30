<div align="center">

# Langara Hacks 2024 Project

### A full-stack music experience built for Langara Hacks 2024.

[![React](https://img.shields.io/badge/React-18-20232a?logo=react)](https://react.dev/)
[![Tailwind](https://img.shields.io/badge/Tailwind-CSS-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Node.js](https://img.shields.io/badge/Node.js-Server-339933?logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Python](https://img.shields.io/badge/Python-Audio%20Processing-3776AB?logo=python&logoColor=white)](https://www.python.org/)

</div>

---

## Overview

This repository contains the prototype built around Langara Hacks 2024. The project combines a React frontend with a Node.js/Python backend flow for retrieving song information, working with lyrics, and experimenting with interactive audio functionality.

The codebase includes:

- a React interface with drag-and-drop interaction;
- song and lyrics retrieval through external APIs;
- audio playback components;
- Python tooling for media/audio processing;
- a lightweight backend service used by the frontend;
- Tailwind CSS for UI styling.

## What I worked on

The project was a practical exercise in connecting multiple parts of a product under hackathon constraints: frontend interaction, external APIs, server-side integration, and media processing.

Key engineering areas included:

- building reusable React components;
- consuming remote song/lyrics data;
- coordinating frontend and backend services;
- handling audio-related workflows;
- integrating JavaScript and Python tooling in one project.

## Stack

| Area | Technology |
| --- | --- |
| Frontend | React 18 |
| Styling | Tailwind CSS |
| HTTP | Axios |
| Backend | Node.js |
| Media tooling | Python, FFmpeg |
| Audio separation | `audio-separator` |
| External data | Genius API |

## Repository structure

```text
langarahack2024/
├── hackathon2024/      # React application + Node server
├── python/             # Python/media-processing utilities
├── requirements.txt
└── README.md
```

The main web application lives under `hackathon2024/`.

## Run the frontend

```bash
cd hackathon2024
npm install
npm start
```

## Python/media dependencies

On macOS:

```bash
pip install audio-separator[cpu] fastapi uvicorn yt-dlp
brew install ffmpeg
```

## Portfolio note

This is an older hackathon project and is kept public as part of my development history. My newer work goes much deeper into backend systems, cloud infrastructure, search, networking, and native applications.

---

<div align="center">

Built during **Langara Hacks 2024**.

</div>
