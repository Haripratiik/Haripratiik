<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2500&pause=900&color=58A6FF&center=true&vCenter=true&width=750&lines=Backend+%2B+full-stack+software+engineer;Physical+AI+%2B+computational+physics+%40+Georgia+Tech+%2F+LANL;Youngest+ever+intern+in+ITER%27s+science+division;Exchange+systems+%7C+market+microstructure+%7C+quant+research;Python+%7C+TypeScript+%7C+C%2B%2B+%7C+JAX" alt="Typing SVG" />

<br/>

**Hari** &nbsp;·&nbsp; Student @ Georgia Tech &nbsp;·&nbsp; CS (Intelligence + Modeling/Simulation) + Physics Minor

*I build simulation systems, trading infrastructure, and the full-stack software that makes both usable.*

<br/>

[![Georgia Tech](https://img.shields.io/badge/Georgia_Tech-B3A369?style=flat-square&logoColor=white)](https://gatech.edu)
[![LANL](https://img.shields.io/badge/Los_Alamos_National_Lab-003B6F?style=flat-square&logoColor=white)](https://lanl.gov)
[![ITER](https://img.shields.io/badge/ITER_France_Alumnus-00539C?style=flat-square&logoColor=white)](https://iter.org)
[![PPPL](https://img.shields.io/badge/Princeton_PPPL-FF6B00?style=flat-square&logoColor=white)](https://pppl.gov)
[![Open to Internships](https://img.shields.io/badge/Open_to_Internships_Summer_2027-2ea44f?style=flat-square)](mailto:harieduam@gmail.com)

</div>

---

## About

My work runs along three tracks. They have more in common than they look like they do: all three come down to simulation, measurement, and the software that makes both trustworthy.

**Research and physical AI.** Fusion plasma simulation and differentiable physics, currently with Dr. Qi Tang's group at Georgia Tech and Los Alamos. Before that, research at Princeton's Plasma Physics Laboratory and at ITER in France, which I joined at 16. Alongside it I build simulated bodies and controllers, GPU physics engines, and digital twins.

**Quant.** Market systems written from scratch: an electronic exchange with its own matching engine, clearing house and trading agents, and a full execution stack pointed at a live venue, each with the research harness needed to measure what it actually does.

**Software.** Most of what I ship is a system rather than a script. The exchange serves 17 REST routes and a streaming socket behind HMAC-signed requests, with a browser trading terminal on top of it. The trading engine runs four processes against a WAL-mode SQLite store, with idempotency keys minted before every network call and a kill switch that stops everything in five seconds. Between the two there are about 2,200 tests. I also build full-stack web applications, a Chrome extension, an MCP server, and CI/CD and runtime monitoring for AI agents.

I'm looking for summer 2027 roles in quant finance, physical AI, and fusion energy.

---

## Research

| Institution | Role | Domain |
|---|---|---|
| **Georgia Tech / Los Alamos National Lab** | Researcher, Dr. Qi Tang's group | JAX MHD solvers · differentiable tokamak digital twins |
| **ITER** · Cadarache, France | Software Engineering Intern *(youngest ever in ITER's science division)* | International thermonuclear reactor project |
| **Princeton Plasma Physics Laboratory** | Research | Spin-polarized fusion · field-reversed configuration plasmas |
| **17th Kudowa Fusion Summer School** · Poland | Selected Researcher *(youngest ever selected)* | Plasma physics · fusion science |

---

## Projects

| Project | Description | Tech |
|---|---|---|
| **[Artificial Brawl Stars Exchange](https://github.com/Haripratiik/artificial-brawlstars-exchange)** | An electronic exchange written from scratch, ~24k lines behind 1,054 tests. A price-time matching engine over a deterministic discrete-event kernel, nine asset classes, auctions and circuit breakers, exact collateral netting on integer money, 17 REST routes plus a streaming socket with HMAC-signed requests, and a browser trading terminal built on vanilla ES modules with no build step. | Python · FastAPI · WebSockets · REST · ES modules |
| **[Prediction Market Trading Engine](https://github.com/Haripratiik/prediction-market-trading-engine)** | Full trading stack for Kalshi, ~23k lines behind 1,133 tests, built on 7.5M rows of live venue data. Four processes over a WAL-mode SQLite store: a recorder ingesting REST and WebSocket feeds with sequence-gap resync, a risk engine, and a diff-based order manager with idempotency keys and a five-second kill switch. Used it to measure how efficient the venue actually is across 4,258 settled markets. | Python · SQLite · WebSockets · RSA-PSS auth |
| **[AgentSym](https://github.com/AgentSym/AgentSymv1)** | CI/CD and runtime-monitoring platform for action-taking AI agents. Runs production-shaped agent harnesses against simulated tools, policies, and state, then turns failures into replayable traces, regressions, and deploy-gate evidence. | Python · FastAPI · React · Docker |
| **[Virturoid](https://github.com/Haripratiik/Virturoid)** | Prompt-to-robot platform that turns natural-language prompts into buildable robot bodies, CAD, BOMs, MuJoCo simulations, and learned controllers. | Python · MuJoCo/MJX · JAX · PyTorch · build123d · Three.js |
| **[Energy Grid Digital Twin](https://github.com/Haripratiik/Energy-Grid-Digital-Twin)** | 80-bus power-grid digital twin with IEEE-validated power flow, real-time state estimation, N-1 contingency screening, and physics-gated AI operations. | FastAPI · React · GPT-4o · pandapower · D3.js |
| **[Internship Tracker](https://github.com/Haripratiik/InternshipTracker)** | Full-stack internship and new-grad job tracker with multi-source scraping, GPT-4o relevance scoring, a Kanban pipeline, and a Chrome extension that auto-fills applications across Greenhouse, Lever, Workday, and Ashby. | Next.js · TypeScript · Firebase · GPT-4o |
| **[MOSAIC Context Manager](https://github.com/Haripratiik/MOSAIC-Context-Manager)** | Permission-aware context layer for retrieval-heavy AI systems. Retrieves, filters, audits, and serves scoped context to LLM workflows through a CLI, a UI, and an MCP server. | Python · JAX · MCP · SQLite |
| **JAX MHD Solver** | Differentiable magnetohydrodynamics solver for tokamak plasma simulation. Active collaboration with LANL. | JAX · NumPy |
| **[Plasma-Physics Macro Placement](https://github.com/Haripratiik/Plasma-Fusion-Physics-Macro-Place-Algo)** | Macro-placement solver for the Partcl × Hudson River Trading 2026 challenge. Models chip placement as a Grad-Shafranov / MHD equilibrium: macros act as current-bearing particles, nets set the current topology, and the layout relaxes toward a low-energy state. | Python · MHD · Optimization |
| **[Stock Portfolio Optimizer](https://github.com/Haripratiik/Stock-Portfolio-Optimizer)** | Portfolio construction and optimization using genetic algorithms, a custom backtesting engine, MCMC sampling, and ML sentiment analysis. | JAX · NumPyro · Python |
| **[Portfolio Regime & Stress Lab](https://github.com/Haripratiik/Portfolio-Regime-Stress-Lab)** | Time-series study of how stress builds and spreads across mega-cap tech stocks: K-Means regime detection, a custom stress-propagation score, walk-forward ARIMA volatility forecasting benchmarked against a naive baseline, and GBM Monte Carlo VaR/CVaR. Companion to the Stock Portfolio Optimizer. | Python · scikit-learn · statsmodels |
| **[SPH Medical Airflow Simulator](https://github.com/Haripratiik/Unity-SPH-Fluid-Simulator)** | Smoothed-particle hydrodynamics engine that simulates airflow through the respiratory bronchioles of a lung, with wall-mesh and particle collision handling. Runs as a full GPU compute pipeline. | C# · HLSL · Unity |
| **[Dark Matter Rotation Curves](https://github.com/Haripratiik/Rotation-Curve-Fitting-Code)** | Bayesian inference pipeline that fits galaxy rotation curves to competing dark-matter models using NUTS/HMC sampling and BIC model selection. | JAX · NumPyro |

---
## Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![HLSL](https://img.shields.io/badge/HLSL-5C2D91?style=flat-square&logo=windows&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Web, backend and infrastructure**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![WebSockets](https://img.shields.io/badge/WebSockets-0A0A0A?style=flat-square)
![REST](https://img.shields.io/badge/REST_APIs-0a66c2?style=flat-square)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Scientific computing**

![JAX](https://img.shields.io/badge/JAX-A8B9CC?style=flat-square&logo=google&logoColor=black)
![NumPyro](https://img.shields.io/badge/NumPyro-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![pandapower](https://img.shields.io/badge/pandapower-FF6B35?style=flat-square&logo=powerbi&logoColor=white)

**Domains**

![Plasma Physics](https://img.shields.io/badge/Plasma_Physics-0a66c2?style=flat-square)
![Bayesian Inference](https://img.shields.io/badge/Bayesian_Inference-7B2FBE?style=flat-square)
![Quant Finance](https://img.shields.io/badge/Quant_Finance-1a7f37?style=flat-square)
![Market Microstructure](https://img.shields.io/badge/Market_Microstructure-0A0A0A?style=flat-square)
![GPU Computing](https://img.shields.io/badge/GPU_Computing-76B900?style=flat-square&logo=nvidia&logoColor=white)
![MHD Simulation](https://img.shields.io/badge/MHD_Simulation-c0392b?style=flat-square)
![Power Systems](https://img.shields.io/badge/Power_Systems-e67e22?style=flat-square)
![Digital Twins](https://img.shields.io/badge/Digital_Twins-0d7377?style=flat-square)

---

<div align="center">

**[harieduam@gmail.com](mailto:harieduam@gmail.com)** &nbsp;·&nbsp; **[LinkedIn](https://linkedin.com/in/haripratiik)** &nbsp;·&nbsp; **[Georgia Tech](https://gatech.edu)**

*Always happy to talk quant finance, fusion energy, and physical AI.*

</div>
