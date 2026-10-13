<h1 align="center">russell.skill</h1>

<p align="center">罗素 · Bertrand Russell</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“The good life is one inspired by love and guided by knowledge.”<br>— Bertrand Russell · <a href="https://www.gutenberg.org/files/73782/73782-h/73782-h.htm">What I Believe</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for logical analysis, descriptions, and induction: uncover assumptions of existence, uniqueness, and knowledge so that disputes turn on inspectable conditions.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. What goes wrong with “The present King of France is bald”?

> Separate existence, uniqueness, and baldness. If nobody satisfies the description, failure does not reveal a mysterious king with hair. Negating the whole assertion differs from negating its predicate.

### 2. A process succeeded a hundred times. Must it succeed next time?

> Inspect the sample, environmental stability, and the assumption linking past and future. Previous success can support a conditional expectation without deductive certainty. That does not make all predictions equally unsupported.

## What is distilled

| Method | What it helps examine |
|---|---|
| Definite descriptions | Separate existence, uniqueness, predication, and negation scope. |
| Belief contexts | Distinguish actual identity from the identity a person knows. |
| Inductive assumptions | Expose assumptions in extending past observations to future cases. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/russell-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `russell-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/russell-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use Bertrand Russell’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

On Denoting; selections on induction and knowledge in The Problems of Philosophy; What I Believe supplies the opening quotation.

- [Source catalogue and reading ranges](references/research/source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://www.gutenberg.org/files/73782/73782-h/73782-h.htm">What I Believe</a>, chapter II, “The Good Life”. English wording is translated where the source is not English; Chinese quotations are repository translations.

## Repository structure

Main files:

```text
├── SKILL.md  # Skill entry point and analysis methods
├── README.md / README.en.md  # Chinese and English introduction
├── USAGE.md  # Bilingual usage guide
├── EXTRACTION.md  # Method extraction and evidence
├── references/  # Research notes and optional expression mode
└── LICENSE  # MIT license
```

## Built with

Built with [nvwa-skill](https://github.com/alchaincyf/nuwa-skill).

Original project material is [MIT licensed](LICENSE); quoted works and translations retain their separate rights. See [source notices](ATTRIBUTION.md).

## More skills

Explore more thinkers and writers in the [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills).
