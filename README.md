<div align="center">

# Bidisha Das

**Senior Member of Technical Staff · Applied AI @ Salesforce · Bengaluru, India (IST)**

I build the layer that lets AI agents **act safely in production**: MCP tools, orchestration,<br>
permission-aware execution, human approval, and evals that gate every release.

[![Portfolio](https://img.shields.io/badge/Portfolio-portfolio--bidisha.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-bidisha.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-bidisha--das-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/bidisha-das)
[![dev.to](https://img.shields.io/badge/dev.to-officialbidisha-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white)](https://dev.to/officialbidisha)

</div>

---

### ⚡ At a glance

- **6 years of production engineering** in **Java, Python and TypeScript**: enterprise AI agents at **Salesforce**, video playback for **50M+ users** at **Disney+ Hotstar**, regulated lending and forex workflows at **MakeMyTrip**.
- **Agent infrastructure:** MCP servers and tool contracts, supervisor/specialist orchestration, approval-gated writes, LLM evaluation with must-pass safety cases.
- **Open source:** merged fixes in Google's **[Shaka Player](https://github.com/shaka-project/shaka-player)**; contributions to **[Supabase](https://github.com/supabase)** (Studio, docs, agent skills).
- **Side projects you can try:** a deployed agent with real OAuth and durable human approval, and a multilingual router with a fail-closed safety gate.

---

### 🔭 Featured: [ResolveFlow](https://github.com/officialbidisha/ResolveFlow)

<a href="https://github.com/officialbidisha/ResolveFlow"><img width="640" alt="ResolveFlow" src="https://github.com/user-attachments/assets/c5209dfd-b2a8-420d-8af0-6e8819d0792f" /></a>

A LangGraph agent that diagnoses GitHub issues and proposes fixes, but **never touches GitHub without an independent LLM review _and_ explicit human approval**. Reasoning and execution are separated by construction, not convention.

- 🔐 **Live and deployed:** sign in with your own GitHub account, and every write runs as *you*.
- 📚 **Grounded diagnoses:** retrieval is gated by a measured relevance threshold, not just "cited a real id".
- ⚖️ **Deterministic review gate:** the review model's approve/escalate call is decided in code, never trusted from the LLM.
- ⏸️ **Durable human-in-the-loop:** the approval pause is a real LangGraph `interrupt()` persisted in Postgres, resumable hours later from a different request.
- 🧪 **Regression evals:** `pass^k` semantics, where one bypassed safety gate is a critical failure, not an average.

**[▶ Live demo](https://resolveflow-web-officialbidishas-projects.vercel.app/)** · **[README](https://github.com/officialbidisha/ResolveFlow#readme)**

`LangGraph` `RAG` `Pinecone` `FastAPI` `React` `TypeScript` `PostgreSQL` `OAuth`

---

### 🛠️ More projects

| Project | What it shows |
|---|---|
| **[BhashaRoute](https://github.com/officialbidisha/bhasharoute)** | Calibrated intent routing for English, Hindi and Bengali (incl. Hinglish) that **abstains when unsure** and asks before any action with side effects. **87.8% macro-F1 vs 62.0%** for keyword rules on 8,157 human-translated requests; the fail-closed safety gate catches **99.5%** of state-changing requests. Three approaches compared on identical splits, up to a fine-tuned XLM-RoBERTa. `PyTorch` `XLM-RoBERTa` `scikit-learn` `FastAPI` |
| **[ai-engineering-harness](https://github.com/officialbidisha/ai-engineering-harness)** | LangGraph `Command`, `interrupt()` and `Send` fan-out at increasing levels of production-readiness: a durable approval service over FastAPI, per-branch failure isolation, prompt-injection fencing and citation validation. |
| **[Langchain-In-Depth](https://github.com/officialbidisha/Langchain-In-Depth)** | RAG pipelines, tool-calling agents, ReAct loops and guardrails, one concept per script, documented with the real bugs hit and fixed along the way. |

<details>
<summary><b>Interview prep and earlier frontend work</b></summary>
<br>

| Project | What it is |
|---|---|
| **[UberDSA](https://github.com/officialbidisha/UberDSA)** | Curated DSA questions with JavaScript solutions. |
| **[ReactChallenges](https://github.com/officialbidisha/ReactChallenges)** · **[HTMLCSSMachineCoding](https://github.com/officialbidisha/HTMLCSSMachineCoding)** · **[Polyfills](https://github.com/officialbidisha/Polyfills)** | React and vanilla-JS machine-coding exercises and polyfills. |
| **[Leetcode-Python](https://github.com/officialbidisha/Leetcode-Python)** | Python DSA solutions, written test-first. |

</details>

---

### 🌱 Open source

| Project | Pull request | Status |
|---|---|---|
| [shaka-player](https://github.com/shaka-project/shaka-player) (Google's DASH/HLS player) | [feat(DASH): subtitle support for `role` attribute and `kind='subtitle'`](https://github.com/shaka-project/shaka-player/pull/10441) | ![](https://img.shields.io/github/pulls/detail/state/shaka-project/shaka-player/10441?style=flat-square&label=) |
| [shaka-player](https://github.com/shaka-project/shaka-player) | [fix(HLS): add subtitle role when there are no roles](https://github.com/shaka-project/shaka-player/pull/5357) | ![](https://img.shields.io/github/pulls/detail/state/shaka-project/shaka-player/5357?style=flat-square&label=) |
| [supabase/agent-skills](https://github.com/supabase/agent-skills) | [fix(supabase): verify effective Data API grants before committing a migration](https://github.com/supabase/agent-skills/pull/651) | ![](https://img.shields.io/github/pulls/detail/state/supabase/agent-skills/651?style=flat-square&label=) |
| [supabase](https://github.com/supabase/supabase) | [fix(studio): keep valid backslash literals in Assistant SQL](https://github.com/supabase/supabase/pull/53226) | ![](https://img.shields.io/github/pulls/detail/state/supabase/supabase/53226?style=flat-square&label=) |
| [supabase](https://github.com/supabase/supabase) | [docs(branching): document overlapping production deploy runs](https://github.com/supabase/supabase/pull/53156) | ![](https://img.shields.io/github/pulls/detail/state/supabase/supabase/53156?style=flat-square&label=) |
| [compodoc](https://github.com/compodoc/compodoc) | [fix(markdown): add anchor ids to generated headings](https://github.com/compodoc/compodoc/pull/1765) | ![](https://img.shields.io/github/pulls/detail/state/compodoc/compodoc/1765?style=flat-square&label=) |
| [compodoc](https://github.com/compodoc/compodoc) | [feat(schemas): JSON schema for additional documentation `summary.json`](https://github.com/compodoc/compodoc/pull/1766) | ![](https://img.shields.io/github/pulls/detail/state/compodoc/compodoc/1766?style=flat-square&label=) |

---

### 🧰 Stack

**Languages** &nbsp;
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**AI agents** &nbsp;
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Pinecone](https://img.shields.io/badge/Pinecone-0B3D2E?style=flat-square)

**Backend & infra** &nbsp;
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

**Frontend** &nbsp;
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

---

### ✍️ Writing

I write up the real bugs, not just the final working code: [dev.to/officialbidisha](https://dev.to/officialbidisha) (LangChain, RAG debugging) and [bidishadas1.wordpress.com](https://bidishadas1.wordpress.com/).

### 📫 Contact

The quickest way to reach me is a message on [LinkedIn](https://www.linkedin.com/in/bidisha-das). More about my work: [portfolio-bidisha.vercel.app](https://portfolio-bidisha.vercel.app).
