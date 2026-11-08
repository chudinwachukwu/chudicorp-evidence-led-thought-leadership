# Case study: evidence-led professional knowledge sharing

**Summary.** This case study describes how documented experience from a real website build became a structured, evidence-led programme of professional education. Its subject is the programme (Project B), not the website itself.

**Project A: the underlying experience.** ChudiCorp.com was created in May 2026 and implemented through Lovable. It offers business-insight services under the line "From Ideas to Insights". Visitors browse a portfolio that is clearly labelled as demonstration work. They can submit a business problem and receive a tailored quote for one-time consulting, which the owner reviews and delivers manually.

Intensive work in October 2026 added the following:
- a protected admin area with eleven request statuses;
- owner-editable private pricing, kept separate from customer quotes;
- Stripe checkout tested only in Test Mode, including successful, declined and authentication-failure cases;
- checkout recovery safeguards;
- hourly reconciliation monitoring;
- spam protection (hidden trap, Cloudflare check, repeat-submission limits);
- search foundations (sitemap, robots rules, canonical tags);
- the removal of public prices from the pages and from the data those pages request;
- admin sign-in with a business email address.

This work is recorded as 24 milestones, M01–M24. The latest production acceptance decision was **conditional**. These checks are still open:
- a live idea submission and real rate-limit testing;
- delivery of failure-alert and password-reset emails;
- a runtime test by a signed-in non-administrator;
- deeper recovery tests.

**The professional problem.** The lessons from this work were real but scattered. Sharing them publicly carried two risks:
- **overclaiming**, for example presenting sandbox payments as revenue, or a discovered sitemap as search success;
- **oversharing**, for example customer references, payment identifiers or security details.

**What I did.**
- Identified transferable lessons and grouped them into five workstreams: Business Analysis and Process Improvement; Product and Project Delivery; Data Analytics and Evidence; AI Governance and Information Protection; and Systems Integration and Commercial Assurance.
- With ChatGPT's assistance, prepared 15 posts and graphics. Some posts draw directly on ChudiCorp milestones. Others (Posts 05 and 10) are clearly labelled hypothetical scenarios.
- Reviewed claims and disclosure boundaries, approved the final content and scheduled all 15 posts manually.

**Later assurance.** After scheduling, I commissioned formal reviews in Lovable to make the portfolio robust:
- **Stage A:** traced each post to milestones, evidence types and limitations.
- **Stage B:** checked all 15 graphics for accuracy, privacy and clarity. 8 passed outright and 7 passed with stated qualifications. None needed redesigning and none exposed private information.
- **Stage C:** produced this documentation.

**Deliverables.**
- 15 approved posts and 15 approved graphics.
- The five-workstream structure.
- An evidence classification and milestone traceability.
- Editorial and disclosure safeguards.
- A scheduled publication calendar.
- GitHub and Behance documentation.
- A performance and retrospective framework.

**Limitations.**
- The milestones do not establish unconditional production acceptance.
- The payment examples are Stripe Test Mode tests, not earned revenue.
- The NHS and AI-workflow examples are hypothetical.
- The Search Console screenshots show successful sitemap processing and 20 discovered pages, with last-read dates of 26 October and 5 November 2026. Their capture times are not independently established, and they do not show indexing, traffic or commercial outcomes.
- Actual LinkedIn performance will be incorporated when supplied and verified.

**Professional value.** The project shows how business analysis, product thinking, project governance, evidence management, visual communication and responsible AI assistance combine in credible knowledge sharing. The central lesson is to separate clearly what was implemented, what was tested, what was independently verified and what remains uncertain.
