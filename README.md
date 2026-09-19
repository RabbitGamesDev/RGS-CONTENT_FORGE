## ⚡ RGS Content Forge — Multimodal Edition

> A lightweight, zero-backend multimodal prompt engine designed for indie hackers and developers. Transform screenshots, code snippets, or video demos into tailored social media content while preserving an authentic devlog voice.

![HTML5](https://img.shields.io/badge/Stack-HTML%20%2F%20Tailwind%20%2F%20JS-black?style=flat-square)
![Architecture](https://img.shields.io/badge/Architecture-Zero--Backend-emerald?style=flat-square)
![Deploy](https://img.shields.io/badge/Deploy-GitHub%20Pages-blue?style=flat-square)

---

## 🚀 Features

* **Multi-Format Processing:** Handles images, screenshots, and large video files (via automatic Google Files API chunking).
* **Targeted Outputs:** Generates ready-to-post content for **Instagram**, **YouTube Shorts**, **X/Twitter Threads**, **LinkedIn**, and **Markdown Devlogs**.
* **Live In-Card Refinement:** Tweak output for a single platform on the fly without re-processing all cards or burning extra tokens.
* **Dev-Native Utility:** Built-in character counters, auto-hashtag injection, and 1-click Markdown export.
* **100% Client-Side & Mobile Responsive:** Runs directly in your browser. Your \`GEMINI_API_KEY\` stays local in \`localStorage\`.

---

## 🛠️ Quick Start

1. **Clone the repository:**
   \`\`\`bash
   git clone https://github.com/YOUR_USERNAME/rgs-content-forge.git
   cd rgs-content-forge
   \`\`\`

2. **Run locally:**
   Simply open \`index.html\` in any web browser or launch it using VS Code Live Server.

3. **Get an API Key:**
   Get your free Gemini API key at [Google AI Studio](https://aistudio.google.com/).

---

## 🌐 Deploy to GitHub Pages

Since this project has **zero backend dependencies**, deploying takes less than a minute:

1. Push this repository to GitHub.
2. Go to **Settings** > **Pages**.
3. Under **Build and deployment**, set the Branch to \`main\` (or \`master\`) and folder to \`/ (root)\`.
4. Click **Save**. Your web app will be live at \`https://YOUR_USERNAME.github.io/rgs-content-forge/\`!

---

## 🔒 Privacy & Security

* **Zero Data Collection:** No databases, external servers, or tracking scripts.
* **Local Storage:** Your API Key is stored exclusively in your browser's \`localStorage\`.
* **Direct Communication:** Requests are sent directly from your client browser to Google Gemini API endpoints.

---

## 📄 License

Distributed under the MIT License. Built with ⚡ by **RGS Labs**.
`
