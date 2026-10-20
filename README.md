# Hi, I'm Francisco Salgado (FranGuh) 👋

**Full-Stack Developer · Local AI Engineer**
Morelos, México · Open to remote roles · Spanish (native) / English (advanced)

I build web apps (React, Node.js, PostgreSQL, AWS) and desktop apps (Tauri, Rust) that run AI models on the user's own hardware: no cloud, no subscription, private by default.

---

### ⚡ Highlights

- **Python → Rust migration (LiveAudio):** moved audio capture, voice activity detection, WebSocket broadcasting and process supervision to a native Rust workspace. Idle memory went from **~959 MB to ~73 MB** and cold start from **~2.8 s to ~17 ms**. [See benchmarks →](https://github.com/plynte-labs/LiveAudio#performance--migration-benchmarks-rust-core-v150-vs-python-v127)
- **Real-time local speech recognition:** Faster-Whisper `small` running at **~25× real-time on an RTX 3060**, streamed as live subtitles into OBS.
- **Production full-stack work (RaukeIT, 2025):** image-sharing platform and product catalog with Stripe payments, JWT auth, AWS S3 uploads, PostgreSQL and MongoDB.

---

### 🛠️ Featured projects

| Project | Stack | What it does |
| --- | --- | --- |
| **[LiveAudio](https://github.com/plynte-labs/LiveAudio)** | `Rust` `Tauri 2` `Faster-Whisper` `ONNX` `WebSocket` | Real-time local subtitles for streamers. Rust core + supervised Python ASR worker, OBS overlay, Windows/Linux. |
| **[OpenCohost](https://github.com/plynte-labs/OpenCohost)** | `Tauri 2` `Rust` `React` `Python` `Ollama` | Local AI co-host for streamers: sees the screen (vision model), listens (STT), talks back (TTS) and remembers conversations. Viewer chat never leaves the machine. |
| **[Brick.draw](https://github.com/plynte-labs/brick-draw)** | `Tauri` `React` `TypeScript` `Rust` | Lightweight layered drawing app with optional local Stable Diffusion XL enhancement. |
| **[EngramView](https://github.com/FranGuh/EngramView)** | `Tauri` `React` `TypeScript` | Read-only desktop viewer for local Engram memory stores. |
| **Floppy** *(private)* | `Python` `CUDA` `DBSCAN` `SQLite` | GPU computer-vision pipeline for unsupervised face clustering at scale, with explicit VRAM management. |

---

### 💻 Tech I've shipped with

```
Web        : React, TypeScript, Next.js, Svelte, Tailwind
Backend    : Node.js, Express, Python, PostgreSQL, MongoDB, SQLite, Stripe, JWT
Desktop    : Tauri 2, Rust (Tokio, CPAL, ONNX Runtime)
Local AI   : Faster-Whisper, Silero VAD, Ollama, Qwen-VL, Qwen Image 2.1, PiperTTS, convaiinnovations/laya, CUDA
Infra      : AWS (EC2, S3), Cloudflare, Vercel, Linux, Git
```

---

### 📬 Contact

- 🌐 [plynte.com](https://plynte.com) · [franguh.plynte.com](https://franguh.plynte.com)
- 💼 gitrafuh@gmail.com
- 💖 [Sponsor my open-source work](https://github.com/sponsors/FranGuh)
