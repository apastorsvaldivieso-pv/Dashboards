**To:** a.pastorsvaldivieso@gmail.com
**Subject:** Competitive Intel Brief — week ending 02 Oct 2026

---

Coverage window: 25 Sep – 2 Oct 2026. Twelfth edition, deduped against the 25 Jul baseline and the 31 Jul, 3 Aug, 7 Aug, 14 Aug, 21 Aug, 28 Aug, 30 Aug, 4 Sep, 12 Sep and 25 Sep editions plus the 25 Sep supplement.

Delivery note: the Gmail connector in this session exposes only a delete-draft tool — no search, no read, no create — so no Gmail draft could be written and the Gmail ledger could not be read. This is the second consecutive run blocked the same way. The ledger was rebuilt from the eleven prior editions in the Competitive Weekly Brief folder, and this file sits in that folder ready to paste. Enabling full Gmail scopes on the connector would restore the draft step.

Eight net-new items: three HIGH, three MEDIUM, two LOW. One is pre-window and previously unreported, flagged individually. Plus two Moody's own moves and one correction to the ledger.

The week in one line: Bloomberg shipped the governed, entitlement-enforced MCP that Moody's Credit MCP has been selling as a differentiator, FactSet published the first real adoption numbers for that architecture, and Moody's answered with a private-credit analytic rather than another connector.

---

BLOOMBERG — HIGH — 29 Sep 2026

Bloomberg launched Bloomberg Enterprise MCP, an AI access layer over Data License Plus (DL+): pricing and reference data across asset classes, company fundamentals and structure, economics and alternative data, drawn from DL+ Live and the Qube Datastore. Scale cited is over 100 million securities and more than 50,000 fields.

The commercially important part is the governance. Requests resolve against the Operational Datastore and client entitlements are validated before data is returned, under standard Data License rights, with tool-level caps on securities and fields per call. Bloomberg is also shipping AI-ready metadata (currency, pricing type, dates), semantic search, entity resolution from names and tickers to instruments, and reusable workflow Skills — named examples include point-in-time universe retrieval, corporate-action adjustment and sanctions exposure assessment. Real-time data support is on the roadmap, and a Terminal solution is promised offering "the same governed and attributable access" into desktop workflows.

Tony McManus, Global Head of Enterprise Data and Indices: "The bottleneck facing financial institutions has shifted from model capability to data readiness." No pricing disclosed, no named clients. Independently corroborated by FactSet's CEO referring to "Bloomberg's recent MCP launch" on the 30 September earnings call.

So what: at BlackRock, Ares and HPS the Bloomberg enterprise seat is already paid for, so the objection shifts overnight from "can your data reach our agents" to "why would we pay twice" — and the sanctions-exposure Skill walks straight into Moody's KYC and compliance ground. Lead with ratings depth, PDs and recovery judgement. Do not open on connector architecture or entitlement handling, because that is now the incumbent's slide too.
https://www.bloomberg.com/company/press/bloomberg-launches-enterprise-mcp-to-seamlessly-connect-bloomberg-data-with-clients-enterprise-ai-applications/
https://fxnewsgroup.com/forex-news/institutional/bloomberg-introduces-enterprise-model-context-protocol/
https://finadium.com/bloomberg-launches-enterprise-mcp-to-connect-data-to-ai-applications/

FACTSET — HIGH — 30 Sep 2026

Q4 revenue $634.7m, up 6.3%; FY26 revenue $2.48bn, up 6.7%, a 47th consecutive year of increase. Organic ASV reached $2,568.2m, up 7.0% (+$168.2m). Q4 net income fell 21.1% to $121.1m on $46.2m of FY26 restructuring charges, while adjusted diluted EPS rose 11.6% to $4.52. FY27 guidance: organic ASV growth 5.0–6.5%, revenue $2,600–2,625m, adjusted EPS $19.25–19.65.

The MCP disclosure is the part that matters. Over 650 clients actively engaged at fiscal year-end, with client adoption up 40% in the quarter alone, and Q4 API call volume at seven times the prior quarter. Only "a couple of dozen" datasets are live out of hundreds, and FactSet launched its first analytics MCP in Q4, extending portfolio analytics into agentic workflows. AI SKUs made up more than 10% of the roughly $86m of ASV added in Q4, exceeding the whole of FY25's AI contribution; clients using AI solutions grew ASV twice as fast as the rest of the base, and a majority of workstation clients increased total ASV after adding MCP.

Packaging is shifting with it. A majority of renewed ASV in Q4 was secured as enterprise agreements or on terms of three years or longer, lifting average contract length by roughly 30% while "broadly preserving pricing". CEO Sanoke Viswanathan described the emerging shape as a large, predictable subscription base covering a set volume of data or agentic capability, with volume-based tiers above it.

By region, Q4 organic ASV grew 7% in the Americas, 5% in EMEA and over 10% in Asia Pacific; institutional buy-side grew 5%, an acceleration of about 100bps. A re-engineered private-markets data pipeline cut processing times by more than 75%. On the competitive frame, Viswanathan called frontier-lab marketplaces "an incredible marketing channel for data" and said of Bloomberg's launch that "the quality, the capabilities that we deliver through our MCP is standing out in the market clearly".

So what: 650 clients and sevenfold call growth is the first externally verifiable proof that MCP distribution converts to ASV, which kills the "nobody is actually using this yet" stall at Oaktree and Hayfin — but the base-plus-consumption-tier structure is the template procurement at both accounts will now ask Moody's to match, so have a view on consumption pricing before the renewal conversation, not during it.
https://www.globenewswire.com/news-release/2026/09/30/3371739/7768/en/factset-reports-results-for-fourth-quarter-and-fiscal-2026.html
https://www.fool.com/earnings/call-transcripts/2026/10/01/factset-fds-q4-2026-earnings-call-transcript/
https://www.gurufocus.com/news/9104575/factset-research-systems-inc-fds-q4-2026-earnings-call-highlights-record-organic-asv-growth-and-surging-ai-adoption

MOODY'S ANALYTICS — HIGH — 1 Oct 2026 (OWN MOVE)

Moody's Analytics and Allvue launched the Moody's Analytics EDF-X Private Credit Model, a forward-looking model that estimates both hard credit events (missed payments, default) and the soft credit events that precede them — covenant waivers and payment-in-kind arrangements.

It is built on de-identified private credit borrower performance data contributed by Allvue, combined with Moody's existing private-company credit risk models, and is delivered through the EDF-X API to customers of both firms. Allvue serves more than 1,000 private capital firms directly or through fund administrators. No borrower count and no pricing disclosed.

Christina Kosmowski, CEO of Moody's Analytics: "By combining Allvue's private market data with Moody's credit intelligence, we can help customers identify borrower stress earlier." Marc Scheipe, CEO of Allvue, framed it as "an independent, third-party evaluation of risk across their direct lending portfolios".

So what: this is the answer to the gap flagged in the 25 September edition — a private-credit-native analytic rather than another connector — and it is the first thing this quarter that beats ICE's identifier standard on ground identifiers cannot reach, so it is the opening at Apollo, HPS, Hayfin and Oaktree: the fight is soft-default prediction, not deal tagging.
https://www.financialcontent.com/article/bizwire-2026-10-1-moodys-analytics-and-allvue-launch-credit-risk-model-to-identify-early-signs-of-borrower-stress-in-private-credit
https://www.stocktitan.net/news/MCO/moody-s-analytics-and-allvue-launch-credit-risk-model-to-identify-8abv0cy4g0r9.html

NASDAQ CALYPSO — MEDIUM — 29 Sep 2026

Nasdaq introduced an agentic AI operating environment inside Calypso, built on the Model Context Protocol and hosted on Amazon Bedrock, with strict sandboxing and no external data retention; on-premises clients can connect to the hosted agents. What is live today is a natural-language assistant over platform data and documentation, with a suite of "governed agentic workers" to follow across capital-markets workflows. Separately, HSBC is expanding its Calypso use to exchange-traded derivatives clearing and extending coverage to US Treasury cash transactions by year-end. Magnus Haglind, Head of Capital Markets Technology, says the platform is evolving "from a system of record into an intelligent platform". No pricing, no named AI clients, no LLM disclosed.

So what: third MCP launch in a single week from a vendor with no credit franchise, which finishes the argument that connector availability is table stakes — delete the MCP slide from the Permira and ICG decks and spend that minute on what the agent is reasoning over instead.
https://www.globenewswire.com/news-release/2026/09/29/3370427/6948/en/nasdaq-calypso-launches-agentic-capabilities-to-scale-ai-adoption-across-the-trade-lifecycle.html
https://www.waterstechnology.com/emerging-technologies/7953294/tt-acquires-trafix-in-247-push-t1-deadlines-in-the-eu-loom-and-more

BLUE FIRE AI AND MIZUHO — MEDIUM — 29 Sep 2026

Singapore-based Blue Fire AI closed US$9m in aggregate commitments, with Asset Management One (AM-One) taking a minority equity stake alongside a strategic commercial agreement with Mizuho Financial Group. AM-One will offer new equity investment products powered by the technology to institutional and retail clients in Japan. AM-One managed approximately JPY80trn (over US$500bn) at 31 December 2025.

The product is a "neuro-symbolic AI decision engine" combining machine-learning pattern recognition with structured reasoning for fundamental analysis at scale, with a claimed seven-year live investment track record after ten years of development. CEO Luke Waddington: "The next era of active management will be built by firms willing to combine deep institutional expertise with genuinely differentiated technology." Valuation and stake size undisclosed.

So what: a $500bn manager chose equity plus commercial agreement over a subscription, which is the structure a BlackRock or a Permira will eventually propose instead of a licence — worth knowing the Moody's answer to "we'd rather own a piece of this" before it is asked rather than after.
https://e27.co/blue-fire-ai-closes-us9m-round-with-am-one-stake-under-mizuho-partnership-20260929/
https://www.finsmes.com/2026/09/blue-fire-ai-closes-9m-funding-round.html
https://apac.entrepreneur.com/business-news/mizuhos-am-one-backs-singapores-blue-fire-to-bring-ai-led-stockpicking-to-japan

ANTHROPIC — MEDIUM — reported 1 Oct 2026 (UNCONFIRMED, press reporting)

Bloomberg reported that Anthropic is targeting marketing its offering the week of 9 November, with potential completion before Thanksgiving and investor meetings from 14 October, seeking a valuation reaching $2trn. Reuters-obtained S-1 documents put 2025 revenue at roughly $4.6bn, grown twelvefold over the year. The confidential S-1 was submitted on 2 June 2026. Treat the valuation figure and the dates as press reporting rather than company guidance — single-sourced to Bloomberg and not confirmed by Anthropic.

So what: Moody's agentic solutions run on Anthropic, so the platform partner is weeks from quarterly public disclosure — that is the concrete reassurance for the vendor-durability question that risk committees at Oaktree and Ares raise, and a reason to expect Anthropic's financial-services push to accelerate rather than pause.
https://finance.yahoo.com/technology/article/anthropic-reportedly-looking-to-ipo-as-early-as-mid-november-180315768.html
https://futurumgroup.com/insights/anthropic-files-for-ipo-looking-to-beat-openai-to-the-punch/

LSEG — LOW — 28 Sep 2026

LSEG was appointed a super validator on the Canton Network, expanding the validator role it already held for its Digital Settlement House (DiSH) application and increasing its governance say over the network.

So what: settlement infrastructure, not credit data or research workflow — logged only so a future run does not mistake it for a missed LSEG move.
https://www.marketsmedia.com/lseg-appointed-as-super-validator-on-canton-network/
https://finadium.com/lseg-expands-canton-network-role-with-super-validator-status/

CREDITBASE — LOW — 18 Sep 2026 (PRE-WINDOW, previously unreported)

CreditBase emerged from stealth with a platform that consolidates legal agreements, emails and chat records into a single database and automates extraction and routing. Modules cover deal records, governance and control, agentic workflows and intelligent routing, with a covenant compliance module in development. Target market is mid-market and institutional lenders in private credit and leveraged finance, US-focused. Founded by John Karakelle (Silicon Valley Bank, then First Citizens) and Yahya Haque (Microsoft, Meta, Snap). Funding amount, investors and clients all undisclosed. Missed by the 25 September edition.

So what: too small and too US-centric to touch a live deal, logged because covenant-compliance automation is the adjacent ground the Moody's private-credit story will have to answer for at Hayfin and ICG within a few quarters.
https://www.fintechfutures.com/fintech-start-ups/credibase-exits-stealth

MOODY'S OWN MOVES

The substantive move is the EDF-X Private Credit Model with Allvue, above. Alongside it, on 30 September Moody's set 21 October for its Q3 2026 results and investor teleconference — diary only.

One correction to the ledger. On 17 June 2026 Moody's launched five decision-grade AI Skills — Earnings Call Summary, Peer Analysis, Public Information Book, Rating Pitch, Sector Analysis — built on the open SKILL.md format and served through Moody's MCP servers, launching in Microsoft 365 Copilot and stated as compatible with platforms from OpenAI, Microsoft, Google and Amazon. Named future areas were credit analysis, lead generation, third-party due diligence and insurance underwriting. Cristina Pieretti, Head of Digital Content and Innovation: "AI platforms are becoming the interface for financial decision-making, and the next phase of adoption will be defined by execution." This never appeared in any prior edition. It is not net-new, and it is recorded here because it materially softens the 25 September claim that Moody's had shipped nothing comparable to Octus's integrations — Moody's has had named, packaged workflow Skills on the same SKILL.md standard Bloomberg has now adopted, since June.
https://www.moodys.com/web/en/us/media-relations/press-releases/moodys-launches-decision-grade-ai-skills-for-major-ai-platforms.html
https://www.stocktitan.net/news/MCO/date-set-for-moody-s-earnings-release-and-investor-b33zp50p1wb5.html

CHECKED, NOTHING NET-NEW (25 Sep – 2 Oct)

S&P Global Market Intelligence (the Farsight partnership and minority investment for Capital IQ Pro pitch decks and CIMs is 23 Jul; the Kensho Data & Platforms / Enterprise Solutions reorg is 6 Jul; the Mobility spin-off completed 7 Jul; a Capital IQ spin-off remains press speculation rather than company statement). MSCI (AI connectors and IndexAI Insights with a ChatGPT app and Claude connector, 24 Feb; UBS private markets partnership 10 Jul). 9fin ($170m Series C at $1.3bn led by HarbourVest, 31 Mar; AI Chat and Research Grid 9 Jun). Debtwire / ION Analytics (editorial and events only). BlackRock Aladdin, eFront and Preqin (eFront Insight end-to-end private markets workflow 5 Feb; Preqin private credit expansion 6 May; the semantic-layer comments were 24 Sep and already covered). Fitch Ratings and Fitch Solutions (macro commentary on an AI market correction only, no product or solutions move). Morningstar / PitchBook (Gemini Enterprise for Financial Services 25 Aug; ChatGPT apps covered 12 Sep). LSEG Workspace (Company Intelligence agent Jul; Deep Research agent Jun). Dun & Bradstreet (Snowflake Cortex Agents on the Commercial Graph 19 Aug). AlphaSense ($350m at $7.5bn, $600m+ ARR and SuperAnalyst 3 Jun; global operations scale-up 7 Apr). Rogo ($160m Series D 29 Apr; the bank strategic-investor round of 10 Sep already covered). Octus (no new platform integration this week after Perplexity, Harvey and Rogo). Hebbia, Model ML, Brightwave, Endex, Perplexity Finance and OpenAI (nothing verifiable in window).

Inaccessible this run: ir.moodys.com/press-releases, rogo.com/news, octus.com/company/news and alpha-sense.com/press each returned a permission or provenance block rather than content; finextra.com and pionline.com returned 403. The WatersTechnology weekly roundup of 2 October is partly paywalled — only the readable section was used, and the Nasdaq Calypso item is independently sourced to Nasdaq's own release. Flagged where used.

WHAT THIS CHANGES FOR NEXT WEEK

Open Apollo, HPS and Hayfin on the EDF-X Private Credit Model, because soft-default prediction — covenant waivers and PIK before a missed payment — is ground ICE's identifier standard cannot reach, and it is the first clean answer this quarter to the question of what Moody's does that a reference-data layer does not. At BlackRock, Ares and HPS assume Bloomberg Enterprise MCP is already on the table and never open on connectors or entitlements, because the incumbent now sells both and the sanctions-exposure Skill reaches into the KYC story too. Carry FactSet's 650 MCP clients and sevenfold call growth into Oaktree and Hayfin as third-party proof that this architecture converts, then be ready for the follow-on question, because FactSet has also published the pricing shape — predictable base plus consumption tiers — that procurement will ask Moody's to match. Put the June Moody's AI Skills launch back into the deck at Ares and HPS, since Moody's has had named workflow Skills on the SKILL.md standard since before Bloomberg adopted it and nobody is saying so. And watch 14 October for Anthropic's investor meetings and 21 October for Moody's own Q3, the two dated events on this beat.

LEDGER — every item covered this edition, for next-run dedup

18 Sep 2026 — CreditBase — Exits stealth with private credit deal-execution platform; deal records, governance, agentic workflows, intelligent routing; covenant compliance module in development; US mid-market and institutional lenders — LOW (PRE-WINDOW, previously unreported)
28 Sep 2026 — LSEG — Appointed super validator on Canton Network, expanding DiSH validator role — LOW
29 Sep 2026 — Bloomberg — Bloomberg Enterprise MCP launches over Data License Plus; 100m+ securities, 50,000+ fields; entitlement validation under standard Data License rights; AI-ready metadata, semantic search, entity resolution; reusable Skills incl. point-in-time universe, corporate-action adjustment, sanctions exposure; real-time and Terminal to follow — HIGH
29 Sep 2026 — Nasdaq Calypso — Agentic AI operating environment on MCP, hosted on Amazon Bedrock, sandboxed, no external data retention; NL assistant live, governed agentic workers to follow; HSBC expanding to ETD clearing and US Treasury cash by year-end — MEDIUM
29 Sep 2026 — Blue Fire AI / Mizuho — US$9m round; Asset Management One (approx. JPY80trn AUM) takes minority equity stake plus strategic commercial agreement; AM-One to offer equity products powered by the technology in Japan — MEDIUM
30 Sep 2026 — FactSet — Q4 and FY26 results: Q4 rev $634.7m +6.3%, FY26 $2.48bn +6.7%, organic ASV $2,568.2m +7.0%; Q4 net income −21.1%; 650+ MCP clients (+40% in quarter), API calls 7x prior quarter, first analytics MCP; AI SKUs >10% of Q4 ASV added; AI clients grew ASV 2x base; EMEA +5%, institutional buy-side +5%; renewals shifting to enterprise agreements and 3yr+ terms, contract length +30%, consumption tiers above a predictable base; FY27 organic ASV guidance 5.0–6.5% — HIGH
30 Sep 2026 — Moody's Corporation — Q3 2026 results and investor teleconference set for 21 October — OWN MOVE
01 Oct 2026 — Moody's Analytics — EDF-X Private Credit Model launches with Allvue; estimates hard and soft credit events (covenant waivers, PIK); built on de-identified Allvue borrower performance data plus Moody's private-company models; delivered via EDF-X API; Allvue serves 1,000+ private capital firms — HIGH / OWN MOVE
01 Oct 2026 — Anthropic — Reported IPO marketing targeted for week of 9 Nov, investor meetings from 14 Oct, valuation sought up to $2trn; S-1 shows 2025 revenue approx. $4.6bn, up 12x — MEDIUM (UNCONFIRMED, Bloomberg/Reuters reporting)

Ledger correction, not net-new: 17 Jun 2026 — Moody's — Launches five decision-grade AI Skills (Earnings Call Summary, Peer Analysis, Public Information Book, Rating Pitch, Sector Analysis) on open SKILL.md format via Moody's MCP servers, launching in Microsoft 365 Copilot; future areas credit analysis, lead generation, third-party due diligence, insurance underwriting. Never logged in a prior edition.

Logged as outside-window, do not re-report as new: MSCI AI connectors and IndexAI Insights (24 Feb 2026); FactSet Chief AI Officer Kate Stepp and CTO Bob Stolte (4 Mar 2026); 9fin $170m Series C at $1.3bn (31 Mar 2026); AlphaSense global operations scale-up (7 Apr 2026); Rogo $160m Series D (29 Apr 2026); BlackRock Aladdin eFront Insight end-to-end private markets workflow (5 Feb 2026); BlackRock Aladdin private credit on Preqin (6 May 2026); AlphaSense $350m at $7.5bn and SuperAnalyst (3 Jun 2026); 9fin AI Chat and Research Grid (9 Jun 2026); Moody's data in Amazon Quick via MCP (16 Jun 2026); Moody's AI Skills for M365 Copilot (17 Jun 2026); LSEG Workspace Deep Research agent (Jun 2026); S&P Global MI reorg into Kensho Data & Platforms and Enterprise Solutions (6 Jul 2026); S&P Global Mobility spin-off completion (7 Jul 2026); MSCI–UBS private markets partnership (10 Jul 2026); LSEG Company Intelligence agent in Workspace (Jul 2026); S&P Global MI–Farsight partnership for Capital IQ Pro (23 Jul 2026); Dun & Bradstreet Snowflake Cortex Agents on Commercial Graph (19 Aug 2026); Morningstar PitchBook GenAI 20 Index (15 Jan 2026); Moody's × MSCI private credit risk tool (28 Apr 2025).

Diary: Anthropic investor meetings 14 Oct 2026; Moody's Q3 2026 results 21 Oct 2026.

Thanks,
Alvaro
