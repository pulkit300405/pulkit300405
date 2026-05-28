<h1 align="center">Hi 👋, I'm Pulkit Singh</h1>
<h3 align="center">
Polymath Engineer &nbsp;|&nbsp; Competitive Programming &nbsp;|&nbsp; Quant Finance &nbsp;|&nbsp; VLSI &nbsp;|&nbsp; Multi-Agent AI
</h3>
<p align="center">
  Building systems across ML, hardware, finance, and autonomous agents.<br/>
  <a href="https://github.com/pulkit300405">
    <img src="https://img.shields.io/badge/GitHub-Profile-black?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

## 👨‍💻 About Me

🎓 2nd-Year B.Tech – Electronics & Communication Engineering (KIET Deemed to be University)  
🏆 3rd Place – Agentic AI Hackathon @ MAIT (1,100+ registrations)  
🥈 Rank 53 – Partcl × HRT Macro Placement Challenge (1.5286 avg HPWL, 17 IBM benchmarks)  
📊 IMC Prosperity 4 – Finals ranked #660 overall, #64 manual, #22 country (4.65L XIRECX)  

- Building **multi-agent AI systems** (ReAct framework, LLaMA-3.3-70B, Groq inference)
- **Quant trading algos** (Black-Scholes, market making, premium selling strategies, pure-Python implementations)
- **Hardware & placement optimization** (simulated annealing, edge extraction, parallel restarts)
- **Competitive programming** — solving across DSA, system design, and optimization problems
- **Full-stack development** — Node.js/Express, React, FastAPI, Docker, Kubernetes

📧 pulkit300405@gmail.com | 🔗 [LinkedIn](https://linkedin.com/in/pulkit-singh-2nd-year-ece)

---

## 🛠 Technical Skills

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Groq%20LLMs-FF6B6B?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/ReAct%20Framework-9333EA?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/VLSI%20Design-6F42C1?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/Quant%20Finance-4CAF50?style=for-the-badge&logoColor=white"/>
</p>

---

## 🚀 Featured Projects

---

### 🤝 [Multi-Agent Negotiation System](https://github.com/pulkit300405/MULTI-AGENTS-NEGOTIATION)
> **3rd Place – Agentic AI Hackathon @ MAIT | ReAct framework with autonomous buyer/seller/mediator agents**

- Built 3 autonomous LLM agents (Buyer, Seller, Mediator) negotiating deals in real-time using **ReAct (Reasoning + Acting)** framework
- Integrated **Groq LLaMA-3.3-70B** for fast agent inference (~500ms/turn)
- Implemented **ZOPA calculator** (Zone of Possible Agreement) — mathematically enforces Pareto-optimal agreement bounds
- **Sentiment scoring** on each agent message + structured negotiation history tracking
- **Prompt injection defense** — validates agent prompts before execution to prevent manipulation
- Result: Agents converge to Pareto-optimal agreements in 3-4 rounds with 80%+ convergence, 7.3/10 avg sentiment

`Node.js` `Express` `React` `Groq API` `LLaMA-3.3-70B` `ReAct Framework` `Vercel`

---

### 💳 [Fraud Detection RL Environment](https://github.com/pulkit300405/fraud-detection-env)
> **Multi-turn RL environment for fraud investigation — agents reason under uncertainty, gather evidence, issue verdicts**

- Designed **OpenEnv-compatible** RL environment where agents investigate sessions via 5 signal types (IP velocity, device fingerprint, login frequency, geo anomaly, request patterns)
- Agents must balance **investigation cost vs. verdict confidence** — max 3-8 steps per session depending on difficulty tier
- **Deterministic heuristic grading** (no LLM-as-judge) ensures reproducibility and speed
- Multi-difficulty tasks: Easy (obvious fraud), Medium (mixed signals), Hard (adversarial evasion)
- Baseline performance: Qwen-72B scores 1.85 (easy), 1.10 (medium), 0.75 (hard)

`Python` `FastAPI` `PyTorch` `OpenEnv` `Docker` `HuggingFace Spaces`

---

### 🏛️ [IICPC Summer Hackathon — Benchmarking Platform](https://github.com/pulkit300405/Summer-Trading-Hackathon)
> **Distributed load testing platform for trading engine evaluation — 5K+ concurrent bots, latency p-percentiles, correctness validation**

- Engineered **Bot Fleet** (Go + goroutines) generating 5K+ concurrent connections with realistic order patterns
- Built **Submission Handler** — accepts contestant code, containerizes in Docker, runs in isolation
- **Telemetry Ingester** — captures latency (p50/p90/p99), throughput (TPS), validates correctness (FIFO, no double-fills)
- **Real-time React Leaderboard** with WebSocket updates
- Full stack: Microservices (Go), PostgreSQL + TimescaleDB (metrics), Kubernetes-ready infrastructure

`Go` `Docker` `Kubernetes` `PostgreSQL` `TimescaleDB` `React` `Microservices`

---

### 📈 [Trading Algorithms — IMC Prosperity 4](https://github.com/pulkit300405/imc-prosperity-4)
> **Multi-strategy quantitative trading bot — market making, momentum, options pricing, finals rank #660**

- Implemented **Black-Scholes option pricing** with pure-Python normal CDF (no external libs)
- **EMA momentum strategy** for directional bets + **market making** for liquidity provision
- **Premium selling** on OTM vouchers — delta hedging + Greeks calculation
- Competed as "KENSAI TRADING" (2-person team) — achieved **#22 country rank, #64 manual rank**
- Total PnL: ~4.65L XIRECs across 5 rounds

`Python (stdlib only)` `Black-Scholes` `Greeks` `Market Making` `Momentum Trading`

---

### 📍 [Macro Placement Challenge — Rank 53](https://github.com/pulkit300405/Macro-Placement-Challenge)
> **Simulated annealing + coordinate descent for circuit macro placement — 17 IBM ICCAD04 benchmarks**

- Implemented **SANetPlacer** using simulated annealing with tuned parameters (T_start = max(cw,ch)*0.25, T_end = max(cw,ch)*0.0008)
- **Edge extraction** via `_build_edges_from_net_nodes()` for NG45 compatibility
- **Refinement phase** (3000 iterations) — coordinate descent + pairwise swaps
- Result: 1.5286 avg HPWL (0 overlaps) across all benchmarks, below RePlAce baseline (1.4578)
- Key insight: Bottleneck is eval speed, not search strategy — optimized for fast evaluation

`Python` `Simulated Annealing` `Coordinate Descent` `Parallel Restarts` `Circuit Design`

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=pulkit300405&show_icons=true&theme=radical&hide_border=true" />
  <img src="https://github-readme-streak-stats.herokuapp.com?user=pulkit300405&theme=radical&hide_border=true" />
</p>

---

## 🏅 Achievements

- **3rd Place** — Agentic AI Hackathon @ MAIT (March 2026, 1,100+ registrations)
- **Rank 53** — Partcl × HRT Macro Placement Challenge (May 2026)
- **IMC Prosperity 4 Finals** — #660 overall, #64 manual strategy, #22 country (April 2026)
- **FOSSEE eSim Fellowship** — Task 5 submission (Tool Manager), IIT Bombay
- **Competitive Programming** — 300+ DSA problems on LeetCode/GFG

---

## 🌐 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/pulkit-singh-2nd-year-ece">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://github.com/pulkit300405">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://leetcode.com/u/pulkit300405/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/>
  </a>
</p>

---

Always learning. Open to **AI/ML internships, quant finance roles, hardware optimization challenges, and hackathons**.

⭐ Check out the projects — feedback welcome!
