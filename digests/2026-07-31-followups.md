# Friday Followups — 2026-07-31

**Window analyzed:** 2026-07-24 → 2026-07-31
**Plan horizon:** 2026-08-03 (Mon) → 2026-08-07 (Fri)
**Generated:** 2026-07-31T15:00:00Z
**Mode:** auto (dry-run — no Calendar MCP connected; config file absent, used context defaults)
**Sources:** Read AI (0 meetings returned) + Slack

## TL;DR

Vinod is back from vacation to a full plate: two product decisions from Thursday's demo are explicitly assigned to him, plus a new hire intro, a people conversation with Ajay on team delivery, and active customer asks from Novo Nordisk and the Bayer account. Read AI returned no meetings for the window (possibly a sync delay); meeting action items were recovered from the #product-agentic-ai demo notes posted to Slack.

- **Candidates considered:** 20 (2 meeting action items via Slack notes, 13 DMs, 20 @-mentions; overlaps removed)
- **Todos accepted:** 11    **For review:** 3    **Dropped:** 6
- **Groups planned:** 5
- **Hours of blocks proposed:** 4.5 h (270 min)
- **Overflow:** 0 groups

---

## The plan

### 1. Kaiya / Agentic AI Product Decisions

**Block:** 2026-08-03 (Mon) 09:00–10:15  (75 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Decide on MCP output format: concise summary vs full output, and confirm consistent behavior across MCP, Slack and Teams  *(30 min)*
  - **Source:** [#product-agentic-ai demo notes — MCP × Meta Agent section](https://tellius-angularapp.slack.com/archives/C079E16KGAZ/p1785440531125679?thread_ts=1785440386.378269&cid=C079E16KGAZ)
  - **Why this is for me:** Explicitly listed as a Vinod action item in the demo rollup: "decide whether to keep the concise MCP summary or send full output, and confirm one consistent behavior across MCP, Slack and Teams (leaning to short summary + 'show more')"

- Give feedback on Yash's memory migration UI (banner design + button label + superuser-vs-all-users scoping)  *(15 min)*
  - **Source:** [#kaiya-us-team-internal — Yash Bhardwaj, Jul 30](https://tellius-angularapp.slack.com/archives/C0BLE3F5Z0R/p1785430645518649)
  - **Why this is for me:** Yash directly @-mentioned Vinod alongside Abhishek and Shashank asking for product feedback on the UI and a scoping decision (admin-only vs every user)

- Review Bayer account status and identify product support areas for next 2–3 weeks  *(30 min)*
  - **Source:** [#cust-bayer — Ajay Khanna, Jul 30](https://tellius-angularapp.slack.com/archives/C066S3T0TGU/p1785459143877879)
  - **Why this is for me:** Ajay's message explicitly asks Shashank and Vinod (product team) to be aware and support multiple delivery streams. Major push required over next 2–3 weeks.

---

### 2. Release Validation — Non-Live Join Coverage

**Block:** 2026-08-03 (Mon) 10:30–11:30  (60 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Plan and execute a full-fledged testing pass across datasets (Health Agent against old existing BVs vs new ClickHouse-based non-live join path) to validate end-to-end accuracy and stability for the 6.x release  *(60 min)*
  - **Source:** [#product-agentic-ai demo notes — Data Architect / Non-Live Join Coverage section](https://tellius-angularapp.slack.com/archives/C079E16KGAZ/p1785440484728259?thread_ts=1785440386.378269&cid=C079E16KGAZ)
  - **Why this is for me:** Explicitly listed as Vinod's action item in the eng rollup: "plan and execute a full-fledged testing pass across datasets (Health Agent against old existing BVs vs new) to validate end-to-end accuracy and stability for the release"

---

### 3. Team & People

**Block:** 2026-08-04 (Tue) 09:00–10:00  (60 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Schedule and hold 30-min intro meeting with Jason Moore (new hire who joined while Vinod was on vacation)  *(30 min)*
  - **Source:** [DM from Jason Moore, Jul 30](https://tellius-angularapp.slack.com/archives/D0BLVADPYFQ/p1785421125459959)
  - **Why this is for me:** Jason reached out directly: "I think I joined while you were on vacation — would love to find 30 mins with you to meet you and get your perspective on where we are going as a company." No response from Vinod yet.
  - **Draft reply:** "Hey Jason — sorry for the slow reply, just got back from vacation. Would love to connect! Happy to do Tuesday or Wednesday this week — does any 30-min slot work for you? Just send me a calendar invite."

- Follow up with Ajay Khanna on Naz and Yash delivery gap discussion  *(30 min)*
  - **Source:** [DM from Ajay Khanna, Jul 29](https://tellius-angularapp.slack.com/archives/D07LK35P63D/p1785344404773849)
  - **Why this is for me:** Ajay explicitly flagged this to discuss "when you are back later this week." Vinod is now back. Topics: how to scope + hand off work, how to set targets, how to track progress for Naz and Yash.
  - **Draft reply:** "Hey Ajay — back now, let's sync on this. This week works — can we do 30 min Tuesday or Wednesday? The scoping/handoff gaps you described make sense and I want to talk through what we can do on our side."

---

### 4. Customer: Novo Nordisk Feature Request

**Block:** 2026-08-03 (Mon) 14:00–14:30  (30 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Review the Novo Nordisk feature request (Nick's question in #cust-novo-nordisk) with Shashank and Ajay, and respond to Nick on difficulty/feasibility  *(30 min)*
  - **Source:** [#cust-novo-nordisk — Nick Pinero, Jul 31](https://tellius-angularapp.slack.com/archives/C04AMGV0W8N/p1785502319973959)
  - **Why this is for me:** Nick @-mentioned Shashank, Vinod, and Ajay directly asking "would this feature be difficult to implement?" in an active customer channel. Needs a response today or early next week.
  - **Related context:** Earlier today Nazmul posted an update in #unstructured-engg on the novodev S3 download fix and file upload regression (react-side fix being PR'd).

---

### 5. Admin & Business

**Block:** 2026-08-04 (Tue) 14:00–14:45  (45 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Confirm (or decline) rescheduling the Shashank/Sriram/Abhishek call to Monday morning — Shashank is on leave Fri Jul 31  *(15 min)*
  - **Source:** [Group DM — Sriram Kumar, Jul 30](https://tellius-angularapp.slack.com/archives/C08RJQ2FYGM/p1785433401258939)
  - **Why this is for me:** Sriram directly asked Vinod and Abhishek if they're moving the call to Monday (Aug 3). Abhishek said "I'm ok with that" but Vinod hasn't confirmed yet.
  - **Draft reply:** "Works for me — Monday morning it is."

- Respond on Snowflake Marketplace / Stripe approach  *(15 min)*
  - **Source:** [Group DM — Ramya Priya, Jul 29](https://tellius-angularapp.slack.com/archives/C0BGYFRC5GD/p1785392460358509)
  - **Why this is for me:** Ramya clarified the Stripe flow (Contact Sales only, no public pricing, private offers settle via Stripe). Abhishek noted inconsistencies and appeared to be asking Vinod to weigh in. Context: "we add this info in here to get through the checklist for snowflake."
  - **Draft reply:** "Makes sense Ramya — proceeding with Contact Sales only / no public pricing works for me. Let's add this to the checklist and move forward as Abhishek suggested."

- Review Ramp transactions for July month-end (memo + itemized receipts for expenses >$30)  *(15 min)*
  - **Source:** [Group DM with Jimena Bedoya + Colin Raaberg, Jul 31](https://tellius-angularapp.slack.com/archives/C0AADC2PV1R/p1785506400890889)
  - **Why this is for me:** Month-end Ramp reminder from Jimena — submit before books close.

---

## Review by hand

Items flagged `maybe` — possibly for Vinod but not confident enough to auto-book.

- **Weigh in on Personalization feature design/execution plan**  *(from Slack mention — Group DM)*
  - **Source:** [Group DM Ajay+Shashank+Vinod+Abhishek, Jul 30](https://tellius-angularapp.slack.com/archives/C08RREF6WL9/p1785461171069409)
  - **Reason for uncertainty:** Ajay asked Abhishek and Vinod if the approach/design/execution plan for Personalization was finalized. Abhishek replied with initial thoughts. Vinod hasn't weighed in, but Abhishek may be handling it. Check if input is still needed.

- **Implicit vs Explicit memory save — Vinod's call revisited**  *(from Slack mention — #kaiya-us-team-internal)*
  - **Source:** [#kaiya-us-team-internal, Jul 29–30](https://tellius-angularapp.slack.com/archives/C0BLE3F5Z0R/p1785393116086839)
  - **Reason for uncertainty:** Abhishek pushed to enable implicit memory save. Shashank noted Vinod had previously decided to keep it explicit-only (in a conversation with Yash). Abhishek wants to revisit. No direct question to Vinod in the thread, but his original decision is being relitigated.

- **Abhishek's cryptic "i dont know how i feel about this.. this sounds strange"**  *(from DM)*
  - **Source:** [DM from Abhishek Mathur, Jul 30](https://tellius-angularapp.slack.com/archives/D08BK24BQV9/p1785421042488189)
  - **Reason for uncertainty:** No thread context available; unclear what Abhishek was reacting to. Likely connected to one of the ongoing product discussions (Snowflake Marketplace, Personalization, or memory). May warrant a quick check-in.

---

## Notes on this run

- **Adapters used:** Calendar = none (no calendar MCP connected — dry-run forced), Messaging = Slack
- **Config status:** `.friday-followups-config.json` not found. Used defaults: identity.email = vinod.iyengar@tellius.com (from session context), lookback = 7 days, timezone = America/Los_Angeles assumed
- **Read AI:** 0 meetings returned for 2026-07-24 → 2026-07-31. Meeting action items recovered from Slack #product-agentic-ai (Thu Jul 30 demo notes). May indicate Read AI sync lag or meetings not yet processed.
- **Tier-2 transcript fetch:** 0 (not needed; structured action items from Slack notes were sufficient)
- **Relevance cache hits:** 0 (first run this config; `.friday-followups-cache.json` not present)
- **Errors:** Config file missing; Calendar MCP not connected (no events created). No other errors.

---

*Generated by friday-followups skill (auto mode, dry-run). Run log: ./.friday-followups-runs.jsonl*
