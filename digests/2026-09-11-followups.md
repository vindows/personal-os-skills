# Friday Followups — Sep 11, 2026

**TL;DR:** 7 groups identified, ~4h 25min of work, 0 overflow. Calendar writes skipped (no calendar MCP connected — dry-run). Config file missing; derived identity from session context and run-log history.

---

## Plan

### Group 1 · Market Access App Rollout — CEO Commitments by Tuesday
**Estimated time:** 60 min | **Status:** URGENT — CEO ask

**Todos:**
- Respond to Ajay in Group DM (C08RREF6WL9): commit to exactly which 3 workers and 7–8 apps are shippable by Tuesday, with owner per item.
- Respond to Ajay in Group DM (C08EJ007HLG): share thoughts and plan (was a separate direct ask — "Pls let me know your thoughts and plan for this").
- Follow-up from Vertical Apps QA this morning (9:30–10am): close the loop on the committed list if not already done.

**Source:**
- [Ajay → group DM C08RREF6WL9 (5:20am PDT)](https://tellius-angularapp.slack.com/archives/C08RREF6WL9/p1789129237689289?thread_ts=1788967954.183159&cid=C08RREF6WL9)
- [Ajay → group DM C08EJ007HLG (5:06am PDT)](https://tellius-angularapp.slack.com/archives/C08EJ007HLG/p1789128414454259)

**Context:** Ajay flagged that 70–80% of the real problem is in the data layer (entity matching, taxonomy), not the UI. 14 apps exist but none are yet confirmed shippable against real customer data. Granola notes from Ajay's morning session detail the full requirements for the market access worker.

**Drafted reply (group DM C08RREF6WL9):**
> Here's where I land based on this morning's QA + Ajay's docs: [COMMITTED 3 WORKERS] and [COMMITTED 7–8 APPS LIST]. Owner for each: [FILL AFTER QA]. For the data layer gap (taxonomy/entity matching), Ankit is building the QA skill/checklist by tomorrow — that's the key gating piece. I'll post the committed list here by end of day.

---

### Group 2 · Kaya Wiki — Document & Unblock Madhukara
**Estimated time:** 60 min | **Status:** High — gates implementation

**Todos:**
- Write up the agreed-upon narrower approach from the research meeting: expose assumptions through an auditable planner tool or existing memory system (not a full file-based Wiki replacement).
- Document the open design questions that need resolution before Madhukara proceeds: granular vs. consolidated files, trust/review states, batch reconciliation, latency/caching.
- Share the doc with Madhukara Phatak, Shashank, and the team.

**Source:** [Read AI — Research/Feature Discussion & Roadmap (Sep 10)](https://app.read.ai/analytics/meetings/01M25QP82FRC2KR5V3033TPKZG)

**Context:** Vinod pushed back on the full file-based Wiki as too broad; group converged on narrower approach using existing memory system with planner-level access. Madhukara is blocked pending Vinod's written direction.

**Drafted doc outline:**
```
Kaya Wiki — Narrowed Approach (Sep 11 direction from Vinod)

Decision: Do NOT replace the storage layer. Instead:
1. Expose assumptions via an auditable planner tool that surfaces inferred assumptions 
   during planning (same session or retrieved from memory).
2. Move long-term memory retrieval from meta-agent injection → planner-accessible retrieval.
3. Wiki = implementation option within existing memory, not a new storage layer.

Open questions before Madhukara builds:
- Granular (one file/assumption) vs. consolidated files?
- Trust states: unreviewed vs. promoted?
- How backfilling existing conversations works?
- Latency budget for retrieval at plan time?

Behavioral test cases (from prototype):
- assumption extracted on first use → reused in later questions ✓
- deletion → re-generated from next conversation ✓  
- explicit user override → persisted as preference ✓
- audit metadata: conversation ID, turn, timestamp ✓
```

---

### Group 3 · Visa Use Case Write-up
**Estimated time:** 30 min | **Status:** This week — sales/SE enablement

**Todos:**
- Write the Visa use case: Oracle EPM variance analysis + Hadoop data, documenting the problem, the Tellius/Kaya approach, and the expected business outcome.
- Format for sales/SE enablement (not a full deck — a written summary they can pull from).

**Source:** [Read AI — Weekly Plan meeting, Sep 9](https://app.read.ai/analytics/meetings/01M21ZD6203W3HFD8TNJN2VJS3)

**Context:** Assigned directly to Vinod in the Weekly Plan call. Needed ahead of the v6.4 launch for reps to have an anchor use case for financial services/CPG.

**Drafted write-up opener:**
> **Visa Use Case: Oracle EPM Variance Analysis + Hadoop Data**
> 
> **The problem:** Finance teams run budget vs. actual variance analysis across Oracle EPM (structured) and Hadoop (semi-structured transaction logs). Reconciling these two sources requires weeks of manual ETL; answers take days to get and are already stale by review time.
> 
> **What Kaya does:** Connects directly to both sources, builds a unified semantic model, and lets finance analysts ask variance questions in plain language — with drill-down to transaction-level detail across both systems. A recurring mission monitors threshold variances weekly and surfaces exceptions without waiting for analyst-initiated queries.
>
> **Outcome:** Time-to-insight for variance review drops from ~5 days to same-day. [FILL: specific metric from Visa proof-of-concept if available]

---

### Group 4 · Token Optimization Blog Review
**Estimated time:** 30 min | **Status:** Today — Chris is getting heat

**Todos:**
- Review the Token Optimization blog draft in Notion and provide feedback or approval so Chris can publish.

**Source:** [Chris Walker → Vinod DM (7:08am PDT)](https://tellius-angularapp.slack.com/archives/D07LL60UP6W/p1789135691583989)

**Context:** Chris said "I'm getting heat to get this blog out" — it's ready and waiting on Vinod's eyes only.

**Drafted reply:**
> On it — will take a look by noon today and get you feedback/thumbs up. 🔥

*(Then actually review the Notion doc and reply with specific feedback or "all good, ship it.")*

---

### Group 5 · Home Page Design — Implementation Green Light for Sriram
**Estimated time:** 15 min | **Status:** This week — blocking Sriram's team

**Todos:**
- Check whether Ajay's feedback on the Home Page design was obtained (it may have come through the research meeting or async).
- Reply to Sriram in the group DM to either unblock implementation or state what's still missing.

**Source:** [Sriram → Group DM C08RJQ2FYGM](https://tellius-angularapp.slack.com/archives/C08RJQ2FYGM/p1789095521163779?thread_ts=1788275914.420099&cid=C08RJQ2FYGM)

**Context:** Sriram asked: "did you get feedback from Ajay. Are we good to go ahead for implementation?" The thread started with a Home Page design review request. Shashank noted it wasn't covered in the call; async feedback was proposed.

**Drafted reply:**
> @Sriram — yes, go ahead with implementation. [OR: still waiting on one input from Ajay re: [SPECIFIC POINT] — can you hold on the [SPECIFIC MODULE] and proceed with the rest?]. I'll follow up with final confirmation by EOD.

---

### Group 6 · Novo Nordisk Video Reaction (Ajay in #cust-novo-nordisk)
**Estimated time:** 15 min | **Status:** Today — CEO-tagged

**Todos:**
- Open the Snowflake/Novo Nordisk customer video Ajay shared in #cust-novo-nordisk.
- Leave a reaction or brief comment for Ajay and the leadership team.

**Source:** [Morning Brief reference → #cust-novo-nordisk](https://tellius-angularapp.slack.com/archives/C04AMGV0W8N/p1789133830353249)

**Context:** Ajay tagged Vinod + leadership team with competitive context (Snowflake doing something in Novo Nordisk). Needs a reaction/acknowledgment to close the loop.

**Drafted comment:**
> Watched this — [competitive take / what's relevant for our positioning in pharma]. Worth noting for the Pladis/Clarivate pitches too. [If alarming]: Let's discuss in the next leadership sync.

---

### Group 7 · External Comms — GitHub AM + AirStreet Partnership Inquiry
**Estimated time:** 15 min | **Status:** This week

**Todos:**
- **GitHub Account Manager (Austin Krueger):** 2 follow-up emails unanswered. Send a brief reply or forward to engineering. Suggested action: 2-sentence reply ("thanks for reaching out — forwarding to our engineering lead [NAME] who manages our GitHub relationship") or ask Austin what specifically he wants to discuss before routing.
- **AirStreet/Janet (janet@hack-nation.com):** Scan the email; she mentions Tellius through an AirStreet Events connection + MIT contacts. Route or decline. Likely a polite decline or "not the right time."

**Source:**
- Morning Brief reference (GitHub AM — 2 follow-ups unanswered)
- [Gmail thread from janet@hack-nation.com](https://mail.google.com/mail/u/0/#inbox/1a0900d68c9dcb6d)

**Drafted GitHub AM reply:**
> Hi Austin — thanks for following up. Happy to connect briefly. What's the main topic you wanted to cover? I can make sure the right person from our side joins. 
> Best, Vinod

**Drafted AirStreet/Janet decline:**
> Hi Janet — thanks for reaching out via AirStreet Events. We're heads-down on a product cycle right now and not in a position to explore partnerships. I'd suggest revisiting in Q1 2027 if Tellius is still on your radar. Best of luck with the program.
> — Vinod

---

## Review by Hand

| Item | Why flagged |
|------|-------------|
| Notion Token Optimization Blog URL in Chris Walker's DM | Couldn't preview Notion content — manual review required |
| Market Access app rollout committed list | Vinod needs to fill in specifics from the 9:30am QA outcome |
| Home Page design Ajay feedback status | Unclear if feedback was received async — check before replying to Sriram |

---

## Overflow

None — all 7 groups fit within the 3-hour weekly cap across Mon–Wed of the coming week.

---

## Notes on This Run

- **Config file:** Missing (`.friday-followups-config.json` not found since Sep 4). Identity derived from session context (`vinod.iyengar@tellius.com`, aliases: Vinod / VI, timezone: America/Los_Angeles). Defaults applied from last successful run log (Aug 28).
- **Calendar MCP:** Not connected. All blocks are dry-run only — no calendar events created.
- **Messaging:** Slack (read-only) + Gmail — both operational.
- **Read AI:** Operational. 2 meetings fetched with full action items.
- **Candidates:** ~30 across sources. Verdicts: yes=9, maybe=3, no=~18 (bot notifications, newsletters, automated alerts filtered).
- **Run completed:** 2026-09-11 ~07:15 PDT (scheduled)

---

*To restore calendar writes: run the skill interactively to recreate `.friday-followups-config.json`*
