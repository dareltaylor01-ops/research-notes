# Learn With Me: Electricity and Chips, 2026-11-16 (Run 4)

Status: DRAFT. Internal research filing, not for publication. Nothing here has been posted or shared, and nothing has gone to Quill.

```
TOPIC:            Electricity and Chips
RUN DATE:         2026-11-16
SOCIAL CAPITAL PIECE: "Deep Dive: The Electric Grid - America's Biggest Bottleneck of the Decade", https://research.socialcapital.com/p/deep-dive-the-electric-grid, 2025-12-03 (web-experience update 2026-02-27)
                  Companion framing: @socialcapital post "The two constraints on AI are effectively electricity and chips…" (Oct 12, 2026), read via a Nitter mirror, https://nitter.rdrama.net/socialcapital/status/2109694345226203444. The seed's "543 GW" appears in that post.
KEYWORDS USED:    §3 Electricity and Chips list (all 10 terms), plus proposed adds "signed vs reported load", "large-load tariff / take-or-pay" and "data center moratorium" (Appendix E)
SOURCES SWEPT:    see Appendix D
WHY THIS TOPIC:   rotation AI Stack (2026-10-26) -> Private Credit (2026-11-02) -> AI ROI (2026-11-09) -> Electricity and Chips (this run). Baseline for "what moved" = tracker check of 2026-10-26.
```

Scope note: the SC deck is paywalled; only the public excerpt was read. Anything attributed to the deck that is not in the excerpt is marked **UNVERIFIED (attribution)**. Free sources only; no paid data. Several secondary sources are used because primaries are paywalled (Bloomberg) or not fetchable. Each is labeled.

---

## 1. Summary (5 bullets)

1. **The China "543 GW" seed is now verified to the primary, and it is a 2025 nameplate number, not output.** NEA's Jan 28, 2026 release gives 3.89 TW cumulative capacity, +16.1% y/y (NEA, https://www.nea.gov.cn/20260129/6874f211acd0417eab7ac10c3061a7c2/c.html, 2026-01-29). An NEA-guided market report states 2025 additions of 5.42亿 kW, i.e. 542 GW (NEA site, https://www.nea.gov.cn/20260618/41e848b9ec6543998757db3864e01ab2/c.html, 2026-06-18). Bloomberg reports 543 GW from NEA data (https://www.bloomberg.com/news/articles/2026-01-28/china-s-four-year-energy-spree-has-eclipsed-entire-us-power-grid, 2026-01-28). The 429 GW in the OpenAI letter is the 2024 figure (prior run, Utility Dive, 2025-10-28).
2. **"Requests vs commitments" now has two datasets that disagree on scope, not on direction.** Wood Mackenzie: 1,066 GW requested, about 28% likely to be committed (Capacity, https://capacityglobal.com/news/wood-mackenzie-us-grid-operators-set-to-serve-28pc-of-data/, 2026-08-25). Latitude Media (new, Nov 13): utilities report 537 GW in pipelines but have signed about 120 GW (22%), against 22 GW operating (via TechTimes, https://www.techtimes.com/articles/330794/20261116/latitude-finds-data-center-power-contracts-cover-22-reported-load-utilities-seek-power-plants.htm, 2026-11-16).
3. **Utility capex keeps rising, and politics is a new variable since SC's piece.** Oncor's $47.5B five-year plan is expected to rise 20% (Utility Dive, https://www.utilitydive.com/news/sempra-expects-20-increase-oncors-capex-plan-load-growth/874010/, 2026-11-06). Goldman expects new Democratic governors in states with over a third of planned US data-center capacity to impose moratoria, mostly affecting not-yet-permitted projects (Goldman note quoted by CNBC, https://www.cnbc.com/2026/11/13/data-center-slowdown-utility-stocks.html, 2026-11-13).
4. **SC's "single bottleneck" framing is incomplete: equipment lead times are stacked.** Wood Mackenzie power-transformer lead time was 128 weeks in Q2 2025 (WoodMac, https://www.woodmac.com/news/opinion/mind-the-gap-tackling-supply-chain-challenges-in-the-electric-td-sector/, 2025-10-15); substation and step-up units were reported above 160 weeks in 2026 (secondary: Data Center Knowledge, https://www.datacenterknowledge.com/build-design/ai-data-center-boom-rewires-us-power-supply-chain, 2026, exact date not shown). GE Vernova is taking 2031 turbine reservations (Utility Dive, https://www.utilitydive.com/news/ge-vernova-gas-turbine-backlog-climbs-to-116-gw/826039/, 2026-07-22).
5. **TSMC's constraint is real, but the CoWoS numbers are press reports, not company guidance.** TSMC's Q3 call (2026-10-15) said demand is "still far above our capability today to supply" (prior run, https://www.fool.com/earnings/call-transcripts/2026/10/15/tsmc-tsm-q3-2026-earnings-call-transcript/). CoWoS capacity above 130,000 wafers/month in 2026 and a 200,000 target for 2027 come from analyst and supply-chain sources (N Globe citing Commercial Times, https://nglobenews.com/en/article/taiwan-tsmc-cowos-packaging-price-hike-2026-10-27/, 2026-10-27). **UNVERIFIED against TSMC.**

---

## 2. What moved since the last tracker check (2026-10-26)

- **Utility earnings and capex (Nov 2026).** Oncor: record 33.3 GW peak in August, base plan $47.5B expected +20% (Utility Dive, 2026-11-06). Alliant reportedly lifted its 2027-30 capex plan 19% to $15.9B on 3.4 GW of contracted data-center demand (DataCenterFeed, https://datacenterfeed.com/article/alliant-energy-capex-15-9-billion-data-center-demand-wisconsin-large-load-tariff-november-2026, Nov 2026; exact date and primary filing **not checked**).
- **Signed vs reported load.** Latitude's platform data (published 2026-11-13): 537 GW reported, about 120 GW signed, 22 GW operating, about 37 GW of new generation being solicited. Jefferies, using a different method, sorted 187 GW of disclosed commitments to 69 GW under the strictest tier (both via TechTimes, 2026-11-16). Georgia Power: 80.1 GW reported vs 12.8 GW signed (same source).
- **Contract strength.** NIPSCO's Amazon contract gives Amazon a one-time option to cut 1,200 MW by 2029-03-31 (TechTimes citing Utility Dive, 2026-11-16).
- **Politics and cost allocation.** Goldman: moratoria likely, limited effect on 2027 construction (CNBC, 2026-11-13). Texas Governor Abbott has put a quiet "pause" on data-center permitting (CNBC, 2026-11-13; single journalist's account). PJM's market monitor attributes $29.4B of $63.6B capacity costs over four auctions to data-center load; that figure is the monitor's own estimate (TechTimes, 2026-11-16). FERC large-load filings from five grid operators were due today (2026-11-16) and SPP's on 2026-11-20 (same source). **Outcome not yet known.**
- **Transformers.** Wood Mackenzie (2026-08-31) estimates 2026 market shortages of 15% (power transformers) and 8% (substations) and says Executive Order 14420 on Chinese bulk-power equipment could worsen them (https://www.woodmac.com/press-releases/us-executive-order-banning-chinese-bulk-power-equipment-set-to-worsen-critical-transformer-shortage/).
- **Turbines.** Siemens Energy gas backlog 69 GW, lead times "three years or more" (Utility Dive, https://www.utilitydive.com/news/siemens-gas-turbine-backlog-nears-70-gw-as-company-expands-manufacturing/827390/, 2026, fiscal Q3 call; exact date not shown). Mitsubishi Power Asia Pacific CEO: delivery "around 2031", 2028-29 slots almost full (Bloomberg via EnergyConnects, https://www.energyconnects.com/news/renewables/2026/october/high-demand-for-gas-turbines-is-pushing-out-deliveries-to-2031-mitsubishi-power-says/, Oct 2026).
- **Chips.** Reported (not confirmed) CoWoS price rises of 10-20% and wafer price rises of 3-6% from Jan 2027 (N Globe citing Commercial Times, 2026-10-27; "TSMC has not officially announced an increase").

---

## 3. Gaps by flag type

**Flag 1, Stale snapshot / market moved**
- **E1 (M) China additions, year and basis.** The seed pair "543 vs 429" is a year mismatch (2025 vs 2024), already corrected last run. Now the 2025 figure is tied to NEA: 542 GW additions (NEA-guided report, 2026-06-18) and 543 GW (Bloomberg, 2026-01-28). The 1 GW difference is unexplained; both are cited. Wind plus solar additions are 434 GW in the NEA-guided report, which matches pv magazine's 315.07 GW solar + 119.33 GW wind (https://www.pv-magazine.com/2026/01/28/china-adds-315-gw-of-solar-in-2025/, 2026-01-28). Mercom reports 311 GW solar + 119 GW wind (https://www.mercomindia.com/strong-solar-buildout-pushes-chinas-power-capacity-to-3890-gw, date not shown), a small **sourcing discrepancy** on solar that is unresolved.
- **E2 (M) Utility capex and demand reality.** See §2: Oncor +20%, Alliant +19% (unverified primary), Goldman on moratoria. These post-date the SC deep dive (2025-12-03).

**Flag 2, Sourcing discrepancy**
- **E3 (H) Requested vs committed power.** WoodMac: 1,066 GW requested, ~12% firm + ~17% likely = 28% (≈298 GW); 768 GW "phantom" (Capacity, 2026-08-25; Bloomberg headline, https://www.bloomberg.com/news/articles/2026-08-12/most-electricity-sought-for-ai-data-centers-in-us-will-never-materialize, 2026-08-12, paywalled). Latitude: 537 GW reported, 120 GW signed (22%). These are different universes (WoodMac compiles requests, with no stated as-of date per The Capacity Factor, https://energy.ai.studio/news/wood-mackenzie-28-per-cent-of-1066-gw-data-centre-requests, 2026-08; Latitude covers 53 utility territories on one definition). Do not pick one. Note: 12% + 17% = 29%, reported as 28%, so rounding is in the source. The "phantom load" term is WoodMac's characterization per Capacity; "768 GW" is a subtraction from 1,066, as The Capacity Factor points out.
- **E4 (M) Transformer shortage size.** WoodMac estimated a 30% power-transformer supply deficit for 2025 (via Plant to Pipeline, https://planttopipeline.com/transformer-lead-time-shortage/, citing WoodMac 2025-08-14) but 15% for 2026 (WoodMac, 2026-08-31). A broker quoted in POWER (2026-01-02) said "There is not a shortage" (same Plant to Pipeline article; single quote). Record both.

**Flag 3, Missing mechanism**
- **E5 (M) Nameplate vs output.** SC and Bloomberg cite additions in GW. NEA's own release shows average utilization of 3,119 hours in 2025, 312 hours lower than 2024 (NEA, 2026-01-29), consistent with solar-heavy additions. The release does not say why. Mechanism (capacity factor) is **not quantified in any source I read**; SC's "China expanded 7x to roughly 10,000 TWh" is **UNVERIFIED (not checked)**.
- **E6 (M) Why queues overstate.** WoodMac: developers file the same project with multiple utilities (Capacity, 2026-08-25). Latitude adds that utilities count load differently, some counting every inquiry (TechTimes, 2026-11-16).

**Flag 4, Missing counter-evidence**
- **E7 (M) Supply-side queue is easing.** LBNL: active generation and storage in US queues was 2,061 GW at end-2025, down 10% from 2024 and from a peak near 2,600 GW at end-2023; 750+ GW withdrawn in 2025; record interconnection agreements in CAISO, ERCOT, SPP and MISO. Gas in queues is 253 GW (+86%). Only 13% of 2000-2020 requests have come online; 75% withdrew (LBNL, https://emp.lbl.gov/news/backlog-power-plants-seeking-transmission-grid-connection-eased-somewhat-2025-amidst, 2026-07-01). This is generation supply, not data-center load, so it is not the same queue as E3.
- **E8 (M) Turbines may not be the gate.** GE Vernova's CEO said turbines are "really not the gating item" in a three-year project cycle (EPC, permitting, fuel) (Power Engineering, https://www.power-eng.com/gas/turbines/data-centers-drive-record-surge-in-ge-vernova-power-equipment-orders-as-turbine-slots-tighten-through-2030/, 2026, Q1 call; exact date not shown).

**Flag 5, Single-constraint framing**
- **E9 (H) "Short on electricity" is one layer of several.** SC says the "bottleneck for America is clear: we are short on electricity" (@socialcapital, 2026-10-12). Evidence of stacked constraints: transformers above 160 weeks (secondary, 2026), turbines to 2031 (Utility Dive 2026-07-22; Bloomberg Oct 2026), CoWoS and wafers (TSMC, 2026-10-15), cost allocation (PJM, $29.4B), permitting politics (CNBC 2026-11-13), and 33 months average from announcement to first power on a small sample (19 projects, 14 in the average; Latitude via TechTimes, 2026-11-16). SC's deep dive itself does cite "delivery queues into 2028 to 2030" (2025-12-03), which fits.

---

## 4. Seed gap status

| Seed | Status | Evidence |
|---|---|---|
| China 543 GW (SC) vs 429 GW (OpenAI) | **VERIFIED (543/542 = 2025 additions) / CORRECTED earlier (429 = 2024).** Residual: 1 GW source difference; solar 315 vs 311 GW | NEA, https://www.nea.gov.cn/20260618/41e848b9ec6543998757db3864e01ab2/c.html, 2026-06-18; Bloomberg, 2026-01-28; pv magazine, 2026-01-28 |
| Goldman "forever bottleneck", $7.6T capex through 2031 | **VERIFIED earlier (2026-10-26); not re-read.** New: Goldman sees ~$1.4T AI hardware spend by end of next year, moratorium risk "modest" | CNBC quoting GS note, 2026-11-13; GS, https://www.goldmansachs.com/what-we-do/investment-banking/insights/articles/navigating-a-system-of-ai-bottlenecks (prior run); Axios, https://www.axios.com/2026/10/20/goldman-ai-energy-infrastructure-bottleneck, 2026-10-20 (search excerpt only) |
| WoodMac 1,000+ GW requested, 28% committed | **VERIFIED (secondary; Bloomberg paywalled), now with Latitude cross-check (different scope)** | Capacity, 2026-08-25; TechTimes, 2026-11-16 |
| TSMC Wei Oct 2, wafer/CoWoS | **CORRECTED earlier (date/source). Latest primary: 2026-10-15 call.** CoWoS capacity numbers **UNVERIFIED (press only)** | prior run; N Globe, 2026-10-27; TrendForce, https://www.trendforce.com/news/2026/09/14/news-tsmc-reportedly-targets-22-2nm-16-3nm-capacity-boost-by-mid-2027-cowos-to-double-by-2028/, 2026-09-14 |
| Power capex forecast | **VERIFIED earlier; utility capex ~$1.3T 2026-2030 (Goldman, via Axios search excerpt 2026-10-20)**; company-level updates in §2 | as listed |
| Transformer / turbine lead times | **VERIFIED partly**: transformer 128 weeks (WoodMac Q2 2025); ">160 weeks" 2026 is secondary (Reuters 2026-07-09 via others, not read) | see E4, E8 |
| Interconnection queue | **VERIFIED**: 2,061 GW generation/storage (LBNL, 2026-07-01). Load-side queue is E3 | LBNL |

---

## 5. Comparison rubric (brief §1 format)

| # | Social Capital said (quote + URL + date) | Public sources add (claim + URL + date) | Gap flag | Sev | Verified? |
|---|---|---|---|---|---|
| 1 | "China wins on raw electric power (added 543 GW of new capacity last year)" (@socialcapital, https://nitter.rdrama.net/socialcapital/status/2109694345226203444, 2026-10-12) | NEA-guided report: 542 GW added in 2025, 3,891 GW cumulative (nea.gov.cn, 2026-06-18); Bloomberg: 543 GW (2026-01-28); utilization down 312 hours (NEA, 2026-01-29) | 3 Missing mechanism | M | Y (capacity); output effect UNVERIFIED |
| 2 | "China expanded 7x to roughly 10,000 TWh" since 2000 (research.socialcapital.com/p/deep-dive-the-electric-grid, 2025-12-03) | NEA: 2025 wind 1.13万亿 kWh + solar 1.17万亿 kWh = 22% of generation; thermal 6.33万亿 kWh, first drop in ten years (nea.gov.cn, 2026-06-18). Total TWh not checked | n/a | L | N (UNVERIFIED) |
| 3 | "The bottleneck for America is clear: we are short on electricity" (@socialcapital, 2026-10-12) | Stacked: transformers (WoodMac 2025-10-15; 2026-08-31), turbines (Utility Dive 2026-07-22), CoWoS (TSMC 2026-10-15), politics/cost (CNBC 2026-11-13; TechTimes 2026-11-16) | 5 Single-constraint | H | Y |
| 4 | "New equipment orders sit in delivery queues into 2028 to 2030" (deep dive, 2025-12-03) | GE Vernova 2031 reservations (2026-07-22); Mitsubishi ~2031 (Oct 2026); transformer >160 weeks (secondary, 2026) | 1 Market moved | M | Y |
| 5 | Demand framing: IEA "global data center demand to more than double by 2030 to nearly 1,000 TWh" (deep dive, 2025-12-03) | Goldman: global data-center power demand +170% 2025-2030 (search excerpt of Axios, 2026-10-20; **not read in full**). WoodMac: 28% of 1,066 GW requests likely committed (2026-08-25); Latitude: 22% signed (2026-11-13) | 2 Sourcing discrepancy / 4 Counter-evidence | H | Y (WoodMac, Latitude); Goldman % partial |
| 6 | "Grid cannot absorb this jump" (deep dive, 2025-12-03) | LBNL: queue down 10% to 2,061 GW; record agreements in four regions (2026-07-01); but median over 3 years request to agreement | 4 Counter-evidence | M | Y |
| 7 | TSMC: US "ahead on chips, dependent on an international supply chain" (@socialcapital, 2026-10-12) | TSMC: demand far above supply; back-end shortage (2026-10-15). CoWoS and prices: press reports only | 5 Single-constraint | M | Partly |

---

## 6. Open questions

1. What explains the 1 GW difference between 542 GW (NEA-guided report) and 543 GW (Bloomberg) and the 311 vs 315 GW solar split? Is one AC and the other DC? **Not answered by any source read.** The NEA's original 2025 statistics table was not found.
2. Which of WoodMac (1,066 GW requested) and Latitude (537 GW reported) is the better yardstick for "real" demand? No source reconciles them. Latitude says the conversion rate "no source can yet say."
3. Will FERC's large-load filings (due 2026-11-16 / 11-20) change the queue rules? Revisit next Electricity and Chips run.
4. Does TSMC confirm CoWoS capacity, or the price rises, in its next release? Check the January 2027 call.
5. The PJM 2029/2030 capacity auction runs Dec 9-15 (TechTimes citing the PJM schedule, 2026-11-16). Worth a tracker row after it clears.
6. The 2026 transformer lead time ">160 weeks" depends on a Reuters story (2026-07-09) read only second-hand. Find the primary.

---

## Appendix A: Chart captions for Quill (all DRAFT, not sent)

- `DRAFT — China's 2025 power build | Added about 542-543 GW of capacity in 2025 (nameplate); cumulative 3,890 GW, +16.1% | Data: NEA, https://www.nea.gov.cn/20260618/41e848b9ec6543998757db3864e01ab2/c.html, 2026-06-18; Bloomberg, https://www.bloomberg.com/news/articles/2026-01-28/china-s-four-year-energy-spree-has-eclipsed-entire-us-power-grid, 2026-01-28`
- `DRAFT — Data-center power: reported vs signed vs operating | Utilities report 537 GW, have signed about 120 GW, and serve 22 GW today | Data: Latitude Media via TechTimes, https://www.techtimes.com/articles/330794/20261116/latitude-finds-data-center-power-contracts-cover-22-reported-load-utilities-seek-power-plants.htm, 2026-11-16`
- `DRAFT — How much requested data-center power gets committed | Wood Mackenzie sees about 28% of 1,066 GW requested being committed (12% firm, 17% likely) | Data: Capacity, https://capacityglobal.com/news/wood-mackenzie-us-grid-operators-set-to-serve-28pc-of-data/, 2026-08-25`
- `DRAFT — US generation interconnection queue | 2,061 GW active at end-2025, down 10% y/y and from a ~2,600 GW peak at end-2023 | Data: Berkeley Lab, https://emp.lbl.gov/news/backlog-power-plants-seeking-transmission-grid-connection-eased-somewhat-2025-amidst, 2026-07-01`
- `DRAFT — Waiting for gear | Power-transformer lead time averaged 128 weeks in Q2 2025; GE Vernova is taking 2031 turbine reservations | Data: Wood Mackenzie, https://www.woodmac.com/news/opinion/mind-the-gap-tackling-supply-chain-challenges-in-the-electric-td-sector/, 2025-10-15; Utility Dive, https://www.utilitydive.com/news/ge-vernova-gas-turbine-backlog-climbs-to-116-gw/826039/, 2026-07-22`
- `DRAFT — CoWoS capacity (press estimates, not TSMC guidance) | Above 130,000 wafers/month in 2026, 200,000 targeted for 2027 | Data: N Globe citing Commercial Times, https://nglobenews.com/en/article/taiwan-tsmc-cowos-packaging-price-hike-2026-10-27/, 2026-10-27`

## Appendix B: Source verification notes

- SC deep dive excerpt read via WebFetch (2026-11-16). The SC homepage fetch returned only "Subscribe", so a newer Electricity and Chips post **cannot be ruled out**; only search found none.
- Bloomberg articles read via search excerpts only (paywalled).
- The Latitude figures are secondhand through TechTimes; the Latitude Intelligence primary was not read.
- The Alliant figure rests on a DataCenterFeed search snippet.
- Goldman figures on power demand (+170%) and $1.3T utility capex come from a search synthesis of Goldman/Axios, not a full read this run.

## Appendix C: Corrections to earlier tracker entries

None this run. The 2026-10-26 entry "~543 GW total UNVERIFIED (NEA primary not read)" is upgraded to verified-to-NEA-guided report (542 GW) and Bloomberg/NEA (543 GW). Prior entries are left as written; history is appended in tracker.md.

## Appendix D: Sources swept (checklist)

| Source | Status this run |
|---|---|
| Social Capital | Read Electric Grid deep dive public excerpt (2025-12-03); @socialcapital Oct 12 post via Nitter mirror. Homepage fetch failed (blank). |
| UBS | Not swept for this topic |
| PitchBook | Not swept |
| S&P Global | Mitsubishi Power interview (S&P Platts, https://www.spglobal.com/energy/en/news-research/latest-news/energy-transition/070326-interview-mitsubishi-power-gas-turbine-orders-stretch-to-2030-amid-ai-security-demand, URL suggests 2026-07-03) via search excerpt only: lead times "five years or more" |
| BIS | Not swept |
| Bloomberg | Headlines/excerpts only (paywalled): China 2026-01-28; WoodMac 2026-08-12; Mitsubishi via EnergyConnects |
| McKinsey | Not swept |
| NBER | Not swept |
| Goldman Sachs | Search excerpts (GS pages; Axios 2026-10-20) and CNBC quote of GS note (2026-11-13) |
| Wood Mackenzie | woodmac.com transformer pieces (2025-10-15; 2026-08-31) via search excerpts; 1,066 GW via Capacity, Energy Central, The Capacity Factor, TFTC |
| LSEG | Not swept |
| Company filings / calls | Utility Dive on GE Vernova (Q2, 2026-07-22), Siemens Energy (fiscal Q3), Sempra/Oncor (Q3, 2026-11-06); TSMC Q3 transcript from prior run, not re-read. No 10-Q/20-F read directly |
| Others | NEA (nea.gov.cn, two pages), LBNL, TrendForce, N Globe, CNBC, Latitude via TechTimes, Mercom, pv magazine (prior run), Plant to Pipeline, Broadview Capital (search excerpt only; not relied on for numbers) |

## Appendix E: Keyword changes (proposed this run)

- ADD (Electricity and Chips) "signed vs reported load": Latitude (2026-11-13), Jefferies (via TechTimes 2026-11-16), WoodMac (2026-08-25); produced verified gap E3 (≥2 sources).
- ADD (Electricity and Chips) "large-load tariff / take-or-pay": NIPSCO-Amazon contract (TechTimes 2026-11-16), Alliant Wisconsin large-load tariff filed (DataCenterFeed, Nov 2026), FERC show-cause orders (TechTimes, 2026-11-16).
- ADD (Electricity and Chips) "data center moratorium": Goldman via CNBC (2026-11-13), CNBC on Texas permitting pause (2026-11-13), Ohio local measures (TechTimes, 2026-11-16).
- No retirements.
