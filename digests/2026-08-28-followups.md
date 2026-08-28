# Friday Followups — 2026-08-28

**Window analyzed:** 2026-08-21 → 2026-08-28
**Plan horizon:** 2026-09-01 (Mon) → 2026-09-05 (Fri)
**Generated:** 2026-08-28T15:00:00Z
**Mode:** auto (dry-run — no Calendar MCP connected; config file absent, used context defaults)
**Sources:** Read AI (9 meetings) + Slack (20 @-mentions) + Gmail

## TL;DR

Heavy week. Two high-urgency items land **today** (build-v-buy slides promised EOW in this morning's Build v Buy meeting; Clarivate assumption sheet flagged urgent in morning brief). Pladis security questions were needed by yesterday (Paul's meeting was today — respond ASAP). Five major cost-model and competitive-analysis deliverables committed to in Product Team Connect. Searce is waiting on LLM-as-judge criteria and LangSmith access. Six active Slack threads need Vinod's reply. Dev1 Anthropic workspace crossed the $750/month spend threshold.

- **Candidates considered:** 51 (22 meeting action items, 14 Slack @-mentions, 15 Gmail items)
- **Todos accepted:** 22    **For review:** 4    **Dropped:** 25
- **Groups planned:** 8
- **Hours of blocks proposed:** 5.5 h (330 min) — excluding 2 items flagged for today
- **Overflow:** 0 groups

---

## The plan

### 1. Build-v-Buy Materials ⚠️ DUE TODAY

**Block:** 2026-08-28 (TODAY) — work now  (120 min)
*Status: proposed (dry-run) · Calendar: none connected*

> **Committed in today's "Build v Buy (cont)" meeting — EOW.**

**Todos in this group:**

- Prepare updated build-v-buy slides with supporting numbers  *(60 min)*
  - **Source:** [Build v Buy (cont) — Aug 28](https://app.read.ai/analytics/meetings/01M0Z8TYGAJB503GDX54KKWV7H)
  - **Why this is for me:** Explicit meeting action item: "Vinod Iyenger will prepare updated build-versus-buy slides and supporting numbers by the end of the week." Ajay also asked for a "shorter trailer version" and side-by-side comparisons.
  - **Related context:** This feeds the Clarivate pricing conversation and Unilever Monday meeting.

- Create supporting video for the build-v-buy message  *(60 min)*
  - **Source:** Same meeting
  - **Why this is for me:** Two explicit action items: "Vinod Iyenger will create a new version of the build-versus-buy slides" and "Vinod Iyenger will produce a supporting video for the build-versus-buy message."

---

### 2. Clarivate — Assumption Sheet ⚠️ URGENT TODAY

**Block:** 2026-08-28 (TODAY) — ship before EOD  (30 min)
*Status: proposed (dry-run) · Calendar: none connected*

> **Morning brief flagged: "Clarivate assumption sheet — ship today. Pricing is due to Clarivate."**

**Todos in this group:**

- Send Clarivate the assumption sheet / pricing inputs  *(30 min)*
  - **Source:** [Morning Brief Aug 28](https://mail.google.com) + [INT Clarivate Sync — Aug 27](https://app.read.ai/analytics/meetings/01M0JNF0GEQ7JWKP1FQ8GWVBGV)
  - **Why this is for me:** The morning brief explicitly flagged this as the day's #1 urgent item. The INT Clarivate Sync covered white-label deployment across Fusion, Epi, and DLNF reports for top 20 pharma companies — pricing is the outstanding blocker.

---

### 3. Pladis — Security Questions ⚠️ OVERDUE (meeting was today)

**Block:** 2026-09-01 (Mon) 09:00–09:30  (30 min)
*Status: proposed (dry-run) · Calendar: none connected*

> Respond today if possible — Paul's team meeting was this morning.

**Todos in this group:**

- Confirm responses to Pladis security questionnaire for Paul Fullerton  *(30 min)*
  - **Source:** [#prosp-pladis — Paul Fullerton, Aug 27 06:32](https://tellius-angularapp.slack.com/archives/C0ANP1C6AJF/p1787837536265429)
  - **Why this is for me:** Paul explicitly asked Vinod: "please let me know if we can have this back today, we are meeting with the team tomorrow morning." The deal-squad update also says "Vinod to confirm responses to security questions." Close date is **Aug 30** (in 2 days).
  - **Draft reply to Paul:** "Paul — apologies for the delay. The security questionnaire responses: [confirm/attach]. The InfoSec team has already confirmed no concerns on the assessment side (per Graham's update). Happy to review together before your next touch with the team."

---

### 4. Cost Model & Cortex Competitive Analysis

**Block:** 2026-09-01 (Mon) 09:30–11:00  (90 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Prepare side-by-side comparison of Cortex agent execution vs. Tellius missions/stored-procedure approach  *(30 min)*
  - **Source:** [Product team connect — Aug 27](https://app.read.ai/analytics/meetings/01M0X2G5D6AH06MAF4FC14AZK1)
  - **Why this is for me:** Explicit action item: "Vinod Iyenger will prepare a side-by-side comparison of Cortex agent execution and the team's existing mission or stored-procedure approach."
  - **Related context:** Cortex costs ~3-5× more per run ($1.50-$2.00 vs. $0.45-$0.50). Tellius missions use templated SQL vs. Cortex's runtime re-generation.

- Build consolidated cost model using the AGIOS analysis  *(30 min)*
  - **Source:** Same meeting
  - **Why this is for me:** Two explicit items: "Vinod Iyenger will use the AGIOS analysis to build a consolidated cost model" and "Vinod Iyenger will prepare and circulate the cost model for the Telius Plus field-team partnership and related services during the week."

- Refine model assumptions (user volume, mission cadence, query volume, deep-insight volume, per-query costs)  *(30 min)*
  - **Source:** Same meeting
  - **Why this is for me:** "Vinod Iyenger will refine the model's assumptions for user volume, mission cadence, query volume, deep-insight volume, and per-query costs."
  - **Context:** Model uses 3,000 users, ~750K queries, ~150K deep insights, weekly mission execution → ~$230K/yr baseline. Goal is to get recurring run cost to ~$0.20.

---

### 5. Searce / Google External — LLM-as-Judge & LangSmith

**Block:** 2026-09-01 (Mon) 11:00–11:30  (30 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Share domain-specific evaluation criteria for LLM-as-judge setup with Aayush Sharma (Searce)  *(15 min)*
  - **Source:** [#external-tellius-searce-google — Aayush Sharma, Aug 27 06:55](https://tellius-angularapp.slack.com/archives/C09J5V0P6AK/p1787838919757889)
  - **Why this is for me:** Aayush directly asked Vinod: "Could you please share the domain-specific evaluation criteria for the LLM-as-judge setup? This will help us align the grading metrics with your exact requirements."
  - **Draft reply:** "Aayush — here are the evaluation criteria for the LLM-as-judge setup: [criteria]. For domain-specific grading, focus on: (1) factual accuracy against source data, (2) metric definition adherence, (3) query generation correctness for the pharmaceutical domain. I'll share a more detailed rubric by EOW."

- Confirm the node_path-to-model mapping that Searce submitted  *(15 min)*
  - **Source:** [#external-tellius-searce-google — Aayush Sharma, Aug 28 06:45](https://tellius-angularapp.slack.com/archives/C09J5V0P6AK/p1787924734002739)
  - **Why this is for me:** Aayush shared the full model mapping table (e.g., `simplified_text_to_sql → claude-sonnet-5`, `agentic_planner → deepseekv4-pro`) and asked "Please let us know if we are good to proceed with this or if you'd like any changes!" Waiting for Vinod's go/no-go.
  - **Draft reply:** "Thanks Aayush — the mapping looks reasonable. One flag: `simplified_text_to_sql` is on claude-sonnet-5 but `orchestrator_node` is on haiku-4-5 — confirm that's intentional given Haiku's lower SQL reasoning. For the LangSmith `LLMRouter` project, Shashank confirmed the project exists but has no traces yet — it needs to be instrumented before you'll get runs. Happy to connect you with Shashank to unblock."

---

### 6. Unilever Monday Meeting Prep

**Block:** 2026-09-01 (Mon) 11:30–12:00  (30 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Review Unilever's competitive positioning against Claude/Cowork and prep for Satish meeting Monday  *(30 min)*
  - **Source:** [Weekly Ajay <> Solutions team connect — Aug 27](https://app.read.ai/analytics/meetings/01M0WRWQ2EX063AMD5YFHQW32X)
  - **Why this is for me:** Team action: "The team will meet Satish on Monday to review Unilever's internal progress and competitive positioning" and "demonstrate the Unilever write-back capabilities and enhanced materials on Monday."
  - **Context:** Unilever has completed use-case validation and is preparing an internal comparison against Tellius that includes Claude Cowork positioning. Monday is the critical meeting.

---

### 7. 6.4 Release Notes & Marketing Review

**Block:** 2026-09-02 (Tue) 09:00–10:00  (60 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Review Chris Walker's 6.4 capabilities deck draft  *(30 min)*
  - **Source:** [#product-marketing — Chris Walker, Aug 27 13:40](https://tellius-angularapp.slack.com/archives/C03PJHXLKD4/p1787863253140269)
  - **Why this is for me:** Chris explicitly @-mentioned Vinod and Abhishek: "Would love your 👀 to check a few things: (1) Am I missing anything? (2) Do you agree with the key capabilities? (3) Any nuances to add?" Deck covers 6.4 and 6.3.x capabilities with differentiation slides.

- Review Ramya's 6.4 release notes first draft  *(30 min)*
  - **Source:** [#product-marketing — Ramya Priya, Aug 27 23:42](https://tellius-angularapp.slack.com/archives/C03PJHXLKD4/p1787899331476649)
  - **Why this is for me:** Ramya @-mentioned Vinod, Abhishek, and Shashank: "Please review the first draft [here]." Draft incorporates 197 JIRA tickets cross-referenced against 6.3 release notes. Ramya also needs Vinod to confirm items for the 6.4 launch story (Live Apps, self-checking, MCP write-backs).

---

### 8. Staffing & People Actions

**Block:** 2026-09-02 (Tue) 10:00–10:45  (45 min)
*Status: proposed (dry-run) · Calendar: none connected*

**Todos in this group:**

- Get departing team member's resume/profile to share with Amanda Wilson  *(15 min)*
  - **Source:** [Vinod / Amanda - Snowflake access / quick run through — Aug 28](https://app.read.ai/analytics/meetings/01M0ZK7V3VB0A0K7AGT7A2SXXG)
  - **Why this is for me:** Explicit meeting action item: "Vinod Iyenger will ask the departing team member for a resume or profile to share with Amanda." Amanda offered to circulate the profile.
  - **Draft message to departing team member:** "Hey — I wanted to let you know that Amanda Wilson has offered to circulate your profile in her network. Could you send me your resume or LinkedIn when you get a chance? Happy to help."

- Talk to Ajay about Ramya Priya's title and promotion options  *(30 min)*
  - **Source:** [Product Content Automation Strategy — Aug 12 (carryover from last week's digest)](https://app.read.ai/analytics/meetings/01KZEDSP6Z77XRJTW8BT7W3NSM)
  - **Why this is for me:** Carryover from Aug 14 digest. Ramya checking years-of-experience; potential path to "Director of Product Content & Experience." No evidence this was addressed in the past two weeks.
  - **Draft message to Ajay:** "Hey Ajay — still need to talk through Ramya's title/promotion path. She's been doing strong work on content and automation. Would love 15 min to discuss the 'Director of Product Content & Experience' option this week."

---

## Review by hand

- **KPI/Metric Validation Concept — "Meeting participant" action items** — Three action items from the Aug 28 meeting use the generic "Meeting participant" attribution: (a) develop a concise written description of the proposed KPI validation approach, (b) obtain clarification from Ishtav on testing methodology and comparison figures, (c) provide Ishtav with specific instructions for additional testing. These could be Vinod's items. Review [the Read AI report](https://app.read.ai/analytics/meetings/01M0ZFW066F1X7DXQ162CHH9ZP) and claim or delegate.

- **Dev1 Anthropic API spend alert** — The Dev1 workspace crossed its $750/month threshold (email from no-reply@anthropic.com, Aug 28). Not a direct action item but may require a budget review or limit increase decision from Vinod.

- **Novo Nordisk App quality thread** — Nick tagged Vinod/Shashank/Abhishek about production-quality issues with apps created from Missions: dark theme, formatting corruption, null sections. Shashank responded about the dark theme. Vinod should verify whether a response from him is needed or if Shashank's replies are sufficient.
  - **Source:** [#cust-novo-nordisk — Nick Pinero, Aug 28 06:09](https://tellius-angularapp.slack.com/archives/C04AMGV0W8N/p1787922558253879)

- **Product Research/Roadmap demo recordings** — Nithin Raj was asked to share all demo recordings from the Aug 27 session with Abhishek, Vinod, and Ajay for async review. Item is on Nithin, but Vinod should watch for these to land and budget time to review.
  - **Source:** [#product-agentic-ai — Aug 27](https://tellius-angularapp.slack.com/archives/C079E16KGAZ/p1787850219614339)

---

## Notes on this run

- **Adapters used:** Calendar = none (no Calendar MCP connected — dry-run forced), Messaging = Slack + Gmail
- **Config status:** `.friday-followups-config.json` not found. Used defaults: identity.email = vinod.iyengar@tellius.com (from session context), lookback = 7 days, timezone = America/Los_Angeles assumed
- **Read AI:** 9 meetings returned for Aug 21–28. All had full summary + action item data.
- **Tier-2 transcript fetch:** 0 (structured action items sufficient)
- **Relevance cache hits:** 0 (cache file not present)
- **Errors:** Config file missing (wizard skipped — auto mode); Calendar MCP not connected (no events created)

---

*Generated by friday-followups skill (auto mode, dry-run). Run log: ./.friday-followups-runs.jsonl*
