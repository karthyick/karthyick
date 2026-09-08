<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:8b5cf6,50:6366f1,100:10b981&height=200&section=header&text=Karthick%20Raja%20M&fontSize=48&fontColor=ffffff&fontAlignY=32&desc=I%20build%20the%20layer%20that%20makes%20LLM%20systems%20cheap%20to%20run%20and%20easy%20to%20inspect&descAlignY=52&descSize=16&animation=fadeIn" alt="header"/>

<p align="center">
  <a href="https://github.com/DenverCoder1/readme-typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3200&pause=900&color=8B5CF6&center=true&vCenter=true&width=620&lines=Senior+AI%2FML+Engineer+%C2%B7+10%2B+years;8+PyPI+packages+%C2%B7+18%2C796+downloads;8+VS+Code+extensions+%C2%B7+5%2C078+installs;Agentic+AI+%C2%B7+RAG+%C2%B7+LLM+fine-tuning;I+ship+the+boring+parts+that+make+agents+reliable" alt="Typing SVG"/>
  </a>
</p>

<p align="center">
  <a href="https://pypi.org/user/karthyick/"><img src="https://img.shields.io/badge/PyPI-18%2C796%20downloads-3775A9?style=for-the-badge&logo=pypi&logoColor=white&labelColor=2b5b8c" alt="PyPI"/></a>
  <a href="https://marketplace.visualstudio.com/publishers/krextensions"><img src="https://img.shields.io/badge/VS%20Code-5%2C078%20installs-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white&labelColor=005a99" alt="VS Code"/></a>
  <a href="https://github.com/karthyick?tab=followers"><img src="https://custom-icon-badges.demolab.com/github/followers/karthyick?color=8b5cf6&labelColor=6d28d9&style=for-the-badge&logo=person-add&label=Follow&logoColor=white" alt="Followers"/></a>
  <a href="https://github.com/karthyick?tab=repositories&sort=stargazers"><img src="https://custom-icon-badges.demolab.com/github/stars/karthyick?color=10b981&labelColor=047857&style=for-the-badge&logo=star&logoColor=white" alt="Stars"/></a>
  <img src="https://komarev.com/ghpvc/?username=karthyick&style=for-the-badge&color=8b5cf6&label=VIEWS" alt="Views"/>
</p>

<h3 align="center">🧠 Eight packages. One thesis.</h3>

<p align="center">
  <samp>An agent loop leaks tokens at every stage, and none of those stages is observable by default.<br/>
  Each package below is one stage made cheap, or made visible — and they compose.</samp>
</p>

```mermaid
flowchart LR
  A["1 · shrink what goes in<br/>context-rainbow · distill-json · rubricon<br/>route only relevant knowledge, compress<br/>the payload, spec before generating"]
  B["2 · don't call twice<br/>semantic-llm-cache<br/>cache by meaning, not by string"]
  C["3 · run it the same way twice<br/>auto-any · langgraph-crosschain<br/>deterministic runs, replayable receipts,<br/>node-to-node across chains"]
  D["4 · keep what happened<br/>tracemaid · clinotes<br/>traces become diagrams, decisions<br/>become git-native memory"]

  A --> B --> C --> D
  D -.->|the next task starts warmer| A

  style A fill:#ede9fe,stroke:#8b5cf6,stroke-width:2px,color:#1f2937
  style B fill:#ede9fe,stroke:#8b5cf6,stroke-width:2px,color:#1f2937
  style C fill:#ede9fe,stroke:#8b5cf6,stroke-width:2px,color:#1f2937
  style D fill:#d1fae5,stroke:#10b981,stroke-width:2px,color:#1f2937
```

<p align="center"><samp>The dotted edge is the point — most agent stacks throw the run away; this one feeds it back.</samp></p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8b5cf6,100:10b981&height=3&section=header" alt=""/>

<h3 align="center">📦 Published work</h3>

<details open>
<summary><b>🐍 PyPI — 8 packages · 18,796 downloads</b></summary>
<br/>

| Package | What it does | Version | Downloads |
|---|---|---|---|
| [**tracemaid**](https://pypi.org/project/tracemaid/) · [src](https://github.com/karthyick/tracemaid) | OpenTelemetry traces → Mermaid diagrams you can actually read | ![v](https://img.shields.io/pypi/v/tracemaid?style=flat-square&color=8b5cf6&label=) | `4,442` |
| [**rubricon**](https://pypi.org/project/rubricon/) | Specification-first generation — write the rubric, *then* generate against it | ![v](https://img.shields.io/pypi/v/rubricon?style=flat-square&color=8b5cf6&label=) | `4,198` |
| [**distill-json**](https://pypi.org/project/distill-json/) · [src](https://github.com/karthyick/DISTILL) | Lossless JSON compression for LLM payloads — 60-85% token reduction, 6.6× ratio | ![v](https://img.shields.io/pypi/v/distill-json?style=flat-square&color=8b5cf6&label=) | `2,974` |
| [**semantic-llm-cache**](https://pypi.org/project/semantic-llm-cache/) · [src](https://github.com/karthyick/prompt-cache) | Cache by *meaning*, not by string — one decorator, 20-40% of calls never leave | ![v](https://img.shields.io/pypi/v/semantic-llm-cache?style=flat-square&color=8b5cf6&label=) | `2,378` |
| [**clinotes**](https://pypi.org/project/clinotes/) · [src](https://github.com/karthyick/clinotes) | Git-native project memory for coding agents — decisions as Markdown, MCP-ready | ![v](https://img.shields.io/pypi/v/clinotes?style=flat-square&color=8b5cf6&label=) | `1,752` |
| [**auto-any**](https://pypi.org/project/auto-any/) | Browser and task automation that replays — every run is a signed receipt | ![v](https://img.shields.io/pypi/v/auto-any?style=flat-square&color=8b5cf6&label=) | `1,473` |
| [**langgraph-crosschain**](https://pypi.org/project/langgraph-crosschain/) · [src](https://github.com/karthyick/langgraph-crosschain) | Direct node-to-node communication across separate LangGraph chains | ![v](https://img.shields.io/pypi/v/langgraph-crosschain?style=flat-square&color=8b5cf6&label=) | `1,093` |
| [**context-rainbow**](https://pypi.org/project/context-rainbow/) · [src](https://github.com/karthyick/context-rainbow) | Color-aware context routing — progressive knowledge loading, not bulk stuffing | ![v](https://img.shields.io/pypi/v/context-rainbow?style=flat-square&color=8b5cf6&label=) | `486` |

<sub>Eight releases between Nov 2025 and Aug 2026. Version badges are live; download totals are cumulative, refreshed from pypistats.</sub>

</details>

<details>
<summary><b>🧩 VS Code Marketplace — 8 extensions · 5,078 installs</b></summary>
<br/>

| Extension | What it does | Installs |
|---|---|---|
| [**Python Venv Activator**](https://marketplace.visualstudio.com/items?itemName=krextensions.venv-activator) | Activates the right venv the moment you open the folder | `2,644` |
| [**Code to Flowchart**](https://marketplace.visualstudio.com/items?itemName=krextensions.code-to-flowchart) | Turns the function under your cursor into an interactive flowchart | `2,243` |
| [Code2Summarize](https://marketplace.visualstudio.com/items?itemName=krextensions.code2summarize) · [Code2PR](https://marketplace.visualstudio.com/items?itemName=krextensions.code2pr) · [Code2Assist](https://marketplace.visualstudio.com/items?itemName=krextensions.code2assist) · [Folder Structure Creator](https://marketplace.visualstudio.com/items?itemName=krextensions.folder-structure-creator) · [Shared Venv Activator](https://marketplace.visualstudio.com/items?itemName=krextensions.shared-venv-activator) · [Package to Flowchart](https://marketplace.visualstudio.com/items?itemName=krextensions.package-to-flowchart) | Six smaller editor tools | `191` |

</details>

<details>
<summary><b>🔬 Research & models</b></summary>
<br/>

**[Evaluation-First Attention](https://github.com/karthyick/evaluation-first-attention)** — specification-driven generation
via dynamic rubric conditioning and failure-weighted reattention. Instead of generating and then scoring, the rubric is
produced first and conditions the generation itself. `rubricon` is the reference implementation.

**[llm_tinystories](https://github.com/karthyick/llm_tinystories)** — a 24.5M-parameter Transformer trained from scratch:
custom 10K-vocab tokenizer, 8.65 perplexity, 100% article-generation accuracy. Trained locally on an RTX 5090 — the point
was proving how far a *small* model gets on a well-shaped domain.

**Domain SLM distillation** — compressing large general models into small domain-specific ones. Same thesis as the
packages: get the same answer for less.

</details>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:10b981,100:8b5cf6&height=3&section=header" alt=""/>

<h3 align="center">🛠️ Stack</h3>

<p align="center"><sub><b>AI / ML</b></sub></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,anaconda&theme=dark" alt="ai"/>
</p>

<p align="center"><sub><b>Backend · Data · Cloud</b></sub></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=fastapi,flask,dotnet,nodejs,postgres,redis,mongodb,docker,kubernetes,azure,aws&perline=11&theme=dark" alt="backend"/>
</p>

<p align="center"><sub><b>Frontend · Tooling</b></sub></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=react,ts,tailwind,threejs,git,github,githubactions,vscode,linux,powershell&perline=10&theme=dark" alt="frontend"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt=""/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white" alt=""/>
  <img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white" alt=""/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt=""/>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt=""/>
  <img src="https://img.shields.io/badge/PEFT%20·%20LoRA%20·%20QLoRA-8b5cf6?style=flat-square" alt=""/>
  <img src="https://img.shields.io/badge/FAISS%20·%20pgvector%20·%20Chroma-10b981?style=flat-square" alt=""/>
  <img src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white" alt=""/>
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" alt=""/>
  <img src="https://img.shields.io/badge/W%26B-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black" alt=""/>
</p>

<p align="center"><sub>Certified: Azure AZ-900 · AI-900 · DP-900 · PL-900 · Executive PG in AI &amp; ML</sub></p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8b5cf6,100:10b981&height=3&section=header" alt=""/>

<h3 align="center">📊 By the numbers</h3>

<p align="center">
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api?username=karthyick&show_icons=true&include_all_commits=true&hide_border=true&theme=radical&bg_color=0d1117&title_color=8b5cf6&icon_color=10b981" alt="stats"/>
  <img height="165" src="https://streak-stats.demolab.com/?user=karthyick&theme=radical&hide_border=true&background=0d1117&ring=8b5cf6&fire=10b981&currStreakLabel=8b5cf6" alt="streak"/>
</p>

<h3 align="center">🐍 Watch the snake eat my contributions</h3>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/karthyick/karthyick/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/karthyick/karthyick/output/github-snake.svg"/>
    <img alt="contribution snake" src="https://raw.githubusercontent.com/karthyick/karthyick/output/github-snake.svg"/>
  </picture>
</p>

<h3 align="center">🏙️ A year of commits, in 3D</h3>

<p align="center">
  <img width="90%" src="./profile-3d-contrib/profile-night-rainbow.svg" alt="3D contribution calendar"/>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:10b981,100:8b5cf6&height=3&section=header" alt=""/>

<h3 align="center">📫 Find me</h3>

<p align="center">
  <a href="https://karthyick.github.io"><img src="https://img.shields.io/badge/Portfolio-8b5cf6?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/karthick-raja-mohan-753431123/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:karthickrajam18@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://aichargeworks.com"><img src="https://img.shields.io/badge/aichargeworks.com-10b981?style=for-the-badge&logo=rocket&logoColor=white" alt="Lab"/></a>
</p>

<p align="center">
  <samp>📍 Chennai, India · Lead AI/ML Engineer @ Appian<br/>
  <a href="https://aichargeworks.com">aichargeworks.com</a> is my R&amp;D lab — everything above gets tried there first.</samp>
</p>

<p align="center">
  <samp>Happy to talk about agent reliability, token economics, small-model training,<br/>or anything above that you think is wrong.</samp>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:10b981,50:6366f1,100:8b5cf6&height=120&section=footer" alt="footer"/>
