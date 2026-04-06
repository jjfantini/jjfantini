### Jennings Fantini

self-taught engineer. started in molecular biology, ended up building financial infrastructure and AI systems.

I've spent the last few years building things that handle real money, real data, and real-time operations - co-founded [Finatic](https://finatic.dev) (cloud-native multi-broker trading backend, received a $1.5M acquisition offer), built [humblFINANCE](https://humblfinance.io), and currently deep in AI agent orchestration and ML feature engineering for finance.

---

**currently working on:** 🔭

- **[humblDATA](https://github.com/humblFINANCE/humblDATA)** - open-source quant data pipeline built on Polars. first-principles volatility estimators, typed end-to-end, modular MVC-DB architecture underneath. backend that powers humblFINANCE.
- **agent orchestration (private clients)** 🤖 - fault-tolerant LLM pipelines with typed outputs, RL feedback loops, retry mechanisms, observability, and distributed agent architectures built to handle concurrent AI operations.

**past projects worth knowing about:**

- **[Finatic](https://finatic.dev)** - co-founded and served as Chief Engineer. built the cloud-native multi-broker trading backend (FastAPI + Supabase/PostgreSQL + Redis) from scratch - real-time trading, high-throughput API workloads, DB-centric automated type generation across Python and TypeScript, and an API designed to be consumed natively by modern AI protocols (MCP, A2A, ACP). drove it to a $1.5M acquisition offer.
- **[humblFINANCE](https://humblfinance.io)** - elegant webstie enabling retail traders access to professioanl hedge-fund grade quantamental analytics; built from an pricing algorithm I developed (humblDATA). full-stack: database, user management, API integration, custom quant algorithm for stable stock price analysis and macro forecasting.

---

**two architecture patterns I keep coming back to:** 🏗️

**[MVC-DB](https://humblfinance.github.io/humblDATA/code_design/mvcdb/)** - personal adaptation of MVC architecture with native DB integration. DB schema drives type generation end-to-end. Python + TypeScript stay in sync automatically. modular, fault-tolerant, type-safe by design. I use this as the backbone for any library that needs to scale fast without falling apart, with clear ownership and seperation of buisness logic.

**[CCCC (Core, Context, Category, Command)](https://humblfinance.github.io/humblDATA/code_design/cccc_method/)** - a custom nested hierarchical design paradigm for organizing code so you always know exactly where something belongs. Core holds internal logic, Context groups high-level modules, Category groups related commands, Command is the smallest executable unit. makes flowcharting your app trivial and reusability almost automatic.

---

**what I'm focused on:** 🎯

AI agent orchestration - ML feature engineering for finance - scalable backend architecture - typed AI pipelines - data systems that don't need babysitting

---

**stack most commonly used:** 🛠️

`Python` 🐍 `TypeScript`🗳️ `R` 🔬 `FastAPI`⚡️ `Next.js` `React`⚛️ `PostgreSQL`🧮 `Redis`💽 `Polars`🐻‍❄️ `Docker`🐋 `Supabase`🚀 `DigitalOcean`🌊 
