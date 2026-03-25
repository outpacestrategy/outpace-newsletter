# Outpace Newsletter — Outpace Your Competition

Weekly newsletter for small-to-mid business owners staying ahead of AI, SEO, and marketing trends.

**Platform:** Beehiiv — [outpacestrategygroup.beehiiv.com](https://outpacestrategygroup.beehiiv.com)
**Cadence:** Drafted Sunday night, sent Monday morning
**Audience:** Local business owners. Busy. Want signal, not noise.

---

## Directory Structure

```
/drafts/         — Current week's draft (working file)
/archive/        — Past issues (YYYY-MM-DD-subject.md)
/templates/      — Reusable formats, subject line swipe file
CLAUDE.md        — Voice, structure, and rules for every issue (read this first)
```

## How It Works

1. **Sunday 9pm** — Cron triggers Claude to draft the week's issue
2. Claude reads `CLAUDE.md`, pulls from overnight research, writes the full draft
3. Draft saved to `/drafts/YYYY-MM-DD.md` and Mission Control Filing Desk
4. **Monday morning** — Drew gets a Telegram ping with subject line options + opening
5. Drew reviews, pastes into Beehiiv, hits send
6. After send, issue moves to `/archive/`

## For Claude Code

Before working on any newsletter task:
1. Read `CLAUDE.md` in full
2. Check `/drafts/` for any current working draft
3. Check `/archive/` for past issues to match voice and format
4. Never publish — drafts only. Drew sends manually.
