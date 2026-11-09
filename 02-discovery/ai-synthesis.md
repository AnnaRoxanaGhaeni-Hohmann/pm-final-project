# AI Synthesis, Product Health & Insights Summary (Module 2)

## Responses
- **Assumption to validate #1:** is there an actual need for an additional credit card
- **Assumption to validate #2:** are interest a reason to not use the product
- **Assumption to validate #3:** is the usage intuitive
- **Moment of misery / red flag #1 (e.g., “user gave up after 3 tries”):** covered payment options are not clear e.g. installments
- **Moment of misery / red flag #2:** fear of credit score worsening
- **Moment of misery / red flag #3:** declines in shop not clearly communicated to customer
- **Product Health & Insights Summary (Claude's output):** # Product Health & Insights Summary
**BU Pay & Credit: First Consumer Card (Friends-and-Family Test Launch, Germany)**

*Basis: fictional practice data; 1,200 invitees over four months. Figures are illustrative and should not be presented as Riverty facts. The test group skews toward employees (53% of invitees), so approval and repayment signals likely overstate real-market performance.*

## Executive Summary
The card converts well through application and approval (48.8% of invitees approved, 93.3% of completed identity checks), and heavy BNPL users spend actively, yet the experience loses people at the points where technical behavior meets user expectation: 26.5% of approved users never activate, and in-store payments fail visibly and without explanation. Stability problems are concentrated in a few high-trust moments (declines, wallet provisioning, notifications), but their impact is amplified by fragmented balances, mismatched due dates, and unclear credit implications. Retention is the open question: roughly a third of activated users lapse within a month, and the card's differentiation against existing bank cards and BNPL apps is not yet established.

## Thematic Synthesis

### 1. Technical Stability (In-Store and Wallet)
In-store payment is the weakest technical area. Decline rates in physical shops run several times the overall decline rate (8.7% vs. 3.5% in Month 4) and rose again after improving in Months 2–3. Failures give users no explanation, and wallet provisioning leaks a large share of activated cards. Because tap-to-pay is the default habit for most consumers, a single unexplained failure often ends in a return to the debit card.

- **In-store declines with no reason shown (T-101): Critical.** 48 declines logged; in-store decline rate peaked at 12.1% in Month 1 and was 8.7% in Month 4. Participants report abandoning the card after one failure.
- **Phone wallet provisioning fails or is abandoned (T-102): High.** 143 activated cards never reached the wallet (only 66.8% of activated cards were added), directly limiting in-store usability.
- **Delayed purchase push notifications (T-108): High.** Late alerts lead users to believe a payment failed and to pay twice with another card.

### 2. Onboarding and Activation
Top-of-funnel interest is healthy, and identity verification and approval perform well. The largest controllable loss occurs after approval, between approval and activation, where over a quarter of approved users stall. Secondary friction exists in the identity-check retry flow. Light BNPL users activate markedly less (62.0% vs. 82.6% for heavy users), suggesting that value perception, not only mechanics, drives this drop.

- **Approval-to-activation drop-off: High.** 73.5% of approved users activate (155 approved people lost); lowest among light BNPL users.
- **Identity check re-requests document after failed upload (T-106): Medium.** Some applicants abandon at this step; overall identity completion is still 87.7%.
- **Activation-to-habit gap: Medium.** Of activated cards, 81.2% make a first purchase, but only about 59% reach three or more purchases in the activation month.

### 3. Trust and Clarity
Users struggle to build an accurate mental model of what they owe, when, and what the card means for their finances. The card and existing pay later products are presented as separate worlds, with different totals, screens, and due dates. Unanswered questions about credit score impact and an inconsistent instalment option add uncertainty, which matters acutely for cautious users who equate "credit card" with interest and debt.

- **Split balance views for card and pay later orders (T-103): High.** Participants cannot tell which total is authoritative; echoed directly in interview feedback.
- **Mismatched statement and pay later due dates (T-104): High.** Two reminders in one week for different amounts create confusion and raise missed-payment risk.
- **Instalment option appears post-purchase for only some categories (T-105): Medium.** Perceived as random; instalments account for only 17.4% of purchases, though share is much higher among heavy users (25.4%).
- **No guidance on credit score impact (T-107): Medium.** A content gap affecting a sensitive, trust-defining question.
- **Instalment/credit framing anxiety: Medium.** Light users react negatively to interest-bearing credit language.

### 4. Engagement, Retention and Value Proposition
Usage is concentrated in heavy BNPL users (5.82 purchases per active month vs. 2.46 for light users) and in partner-merchant spend (63.1% of volume), with monthly spend per active card trending upward. However, early-cohort retention shows meaningful decay: about 66% of Month 1 activators were still active one month later and roughly 51–55% after two to three months, with later cohorts tracking similarly. Qualitative feedback points to competing habits (bank card in shops, existing BNPL apps) and to cashback as a trial driver rather than a retention driver. Merchants question what the card gives them at their own checkout, and SME merchants value traffic-driving offers over generic acceptance.

- **Unproven differentiation versus bank card and existing BNPL apps: High.** Users cite habit, app fatigue, and low top-of-mind recall for in-store use.
- **Retention decay across cohorts: High.** Approximately a third lapse within one month of activation.
- **Merchant value proposition unclear (enterprise and SME): Medium.** Concern that the card could divert customers to large marketplaces.
- **Incentive dependence: Medium.** Cashback may inflate trial without sustaining use.

### 5. Support Load and Operating Constraints
Most support demand is likely driven by the unexplained failures and unclear balances above rather than by independent defects, since users are asking questions the product does not currently answer (declines, which total is real, credit impact). Organizational constraints also shape how quickly any of this can change.

- **Reactive support volume from unexplained declines, duplicate reminders and missing help content: Medium.** Inferred from ticket themes rather than measured contact volumes.
- **Proposition change cycle time: Medium.** Pricing, credit policy and terms changes require approval measured in months.
- **Data representativeness: Medium.** Employee-heavy test group (639 of 1,200 invitees) likely flatters approval and repayment; churn and share of existing users who would take a card are not measurable in this test.

### Minor Technical Debt
Wording and help-content gaps, minor notification timing variances outside the affected shops, and inconsistent labeling across the card and pay later screens.
- **Did the AI catch the specific moment of misery / pain point you found in Step 1?:** yes, tecnical problems have been identified, also the problem of not full products understanding
- **Did it smooth over a critical frustration into a generic bullet point?:** yes but not all well structured
- **Did the AI try to suggest features or a roadmap despite the constraints?:** No , not specifically
- **Logic leak / hallucination #1 (e.g., “AI suggested a new search bar feature, roadmap leak”):** _(not filled in)_
- **Logic leak / hallucination #2:** _(not filled in)_
