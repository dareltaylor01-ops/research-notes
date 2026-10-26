# Learn With Me: Living Tracker (append-only)

Status: DRAFT. This is an internal research tracker, not for publication.
Rules: append history rows only and never edit or delete earlier rows. Every value cites its source URL and date, and anything unverified is labeled UNVERIFIED.

| Topic | Metric | Value | Source (URL) | Source date | Last checked | Change vs prior | Status |
|---|---|---|---|---|---|---|---|
| AI Stack | Nvidia / TSMC / ASML gross margin | see brief §4 | TBD | TBD | — | — | unverified (baseline from brief, 2026-10-24) |
| AI Stack | Inference share of compute by 2030 | see brief §4 | TBD | TBD | — | — | unverified (baseline from brief, 2026-10-24) |
| AI Stack | Announced DC GW vs energized | see brief §4 | TBD | TBD | — | — | unverified (baseline from brief, 2026-10-24) |
| Private Credit | Chip-backed debt market size | see brief §4 | TBD | TBD | — | — | unverified (baseline from brief, 2026-10-24) |
| Private Credit | Hyperion / Excalibur bond prices | see brief §4 | TBD | TBD | — | — | unverified (baseline from brief, 2026-10-24) |
| Private Credit | CoreWeave borrowing cost | see brief §4 | TBD | TBD | — | — | unverified (baseline from brief, 2026-10-24) |
| Private Credit | AI borrowing YTD / off-balance-sheet | see brief §4 | TBD | TBD | — | — | unverified (baseline from brief, 2026-10-24) |
| AI ROI | % firms with positive EBIT from AI | see brief §4 | TBD | TBD | — | — | unverified (baseline from brief, 2026-10-24) |
| Elec & Chips | China capacity added (GW) | see brief §4 | TBD | TBD | — | — | unverified (baseline from brief, 2026-10-24) |
| Elec & Chips | Grid requests vs utility commitments | see brief §4 | TBD | TBD | — | — | unverified (baseline from brief, 2026-10-24) |
| Elec & Chips | Power capex forecast | see brief §4 | TBD | TBD | — | — | unverified (baseline from brief, 2026-10-24) |

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
