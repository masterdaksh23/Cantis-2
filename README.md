# ✦ Cantis — Psychic AI Intelligence Platform

> **"Beyond the threshold of machine and mind."**  
> A production-ready, self-contained, high-performance AI chatbot with a futuristic dark aesthetic, 3D particle physics, psychic visual effects, and real-time streaming intelligence via OpenRouter.

---

## ⚡ Quick Start

Cantis is completely self-contained with zero required build steps.

### Method 1: Direct Browser Launch
Simply open `index.html` in any modern web browser:
```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

### Method 2: Local HTTP Server
Run with any standard static server:
```bash
# Using Node.js
npm start
# or
npx serve -l 3000 .

# Using Python 3
python3 -m http.server 3000
```
Then visit: `http://localhost:3000`

---

## 🎬 Section 1: Landing / 3D Intro Experience

- **3D Animated Intro**: Large, glowing, rotating 3D title **"CANTIS"** with psychic neon shimmer, multi-axis 3D perspective transforms, and dual orbital aura rings.
- **Entry Portal Button**: *"Enter into the World of Cantis"* with an ethereal breathing pulse glow, magnetic hover elevation, and a smooth cinematic warp transition into the chat interface.
- **Atmospheric Background Music**: Lo-fi ambient soundscape that starts seamlessly on page journey, equipped with an interactive play/pause audio controller and dual-engine fallback (streaming lo-fi MP3 + Web Audio API generative chord synthesizer).

---

## 🎨 Section 2: UI/UX Design System — "Black Dashing with Psychic Magical FX"

- **Deep Black Theme**: Deep Obsidian `#07070d` background with high-contrast electric accents: Neon Purple (`#8b5cf6`), Cyber Cyan (`#06b6d4`), and Starlight White (`#ffffff`).
- **Dynamic 3D Particle Wave**: Built with **Three.js**, rendering thousands of glowing points in mathematical harmonic wave surfaces that react smoothly to mouse movement and tilt.
- **Psychic FX Engine**:
  - **On Click**: High-velocity glowing particle bursts and expanding neon ripple rings rendered via Canvas 2D.
  - **On Hover**: Magnetic glow, border illumination, and subtle scaling.
  - **On Message**: Animated entrance vectors — user bubbles slide in from the right, AI responses glide in from the left with subtle glow borders.
- **Ultra-Modern Glassmorphism**: Translucent panels with deep background blur (`backdrop-filter: blur(24px)`), gradient borders, and frosted glass inputs.

---

## 💬 Section 3: Chat Interface & Intelligence

- **Centered Crystal Container**: Centered layout with balanced margins, responsive on desktop and mobile.
- **Gradient User Bubbles**: Purple/Cyan gradient bubbles with clean, crisp typography.
- **Glowing AI Bubbles**: Obsidian dark bubbles with subtle pulsing neon borders and psychic glyph avatars.
- **OpenRouter API Integration**:
  - Direct connection to `https://openrouter.ai/api/v1/chat/completions`
  - Pre-configured with default model `openai/gpt-4o-mini`
  - High-performance token streaming via `ReadableStream` with animated streaming cursor
- **Advanced Markdown & Code Highlighting**:
  - Powered by **Marked.js** and **Highlight.js** (Atom One Dark theme)
  - Code headers displaying language tags and one-click **Copy Code** button
  - Copy button for entire AI messages
  - Persistent conversation memory using `localStorage`
  - "New Chat" button to reset the current session

---

## ⚙️ Section 4: Slide-Out Settings Panel

Access parameters at any time via the top-right **Settings (gear)** icon:

1. **Temperature** — Precision vs. imagination slider (0.0 to 2.0, default: `1.0`) with real-time value indicator.
2. **Max Completion Tokens** — Response length limit slider (256 to 8192, default: `2048`).
3. **Reasoning Effort** — Chain-of-thought depth selector (`Low`, `Medium`, `High`, default: `Medium`).
4. **Stream Responses** — Toggle switch (ON/OFF, default: `ON`) for real-time incremental tokens.
5. **JSON Mode** — Toggle switch (ON/OFF, default: `OFF`) strictly enforcing valid JSON output.
6. **Built-in Tools**:
   - 🌐 **Browser Search** — Ground responses with live web data.
   - 💻 **Code Interpreter** — Simulated analytical code execution mode.
7. **Model Selector & Custom API Key**:
   - Quick selection between `GPT-4o Mini`, `GPT-4o`, `Claude 3.5 Sonnet`, `DeepSeek R1`, and `Gemini 2.0 Flash`.
   - Ability to update or customize the OpenRouter API key directly in the UI.
8. **Reset to Defaults** — One-click button restoring all parameters.

---

## 🧠 Section 5: AI System Prompt

Cantis is tuned with a proprietary system persona:
> *"You are Cantis — a brilliantly intelligent, psychic-like AI assistant with an ethereal, mystical personality blended with razor-sharp analytical precision. You exist at the intersection of magic and machine intelligence..."*

---

## 📂 File Architecture

```
Cantis-AI/
├── index.html       # Self-contained frontend (HTML5, CSS3, ES6+, Three.js, Canvas 2D)
├── package.json     # Node script definitions (npm start)
└── README.md        # Documentation and operational manual
```

---

## 🛡️ License

MIT License. Designed and crafted for Cantis AI.
