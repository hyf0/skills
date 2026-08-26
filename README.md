# skills

Reusable skills for Claude Code and Codex.

## Skills

### [hyfdev-adversarial-review](skills/hyfdev-adversarial-review/SKILL.md)

Adversarial review of a finished deliverable before it reaches the user: fresh reviewer subagents try to disprove it from three directions (open, over-engineering, residue), the agent verifies and fixes what holds, then reports. Runs once per deliverable when the agent considers it done, or on request at level strong or max (`/hyfdev-adversarial-review strong` in Claude Code, `$hyfdev-adversarial-review strong` in Codex).

Install globally for Claude Code and Codex:

```bash
npx skills@latest add hyfdev/skills --skill hyfdev-adversarial-review -g -a claude-code -a universal -y
```

### [hyfdev-rolldown-pr-review](skills/hyfdev-rolldown-pr-review/SKILL.md)

Review Rolldown PRs with problem-first reasoning, independent adversarial review, concise author-facing findings, and evidence-backed Approve or Request changes decisions; every published review and standalone comment names the GitHub handle of the requesting user after that user has reviewed or explicitly supervised the result, along with the assisting model. Explicit invoke only (`/hyfdev-rolldown-pr-review` in Claude Code, `$hyfdev-rolldown-pr-review` in Codex); the model will not start this skill from an ordinary review request.

Install globally for Claude Code and Codex:

```bash
npx skills@latest add hyfdev/skills --skill hyfdev-rolldown-pr-review -g -a claude-code -a universal -y
```

## License

MIT
