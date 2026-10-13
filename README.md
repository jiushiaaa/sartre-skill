<h1 align="center">sartre.skill</h1>

<p align="center">萨特 · Jean-Paul Sartre</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“存在先于本质。”<br>— 萨特 · <a href="https://www.marxists.org/reference/archive/sartre/works/exist/sartre.htm">《存在主义是一种人道主义》</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将处境中的自由、自欺与共同实践整理为思想分析 Skill，让 AI 同时看见选择的责任和行动的限制，不用身份标签或宏观结构替具体的人完成解释。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. “我只是服从命令”，能解释掉全部责任吗？

> 命令是处境的一部分，还要看当时有什么实际选择、怎样理解命令以及拒绝的代价。不能把服从直接当免责，也不能假定受胁迫者具有无限行动能力。

### 2. 我们讨厌同一个制度，是否已经构成行动共同体？

> 共同反感只能说明一个共同对象。还需查看成员是否相互回应、协调任务和承担承诺；由外部归在一起的人，不必然已经开展共同实践。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 具体责任 | 调查可行行动、舍弃项、限制与选择理由。 |
| 社会中介 | 通过家庭、教育、工作等材料连接个人与结构。 |
| 共同实践 | 区分共同对象、外部归类与实际相互行动。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/sartre-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `sartre-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/sartre-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用方式

- **中性思想模式（默认）：**“用萨特的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：**明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

《存在主义是一种人道主义》；《存在与虚无》自欺选段；《方法问题》及《辩证理性批判》选段。

- [原作来源、版本与实际阅读范围](source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://www.marxists.org/reference/archive/sartre/works/exist/sartre.htm">《存在主义是一种人道主义》</a>，Philip Mairet 英译。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

## 仓库结构

主要文件：

```text
├── SKILL.md  # Skill 入口与分析方法
├── README.md / README.en.md  # 中英文介绍
├── USAGE.md  # 双语使用说明
├── EXTRACTION.md  # 方法提炼与证据
├── references/  # 研究笔记与可选人物表达模式
└── LICENSE  # MIT 许可
```

## 构建工具

使用 [nvwa-skill](https://github.com/alchaincyf/nuwa-skill) 构建。

项目原创材料采用 [MIT](LICENSE)，所引原著与译本保留各自权利。详见 [来源说明](ATTRIBUTION.md)。

## 更多 Skill

更多人物 Skill 请查看 [Philosophy Skills 合集](https://github.com/jiushiaaa/Philosophy-Skills)。
