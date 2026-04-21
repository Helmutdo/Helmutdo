![Helmut Schweitzer Banner](https://media.licdn.com/dms/image/v2/D4E16AQG8C0oW3LY65g/profile-displaybackgroundimage-shrink_350_1400/B4EZVkS87vHgAc-/0/1741144445464?e=1775088000&v=beta&t=BAp9Q905ck7WLLQgnqzfM4rIztnvhgyyo0_cRxRIfSo)
# Helmut Schweitzer

```python
profile = {
    "role":     "Python Backend Developer",
    "focus":    ["LLM integration", "API automation", "backend systems"],
    "stack":    ["FastAPI", "PostgreSQL", "Docker", "Next.js 14", "TypeScript"],
    "ai":       ["Claude", "GPT-4o", "Gemini", "LangChain"],
    "env":      "Arch Linux / Hyprland",
    "status":   "open to remote"
}
```

---

## Projects in production

### [AI-coach](https://github.com/Helmutdo/AI-coach) 
Full-stack endurance analytics platform. Pulls training data from **Strava OAuth**, normalizes heterogeneous metrics (HRV, sleep, body battery, power, pace, CTL/ATL/TSB) into a unified schema, and exposes a multi-model AI coach that runs **Claude + GPT-4o + Gemini** in parallel.

```
FastAPI · Next.js 14 · TypeScript · PostgreSQL · Docker
Fernet encryption for OAuth tokens · rate limiting via slowapi
Google OAuth (NextAuth v5) · deployed on Vercel + Railway
```

---

### Agentic SRE System · AgentX Hackathon — 48h build
Autonomous incident response agent. Ingests multimodal reports (text + logs + images), triages with LLMs, scores severity, creates tickets, routes engineer notifications — zero human in the loop for initial classification.

```
FastAPI · Next.js · PostgreSQL · Docker Compose
LLM orchestration · Langfuse observability · prompt injection safeguards
```

---

### Multi-agent Fraud Detection · Reply AI Challenge — 6h build
End-to-end fraud pipeline across heterogeneous financial datasets. Three specialized agents running in parallel:

```
GPS Impossibility Agent   →  haversine distance cross-referencing
Behavioral Analysis Agent →  per-user transaction pattern modeling
NLP Phishing Agent        →  SMS/email social engineering detection

LangChain · OpenRouter (GPT-4o-mini) · Langfuse tracing
```

---

### [Mini SOC](https://github.com/Helmutdo/mini-soc-helmut)
SSH brute-force detection from Linux auth logs. FastAPI backend · SQLite · real-time dashboard · IP geolocation.

---

## Stack

| Layer | Technologies |
|---|---|
| Backend | Python · FastAPI · SQLAlchemy · Pydantic |
| Database | PostgreSQL · SQLite |
| AI/LLM | Anthropic Claude · OpenAI · Gemini · LangChain · OpenRouter |
| Frontend | Next.js 14 · TypeScript · TailwindCSS |
| Infra | Docker · AWS · Railway · Vercel |
| Integrations | Strava OAuth · Garmin Connect · Google OAuth |
| Environment | Arch Linux · Hyprland · Git |

---

## Contact

[linkedin.com/in/helmut-schweitzerg](https://www.linkedin.com/in/helmut-schweitzerg) · helmut.schweitzerg@gmail.com · open to remote
