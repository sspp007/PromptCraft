# PromptCraft // Studio & Style Manager for Generative AI

**PromptCraft** is a lightweight, responsive, single-page web application designed for prompt engineering. It allows developers and designers to compose, customize, and optimize text prompt strings for generative AI engines (like Midjourney, DALL-E, and Stable Diffusion) using a strict, high-fidelity **Neo-Brutalist** aesthetic.

---

## 🛠️ Key Features

- **Subject & Action Input**: A dedicated workspace text area with real-time character counting.
- **Interactive Style Modifiers**: Clickable, mechanical style pills (e.g., Anime, Photorealistic, Cyberpunk, 3D Render) that toggle active states and inject style keywords dynamically.
- **Advanced Presets**: Dropdowns for selecting camera lens models (e.g., Sony A1 85mm, Canon 24mm) and geometry preservation rules.
- **One-Click Compilation**: Combines inputs, strips redundant spaces, filters out unused presets, and appends professional quality keywords (`masterpiece, highly detailed, cinematic lighting, 8k resolution`).
- **Live Generated Output**: Real-time display panel with automatic word/character stats.
- **Instant Copy to Clipboard**: Copies the generated text with a custom 2-second visual confirmation animation (success indicator changes the button background to lime green).
- **Extensible Architecture**: Structured modular layouts containing a developer panel and placeholders for planned tools like *Global Pulse Dashboard*, *Chronos Timeline Explorer*, and *Aspect Ratio Tool*.

---

## 🎨 Design System (Neo-Brutalism)

The application adheres to a strict Neo-Brutalist design paradigm:
- **Font**: Google Fonts' **Space Grotesk** for clean, industrial-grade sans-serif legibility.
- **Color Palette**:
  - Background: Muted Cream (`#f3ead3`)
  - Primary Action / Highlights: Vibrant Orange (`#ff9c3a`)
  - Success Indicator / Badge: Lime Green (`#a3e635`)
  - Card Backing: Stark White (`#ffffff`)
- **Borders & Shadows**: Strict black borders (`border-4 border-black`) paired with hard-edged, solid drop shadows (`box-shadow: 6px 6px 0px 0px rgba(0,0,0,1)`).
- **Physical Animations**: Hovering translates elements up and left slightly while click/active states translate them down and right (`6px`), mimicking mechanical compression.

---

## 💻 Tech Stack

- **Markup**: Semantic HTML5
- **Styling**: Tailwind CSS (loaded via CDN) & custom utility styles
- **Logic**: Vanilla ES6 JavaScript (No frameworks, bundlers, or external CSS dependencies)

---

## 🚀 How to Run

Because PromptCraft is self-contained in a single page, you can open and run it locally without installing complex build pipelines.

### Option A: Direct Local Execution
Simply open [index.html](file:///c:/Users/USER/Desktop/PromptCraft/index.html) in any modern web browser.

### Option B: Local Development Server
If you prefer running a local loopback server, navigate to the folder using your terminal and spin up a lightweight server:

**Using Python:**
```bash
python -m http.server 8000
```
Open your browser to `http://localhost:8000`.

**Using Node.js:**
```bash
npx serve
# or
npx http-server
```

---

## 📂 Project Structure

```text
PromptCraft/
├── index.html     # Unified app core, styling system, components, & logic
└── README.md      # Project documentation
```

---

## 👤 Developer
Built with ⚡ by **Shahid** (Full-Stack Web & Systems Developer).
