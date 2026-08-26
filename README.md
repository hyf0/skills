# skills

Reusable skills for Claude Code and Codex.

## Skills

### [hyfdev-adversarial-review](skills/hyfdev-adversarial-review/SKILL.md)

Adversarial review of a finished deliverable before it reaches the user: fresh reviewer subagents try to disprove it from three directions (open, over-engineering, residue), the agent verifies and fixes what holds, then reports. Runs once per deliverable when the agent considers it done, or on request at level strong (强力) or max (极致) (`/hyfdev-adversarial-review strong` in Claude Code, `$hyfdev-adversarial-review strong` in Codex).

Install globally for Claude Code and Codex:

```bash
npx skills@latest add hyfdev/skills --skill hyfdev-adversarial-review -g -a claude-code -a universal -y
```

## License

MIT
