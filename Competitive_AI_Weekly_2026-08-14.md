# Competitive AI Weekly — 7–14 August 2026

Week ending 14 Aug 2026 · Coverage window 7–14 Aug 2026 · Fifth edition

Deduped against the 25 Jul baseline, 31 Jul, 3 Aug & 7 Aug editions · Focus: European AM, alternative asset managers, private credit, GenAI

**7** net-new items
 4 HIGH
 3 MEDIUM
 0 LOW

Busier week than it first looked — the action was at the deal and workflow layer, not in headline product launches. Three in-window moves push AI agents deeper into private-markets execution: Rogo bought a due-diligence platform, D&B went headless into nCino's lending workflows, and OpenAI put a named asset-manager case study behind Model ML. NVIDIA's $500B compute-financing consortium names Apollo and BlackRock directly, and Anthropic made two enterprise-economics moves (permanent Sonnet 5 pricing, Compliance API into Cowork/Claude Code). I've also pulled forward one pre-window item no prior edition caught — PitchBook/Lumonic's MCP go-live — because it lands on the private-credit-surveillance pitch. Four HIGH, three MEDIUM.

## High — items that change what to say in the room

## Rogo

**High
 11 Aug 2026
 — in-window**

### Acquires Rivanna to bolt AI-native private-markets due diligence onto its Felix agent

Rogo acquired Rivanna, an AI platform built for private-equity due diligence, and is folding it into Rogo and its autonomous agent Felix. The combined capability ingests entire virtual data rooms, queries tens of thousands of documents with citations, flags risks proactively, tracks diligence and keeps deal knowledge centralised — "institutional-grade, cited analysis in minutes, not hours." Rivanna had already run on 300+ live M&A transactions for PE and corporate-development teams. This pushes Rogo from financial-research assistance into private-equity / private-credit transaction execution.

**So what for Alvaro:** the message is that the differentiation can't be "AI for credit research" — Rogo is now attacking the document-heavy diligence workflow that alt managers run on analyst labour. The defensible Moody's position is proprietary credit and private-company intelligence embedded *inside* the diligence agent (financials, PDs, ownership, adverse-media, sector benchmarks, credit signals), not competing with Rogo on the interface. Carry one line into HPS, Ares, Oaktree, Apollo and Permira: whoever runs diligence in Rogo/Felix still needs Moody's decision-grade content underneath the agent's reasoning.

**Sources:**
 [Rogo announcement](https://x.com/RogoAI/status/2087226824241598661) ·
 [Rivanna](https://www.rivanna.ai/post/rivanna-acquired-by-rogo)

## Dun & Bradstreet

**High
 13 Aug 2026
 — in-window**

### Goes headless into nCino — D&B Commercial Graph embedded in Client Lifecycle Management, GA later 2026 starting in EMEA

D&B and nCino announced a strategic alliance embedding the D&B Commercial Graph (verified business identity, ownership and risk across 650M+ entities, 107B+ monthly data-quality checks) directly into nCino's Client Lifecycle Management. Identity and risk data follow a commercial client from onboarding through loan origination to ongoing monitoring, instead of being re-collected in separate steps; D&B beneficial-ownership data is accessible inside nCino for continuous KYC. General availability is planned later in 2026, **starting with EMEA institutions** before expanding beyond the UK. A commissioned Celent study cited ~$14,700 average commercial-onboarding cost as the pain being targeted.

**So what for Alvaro:** this is a clean example of a major data provider going headless and workflow-native — putting its data inside somebody else's agentic platform rather than making customers open a standalone app. It's highly analogous to the Moody's MCP / agentic strategy, and it reframes the competitive question for European AM: it's no longer who owns the desktop, but *whose proprietary dataset becomes the default context an agent calls*. It also gives D&B a credible route into private-credit borrower and KYC workflows — worth flagging where BlackRock, Apollo or Ares run bank-style origination or continuous-monitoring processes.

**Sources:**
 [PR Newswire](https://www.prnewswire.com/news-releases/ncino-and-dun--bradstreet-collaborate-to-speed-client-onboarding-and-enhance-lifecycle-management-for-financial-institutions-302850611.html) ·
 [StockTitan](https://www.stocktitan.net/news/NCNO/n-cino-and-dun-bradstreet-collaborate-to-speed-client-onboarding-and-vj5ppvp9evr4.html)

## OpenAI

**High
 10 Aug 2026
 — in-window**

### Model ML case study shows OpenAI models running research → model → deck as one investment workflow

OpenAI published a finance deployment with Model ML, whose agents take an assignment from research and analysis through to editable Excel models and PowerPoint investment materials — the core agent selects tools, reconciles evidence, runs the calculations and routes across models, now expanded in production on GPT-5.6 Sol. The headline proof point is a named (but unidentified) **global asset manager**: a bespoke tearsheet that took an analyst ~60 minutes now takes ~5. Model ML's agents also processed data rooms of 100,000+ rows and hundreds of files in a single pass, and it reported GPT-5.6 Sol using ~36% fewer tokens per Excel workbook than Anthropic Opus 5, and ~21% fewer than Fable 5 on its PowerPoint workflow.

**So what for Alvaro:** this is more than a ChatGPT feature — it shows the traditional split between the research terminal, Excel modelling and deck production collapsing into one agentic workflow, sitting on OpenAI rather than Anthropic. Don't assume the buy-side standardises on Claude, and don't assume the Moody's interface stays the destination. Position Moody's data and analytics as tools callable by *whichever* orchestration layer wins — OpenAI, Claude, Model ML, Rogo or the client's own agents — and keep the "Moody's-data-in-both-stacks" answer ready for any BlackRock, Apollo or Ares LLM-selection conversation.

**Sources:**
 [OpenAI — Model ML case study](https://openai.com/index/model-ml/) ·
 [StartupHub](https://www.startuphub.ai/ai-news/artificial-intelligence/2026/model-ml-s-gpt-5-6-sol-transforms-finance-analysis)

## PitchBook / Lumonic (a Morningstar company)

**High
 23 Jul 2026
 — pre-window, previously unreported**

### Lumonic MCP server hits general availability — auditable, source-linked private-credit portfolio data into Claude & ChatGPT

Lumonic — the AI portfolio-monitoring platform for private credit and PE that PitchBook (a Morningstar company) acquired in 2025 — took its MCP server to general availability for all customers. It gives Claude, ChatGPT and any firm-approved MCP assistant read-only access to a firm's own portfolio financials, covenant status, reporting status and tracked KPIs, mapped to each user's permissions, with every figure linked back to its source document down to the exact cell. It ships with an MCP Library of tested prompts/artifacts for PC/PE/VC and pairs with PitchBook's Premium Connector so one prompt pulls PitchBook comps plus the firm's own portfolio numbers into a single auditable Excel model. Named use cases: flag borrowers approaching covenant breach, list who hasn't submitted financials, generate per-company one-pagers, pull exposure by sector/vintage. CEO Kevin Hsu: "Any AI assistant can produce an EBITDA figure in seconds. Proving it is the hard part." Dated 23 Jul so pre-window, but no prior edition caught it and it's on the bullseye.

**So what for Alvaro:** the most direct competitive answer yet to the Moody's agentic / private-credit-surveillance pitch — auditable, source-linked covenant-breach detection inside Claude, backed by a Morningstar/PitchBook incumbent, not a seed-stage startup like Allvue or Ellis. Expect "we already monitor covenants in Lumonic and query it in Claude — why Moody's?" in HPS, Ares, Oaktree, Hayfin, Permira or Apollo rooms. Counter: Lumonic reasons over the GP's own submitted documents; Moody's supplies the external, independent credit view those numbers must be benchmarked against — the committee-grade audit trail Lumonic's internal extraction can't manufacture.

**Sources:**
 [Investing News Network](https://investingnews.com/lumonic-launches-mcp-server-bringing-audit-ready-portfolio-data-to-leading-ai-assistants/) ·
 [BusinessWire](https://www.businesswire.com/news/home/20260723551409/en/) ·
 [lumonic.com/mcp](https://www.lumonic.com/mcp)

## Medium — context that shifts positioning

## NVIDIA × Apollo / BlackRock / Blackstone / Brookfield / Goldman / KKR

**Medium
 10 Aug 2026
 — in-window**

### NVIDIA and six financial firms to build "Compute Financing Platforms" mobilising $500B+ of third-party capital

NVIDIA signed MOUs with Apollo, BlackRock, Blackstone, Brookfield, Goldman Sachs and KKR to establish AI compute-infrastructure financing platforms mobilising over $500B of third-party capital — loans and credit — to fund AI data centres and "AI factories." NVIDIA can optionally backstop up to $125B (~25%). Two of the six — Apollo and BlackRock — are your Tier 1 accounts; Blackstone, Brookfield and KKR sit adjacent. A credit-market event, not a data-vendor product, but the most account-relevant thing this week.

**So what for Alvaro:** Apollo and BlackRock are now standing up large, complex, monitoring-hungry AI-infrastructure credit exposures — exactly the new-issuance-plus-surveillance need the Moody's Q2 story was built on (~20% of $5B+ deals tied to AI infrastructure; AI-infra funding as a rating-agency tailwind). Use it as the cold-open in the next Apollo and BlackRock credit-team conversation, then bridge from their own headline to how MA packages ratings and monitoring into their internal workflows.

**Sources:**
 [NVIDIA Newsroom](https://nvidianews.nvidia.com/news/nvidia-partners-with-apollo-blackrock-blackstone-brookfield-goldman-sachs-and-kkr-to-establish-ai-compute-infrastructure-financing-platforms-to-mobilize-over-500-billion-of-third-party-capital) ·
 [Quartz](https://qz.com/nvidia-wall-street-ai-infrastructure-financing-500-billion-081126) ·
 [Bloomberg](https://www.bloomberg.com/news/newsletters/2026-08-12/nvidia-calms-credit-markets-with-ai-capital-consortium)

## Anthropic

**Medium
 10 Aug 2026
 — in-window**

### Claude Sonnet 5's introductory pricing made permanent — $2/$10 per M tokens, September hike to $3/$15 cancelled

Anthropic scrapped the planned 1 September step-up and locked Sonnet 5 at $2 per million input / $10 per million output tokens — a third below the intended $3/$15 — amid reports of enterprises struggling with ballooning AI costs, and weeks after OpenAI's own price cuts. Sonnet 5 is positioned around agentic work, tool use and knowledge work, with performance in some settings approaching the Opus tier. (Caveat Anthropic itself flags: tokenizer changes can map the same text to ~1.0–1.35× as many tokens, so headline pricing isn't a clean one-third workload saving.)

**So what for Alvaro:** cheaper agentic economics make large-scale document interrogation, portfolio monitoring and persistent agents easier to justify at any asset manager — which raises the relative value of the proprietary data and tools connected to the model and weakens any premium pricing based merely on having an embedded LLM. It's a clean concrete opener for anyone at BlackRock, Apollo or Ares who paused on token cost, and it updates the Opus 5 pricing thread from the 31 Jul brief.

**Sources:**
 [The Stack](https://www.thestack.technology/anthropic-follows-openai-with-frontier-model-price-cuts/) ·
 [Claude Platform pricing](https://platform.claude.com/docs/en/about-claude/pricing)

**Medium
 11 Aug 2026
 — in-window**

### Compliance API coverage extended to Claude Cowork and Claude Code (beta for Enterprise)

Anthropic extended its Compliance API to Claude Cowork (desktop, web, mobile) and Claude Code (CLI and desktop) in beta for Claude Enterprise customers. Compliance and security teams can pull session content and metadata — prompts, responses and tool activity in one consolidated, server-hosted transcript per session — through the same interface they already use for Claude chats. It excludes Claude Code on web, Claude Code via the Claude Platform, and sessions on Bedrock, Vertex AI or Microsoft Foundry.

**So what for Alvaro:** compliance and auditability is one of the biggest blockers to deploying agents inside regulated financial institutions, so extending governed coverage to Anthropic's agentic work environments chips away at exactly that objection. It strengthens Claude as an enterprise *execution* environment (not just an LLM), which reinforces the integration assumption to bring to InfoSec/compliance stakeholders at BlackRock, Apollo and Ares: professionals operate from Claude/Cowork while Moody's data sits behind governed connectors/MCP.

**Sources:**
 [Claude — Compliance API update](https://claude.com/blog/compliance-api-cowork-and-claude-code)

## Moody's own moves — same-view read

**Own7–14 Aug 2026**

### No net-new Moody's product, partnership or M&A press in the window

Q2 (22 Jul: +45% first-time private-credit mandates, agentic solutions named an MA priority, ~20% of $5B+ deals tied to AI infrastructure) still stands and hasn't been superseded; the 14 Aug dividend ex-date carries no commercial read. The relevant signal is competitive-adjacent: the NVIDIA consortium reinforces the Moody's "AI-infrastructure debt is a rating-agency tailwind" framing, while D&B-into-nCino and Lumonic's MCP go-live show rivals executing the same headless / agent-native distribution model Moody's is pursuing — a reason to keep the MCP and data-licensing story crisp and first in the room.

## Checked — nothing net-new inside 7–14 Aug

Core Nine / adjacent names checked with nothing net-new dated in the window:

- **S&P Global** — no window press; Q2, Adaptive Retrieval, datacenterHawk, With Intelligence-in-Capital IQ Pro, ETF Intelligence all in prior briefs or pre-window.
- **Bloomberg** — no net-new Terminal / BQuant / ASKB news; Canoe acquisition covered 31 Jul.
- **MSCI** — only the routine 12 Aug index-review announcement; Q2 and first AI training-data licence in prior briefs.
- **FactSet** — published new MCP / connected-AI-architecture material 11–12 Aug, but it's thought-leadership, not a product, deployment, client win or partnership — not counted.
- **BlackRock Aladdin / eFront / Preqin** — no window product press; Preqin Benchmarks expansion was 8 Jul. (BlackRock appears this week via the NVIDIA consortium, above.)
- **FitchRatings** — nothing net-new; record 6% private-credit default print covered 7 Aug.
- **LSEG** — nothing in window; H1 results and Workspace/Microsoft/MCP detail covered 3 Aug.
- **Morningstar / PitchBook** — the net-new PitchBook item is Lumonic MCP GA, above; Perplexity integration was 7 May.
- **AlphaSense / Hebbia** — fresh AI thought-leadership but no comparable commercial event; AlphaSense $350M round was 3 Jun, AlphaSummit covered 31 Jul.
- **Perplexity Finance / Brightwave / Endex / Ellis** — no net-new FS-specific move; Ellis stealth launch covered 3 Aug; OpenAI's $7B employee tender (11 Aug) is corporate, not an FS product.

## What this changes for next week

The theme is that AI is moving into private-markets execution and data providers are going headless, so the Moody's line has to be "proprietary credit intelligence as callable context," not "an AI for research." Open the next Apollo and BlackRock credit-team conversations on the NVIDIA compute-financing platform they just joined — their own headline, and a direct surveillance-and-ratings opening. Before any HPS, Ares, Oaktree, Hayfin or Permira meeting, internalise both Rogo/Rivanna and Lumonic's MCP go-live, and lead with the counter: whoever runs diligence in Rogo/Felix or monitors covenants in Lumonic still needs Moody's independent, committee-grade credit view underneath. Treat D&B-into-nCino and OpenAI/Model ML as proof that the desktop is losing to the agent — reframe every European-AM conversation around whose data an agent calls, and keep the "Moody's-data-in-both-stacks" answer ready. Cheaper Sonnet 5 and the Compliance API extension are the concrete openers for anyone who stalled on cost or InfoSec.

---

_Competitive Intel Brief · week ending 14 Aug 2026 · verified, net-new only · prepared for Alvaro De Pastors, Moody's Analytics_
