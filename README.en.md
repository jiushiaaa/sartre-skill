<h1 align="center">sartre.skill</h1>

<p align="center">萨特 · Jean-Paul Sartre</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“Existence comes before essence.”<br>— Jean-Paul Sartre · <a href="https://www.marxists.org/reference/archive/sartre/works/exist/sartre.htm">Existentialism Is a Humanism</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for situated freedom, bad faith, and common praxis: keep responsibility and constraint in view without letting a role label or a social structure stand in for an explanation of a person.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. Does “I was only following orders” explain away responsibility?

> Orders are part of a situation. Examine feasible alternatives, how the order was interpreted, and the cost of refusal. Obedience does not automatically absolve, and coercion must not be treated as unlimited freedom.

### 2. Does opposing the same institution make us an acting community?

> A shared objection identifies a common object. Examine reciprocal responses, coordination, and commitments. Being grouped together from outside does not establish common praxis.

## What is distilled

| Method | What it helps examine |
|---|---|
| Situated responsibility | Examine feasible actions, alternatives, constraints, and reasons. |
| Social mediations | Connect people and structures through documented social relations. |
| Common praxis | Distinguish shared objects and external grouping from reciprocal action. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/sartre-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `sartre-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/sartre-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use Jean-Paul Sartre’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

Existentialism Is a Humanism; selections on bad faith in Being and Nothingness; excerpts from Search for a Method and Critique of Dialectical Reason.

- [Source catalogue and reading ranges](source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://www.marxists.org/reference/archive/sartre/works/exist/sartre.htm">Existentialism Is a Humanism</a>, Philip Mairet translation. English wording is translated where the source is not English; Chinese quotations are repository translations.

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
