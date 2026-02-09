# Aurora Audio Recorder

Aurora Audio Recorder is a browser-based web application designed to transform any device into a **portable vocal recording environment**.  
The project is built around the concept of a **Vocal Sphere**: a mobile recording system that combines **software and physical acoustic solutions** to recreate studio-like recording conditions outside of a traditional studio.

Portability in this context is not only related to mobility, but also to **accessibility, flexibility, and ease of use**.

To use directly the web application go to https://kevinporcu.github.io/aurora_audio_recorder/

---
## IMPORTANT NOTE

Google Drive access is currently limited because the application is in testing mode. To enable Drive integration, users must contact the project owner via email to be added as authorized testers.
The owners' email are at the end of the ReadMe.

---

## Concept

Aurora Audio Recorder is part of a broader recording system conceived to enable vocal recording in **non-treated environments** while maintaining control over sound quality.

The system is composed of:
- a **web-based audio application**
- an optional **face mask**, designed to reduce early reflections and environmental noise close to the microphone
- a **compact vocal box**, built to improve acoustic isolation and absorption around the performer

When used together, these elements adapt the surrounding environment for vocal recording, allowing the user to approach **studio-like conditions** even in temporary or mobile setups.  
The web application represents the digital core of the system, while the face mask and vocal box provide **passive acoustic conditioning**.

---

## Main Features

Aurora Audio Recorder provides a complete vocal recording workflow directly in the browser:

- Recording from the device microphone using the **Web Audio API**
- Real-time waveform visualization during playback
- Manual control of audio parameters through **interactive knobs**
- Preset system with **four predefined effect chains**
- Playback of recordings **with or without effects**
- Export of recordings as **WAV files** (clean or processed)
- Direct upload of WAV files to **Google Drive**

All audio processing and rendering are performed **client-side**, without requiring external software or plugins.

---

## Google Drive Integration

Aurora Audio Recorder supports cloud storage through **Google Drive integration**.

After authorization:
- A dedicated folder is automatically created on the user’s Drive
- Clean and processed WAV files can be uploaded independently
- File names are generated using timestamps to prevent overwriting existing recordings

This feature enables simple **backup, sharing, and cross-device access** directly from the application.

---

## Technologies Used

- **HTML5**, **CSS**, **JavaScript**
- **Web Audio API**
- **MediaRecorder API**
- **OfflineAudioContext** for effect rendering
- **Google Drive REST API**

---

## Project Context

Aurora Audio Recorder was developed as an **academic project**.

---

# Owners:

Gabriele Berrini (gabriele.berrini@mail.polimi.it) & 
Kevin Porcu (kevin.porcu@mail.polimi.it)


