# Competitive AI Weekly — 5–11 September 2026

This week is materially more significant than the previous one. I found **seven net-new developments** that clear the threshold after running the company-by-company scan and the ecosystem/model cross-check. The biggest by some distance is **ChatGPT for Financial Services**.

## OpenAI / ChatGPT

### 10 Sep — ChatGPT for Financial Services launches — **HIGH**

OpenAI launched a dedicated **ChatGPT for Financial Services** experience built on ChatGPT Work and GPT‑6 Astra. **Morgan Stanley and Evercore are design partners**, and the initial workflows target investment banking and equity research: company research, valuation/LBO modelling, buyer screening, earnings analysis, pitchbooks, Excel, Word and PowerPoint outputs.

The strategically important part is the data architecture. **Daloopa, PitchBook, LSEG News and Crunchbase are built directly into the product**, with OpenAI indexing and hosting the data itself. Separately, OpenAI says it is working with **S&P Capital IQ, LSEG, MSCI, Dow Jones Factiva and Moody’s on shared sign-in and entitlement integrations**. Its broader connector ecosystem includes 50+ connectors including FactSet, Preqin and Datasite.

**Source quality:** OpenAI primary + Reuters — High.  
**Deployment:** Available to eligible financial institutions.  
**Named clients/partners:** Morgan Stanley, Evercore, Daloopa, PitchBook, LSEG, S&P Global, MSCI, Factiva, Moody’s and others.  
**Outcome:** No client ROI or pricing disclosed yet.  
**Why HIGH:** OpenAI is no longer merely supplying a model underneath financial applications; it is beginning to own the **research + data + modelling + deliverable workflow itself**.

**Commercial implication — inference:** This is both a threat and an opportunity for Moody’s. The wrong battle is trying to beat ChatGPT on the generic assistant layer. The stronger position is making Moody’s **credit, private-company, default/recovery, research and risk intelligence the trusted layer ChatGPT calls**, particularly for private credit and credit risk where OpenAI’s first release is much less developed than investment banking/equity research.

[OpenAI — ChatGPT for Financial Services](https://openai.com/index/introducing-chatgpt-financial-services/?utm_source=chatgpt.com)

### 9 Sep — Astra reaches production + Hebbia benchmark — **HIGH**

The Astra model itself was captured last week, so I am **not counting the model launch again**. The net-new development is its production rollout across ChatGPT Work, Codex and the API, together with pricing, enterprise controls and new finance-relevant evaluations. API pricing starts at **$10/million input tokens and $50/million output tokens**.

Most relevant: **Hebbia** says Astra produced the best decks it had tested, followed the brief **17% more faithfully** than the next-best model and sourced claims to the correct document **19% more often**. OpenAI also published validation from **XTX Markets**.

**Deployment:** Production.  
**Outcome:** Hebbia +17% brief adherence and +19% correct-document sourcing in its evaluation.  
**Why HIGH:** Horizontal frontier models are rapidly absorbing document analysis, financial reasoning and presentation creation that specialised finance platforms previously treated as differentiators.

**Commercial implication — inference:** Owning the LLM is becoming less important. **Data quality, specialist models, provenance and workflow context** become more important.

[OpenAI — GPT-6 Astra for work](https://openai.com/index/gpt-6-astra-next-generation-work/?utm_source=chatgpt.com)

### 10 Sep — Data agent launches in ChatGPT Work — **MEDIUM**

OpenAI launched a **Data agent** that connects directly to Snowflake, Databricks, BigQuery, Redshift, MongoDB, ClickHouse, Google Drive and SharePoint. It can investigate data, create interactive dashboards and work with Power BI, Tableau, Sigma, ThoughtSpot, Oracle BI and Omni while respecting existing permissions and semantic definitions.

**Deployment:** Available through ChatGPT Work.  
**Outcome:** OpenAI says nearly all its product organisation and more than two-thirds of GTM use data agents internally.  
**Why MEDIUM:** It is horizontal rather than finance-specific, but it makes ChatGPT an increasingly credible layer over firms’ internal data and BI estates.

**Commercial implication — inference:** Asset managers may increasingly analyse **internal Snowflake/Databricks data + external licensed datasets from the same agent**. Moody’s therefore needs to be easy to combine with the client’s own data rather than operating as a separate analytical island.

[OpenAI — Data agent](https://openai.com/index/put-data-to-work/?utm_source=chatgpt.com)

### 10 Sep — Agents API enters public beta — **MEDIUM-HIGH**

OpenAI also launched the **Agents API**, exposing the managed orchestration layer behind Codex. It handles long-running sessions, context compaction, MCP and custom tools, programmatic parallel tool calls and multi-agent delegation; agents can run in OpenAI sandboxes, client infrastructure or partner environments.

One financial-services launch customer, **Hypha**, says separating the agent harness from the sandbox reduced failed agent responses by **86%**. OpenAI charges no additional Agents API fee during the beta beyond model/tool usage.

**Why MEDIUM-HIGH:** It lowers the infrastructure hurdle for banks, asset managers and fintechs to build their **own** production agents rather than buying a vertically integrated agent application.

**Commercial implication — inference:** This strengthens the case for Moody’s to expose capabilities as **modular callable tools**—data, PDs, models, research, entity intelligence—because clients may increasingly build the orchestration layer themselves.

[OpenAI — Agents API](https://openai.com/index/introducing-the-agents-api/?utm_source=chatgpt.com)

## Rogo

### 10 Sep — Five major banks make strategic investments — **HIGH**

**Barclays, BNP Paribas/Opera Tech Ventures, Citi Ventures, MUFG Innovation Partners and Société Générale** invested strategically in Rogo, alongside Sixth Street co-founder Josh Easterly. Rogo says it now has nine global banks on its cap table and deployments covering **50,000+ professionals across 350+ firms**. It explicitly says the funding will accelerate EMEA and APAC expansion, with both regions scaling toward hundreds of employees.

The Wall Street Journal reports the new strategic investment at roughly **$30m** and says Rogo is now expanding into wealth-management workflows such as portfolio reviews and client relationship analysis.

**Source quality:** Rogo + WSJ — High; the $30m figure is press-reported rather than company-confirmed.  
**Deployment:** Existing production deployments.  
**Why HIGH:** This is not simply another funding round. Major banks—including Barclays, BNP and Société Générale in Europe—are putting capital behind the platform while Rogo is simultaneously expanding EMEA distribution.

**Commercial implication — inference:** Rogo increasingly looks like a potential **default AI orchestration layer for institutional finance**. Getting Moody’s proprietary data and analytics deeply embedded in these environments becomes more important before client workflows solidify around alternative sources.

[Rogo — Strategic investors announcement](https://rogo.com/news/strategic-investors?utm_source=chatgpt.com)

### 8 Sep — Rogo integrates live Datasite VDRs — **HIGH**

Rogo and **Datasite** launched a connector allowing authorised deal teams to work directly against live virtual data rooms without exporting documents or bypassing permissions. Users can interrogate an entire deal room, folder or document with citations and then use the information in diligence summaries, **IC memos, financial models, valuations, management-meeting preparation and diligence trackers**.

Rogo can combine that VDR content with internal firm knowledge, public filings, news, market data and other licensed sources. The connector is available to Rogo clients with active Datasite projects.

**Outcome:** No quantified ROI disclosed.  
**Why HIGH:** This gives Rogo access to one of the most valuable sources of proprietary information in PE/private-credit transactions—the live deal room.

**Commercial implication — inference:** There is an obvious differentiated Moody’s workflow here: **live borrower/deal-room evidence + Moody’s private-company financials + PD/default/recovery data + sector/macro context → IC memo and monitoring workflow**. The risk is that Rogo owns the orchestration and treats data vendors as interchangeable inputs.

[Rogo — Datasite partnership](https://rogo.com/news/announcing-rogo-s-partnership-with-datasite?utm_source=chatgpt.com)

## BlackRock Aladdin

### 9 Sep — Danske Bank launches Butterfly on Aladdin Wealth — **MEDIUM**

Danske Bank launched **Butterfly**, its new private-banking advisory platform powered by Aladdin Wealth. Danske says it is the **first Nordic bank** to offer investment advice powered by Aladdin Wealth. The platform performs continuous portfolio monitoring, stress testing, scenario analysis, portfolio optimisation and targeted alerts/recommendations.

Private Banking clients went live on 9 September, with Premium clients and expansion into Finland and Sweden planned later this year. Danske says greater automation of routine work should free advisers to focus on personalised recommendations, although no quantified productivity figure was provided.

**Why MEDIUM:** Primarily wealth rather than institutional asset management/private credit, but it is another meaningful European example of Aladdin becoming the underlying analytics and workflow infrastructure.

**Commercial implication — inference:** Moody’s should increasingly think about **embedding intelligence into Aladdin-type environments**, not only persuading the end user to move into a Moody’s interface.

[BlackRock — Danske Bank / Aladdin Wealth](https://www.blackrock.com/aladdin/discover/press-release/danske-bank-invests-in-advisory-solution-for-affluent-private-clients?utm_source=chatgpt.com)

## Carryover verification: Model ML / Astra

The **Model ML Astra test that was pending last week is now fully verified**, but its event date is **4 September**, so I have not counted it as a new item for 5–11 September.

Model ML tested Astra before launch on its finance-specific Composite. Astra led **four of five categories**. In analytical finance it scored 93.21 at an estimated $6.92/task versus Fable 5.1 at 92.54/$5.23 and Gemini 3.8 Flash at 92.39/$0.97. In PowerPoint it scored 80.88 versus Fable 5.1 at 80.79, but at **$4.65 vs $12.71 per task**. Model ML’s conclusion is important: model quality and economics differ by workflow, reinforcing its **model-agnostic routing** strategy.

[Model ML — GPT-6 Astra benchmark](https://modelml.com/articles/gpt-6-astra?utm_source=chatgpt.com)

## What I excluded

After both passes, I found no additional material net-new event dated **5–11 September** for Bloomberg, MSCI, FactSet, Dun & Bradstreet, 9fin, Debtwire, LSEG, AlphaSense, Credit Benchmark, Perplexity Finance or Anthropic financial services.

The **Capital IQ spin-off** is deliberately not repeated: the underlying Bloomberg report is dated **1 September**, despite some later articles resurfacing it this week. Rogo’s **Arvo acquisition** is likewise a 1 September event already captured in last week’s corrected report.

For **S&P, MSCI, LSEG and FactSet**, their appearance inside the new ChatGPT Financial Services ecosystem is relevant, but I have treated it under the OpenAI launch rather than manufacturing four separate “new” vendor announcements. That avoids double-counting.

## The three that matter most

1. **ChatGPT for Financial Services** — potentially the most consequential competitive launch in this monitoring series so far because OpenAI is moving directly into the financial workflow and data-consumption layer.
2. **Rogo’s strategic bank investment** — strong evidence that finance-native agent platforms are moving from experimentation toward institutional infrastructure, with an especially relevant EMEA signal.
3. **Rogo + Datasite** — the private-markets workflow is getting materially deeper: AI can now work directly against secure live transaction data, not merely public research.

The common thread is important: **OpenAI is pulling trusted financial data into a horizontal AI execution layer; Rogo is pulling trusted financial and proprietary transaction data into a vertical execution layer; data providers increasingly compete to be the trusted intelligence source called by either.** That argues against treating the standalone UI as the strategic moat.

