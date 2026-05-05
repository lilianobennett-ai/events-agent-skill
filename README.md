# events-research-agent

> A Claude Skill for growth marketers who want consistent, structured event evaluations across every session.

Stops you re-pasting your ICP, competitor list, and verdict framework into every conversation. Instead, the skill loads the structure once and applies it consistently to every event question you ask.

## What it does

Activates whenever you ask Claude about:
- Conferences, summits, trade shows, expos
- Sponsorship decisions
- Speaker / CFP submissions
- Event ROI comparisons
- Building an events calendar

For each event, it produces a structured verdict with:
- GO / SPONSOR / SPEAKER-FIRST / WATCH / SKIP rating
- Pipeline estimate (conversations → demos → opportunities)
- Competitor flags from your list
- CFP deadlines and startup tier opportunities
- Travel cost from your home base
- Trip-stack opportunities with your existing committed events

## Install

### Claude.ai (Pro / Team / Enterprise)

1. Download this folder as a zip
2. Go to claude.ai → Settings → Capabilities → Skills
3. Upload the zip
4. The skill activates automatically when you ask about events

### Claude Code

```bash
mkdir -p ~/.claude/skills/events-research-agent
cp -r SKILL.md references/ ~/.claude/skills/events-research-agent/
```

The skill loads on next Claude Code session. Trigger with `/events-research-agent` or just ask about events naturally.

### Claude API

See [Anthropic's Skills API quickstart](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview) for uploading custom skills via the API.

## First-time use

When you first ask about events, the skill will request your company context — five short questions about your ICP, verticals, competitors, and priorities. Answer once. The context persists for the session.

For longer-term use, paste your context into a Claude Project's knowledge base or a `events-context.md` file you upload. The skill will read it instead of asking.

See `references/example-context.md` for the structure.

## Want the full version?

This Skill is the lightweight share-and-go version. For the full template with daily cron-based automation, multiple example configs (B2B SaaS, AI infrastructure, etc.), and Slack/Notion/email integrations, see the parent repo:

**[github.com/lilianobennett-ai/events-agent](https://github.com/lilianobennett-ai/events-agent)**

## License

MIT. Fork it, modify it, share it.

## Not affiliated with Anthropic

This is a community-built skill using Claude as the runtime. It is not affiliated with, endorsed by, or supported by Anthropic. "Claude" is a product of Anthropic.

---

Built by [Lilian Bennett](https://github.com/lilianobennett-ai). "If this saves you time, ⭐ star the repo and tell me how you customised it.
