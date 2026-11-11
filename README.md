# Hi, I'm Caleb 👋

I build AI-powered web apps and browser games, mostly with JavaScript/TypeScript, Claude and local LLMs. My tools come from my own work in sales: I build what I wished I had on the phones. I also ran social media for a local restaurant for a year.

🌐 [calebzinabu.vercel.app](https://calebzinabu.vercel.app/) · 💼 [LinkedIn](https://www.linkedin.com/in/calebzinabu/) · 📫 czinabu@gmail.com · Wichita, KS · Open to freelance work

---

## AI tools

### [Inroad](https://github.com/czinabu/inroad-outreach) · [Live](https://inroad-outreach.vercel.app/)
Outreach assistant for sales reps. It drafts LinkedIn, email and phone openers, runs a follow-up sequence, and has a live-call objection handler.
- **Stack:** Node.js, TypeScript, Claude API, with LM Studio or Ollama as a free local alternative
- **Bring your own model:** the browser calls the model directly, so the server never receives the user's API key
- **Security:** Content Security Policy, SSRF protection on the website reader, and DNS-rebinding protection when run locally
- **Quality:** API and prompt tests plus typechecking in GitHub Actions on every PR

### [Rolevisor](https://github.com/czinabu/rolevisor) · [Live](https://rolevisor.vercel.app)
Rewrites a resume for a specific job posting. It shows a match score, which skills you have and which are missing, and a list of what changed.
- **Stack:** Next.js, TypeScript, Claude API, Ollama / LM Studio

### Local AI dev tools
Self-hosted apps that run on your own machine, so the code never leaves it.
- [code-documentation-generator](https://github.com/czinabu/code-documentation-generator): writes Markdown docs for Python code (FastAPI, Ollama + Qwen)
- [local-refactor-dashboard](https://github.com/czinabu/local-refactor-dashboard): suggests cleaner, faster versions of code (Python, Ollama + Qwen)

## Games

Built with Three.js and no asset files: every model, sound and song is generated in code.

| Game | Engineering highlights | Play |
| --- | --- | --- |
| [Power Trip](https://github.com/czinabu/power-trip) | Modular source that builds to one HTML file, online co-op over WebRTC with a TURN relay on a Vercel function, motion-capture animation, and a Windows app (Electron) that updates itself from nightly GitHub Actions releases | [Play](https://power-trip.vercel.app) |
| [Neon Trench](https://github.com/czinabu/neon-trench) | 6DOF flight combat with a 22-operation campaign and procedural trenches, plus a Windows desktop build | [Play](https://neon-trench.vercel.app/) |

## Tech

**Languages:** JavaScript · TypeScript · Python · C++ · HTML/CSS
**Frameworks:** Node.js · Next.js · FastAPI · Three.js · Electron
**AI:** Claude API · Claude Code · Ollama · LM Studio · Qwen · Gemma
**Infra:** Vercel · GitHub Actions · Docker · Linux · Tailscale
