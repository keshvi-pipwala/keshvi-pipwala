<!-- HEADER BANNER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:1b3a4b,100:6E56CF&height=210&section=header&text=Keshvi%20Pipwala&fontSize=58&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=AI%20Product%20Manager%20%C2%B7%20Forward-Deployed%20AI%20Builder&descAlignY=60&descSize=20&descAlignX=50" alt="Keshvi Pipwala" />

<!-- TYPING ANIMATION -->
<p align="center">
  <a href="https://keshvi-portfolio-ten.vercel.app/">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6E56CF&center=true&vCenter=true&width=650&lines=Six+AI+builds+shipped+%C2%B7+all+with+live+demos;100%25+precision+on+auto-posts+(Close+Copilot);0%E2%86%925%2C000+users+%C2%B7+ASU+AI+platform;NASA+L'SPACE+data+pipelines+%C2%B7+95%25+accuracy;Open+to+AI+PM+%C2%B7+TPM+%C2%B7+Forward-Deployed+AI" alt="Typing SVG" />
  </a>
</p>

<!-- OPEN TO WORK -->
<p align="center">
  <img src="https://img.shields.io/badge/Open%20to%20Work-AI%20PM%20%C2%B7%20Technical%20PM%20%C2%B7%20Forward--Deployed%20AI-6E56CF?style=for-the-badge&logo=github&logoColor=black&labelColor=0f2027" alt="Open to work" />
</p>

<!-- COUNTERS -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=keshvi-pipwala&label=Profile%20views&color=6E56CF&style=flat-square" alt="Profile views" />
  <img src="https://img.shields.io/github/followers/keshvi-pipwala?label=Followers&style=flat-square&color=6E56CF&labelColor=0f2027" alt="Followers" />
  <img src="https://img.shields.io/github/stars/keshvi-pipwala?label=Stars&style=flat-square&color=6E56CF&labelColor=0f2027" alt="Stars" />
</p>

---

## 👩‍💻 Who I Am

```ts
const keshvi = {
  title: "AI / Data Product Manager · Forward-Deployed AI Builder",
  location: "Tempe, AZ",
  stack: {
    languages: ["Python", "TypeScript", "SQL", "Bash"],
    ai: ["LLM product specs", "agent evals", "RAG", "confidence routing", "Claude/Gemini APIs", "LiteLLM", "ChromaDB"],
    data: ["ETL + validation", "PostgreSQL", "SQLite FTS5", "Pandas", "Tableau/Power BI"],
    infra: ["FastAPI", "Celery", "Redis", "Docker Compose", "GitHub Actions", "Prometheus/Grafana", "Vercel/Render"],
  },
  shipped: ["Close Copilot", "SubmissionClear", "InsightIQ", "GitSense", "ResilienceOS", "Resilient LLM Gateway"],  // all six have live demos
  howIBuild: "spec, tradeoffs, eval set and QA are mine; implementation is AI-assisted — and I say so",
  certifications: ["Anthropic AI Fluency", "Anthropic Claude 101", "AWS Academy: Data Engineering", "AWS Academy: ML Foundations"],
  recently: "AI/Data PM @ ASU (0→5,000+ users, +18% retention) · Software Engineer @ NASA L'SPACE (95% anomaly-detection accuracy)",
  status: "Available now",
  openToFields: ["AI Product Management", "Technical Program/Project Management", "Forward-Deployed / Applied AI"],
};
```

---

## 🚀 Featured Projects

### 🧾 Close Copilot — auto-post what the agent is sure about; route the rest to a human

<a href="https://github.com/keshvi-pipwala/close-copilot">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=keshvi-pipwala&repo=close-copilot&theme=nord&title_color=6E56CF&icon_color=6E56CF&border_color=6E56CF&hide_border=false" alt="Close Copilot" />
</a>

An agent categorizes every transaction in a close and scores its own confidence; rows ≥ 0.85 post automatically, the rest go to a human review queue with the agent's reasoning. Designed the trust model and the eval: **100% precision on auto-posts, 96.2% overall accuracy on a 104-row labeled set** — reproducible with `npm run eval`.

| Layer | Technology |
|---|---|
| Product | Confidence routing · Human-in-the-loop · Eval design |
| App | Next.js · TypeScript · Tailwind |
| AI | On-device rules+confidence agent · optional Claude route with fail-safe fallback |

**🔗 [Live Demo](https://close-copilot.vercel.app) · [Code](https://github.com/keshvi-pipwala/close-copilot)**

<br/>

### 📨 SubmissionClear — an AI teammate for insurance intake, built for FurtherAI

<a href="https://github.com/keshvi-pipwala/submissionclear">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=keshvi-pipwala&repo=submissionclear&theme=nord&title_color=6E56CF&icon_color=6E56CF&border_color=6E56CF&hide_border=false" alt="SubmissionClear" />
</a>

Built for a forward-deployed engineer application: broker email in → classify attachments → extract fields with per-field confidence → cross-document validation → FMCSA / FEMA flood-zone / fire-class enrichment → eligibility → underwriter triage. Anything under 90% confidence routes to a human. Includes the "how this maps to what FurtherAI already does" section — the point of a forward-deployed artifact.

**🔗 [Live](https://keshvi-pipwala.github.io/submissionclear/) · [Code](https://github.com/keshvi-pipwala/submissionclear)**

<br/>

### 🔀 Resilient LLM Gateway — one interface, ordered fallbacks, tracked spend

<a href="https://github.com/keshvi-pipwala/litellm-resilient-gateway">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=keshvi-pipwala&repo=litellm-resilient-gateway&theme=nord&title_color=6E56CF&icon_color=6E56CF&border_color=6E56CF&hide_border=false" alt="Resilient LLM Gateway" />
</a>

The generalized fix for the rate-limit problem that hit GitSense: a LiteLLM router with a strict primary → fallback chain, retries + cooldown, per-request spend tracking and a budget guard. Runs offline in mock mode with zero API keys; 6 tests cover failover, spend and budget.

**🔗 [Live Demo](https://keshvi-pipwala.github.io/litellm-resilient-gateway/) · [Code](https://github.com/keshvi-pipwala/litellm-resilient-gateway)**

<br/>

### 🤖 GitSense — a 24/7 PR-review agent that never misses a breaking change

<a href="https://github.com/keshvi-pipwala/gitsense">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=keshvi-pipwala&repo=gitsense&theme=nord&title_color=6E56CF&icon_color=6E56CF&border_color=6E56CF&hide_border=false" alt="GitSense" />
</a>

Defined the product, risk-scoring logic, and evals for a PR-review agent, then directed an AI-assisted build — and owned the call to move from the Claude API to Gemini when rate limits threatened reliability.

| Layer | Technology |
|---|---|
| Agent | Claude / Gemini APIs · Agent Evals |
| Backend | Python · FastAPI |
| Product | Product Spec · Risk Scoring · Slack Alerts |

**🔗 [Live Demo](https://keshvi-pipwala.github.io/gitsense/) · [Code](https://github.com/keshvi-pipwala/gitsense)**

<br/>

### 📊 InsightIQ — upload a CSV, ask in plain English, get an answer and a chart

<a href="https://github.com/keshvi-pipwala/insightiq">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=keshvi-pipwala&repo=insightiq&theme=nord&title_color=6E56CF&icon_color=6E56CF&border_color=6E56CF&hide_border=false" alt="InsightIQ" />
</a>

Scoped the product around one promise — every answer grounded in the uploaded data — then redirected the build to SQLite FTS5 retrieval when Render's memory limits ruled out sentence-transformer embeddings.

| Layer | Technology |
|---|---|
| AI | RAG · Gemini API |
| Retrieval | SQLite FTS5 |
| Frontend | React |
| Deploy | Render |

**🔗 [Live Demo](https://insightiq-frontend-jn6h.onrender.com/) · [Code](https://github.com/keshvi-pipwala/insightiq)**

<br/>

### 🧨 ResilienceOS — find out how a distributed system breaks before users do

<a href="https://github.com/keshvi-pipwala/resilienceos">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=keshvi-pipwala&repo=resilienceos&theme=nord&title_color=6E56CF&icon_color=6E56CF&border_color=6E56CF&hide_border=false" alt="ResilienceOS" />
</a>

A chaos-engineering sandbox — scoped the experiment surface (latency, failures) and the evals that prove a system recovers, and directed the AI-assisted implementation.

| Layer | Technology |
|---|---|
| Core | Python |
| Systems | Chaos Engineering · Fault Injection |
| Infra | Distributed Systems |

**🔗 [Live Demo](https://keshvi-pipwala.github.io/resilienceos/) · [Code](https://github.com/keshvi-pipwala/resilienceos)**

---

## 🧰 Tech Stack

**Languages & Core**

<img src="https://skillicons.dev/icons?i=py,ts,js,bash" alt="languages" />

**AI / LLM Systems** — LLM product specs · agent evals · RAG · confidence routing · Claude & Gemini APIs · LiteLLM · ChromaDB

**Data & Backend** — ETL + validation · PostgreSQL · SQLite FTS5 · Celery · Redis · Pandas

<img src="https://skillicons.dev/icons?i=fastapi,postgres,sqlite,kafka,redis" alt="data-backend" />

**Cloud, DevOps & Tools**

<img src="https://skillicons.dev/icons?i=aws,docker,githubactions,vercel,prometheus,grafana,git,github" alt="cloud-devops" />

---

## 📈 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=keshvi-pipwala&show_icons=true&count_private=true&theme=nord&title_color=6E56CF&icon_color=6E56CF&text_color=c9d1d9&border_color=6E56CF" alt="stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=keshvi-pipwala&layout=compact&theme=nord&title_color=6E56CF&text_color=c9d1d9&border_color=6E56CF" alt="top langs" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=keshvi-pipwala&theme=nord&ring=6E56CF&fire=6E56CF&currStreakLabel=6E56CF&sideLabels=6E56CF&border=6E56CF" alt="streak" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=keshvi-pipwala&theme=nord&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" alt="trophies" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=keshvi-pipwala&theme=nord&hide_border=true&bg_color=00000000&color=6E56CF&line=6E56CF&point=ffffff&area=true" alt="activity graph" />
</p>

---

## 🌐 Connect

<p align="center">
  <a href="https://www.linkedin.com/in/keshvi-pipwala-5a7bb0247/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:keshvipipwalan@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://keshvi-portfolio-ten.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-6E56CF?style=for-the-badge&logo=vercel&logoColor=black" alt="Portfolio" /></a>
  <a href="https://github.com/keshvi-pipwala"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

<!-- FOOTER BANNER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:6E56CF,100:0f2027&height=120&section=footer" alt="footer" />
