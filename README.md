# Hi, I'm Ray 👋

I build reusable Codex skills and agent workflows for technical reasoning, architecture review, visual explanation, and support engineering.

我主要维护可复用的 Codex Skill 与 Agent 工作流，让复杂技术任务更容易理解、执行和验证。

- 📝 [Technical notes and experiments](https://huruizhi.github.io/)

## Featured Skills / 精选 Skills

| Skill | What it does / 功能 |
|---|---|
| [bilibili-render-pdf](https://github.com/huruizhi/bilibili-render-pdf) | Turn Bilibili videos into structured Chinese LaTeX course notes and compiled PDFs.<br>将 B 站视频整理为结构化中文 LaTeX 讲义与 PDF。 |
| [youtube-render-pdf](https://github.com/huruizhi/youtube-render-pdf) | Turn YouTube videos into figure-rich Chinese LaTeX course notes and compiled PDFs.<br>将 YouTube 视频整理为包含关键配图的中文 LaTeX 讲义与 PDF。 |
| [ray-archviz](https://github.com/huruizhi/ray-archviz) | Turn Agent systems, toolchains, and data flows into friendly hand-drawn Chinese architecture infographics.<br>将 Agent 系统、工具链与数据流转换为轻手绘中文架构图。 |
| [ray-review-software-design](https://github.com/huruizhi/ray-review-software-design) | Review module boundaries, abstractions, dependencies, and long-term software design quality.<br>评审模块边界、抽象、依赖关系与长期设计质量。 |

## Open-source Agent Projects / 开源 Agent 项目

| Project | What it explores / 探索方向 |
|---|---|
| [openclaw-agent-orchestrator](https://github.com/huruizhi/openclaw-agent-orchestrator) | Multi-agent task decomposition, dependency DAGs, scheduling, state tracking, and validation.<br>多 Agent 任务拆解、依赖 DAG、调度、状态跟踪与验证。 |
| [pi-durable-demo](https://github.com/huruizhi/pi-durable-demo) | Durable Agent execution and recovery experiments.<br>可持久化 Agent 执行与故障恢复实验。 |

## Install a Skill / 安装 Skill

Each standalone Skill repository can be cloned directly into the Codex skills directory. 每个独立 Skill 仓库都可以直接克隆到 Codex Skill 目录：

```bash
git clone https://github.com/huruizhi/bilibili-render-pdf.git ~/.codex/skills/bilibili-render-pdf
git clone https://github.com/huruizhi/youtube-render-pdf.git ~/.codex/skills/youtube-render-pdf
```

Then invoke the selected Skill explicitly. 然后按需显式调用对应 Skill：

```text
$bilibili-render-pdf 把这个 B 站视频整理成中文 PDF 讲义：<URL>
$youtube-render-pdf 把这个 YouTube 视频整理成中文 PDF 讲义：<URL>
```
