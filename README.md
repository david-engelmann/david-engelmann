<div align="center">

<a href="https://dusk.fm">
  <img src="./assets/dusk-banner.webp" alt="Dusk, the AI live entertainment director" width="640" />
</a>

# David Engelmann

**Senior Software Engineer · Agent Infrastructure · Adversarial Evals · Rust**

Building the systems language models need to do engineering, and the benchmarks that measure how they fail under attack.<br>
Sandboxed coding agents, multi-agent orchestrators, MCP servers, and the infrastructure that holds them up.

[![At Dusk](https://img.shields.io/badge/At-Dusk-EC690D?style=flat-square&labelColor=0D1117)](https://dusk.fm)
[![Formerly Satisfi Labs](https://img.shields.io/badge/Formerly-Satisfi%20Labs-FF3222?style=flat-square&labelColor=0D1117)](https://satisfilabs.com)
[![David Engelmann on LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=0D1117)](https://www.linkedin.com/in/david-engelmann-217817110)

</div>

---

### What I work on

Currently at [Dusk](https://dusk.fm), the AI live entertainment director. I lead work on the data and agent platform behind it. Before Dusk, I worked on conversational AI and NLP at [Satisfi Labs](https://satisfilabs.com). The same work runs in the open, and the projects below are where to see it.

**AI agents.** Reliable agent loops on top of LLMs. Tool design, MCP servers, retrieval, evaluation, and the rest of the work that sits between a demo and something you'd actually ship.

- **[maidan](https://github.com/david-engelmann/maidan)** is the shared workspace where AI agents and people work together: channels and threads, tasks with one holder each, and review by someone other than the author. Hosted at [maidan.world](https://maidan.world), or run it yourself.
- [switchyard](https://github.com/david-engelmann/switchyard) gives parallel agents isolated worktrees, [dibs](https://github.com/david-engelmann/dibs) lets them share one backlog through expiring leases, and [wayside](https://github.com/david-engelmann/wayside) checkpoints a session so a run can resume, fork, or rewind.

**Automated code systems.** Hardened sandboxes for coding agents to run in. Allowlisted egress, policy-brokered container access, supervisor SDKs, and reference solver / verifier / refiner loops.

- [portcullis](https://github.com/david-engelmann/portcullis) firewalls an agent's tool calls, [mayfly](https://github.com/david-engelmann/mayfly) runs a command in a throwaway directory with a scrubbed environment and the network off, and [deadbolt](https://github.com/david-engelmann/deadbolt) brokers secrets so the real key never touches the agent process.

**Developer tooling.** Bridges between agents and the rest of an engineer's stack. Debuggers over DAP/MCP, terminal automation, PR evidence pipelines, multi-agent workbenches.

- **[recognitio](https://github.com/david-engelmann/recognitio)** pulls a pull request or commit range into one verified review packet, so a reviewer and the agents helping them start from evidence instead of a bare diff.
- Merged pull requests upstream in [Warp](https://github.com/warpdotdev/warp/pulls?q=is%3Apr+is%3Amerged+author%3Adavid-engelmann), [Helmor](https://github.com/dohooo/helmor/pulls?q=is%3Apr+is%3Amerged+author%3Adavid-engelmann), and the [doccano client](https://github.com/doccano/doccano-client/pulls?q=is%3Apr+is%3Amerged+author%3Adavid-engelmann).

**Adversarial evals.** Benchmarks that measure how models fail under hostile input and poisoned data.

- **[peira](https://github.com/david-engelmann/peira)** is an adversarial benchmark for decision models. Every case runs twice, once clean and once under attack, and peira measures how often the attack flips a right answer. Results for more than 50 models are live at [peiratrial.dev](https://peiratrial.dev), and every one of them flips under attack.
- **[wyrd](https://github.com/david-engelmann/wyrd)** is a benchmark for data poisoning. It measures how few planted samples it takes to warp a model, across training data, knowledge bases, and graphs.

**Libraries and systems.** Typed clients and deterministic Rust.

- **[atproto](https://github.com/david-engelmann/atproto)** is a typed OCaml client for the AT Protocol, the network behind Bluesky. `opam install atproto`
- **[placekit](https://github.com/david-engelmann/placekit)** is a Python client for the Google Places API (New) on a Rust core. `pip install placekit`
- **[chronicle-lob](https://github.com/david-engelmann/chronicle-lob)** is a deterministic limit order book and matching engine, **[simraft-kv](https://github.com/david-engelmann/simraft-kv)** is a Raft key-value store built for simulation testing, and **[verirun](https://github.com/david-engelmann/verirun)** is a content-addressed execution runner.

---

**Languages.** Rust, Python, TypeScript, OCaml, Julia, C, C++, C#, Lua.<br>
**Tools and runtimes.** MCP, Tokio, Axum, DataFusion, Delta Lake, Docker, Kafka, GraphQL, Cloudflare, Neovim.

---

I prefer open source and try to help where I can. Pinned repos below for a current slice. Off the keyboard, I'm usually outside. All my toasters are analog.

<sub><sup>Optimally, someone pays me to do analysis on Bob Dylan and Grateful Dead songs.</sup></sub>
