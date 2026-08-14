# Friday Followups — 2026-08-14

**Window analyzed:** 2026-08-07 → 2026-08-14
**Plan horizon:** 2026-08-17 (Mon) → 2026-08-21 (Fri)
**Generated:** 2026-08-14T15:00:00Z
**Mode:** auto (dry-run — no Calendar MCP connected; config file absent, used context defaults)
**Sources:** Read AI (5 meetings with data) + Slack (DMs + mentions) + Gmail

## TL;DR

Five Read AI meetings this week surfaced explicit Vinod action items across three deals (Columbia, Unilever, Bayer/Novo) and two internal workstreams (Debugger/Yash, Ramya/Content). On top of meeting items, Slack has 6 open threads where people are waiting directly on Vinod: Colin needs board product slides (deadline was today), Manik needs a Genie vs. Kaiya slide for Columbia, Savannah needs Claude vs. Tellius content for Unilever, Shashank needs two spending decisions, and Paul needs a quick Pladis reply. The single most time-sensitive item is **NOT in the meetings or Slack**: Ajay asked yesterday to let Yash go today (Friday) and needs a quick chat with Vinod before that happens.

- **Candidates considered:** 44 (16 meeting action items, 12 Slack DMs, 16 @-mentions)
- **Todos accepted:** 19    **For review:** 4    **Dropped:** 21
- **Groups planned:** 7
- **Hours of blocks proposed:** 6.25 h (375 min)
- **Overflow:** 0 groups

---

## The plan

### 1. Yash Departure — Conversation & Notice

**Block:** 2026-08-14 (TODAY — Fri) 16:00–17:00  (60 min)
*Status: proposed (dry-run) · Calendar: none connected*

> ⚠️ **URGENT TODAY (Fri Aug 14):** Ajay said "notice given this Friday." This must happen today.

**Todos in this group:**

- **[URGENT — TODAY]** Quick chat with Ajay to align on the conversation before speaking with Yash  *(15 min)*
  - **Source:** [Group DM — Ajay, Shashank, Vinod, Colin — Aug 12](https://tellius-angularapp.slack.com/archives/C0BPUMATB2A/p1786587223260519)
  - **Why this is for me:** Ajay said "Let's have a quick chat tomorrow about this" (yesterday = Aug 13) and asked Colin to share the narrative with Vinod. Ajay's plan: 4 weeks notice + severance folded in, last day Sept 11 (H-1B accommodation). Vinod delivers the message.
  - **Draft reply to Ajay:** "Ready to chat — let me know when you have 10 mins."

- **[URGENT — TODAY]** Inform Yash of the decision, with the H-1B accommodation clearly communicated  *(45 min)*
  - **Source:** Same Ajay DM thread; Ajay drafted the full conversation guide
  - **Why this is for me:** Vinod is the designated person to deliver the news. Key points per Ajay's guide: (1) Lead with company-level strategic shift, not personal judgment. (2) Acknowledge Yash's specific contributions (MCP auth, memory migration, debug agent). (3) Clearly state: last day Sept 11, 4 weeks' notice with severance folded in. (4) Have COBRA/benefits/follow-up contact ready. (5) Leave room for Yash to ask questions — especially on H-1B timeline.

---

### 2. Columbia Deal — Deck, Demo & Positioning

**Block:** 2026-08-17 (Mon) 09:00–10:30  (90 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Share the architecture presentation deck with Dan (Columbia decision-maker)  *(15 min)*
  - **Source:** [Columbia | Tellius: Architecture Discussion — Aug 14](https://app.read.ai/analytics/meetings/01KZVRKY4EJZRWT8Z2QYB99HEF)
  - **Why this is for me:** Explicit meeting action item: "Tellius team will share the architecture presentation deck with Columbia."

- Schedule a follow-up demo session for Jeff Madison (Columbia enterprise architect) focused on agent authoring and platform depth  *(15 min)*
  - **Source:** Same meeting
  - **Why this is for me:** Explicit action item: "Tellius team will schedule a follow-up session to demonstrate agent authoring and the platform in greater detail for Jeff Madison." Jeff's key objection was build-vs-buy (Databricks Agent Bricks/Genie) — the follow-up should directly address this.
  - **Draft outreach to Devin/Manik:** "Let's get the Jeff Madison demo on the calendar this week — focus on agent authoring, cached reasoning cost advantage (~100x vs re-running frontier models per step), and our Unity Catalog integration story. 30-45 min."

- Work with Manik on a Genie vs. Kaiya differentiator slide for the Columbia deck  *(45 min)*
  - **Source:** [DM from Manik Aggarwal — Aug 13 22:28](https://tellius-angularapp.slack.com/archives/D07MCE43X41/p1786685283409129)
  - **Why this is for me:** Manik asked directly: "I think we need a slide for showing differentiator of latest Genie vs Tellius Kaiya — do we have anything related to that available? otherwise I can put something together and send it across for your input." No reply yet.
  - **Draft reply to Manik:** "Good call — we don't have a dedicated Genie slide yet. Let me put together the key differentiator points: (1) orchestration/guardrails/checkpointing at scale, (2) cached plan reasoning (~100x token cost reduction vs. Genie re-running frontier models), (3) multi-source knowledge beyond just Unity Catalog (unstructured docs, web), (4) our action layer (Slack/email distribution, PowerPoint outputs, scheduled missions). Can you do the visual? I'll send you the copy."

- Initiate pricing/TCO discussion with Devin to define workload inputs needed for Columbia's estimate  *(15 min)*
  - **Source:** Same meeting
  - **Why this is for me:** Action item: "Tellius team will prepare workload-based pricing and total-cost calculations when Columbia's expected workloads are defined." First step is to get Columbia to define their expected workloads.

---

### 3. Unilever — Claude/Cowork vs. Tellius Differentiation Content

**Block:** 2026-08-17 (Mon) 10:30–11:30  (60 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Provide Savannah with Claude/Cowork-vs-Tellius comparison narrative for two-slide Unilever deck  *(60 min)*
  - **Source:** [#prosp-unilever — Savannah Miller, Aug 13 18:27](https://tellius-angularapp.slack.com/archives/C0B19HPU9SM/p1786670866339849)
  - **Why this is for me:** Savannah explicitly asked "@Vinod Iyengar can you help provide this information" with a detailed outline: (a) document what happened when raw data was uploaded into Claude — missed UOM inconsistencies, wrong leakage calc due to missing currency conversion; (b) the iteration loop where Claude requires manual correction vs. Tellius auto-flagging UOM mismatches; (c) why Tellius scales where Claude doesn't — repeatability on 50K+ invoices, centralized metrics layer, production path.
  - **Draft reply to Savannah:**

    > Savannah — great framing. Here's the content for both slides:
    >
    > **Where Claude/Cowork stops:**
    > - When I uploaded the raw Unilever invoice data into Claude, it processed the data as-is without flagging UOM inconsistencies (e.g., cases vs. pallets mixed). It calculated leakage without applying currency conversion, producing a wrong number.
    > - The fix loop: I had to manually tell Claude what it got wrong, one correction at a time. It doesn't know what it doesn't know. Every cycle requires a human prompt.
    >
    > **Where Tellius picks up and follows through:**
    > - The semantic layer applies the UOM and currency conversion rules *before* analysis — the system flags mismatches proactively, not after you've already shipped a wrong number to Anoop.
    > - Repeatability: the logic runs on the next 50K invoices automatically, without prompting. Claude can technically do this too, but it requires re-prompting every session — there's no persistent governed model.
    > - Centralized metrics layer: defined calcs, scheduled runs, async alert monitoring (e.g., flag OSF gaps before they hit the claim pack). None of this exists in a Claude workflow.
    > - Production path: async processing, alerting, rollout across categories/regions. Claude is a session; Tellius is an operating system.
    >
    > Feel free to adjust the framing — happy to review the slide draft.

---

### 4. Board Slides & Spending Decisions

**Block:** 2026-08-14 (TODAY — Fri) 15:00–15:30  (30 min)
*Status: proposed (dry-run) · Calendar: none connected*

> ⚠️ **Board slides deadline may have already passed** (Colin's drop-dead was 11:30 AM ET today). Send immediately regardless.

**Todos in this group:**

- Send product slides to Colin for the board review  *(10 min)*
  - **Source:** [Group DM (Amanda, Vinod, Colin) — Aug 13](https://tellius-angularapp.slack.com/archives/C0AFA7L086B/p1786639924433709) and [DM from Colin — Aug 13 15:39](https://tellius-angularapp.slack.com/archives/D0A0LTX2J6L/p1786660740737889)
  - **Why this is for me:** Colin asked twice — first in the group DM ("can you send me the Product slides for the board"), then in a direct DM. The group DM context shows Colin said drop dead time was 11:30 AM ET today. No response from Vinod visible.
  - **Draft reply to Colin:** "Sorry for the delay — sending now. [attach slides]"

- Confirm to Shashank whether support can be removed from Year 2 per the agreement ($5,904/mo)  *(10 min)*
  - **Source:** [Group DM (Shashank, Vinod, Colin) — Aug 13](https://tellius-angularapp.slack.com/archives/C0BP07YMPV1/p1786631886309409)
  - **Why this is for me:** Shashank asked Vinod directly: "Can you confirm if we can disable it as per the agreement." This is a decision only Vinod can make (contract knowledge).

- Confirm Pendo renewal pause — $10k, auto-renewing end of August  *(5 min)*
  - **Source:** [Group DM (Ajay, Shashank, Sriram, Jimena, Vinod, Abhishek, Colin) — Aug 12](https://tellius-angularapp.slack.com/archives/C0A8FSP6PU1/p1786534419477229)
  - **Why this is for me:** Shashank asked: "Wanted to check if you paused the Pendo auto renewal?" Tellius uses PostHog for recording instead. No response from Vinod visible.
  - **Draft reply:** "Yes, let's stop the Pendo renewal — we're not using it and PostHog covers our needs. Go ahead and disable."

- Reply to Paul Fullerton on Pladis use case ("good to share back?")  *(5 min)*
  - **Source:** [#prosp-pladis — Paul Fullerton, Aug 14 06:08](https://tellius-angularapp.slack.com/archives/C0ANP1C6AJF/p1786712922885299)
  - **Why this is for me:** Paul shared the Pladis use case (AI Analyst across NIQ/Kantar/retailer MCPs/YouGov for Savoury Biscuits category review, host-and-run in their VPC) and then asked Vinod if it's good to share back. Quick directional reply needed.
  - **Draft reply:** "Yes, that framing is solid — good to share. The Commercial Equation decomposition + OSF monitoring + unified view across four sources is the right story for them."

---

### 5. Engineering & Product — Debugger, Repos & PRs

**Block:** 2026-08-17 (Mon) 14:00–15:30  (90 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Send Yash the screenshot of the problematic mission/debug session where debug-agent and Claude disagreed  *(10 min)*
  - **Source:** [Debugger UI and Agent Decisions — Aug 12](https://app.read.ai/analytics/meetings/01KZEZ5E76R3YSNP90PXM4PTKJ)
  - **Why this is for me:** Explicit meeting action item: "Vinod Iyenger will send a screenshot of the problematic mission/debug session to Yash for investigation."

- Review (or delegate with sign-off) Yash's MCP auth PRs — 4 PRs must ship together  *(45 min)*
  - **Source:** [#kaiya-us-team-internal — Yash Bhardwaj, Aug 12](https://tellius-angularapp.slack.com/archives/C0BLE3F5Z0R/p1786587359656889)
  - **Why this is for me:** Yash posted detailed update for Vinod/Abhishek/Shashank/Ajay on 4 coordinated PRs for MCP auth (middleware, React, MCP server, Kaiya). Key warning: all 4 must deploy together — half-deploy causes every MCP tool call to 403. Vinod tagged explicitly.
  - **Related:** Memory + Learnings deprecation (5 PRs, also must ship in same release — Yash flagged known edge case with Shashank).

- Set up Cursor React project and repo access for Ramya (for automated docs/video generation)  *(30 min)*
  - **Source:** [Product Content Automation Strategy — Aug 12](https://app.read.ai/analytics/meetings/01KZEDSP6Z77XRJTW8BT7W3NSM)
  - **Why this is for me:** Explicit meeting action item: "Vinod Iyenger will help set up the Cursor React project and repo access on the next call so real HTML and assets can be used for documentation and videos."

- Accept OpenRouter invitation to join Tellius organization  *(5 min)*
  - **Source:** [Gmail — Shashank L invitation via OpenRouter, Aug 14](https://mail.google.com)
  - **Why this is for me:** Shashank invited Vinod to the Tellius organization on OpenRouter. Quick one-click action.

---

### 6. AG Grid Renewal — Re-book & Respond

**Block:** 2026-08-17 (Mon) 11:30–11:45  (15 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Reply to Holly Hopkins and re-book the AG Grid renewal call (original booking was auto-canceled)  *(15 min)*
  - **Source:** [Gmail — Holly Hopkins at AG Grid, Aug 14 08:51](https://mail.google.com)
  - **Why this is for me:** Vinod replied to Holly's renewal notice saying "I have something booked for Monday on your calendar." But the AG Studio demo booking was subsequently canceled (adam.wang@ag-grid.com). Holly replied "I can't seem to see anything on my calendar?" — she's waiting. Need to clarify or rebook.
  - **Draft reply to Holly:** "Hi Holly, apologies — the original booking seems to have been canceled. Can we find 30 min this week? I'm available Monday afternoon or Tuesday morning PT. Let me know what works for you. Thanks, Vinod"

---

### 7. People — Ramya Title & Promotion

**Block:** 2026-08-18 (Tue) 09:00–09:30  (30 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Talk to Ajay about Ramya Priya's title and promotion options  *(30 min)*
  - **Source:** [Product Content Automation Strategy — Aug 12](https://app.read.ai/analytics/meetings/01KZEDSP6Z77XRJTW8BT7W3NSM)
  - **Why this is for me:** Explicit meeting action item: "Vinod Iyenger will talk to Ajay about possible title and promotion options for Ramya." Ramya's path discussed: "director of product content and experience." She needs to first confirm years-of-experience (Ramya is checking this).
  - **Draft message to Ajay:** "Hey Ajay, I wanted to talk to you about a title/promotion conversation with Ramya. She's been doing strong work on the content and automation side and I think there's a case for moving her toward Director of Product Content & Experience. Would love to sync on this for a few minutes."

---

## Review by hand

- **Amanda Wilson + Chris Walker connection** — Amanda asked in a group DM whether Vinod and Chris have "connected on this one already" (a topic that ties to a blog, possibly around competitive positioning or a new asset). Not clear what "this" refers to. Review the group DM (C08J1KVFZ6U, Aug 14 07:02) and connect with Chris if relevant.
  - **Source:** [Group DM — Amanda, Chris, Vinod, Abhishek, Aug 14](https://tellius-angularapp.slack.com/archives/C08J1KVFZ6U/p1786716124219039)

- **Novo Nordisk Vizpad question** — Vinod asked "but you manually created the Vizpad?" and Nick replied "the Novo team created it in production environment." Seems informational, not a clear Vinod action, but worth verifying the production Vizpad is working as expected given the 4 open bugs on the Novo Nordisk account.
  - **Source:** [Group DM thread — Aug 14 04:39](https://tellius-angularapp.slack.com/archives/C09LFCZE35K/p1786707553719069)

- **Weekly Plan meeting (Aug 13) — action items** — Read AI emailed a report for the Weekly Plan meeting (Sriram demo of group analytics, product/engineering updates) but this meeting was not yet returned by the API (likely still processing). Check the Read AI report email or app.read.ai for Vinod-specific action items when available.
  - **Source:** [Gmail — Read AI report for Recurring: Weekly Plan, Aug 14 05:02](https://mail.google.com)

- **Reusable Agent Architecture (Snowflake call) action items** — Vinod was the Tellius presenter on this call (Ajay Khanna, Atul Khanna, Wayne Wilson et al.). Several action items are attributed to "conference room participant" / "meeting participant" — unclear which belong to Vinod vs. the telecom customer team. Review the [Read AI report](https://app.read.ai/analytics/meetings/01KZVJWTQCKJY0V8J6ZS25J22N) and identify any Tellius-side deliverables for Vinod.

---

## Notes on this run

- **Adapters used:** Calendar = none (no calendar MCP connected — dry-run forced), Messaging = Slack + Gmail
- **Config status:** `.friday-followups-config.json` not found. Used defaults: identity.email = vinod.iyengar@tellius.com (from session context), lookback = 7 days, timezone = America/Los_Angeles assumed
- **Read AI:** 5 meetings returned with full data for Aug 7–14. Weekly Plan (Aug 13) not yet returned by API — likely processing lag.
- **Tier-2 transcript fetch:** 0 (structured action items from meetings were sufficient)
- **Relevance cache hits:** 0 (cache file not present)
- **Errors:** Config file missing (wizard skipped — auto mode); Calendar MCP not connected (no events created); Weekly Plan Aug 13 meeting not yet in Read AI API response (processing lag — check manually).

---

*Generated by friday-followups skill (auto mode, dry-run). Run log: ./.friday-followups-runs.jsonl*
