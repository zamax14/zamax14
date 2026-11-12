<a href="https://zamax14.github.io/Portafolio/"><img src="assets/header.gif" alt="EPISODE:2026 — Alejandro Zárate. The Engineer Who Automates the Automation." width="100%"></a>

## Hi, I'm Alejandro 👋

AI Engineer from Guadalajara, Mexico. I build retrieval systems, agents and MCP servers, plus
the less glamorous parts that keep them running: APIs, data pipelines, geospatial databases
and Linux boxes. Most of what I build speaks Spanish.

- 🏛️ **AI Developer @ [IIEG](https://iieg.gob.mx)**: GenAI over Jalisco's public data (RAG, agents, MCP servers)
- 🦎 **Co-founder @ [Datzin](https://datzin.com.mx)**: a software studio with an axolotl mascot (this is the closest emoji, sorry)
- 🧩 **Consultant @ Ixti**: client systems, automation, geospatial ML
- 🎓 **M.Sc. @ UdeG**: Spanish embeddings that help agents pick the right tool

### Things you should know about me

- 🤖 **AI nerd.** I spend more time as a *markdown manager* than as a software engineer. It's the natural evolution of *"spent 10 hours automating a 5-minute task"* into *"spend longer writing skills and agents than writing code, so my AI codes the way I like."*
- 🟣 **Evangelion fan.** Very. Veeeeery. (Yes, there's a MAGI further down.)
- 🎮 **Gamer.** Recovered League of Legends player, jungle/top. Quitting is the greatest achievement of my life. These days: Pokémon, The Binding of Isaac, Minecraft, Assassin's Creed, Hollow Knight…
- 🖥️ **Hardware and homelabbing**, one of my questionable life decisions.
- 🐈 **One cat.** He hates me, except when he decides he doesn't. That's the real kind of love.
- 🍳 **I love cooking.** It's like dev: three hours of work for something that's gone in five minutes.
- 🧠 **Expert in nothing, I dabble in everything.** We're here to learn.

### What runs on me

<img src="assets/boot.gif" alt="Boot log listing my stack: Python, FastAPI, PostgreSQL, PostGIS, pgvector, DuckDB, LangChain, LangGraph, Deep Agents, FastMCP, sentence-transformers, FAISS, PyTorch, Airflow, Docker, Linux, AWS, GCP, Terraform, React, TypeScript, Claude Code, Codex" width="100%">

## Episodes

#### Agents and AI tooling

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/zamax14/claude-decide"><img src="assets/laya.webp" alt="claude-decide token benchmark"></a>
      <br><b><a href="https://github.com/zamax14/claude-decide">Laya / claude-decide</a></b>
      <br><sub>A 322M local model picks which skills and MCP tools Claude Code needs for each request. −39% tokens and −37% cost on Opus. <a href="https://huggingface.co/Zamax14/laya-context-prefilter">🤗 model</a></sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/zamax14/MAGI-Agent"><img src="assets/magi.webp" alt="MAGI deliberation console"></a>
      <br><b><a href="https://github.com/zamax14/MAGI-Agent">MAGI</a></b>
      <br><sub>Three Claude agents (a dev, a blind tester and a docs reviewer) deliberate on your branch before a human does. Told you.</sub>
    </td>
    <td width="33%" valign="top">
      <img src="assets/data-agent.webp" alt="Data Agent episode card">
      <br><b>Data Agent</b> <sub><code>private</code></sub>
      <br><sub>Local-first data analyst on Deep Agents + Ollama: predefined indicators (no free-form SQL), hybrid RAG with BM25 and embeddings, Plotly charts, report templates and human approvals. An ASCII axolotl shows you what it's doing.</sub>
    </td>
  </tr>
</table>

#### Research

<table>
  <tr>
    <td width="33%" valign="top">
      <img src="assets/thesis.webp" alt="Retrieval metrics heatmap by embedding model">
    </td>
    <td valign="top">
      <b>Spanish embeddings for agentic tool selection</b> <sub><code>M.Sc. thesis · private</code></sub>
      <br><sub>If an agent retrieves the right context and the right tool, it needs fewer tokens to get the job done. The pipeline:</sub>
      <br><sub>
        1. <a href="https://github.com/zamax14/SyntheticDataLLM">SyntheticDataLLM</a> turns documents into Spanish Q&amp;A with local models<br>
        2. Fine-tune BETO and E5 with MNRL, cosine and triplet losses<br>
        3. Evaluate context retrieval over 3,530 chunks and tool retrieval among a ReAct agent's 24 BI tools plus distractors (FAISS vs BM25, Hit@K, MRR, nDCG), on a DGX A100 via SLURM
      </sub>
      <br><sub>Laya (above) started as the practical side of the same question.</sub>
    </td>
  </tr>
</table>

#### Datzin, open source

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/DatzinDev/Atlas"><img src="assets/atlas.webp" alt="Atlas geoportal design"></a>
      <br><b><a href="https://github.com/DatzinDev/Atlas">Atlas</a></b>
      <br><sub>PostGIS layers as WMS, WFS and vector tiles from inside FastAPI. No GeoServer. Powers <a href="https://densimap.datzin.com.mx">DensiMap</a>.</sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/DatzinDev/VizControl"><img src="assets/vizcontrol.webp" alt="VizControl replay"></a>
      <br><b><a href="https://github.com/DatzinDev/VizControl">VizControl</a></b>
      <br><sub>Record a Python run, then replay it in the browser step by step, like a debugger after the fact.</sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/DatzinDev/EIC-API-MCP"><img src="assets/eic.webp" alt="EIC intercensal survey service"></a>
      <br><b><a href="https://github.com/DatzinDev/EIC-API-MCP">EIC-API-MCP</a></b>
      <br><sub>INEGI's intercensal survey behind DuckDB, FastAPI and FastMCP, so any AI assistant can query it. <a href="https://eic.datzin.com.mx">Live</a>.</sub>
    </td>
  </tr>
</table>

#### IIEG, public sector

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/iieg-oficial/minerva"><img src="assets/minerva.webp" alt="Minerva identity provider"></a>
      <br><b><a href="https://github.com/iieg-oficial/minerva">Minerva</a></b>
      <br><sub>OAuth2/OIDC identity provider for a whole state institute: PKCE, JWKS key rotation and a FastAPI SDK, so no system re-implements login again.</sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/iieg-oficial/Indicadores_SIEEJ"><img src="assets/indicadores.webp" alt="Indicadores episode card"></a>
      <br><b><a href="https://github.com/iieg-oficial/Indicadores_SIEEJ">Indicadores SIEEJ</a></b>
      <br><sub>Official statistics as an MCP server and REST API. One YAML per indicator and one output contract across 33 databases, so agents never make up a number.</sub>
    </td>
    <td width="33%" valign="top">
      <br><b>…and more</b>
      <br><sub>Corkbit (Kanban + thermal printer + MCP), airflow-mcp, ETL pipelines, road-sign detection, talks and workshops. They all live in my <a href="https://zamax14.github.io/Portafolio/">portfolio</a>.</sub>
    </td>
  </tr>
</table>

---

<p align="center">
  <a href="https://zamax14.github.io/Portafolio/">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/alexzaratem14">LinkedIn</a> ·
  <a href="https://datzin.com.mx">Datzin</a> ·
  <a href="https://huggingface.co/Zamax14">🤗 Hugging Face</a> ·
  <a href="mailto:zarate.alejandroM14@gmail.com">Email</a>
</p>

<img src="assets/footer.gif" alt="God's in his heaven. All's right with the world. — prod is green, the cat is (mostly) fine. To be continued." width="100%">
