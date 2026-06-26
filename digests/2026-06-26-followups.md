# Friday Followups — 2026-06-26

> **Mode:** auto (dry-run — no Calendar MCP available)
> **Sources:** Read AI (10 meetings) · Slack (DMs + channel mentions) · Gmail
> **Config:** missing — calendar writes skipped; digest only

---

## TL;DR

**10 open loops** where someone is waiting on Vinod across 3 groups.
~6–8 hours of work identified. No calendar blocks created (Calendar MCP not connected).

---

## GROUP 1 — Unified Interface / Architect (Internal Product)

> **Context:** Shubham is about to start building. Nothing is documented. Monday engineering review is already committed.

### 1. Write up unified interface design doc
**Who's waiting:** Abhishek Mathur (+ Shubham Shrivastava)
**Where:** Slack group DM (Shashank, Sriram, Vinod, Abhishek) — Jun 26 06:41 AM
**Quote:** *"were you able to do a writeup for unified interface? imo there are lots of moving parts to this.. and if not documented, we won't be aligned. i'd rather have things documented before Shubham starts working on it."*
**Source:** [Slack thread](https://tellius-angularapp.slack.com/archives/C08RJQ2FYGM/p1782481260772809)

**Drafted reply (Slack):**
> Working on the writeup now — will drop a draft in this thread or a doc link by EOD. Agree it needs to be documented before Shubham picks it up. The key pieces: unified chat-left / artifact-right shell, Build as a tab/toggle inside chat (not a separate screen), mode switching without losing context, and inline-edit draft states. Will include the onboarding flow splits (trial / invite-admin / day-1) as a separate section.

---

### 2. Set up engineering review call with Shri Ram re: Architect direction
**Who's waiting:** Nithya Suri + engineering team
**Where:** Meeting action item — "quick design sync" (Jun 26)
**Commit:** *"Vinod will check engineering availability and set up the review call with Shri Ram / the engineering team"* + *"coordinate the Monday discussion to review unified interface and Architect direction"*
**Source:** [Read AI](https://app.read.ai/analytics/meetings/01KVZS8Y86KJ5G09VM42MMJC85)

**Drafted reply (Slack DM to Shri Ram):**
> Hi Shri Ram — can we sync Mon or Tue this week to review the unified interface + Architect direction? Nithya has the designs ready and we want engineering aligned before anyone starts building. 30 min should do it. What time works?

---

### 3. Give feedback on accordion UI (Shubham's thinking-steps update)
**Who's waiting:** Shubham Shrivastava
**Where:** #product-agentic-ai — Jun 26 10:27 AM
**Quote:** *"We've added an accordion at the top of the steps. Please let us know your feedback."*
**Source:** [Slack thread](https://tellius-angularapp.slack.com/archives/C079E16KGAZ/p1782408465932279)

**Drafted reply (Slack thread):**
> Looks good — accordion is the right call. A few quick asks: (1) make sure the collapsed single line is always updating (not static text like "Thinking…") so users know it's progressing; (2) label it "Thought Process" not "Applied Skills" per our earlier discussion; (3) failed intermediate steps should be hidden or collapsed by default in the final view. Will test on demo2.

---

## GROUP 2 — Customer Commitments (Agios + Bayer)

> **Context:** Monday is a big day — Agios enablement for 10 users and a proposal review with Deepanshu. Bayer 6.3 deployment is also live this weekend.

### 4. Address mission/app refresh reliability concern (Agios POC blocker)
**Who's waiting:** Manik Aggarwal + Shashank L
**Where:** Group DM (Shashank, Sriram, Vinod, Abhishek) + linked thread in #kaiya-team-internal (Jun 26 03:27 AM)
**Quote (Shashank):** *"We should discuss about how to address this on Monday call. I think its a concern that we will have to address."*
**Quote (Manik):** *"On the refresh workflow of the app, I feel this is going to be a big challenge. We have been constantly linking apps with missions for a reliable workflow but if they are disjointed - every single refresh we are going to have issues."* — also tagged Vinod directly asking for guidance.
**Source:** [Slack](https://tellius-angularapp.slack.com/archives/C08RJQ2FYGM/p1782469667164369)

**Drafted reply (Slack group DM):**
> Yes — this is a real gap we need to address. Short-term guidance for Manik/Agios: keep using the mission→app pattern for production setups; app refresh should re-run the linked mission first, then regenerate the app from the mission output. I'll add this to Monday's agenda with a clear answer on the planned fix. For 6.3+ we need a documented "refresh app from mission" flow as a first-class UX action.

---

### 5. Investigate persona-based Kaya/chat restrictions for Agios
**Who's waiting:** Deepanshu Arora (Agios) via Manik + Vinod committed
**Where:** Meeting action item — "Deepanshu / Vinod connect" (Jun 26)
**Commit:** *"Vinod Iyengar will investigate and define mechanisms to restrict Kaya/chat access by user persona and report back"*
**Source:** [Read AI](https://app.read.ai/analytics/meetings/01KVZQPRM6GP2SMJRMX36EBEND)
**Monday meeting:** Proposal review with Deepanshu team already scheduled.

**Drafted reply (Slack DM to Manik to share with Deepanshu before Monday):**
> Before Monday's call: confirmed I'm scoping the persona-based Kaya restriction. Phase 1 plan — restrict certain user roles to prebuilt agents only (no free-form prompting), with a governed chat experience for flows that need user input (like patient ID lookup). I'll have the detailed approach ready to walk through on Monday. Also on track for initial guardrails + version-switching early next week.

---

### 6. Respond to Agios cookie-clearing / app stability issue
**Who's waiting:** Manik Aggarwal (enablement for 10 users Mon)
**Where:** #cust-agios — Jun 25 10:26 AM
**Quote:** *"Again an issue has been reported by our champion at Agios. He had to clear the cookies again to get the application to work. We are having a broader enablement on Monday to 10 team members and want to ensure Tellius application is working fine"*
**Source:** [Slack](https://tellius-angularapp.slack.com/archives/C0A86DM2K1N/p1782408378292049)

**Drafted reply (Slack #cust-agios thread):**
> I'm flagging this to the frontend leads now for a root-cause fix before Monday. In the meantime, Manik — for the 10-person enablement, please have participants clear cookies + cache once before the session as a precaution. I'll confirm status by Sunday evening.

---

## GROUP 3 — Sales / Partnerships

### 7. Reply to Robby Franco (Orb) — review follow-up + confirm Aug 6 check-in
**Who's waiting:** Robby Franco, Orb AE
**Where:** Gmail — "Tellius <> Orb | Discovery - Follow up" (Jun 26 12:31 AM UTC)
**Context:** Robby sent the recording (Gong link) and "Tellius x Orb" deck after today's billing platform demo. Waiting for Vinod to review and confirm the Aug 6 check-in.
**Source:** Gmail thread `19f0156e80235283`

**Drafted reply (Email):**
> Hi Robby — thanks for the quick turnaround on the recap and deck. I've skimmed through it and the BYO-LLM / flat platform fee framing for on-prem is exactly the piece I want to think through more carefully. Aug 6th works for the 15-min check-in — feel free to send a calendar invite. I'll use the time between now and then to map out the pricing scenarios we'd want modeled in the tailored demo. Talk soon.

---

### 8. Estimate LOE for BI migration skills repo (Sigma + ThoughtSpot campaign)
**Who's waiting:** Chris Walker (marketing) + Ajay
**Where:** Group DM thread (C0AT2PBJY13) — Chris asked multiple times, Abhishek said he'd look at the repo
**Quote:** *"@Abhishek Mathur @Vinod Iyengar lmk — in the meantime, I can start the marketing content / distro groundwork"*
**Context:** Chris has a full 1-week rollout plan ready for Sigma + ThoughtSpot migration campaign. Blocked on Vinod/Abhishek's LOE estimate for item #1 (the open-source migration-skills repo and converter plugins).
**Source:** [Slack thread](https://tellius-angularapp.slack.com/archives/C0AT2PBJY13/p1782481235227909)

**Drafted reply (Slack thread):**
> Chris — go ahead and start the marketing content + distro groundwork, that's not blocked on us. For the tooling (item 1): rough LOE is 2–3 eng days per converter plugin (Sigma, ThoughtSpot) once we scope the output format. The framework skeleton (discovery→convert→build→parity-check) is maybe another 1–2 days. Abhishek and I can confirm exact effort after he reviews the repo. I'd suggest we prioritize Sigma first given their current traction — let's align on that and kick it off next week.

---

### 9. Coordinate with Ajay re: Unilever use case + Anoop meeting Tuesday
**Who's waiting:** Ajay Khanna (meeting Anoop in London Tue Jun 30)
**Where:** Group DM (Ajay, Vinod, Abhishek) — Jun 25 + today
**Context:** Ajay is packaging the Unilever P2P/Procure-to-Pay use case as a vertical app. Venkat is wrapping up the two Unilever use cases by Monday. Ajay meeting Anoop (Unilever) in London Tuesday.
**Source:** [Slack](https://tellius-angularapp.slack.com/archives/C08EJ007HLG/p1782482788490369)

**Drafted reply (Slack group DM):**
> Ajay — noted on London Tuesday. Make sure Venkat wraps the two Unilever use cases by Monday EOD. Abhishek and I will review and ensure the vertical app packaging is solid before your meeting. Key message for Anoop: these are near-OOB apps combining insights + missions + FP&A analytics — quick time-to-value, Snowflake-native. Let me know if you need a specific demo scenario prepped.

---

### 10. Review Maithri's mission execution UI design recording
**Who's waiting:** Maithri Udupa + Abhishek (for feedback)
**Where:** Meeting action item — "Research/Feature Discussion" (Jun 26)
**Commit:** *"Maithri Udupa will share the recording to collect feedback from Vinod and Abhishek"*; *"Vinod will review Maithri's UI design as suggested by Ajay"*
**Source:** [Read AI](https://app.read.ai/analytics/meetings/01KVZGTWTRNNK0HFNH2G8WWKAY)

**Drafted reply (Slack to Maithri):**
> Maithri — drop the recording link here when it's up. I'll review by EOD and share thoughts on the outline+flow diagram combination. The approach (editable outline + read-only flow diagram with conditional branches) sounds right to me from the meeting — looking forward to seeing the details.

---

## Review by Hand (Maybe / Unclear ownership)

- **Bayer MCP server question** — Abhishek asked whether Bayer wants to *play* with MCP or has a *production use case*. Shashank noted Naz/Yash could pick this up. Vinod may need to weigh in on the product readiness question before Venkat's meeting with Bayer.
- **Estimator edge-case evaluations** — Vinod committed in the engineering meeting to run additional evals on the estimator (no-fabrication behavior). No external stakeholder waiting yet, but this was a public commitment.

---

## Notes on This Run

- **Calendar MCP:** Not connected — no calendar blocks created. Run as dry-run.
- **Config file:** Missing — wizard skipped (auto mode). To configure, run `friday-followups --reconfigure` interactively.
- **Read AI:** 10 meetings fetched (Jun 19–26); Vinod attended 7 of them.
- **Slack:** Searched DMs + channel @-mentions past 7 days.
- **Gmail:** Scanned unread inbox threads past 7 days; automated alerts filtered out.
- **Granola:** Not connected — skipped.
- **Errors:** None.
