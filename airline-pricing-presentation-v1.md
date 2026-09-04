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
  --color-accent2: #0ea5e9;
  --color-border: #d1d5db;
  --font-default: 'Inter', 'Segoe UI', sans-serif;
}

section {
  background-color: var(--color-background);
  color: var(--color-foreground);
  font-family: var(--font-default);
  font-weight: 400;
  box-sizing: border-box;
  border-top: 8px solid var(--color-heading);
  position: relative;
  line-height: 1.6;
  font-size: 20px;
  padding: 52px 60px 70px 60px;
}

h1, h2, h3, h4, h5, h6 {
  font-weight: 700;
  color: var(--color-heading);
  margin: 0;
  padding: 0;
}

h1 {
  font-size: 52px;
  line-height: 1.2;
  letter-spacing: -0.02em;
}

h2 {
  position: absolute;
  top: 36px;
  left: 60px;
  right: 60px;
  font-size: 34px;
  padding-bottom: 14px;
  border-bottom: 3px solid var(--color-accent);
}

h2 + * {
  margin-top: 100px;
}

h3 {
  color: var(--color-accent);
  font-size: 22px;
  margin-top: 20px;
  margin-bottom: 8px;
  font-weight: 600;
}

ul, ol {
  padding-left: 28px;
  margin: 0;
}

li {
  margin-bottom: 8px;
  line-height: 1.6;
}

li li {
  margin-top: 4px;
  margin-bottom: 4px;
  font-size: 0.9em;
  color: #374151;
}

footer {
  font-size: 14px;
  color: #9ca3af;
  position: absolute;
  left: 60px;
  right: 60px;
  bottom: 24px;
}

section.lead {
  border-top: none;
  display: flex;
  flex-direction: column;
  justify-content: center;
  background: linear-gradient(135deg, #1e3a8a 0%, #1d4ed8 50%, #0ea5e9 100%);
  padding: 60px 80px;
}

section.lead footer { display: none; }
section.lead h1 {
  color: #ffffff;
  font-size: 56px;
  margin-bottom: 20px;
  line-height: 1.15;
}
section.lead p {
  font-size: 22px;
  color: rgba(255,255,255,0.85);
  font-weight: 400;
  line-height: 1.6;
}
section.lead .tag {
  display: inline-block;
  background: rgba(255,255,255,0.15);
  border: 1px solid rgba(255,255,255,0.3);
  color: #ffffff;
  font-size: 14px;
  font-weight: 600;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  padding: 6px 16px;
  border-radius: 20px;
  margin-bottom: 24px;
}

table {
  border-collapse: collapse;
  width: 100%;
  margin: 8px 0;
  font-size: 16px;
}

th, td {
  border: 1px solid var(--color-border);
  padding: 9px 12px;
  text-align: left;
}

th {
  background-color: var(--color-heading);
  color: #ffffff;
  font-weight: 600;
  font-size: 15px;
}

tr:nth-child(even) {
  background-color: #f9fafb;
}

strong { color: var(--color-heading); font-weight: 700; }

.highlight {
  background: linear-gradient(135deg, #eff6ff, #dbeafe);
  border-left: 4px solid var(--color-accent);
  padding: 12px 20px;
  border-radius: 0 8px 8px 0;
  margin: 12px 0;
  font-size: 18px;
}

.two-col {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 32px;
  margin-top: 8px;
}

.pillar {
  background: #f8fafc;
  border: 1px solid #e2e8f0;
  border-top: 4px solid var(--color-accent);
  border-radius: 8px;
  padding: 20px;
}

.pillar h3 {
  margin-top: 0;
  font-size: 18px;
}
</style>

<!-- _class: lead -->
<!-- _paginate: false -->

<div class="tag">Strategic Pricing · MBA Presentation</div>

# Airline Pricing Strategy

Yield Management, Ancillary Revenue &
Conjoint-Driven Optimization

April 2026

---

## Agenda

1. **Industry Overview** — The US airline pricing landscape
2. **Pricing Environment** — Key trends & revenue pillars
3. **Core Challenge** — Segment mismatch & revenue leakage
4. **Conjoint Analysis** — Methodology & willingness-to-pay findings
5. **Strategic Recommendations** — Three actionable initiatives
6. **Impact Analysis** — Quantified revenue opportunity & risks

---

## US Airline Industry Snapshot

- Total US airline revenue (2023): **~$225B**
- Ticket revenue ~85% | Ancillary & other ~15–18%
- **Big 3** (Delta, United, American) control ~65–70% of total revenue
- Market HHI: ~1,200–1,500 — moderately concentrated

**RASM (Revenue per Available Seat Mile) — 2023–2024:**

| Carrier | RASM | vs. Delta |
|---|---|---|
| **Delta** | $0.200–0.207 | Benchmark |
| United | $0.188–0.193 | –6% |
| American | $0.175–0.180 | –13% |
| Spirit (ULCC) | $0.100–0.105 | –50% |

> Delta commands a consistent **8–12% RASM premium** — the industry's sharpest differentiator

---

## Pricing: 50 Years of Evolution

<style scoped>
ol li { margin-bottom: 10px; font-size: 19px; }
</style>

1. **1978** — Deregulation → open fare competition begins
2. **1980s–90s** → Yield management & fare buckets *(26+ fare classes per flight)*
3. **2000s–2010s** → Ancillary unbundling — baggage fees, seat selection, buy-on-board
4. **2017–2019** → Basic Economy launches across AA, Delta & United
5. **2020–2021** → Change fees eliminated; loyalty card revenue surges past fee revenue
6. **2022–2025** → **NDC, continuous pricing, AI/ML offer personalization**

<div class="highlight">
Global ancillary revenue: <strong>$109.5B (2019) → ~$120B (2023)</strong> — a new all-time record despite fare normalization
</div>

---

## Three Revenue Pillars

<div class="two-col">
<div class="pillar">
<h3>Ticket Revenue</h3>

- US avg domestic RT: **~$375** (2024)
- Real fares ≈ flat vs. 2019 in inflation-adjusted terms
- Price elasticity:
  - Leisure: **–1.2 to –1.8**
  - Business: **–0.4 to –0.6**
</div>
<div class="pillar">
<h3>Ancillary Fees</h3>

- US baggage fees (2023): **~$7.5B**
- ULCCs earn **$75–80** ancillary/passenger
- Dynamic pricing now applied to bags, upgrades & Wi-Fi
</div>
</div>

<div class="pillar" style="margin-top:16px; border-top-color: #0ea5e9;">
<h3 style="color:#0369a1;">Loyalty / Co-Brand Cards — The Hidden Engine</h3>

| Partner | 2023 Revenue to Airline |
|---|---|
| Delta + American Express | **$6.8B** |
| American + Citi/Barclays | ~$5.0–5.5B |
| United + Chase | ~$4.5B |
</div>

---

## Core Challenge: Segment Mismatch

Airlines serve radically different customers with vastly different WTP — yet pricing relies on blunt fare buckets that **leave revenue on the table** from premium travelers and **alienate** price-sensitive leisure travelers.

**Four structural pressures:**

1. **ULCC compression** — Spirit & Frontier suppress base fares on leisure routes
2. **Bleisure blurring** — Business/leisure lines eroded post-COVID; traveler identity is fluid
3. **Undermonetized premium leisure** — 38% of premium cabin by 2023, yet priced like corporate
4. **Spirit's bankruptcy (Nov 2024)** — Proves pure price competition is a losing strategy in the US

<div class="highlight">
The opportunity: <strong>Precision pricing by segment</strong> — the same seat, different value proposition, different price
</div>

---

## Conjoint Analysis: Methodology

**What is Choice-Based Conjoint (CBC)?**
Respondents choose between hypothetical flight options. Statistical modeling decomposes implicit preferences into **part-worth utilities** — the gold standard for measuring WTP.

<style scoped>table { font-size: 15px; } th, td { padding: 8px 10px; }</style>

| Attribute | Levels Tested |
|---|---|
| **Price** | ±30–50% range from baseline |
| **Seat legroom** | 28" / 30" / 32" / 34" |
| **Checked baggage** | Free / $30 / $60 |
| **Cancellation policy** | Free changes / $200 fee / Non-refundable |
| **Wi-Fi** | Free / $8 / $20 / None |
| **On-time performance** | 65% / 75% / 85% |
| **Routing** | Nonstop / 1-stop connection |
| **Loyalty miles** | Miles earned / Not earned |

---

## Conjoint: WTP by Segment

<style scoped>table { font-size: 14px; } th, td { padding: 7px 10px; }</style>

| Attribute | Price-Sensitive Leisure | Premium Leisure | SME Business | Corporate |
|---|---|---|---|---|
| Nonstop vs. 1-stop | +$50–80 | +$100–120 | +$80–150 | +$150–200 |
| Free checked bag | +$25–35 | +$20–30 | +$40–60 | +$50–80 |
| **Free cancellation** | +$15–25 | +$40–60 | **+$100–150** | **+$150–250** |
| Premium seat (+4" legroom) | +$20–40 | +$80–150 | +$60–100 | +$100–200 |
| Wi-Fi (free vs. paid) | +$5–10 | +$10–15 | +$15–25 | +$20–30 |
| On-time +10 pp | +$10–15 | +$15–20 | +$30–40 | +$40–50 |

<div class="highlight">
Key insight: Business travelers are <strong>2–3× less price-elastic</strong> than leisure. Flexibility and on-time reliability drive their premium — not cabin class alone.
</div>

---

## Conjoint: Attribute Importance

<style scoped>
.bar-wrap { margin: 8px 0; }
.bar-label { font-size: 17px; font-weight: 500; margin-bottom: 2px; }
.bar { height: 22px; border-radius: 4px; background: linear-gradient(90deg, #1e3a8a, #2563eb); display: flex; align-items: center; padding-left: 8px; color: white; font-size: 13px; font-weight: 600; }
</style>

<div class="bar-wrap"><div class="bar-label">1. Price / fare</div><div class="bar" style="width:70%">35%</div></div>
<div class="bar-wrap"><div class="bar-label">2. Nonstop vs. connection</div><div class="bar" style="width:40%">20%</div></div>
<div class="bar-wrap"><div class="bar-label">3. Schedule convenience</div><div class="bar" style="width:30%">15%</div></div>
<div class="bar-wrap"><div class="bar-label">4. Cancellation flexibility</div><div class="bar" style="width:24%">12%</div></div>
<div class="bar-wrap"><div class="bar-label">5. Seat comfort / legroom</div><div class="bar" style="width:16%; background: linear-gradient(90deg,#0369a1,#0ea5e9)">8%</div></div>
<div class="bar-wrap"><div class="bar-label">6. Baggage inclusion</div><div class="bar" style="width:12%; background: linear-gradient(90deg,#0369a1,#0ea5e9)">6%</div></div>
<div class="bar-wrap"><div class="bar-label">7. Wi-Fi & IFE</div><div class="bar" style="width:8%; background: linear-gradient(90deg,#4b5563,#9ca3af)">4%</div></div>

**Segment divergence:** Business = Schedule + Flexibility (~50%) · Leisure = Price (~45–50%) · Premium leisure = Comfort + Flexibility

---

## Rec. 1: Personalized Bundling via NDC

**Recommendation:** Use conjoint-derived WTP profiles to construct segment-targeted bundles via NDC infrastructure

**Example bundles:**

| Bundle | Target | Contents | Price |
|---|---|---|---|
| **Flexibility Bundle** | SME Business | Free cancel + priority boarding + 1 bag | $89 add-on |
| **Comfort Bundle** | Premium Leisure | Extra legroom + Wi-Fi + lounge day pass | $120 add-on |
| **Value Bundle** | Price-Sensitive | 1 checked bag + basic seat select | $45 add-on |

**Evidence base:**
- Delta, Lufthansa & Air Canada already deploying continuous pricing + NDC
- Personalized offers improve revenue capture by **1–3%** with zero capacity change
- United's Basic Economy was conjoint-informed: carry-on was the **#1 valued economy attribute**

---

## Rec. 2: Dynamic Ancillary Pricing

**Recommendation:** Apply yield management logic to ancillaries — not just to seats

<div class="two-col">
<div>
<h3>Current State</h3>

- Flat bag fees ($35) regardless of booking window or load factor
- No dynamic pricing for seat upgrades
- Per-flight Wi-Fi only; no subscription options
- Legacy ~$45–55 ancillary per passenger
</div>
<div>
<h3>Recommended State</h3>

- Bags: **$20–25** (early booking) → **$45–55** (at gate)
- Seat upgrades priced dynamically by remaining inventory
- Wi-Fi monthly subscription passes for frequent flyers
- Target: **$70–75** ancillary per passenger
</div>
</div>

<div class="highlight">
Closing a $20–25/pax ancillary gap at a 50M-passenger carrier = <strong>$1.0–1.25B annual revenue opportunity</strong>
</div>

---

## Rec. 3: Premium Leisure Monetization

**Recommendation:** Explicitly price and market Premium Economy/Comfort+ to the post-COVID bleisure segment

**Market opportunity:**
- Premium leisure grew from ~20% → **38%** of premium cabin (2023)
- Premium Economy is the **fastest-growing cabin globally** (2022–2025)
- WTP: **$300–600** over economy on transcon · **$800–1,500** on international

**Tactical actions:**
- Targeted upsell campaigns at **T-21, T-7, T-48 hours** — highest conversion windows
- Conjoint-informed **3-tier price laddering** (not 2-tier): Economy → Comfort+ → Business
- Bundle premium seat + lounge day pass for leisure travelers *(United Polaris Day Pass model)*

<div class="highlight">
Delta's premium cabin revenue grew <strong>25–30% faster</strong> than main cabin in 2022–2023
</div>

---

## Impact Analysis

**Model:** Mid-size US carrier — 50M passengers/year · ~$15B revenue baseline

<style scoped>table { font-size: 16px; } th, td { padding: 10px 14px; }</style>

| Initiative | Revenue Driver | Conservative | Optimistic |
|---|---|---|---|
| NDC Personalized Bundling | 1–3% RASM improvement | **+$150M** | **+$450M** |
| Dynamic Ancillary Pricing | Close $20–25/pax gap | **+$500M** | **+$1.0B** |
| Premium Leisure Monetization | 5–10% premium yield lift | **+$200M** | **+$400M** |
| **Total 3-Year Opportunity** | | **+$850M** | **+$1.85B** |

**Key assumptions:**
- Baseline RASM $0.185 · 270B ASMs · 20% of passengers eligible for premium upsell
- 60% of ancillary opportunity realizable within 3 years
- No demand destruction assumed — recommendations stay within price elasticity bounds

---

## Risks & Mitigations

<style scoped>table { font-size: 16px; } th, td { padding: 9px 12px; }</style>

| Risk | Likelihood | Mitigation |
|---|---|---|
| Customer backlash to dynamic bag fees | Medium | Phase in gradually; grandfather loyalty members |
| GDS/OTA channel conflict with NDC | **High** | Incentivize direct booking; negotiate OTA NDC adoption |
| Regulatory scrutiny of personalized pricing | Medium | Ensure pricing is attribute-based, not identity-based |
| Competitor retaliation on ancillary pricing | Low–Medium | First-mover advantage; monitor RASM response closely |
| ULCC re-entry pricing wars | Low *(post-Spirit)* | Basic Economy firewall sufficient if brand premium maintained |

---

<!-- _class: lead -->
<!-- _paginate: false -->

# Key Takeaways

**1.** Ancillary revenue is the **margin engine** — ticket fares are customer acquisition costs

**2.** Conjoint reveals **extreme segment heterogeneity** — one-size pricing leaves billions on the table

**3.** The ULCC pure price model **failed** in the US — Spirit's bankruptcy is the proof point

**4.** NDC + dynamic ancillaries = the **next $1B+ revenue frontier** for mid-size carriers

**5.** Premium leisure is **structurally larger** post-COVID — monetize it intentionally

---

The airlines that win in 2026–2030 will treat pricing as a **personalization problem**, not a seat inventory problem.
