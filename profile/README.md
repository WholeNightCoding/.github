# Whole Night Coding

> Tools and skills for Claude Code, built late at night.
> 通宵给 Claude Code 写工具的小作坊。

We build small, focused, local-first tools that make Claude Code more useful —
for analyzing your own usage, monitoring your own projects, and capturing what
you're building.

## Projects

### CLI tools & dashboards

| Repo | What |
|---|---|
| [**token-usage**](https://github.com/WholeNightCoding/token-usage) | Local-first analytics for your Claude Code token consumption. CLI + browser dashboard + Markov / change-point / Gini analysis + 🤖 AI 解读. |

### Claude Code skills

Auto-discovered by Claude Code when cloned into `~/.claude/skills/`.

| Repo | Triggers on |
|---|---|
| [**web-screenshot**](https://github.com/WholeNightCoding/web-screenshot) | "截图" / "screenshot this page" / "拍个图" — drives a headless browser via natural language to PNG any URL. Self-bootstraps Node deps + chrome-headless-shell on first run. |

## Principles

- **Local-first.** Your data never leaves your machine. No telemetry, no
  analytics, no outbound calls (except local `claude` CLI for AI features
  the user explicitly invokes).
- **Self-contained.** Skills auto-bootstrap their runtime deps on first run.
  Only hard dependencies are what's already standard (Python 3.11+ stdlib for
  CLI tools, Node 18+ for browser-driven skills).
- **AI-friendly.** Skills are written for Claude Code to discover and apply
  automatically — natural-language triggers, not CLI flags.
- **Bilingual where it matters.** Chinese UI strings stay Chinese. Code stays
  English. READMEs go both ways.

## Contributing

Issues and PRs welcome on any of the repos. Each repo's `CLAUDE.md` documents
its conventions for Claude Code contributors.
