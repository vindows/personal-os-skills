# Friday Followups — 2026-08-07

**Window analyzed:** 2026-07-31 → 2026-08-07
**Plan horizon:** 2026-08-10 (Mon) → 2026-08-14 (Fri)
**Generated:** 2026-08-07T15:30:00Z
**Mode:** auto (dry-run — no Calendar MCP connected; config file absent, used context defaults)
**Sources:** Read AI (3 meetings with data) + Slack + Gmail

## TL;DR

A full week of product work crystallized into a heavy but manageable agenda: three in-depth 1:1s with Yash (memory/citation) and Ajay (6.4 UX + GTM) produced ~10 direct action items for Vinod. On top of that, Ajay has assigned Vinod to lead a competitive analysis vs Databricks/Snowflake with a mid-next-week SE session, and has asked for a written position on personalization/end-user experience before Monday. Yash is waiting on product feedback on the memory migration UI and a decision on the Query Learnings create path. **Urgent today (Fri Aug 7):** Ramya is waiting on confirmation of tonight's perf review time.

- **Candidates considered:** 44 (14 meeting action items, 9 DMs, 21 @-mentions)
- **Todos accepted:** 17    **For review:** 3    **Dropped:** 24
- **Groups planned:** 5
- **Hours of blocks proposed:** 5.75 h (345 min)
- **Overflow:** 0 groups

---

## The plan

### 1. 6.4 Product Execution

**Block:** 2026-08-10 (Mon) 09:00–10:30  (90 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Send formal note to Yash about delivery expectations and task-assignment changes as agreed with Ajay  *(15 min)*
  - **Source:** [Product, Engineering, and UX Priorities — Aug 4](https://app.read.ai/analytics/meetings/01KZ4JWJFCHW1QF8YH8GZY0S8V)
  - **Why this is for me:** Explicit Vinod action item from the Ajay/Vinod 1:1: "Vinod Iyenger will send the formal note to Yash as discussed."

- Send the product update to the team covering 6.4 priorities and UX decisions from this week  *(15 min)*
  - **Source:** [Product, Engineering, and UX Priorities — Aug 4](https://app.read.ai/analytics/meetings/01KZ4JWJFCHW1QF8YH8GZY0S8V)
  - **Why this is for me:** Explicit action item: "Vinod Iyenger will send the product update to the team shortly after the meeting."

- Map scenarios and propose UI adjustments for day-zero, returning, and enterprise users (home screen / missions / sample prompts)  *(60 min)*
  - **Source:** [Product, Engineering, and UX Priorities — Aug 4](https://app.read.ai/analytics/meetings/01KZ4JWJFCHW1QF8YH8GZY0S8V)
  - **Why this is for me:** Multiple action items from the Ajay/Vinod 1:1: merge per-Kaya chat histories → single universal history; change home screen to "Suggested for you" as primary view; floating/scrolling missions area for returning users; mission/briefing display for non-scheduled missions; fix sample-prompt button click behavior. Vinod owns the design spec.

---

### 2. Quick Replies & Urgent Items (incl. TODAY — Fri Aug 7)

**Block:** 2026-08-10 (Mon) 10:30–11:15  (45 min)
*Status: proposed (dry-run) · Calendar: none connected*

> ⚠️ **Urgent TODAY (Fri Aug 7):** Ramya is waiting for time confirmation before the day ends.

**Todos in this group:**

- **[URGENT — TODAY]** Confirm perf review with Ramya: clarify whether "8:30am IST" means tonight (8:30pm IST = ~8pm PDT Fri) or tomorrow morning Saturday  *(15 min)*
  - **Source:** [DM from Ramya Priya — Aug 7, 06:51 PDT](https://tellius-angularapp.slack.com/archives/D07LJPMT8HM/p1786110710177589)
  - **Why this is for me:** Ramya asked if Vinod is available today and if perf review is happening. Vinod said 8:30am IST but Ramya is uncertain if that means tonight or tomorrow. No confirmation from Vinod yet.
  - **Draft reply:** "Hey Ramya — yes, 8:30 PM your time tonight works. See you then!"

- Reply to Gopi Vamsi on grounding latency data (5–10s SQL, 10–20s Python) in #product-agentic-ai  *(10 min)*
  - **Source:** [#product-agentic-ai — Gopi Vamsi, Aug 6 07:42 PDT](https://tellius-angularapp.slack.com/archives/C079E16KGAZ/p1786027320618339?thread_ts=1785897900.257899&cid=C079E16KGAZ)
  - **Why this is for me:** Gopi @-mentioned Vinod directly to share the latency numbers he was asked for. No reply from Vinod yet.
  - **Draft reply:** "Thanks Gopi — those latency numbers are too high for production. Let's discuss what's causing the Python step lag and if we can parallelize. Will connect on Monday."

- Reply to Manik on checking with Jeh Aerospace about their Claude build vs buy experience  *(10 min)*
  - **Source:** [DM from Manik Aggarwal — Aug 6 08:42 PDT](https://tellius-angularapp.slack.com/archives/D07MCE43X41/p1786030934155279)
  - **Why this is for me:** Manik asked Vinod directly if it's a good idea to reach out to Jeh Aerospace for feedback (not selling, just learning). No reply.
  - **Draft reply:** "Yes good idea — not a selling conversation, just learning. Go ahead and reach out. Would be valuable context for our positioning work."

- Acknowledge Aditya Mathur's document send  *(10 min)*
  - **Source:** [DM from Aditya Mathur — Aug 6 08:33 PDT](https://tellius-angularapp.slack.com/archives/D09V432119N/p1786030420954069)
  - **Why this is for me:** Aditya apologized for missing Vinod's earlier message and sent the full document + diagram. Vinod hasn't acknowledged.
  - **Draft reply:** "Thanks Aditya — got it, will review this week."

---

### 3. GTM Positioning & Competitive Analysis

**Block:** 2026-08-11 (Tue) 09:00–10:15  (75 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Confirm lead ownership on Databricks Genie + Snowflake Cortex competitive analysis; coordinate sections with Chris; target EOD Mon Aug 10  *(15 min)*
  - **Source:** [Group DM — Ajay, Shashank, madhukara, Vinod, Abhishek — Aug 6 08:15 PDT](https://tellius-angularapp.slack.com/archives/C09C59A2153/p1786029302668969?thread_ts=1786029302.668969&cid=C09C59A2153)
  - **Why this is for me:** Ajay directly asked Vinod to "take a lead, get help from Chris and arrange a session with the sales and SE team mid next week." Vinod shared strategic framing but hasn't confirmed ownership or the session date.
  - **Related context:**
    - [Ajay's 4-area breakdown (capabilities, benefits, positioning, GTM)](https://tellius-angularapp.slack.com/archives/C09C59A2153/p1786070272532939?thread_ts=1786029302.668969&cid=C09C59A2153)

- Set up SE enablement session with Chris Walker for mid-next-week (Tue/Wed Aug 12/13)  *(15 min)*
  - **Source:** Same thread as above.
  - **Why this is for me:** Ajay specifically requested Vinod arrange a session with the sales + SE team mid-next-week.
  - **Draft reply to Ajay:** "Got it — will take the lead. Will loop in Chris and get a session on the calendar for Wed Aug 13. We can cover: (1) Databricks Genie comparison, (2) Snowflake Cortex comparison, (3) how to position Tellius when customers are already in the Snowflake ecosystem."

- Share Deep Insights product feedback + positioning spec with Nick and the broader SE team  *(30 min)*
  - **Source:** [Group DM — Ajay to Vinod — Aug 6 11:58 PDT](https://tellius-angularapp.slack.com/archives/C08RREF6WL9/p1786042689138529)
  - **Why this is for me:** Ajay thanked Vinod for his BCD/Bitdefender feedback, then asked to "also share this with Nick and the broader SE team on best way to pitch and position." Vinod wrote a detailed spec for Manik but hasn't shared it more broadly.

- Finalize and share the spec on Deep Insights presentation (mini-app format + transparency) and demo best practices  *(15 min)*
  - **Source:** [Group DM — Vinod's own message — Aug 6 11:39 PDT](https://tellius-angularapp.slack.com/archives/C08RREF6WL9/p1786041737771439)
  - **Why this is for me:** Vinod noted he is "writing a small spec for it and will share the design as well" covering (a) Deep Insights output as mini-app with TLDR + slides, (b) number validation and transparency as a feature. Needs to be published/shared.

---

### 4. Personalization & End-User Experience

**Block:** 2026-08-11 (Tue) 10:15–11:00  (45 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Write up and post Vinod's position on personalization + end-user experience in the team group DM  *(30 min)*
  - **Source:** [Group DM — Ajay, Aug 6 18:51 PDT](https://tellius-angularapp.slack.com/archives/C08RREF6WL9/p1786067519942879)
  - **Why this is for me:** Ajay asked all team members including Vinod to "prioritize and put together your thoughts and discuss, so we can focus on building it next week." Three areas: (1) conversational onboarding/personalization, (2) blank-screen problem, (3) response certification. No reply from Vinod yet — Ajay wants to align before building starts Monday.
  - **Draft reply:** "Great prompt. Here's my initial take on the three areas: (1) Conversational onboarding — this overlaps with the home screen work we're already doing for 6.4. The 'Suggested for you' view + missions surfacing is the non-conversational version. We can layer a quick preference-capture flow on first session. (2) Blank screen — already addressed in the 6.4 plan: preloading sample apps and missions in trial instances. (3) Response certification — citations + number validation is in the 6.4 Yash work. I'll map out how these stitch together as a coherent onboarding arc and share a design by EOD Mon."

- Note connection to the 6.4 UX work already planned (home screen, missions, sample prompts) and flag for Ajay/Shashank  *(15 min)*
  - **Source:** [Product, Engineering, and UX Priorities — Aug 4](https://app.read.ai/analytics/meetings/01KZ4JWJFCHW1QF8YH8GZY0S8V)
  - **Why this is for me:** The UX decisions from the Ajay/Vinod Aug 4 meeting directly address Ajay's three-part end-user experience ask — Vinod should connect these dots explicitly in the response.

---

### 5. Memory, Citations & Yash PRs

**Block:** 2026-08-12 (Wed) 09:00–10:30  (90 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Give Yash product feedback on memory migration UI: how migrated learnings should display on the memory tab; review the three screenshots  *(30 min)*
  - **Source:** [#kaiya-us-team-internal — Yash Bhardwaj, Aug 6 11:41 PDT](https://tellius-angularapp.slack.com/archives/C0BLE3F5Z0R/p1786041714638899?thread_ts=1785993785.429349&cid=C0BLE3F5Z0R)
  - **Why this is for me:** Yash explicitly said "I didn't get any feedback on this UI piece...I'd appreciate your thoughts on this" — @-mentioning both Vinod and Abhishek. Yash also has an open question on what he calls the "first screenshot" needing improvement.

- Product call decision: Query Learnings create path — keep superUser-only (Shashank's proposal) or deprecate?  *(20 min)*
  - **Source:** Same thread as above.
  - **Why this is for me:** Yash flagged this as a product decision: "nobody will be able to create a new query learning, and Memory doesn't cover that case." Shashank proposed superUser-only visibility; Abhishek asked questions but Vinod hasn't weighed in.
  - **Draft reply:** "Agree with Shashank — let's keep Query Learnings visible for superUsers only for now. Query Learnings feed analytic planner specifically, so we don't want to silently remove that capability. Flag it as 'legacy/advanced' in the UI and document it. We can revisit in a follow-up sprint if we want to migrate the analytic planner to use memories too."

- Review Yash's 4 open PRs for memory + citation changes (or delegate review to Abhishek with Vinod sign-off)  *(30 min)*
  - **Source:** [Memory and Citation Engineering — Aug 4](https://app.read.ai/analytics/meetings/01KZ4NJJPG0APNR4N9PSYV0ESJ)
  - **Why this is for me:** Explicit action item from the Aug 4 meeting. Yash re-requested reviews as PRs have all changed.

- Create tracking ticket for citation/mission preview integration and resend Zoom series links to Yash  *(10 min)*
  - **Source:** [Memory, Evals, and SaaS Positioning — Aug 4](https://app.read.ai/analytics/meetings/01KZ9RBQXEH2TWX0K98GMQ7S0E)
  - **Why this is for me:** Two explicit Vinod action items from the meeting.

---

## Review by hand

- **Respond to Bayer Shashank follow-up: who owns the MCP token auth work?**
  - **Source:** [#product-agentic-ai — Shashank, Aug 7 03:28 PDT](https://tellius-angularapp.slack.com/archives/C079E16KGAZ/p1786098512537159?thread_ts=1786064872.707559&cid=C079E16KGAZ)
  - **Reason:** Vinod approved Shashank's recommended approach and asked "who can work on it? and what does their application need to send us?" — Shashank hasn't replied yet. This will likely land as an action item once Shashank responds. Check thread Monday morning.

- **Unilever connect meeting (today, Aug 7) — action items**
  - **Source:** [Gmail — Read AI report: Unilever connect Aug 7 @ 6:30am](https://app.read.ai)
  - **Reason:** Read AI emailed a meeting report but the meeting wasn't yet returned by the API (likely still processing). The snippet mentions "Satish's" validation/scope items. Vinod should review this report for personal action items — may generate Group 1/3 additions.

- **GCP billing: 10% of $50k August budget reached**
  - **Source:** [Gmail — Google Cloud billing alert, Aug 7 04:20 PDT]
  - **Reason:** 10% hit on the first week of August. Not immediately actionable but worth monitoring — if spending is front-loaded, the $50k cap could bind before month end.

---

## Notes on this run

- **Adapters used:** Calendar = none (no calendar MCP connected — dry-run forced), Messaging = Slack + Gmail
- **Config status:** `.friday-followups-config.json` not found. Used defaults: identity.email = vinod.iyengar@tellius.com (from session context), lookback = 7 days, timezone = America/Los_Angeles assumed
- **Read AI:** 3 meetings returned with full data (Memory/Evals Aug 4, Memory/Citation Aug 4, Product/Eng/UX Aug 4). 2 "Zoom Meeting" stubs with no summary/action items — skipped. 1 meeting (Unilever connect Aug 7) not yet returned by API (processing delay).
- **Tier-2 transcript fetch:** 0 (structured action items from meetings were sufficient)
- **Relevance cache hits:** 0 (cache file not present)
- **Errors:** Config file missing (wizard skipped — auto mode); Calendar MCP not connected (no events created); Unilever Aug 7 meeting not yet in Read AI API response (processing lag — check manually).

---

*Generated by friday-followups skill (auto mode, dry-run). Run log: ./.friday-followups-runs.jsonl*
