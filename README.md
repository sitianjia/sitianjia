<div align="center">

# Ma Xiaoming

*Applied AI researcher. Most of my work lives in the gap between agent demos and agents that don't fall over on Friday night.*

![Shanghai](https://img.shields.io/badge/Shanghai-China-red?style=for-the-badge)
![focus](https://img.shields.io/badge/focus-agent_deployment-blueviolet?style=for-the-badge)

</div>

---

## What I work on

LLM agents in production — the part nobody tweets about. Picking the right tools out of fifty. Evaluating tool-use without LLM-judge wash. Recording traces that survive a postmortem. Building flows you can resume after a worker dies on step 7.

The four repos pinned here are pieces of the same picture: how to take an agent from "works in a notebook" to "shipped, observable, and debuggable".

## What I'm thinking about

- Why "demo-good" and "prod-good" are different problems, and how the gap shows up empirically
- Cheap routing layers that protect the LLM from its own option-explosion problem
- Trace formats that one engineer can read and one machine can grep
- Checkpointing patterns for agents whose tool calls cost real money

## Tools I keep reaching for

`Python` &middot; `PyTorch` &middot; `vLLM` &middot; `OpenAI / Anthropic / Qwen` SDKs &middot; `Pydantic` &middot; `pytest` &middot; `Jinja2` &middot; `Rich` &middot; `Docker` &middot; `tmux` &middot; a stubborn refusal to add a database

## Pinned

- [`agent-eval-kit`](https://github.com/sitianjia/agent-eval-kit) — YAML cases, replayable traces, deterministic checks for tool-using agents
- [`tool-router`](https://github.com/sitianjia/tool-router) — pick K tools before they ever hit the LLM
- [`agent-tape`](https://github.com/sitianjia/agent-tape) — structured trace recorder + replay; jsonl on disk, no service
- [`flowmind`](https://github.com/sitianjia/flowmind) — declarative agent flows in YAML, with checkpointing

## Activity

![Graph](https://github-readme-activity-graph.vercel.app/graph?username=sitianjia&theme=minimal&hide_border=true&area=true)

---

<sub>Not on Twitter. Not looking for a job. PRs welcome, issues even more welcome — I read all of them.</sub>
