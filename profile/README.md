# Welcome to the Conventional Branch Organization

**Clean branches, cleaner workflows — a Git naming convention for everyone.**

[![Conventional Branch](https://conventionalbranch.org/badge.svg)](https://conventionalbranch.org/)
[![Website](https://img.shields.io/static/v1?label=Website&message=conventionalbranch.org&color=6192c3)](https://conventionalbranch.org/)

**Conventional Branch** is a specification for Git branch names. It defines a small
convention, `<type>/<description>`, in which every branch declares its own purpose —
turning a branch name into something your CI/CD pipelines, review policies, and tooling
can act on directly.

The specification is published in [machine-readable form](https://conventionalbranch.org/spec.json),
with a [JSON Schema](https://conventionalbranch.org/schema/v1/spec.schema.json), permanent
version-pinned endpoints, and language-agnostic conformance fixtures, so supporting it is a
solved problem for any tool. It is used by [Ledger](https://github.com/LedgerHQ/ledger-live),
[Sanity](https://github.com/sanity-io/sdk), [Ansible](https://github.com/ansible/metrics-utility),
[Texas Instruments](https://github.com/TexasInstruments/processor-sdk-doc), and the
[Government of British Columbia](https://github.com/bcgov/nr-pies), among
[others](https://conventionalbranch.org/about/#projects-using-conventional-branch).

## 🌍 Multilingual Documentation

[English](https://conventionalbranch.org/) ·
[简体中文](https://conventionalbranch.org/zh/) ·
[繁體中文](https://conventionalbranch.org/zh-hant/) ·
[日本語](https://conventionalbranch.org/ja/) ·
[Deutsch](https://conventionalbranch.org/de/) ·
[Español](https://conventionalbranch.org/es/) ·
[Français](https://conventionalbranch.org/fr/) ·
[Polski](https://conventionalbranch.org/pl/) ·
[Português (Brasil)](https://conventionalbranch.org/pt-br/) ·
[Русский](https://conventionalbranch.org/ru/) ·
[ภาษาไทย](https://conventionalbranch.org/th/)

## 🤖 Agent Skill

Teach your AI coding assistant (Claude Code, Cursor, and more) to create and validate branch names that follow the specification.

Install the [Conventional Branch Skill](https://github.com/conventional-branch/conventional-branch/blob/main/skills/conventional-branch/SKILL.md) with:

```bash
npx skills add conventional-branch/conventional-branch --skill conventional-branch
```

Then just ask your agent to create a branch — it will follow the convention automatically.

The specification also maintains a [registry of AI agent branch prefixes](https://conventionalbranch.org/about/#ai-agent-source-prefixes)
— `ai/`, `claude/`, `codex/`, `copilot/`, `cursor/` — so tools and teams can recognize
agent-authored branches consistently.

## ⭐ Show Your Support

If you find this project helpful, follow us and give it a ⭐️ on [GitHub](https://github.com/conventional-branch/conventional-branch)!
Your support helps developers discover and adopt the specification.
