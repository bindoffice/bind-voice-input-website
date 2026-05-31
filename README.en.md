# Bind Voice Input

**Speak, don't type.**

Bind Voice Input is a macOS-native, fully offline voice input tool. Press a global hotkey to start speaking, press again when you're done — recognized text is injected at the cursor in any app. No internet required; your voice never leaves your Mac.

[中文](./README.md)

---

## Why Bind Voice Input

| | Bind Voice Input | Typical Cloud ASR |
|---|---|---|
| Where speech is processed | 100% on your Mac | Uploaded to the cloud |
| Works offline | ✓ Fully offline | Requires internet |
| Usage / API fees | No per-minute billing | Subscription or pay-per-minute |
| Data privacy | Voice stays on device | Routed through third-party servers |
| Input in any app | ✓ System-level injection | Usually limited to vendor's own app |
| Screen OCR | ✓ Built in | — |
| macOS integration | ✓ Native menu-bar app | Cross-platform, generic UX |

---

## Core Features

### Fully Offline, Local ASR

Powered by the built-in Qwen3-ASR model, speech recognition runs entirely on your Mac. No API calls, no usage-based fees — works even when you're offline.

- Run locally forever after the initial model download
- Low latency — text appears as soon as you finish speaking
- Multilingual recognition including Chinese, English, and more

### Global Hotkey — Speak and Write Instantly

Press a hotkey to start recording, press again to finish. The transcript is injected at the current cursor position. No window switching — seamless for writing, chat, and coding.

- Customizable global hotkey
- Tap to start / tap again to stop
- Works in most macOS apps (Word, Notion, Slack, VS Code, Gmail, Terminal, and more)

### Screen OCR Capture

Select any region on screen and extract text in one step. Combine with voice input to turn what you see and what you say into editable text.

- Select any screen region
- Multilingual OCR
- Copy or inject results directly

### Conversation Translation & Refinement

Built-in translation dialog with multi-turn support. Optional LLM refinement makes dictated text clearer and more polished.

- Real-time voice translation conversations
- Optional local or cloud LLM refinement
- UI available in 12 languages

---

## System Requirements

- **macOS 14** (Sonoma) or later
- Optimized for **Apple Silicon** (M-series); Intel Macs are supported but may be slower
- Initial launch downloads the Qwen3-ASR model (hundreds of MB, one-time)

---

## Download

[Download Bind Voice Input for macOS](https://github.com/bindoffice/bind-voice-input-website/raw/refs/heads/main/assets/Bind-Voice-Input-2.0.1.dmg)

Free to download, runs locally. First launch walks you through permissions (microphone, accessibility) and model download.

---

## Design Principles

1. **Unobtrusive** — Menu-bar icon and lightweight overlay; stays out of your way
2. **Efficient** — Speaking is faster than typing; keep your flow uninterrupted
3. **Trustworthy** — Local processing, transparent permissions, data stays on your Mac
4. **Focused** — Deep macOS optimization, not a cross-platform compromise

---

## Links

| | |
|---|---|
| Product landing page | `index.html` in this directory (static site) |
| BindOffice | [bindoffice.com](https://bindoffice.com) |
| Website repo | [bindoffice/bind-voice-input-website](https://github.com/bindoffice/bind-voice-input-website) |

---

© 2026 [BindOffice](https://bindoffice.com). Made for Mac · Privacy first
