<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Hi,%20I'm%20Luiz%20👋&fontSize=42&fontColor=ffffff&animation=fadeIn)

[![Portfolio](https://img.shields.io/badge/Portfolio-luizblum.com-7C3AED?style=for-the-badge&logo=google-chrome&logoColor=white)](https://luizblum.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-luizcauet-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/luizcauet)
[![Resume](https://img.shields.io/badge/Resume-PDF-16A34A?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://luizblum.com/assets/Luiz%20Cauet%20Castilla%20Ruy%20Blum%20Resume%202027.pdf)

</div>

### 👋 About

**ML Systems · Backend Engineering**

Computer Engineering (Systems Programming) + CS minor at UC Santa Cruz, graduating March 2027.

I build machine learning pipelines, backend services, and software that connects the two. My projects span audio retrieval (Resonance), model training and evaluation (The Audition), adaptive queueing with persistent state (SmartQueue), and a deployed music community app (Slug Collective).

**Seeking full-time ML systems and backend engineering roles starting March 2027.** Authorized to work in the US, EU, and Brazil, no sponsorship needed.

<div align="center">
  
[![My Skills](https://skillicons.dev/icons?i=py,ts,cpp,java,pytorch,fastapi,docker,supabase,postgres,aws,linux,git,godot&perline=13)](https://skillicons.dev)

</div>

## Projects

### 🎛️ Resonance — Text-to-Synth Preset Generator

AI-powered discovery for Vital synthesizer presets. Describe a sound in plain English and Resonance retrieves matching presets, lets you preview them, and conversationally refines them. Retrieval uses LAION-CLAP embeddings + cosine-similarity search over presets (pgvector); refinement is an LLM-driven JSON parameter patch against Vital's real parameters. Built with a team over four Agile sprints for CSE 115A (originally prototyped as SynthGPT). Stack: Next.js, FastAPI, PostgreSQL/pgvector, Docker Compose. Live demo is currently paused — the repo has full setup to run it locally.

[→ Source](https://github.com/andrewweckwerth/Resonance) · [→ Project page](https://luizblum.com/#project/resonance)

### 🎸 The Audition — AI-Driven Guitar Performance Game

Lead AI & Software Engineer on a 13-person team building a musical 3D psych-horror game. I built a PyTorch model to score guitar-solo sequences, along with a comparison website and sequence database to collect human preferences. Predicted scores achieved Spearman rank correlation of 0.848 against human-derived Elo scores. I also build gameplay systems and AI in Godot.

[→ See it on my site](https://luizblum.com/#project/audition)

### 🎶 Slug Collective — Music Community & Event Groups

A deployed community app I built for the UCSC music collective I founded. Members discover people through shared artists and genres, find creative collaborators, and start private conversations. For production sessions, attendees scan a QR code and join with saved taste; admins configure group size, review and adjust assignments, then publish groups. Results show your own group first, with an option to browse the others.

Built with JavaScript, Cloudflare Workers, D1/SQLite, and Discord OAuth. Music imports are parsed on-device; the recommendation and grouping systems use explicit scoring rules rather than a trained ML model. Validation includes 118 automated tests and local browser checks with fictional members.

[→ Source](https://github.com/LuizCauet/slug-collective) · [→ Project page](https://luizblum.com/#project/slugcollective) · [→ Live beta (club sign-in required)](https://beta.slugcollective.workers.dev/)

### 🎵 SmartQueue — Adaptive Spotify Queue

Spotify's queue, rebuilt. Artists are ranked in tiers (1–10, starting at 5); skips (early −2, late −0.5) and full plays (+1) adjust tiers, and every 3 songs the remaining queue is resampled with probability proportional to tier — so you hear more of what you want without leaving your playlist. The next few tracks stay locked so the player UI stays predictable. Supabase Auth + PostgreSQL + RLS for persistent state; Spotify Web Playback SDK.

[→ Repo](https://github.com/LuizCauet/smart-queue)

### 🏆 Collab — Music Collaboration Forum

1st place hackathon winner. Full-stack platform for musicians to find collaborators — auth, media uploads, real-time interaction, AWS S3 audio storage.

[→ Repo](https://github.com/LuizCauet/Collab)

### 🧩 Procedural Generation Research — Augmented Design Lab

Past research (Jan–Mar 2026) with Dr. Jim Whitehead: LLM + procedural content generation, Wave Function Collapse, Z3 constraint solving, grid-based world generation.

[→ Wave Function Collapse](https://github.com/LuizCauet/Wave-Function-Collapse) · [Demo](https://github.com/LuizCauet/Wave-Function-Collapse-Demo) · [Z3 Solver](https://github.com/LuizCauet/Z3-Constraint-Solver)

---

### 🛠️ More projects

- [StockMentions](https://github.com/LuizCauet/StockMentions) — Finds the most mentioned stocks on Reddit.
- [Panda3D-Traffic-Simulation](https://github.com/LuizCauet/Panda3D-Traffic-Simulation) — Traffic simulation built with Panda3D.
- [Swole](https://github.com/LuizCauet/Swole) — Simple daily macro tracking.

### 💼 Experience

- **The Audition** — Lead AI & Software Engineer (Sep 2025 – now). PyTorch guitar-solo scoring model, human-preference data collection, and model evaluation (Spearman ρ = 0.848); gameplay systems + AI in Godot; leading a 13-person team.
- **Integem** — AI & Robotics Instructor (Jun–Jul 2026). Guided students through the full YOLOv5 pipeline (dataset → annotation → training → tuning); taught CV + NVIDIA GenAI curriculum.
- **Augmented Design Lab** — Research Participant (Jan–Mar 2026). PCG prototypes with LLMs, Wave Function Collapse, Z3; grid-based world generation + constraint pipelines.
- **The Slug Collective** — Founder & President (Dec 2024 – now). 100+ members, $1,500 funding, 12-track release.

<div align="center">

![footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer)

</div>
