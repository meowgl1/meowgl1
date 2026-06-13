<div align="center">

<!-- PIXEL ART HEADER — host this SVG in your repo as assets/header.svg -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0,0,0,255&height=4&section=header" width="100%"/>

```
 ████████╗██╗  ██╗ ██████╗ ███╗   ███╗ █████╗ ███████╗
    ██╔══╝██║  ██║██╔═══██╗████╗ ████║██╔══██╗██╔════╝
    ██║   ███████║██║   ██║██╔████╔██║███████║███████╗
    ██║   ██╔══██║██║   ██║██║╚██╔╝██║██╔══██║╚════██║
    ██║   ██║  ██║╚██████╔╝██║ ╚═╝ ██║██║  ██║███████║
    ╚═╝   ╚═╝  ╚═╝ ╚═════╝ ╚═╝     ╚═╝╚═╝  ╚═╝╚══════╝
```

**`[ AI Engineer · Full-Stack Developer · Melbourne, AU ]`**

[![Portfolio](https://img.shields.io/badge/▶_mowgli.studio-000000?style=for-the-badge&logoColor=white)](https://mowgli.studio)
[![LinkedIn](https://img.shields.io/badge/▶_LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/thomas-galindo)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0,0,0,255&height=4&section=footer" width="100%"/>

</div>

&nbsp;

## `> whoami`

Hey, nice to meet you 👋🏼

I'm Thomas. I build AI systems that can ship solid structures.

This profile is where I show what I'm currently working on. Not polished marketing, just real projects I'm figuring out as I go. I use multiple AI models for different tasks depending on what makes sense to me. Iit saves time, saves money, and produces better results than locking into one.

I've been building as a full-stack developer for 4 years. At some point I decided to stop and go deeper, back to fundamentals, proper engineering, real computer science. I always believed you can do things better if you understand *why* they work. That's what I'm doing now.

Currently finishing a Bachelor of Software Engineering (AI specialization) at Torrens University Australia.

&nbsp;

## `> ls ./projects`

> **Why Jungle Book names?**
> I'm genuinely bad at naming things. If you're a developer you get it. Ever spent 2 minutes stuck on what to call a variable? The Jungle Book is my solution. Every project in this suite is named after a character. It doesn't mean anything technical. It just means I can keep building instead of getting lost in a naming spiral.

&nbsp;

### 🐺 [**Mowgli CLI**](https://github.com/meowgl1/mowgli-cli) *(in progress)*
**What it does:** A personal CLI that works like Claude CLI or Gemini CLI (but smarter about *which* model does what).

**What problem it solves:** Different AI models are better at different things. Instead of routing everything through one model, Mowgli CLI lets you build entire pipelines where each task goes to the model best suited for it. The result: the same request, fragmented across multiple models, now costs 30% fewer tokens than running it end-to-end on a single model — down from burning ~20% of a Claude Pro plan on a single run.

**In progress:** swarm coordination · complexity-based request routing · workflow monitoring · output evaluation · multi-model cost tracking · AI slop detection 

Connected to `.studio` for shared context and memory across all projects.

`Python · Claude SDK · Multi-model routing · Swarm · Loop engineering`

---

### 🗂️ [**.studio**](https://github.com/meowgl1/studio)
**What it does:** A context and memory management layer for AI coding agents.

**What problem it solves:** Every AI tool speaks a slightly different language and forgets everything between sessions. `.studio` acts as the shared brain across all your projects. It manages context, memory, logs, skills, agents, and rules in a structured way that any model can read. An embedded AgenticOS layer lets you review and update agents, skills, and workflows from one place. Each project gets its own local layer on top of shared global conventions, so the AI always knows where it is and what the rules are.

`Python · Claude Code · AgenticOS · Context engineering · Markdown`

---

### 🐍 [**Kaa**](https://github.com/meowgl1/analyst-system)
**What it does:** A multi-agent system that analyses your computer | security, performance, OS state

**What problem it solves:** I once downloaded a bunch of GitHub packages without checking what was inside. My computer started shutting down randomly. I spent days troubleshooting. So I built Kaa: 11 AI agents and 700+ skills, each responsible for a different part of your system, producing structured reports that tell you exactly what's wrong.

Found the problem in a few hours. Now I use it as a testing ground for infrastructure and API validation.

`Python · Claude SDK · Dashboard`

---

### 🐺 [**Akela**](https://github.com/meowgl1/akela)
**What it does:** A local knowledge base you can have a conversation with.

**What problem it solves:** I had documentation, notes, PDFs, and articles spread across dozens of projects. Finding anything was slow. Akela lets you feed it all your documents and then *ask questions in plain language*. It finds the answer and tells you exactly which source it came from. Runs 100% locally on your machine using Ollama (Qwen 2.5), so it costs nothing to query.

Built it as a research project to understand the real tradeoffs of local-first RAG: what works, what doesn't, and what breaks at scale. 
(I'm also thinking to connect this project to Mowgli CLI for complexity detection and orchestration)

`Python · TypeScript · Ollama · Qwen 2.5 · Graph RAG`

---

### 🌿 **Jungle**
**What it does:** An AI lead scraper that runs on your own hardware.

**What problem it solves:** Most lead scraping tools either cost a lot per API call or produce messy, unstructured data. Jungle downloads raw HTML, feeds it to a local LLM, and returns clean, structured lead data. Zero API cost.

Connected to `Baloo` for shared context and memory across all projects.

`Python · Ollama · Docker`

---

### 🐻 [**Baloo**](https://github.com/meowgl1/baloo)
**What it does:** An autonomous research and publishing agent.

**What problem it solves:** Keeping up with research across multiple topics is time-consuming. Baloo does it for you: it searches Google Scholar, evaluates and deduplicates sources, builds a content roadmap, and writes structured articles or course modules automatically. Available in EN / IT / ES for anyone curious about the same topics I am.

`Claude SDK · Next.js · Supabase`

&nbsp;

## `> ls ./shipped`

Things I've built and sent into the world:

| | |
|---|---|
| **[rhytm.store](https://rhytm.store)** | Shopify store I own. I use it as a live lab for CRO, funnel testing, and AI-assisted e-commerce ops. Real traffic, real data. |
| **[basefundamentals.store](https://basefundamentals.store)** | Second Shopify store. It's a martial arts sportswear. Same idea: test automation and e-commerce systems on a real business, not a sandbox. |
| **E-commerce builds** | Co-founder. 2 years building e-commerce platforms: PrestaShop, Shopify, custom PHP, Cloud, Serverless, Vue.js. From zero to live.  [Cartalytic agency](https://cartalytic.com).|
| **20+ freelance projects** | 4 years building web platforms: WordPress, Vue.js, PHP, Cloud, Serverless. For clients in retail, wellness, B2B, and hospitality through [6chic agency](https://6chic.net). |

&nbsp;

## `> cat stack.txt`

```
AI ········· Claude SDK/API · Ollama · Multi-agent systems · RAG
            Agentic pipelines · Context engineering · Loop engineering
Backend ···· Python · TypeScript · Node.js · Docker · SQL · PHP · Cloud AWS
Frontend ··· Next.js · Tailwind CSS · Shopify Liquid
E-commerce · Shopify · PrestaShop · CRO · Funnel optimization · SEO & AEO
```

&nbsp;

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0,0,0,255&height=4" width="100%"/>

`// always building · always learning`

</div>
