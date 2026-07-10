# Friday Followups — 2026-07-10

> **Mode:** auto (dry-run — no Calendar MCP available)
> **Sources:** Read AI (13 meetings, Jul 3–10) · Slack (DMs + channel @-mentions) · Gmail
> **Config:** missing — calendar writes skipped; digest only

---

## TL;DR

**14 open loops** where someone is waiting on Vinod across 5 groups.
~12–13 hours of work identified. **1 item is due today at 2pm PST.** No calendar blocks created (Calendar MCP not connected).

---

## ⚠️ GROUP 0 — URGENT: Due Today

### 1. Review Manik's Crossmedia RFI responses — DUE 2pm PST TODAY
**Who's waiting:** Manik Aggarwal
**Where:** Group DM (Manik, Vinod, Paul Fullerton) — Jul 9 8:04 PM PDT
**Quote:** *"@Vinod — can I have your eyes on the RFI responses I have prepared for Crossmedia? Would appreciate your input on a few items. Due for submission tomorrow — if you can provide your input before 2pm PST tomorrow would be super helpful."*
**Source:** [Slack DM](https://tellius-angularapp.slack.com/archives/C0BGE4HJ37C/p1783652688123499)
**Doc:** [RFI Google Doc](https://docs.google.com/document/d/1dMfjr3EFzqEo73ar9z4nuOjUS_ccp5NE_bFGx4j-QdE/edit?tab=t.0)

**Drafted reply (Slack DM):**
> Manik — on it now, will add comments to the doc before 2pm. Pinging you once done.

---

## GROUP 1 — GTM & Sales Execution

> **Context:** Multiple deliverables from this week's GTM/Product Sync and GTM/Content meeting that Ajay and others are actively waiting on.

### 2. Draft pricing and sizing options (TA-bundle vs. seat-pack)
**Who's waiting:** Ajay Khanna
**Where:** Meeting action item — "Product Sync" (Jul 8)
**Commit:** *"Vinod Iyengar will draft the pricing and sizing options (put the proposals on paper for side-by-side review)"*
**Source:** [Read AI](https://app.read.ai/analytics/meetings/01KWZ249WR5P88CWWTW4MTXKY8)

**Drafted reply (Slack DM to Ajay):**
> Ajay — pricing doc coming tonight/tomorrow AM. Will lay out both models (TA-bundle vs. seat-pack with overage backstop) side by side including pool sizing rules. I'll also include the credit-consolidation approach (single pool, differentiated seat types) as we discussed.

---

### 3. Send draft GTM/enablement material to Ajay before broader sharing
**Who's waiting:** Ajay Khanna
**Where:** Meeting action item — "Product Sync" (Jul 8)
**Commit:** *"Vinod Iyengar will send the draft GTM/enablement material to Ajay for review before broader sharing."*
**Source:** [Read AI](https://app.read.ai/analytics/meetings/01KWZ249WR5P88CWWTW4MTXKY8)

**Drafted reply (Slack DM to Ajay, bundled with #2):**
> Also sending you the GTM/enablement draft alongside the pricing doc — please review before I share with the broader team.

---

### 4. Propose free-usage promotion for apps (remove credit friction)
**Who's waiting:** Chris Walker, Amanda Wilson, Ajay
**Where:** Meeting action item — "GTM / Content / Outbound Help from Product" (Jul 9)
**Commit:** *"Vinod Iyengar will propose a temporary free-usage promotion for apps to remove credit friction and encourage trial use."*
**Source:** [Read AI](https://app.read.ai/analytics/meetings/01KX43HNBN89CEP1X8ACC9Z7H8)

**Drafted reply (Slack DM to Abhishek + Chris):**
> Proposal for free apps: give trial users 30 days of unlimited app credits (no per-action billing), capped at X app runs/month. Goal is to remove the "60 credits for one insight" surprise that's killing trial conversion. I'll write up a one-pager with mechanics and margin impact — should be ready by end of next week.

---

### 5. Give feedback on Ajay's Pharma/Snowflake positioning doc
**Who's waiting:** Ajay Khanna
**Where:** Group DM (Ajay, Shashank, Madhukar, Vinod, Abhishek) — Jul 9 9:38 PM PDT
**Quote:** *"Here you go for my take for Tellius positioning for Pharma commercial teams leveraging Snowflake... Please let me know for any feedback or comments."*
**Source:** [Slack thread](https://tellius-angularapp.slack.com/archives/C09C59A2153/p1783658338748489)
**Doc:** Ajay's artifact linked in thread

**Drafted reply (Slack group DM):**
> Good framing Ajay. One addition to Madhukar's comment: in the cost/TCO section, emphasize that with missions running at rep×HCP×daily frequency, the per-LLM-call structure of Cortex agents becomes prohibitive at scale — Tellius abstracts that with caching, templated SQL, and plan reuse. Also: the AutoBV vs. single-semantic-view point is strong, lead with that in the differentiation section.

---

## GROUP 2 — Engineering / Product Decisions

> **Context:** Engineering team is waiting on Vinod's input on several cross-cutting decisions from this week's research/product meetings.

### 6. Co-own Cortex-vs-Tellius solutions slides with Abhishek
**Who's waiting:** Abhishek Mathur (+ solutions team)
**Where:** #product-agentic-ai eng action items (Jul 9)
**Commit:** *"Abhishek Mathur · Vinod Iyengar — build 2–3 solutions-team slides: Cortex-vs-Tellius use-case guidance + productionization gaps"*
**Source:** [Slack thread](https://tellius-angularapp.slack.com/archives/C079E16KGAZ/p1783616660776319)

**Drafted reply (Slack to Abhishek):**
> Abhishek — let me take the first pass on the Cortex-vs-Tellius slides. I'll structure as: (1) which use cases are fine on Cortex Agents alone, (2) where Tellius is required (scale/consistency/finished output), (3) productionization risk matrix. Can have a draft by Monday. Should we sync Tue AM to review?

---

### 7. Review Templated SQL document (Shashank's doc)
**Who's waiting:** Abhishek Mathur, Shashank L
**Where:** #product-agentic-ai eng action items (Jul 9)
**Commit:** *"Vinod Iyengar — review the Templated SQL document Shashank L shared and give feedback; discuss tomorrow morning"*
**Source:** [Slack thread](https://tellius-angularapp.slack.com/archives/C079E16KGAZ/p1783616644831199)

**Drafted reply (Slack to Shashank + Abhishek):**
> Shashank — sharing link to the Templated SQL doc here? I don't see it pinned. Will review today/tomorrow and add comments — I'm aligned on the direction (immutable templates, user-triggered resync, no silent rewrites). Key thing I want to check is how we handle multi-source BV scenarios.

---

### 8. Review and approve sample apps/data for trial (after Ankit+Shashank first-pass)
**Who's waiting:** Ankit Kumar Singh, Shashank L (trial readiness)
**Where:** Meeting action item — "Recurring: Weekly Plan" (Jul 9)
**Commit:** *"Vinod will review and approve the sample apps and data after the first-level review"*
**Source:** [Read AI](https://app.read.ai/analytics/meetings/01KX4X435MNBA5A3XRETMR3K9T)

**Drafted reply (Slack DM to Shashank):**
> Shashank — once you and Ankit have done the first-pass review on the sample apps/data, drop a link here and I'll do the approval review. Let's aim to complete this by Tuesday so trial has clean assets for the week.

---

### 9. Free trial UX changes: architect routing, CTA, and sample data loading
**Who's waiting:** Lisa McElwain, Amanda Wilson, Chris Walker (trial readiness)
**Where:** Meeting action items — "Quick Sync: Free Trial" (Jul 8)
**Commit:** Multiple Vinod actions: route users to Architect by default, make connect-data CTA prominent, load sample data into trial instance ("targeting completion in a few days")
**Source:** [Read AI](https://app.read.ai/analytics/meetings/01KWZ0E95GCDY8RXWJJKXZ8WGT)

**Drafted reply (Slack DM to Rakesh/Sriram, copied Amanda + Lisa):**
> For the trial UX sprint: I've finalized the three quick-win changes from our sync: (1) route post-login directly to Architect if no BV exists, (2) replace the multiple CTAs with a single prominent "Connect your data" overlay, (3) load e-commerce sample dataset so every new trial user has data to explore. I'll spec these out with Jira tickets by Monday. Rakesh/Sriram — please flag if any of these have backend dependencies I should know about.

---

## GROUP 3 — Partners & Cloud

### 10. Ask contact to set up SI delivery lead introductions (TCS, Wipro, etc.)
**Who's waiting:** Colin Raaberg
**Where:** Meeting action item — "Product Execution Morning Stand-up" (Jul 8)
**Commit:** *"Vinod Iyengar will ask his contact to set up introductions to SI delivery leads (e.g., TCS and Wipro) and will schedule the initial calls"*
**Source:** [Read AI](https://app.read.ai/analytics/meetings/01KX1AD2XD5SNANQRXRMT019RE)

**Drafted reply (Slack DM to Colin):**
> Colin — I'm reaching out to my contact today to arrange intro calls with the SI delivery leads at TCS and Wipro. I'll CC you once I get confirmation of interest. Should take a few days to get a response.

---

### 11. Reply to Google Cloud MSR — acknowledge June report, reschedule Jul 14 meeting
**Who's waiting:** Karoly (Google Cloud XWF team)
**Where:** Gmail — "Google Cloud Monthly Service Review (MSR) - June 2026" (Jul 9, 9:57pm UTC)
**Context:** Karoly noticed Vinod declined the Jul 14 MSR review meeting and is sharing the June report. Needs acknowledgment and either a reschedule or alternative engagement.
**Source:** Gmail thread `19f48e2ed6d57578`

**Drafted reply (Email):**
> Hi Karoly — thanks for sending the June report, I'll review it this week. Re the Jul 14 meeting — I had a conflict at that time but would like to reschedule. Can you share 2–3 alternative windows the week of Jul 14 or the following week? Happy to discuss both May and June together. Appreciate your patience.

---

## GROUP 4 — Quick Async

### 12. Reply to Yash: "Which workspace?"
**Who's waiting:** Yash Bhardwaj
**Where:** DM (Vinod ↔ Yash) — Jul 10 7:06 AM PDT
**Context:** Vinod asked "Can we add it please" and Yash asked for clarification on which workspace. No reply from Vinod yet.
**Source:** [Slack DM](https://tellius-angularapp.slack.com/archives/D08MT79KX88/p1783692416267409)

**Drafted reply (DM):**
> Sorry Yash — I meant [workspace name]. Can you add it there?
*(Note: Vinod should fill in the specific workspace name based on context of the preceding conversation.)*

---

### 13. Give Ajay background on Performance Edge embedding use case
**Who's waiting:** Ajay Khanna
**Where:** #product-agentic-ai eng action items (Jul 9)
**Commit:** *"Ajay Khanna — sync with Vinod Iyengar for the full background/purpose on the Performance Edge embedding use case"*
**Source:** [Slack thread](https://tellius-angularapp.slack.com/archives/C079E16KGAZ/p1783616610888139)

**Drafted reply (Slack DM to Ajay):**
> Ajay — for Performance Edge: this is a customer's existing analytics app with AI icons on each widget. Clicking opens a Kaiya contextual chat via MCP — the customer authenticates once via OAuth, no Tellius login needed. App parameters (brand/region/quota/filters) are passed as soft context to Kaiya text-to-SQL / DI. The key use case: on-demand AI analysis within their existing tool without migrating to Tellius. Can do a quick 15 min call if this needs more color.

---

### 14. Think through compounding cost implications (memory/caching changes)
**Who's waiting:** Ajay Khanna (raised in Product Research/Roadmap Jul 8)
**Where:** Meeting action item — "Product Research/Roadmap Internal Discussion" (Jul 8)
**Commit:** *"Vinod Iyengar will think through compounding implications and look into the cost impact related to those changes"*
**Source:** [Read AI](https://app.read.ai/analytics/meetings/01KWYBVM93T78CGR5E7ZKWW1VR)

**Drafted reply (Slack DM to Ajay):**
> Ajay — on the compounding cost analysis: my quick take is that templated SQL + plan reuse can cut ~40–50% of per-mission LLM calls (the planner and SQL agent steps are the expensive ones; once templatized they don't re-run unless schema changes). The bigger lever is smaller model routing for execution tasks (Haiku for SQL validation, full model only for planning). I'll model this out concretely with assumptions by next week.

---

## Review by Hand (Maybe / Unclear ownership)

- **Regeneron "better together" material** — Vinod told Ajay/Nick on Jul 9 "I'll send over some material today evening." It's now Jul 10. Unclear if this was sent — worth confirming with Ajay/Nick whether received.
- **Sriram's front-end items list** — Sriram committed to "share the list of missing front-end items with Vinod and confirm which items are already assigned." Waiting on Sriram, but Vinod should confirm receipt once shared.
- **Agios/Deepanshu pricing meeting (today)** — Vinod is presenting pricing to Deepanshu at Agios today. Savannah and Ajay have prepped the deck/tabs; this is in active motion.

---

## Notes on This Run

- **Calendar MCP:** Not connected — no calendar blocks created. Run as dry-run.
- **Config file:** Missing — wizard skipped (auto mode). To configure, run `friday-followups --reconfigure` interactively.
- **Read AI:** 13 meetings fetched (Jul 3–10, 2 pages); Vinod attended 10 of them.
- **Slack:** Searched DMs + channel @-mentions past 7 days.
- **Gmail:** Scanned unread inbox threads past 7 days; automated (Read AI reports, Jira, calendar invites) filtered out.
- **Granola:** Not authenticated — skipped.
- **Errors:** config_missing (auto mode, wizard skipped), calendar_mcp_missing (no calendar writes), granola_mcp_missing (not authenticated).
