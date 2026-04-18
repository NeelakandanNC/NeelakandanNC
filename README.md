### Hi, I'm Neelakandan

ECE undergrad at NIT Agartala · building AI agents that actually ship ·

---

### Recent

🏆 **NSCIF 2026 Finalist** — National-level hackathon by Ashoka University × Connecting Dreams Foundation, 1000+ teams. Pitched **Ydhya / TriageAI** to VCs, clinicians, and founders at EMPI Business School, Delhi.

🥉 **SRCC Derivatives Challenge 2025** — 3rd nationally. Portfolio optimization under live-market pressure.

---

### Projects

**[ZeraPortfolio Advisor](https://github.com/NeelakandanNC/ZeraPortfolio)** — Post-market intelligence for your Zerodha portfolio  
A swarm of 4 Gemini agents (geopolitical · fundamental · risk · synthesis) orchestrated via **Google ADK** and `asyncio.TaskGroup` fan-out. Pulls live holdings from Zerodha Kite, fundamentals from Screener.in, geopolitical signals from a World Monitor sidecar. Produces a Bloomberg-dark daily report, renders HTML → PDF via WeasyPrint, delivers to WhatsApp via Twilio. `FastAPI · React 18 · Neon Postgres · APScheduler`

**[Ydhya / TriageAI](https://github.com/NeelakandanNC/TriageAI)** — Clinical decision support for rural junior doctors  
XGBoost classifier trained on a **real 20,000-row clinical dataset** — not synthetic, not a demo. Google ADK multi-agent backend analyzes vitals + symptoms + co-morbidities, flags complications with clinical rationale, warns at resource thresholds, and routes escalations to the right specialist. Validated and iterated with practicing doctors during the NSCIF finals.

**Compliance RAG** — Regulatory Q&A with clause-level citation  
FastAPI + Pinecone vector store + GPT-4o retrieval, Streamlit frontend, Docker-packaged. Every answer carries the exact clause it came from — built to make hallucinated compliance advice impossible.

**Gemma 2B QLoRA** — Fine-tuning on commodity hardware  
4-bit NF4 quantization with **BitsAndBytes + PEFT** (LoRA rank 8). Runs on a single T4 and on Apple Silicon locally. A study in squeezing useful training out of one GPU.

---

### Stack

<pre>
Languages      Python · JavaScript · TypeScript · C++
AI / Agents    Google ADK · Gemini · MCP · LangChain · Ollama
ML             XGBoost · LightGBM · CatBoost · QLoRA (Gemma 2B) · Scikit-learn
Web            FastAPI · React 18 · Vite · TailwindCSS
Data / Infra   PostgreSQL (Neon) · Pinecone · Docker · APScheduler · Twilio · Zerodha Kite
</pre>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=NeelakandanNC&show_icons=true&hide_border=true&count_private=true&theme=default&hide_title=true" height="120" />
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NeelakandanNC&layout=compact&hide_border=true&theme=default" height="120" />
</p>
