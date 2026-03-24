# Antoine Naccache

AI/ML Engineer based in San Francisco. I build agentic AI systems, LLM-powered applications, and the occasional hackathon winner.

Currently at **AXA Investment Managers** — building internal AI platforms (compliance tools, code intelligence, GPU infra) for regulated financial environments.

---

## Featured Projects

### Temporal Drift — 1st Place, Arcade AI GameJam (March 2025)
> A browser-based first-person game where AI generates every room around you and every NPC is a living chatbot with a secret to share.

You wake up. Something feels off. Through AI-generated worlds and conversations, you uncover you're a time traveler — and your mission is to prevent the assassination of King Henri IV of France in 1610.

- **Three.js** for real-time 3D rendering (no bundler, pure ES modules)
- **Claude API** for world generation (structured JSON room definitions) and per-NPC persistent conversations
- **Tripo3D** for text-to-3D model generation with animated idle variants
- Rooms are built in a staging scene during hallway transitions, then swapped in on arrival

[View repo](https://github.com/AntoineNaccache/WorldOfAI)

---

### Cats Image Generator — Full-Stack AI Web App
> Browse and generate AI-painted cat portraits in the style of Renaissance masters.

A production web app with Google OAuth, role-based access, and an AI generation pipeline that queries the Met Museum API for real paintings and uses Mistral AI to reimagine your cat in that style.

- **NestJS** backend deployed serverless on Vercel, **Supabase** for auth (JWKS/ES256), storage, and PostgreSQL
- **React 19 + Vite** frontend with Google OAuth via Supabase Auth
- Admin-only generation endpoint, rate limiting, Row Level Security
- Live: [cats-image-generator-ui.vercel.app](https://cats-image-generator-ui.vercel.app)

---

## Background

- **CentraleSupélec** (Université Paris-Saclay) — MSc Applied Mathematics & Computer Science, Data Science. Ranked #2 engineering school in France.
- Past work: distributed LLM training (Mistral 7B, DeepSpeed, 4 GPUs) at Headmind Partners; GNN-based money laundering detection (F1: 0.80) at Banque de France; NLP systems at ENGIE and Unifai.
- Active in the SF AI scene: HackNight @GitHub, Google Agentic AI Workshop, WorkOS MCP Nights.

---

Antoine.Naccache@laposte.net
