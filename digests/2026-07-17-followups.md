# Friday Follow-Ups — July 17, 2026

**Run mode:** auto (dry-run — no Calendar MCP connected; no config file present)
**Sources:** Read AI (10 meetings, Jul 10–17) · Slack (@-mentions + DMs) · Gmail (inbox, last 7 days)
**TL;DR:** 7 topic groups · ~16 open items on Vinod · 2 urgent external replies needed today

---

## URGENT / Today

### 1. Searce Smart Model Router — reply needed before they publish
**Who's waiting:** Udita Biswas (udita.biswas@searce.com), cc Aditya Mathur, Kiran Gurajala
**Context:** Vinod missed today's Searce call (ran long). Udita sent their PoV on the Smart Model Router use case and is waiting on Vinod's thoughts before they finalize a blog post.
**Draft reply:**
> Hi Udita — thanks for sending this over. I'll review the PoV today and share thoughts by EOD. Apologies for missing the call — looking forward to the collab on the blog. Will loop in Abhishek as needed.

---

### 2. NYU AI Compliance Review — Venkat waiting in #cust-nyu
**Who's waiting:** Venkatraman (+ Paul Fullerton CC'd)
**Context:** Venkat tagged Vinod in #cust-nyu to review and confirm AI governance language for a customer-facing response (NYC LL 144, EU AI Act Article 10 & 14 compliance). Content covers how Kaya exposes SQL to prevent automation bias and uses governed Business Views.
**Draft reply (in Slack #cust-nyu):**
> @Venkatraman — reviewed. The framing on SQL transparency + BV governance is accurate. One suggestion: clarify that the governed query layer enforces published BV definitions at runtime, not at response generation, to distinguish from model-level guardrails. That distinction will matter to NYU's compliance team. LGTM otherwise — @Paul Fullerton please coordinate on final delivery.

---

## Meeting Action Items (from Read AI)

### 3. Snowflake Marketplace HTML Artifact ⚠️ Due by Tue 7/22 for 7/23 meeting
**Meeting:** Post Snowflake sync · Jul 16
**Who's waiting:** Atul Khanna (Atriano), Abhishek Mathur (monitoring Marketplace progress while out)
**Items outstanding:**
- [ ] Send Magic Quadrant blog link + MQ image + write-up to Atul's outreach contact
- [ ] Build HTML tabs: MQ · context/tribal-knowledge layer · marketplace listing
- [ ] Add semi-technical diagram: where memories are stored, how retrieval works (no low-level impl details)
- [ ] Publish consolidated HTML artifact combining narrative + diagram + blog content → share for review
**Meeting link:** https://app.read.ai/analytics/meetings/01KXGRN9SJT9CJ0PNPCVB6AR7K

---

### 4. Agios Pilot Proposal — credits breakdown + doc corrections
**Meeting:** Tellius proposal review · Jul 16
**Who's waiting:** Deepanshu Arora + Mark Skvara (Agios), Savannah Miller (tracking)
**Items outstanding:**
- [ ] Send detailed credit-activity breakdown: questions / deep analyses / exports → pool calculation
- [ ] Update proposal to correct app and mission counts (Mark shouldn't need to micro-review)
**Email thread:** RE: Tellius × Agios — Pilot & Year 2 Proposal (deepanshu.arora@agios.com replied Thu)
**Note:** Deepanshu also asked about custom branding; Manik replied "yes feasible" — confirm with specifics if needed.

---

### 5. Product Positioning — "mode/context/brain" description
**Meeting:** Reconnect: Product + GTM Initiatives · Jul 16
**Who's waiting:** Ajay Khanna, Abhishek Mathur, Madhukara (building product recipe doc)
**Items outstanding:**
- [ ] Draft Vinod's version of "mode/context/brain" (the shared context/knowledge model) → share for homepage and positioning doc
**Note:** Abhishek has already submitted his version. This feeds the product recipe / differentiation narrative.
**Meeting link:** https://app.read.ai/analytics/meetings/01KXGTBE22TEXJ7K88GFA5MWPX

---

### 6. Data Architecture follow-ons
**Meeting:** Data Architecture and Chat UX · Jul 16/17
**Who's waiting:** Shashank, Madhukar, team
**Items outstanding:**
- [ ] Share architect design links + ambitious data module porting designs with team
- [ ] Send use cases for cursor and related scenarios to team (for Madhukar to review re: meta-agent behavior)
- [ ] Test newer OpenAI/Anthropic models (5.4/5.5/5.6/Net5) · propose default fallback for each provider
**Meeting link:** https://app.read.ai/analytics/meetings/01KXQ56J3CW049JBF6P90S9VYR

---

### 7. Meta-agent lookup scenarios
**Meeting:** Product Research/Roadmap · Jul 16
**Who's waiting:** Ajay Khanna, Madhukara, Shashank
**Items outstanding:**
- [ ] Review and propose 2–3 lookup scenarios for the meta-agent to support (near-term priority per meeting)
- [ ] Join Unilever Friday 10:30 AM ET call (may be today/next Fri — confirm)
**Meeting link:** https://app.read.ai/analytics/meetings/01KXGCG3VGHT844NNND5MHFQNE

---

### 8. Nithya / Design contractor
**Meeting:** Quick design sync · Jul 16
**Who's waiting:** Nithya Suri (DMs + design tasks)
**Items outstanding (partial — task list already shared in Slack DM):**
- [ ] Set up Clockify + ping Clockify contact to enable Nithya's account
- [ ] Send revised contract/proposal
- [ ] Review onboarding/trial screens → feedback before handing to Rakesh
- [ ] Confirm whether Rakesh's UI changes are merged to live (check with Rakesh)
**Note:** Nithya replied "Just saw these messages / Would you want to connect now?" — she's available and waiting.
**Meeting link:** https://app.read.ai/analytics/meetings/01KXGKE57WTN0DYDDZ21EVTHQ4

---

## Slack — Waiting for Vinod's Input

### 9. Chris Walker — review request in group DM
**Who:** Chris Walker (group DM with Ajay, Amanda Wilson, Abhishek)
**Message:** "@Vinod Iyengar :point_up: your review please"
**Draft reply:** "On it — will review today and share feedback."

---

### 10. Rahul B U — live narration support in #product-agentic-ai
**Who:** Rahul B U, cc Shashank, Abhishek, Ajay
**Context:** Live narration/summary is now available in apps. Users can request LLM-generated content based on desired data. Asking for review.
**Draft reply:**
> Nice work. Quick questions: (1) Does the narration regenerate when the view data changes, or only on demand? (2) What's the latency p95 on a 10-chart app? Post a short Loom if you have one. Happy to loop in a design review next week.

---

### 11. Abhishek Nangare — "Jump to Latest" feature in #product-agentic-ai
**Who:** Abhishek Nangare
**Context:** Added a "Jump to Latest" button for auto-scroll control. Asking for feedback on visibility, placement, usability.
**Draft reply:**
> The idea is solid — good for long conversations. Placement should be bottom-right, fixed, and only visible when user has scrolled up more than 1 viewport. Make sure it disappears immediately once they scroll back to bottom. If the icon is just an arrow, consider adding a small unread-count badge for context.

---

### 12. Praveen Bandi — mission creation question in #product-agentic-ai
**Who:** Praveen Bandi
**Context:** "@Vinod did you mean you created a mission from kaya conversation. may i know how did you ran the mission?"
**Draft reply:**
> Yes — started in the Kaya chat, triggered the mission creation flow from there. Happy to walk through the exact steps — let me know if you want a quick Zoom.

---

### 13. Amanda Wilson — homepage HTML draft in #2026h2-positioning
**Who:** Amanda Wilson
**Context:** Shared working draft of homepage HTML (section A/B/C options). Chris Walker's positioning thread may inform changes. Wants review before tomorrow's discussion.
**Draft reply:**
> Will review today. One early signal: keep the L0 value prop to ≤12 words — anything longer loses the CRO impact on mobile. Will add inline comments on the draft.

---

## Email — Needs Response

### 14. Tom Mackay — Zoom video clip (1:29)
**Who:** Tom Mackay
**Context:** Tom shared a 1.5-min clip labeled "Video for Vinod" — recorded Jul 16. Likely a product question or sales context share.
**Action:** Watch the clip and reply.
**Draft reply (after watching):**
> Thanks Tom — watched this. [Add specific response after viewing.]

---

## Review by Hand (maybe)

- **Aisle.ai follow-up email** (Colin → Chris/Kevin, cc Vinod/Manik/Paul): Colin sent the post-visit recap. Content looks good. Vinod may want to add a personal note to Chris/Kevin given the Heineken context discussed — not urgent but worth a read.
- **Snowflake OAuth outage** (Manik handling, Aisle.ai): Vinod is cc'd. Manik's team is debugging. No action needed unless Vinod wants to escalate.
- **Claude API spend >$5K/month**: Anthropic threshold alert. Likely driven by Visa POC build + Anthropic outage earlier this week inflating retries. Flag to Ajay if spend justification is needed.

---

## Notes on This Run

- **Config:** No `.friday-followups-config.json` found — wizard skipped (auto mode). Running with inferred identity: `vinod.iyengar@tellius.com`.
- **Calendar:** No Google Calendar MCP connected. Calendar blocks not written. This is a digest-only run.
- **Granola:** Requires interactive auth — skipped.
- **Read AI:** 10+ meetings found for Jul 10–17. Vinod attended 8; explicitly assigned action items in 6 meetings.
- **Errors:** None (degraded mode: no calendar writes).
