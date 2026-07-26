# skills

Reusable skills for Claude Code and Codex.

## Skills

### [hyfdev-rolldown-pr-review](skills/hyfdev-rolldown-pr-review/SKILL.md)

Review Rolldown PRs with problem-first reasoning, independent adversarial review, concise author-facing findings, and evidence-backed Approve or Request changes decisions; every published review and standalone comment names the GitHub handle of the requesting user after that user has reviewed or explicitly supervised the result, along with the assisting model. Explicit invoke only (`/hyfdev-rolldown-pr-review` in Claude Code, `$hyfdev-rolldown-pr-review` in Codex); the model will not start this skill from an ordinary review request.

Install globally for Claude Code and Codex:

```bash
npx skills@latest add hyfdev/skills --skill hyfdev-rolldown-pr-review -g -a claude-code -a universal -y
```

## License

MIT
