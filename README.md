# Hi, I'm Ray 👋

I build reusable Codex skills and agent workflows for technical reasoning, architecture review, visual explanation, and support engineering.

我主要维护可复用的 Codex Skill 与 Agent 工作流，让复杂技术任务更容易理解、执行和验证。

- 📝 [Technical notes and experiments](https://huruizhi.github.io/)
- 🧰 [Public Codex skills collection](https://github.com/huruizhi/codex-skills)

## Featured Skills

| Skill | What it does |
|---|---|
| [ray-archviz](https://github.com/huruizhi/ray-archviz) | Turn Agent systems, toolchains, and data flows into friendly hand-drawn Chinese architecture infographics. |
| [review-software-design-skill](https://github.com/huruizhi/review-software-design-skill) | Review module boundaries, abstractions, dependencies, and long-term software design quality. |
| [codex-skills](https://github.com/huruizhi/codex-skills) | A public collection of reusable personal Codex skills and adapted development workflows. |
| [support-troubleshooting](https://github.com/huruizhi/support-troubleshooting) | Evidence-driven Codex plugin for support-ticket triage and troubleshooting. |

## Open-source Agent Projects

| Project | What it explores |
|---|---|
| [openclaw-agent-orchestrator](https://github.com/huruizhi/openclaw-agent-orchestrator) | Multi-agent task decomposition, dependency DAGs, scheduling, state tracking, and validation. |
| [pi-durable-demo](https://github.com/huruizhi/pi-durable-demo) | Durable Agent execution and recovery experiments. |

## Install a Skill

Each standalone Skill repository can be cloned directly into the Codex skills directory:

```bash
git clone https://github.com/huruizhi/ray-archviz.git ~/.codex/skills/ray-archviz
```

Then invoke it explicitly when needed:

```text
$ray-archviz 把下面的系统说明生成一张轻手绘卡片式中文架构图……
```
