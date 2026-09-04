---
marp: true
theme: default
paginate: true
size: 16:9
footer: Strategic Pricing | MBA Presentation | April 2026
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap');

:root {
  --color-background: #ffffff;
  --color-foreground: #1f2937;
  --color-heading: #1e3a8a;
  --color-accent: #2563eb;
  --color-border: #d1d5db;
  --font-default: 'Inter', 'Segoe UI', sans-serif;
}

section {
  background-color: var(--color-background);
  color: var(--color-foreground);
  font-family: var(--font-default);
  box-sizing: border-box;
  border-top: 8px solid var(--color-heading);
  position: relative;
  line-height: 1.7;
  font-size: 20px;
  padding: 52px 60px 70px 60px;
}

h1, h2, h3 { font-weight: 700; color: var(--color-heading); margin: 0; padding: 0; }
h1 { font-size: 52px; line-height: 1.2; letter-spacing: -0.02em; }
h2 {
  position: absolute;
  top: 36px; left: 60px; right: 60px;
  font-size: 34px;
  padding-bottom: 14px;
  border-bottom: 3px solid var(--color-accent);
}
h2 + * { margin-top: 100px; }
h3 { color: var(--color-accent); font-size: 21px; margin-top: 18px; margin-bottom: 8px; font-weight: 600; }

ul, ol { padding-left: 28px; margin: 0; }
li { margin-bottom: 10px; line-height: 1.7; }
li li { font-size: 0.9em; color: #374151; margin-bottom: 4px; }

footer { font-size: 14px; color: #9ca3af; position: absolute; left: 60px; right: 60px; bottom: 24px; }

section.lead {
  border-top: none;
  display: flex; flex-direction: column; justify-content: center;
  background: linear-gradient(135deg, #1e3a8a 0%, #1d4ed8 55%, #0ea5e9 100%);
  padding: 60px 80px;
}
section.lead footer { display: none; }
section.lead h1 { color: #ffffff; font-size: 54px; margin-bottom: 20px; line-height: 1.2; }
section.lead p { font-size: 22px; color: rgba(255,255,255,0.85); line-height: 1.6; }
section.lead .tag {
  display: inline-block;
  background: rgba(255,255,255,0.15);
  border: 1px solid rgba(255,255,255,0.3);
  color: #ffffff; font-size: 13px; font-weight: 600;
  letter-spacing: 0.08em; text-transform: uppercase;
  padding: 6px 16px; border-radius: 20px; margin-bottom: 24px;
}

.highlight {
  background: linear-gradient(135deg, #eff6ff, #dbeafe);
  border-left: 4px solid var(--color-accent);
  padding: 14px 20px; border-radius: 0 8px 8px 0;
  margin: 14px 0; font-size: 19px;
}

.warn {
  background: #fff7ed;
  border-left: 4px solid #f97316;
  padding: 14px 20px; border-radius: 0 8px 8px 0;
  margin: 14px 0; font-size: 19px;
}

.two-col { display: grid; grid-template-columns: 1fr 1fr; gap: 28px; margin-top: 8px; }

.card {
  background: #f8fafc; border: 1px solid #e2e8f0;
  border-top: 4px solid var(--color-accent);
  border-radius: 8px; padding: 18px 20px;
}
.card.orange { border-top-color: #f97316; }
.card h3 { margin-top: 0; font-size: 18px; }

table { border-collapse: collapse; width: 100%; margin: 8px 0; font-size: 17px; }
th, td { border: 1px solid var(--color-border); padding: 10px 14px; text-align: left; }
th { background-color: var(--color-heading); color: #ffffff; font-weight: 600; }
tr:nth-child(even) { background-color: #f9fafb; }
strong { color: var(--color-heading); font-weight: 700; }
</style>

<!-- _class: lead -->
<!-- _paginate: false -->

<div class="tag">Strategic Pricing · MBA Presentation</div>

# Airline Pricing Strategy

A Framework Analysis Using the Value Cascade,
the Seven Pricing Games & Conjoint Analysis

April 2026

---

## Agenda

1. **Industry Overview** — What makes airline pricing unique
2. **Diagnosing the Game** — Which BCG pricing game airlines play
3. **The Value Cascade** — Where airlines create and fail to capture value
4. **The Challenge** — Segment mismatch and revenue leakage
5. **Conjoint Analysis** — Measuring what passengers truly value
6. **Recommendations** — Three strategic priorities
7. **Anticipating Response** — Risks and competitive dynamics

---

## What Makes Airline Pricing Unique

Airlines operate at the intersection of almost every pricing challenge simultaneously:

- **Fixed capacity** that cannot be adjusted once a flight is scheduled
- **Perishable inventory** — an empty seat at departure is revenue lost forever
- **Radically different customers** sharing the same physical product
- **Transparent pricing** exposed across dozens of comparison platforms
- **High emotional sensitivity** — passengers feel price unfairness acutely

This combination makes airline pricing one of the most strategically rich environments to study — and one of the most consequential to get wrong.

<div class="highlight">
Pricing is not just a revenue tool for airlines. It is the primary mechanism through which they communicate value, define their brand, and shape customer behavior.
</div>

---

## Diagnosing the Game: Airlines Play Two Games at Once

Using BCG's Strategic Pricing Hexagon, airlines sit at a rare intersection.

<div class="two-col">
<div class="card">
<h3>The Dynamic Game (Primary)</h3>

Fixed capacity, fluctuating demand, low marginal cost, and real-time competition demand continuous price adjustment. This is yield management — the core operational pricing engine. Every seat on every route is re-priced constantly based on booking pace, competitor moves, and historical demand signals.
</div>
<div class="card orange">
<h3>The Choice Game (Strategic)</h3>

Airlines also present a structured lineup of cabin classes and fare tiers designed to shape customer behavior. The way options are framed — Basic Economy, Main Cabin, Comfort+, Business — is designed to migrate customers up the fare ladder, exploiting behavioral biases more than price precision.
</div>
</div>

<div class="highlight">
The strategic opportunity lies in the <strong>gap between these two games</strong>: airlines are technically sophisticated at dynamic pricing but often blunt in how they frame choices and communicate value to different segments.
</div>

---

## The Value Cascade: Value Creation

Nagle's framework begins with a foundational question: **what is the customer's total economic value?**

**Total Economic Value = Reference Price + Differentiation Value**

For airline passengers, the calculation looks different by segment:

- The **reference price** is the cheapest available fare on the same route — set by ultra-low-cost carriers like Spirit or Frontier
- The **monetary differentiation value** is real and measurable: reliability, fewer delays, nonstop routing, flexibility to change plans
- The **psychological differentiation value** is where legacy carriers earn their premium: brand trust, loyalty status recognition, the sense of being treated as a valued customer

<div class="warn">
Most airlines articulate their differentiation value in marketing — but fail to <strong>price to it</strong>. The result: premium customers pay less than their true WTP, and undifferentiated customers overpay relative to what they receive.
</div>

---

## The Value Cascade: Value Communication

How airlines communicate price shapes willingness-to-pay before the customer even sees a number. Nagle's nine pricing effects are all present in aviation:

- **Competitive-Reference Effect** — passengers anchor on the lowest fare in search results. Airlines can reframe the reference by positioning against a higher-priced alternative, not a cheaper one
- **Switching-Cost Effect** — loyalty programs are the most powerful switching cost in consumer pricing; elite status members are dramatically less price-sensitive
- **Difficult-Comparison Effect** — fare class complexity, bundling differences, and cabin tier naming make direct comparison hard, which reduces sensitivity
- **Shared-Cost Effect** — business travelers expensing their tickets are materially less price-sensitive than leisure travelers paying personally
- **Fairness Effect** — the most dangerous effect; passengers who feel a price is unfair will not just walk away, they will vocalize it, creating reputational damage that outlasts the transaction

---

## The Value Cascade: Price Structure

Price structure is where airlines have been most innovative — and where the biggest strategic debate lives.

**The unbundling revolution:** By separating bags, seats, and flexibility into optional add-ons, airlines created a price structure that allows price-sensitive customers to buy less while capturing more from customers who want more. This was a genuine pricing innovation.

**The problem it created:** Unbundling without intelligent re-bundling fragments the customer experience and invites comparison shopping on price alone. When every purchase is a separate decision, customers become transactional — exactly the behavior airlines need to prevent.

**Yield management as a structural tool:** The core price structure innovation — allocating seat inventory across fare classes and adjusting in real time — remains the most profitable mechanism in airline pricing. The frontier is extending this logic beyond seats to every ancillary product.

<div class="highlight">
The next structural evolution is <strong>personalized bundling</strong>: using customer data to reassemble the right combination of attributes for each segment at a price that reflects their specific value.
</div>

---

## The Challenge: Where Value Is Not Being Captured

Despite sophisticated systems, airlines leave significant value on the table due to segment mismatch.

| Customer Type | What They Value Most | Where Pricing Falls Short |
|---|---|---|
| **Price-Sensitive Leisure** | Lowest possible fare | Forced to pay for things they don't want; switches to ULCC |
| **Premium Leisure** | Comfort and experience | Priced and marketed like a corporate traveler they are not |
| **SME Business** | Flexibility and reliability | Pays retail without the recognition of corporate accounts |
| **Corporate** | Status, relationships, schedule | Negotiated contracts often undervalue loyalty and reliability |

<div class="warn">
Post-COVID, the boundary between these segments has dissolved. "Bleisure" travelers move between segments trip by trip — yet pricing systems still treat them as fixed types. This is the core structural mismatch.
</div>

---

## Conjoint Analysis: The Right Tool for This Problem

**Why conjoint analysis?**

The challenge in airline pricing is not knowing what customers prefer in the abstract — it is measuring how much they value each attribute when forced to make real trade-offs. Stated preference surveys are unreliable because people say they care about everything.

**Choice-Based Conjoint (CBC)** solves this by showing respondents realistic flight scenarios and asking them to choose. Statistical decomposition then reveals:
- The implicit value each segment places on each attribute
- The true willingness-to-pay for each incremental benefit
- Which attributes should anchor bundles for which segments
- Where the price fence between segments naturally falls

**What we learn that yield management alone cannot tell us:**
Yield management optimizes *when* to charge what price. Conjoint reveals *what* product to sell at each price point. The two tools answer different questions and are most powerful in combination.

---

## Conjoint Findings: What Passengers Actually Trade Off

The hierarchy of passenger preferences — with critical segment divergence:

**Attributes by overall importance:**
1. **Price** — dominant on average, but this average hides more than it reveals
2. **Routing** (nonstop vs. connection) — passengers pay to avoid connections, but the amount varies sharply
3. **Cancellation flexibility** — low value for leisure, critical for business
4. **Seat comfort** — growing in importance as premium leisure expands
5. **Baggage policy** — a threshold item; removal triggers strong dissatisfaction
6. **Wi-Fi and amenities** — valued but secondary in the decision hierarchy

**The critical insight:** Business travelers weight flexibility and schedule as heavily as leisure travelers weight price. They are not just less price-sensitive — they are buying a categorically different product. Airlines that price business and leisure fares as a continuum are leaving both segments underserved.

<div class="highlight">
Conjoint doesn't just tell you what to charge. It tells you <strong>what product to build for each segment</strong> before you set the price.
</div>

---

## Recommendations

Three strategic priorities emerge from applying the Value Cascade and conjoint insights to the airline pricing challenge.

**The through-line across all three:** airlines need to shift from optimizing price to optimizing the relationship between product, segment, and price simultaneously.

| Recommendation | Game Lever | Value Cascade Stage |
|---|---|---|
| **1. Segment-Targeted Bundling** | Choice Game | Price Structure |
| **2. Dynamic Ancillary Pricing** | Dynamic Game | Price Structure + Policy |
| **3. Premium Leisure Monetization** | Choice Game | Value Creation + Communication |

Each recommendation directly addresses a documented failure mode in the current pricing cascade — not a hypothetical opportunity.

---

## Rec. 1: Segment-Targeted Bundling

**The problem it solves:** Unbundling created price transparency but destroyed product coherence. Customers optimize each purchase decision separately, producing both lower spend and lower satisfaction.

**The recommendation:** Use conjoint-derived WTP profiles to construct named, segment-specific bundles that reassemble the right combination of attributes for each traveler type.

- A **business traveler bundle** leads with the attributes conjoint shows they value most — flexibility, reliability, and status recognition — rather than a generic seat and bag combination
- A **premium leisure bundle** leads with comfort and experience — legroom, lounge access, and priority — positioned as an aspirational upgrade, not a corporate default
- A **value bundle** for price-sensitive travelers packages the essentials at a visible discount versus à la carte, reducing sticker shock while increasing total wallet share

**Why this works:** It shifts the customer from comparing prices to comparing products — engaging the Difficult-Comparison Effect and reducing sensitivity to the base fare.

---

## Rec. 2: Dynamic Ancillary Pricing

**The problem it solves:** Ancillary fees are currently flat — the same bag fee regardless of when you book, how full the flight is, or how price-sensitive you are. This is the Cost Game applied to a Dynamic Game environment. It's a structural mismatch.

**The recommendation:** Extend yield management logic from seats to every ancillary product — bags, seat upgrades, Wi-Fi, and boarding priority should all respond to the same demand signals that govern seat pricing.

- Passengers who book early receive lower ancillary prices — rewarding planners and reinforcing the value of direct booking
- Prices rise as departure approaches and inventory fills — capturing the urgency premium from late-bookers
- Frequent flyers with proven spend patterns receive personalized offers before the general public sees any pricing at all

**The fairness risk:** This recommendation must be framed carefully. "Prices vary based on availability" is acceptable. "We charge more because our algorithm thinks you'll pay it" is not. Transparency in the pricing rationale is essential to avoid the Fairness Effect.

---

## Rec. 3: Monetize the Premium Leisure Segment

**The problem it solves:** Post-COVID, leisure travelers began choosing premium cabins at rates airlines were not prepared to serve. They were priced like corporate travelers and marketed like upgrades — when in fact they represent a new primary segment with its own distinct WTP profile.

**The recommendation:** Design, price, and market a premium product explicitly for this segment — not as a derivative of corporate pricing or as a lucky upgrade.

- Conjoint shows premium leisure travelers will pay meaningfully above economy for comfort and experience, but are sensitive to price in ways that corporate travelers are not — the price ladder must be calibrated to this middle band
- Upsell campaigns timed to the moments when these travelers make upgrade decisions — weeks before departure, not at booking — convert at significantly higher rates
- The product must be presented as a complete experience, not a list of features, because premium leisure purchase decisions are driven by aspiration more than calculation

**The strategic anchor:** This segment is structurally larger than it was before COVID. Its growth is not cyclical — it reflects a permanent shift in how people value travel.

---

## Anticipating Response

**Competitive dynamics:**

The recommendations create first-mover advantage, but competitors will follow once RASM improvement is visible in earnings. The durable moat is not the pricing mechanism — it is the data and customer relationships built through personalization over time.

**The ULCC lesson:**

Spirit's bankruptcy is not just a story about one company failing. It is a market signal that pure price competition in the US has a structural ceiling. Passengers chose experience and reliability when the price gap narrowed. Legacy carriers that invest now in value-based pricing will be better positioned when the next ULCC cycle emerges.

**Fairness is the existential risk:**

Every pricing innovation in this industry has a fairness dimension. Dynamic ancillary pricing, personalized bundling, and premium segmentation must all be designed with the Fairness Effect explicitly in mind. Customers accept variable prices when the logic is clear. They do not accept prices that feel targeted, arbitrary, or predatory — and in the age of social media, the reputational cost of perceived unfairness is immediate and severe.

---

<!-- _class: lead -->
<!-- _paginate: false -->

# The Core Argument

Airlines already have the most sophisticated pricing infrastructure in any consumer industry.

The opportunity is not better algorithms.

It is **better strategy** — aligning the Dynamic Game's technical precision with the Choice Game's ability to shape how customers perceive and value what they are buying.

**Conjoint analysis is the bridge** between the two.