<div align="center">
  <img src="assets/hero.svg" width="100%" alt="Chandan Garg — terminal intro" />
</div>

<h2 align="left"> Hello there! I'm Chandan Garg, a Full Stack Web Developer and Node.js enthusiast.</h2>

I build AI-native tools that turn messy inputs (a spoken sentence, a stack trace, an open question) into something you can act on. Below are three of them, with their pipelines running live.

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="30" alt="javascript logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="30" alt="typescript logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="30" alt="react logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="30" alt="nextjs logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="30" alt="nodejs logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" height="30" alt="express logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="30" alt="python logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" height="30" alt="fastapi logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="30" alt="html5 logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="30" alt="css3 logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" height="30" alt="figma logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" height="30" alt="c logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="30" alt="cplusplus logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="30" alt="java logo" />
</div>

---

##  Featured projects · live workflows

### 🎙 [VoiceGraph](https://github.com/Chandan11232/voicegraph) — *say the system, shape it by hand*

<a href="https://voicegraph-mocha.vercel.app"><img src="assets/voicegraph.svg" width="100%" alt="VoiceGraph workflow: voice → API → Groq LLM → validate + ELK layout → React Flow canvas" /></a>

A voice-first architecture whiteboard. Describe a system out loud and it becomes an editable diagram. Refine it by voice or by hand, get an AI architecture review that flags single points of failure, and export to PNG, SVG, Mermaid or a generated README section.

![React](https://img.shields.io/badge/React_Flow-20232a?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-1a1a2e?style=flat-square&logo=vite&logoColor=FFD62E)
![Groq](https://img.shields.io/badge/Groq-gpt--oss--120b-f55036?style=flat-square)
![Wispr Flow](https://img.shields.io/badge/Wispr_Flow-voice-a371f7?style=flat-square)
![Vercel](https://img.shields.io/badge/Vercel-serverless-000?style=flat-square&logo=vercel)
&nbsp;→&nbsp; **[Live demo](https://voicegraph-mocha.vercel.app)** · **[Code](https://github.com/Chandan11232/voicegraph)**

---

###  [GraphSleuth](https://github.com/Chandan11232/GraphSleuth) — *from bug report to verified fix*

<a href="https://codebase-detector.vercel.app"><img src="assets/graphsleuth.svg" width="100%" alt="GraphSleuth workflow: bug report → FalkorDB code graph trace → ranked suspects → sandbox verify → PR draft" /></a>

A bug-investigation agent that reasons over a FalkorDB graph of your codebase. Give it a bug report or stack trace and it traces call paths to the likely root cause, shows the Cypher behind every step, drafts a patch, tests it in a sandbox before and after, and prepares a PR with suggested reviewers, waiting for a human to approve. Confirmed root causes are remembered for next time. Built for Graph Hacks 2026.

![Python](https://img.shields.io/badge/Python-FastAPI-3776AB?style=flat-square&logo=python&logoColor=white)
![FalkorDB](https://img.shields.io/badge/FalkorDB-graph-ff4f64?style=flat-square)
![tree-sitter](https://img.shields.io/badge/tree--sitter-parsing-2ea043?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-server-8b5cf6?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-optional_LLM-000?style=flat-square)
&nbsp;→&nbsp; **[Live demo](https://codebase-detector.vercel.app)** · **[Code](https://github.com/Chandan11232/GraphSleuth)**

---

###  [ResearchMind](https://github.com/Chandan11232/research-mind) — *research that iterates until it's sure*

<a href="https://research-mind.vercel.app"><img src="assets/researchmind.svg" width="100%" alt="ResearchMind workflow: question → plan → Tavily search → analyze → loop until done → report" /></a>

An iterative AI research app. A LangGraph workflow plans, searches the web with Tavily, analyzes what it found with Llama 3.3 on Groq, and loops back with a refined query until it has enough evidence to write the report, all driven from a dark terminal-style Next.js UI.

![LangGraph](https://img.shields.io/badge/LangGraph-agent_loop-1C3C3C?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-backend-009688?style=flat-square&logo=fastapi&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-Llama_3.3-f55036?style=flat-square)
![Tavily](https://img.shields.io/badge/Tavily-search-3fb950?style=flat-square)
![Next.js](https://img.shields.io/badge/Next.js-terminal_UI-000?style=flat-square&logo=nextdotjs)
&nbsp;→&nbsp; **[Live demo](https://research-mind.vercel.app)** · **[Code](https://github.com/Chandan11232/research-mind)**

---

##  Let's connect

<div align="center">
  <a href="mailto:cgarg2461@gmail.com" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail logo" />
  </a>
  <a href="https://www.linkedin.com/in/chandan-garg-701b81420/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="linkedin logo" />
  </a>
  <a href="https://github.com/Chandan11232" target="_blank">
    <img src="https://img.shields.io/static/v1?message=GitHub&logo=github&label=&color=181717&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="github logo" />
  </a>
</div>

<br/>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=Chandan11232&color=a371f7&style=for-the-badge&label=PROFILE+VIEWS" alt="profile views" />
</div>
