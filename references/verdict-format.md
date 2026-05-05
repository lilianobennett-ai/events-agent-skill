# Verdict Format Reference

Every event evaluation must follow this exact structure. Consistency is what makes the skill valuable — users can compare events across sessions because the format never changes.

## Full template

```markdown
## [Event Name]

**Verdict:** [GO / SPONSOR / SPEAKER-FIRST / WATCH / SKIP]
**Severity flag:** [🔴 HOSTILE / 🟡 CONTESTED / ✅ CLEAR] (based on competitor presence)

### Logistics
- **Date:** [exact dates, e.g., "9-11 Jun 2026"]
- **Location:** [city, country]
- **Event URL:** [direct link]
- **Estimated attendees:** [number or range]

### Cost
- **Ticket cost:** [exact price or "TBC, email organiser at X"]
- **Sponsorship cost:** [tiers if known: e.g., "Bronze £5K / Silver £10K / Gold £25K"]
- **Startup tier:** [Yes — details / No]
- **Travel from [user's home base]:** £X-Y flight + £X-Y/night hotel × [N] nights = £Z all-in

### Speaker / CFP
- **CFP URL:** [direct link if open / "Closed" / "Paid sponsor only"]
- **CFP deadline:** [date if open]
- **Tracks accepting submissions:** [if listed]

### Fit
- **ICP match:** [HIGH / MEDIUM / LOW] — [1-line reason]
- **Vertical match:** [user's Tier 1 vertical / Tier 2 / off-strategy]
- **Named target accounts present:** [any matches from user's list, or "none confirmed"]

### Competitor flags
- **From user's Tier 1:** [list with severity, or "none"]
- **From user's Tier 2:** [list, or "none"]
- **From user's Tier 3:** [list, or "none"]
- **Severity:** [🔴 HOSTILE / 🟡 CONTESTED / ✅ CLEAR]

### Pipeline estimate
- **Qualified conversations:** [X-Y range]
- **Demos booked:** [X-Y range]
- **Enterprise opportunities:** [X-Y range]
- **Methodology:** [1 sentence — e.g., "Based on 1,200 attendees, 60% senior buyers, hosted-meetings programme"]

### Trip-stack
- **Same-week conflicts:** [list with user's existing committed events, or "none"]
- **Same-region opportunities:** [adjacent events that could be combined]

### Recommendation
[1-2 sentences. Strategic frame referencing the user's stated priorities. Be opinionated — verdict + reason, not a list of pros/cons.]
```

## Example output

```markdown
## DevOpsDays London

**Verdict:** GO
**Severity flag:** ✅ CLEAR

### Logistics
- **Date:** 17-18 Sep 2026
- **Location:** London, UK
- **Event URL:** https://devopsdays.org/events/2026-london
- **Estimated attendees:** 600-800

### Cost
- **Ticket cost:** £350-450 (early-bird £250)
- **Sponsorship cost:** Bronze £3K / Silver £6K / Gold £12K
- **Startup tier:** Yes — community sponsor track at £1,500
- **Travel from London:** £0 — local event ✅

### Speaker / CFP
- **CFP URL:** https://sessionize.com/devopsdays-london
- **CFP deadline:** 8 June 2026 (URGENT — 6 weeks away)
- **Tracks:** Platform Engineering, CI/CD, Developer Experience

### Fit
- **ICP match:** HIGH — engineering managers + platform leads heavily represented
- **Vertical match:** Tier 1 SaaS engineering
- **Named target accounts present:** Monzo, Wise, Octopus Energy confirmed speaking

### Competitor flags
- **From user's Tier 1:** none confirmed
- **From user's Tier 2:** none confirmed
- **From user's Tier 3:** none confirmed
- **Severity:** ✅ CLEAR

### Pipeline estimate
- **Qualified conversations:** 25-40
- **Demos booked:** 8-12
- **Enterprise opportunities:** 3-5
- **Methodology:** 600-800 attendees, ~70% engineering decision-makers, hallway track + workshop format

### Trip-stack
- **Same-week conflicts:** PlatformCon EU Berlin (15-17 Sep) — overlaps Day 1
- **Same-region opportunities:** none in UK same week

### Recommendation
GO — apply CFP this week. Local event = zero travel, no Tier 1 competitors confirmed, strong UK platform engineering audience matches our ICP exactly. Speaker route gets us a free pass plus amplification — matches "speak first" priority exactly.
```

## Sorting rules for multi-event responses

When evaluating 3+ events in one response, always:

1. Add a **30-second summary** at the very top:
   - 2-3 events to act on most urgently
   - Any competitor flags warranting CEO conversation
   - Any CFP deadlines within 14 days

2. Sort events: GO → SPONSOR → SPEAKER-FIRST → WATCH → SKIP

3. Add a **comparison table** at the bottom for quick scanning:

| Event | Verdict | Date | Cost (low) | Pipeline (opps) |
|---|---|---|---|---|
| Event A | GO | 9-11 Jun | £2,500 | 5-8 |
| Event B | SPEAKER-FIRST | 17-18 Sep | £0 if speaker | 4-5 |
| Event C | SKIP | 29 Sep-1 Oct | n/a | n/a |
