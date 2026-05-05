# review-skill

> [!IMPORTANT]
> **This repo has moved.** The canonical home for the `/review` skill is now
> [**dotbrains/skills**](https://github.com/dotbrains/skills), alongside the
> rest of the dotbrains agent skills.
>
> Install with:
>
> ```bash
> npx skills@latest add dotbrains/skills
> ```
>
> Or copy the file directly:
>
> ```bash
> mkdir -p ~/.claude/skills/review
> curl -fsSL https://raw.githubusercontent.com/dotbrains/skills/main/skills/review/SKILL.md \
>   -o ~/.claude/skills/review/SKILL.md
> ```
>
> This repository is archived and will not receive further updates. File
> issues and PRs against [dotbrains/skills](https://github.com/dotbrains/skills).

---

Portable `/review` skill for high-signal pull request review:

1. Read PR metadata and description.
2. Read associated ticket to understand scope and intent.
3. Analyze diff plus surrounding code context.
4. Run PR-suggested tests in read-only mode.
5. Produce a structured review with Critical / Suggestions / Nits.

See the canonical [`SKILL.md`](https://github.com/dotbrains/skills/blob/main/skills/review/SKILL.md) in dotbrains/skills.
