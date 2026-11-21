<div align="center">

<a href="https://dusk.fm">
  <img src="./assets/dusk-banner.webp" alt="Dusk, the AI live entertainment director" width="640" />
</a>

# David Engelmann

### Senior Software Engineer

**AI&nbsp;Agents&nbsp;·&nbsp;Data&nbsp;Platform · Full&nbsp;Stack&nbsp;·&nbsp;Rust**

I build AI products end to end:<br>
the agents, the infrastructure and data systems underneath, and the apps on top.<br>
At [Dusk](https://dusk.fm) I lead work on the data and agent&nbsp;platform.

[![At Dusk](https://img.shields.io/badge/At-Dusk-EC690D?style=flat-square&labelColor=0D1117)](https://dusk.fm)
[![Formerly Satisfi Labs](https://img.shields.io/badge/Formerly-Satisfi%20Labs-FF3222?style=flat-square&labelColor=0D1117)](https://satisfilabs.com)
[![David Engelmann on LinkedIn](https://img.shields.io/badge/On-LinkedIn-0A66C2?style=flat-square&labelColor=0D1117)](https://www.linkedin.com/in/david-engelmann-217817110)

</div>

---

### Featured projects

<p align="center">
  <a href="https://maidan.world"><img src="./assets/maidan-board.gif" alt="The maidan board: a task is filed, claimed by an agent, reviewed by another, and moved to Done" width="400" /></a>
  &nbsp;
  <a href="https://peiratrial.dev"><img src="./assets/peira-board.png" alt="The peira results board: Decision models, measured under attack" width="400" /></a>
</p>

- **[maidan](https://github.com/david-engelmann/maidan)** is the shared workspace where AI agents and people work together. Channels and threads, tasks with one holder each, and review by someone other than the author. One repo holds every layer: a Rust server that speaks MCP and A2A, a web UI, a Helm chart, and SDKs in Python, TypeScript, Go, and Rust. Bring Claude&nbsp;Code, Codex, Cursor, or your own agent. Hosted at [maidan.world](https://maidan.world), with a [live demo](https://try.maidan.world) and [docs](https://docs.maidan.world).

- **[peira](https://github.com/david-engelmann/peira)** is an AI safety benchmark for decision models. Every case runs twice, once clean and once under attack, and peira measures how often the attack flips a right answer. Results for more than 50 models are live at [peiratrial.dev](https://peiratrial.dev), and no model on the board is&nbsp;immune.

- **[atproto](https://github.com/david-engelmann/atproto)** is a typed OCaml client for the AT&nbsp;Protocol, the open protocol behind Bluesky. It resolves identities, reads and writes repositories, follows the firehose, and handles&nbsp;OAuth.<br>
  `opam install atproto`

### What I work on

[Dusk](https://dusk.fm) is the AI live entertainment director, a platform for booking, managing, and promoting live entertainment. Before Dusk, I worked on conversational AI and NLP at [Satisfi&nbsp;Labs](https://satisfilabs.com). The same areas run through my open source work. Each row below links to&nbsp;examples.

- **AI agents.** Reliable agent loops on top of LLMs. Tool design, MCP servers, retrieval, evaluation, and the rest of the work that sits between a demo and something you'd actually&nbsp;ship.<br>
  [`maidan`](https://github.com/david-engelmann/maidan)&ensp;[`switchyard`](https://github.com/david-engelmann/switchyard)&ensp;[`dibs`](https://github.com/david-engelmann/dibs)&nbsp;&nbsp;[`wayside`](https://github.com/david-engelmann/wayside)

- **Data and distributed systems.** The storage layer that agents and services depend on. Raft consensus, write-ahead logs, deterministic simulation testing, and DataFusion query engines over Delta&nbsp;Lake.<br>
  [`simraft-kv`](https://github.com/david-engelmann/simraft-kv)&ensp;[`chronicle-lob`](https://github.com/david-engelmann/chronicle-lob)&ensp;[`verirun`](https://github.com/david-engelmann/verirun)

- **Product engineering.** The apps on top. React&nbsp;Native and Expo for iOS and Android, Next.js on the web, and GraphQL&nbsp;APIs&nbsp;in&nbsp;between.<br>
  [`dusk.fm`](https://dusk.fm)

- **Automated code systems.** Hardened sandboxes for coding agents to run in. Allowlisted egress, policy-brokered container access, supervisor SDKs, and reference solver / verifier / refiner&nbsp;loops.<br>
  [`portcullis`](https://github.com/david-engelmann/portcullis)&ensp;[`mayfly`](https://github.com/david-engelmann/mayfly)&ensp;[`deadbolt`](https://github.com/david-engelmann/deadbolt)&nbsp;&nbsp;[`arvin`](https://github.com/david-engelmann/arvin)

- **Developer tooling.** Bridges between agents and the rest of an engineer's stack. Debuggers over DAP/MCP, terminal automation, PR evidence pipelines, multi-agent&nbsp;workbenches.<br>
  [`recognitio`](https://github.com/david-engelmann/recognitio)<br>
  16 merged pull requests upstream:<br>
  [`warp`](https://github.com/warpdotdev/warp/pulls?q=is%3Apr+is%3Amerged+author%3Adavid-engelmann)&ensp;[`helmor`](https://github.com/dohooo/helmor/pulls?q=is%3Apr+is%3Amerged+author%3Adavid-engelmann)&ensp;[`doccano-client`](https://github.com/doccano/doccano-client/pulls?q=is%3Apr+is%3Amerged+author%3Adavid-engelmann)

- **Libraries.** Typed clients and Rust-backed Python packages. An OCaml client for the AT&nbsp;Protocol on opam, and PyO3 libraries on&nbsp;PyPI.<br>
  [`atproto`](https://github.com/david-engelmann/atproto)&ensp;[`placekit`](https://github.com/david-engelmann/placekit)&ensp;[`youtube_stats`](https://github.com/beatgig/youtube_stats)&ensp;[`soundcloud_stats`](https://github.com/beatgig/soundcloud_stats)&nbsp;&nbsp;[`meta_stats`](https://github.com/beatgig/meta_stats)

- **Evaluation.** Benchmarks for how models fail under prompt injection and data&nbsp;poisoning.<br>
  [`peira`](https://github.com/david-engelmann/peira)&ensp;[`wyrd`](https://github.com/david-engelmann/wyrd)

### Skills

Rust, Python, and TypeScript are my daily languages. Everything I work with is grouped&nbsp;below.

<p>
  <b>Languages</b><br>
  <img src="https://img.shields.io/badge/Rust-CE422B?style=flat-square&labelColor=0D1117&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&labelColor=0D1117&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&labelColor=0D1117&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Go-0095BA?style=flat-square&labelColor=0D1117&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&labelColor=0D1117&logo=gnubash&logoColor=white" alt="Bash" />
  <img src="https://img.shields.io/badge/OCaml-EC6813?style=flat-square&labelColor=0D1117&logo=ocaml&logoColor=white" alt="OCaml" />
  <img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&labelColor=0D1117&logo=swift&logoColor=white" alt="Swift" />
  <img src="https://img.shields.io/badge/Lua-6465C3?style=flat-square&labelColor=0D1117&logo=lua&logoColor=white" alt="Lua" />
  <img src="https://img.shields.io/badge/C-708CAB?style=flat-square&labelColor=0D1117&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&labelColor=0D1117&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&labelColor=0D1117&logo=dotnet&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/Julia-9558B2?style=flat-square&labelColor=0D1117&logo=julia&logoColor=white" alt="Julia" />
</p>

<p>
  <b>AI and agents</b><br>
  <img src="https://img.shields.io/badge/MCP-8B5CF6?style=flat-square&labelColor=0D1117&logo=modelcontextprotocol&logoColor=white" alt="MCP (Model Context Protocol)" />
  <img src="https://img.shields.io/badge/A2A-4285F4?style=flat-square&labelColor=0D1117&logo=google&logoColor=white" alt="A2A (Agent2Agent protocol)" />
  <img src="https://img.shields.io/badge/ACP-6366F1?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="ACP (Agent Client Protocol)" />
  <img src="https://img.shields.io/badge/LLM%20agents-7C3AED?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="LLM agents" />
  <img src="https://img.shields.io/badge/Agent%20evals-B45309?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="Agent evals" />
  <img src="https://img.shields.io/badge/OpenAI%20API-57606A?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="OpenAI API" />
  <img src="https://img.shields.io/badge/Anthropic%20API-D97757?style=flat-square&labelColor=0D1117&logo=anthropic&logoColor=white" alt="Anthropic API" />
  <img src="https://img.shields.io/badge/Vector%20search-0F766E?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="Vector search" />
  <img src="https://img.shields.io/badge/Rig-CE422B?style=flat-square&labelColor=0D1117&logo=rust&logoColor=white" alt="Rig" />
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&labelColor=0D1117&logo=claude&logoColor=white" alt="Claude Code" />
  <img src="https://img.shields.io/badge/pgvector-336791?style=flat-square&labelColor=0D1117&logo=postgresql&logoColor=white" alt="pgvector" />
  <img src="https://img.shields.io/badge/LiteLLM-0C92CE?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="LiteLLM" />
  <img src="https://img.shields.io/badge/Gemini%20API-8E75B2?style=flat-square&labelColor=0D1117&logo=googlegemini&logoColor=white" alt="Gemini API" />
  <img src="https://img.shields.io/badge/Vercel%20AI%20SDK-57606A?style=flat-square&labelColor=0D1117&logo=vercel&logoColor=white" alt="Vercel AI SDK" />
  <img src="https://img.shields.io/badge/RAG-0F766E?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="RAG (retrieval-augmented generation)" />
</p>

<p>
  <b>Backend and APIs</b><br>
  <img src="https://img.shields.io/badge/Tokio-CE422B?style=flat-square&labelColor=0D1117&logo=rust&logoColor=white" alt="Tokio" />
  <img src="https://img.shields.io/badge/Axum-CE422B?style=flat-square&labelColor=0D1117&logo=rust&logoColor=white" alt="Axum" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&labelColor=0D1117&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=flat-square&labelColor=0D1117&logo=graphql&logoColor=white" alt="GraphQL" />
  <img src="https://img.shields.io/badge/gRPC-244C5A?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="gRPC" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&labelColor=0D1117&logo=pydantic&logoColor=white" alt="Pydantic" />
  <img src="https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&labelColor=0D1117&logo=webassembly&logoColor=white" alt="WebAssembly" />
  <img src="https://img.shields.io/badge/Protobuf-4285F4?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="Protobuf" />
  <img src="https://img.shields.io/badge/PyO3-3776AB?style=flat-square&labelColor=0D1117&logo=python&logoColor=white" alt="PyO3" />
  <img src="https://img.shields.io/badge/REST%20APIs-57606A?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="REST APIs" />
  <img src="https://img.shields.io/badge/WebSocket-57606A?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="WebSocket" />
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&labelColor=0D1117&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/OpenAPI-6BA539?style=flat-square&labelColor=0D1117&logo=openapiinitiative&logoColor=white" alt="OpenAPI" />
  <img src="https://img.shields.io/badge/Stripe%20API-635BFF?style=flat-square&labelColor=0D1117&logo=stripe&logoColor=white" alt="Stripe API" />
  <img src="https://img.shields.io/badge/Slack%20API-7C3085?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="Slack API" />
</p>

<p>
  <b>Data</b><br>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&labelColor=0D1117&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Delta%20Lake-0095BA?style=flat-square&labelColor=0D1117&logo=databricks&logoColor=white" alt="Delta Lake" />
  <img src="https://img.shields.io/badge/DataFusion-E26300?style=flat-square&labelColor=0D1117&logo=apache&logoColor=white" alt="DataFusion" />
  <img src="https://img.shields.io/badge/Arrow-0B5394?style=flat-square&labelColor=0D1117&logo=apachearrow&logoColor=white" alt="Arrow" />
  <img src="https://img.shields.io/badge/Raft-1F6FEB?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="Raft" />
  <img src="https://img.shields.io/badge/SQLx-CE422B?style=flat-square&labelColor=0D1117&logo=rust&logoColor=white" alt="SQLx" />
  <img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&labelColor=0D1117&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="SQLAlchemy" />
  <img src="https://img.shields.io/badge/Kafka-57606A?style=flat-square&labelColor=0D1117&logo=apachekafka&logoColor=white" alt="Kafka" />
  <img src="https://img.shields.io/badge/Parquet-138DEA?style=flat-square&labelColor=0D1117&logo=apacheparquet&logoColor=white" alt="Parquet" />
  <img src="https://img.shields.io/badge/Typesense-D52B88?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="Typesense" />
  <img src="https://img.shields.io/badge/Alembic-6BA81E?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="Alembic" />
  <img src="https://img.shields.io/badge/pandas-E70488?style=flat-square&labelColor=0D1117&logo=pandas&logoColor=white" alt="pandas" />
  <img src="https://img.shields.io/badge/SQLite-0F80CC?style=flat-square&labelColor=0D1117&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Polars-0075FF?style=flat-square&labelColor=0D1117&logo=polars&logoColor=white" alt="Polars" />
  <img src="https://img.shields.io/badge/PostGIS-336791?style=flat-square&labelColor=0D1117&logo=postgresql&logoColor=white" alt="PostGIS" />
  <img src="https://img.shields.io/badge/S3-569A31?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="S3" />
</p>

<p>
  <b>Frontend and mobile</b><br>
  <img src="https://img.shields.io/badge/React%20Native-087EA4?style=flat-square&labelColor=0D1117&logo=react&logoColor=white" alt="React Native" />
  <img src="https://img.shields.io/badge/Expo-57606A?style=flat-square&labelColor=0D1117&logo=expo&logoColor=white" alt="Expo" />
  <img src="https://img.shields.io/badge/EAS-57606A?style=flat-square&labelColor=0D1117&logo=expo&logoColor=white" alt="EAS (Expo Application Services)" />
  <img src="https://img.shields.io/badge/Tamagui-EC4899?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="Tamagui" />
  <img src="https://img.shields.io/badge/React-087EA4?style=flat-square&labelColor=0D1117&logo=react&logoColor=white" alt="React" />
  <img src="https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat-square&labelColor=0D1117&logo=reactquery&logoColor=white" alt="TanStack Query" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&labelColor=0D1117&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Next.js-57606A?style=flat-square&labelColor=0D1117&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Zustand-8A5A2B?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="Zustand" />
  <img src="https://img.shields.io/badge/Storybook-FF4785?style=flat-square&labelColor=0D1117&logo=storybook&logoColor=white" alt="Storybook" />
  <img src="https://img.shields.io/badge/Leptos-EF3939?style=flat-square&labelColor=0D1117&logo=leptos&logoColor=white" alt="Leptos" />
  <img src="https://img.shields.io/badge/Tauri-1B97A3?style=flat-square&labelColor=0D1117&logo=tauri&logoColor=white" alt="Tauri" />
</p>

<p>
  <b>Infrastructure, CI/CD, and observability</b><br>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&labelColor=0D1117&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&labelColor=0D1117&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&labelColor=0D1117&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/Kustomize-326CE5?style=flat-square&labelColor=0D1117&logo=kubernetes&logoColor=white" alt="Kustomize" />
  <img src="https://img.shields.io/badge/Porter-5B5BD6?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="Porter" />
  <img src="https://img.shields.io/badge/Cloudflare%20Workers-DA690C?style=flat-square&labelColor=0D1117&logo=cloudflareworkers&logoColor=white" alt="Cloudflare Workers" />
  <img src="https://img.shields.io/badge/Helm-555EEC?style=flat-square&labelColor=0D1117&logo=helm&logoColor=white" alt="Helm" />
  <img src="https://img.shields.io/badge/AWS-C57600?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Nix-5277C3?style=flat-square&labelColor=0D1117&logo=nixos&logoColor=white" alt="Nix" />
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&labelColor=0D1117&logo=googlecloud&logoColor=white" alt="Google Cloud" />
  <img src="https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&labelColor=0D1117&logo=firebase&logoColor=white" alt="Firebase" />
  <img src="https://img.shields.io/badge/Vercel-57606A?style=flat-square&labelColor=0D1117&logo=vercel&logoColor=white" alt="Vercel" />
  <img src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&labelColor=0D1117&logo=opentelemetry&logoColor=white" alt="OpenTelemetry" />
  <img src="https://img.shields.io/badge/tracing-CE422B?style=flat-square&labelColor=0D1117&logo=rust&logoColor=white" alt="tracing" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&labelColor=0D1117&logo=prometheus&logoColor=white" alt="Prometheus" />
  <img src="https://img.shields.io/badge/Tempo-F46800?style=flat-square&labelColor=0D1117&logo=grafana&logoColor=white" alt="Tempo" />
  <img src="https://img.shields.io/badge/Loki-F46800?style=flat-square&labelColor=0D1117&logo=grafana&logoColor=white" alt="Loki" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&labelColor=0D1117&logo=grafana&logoColor=white" alt="Grafana" />
  <img src="https://img.shields.io/badge/Sentry-6C5FC7?style=flat-square&labelColor=0D1117&logo=sentry&logoColor=white" alt="Sentry" />
  <img src="https://img.shields.io/badge/PostHog-1D4AFF?style=flat-square&labelColor=0D1117&logo=posthog&logoColor=white" alt="PostHog" />
</p>

<p>
  <b>Testing and developer tools</b><br>
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&labelColor=0D1117&logo=pytest&logoColor=white" alt="pytest" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="Playwright" />
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&labelColor=0D1117&logo=vitest&logoColor=white" alt="Vitest" />
  <img src="https://img.shields.io/badge/proptest-CE422B?style=flat-square&labelColor=0D1117&logo=rust&logoColor=white" alt="proptest" />
  <img src="https://img.shields.io/badge/Simulation%20testing-0F766E?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="Deterministic simulation testing" />
  <img src="https://img.shields.io/badge/TLA%2B-1F6FEB?style=flat-square&labelColor=0D1117&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNSIgZmlsbD0id2hpdGUiLz48L3N2Zz4%3D&logoColor=white" alt="TLA+" />
  <img src="https://img.shields.io/badge/Kani-CE422B?style=flat-square&labelColor=0D1117&logo=rust&logoColor=white" alt="Kani" />
  <img src="https://img.shields.io/badge/loom-CE422B?style=flat-square&labelColor=0D1117&logo=rust&logoColor=white" alt="loom" />
  <img src="https://img.shields.io/badge/cargo--fuzz-CE422B?style=flat-square&labelColor=0D1117&logo=rust&logoColor=white" alt="cargo-fuzz" />
  <img src="https://img.shields.io/badge/cargo--mutants-CE422B?style=flat-square&labelColor=0D1117&logo=rust&logoColor=white" alt="cargo-mutants" />
  <img src="https://img.shields.io/badge/CLI%20tools-CE422B?style=flat-square&labelColor=0D1117&logo=rust&logoColor=white" alt="CLI tools" />
  <img src="https://img.shields.io/badge/Ruff-5C8A0A?style=flat-square&labelColor=0D1117&logo=ruff&logoColor=white" alt="Ruff" />
  <img src="https://img.shields.io/badge/uv-DE5FE9?style=flat-square&labelColor=0D1117&logo=uv&logoColor=white" alt="uv" />
  <img src="https://img.shields.io/badge/Poetry-3B82F6?style=flat-square&labelColor=0D1117&logo=poetry&logoColor=white" alt="Poetry" />
  <img src="https://img.shields.io/badge/Neovim-57A143?style=flat-square&labelColor=0D1117&logo=neovim&logoColor=white" alt="Neovim" />
  <img src="https://img.shields.io/badge/Warp-008FDF?style=flat-square&labelColor=0D1117&logo=warp&logoColor=white" alt="Warp" />
</p>

<details>
<summary><sub>Skills as plain text</sub></summary>
<br>

<b>Languages:</b> Rust, Python, TypeScript, Go, SQL, Bash, OCaml, Swift, Lua, C, C++, C#, Julia<br>
<b>AI and agents:</b> MCP (Model Context Protocol), A2A (Agent2Agent protocol), ACP (Agent Client Protocol), LLM agents, Agent evals, OpenAI API, Anthropic API, Vector search, Rig, Claude Code, pgvector, LiteLLM, Gemini API, Vercel AI SDK, RAG (retrieval-augmented generation)<br>
<b>Backend and APIs:</b> Tokio, Axum, FastAPI, GraphQL, gRPC, Pydantic, WebAssembly, Protobuf, PyO3, REST APIs, WebSocket, Node.js, OpenAPI, Stripe API, Slack API<br>
<b>Data:</b> PostgreSQL, Delta Lake, DataFusion, Arrow, Raft, SQLx, Redis, SQLAlchemy, Kafka, Parquet, Typesense, Alembic, pandas, SQLite, Polars, PostGIS, S3<br>
<b>Frontend and mobile:</b> React Native, Expo, EAS (Expo Application Services), Tamagui, React, TanStack Query, Vite, Next.js, Zustand, Storybook, Leptos, Tauri<br>
<b>Infrastructure, CI/CD, and observability:</b> Docker, GitHub Actions, Kubernetes, Kustomize, Porter, Cloudflare Workers, Helm, AWS, Nix, Google Cloud, Firebase, Vercel, OpenTelemetry, tracing, Prometheus, Tempo, Loki, Grafana, Sentry, PostHog<br>
<b>Testing and developer tools:</b> pytest, Playwright, Vitest, proptest, Deterministic simulation testing, TLA+, Kani, loom, cargo-fuzz, cargo-mutants, CLI tools, Ruff, uv, Poetry, Neovim, Warp

</details>

---

I prefer open source and try to help where I can. Pinned repos below for a current slice. Off the keyboard, I'm usually outside. All my toasters are&nbsp;analog.

<sub><sup>Optimally, someone pays me to do analysis on Bob Dylan and Grateful&nbsp;Dead&nbsp;songs.</sup></sub>
