# Pacedall Clarity

> Browser-based pronunciation coaching for clearer, more confident international English.

**Live URL:** clarity.pacedall.com

## What It Does
Pacedall Clarity helps users improve pronunciation clarity through structured practice with immediate feedback. It covers the most common pronunciation challenges for international English speakers.

## Five Exercise Categories

| Category | Focus |
|----------|-------|
| Vowel Sounds | Long/short vowels, diphthongs, neutral vowels |
| Consonant Clarity | TH sounds, V/W, L/R placement |
| Word Stress | Stress patterns that change meaning |
| Connected Speech | Linking words naturally in phrases |
| Professional Phrases | Presentations, interviews, meetings |

## How It Works
1. **Listen** — hear the correct pronunciation via the browser's text-to-speech engine
2. **Record** — tap the big red mic button and say the word or phrase
3. **Playback** — hear yourself back immediately
4. **Score** — speech recognition scores your attempt (Great / Good / Keep Trying)
5. **Advance** — move to the next exercise when ready

## Browser Requirements
- **Chrome or Edge required** for speech recognition
- Firefox and Safari have limited Web Speech API support
- Mic permission required for recording and recognition

## Features
- 40 exercises across 5 categories
- Multiple target voice options (British, American, Australian)
- Live waveform visualiser
- Session progress tracking
- Phonetic transcriptions (IPA) for each exercise
- Pronunciation tips for every word and phrase
- Works entirely in the browser — no server, no account

## Keyboard Shortcuts
| Key | Action |
|-----|--------|
| Space | Start/stop recording |
| L | Listen to target pronunciation |
| → | Next exercise |
| ← | Previous exercise |

## Deployment (Cloudflare Pages via GitHub)
1. Push to GitHub repo
2. Cloudflare Pages → connect repo
3. No build command, output directory: `/`
4. DNS CNAME: `clarity` → your `.pages.dev` domain

## The Pacedall Flow Suite
| App | URL |
|-----|-----|
| Pacedall Flow | flow.pacedall.com |
| Pacedall Breath | breath.pacedall.com |
| Pacedall Voice | voice.pacedall.com |
| Pacedall Cue | cue.pacedall.com |
| Pacedall Clarity | clarity.pacedall.com |

---
Built by Pacedall.com — Small but Awesome.
