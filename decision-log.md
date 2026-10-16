# Decision Log

*The work proves itself here. Predictions go in before outcomes come out. No edits after the fact.*

## The rules

1. **Log the decision BEFORE it runs.** Date-stamped, in plain language.
2. **Each of the three agents records** a prediction, a confidence (0–100%), a one-line rationale, and a timestamp — all before the outcome is known.
3. **Predictions freeze when the decision runs.** No edits after the outcome lands. A frozen miss beats a polished rewrite.
4. **Log the outcome with real numbers** when it lands.
5. **Score each agent**: hit / partial / miss. Track calibration over time — an agent that's 90% confident and right half the time is telling you something.

## The agents

From the framework documents (confirmed via Claude, 2026-10-09):

- **Agent 1 — Sevro:** metrics thinking. Reads the numbers — what the data says the outcome will be.
- **Agent 2 — Tanjiro:** audience judgment. Reads the people — who this lands with and how they'll move.
- **Agent 3 — 4th Hokage:** vision. Reads the arc — where this decision points over time, what it sets in motion.

## Scoreboard

| Agent | Decisions | Hits | Partials | Misses | Notes on calibration |
|-------|-----------|------|----------|--------|----------------------|
| Sevro (metrics) | 0 | 0 | 0 | 0 | — |
| Tanjiro (audience) | 0 | 0 | 0 | 0 | — |
| 4th Hokage (vision) | 0 | 0 | 0 | 0 | — |

---

## Entries

### DL-001 — Facebook ad campaign ($15/day × 7)

- **Date proposed:** 2026-10-09
- **Status:** SPEC LOCKED 2026-10-09 — Alexander approved all three gates: (1) copy — yes, (2) Facebook targeting to builders / decision-makers / framework-curious — yes, (3) checkpoint cleared, ready to lock — yes. (His word; the Facebook checkpoint clear happens in his account.)
- **The decision:** Run the approved Facebook ad campaign at $15/day for 7 days ($105 total) to **get Alexander paid for his frameworks** — selling the Aegis line (Swarm Core / Dashboard / Complete, $888 each).
- **Product readiness (his bar: auditable, runnable, executable, real):**
  - Aegis Swarm Core: rebuilt 2026-10-09 — 55/55 tests pass, 9/9 rogue attacks blocked, AUDITABILITY.md shipped, honest copy live on Gumroad. ✓
  - Aegis Dashboard: hardened pre-launch — API-key auth, 10/10 tests passing. ✓
  - Aurora license server v1.2: 9/9 live endpoint checks passed, private repo pushed. ✓
  - Verdict: the bar he named is already substantially met — he built the thing he's demanding.
- **Angle (locked):** not "try this neat tool" — **frameworks that don't break under real stakes.** Target: people who need to *prove* their thinking works — builders, decision-makers, teams that can't afford to guess.
- **Success metric (locked):** revenue — direct pipeline to paid work off Aurora. **Spend $105 to prove Aurora generates paid interest, not curiosity.** Win = paid interest attributable to the campaign (sale, qualified paid-work inquiry).
- **Platform:** Facebook — the $105 is approved there, and the audience is targetable there (job titles: founder, CTO, engineering manager, product lead; interests: AI/ML, software engineering, startups; US 25–54). Checkpoint clearance is still the gate.
- **Copy (draft v1 — awaiting his approval):**
  - *Variant A — direct:*
    - Primary: "Most AI frameworks sound good in a demo and break the first time real stakes touch them. Aegis Swarm Core was rebuilt from the ground up and proven: 55 out of 55 tests pass, 9 out of 9 rogue-agent attacks blocked, every action sealed in a hash-chained audit log. If your team can't afford to guess whether its AI does what it claims — stop guessing. Audit it."
    - Headline: "Frameworks that don't break under real stakes."
    - CTA: Learn more → Aegis Gumroad page.
  - *Variant B — decision-log angle:*
    - Primary: "We log every prediction before the outcome — then score it cold. That's how you know whether an AI framework actually works or just sounds good. Aegis is the first product we ran through our own decision log: 55/55 tests, 9/9 attacks blocked, full audit trail. Built by people who prove their thinking instead of performing it."
    - Headline: "Prove your AI works. We did."
    - CTA: Learn more → Aegis Gumroad page.
- **Copy decision:** BOTH — A/B test. Variants A and B run head-to-head, budget split evenly ($7.50/day per variant, $52.50 each over 7 days). Winner judged on paid interest per dollar.
- **Independent reviewer's verdict (Claude, 2026-10-09):** "The ad is the gauntlet. For your audience — builders and decision makers who can't afford to guess — they don't want reassurance, they want to see someone else who stopped guessing first. You're showing, not telling. Risk: it's sparse, some won't get it — but the ones who do will be exactly the ones you want, the ones who already think like you. Verdict: run it." (Longer proof belongs on the landing page, not in the ad.)
- **Predictions** *(full spec now with Sevro, Tanjiro, 4th Hokage — awaiting their locked calls, timestamped):*
  - Sevro (metrics): — pending
  - Tanjiro (audience): — pending
  - 4th Hokage (vision): — pending
- **What to measure:** spend, impressions, clicks, click-through rate, attributed sales, revenue, cost per acquisition. Note whether revenue clears Gumroad's $100 payout minimum.
- **Outcome:** — pending
- **Score:** — pending

---

*New entries copy the DL-001 template. The log grows; the rules don't change.*
