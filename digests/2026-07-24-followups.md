# Friday Follow-ups — 2026-07-24

**Run mode:** auto (fallback — config missing, no calendar writes)
**Sources:** Slack DMs · Gmail · Read AI
**Window:** 2026-07-17 → 2026-07-24

---

## TL;DR

7 open loops identified requiring Vinod's action. 5 meeting action items outstanding from this week's calls. No calendar blocks written (config not set up — run `/skill friday-followups` interactively to configure).

---

## SLACK — Direct Messages

### 1. Jimena Bedoya — All Hands Product slot (Aug 3)
**Who's waiting:** Jimena Bedoya (jimena.bedoya@tellius.com)
**Context:** She's OOO next week and building the Aug 3 All Hands agenda now. Asking if Product team can do a 10-minute update.
**Thread:** https://tellius-angularapp.slack.com/archives/D07LYAK5H37/p1784824348483139

**Draft reply:**
> Hey Jimena! Yes, happy to have the Product team do a 10-min slot on Aug 3. I'll plan to cover [e.g., "our roadmap progress and the enterprise memory launch"]. I'll send you a one-liner for the agenda by Monday. Have a great week off!

---

## EMAIL — Needs Reply

### 2. Searce-development GCP project investigation (Google TAM)
**Who's waiting:** Karoly Stephanie Luna, Google Technical Account Advisor (karoly@xwf.google.com)
**Context:** During a recent meeting Vinod flagged an unknown project ("searce-development"). Karoly confirmed it has been active 3 months, running Compute Engine (primary cost driver), Secret Manager, and Cloud KMS. She's waiting for Vinod's next step.
**Note:** Shashank was also assigned in the Data Architecture meeting to investigate the ~$576/month GCP CS dev project — likely the same issue.
**Thread:** Gmail thread 19f9070b9a0ad46e

**Draft reply (to karoly@xwf.google.com):**
> Hi Karoly, thank you for investigating. Compute Engine as the primary driver is helpful — I'll loop in Shashank from our infra team to determine if these resources are still needed or can be shut down. I'll follow up once we've reviewed. If it would be useful, can you confirm the project billing account and whether the Compute Engine instances are currently running? Thanks again.

---

### 3. Google Cloud IAM access request — chris.walker@tellius.com
**Who's waiting:** Automated request, but Chris Walker is waiting on access
**Context:** Chris Walker requested a role on GCP resource 01F2CC-B15A24-CA1789. Vinod is the approver.
**Thread:** Gmail thread 19f912102e4da0ef
**Action needed:** Review and approve/deny in the Google Cloud console — not an email reply.

**Draft approval note (internal):**
> Approve if chris.walker@tellius.com's role on 01F2CC-B15A24-CA1789 is in scope for their work. Verify with Chris or Shashank what access level is needed before granting broad roles.

---

### 4. Claude API monthly spend alert — $9,000 threshold crossed
**Who's waiting:** Shared alert (Anthropic → Ajay, Jimena, Shashank, Abhishek, Vinod)
**Context:** Tellius hit the self-set $9,000/month Claude API spend threshold. Possibly expected given the product build, but worth confirming it's intentional with the team.
**Thread:** Gmail thread 19f94006a346c672
**Action:** Internal check — confirm with Shashank/Ajay that spend is expected or adjust threshold.

**Draft Slack message (e.g., #infra or #product-eng):**
> Hey team — heads up, we hit our $9k/month Claude API threshold. Is this expected given current usage? Should we adjust the alert threshold or do we need to look at optimization?

---

## MEETING ACTION ITEMS (from Read AI)

### 5. Enterprise Memory & GTM Strategy (Jul 17) — Send enterprise-brain document
**Who's waiting:** Atul Khanna + team (Armando Olivares)
**Context:** Vinod committed to circulating the detailed enterprise-brain document to help Atul advise on framing (enterprise-brain vs. original framing as primary).
**Meeting:** https://app.read.ai/analytics/meetings/01KXRF3FQCSQ4F6T0158C9R998

**Draft message (Slack/email to Atul):**
> Hey Atul — sending over the enterprise-brain doc as promised. [attach doc] Would love your take on whether this framing or the original should lead. Let me know what you think.

---

### 6. Data Architecture & Chat UX (Jul 17) — Share architect design links + data module porting designs
**Who's waiting:** Shashank, Nitya (and broader eng team)
**Context:** Vinod committed to sharing (a) the architect design links and (b) the more ambitious data module porting designs so Nitya can consolidate and the team can begin the revamp.
**Meeting:** https://app.read.ai/analytics/meetings/01KXQ56J3CW049JBF6P90S9VYR

**Draft Slack (to Shashank/Nitya):**
> Hey — sharing the architect design links [link] and data module porting designs [link] as promised. Nitya, this should give you what you need to consolidate designs. Let me know if anything's missing.

---

### 7. Data Architecture & Chat UX — Send cursor/related use cases to team
**Who's waiting:** Shashank + Madhukar (to decide on meta-agent behavior unification)
**Context:** Vinod committed to sending use cases for the cursor and related scenarios so Madhukar can evaluate whether and how to unify meta-agent behavior.

**Draft Slack (to Shashank/Madhukar):**
> Hey — here are the cursor + related scenario use cases I mentioned: [list/doc]. Madhukar, these should help you evaluate the meta-agent unification question. Happy to walk through them.

---

### 8. Data Architecture & Chat UX — Test newer OpenAI/Anthropic models and propose fallback
**Who's waiting:** Shashank + eng team
**Context:** Vinod committed to testing OpenAI 5.4/5.5/5.6 and Anthropic Net5 models and proposing a default fallback configuration.

**Draft Slack (to Shashank):**
> Update on model testing: I've been testing OpenAI 5.4/5.5 and Anthropic's latest. [Add findings.] My recommendation for the default fallback is: [model + rationale]. Let me know if you want to discuss before we commit.

---

### 9. Enterprise Memory & GTM — Test LinkedIn automated posting
**Who's waiting:** Self (committed to evaluate traction)
**Context:** Vinod said he'd set up and test automated posting of pre-authored LinkedIn ideas (during a flight) to gauge engagement. This is a solo task.
**Note:** Lower priority than team-blocking items above.

---

## Notes on this run

- **Config missing:** `.friday-followups-config.json` not found. Auto mode skipped the wizard per spec. No calendar blocks were written.
- **No calendar MCP:** Cannot book follow-up blocks without config.
- **Messaging:** Slack connected and searched. No channel @-mentions of "vinod" found this week; DMs showed 1 actionable item.
- **Gmail:** 201 unread threads; filtered to INBOX + IMPORTANT for actionability. Newsletters, Tellius automated alerts, and CC-only threads excluded.
- **Read AI:** 2 meetings found for the past 7 days with 10 action items assigned to Vinod.
- **Run log:** `.friday-followups-runs.jsonl` updated with failure entry.
- **To set up fully:** Run `/skill friday-followups` interactively to configure identity, calendar, and working hours — then future scheduled runs will book calendar blocks automatically.
