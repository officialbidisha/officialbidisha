<div align="center">

# Hi, I'm Bidisha 👋

**Applied AI Engineer @ Salesforce · building agent harnesses · Bangalore, India**

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=650&lines=Building+RAG+%2B+agent+systems+with+LangChain+%26+LangGraph;Going+deep+on+Python%2C+carrying+years+of+JS+%2B+DSA+with+me;I+learn+by+building+and+breaking+things%2C+not+tutorials)](https://git.io/typing-svg)

[![Portfolio](https://img.shields.io/badge/Portfolio-portfolio--bidisha.vercel.app-000000?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-bidisha.vercel.app)
[![Blog](https://img.shields.io/badge/Blog-WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white)](https://bidishadas1.wordpress.com/)
[![dev.to](https://img.shields.io/badge/dev.to-@officialbidisha-0A0A0A?style=flat-square&logo=devdotto&logoColor=white)](https://dev.to/officialbidisha)
[![Profile views](https://komarev.com/ghpvc/?username=officialbidisha&style=flat-square&color=blue&label=Profile+views)](https://github.com/officialbidisha)
[![GitHub followers](https://img.shields.io/github/followers/officialbidisha?style=flat-square&label=Followers&color=blue)](https://github.com/officialbidisha?tab=followers)

</div>

---

### 🧠 What I work on

- **Agent harnesses:** orchestration, MCP tools, permission-aware execution, human approvals and evals.
- **Safe execution by design:** the part of the system that reasons stays separate from the part that acts.
- **Learning in public:** I write up the real bugs, not just the final working code ([dev.to](https://dev.to/officialbidisha), [blog](https://bidishadas1.wordpress.com/)).

---

### 🔭 Featured project: [ResolveFlow](https://github.com/officialbidisha/ResolveFlow)

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

### 🛠️ Also building

| Project | What it is |
|---|---|
| **[BhashaRoute](https://github.com/officialbidisha/bhasharoute)** | Calibrated, code-mix-robust intent routing for English, Hindi and Bengali (incl. Hinglish), with an independent side-effect safety gate. It abstains when unsure and asks before any action with side effects. `PyTorch` `XLM-RoBERTa` `FastAPI` |
| **[ai-engineering-harness](https://github.com/officialbidisha/ai-engineering-harness)** | LangGraph `Command`, `interrupt()` and `Send` fan-out at increasing levels of production-readiness: a durable approval service over FastAPI, per-branch failure isolation, prompt-injection fencing and citation validation. |
| **[Langchain-In-Depth](https://github.com/officialbidisha/Langchain-In-Depth)** | Hands-on LangChain/LangGraph: RAG pipelines, tool-calling agents, ReAct loops, guardrails. One concept per script, documented with the real bugs hit and fixed along the way. |
| **[Leetcode-Python](https://github.com/officialbidisha/Leetcode-Python)** | Python DSA solutions written test-first while learning the language, coming from a JavaScript background. |
| **[UberDSA](https://github.com/officialbidisha/UberDSA)** · **[ReactChallenges](https://github.com/officialbidisha/ReactChallenges)** | Interview-prep repos: real interview questions and React machine-coding exercises, kept for the frontend/JS depth behind the AI-systems work above. |

---

### 🌱 Open source

| Project | Pull request | Status |
|---|---|---|
| [shaka-player](https://github.com/shaka-project/shaka-player) (Google's DASH/HLS player) | [feat(DASH): subtitle support for `role` attribute and `kind='subtitle'`](https://github.com/shaka-project/shaka-player/pull/10441) | ![](https://img.shields.io/github/pulls/detail/state/shaka-project/shaka-player/10441?style=flat-square&label=) |
| [shaka-player](https://github.com/shaka-project/shaka-player) | [fix(HLS): add subtitle role when there are no roles](https://github.com/shaka-project/shaka-player/pull/5357) | ![](https://img.shields.io/github/pulls/detail/state/shaka-project/shaka-player/5357?style=flat-square&label=) |
| [supabase](https://github.com/supabase/supabase) | [fix(studio): keep valid backslash literals in Assistant SQL](https://github.com/supabase/supabase/pull/53226) | ![](https://img.shields.io/github/pulls/detail/state/supabase/supabase/53226?style=flat-square&label=) |
| [supabase](https://github.com/supabase/supabase) | [docs(branching): document overlapping production deploy runs](https://github.com/supabase/supabase/pull/53156) | ![](https://img.shields.io/github/pulls/detail/state/supabase/supabase/53156?style=flat-square&label=) |
| [compodoc](https://github.com/compodoc/compodoc) | [fix(markdown): add anchor ids to generated headings](https://github.com/compodoc/compodoc/pull/1765) | ![](https://img.shields.io/github/pulls/detail/state/compodoc/compodoc/1765?style=flat-square&label=) |
| [compodoc](https://github.com/compodoc/compodoc) | [feat(schemas): JSON schema for additional documentation `summary.json`](https://github.com/compodoc/compodoc/pull/1766) | ![](https://img.shields.io/github/pulls/detail/state/compodoc/compodoc/1766?style=flat-square&label=) |

---

### 🧰 Stack

**Languages**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**AI / ML**<br>
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Pinecone](https://img.shields.io/badge/Pinecone-0B3D2E?style=flat-square)

**Backend, data & web**<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

### 📊 GitHub stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=officialbidisha&theme=tokyonight" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=officialbidisha&theme=default" />
  <img height="165" alt="Bidisha's GitHub stats" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=officialbidisha&theme=default" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=officialbidisha&theme=tokyonight" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=officialbidisha&theme=default" />
  <img height="165" alt="Bidisha's top languages" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=officialbidisha&theme=default" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=officialbidisha&theme=tokyonight&hide_border=true" />
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com/?user=officialbidisha&hide_border=true" />
  <img alt="Bidisha's GitHub streak" src="https://streak-stats.demolab.com/?user=officialbidisha&hide_border=true" />
</picture>

</div>

---

### 📫 Connect

- 🌐 [portfolio-bidisha.vercel.app](https://portfolio-bidisha.vercel.app)
- ✍️ [dev.to/officialbidisha](https://dev.to/officialbidisha): write-ups on LangChain, RAG debugging, and the JS → Python DSA transition
- 📝 [bidishadas1.wordpress.com](https://bidishadas1.wordpress.com/): latest post, [*Brainy is the new sexy*](https://bidishadas1.wordpress.com/2026/08/19/brainy-is-the-new-sexy/)

<div align="center"><sub>Think, coz brain is the new sexy.</sub></div>
