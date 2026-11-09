# Standing Research Brief: "Learn With Me" Gap Tracker
Modeled on Social Capital Hedosophia's "Learn With Me" series (research.socialcapital.com).
Owner: Darel · Executor: Forge · Captions consumer: Quill · Status: DRAFT (internal, not for publication)

---
## 1. Template (one per run)

```
TOPIC:            <AI Stack | Private Credit | AI ROI | Electricity and Chips>
RUN DATE:         YYYY-MM-DD
SOCIAL CAPITAL PIECE: <title, URL, publish date>
KEYWORDS USED:    <from §3, plus any new ones added this run>
SOURCES SWEPT:    <checklist below>
```

### Source list (check each, every run)
| Source | What to look for |
|---|---|
| UBS | Capex, credit, AI adoption research notes |
| PitchBook | Private credit / VC deal volume, fund flows |
| S&P Global (Ratings, Market Intelligence) | Ratings actions, default data, data-center/power datasets |
| BIS | Financial-stability notes on private credit, leverage |
| Bloomberg | Bond pricing, deal news, market moves since SC publish date |
| McKinsey | Compute demand, AI adoption/EBIT surveys |
| NBER | Working papers on productivity, AI and organizations |
| Goldman Sachs | Power demand, capex forecasts |
| Wood Mackenzie | Grid interconnection, utility commitments |
| LSEG | Deal/financing maps, debt issuance data |
| Company filings (10-K/10-Q/20-F, earnings calls) | Margins, capex, guidance, debt terms |
| Others as found (Economist, Wharton, govt letters) | Log each; add to list if useful twice |

### Comparison rubric
| # | Social Capital said (quote + URL + date) | Public sources add (claim + URL + date) | Gap flag (§1 rules) | Severity (H/M/L) | Verified? (Y/N) |
|---|---|---|---|---|---|

Severity: **H** = changes the thesis; **M** = changes a number or framing; **L** = useful context.

### Gap-flagging rules
1. **Stale snapshot / market moved** — a figure or conclusion has been overtaken by events after the SC publish date (prices, deals, delays). Cite the later dated source.
2. **Sourcing discrepancy** — two credible sources give different numbers for the same metric. Record both, with sources; do not pick one without reason.
3. **Missing mechanism** — SC states an outcome but not the economics/causal chain (e.g., where margin accrues, why gains occur).
4. **Missing counter-evidence** — credible data that cuts against the SC conclusion is absent.
5. **Single-constraint framing** — SC names one bottleneck where evidence shows sequential/stacked constraints.
Every flag must cite at least one source with URL and date. No source → not a flag; log as "lead" instead.

---
## 2. Weekly cadence
**Rotation:** Week 1 AI Stack → Week 2 Private Credit → Week 3 AI ROI → Week 4 Electricity and Chips → repeat.

**Each run:**
1. Re-read the topic's SC piece(s); check for new SC posts.
2. Keyword sweep (§3) across the source list, prioritizing items dated since the last run.
3. Verify all seed/open gaps for this topic (§4); mark verified, corrected, or dropped.
4. Fill the comparison rubric.
5. Write a **2-3 page memo**: summary (5 bullets) → what moved since last run → gaps by flag type → open questions. **Every claim cites source, URL, and date.**
6. Write **chart-snippet captions for Quill**, each marked **DRAFT**: `DRAFT — <chart title> | <one-line caption> | Data: <source, URL, date>`.
7. Update the **living tracker** below.
8. File memo + tracker update (Notion Heighliner research section or GitHub, per Forge preference). Internal filing only.

### Living tracker (update each run; append history, do not overwrite)
| Topic | Metric | Value | Source (URL) | Source date | Last checked | Change vs prior | Status |
|---|---|---|---|---|---|---|---|
| AI Stack | Nvidia / TSMC / ASML gross margin | see §4 | TBD | TBD | — | — | unverified |
| AI Stack | Inference share of compute by 2030 | see §4 | TBD | TBD | — | — | unverified |
| AI Stack | Announced DC GW vs energized | see §4 | TBD | TBD | — | — | unverified |
| Private Credit | Chip-backed debt market size | see §4 | TBD | TBD | — | — | unverified |
| Private Credit | Hyperion / Excalibur bond prices | see §4 | TBD | TBD | — | — | unverified |
| Private Credit | CoreWeave borrowing cost | see §4 | TBD | TBD | — | — | unverified |
| Private Credit | AI borrowing YTD / off-balance-sheet | see §4 | TBD | TBD | — | — | unverified |
| AI ROI | % firms with positive EBIT from AI | see §4 | TBD | TBD | — | — | unverified |
| Elec & Chips | China capacity added (GW) | see §4 | TBD | TBD | — | — | unverified |
| Elec & Chips | Grid requests vs utility commitments | see §4 | TBD | TBD | — | — | unverified |
| Elec & Chips | Power capex forecast | see §4 | TBD | TBD | — | — | unverified |
| AI Stack | Nvidia GAAP gross margin | 75.0% (qtr ended 2026-07-26); Q3 FY27 guide 74.0% ±50 bp | https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-second-quarter-fiscal-2027 | 2026-08-26 | 2026-10-26 | first verified value (seed 75%) | verified |
| AI Stack | TSMC gross margin | 66.4% (3Q26); 67.7% (2Q26); 4Q26 guide 65–67% | https://pr.tsmc.com/english/news/3346 | 2026-10-15 | 2026-10-26 | −1.3 pp QoQ; seed 66% holds | verified |
| AI Stack | ASML gross margin | 57.5% (Q3 2026); 54.0% (Q2 2026); FY26 guide ~56% | https://investor.asml.com/news-releases/news-release-details/asml-reports-eu11.7-billion-total-net-sales-and-eu5.0-billion-net-income-q3-2026 | 2026-10-14 | 2026-10-26 | seed 53% corrected to 57.5% | corrected |
| AI Stack | CoreWeave operating margin (rental-tier proxy) | GAAP −2%, adjusted 5%; net interest $640M on $2,575M revenue (Q2 2026) | https://investors.coreweave.com/news/news-details/2026/CoreWeave-Reports-Strong-Second-Quarter-2026-Results/default.aspx | 2026-08-11 | 2026-10-26 | new metric | verified |
| AI Stack | Inference share of AI demand by 2030 | ~60% inference / ~40% training | https://www.mckinsey.com/industries/semiconductors/our-insights/scaling-ai-inference | 2026-10-05 | 2026-10-26 | first verified value | verified |
| AI Stack | Announced DC GW vs energized | "272 GW" = Enverus US Lower-48 *potential* capacity (136k acres × 2.0 MW/acre), not announced or global; global announced-vs-energized figure still UNVERIFIED | https://www.enverus.com/newsroom/data-center-sites-unseen-2026-parcel-update/ | 2026-04-22 | 2026-10-26 | seed corrected | corrected / partly unverified |
| AI Stack | Largest operating AI campus (current IT power) | ~1,037 MW, Anthropic-Amazon New Carlisle (Epoch estimate, ~±1.4x) | https://epoch.ai/graphs/largest-ai-data-centers-by-power-capacity | 2026-10-26 | 2026-10-26 | seed "under 1 GW" overtaken | corrected |
| AI Stack | H100 SXM rental index | $3.03/GPU-hr settle; Oct MTD +11.8% | https://data.ornn.com/markets/h100-sxm | 2026-10-25 | 2026-10-26 | new metric | verified (single source) |
| Private Credit | Chip-backed debt market size | "on track to become a trillion-dollar market" (no horizon stated) | https://finance.yahoo.com/technology/ai/articles/blackstone-bet-chips-drove-debt-111500562.html (Bloomberg) | 2026-10-23 | 2026-10-26 | seed verified | verified |
| Private Credit | Hyperion / Excalibur bond prices | Hyperion "a little under 91 cents"; Excalibur "below 87 cents" | https://finance.yahoo.com/markets/stocks/articles/investors-dump-data-centre-bonds-132608292.html (FT) | 2026-10-15 | 2026-10-26 | Excalibur seed (<88) corrected to <87 | verified / corrected |
| Private Credit | CoreWeave bond yield (not borrowing cost) | 9.75% 2031 bond YTM 15.97%; 5-yr CDS ~1,081 bp | https://www.cnbc.com/2026/10/20/coreweave-debt-janus-henderson-lloyd.html | 2026-10-20 | 2026-10-26 | seed reframed (yield, not borrowing); ">16%" UNVERIFIED | corrected |
| Private Credit | AI borrowing YTD / balance-sheet debt | ~$850bn borrowed 2026 YTD (~4x 2023); >$3trn debt ON balance sheets; off-BS: $1.2trn uncommenced leases + $1.5trn purchase commitments (CreditSights) | https://www.hindustantimes.com/world-news/the-ai-industry-s-gigantic-debts-are-making-investors-nervous-101792402325349.html (The Economist) | 2026-10-19 | 2026-10-26 | "$3T off-BS" seed corrected to on-BS | verified / corrected |
| Private Credit | OpenAI IPO timing | IPO delayed "until next year" | https://finance.yahoo.com/markets/stocks/articles/investors-dump-data-centre-bonds-132608292.html (FT) | 2026-10-15 | 2026-10-26 | seed verified | verified |
| Private Credit | Circular AI financing share | 46.4% of AI-to-AI deal value (2021–25) also supplier-customer; LSEG map UNVERIFIED (404) | https://www.bis.org/publications/bulletin-137-circular-relationships-among-ai-firms | 2026-10-01 | 2026-10-26 | new metric | verified (BIS) / LSEG unverified |
| AI ROI | % respondents with positive EBIT from AI | 37%; high performers ~6% | https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai | 2026-08-25 | 2026-10-26 | seed verified | verified |
| AI ROI | Strong ROI: growth vs efficiency metrics | 35% vs 13% ("nearly 3x") | https://www.businesswire.com/news/home/20261013596222/en/ | 2026-10-13 | 2026-10-26 | seed verified | verified |
| Elec & Chips | China capacity added (GW) | 429 GW = 2024 (OpenAI letter); 2025: 315.07 GW solar + 119.33 GW wind verified; ~543 GW total UNVERIFIED (NEA primary not read) | https://www.utilitydive.com/news/openai-white-house-china-energy-dominance/803967/ ; https://www.pv-magazine.com/2026/01/28/china-adds-315-gw-of-solar-in-2025/ | 2025-10-28 / 2026-01-28 | 2026-10-26 | discrepancy = different years | partly verified |
| Elec & Chips | Grid requests vs utility commitments | 1,066 GW requested; ~28% likely committed (~768 GW "phantom") | https://capacityglobal.com/news/wood-mackenzie-us-grid-operators-set-to-serve-28pc-of-data/ (WoodMac via Bloomberg) | 2026-08-25 | 2026-10-26 | seed verified (secondary) | verified (secondary) |
| Elec & Chips | Power / AI capex forecast | ~$7.6tn AI capex 2026–2031 (compute+DC+power); utility capex ~$1.3tn 2026–2030 | https://www.goldmansachs.com/insights/articles/tracking-trillions-the-assumptions-shaping-scale-of-the-ai-build-out ; https://www.goldmansachs.com/what-we-do/investment-banking/insights/articles/navigating-a-system-of-ai-bottlenecks | 2026-05-01 / 2026-10-19 | 2026-10-26 | seed verified | verified |
| Elec & Chips | TSMC supply vs demand | "demand… still far above our capability today to supply"; back-end "a little bit shortage"; seed date "Oct 2" corrected (blog; primary = 2026-01-15 and 2026-10-15 calls) | https://www.fool.com/earnings/call-transcripts/2026/10/15/tsmc-tsm-q3-2026-earnings-call-transcript/ | 2026-10-15 | 2026-10-26 | seed date corrected | corrected |

### History: 2026-11-09 run (AI ROI)

| Topic | Metric | Value | Source (URL) | Source date | Last checked | Change vs prior | Status |
|---|---|---|---|---|---|---|---|
| AI ROI | % respondents with some EBIT impact from AI | 37% "at least some EBIT impact"; high performers (≥5% EBIT + "significant") ~6%; both flat vs 2025 | https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai | 2026-08-25 | 2026-11-09 | no change; wording corrected from "positive EBIT" | verified |
| AI ROI | Strong ROI: growth vs efficiency metrics | 35% vs 13% = 2.7x ("nearly 3x"); by growth-metric count 13/32/37/43% (n=65 for three) | https://knowledge.wharton.upenn.edu/wp-content/uploads/2026/10/Wharton-GBK-AI-Adoption-Report-2026.pdf | 2026-10-13 | 2026-11-09 | primary PDF read; "3x" corrected to 2.7x | verified (self-reported, association only) |
| AI ROI | Positive vs strongly positive ROI (enterprise leaders) | 80% positive; 28% strongly positive (n=1,416) | https://www.gbkcollective.com/thoughtleadership/wharton-gbk-ai-study-2026-press-release | 2026-10-13 | 2026-11-09 | new metric | verified |
| AI ROI | Execs reporting no productivity impact (3 yrs) | 89% no labor-productivity impact; >90% no employment impact; expect +1.4% productivity next 3 yrs | https://www.nber.org/digest/202605/global-evidence-business-use-ai | 2026-05-01 | 2026-11-09 | new metric; discrepancy with surveys above | verified |
| AI ROI | NBER organization capital (w35684) | AI investment associated with productivity growth via organization capital; 1 SD → +6.2 pp sales/worker, +7.5 pp TFP over 6 yrs (2018–24) per ITIF | https://www.nber.org/papers/w35684 ; https://itif.org/publications/2026/09/08/investing-more-ai-experienced-roughly-one-percentage-point-productivity-growth-per-year/ | 2026-08 / 2026-09-08 | 2026-11-09 | seed verified; magnitudes secondary | verified (abstract) / magnitudes via ITIF |
| AI ROI | 515-startup field experiment revenue effect | 1.9x on log(x+1), p<0.1; raw diff −$1.75M insignificant; gains largest at P90+; capital demand −39.5%, labor unchanged | https://mackinstitute.wharton.upenn.edu/wp-content/uploads/2026/04/ssrn-6513481.pdf | 2026-03-30 | 2026-11-09 | primary paper identified; "near-zero revenue" not stated in paper | verified (primary) / SC "barely moved" UNVERIFIED |
| AI ROI | US nonfarm productivity | Q3 2026 +3.6% annualized; +2.1% y/y; Q2 revised to 2.1%; AI attribution contested | https://www.axios.com/2026/11/05/labor-output-productivity-ai ; https://www.investing.com/news/economic-indicators/us-worker-productivity-surges-in-third-quarter-5004543 | 2026-11-05 | 2026-11-09 | new metric; SC "not in productivity numbers" partly overtaken | verified (secondary; BLS primary not read) |
| AI ROI | Ramp paid AI adoption | 55.9% of Ramp businesses (Sep 2026), +0.6 pp m/m, +12.1 pp y/y; "top of the S-curve" | https://ramp.com/data/ai-index | data through 2026-09 | 2026-11-09 | new metric | verified (Ramp sample only) |
| AI ROI | Ramp median AI spend per employee per month | $15.70 (Sep), $14.74 (Aug), median firm paying for AI; top 1% $9,567.53; SC cites $12.50 | https://ramp.com/data/ai-index | data through 2026-09 | 2026-11-09 | new metric; discrepancy with SC $12.50 | partly verified ($12.50 UNVERIFIED) |

---
## 3. Standing keyword list
**AI Stack:** AI value chain margins; Nvidia gross margin; TSMC gross margin; ASML gross margin; GPU rental pricing; neocloud margins; inference vs training compute demand; data center announced vs energized; gigawatt campus; CoWoS capacity; CUDA moat; photoresist / Japanese film supply; model cost per token.
**Private Credit:** chip-backed debt; GPU-backed loans; data-center ABS/CMBS; Hyperion bonds; Blackstone Excalibur; CoreWeave debt yield; Meta Big Sky / off-balance-sheet SPV; junk-bond share AI; private credit spreads; circular financing Nvidia; vendor financing AI; OpenAI IPO; AI borrowing total.
**AI ROI:** AI EBIT impact survey; AI high performers; AI ROI growth vs efficiency metrics; organization capital AI; AI productivity NBER; AI reorganization startups; enterprise AI revenue; GenAI pilot to production.
**Electricity and Chips:** China capacity additions GW; US power shortage AI; OpenAI White House letter electricity; power forever bottleneck; utility capex forecast; interconnection queue; large-load requests utilities; wafer supply bottleneck; CoWoS shortage; transformer / turbine lead times.

**How to extend:** Each run, add any term that (a) appeared in ≥2 credible sources or (b) produced a verified gap. Retire terms with zero useful hits for 3 consecutive runs of that topic. Log adds/retirements with date at the bottom of this section.

Keyword change log:
- (none yet)
- 2026-10-26 (run 1, AI Stack): ADD AI Stack "neocloud consolidation / impairment" (Gartner 2026-10-14; FT 2026-10-15); ADD AI Stack "cost to serve / cost per outcome" (McKinsey 2026-10-05, 2026-08-25; verified gaps G8/G9); ADD Elec & Chips "phantom load" (Capacity/WoodMac 2026-08-25; Bloomberg 2026-08-12). No retirements.
- 2026-11-02 (run 2, Private Credit): ADD Private Credit "data-center lease off-ramps / force majeure" (Bloomberg 2026-10-28; NYT via FinancialMarkets 2026-10-19); ADD Private Credit "non-traded BDC redemptions" (PitchBook 2026-10-12; Stanger/AltsWire 2026-10-02); ADD Private Credit "PIK interest / maturity wall" (Moody's via Reuters 2026-10-27; verified gap P10). No retirements.
- 2026-11-09 (run 3, AI ROI): ADD AI ROI "AI mapping problem / use-case discovery" (Mack Institute/INSEAD paper 2026-03-30; HBS AI Institute; verified gap R8); ADD AI ROI "BLS productivity AI" (Axios and Reuters 2026-11-05; verified gap R1); ADD AI ROI "strongly positive ROI vs positive ROI" (GBK 2026-10-13; McKinsey 2026-08-25; NBER 2026-05-01; verified gap R3). No retirements.

---
## 4. Seed gap list (from prototype)
All items below: **user-supplied, verify citation on first run.** No source URLs are asserted here; add them only after verification.

**AI Stack**
- Margin math: Nvidia 75% gross, TSMC 66%, ASML 53%, assembly/rental near zero. — *user-supplied, verify citation on first run*
- McKinsey Oct: inference 60% of compute demand by 2030 vs 40% training. — *user-supplied, verify citation on first run*
- 272 GW announced globally; largest operating campuses under 1 GW. — *user-supplied, verify citation on first run*

**Private Credit**
- Bloomberg Oct 23: chip-backed debt on track for $1T. — *user-supplied, verify citation on first run*
- Hyperion bonds 91 cents; Blackstone Excalibur below 88. — *user-supplied, verify citation on first run*
- CoreWeave borrowing briefly 16%. — *user-supplied, verify citation on first run*
- OpenAI delayed IPO. — *user-supplied, verify citation on first run*
- Economist: $850B borrowed this year (4x 2023), ~$3T off-balance-sheet. — *user-supplied, verify citation on first run*
- LSEG circular-finance map missed. — *user-supplied, verify citation on first run*

**AI ROI**
- McKinsey: 37% positive EBIT, 6% high performers. — *user-supplied, verify citation on first run*
- Wharton: growth-metric trackers 3x more likely to see strong ROI. — *user-supplied, verify citation on first run*
- NBER: gains from organization capital. — *user-supplied, verify citation on first run*
- Near-zero revenue in both groups. — *user-supplied, verify citation on first run*

**Electricity and Chips**
- China 543 GW (Social Capital) vs 429 GW (OpenAI White House letter). — *user-supplied, verify citation on first run*
- Goldman: "forever bottleneck", $7.6T capex through 2031. — *user-supplied, verify citation on first run*
- WoodMac: 1000+ GW requested, utilities commit 28%. — *user-supplied, verify citation on first run*
- TSMC C.C. Wei Oct 2: wafer supply/CoWoS bottleneck. — *user-supplied, verify citation on first run*

**Overall:** SC pieces are snapshots; weekly cadence + living tracker addresses "market moved" gaps. — *user-supplied*

---
## 5. Rules
1. **No invented numbers.** Every number traces to a cited source (URL + date). Unverified = labeled unverified.
2. **Every claim cites a source.**
3. **Drafting is free:** research, memos, tracker updates, and internal filing need no approval.
4. **Publishable or spend-triggering actions stop as a DRAFT for Darel:** any post, external share, Quill publication, paid data/subscription, or purchase. Present the draft; wait for explicit approval.
