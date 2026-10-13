<h1 align="center">russell.skill</h1>

<p align="center">罗素 · Bertrand Russell</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“美好的生活，是由爱激励、由知识引导的生活。”<br>— 罗素 · <a href="https://www.gutenberg.org/files/73782/73782-h/73782-h.htm">《我所相信的》</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将逻辑分析、描述理论与归纳问题整理为思想分析 Skill，让 AI 拆开句子里隐藏的存在、唯一性和知识前提，使争论从措辞回到可检查的条件。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. “现任法国国王是秃头”错在哪里？

> 先拆成有一位现任法国国王、只有一位，以及那个人是秃头。若不存在满足描述的人，不能把句子的失败解释成有一位神秘国王只是头发很多；否定整句与否定谓词也要分开。

### 2. 过去一百次都成功，下一次就一定成功吗？

> 列出样本、环境稳定性与从过去到未来的推断前提。过去成功可以支持有条件的预期，但不构成演绎保证；指出这一点也不等于所有预测同样没有根据。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 描述分析 | 分别检查存在、唯一性、谓词与否定范围。 |
| 信念语境 | 区分现实中的同一对象与当事人知道的同一性。 |
| 归纳前提 | 指出从已观察情况推向未来所依赖的假设。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/russell-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `russell-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/russell-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用方式

- **中性思想模式（默认）：**“用罗素的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：**明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

〈论指称〉；《哲学问题》归纳与知识相关选段；《我所相信的》作为开篇引文来源。

- [原作来源、版本与实际阅读范围](references/research/source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://www.gutenberg.org/files/73782/73782-h/73782-h.htm">《我所相信的》</a>，第二章“美好的生活”。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

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
