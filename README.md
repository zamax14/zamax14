<a href="https://zamax14.github.io/Portafolio/"><img src="assets/header.gif" alt="EPISODE:2026 — Alejandro Zárate. The Engineer Who Automates the Automation." width="100%"></a>

## Hi, I'm Alejandro 👋

AI Engineer from Guadalajara, Mexico. I build retrieval systems, agents and MCP servers, plus the
unglamorous parts that keep them alive. Most of it speaks Spanish.

- 🏛️ **[IIEG](https://iieg.gob.mx)**: AI Engineer + Software Dev + Data Engineer + whatever's needed that week
- 🦎 **[Datzin](https://datzin.com.mx)**: co-founder, aspiring tech communicator, maker of for-fun projects in case one of them turns into something someday (closest emoji to an axolotl, sorry)
- 🧩 **Ixti**: AI consultant
- 🎓 **UdeG**: M.Sc. thesis on Spanish embeddings that help agents pick the right tool

### Things you should know about me

- 🤖 **AI nerd.** I'm more *markdown manager* than software engineer now. It's the natural evolution of *"10 hours automating a 5-minute task"* into *"more time writing skills and agents than code, so my AI codes the way I like."*
- 🟣 **Evangelion fan.** Very. Veeeeery. (There's a MAGI further down.)
- 🎮 **Gamer.** Recovered League player, jungle/top. Quitting was the greatest achievement of my life. Now: Pokémon, Binding of Isaac, Minecraft, Assassin's Creed, Hollow Knight.
- 🖥️ **Hardware and homelab**, one of my questionable life decisions.
- 🐈 **One cat.** He hates me until he decides he doesn't. Real love.
- 🍳 **Cooking.** Like dev: three hours of work, gone in five minutes.
- 🧠 **Expert in nothing, I dabble in everything.** We're here to learn.

### Toolbox

[![stack](https://skillicons.dev/icons?i=python,fastapi,postgres,docker,linux,pytorch,aws,gcp,terraform,githubactions,nginx,react,ts&perline=13)](https://zamax14.github.io/Portafolio/)

![Claude Code](https://img.shields.io/badge/Claude_Code-main_harness-D97757?style=flat-square&logo=claude&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-second_opinion-10A37F?style=flat-square&logo=gnometerminal&logoColor=white)
![Skills](https://img.shields.io/badge/skills_%26_agents-more_than_features-5B4A7D?style=flat-square&logo=markdown&logoColor=white)
![Vibe Coder](https://img.shields.io/badge/Vibe_Coder-with_an_engineering_degree-1C1B19?style=flat-square)

<sub>I don't ask AI for code and hope for the best. I design the system and write the skills, rules and agents, and the harness does the typing. **Architect of what the AI builds.**</sub>

<details>
<summary><sub><code>$ dmesg | tail</code></sub></summary>
<br>
<img src="assets/boot.gif" alt="Boot log listing my stack, ending with: cat.service refuses to cooperate (expected)" width="100%">
</details>

## Episodes

#### Agents and AI tooling

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/zamax14/claude-decide"><img src="assets/laya.webp" alt="claude-decide token benchmark"></a>
      <br><b><a href="https://github.com/zamax14/claude-decide">Laya / claude-decide</a></b>
      <br><sub>A 322M local model picks which skills and tools Claude Code needs. −39% tokens on Opus. <a href="https://huggingface.co/Zamax14/laya-context-prefilter">🤗</a></sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/zamax14/MAGI-Agent"><img src="assets/magi.webp" alt="MAGI deliberation console"></a>
      <br><b><a href="https://github.com/zamax14/MAGI-Agent">MAGI</a></b>
      <br><sub>Three Claude agents (dev, blind tester, docs) vote on your branch before a human does. Told you.</sub>
    </td>
    <td width="33%" valign="top">
      <img src="assets/data-agent.webp" alt="Data Agent episode card">
      <br><b>Data Agent</b> <sub><code>private</code></sub>
      <br><sub>A local-first data analyst built on Deep Agents + Ollama. It handles indicators, hybrid RAG, charts and reports, and asks you before acting. An ASCII axolotl narrates.</sub>
    </td>
  </tr>
</table>

#### Research

<table>
  <tr>
    <td width="40%" valign="top">
      <img src="assets/thesis.webp" alt="Tool selection MRR@5: proposed model 0.87 vs 0.44 for the best existing model">
    </td>
    <td valign="top">
      <b>Spanish embeddings for agentic tool selection</b> <sub><code>M.Sc. thesis · private</code></sub>
      <br><sub>My fine-tuned Spanish embedding model picks the right tool out of 213 (24 real, 189 decoys) with <b>MRR@5 0.87</b>. The best off-the-shelf model gets 0.44, and BM25 gets 0.36.</sub>
      <br><sub>Pipeline: <a href="https://github.com/zamax14/SyntheticDataLLM">SyntheticDataLLM</a> (Spanish Q&amp;A from documents) → fine-tuning E5/BETO → retrieval and tool-selection benchmarks on a DGX A100.</sub>
    </td>
  </tr>
</table>

#### Datzin, open source

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/DatzinDev/Atlas"><img src="assets/atlas.webp" alt="Atlas geoportal design"></a>
      <br><b><a href="https://github.com/DatzinDev/Atlas">Atlas</a></b>
      <br><sub>Serves PostGIS layers as WMS, WFS and vector tiles from FastAPI, with no GeoServer. Powers <a href="https://densimap.datzin.com.mx">DensiMap</a>.</sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/DatzinDev/VizControl"><img src="assets/vizcontrol.webp" alt="VizControl replay"></a>
      <br><b><a href="https://github.com/DatzinDev/VizControl">VizControl</a></b>
      <br><sub>Records a Python run so you can replay it in the browser, like a debugger after the fact.</sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/DatzinDev/EIC-API-MCP"><img src="assets/eic.webp" alt="EIC intercensal survey service"></a>
      <br><b><a href="https://github.com/DatzinDev/EIC-API-MCP">EIC-API-MCP</a></b>
      <br><sub>Mexico's intercensal survey, served with DuckDB, FastAPI and MCP so any AI assistant can query it. <a href="https://eic.datzin.com.mx">Live</a>.</sub>
    </td>
  </tr>
</table>

#### IIEG, public sector

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/iieg-oficial/minerva"><img src="assets/minerva.webp" alt="Minerva identity provider"></a>
      <br><b><a href="https://github.com/iieg-oficial/minerva">Minerva</a></b>
      <br><sub>OAuth2/OIDC identity provider for a whole institute. With it, nobody has to build login again.</sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/iieg-oficial/Indicadores_SIEEJ"><img src="assets/indicadores.webp" alt="Indicadores episode card"></a>
      <br><b><a href="https://github.com/iieg-oficial/Indicadores_SIEEJ">Indicadores SIEEJ</a></b>
      <br><sub>Official statistics served as an MCP server, so agents quote real numbers and never invent them.</sub>
    </td>
    <td width="33%" valign="top">
      <br><b>…and more</b>
      <br><sub>Corkbit, airflow-mcp, ETL pipelines, road-sign detection, talks and workshops, all in my <a href="https://zamax14.github.io/Portafolio/">portfolio</a>.</sub>
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

<img src="assets/footer.gif" alt="CI's in its heaven. All's green in prod. — build passing, 0 incidents, the cat is (mostly) fine. To be continued." width="100%">
