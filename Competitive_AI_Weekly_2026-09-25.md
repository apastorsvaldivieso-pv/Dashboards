# Competitive AI Weekly — 18–24 September 2026

Five developments cleared the materiality threshold this week. The strongest pattern is the convergence of **finance-native orchestration + licensed data + governed agent access**.

### Dun & Bradstreet — 24 Sep — **HIGH**

D&B launched new AI-powered credit capabilities inside **D&B Finance Analytics** and via its MCP server into **Claude, ChatGPT, Codex, Microsoft Copilot and Databricks**. The workflows cover company research, risk analysis, identity verification, portfolio management and monitoring. Gemini Enterprise support is planned.

D&B reports benchmarked improvements of **30–40% faster credit analysis**, **20–25% lower credit losses** from earlier risk visibility, and **10–15% more growth opportunities** from portfolio insight. These are D&B-reported benchmarks, not independently audited customer results.

**Deployment:** live.  
**Named partners:** Anthropic, OpenAI, Microsoft, Databricks.  
**Source quality:** primary — High.  
**Why HIGH:** This is a very direct example of a credit-data provider turning proprietary risk intelligence into agent infrastructure rather than keeping it inside its own application.

**Commercial implication — inference:** This is probably the clearest current benchmark for Moody’s Credit MCP. Simply exposing data through MCP is becoming table stakes; the stronger commercial story is proving that Moody’s PDs, private-company data, defaults/recoveries and research improve measurable underwriting and monitoring outcomes.

[D&B announcement](https://www.dnb.com/en-us/newsroom/press-releases/dnb-accelerates-credit-analysis-with-new-ai-powered-capabilities.html?utm_source=chatgpt.com)

---

### Rogo + Octus — 21 Sep — **HIGH**

Rogo partnered with **Octus**, making Octus data available as a configurable source directly inside Rogo agents. The content includes private-company financials, capital structures, covenants, restructuring intelligence, credit news, debt documents and structured-credit data.

Mutual customers can use it across **origination, underwriting, portfolio monitoring, distressed credit, private credit and restructuring**, including investment-strategy screening, covenant analysis and preparation of underwriting and IC materials.

**Deployment:** available now to mutual licensed customers.  
**Named partner:** Octus.  
**Outcome:** no quantified ROI disclosed; Octus says its corpus includes millions of documents across leveraged-credit and private-credit borrowers.  
**Source quality:** primary — High.  
**Why HIGH:** This is a direct competitive move into the exact private-credit workflows that matter most: sourcing, underwriting, IC and monitoring.

**Commercial implication — inference:** Rogo + Octus is much closer to a direct Moody’s workflow competitor than a generic LLM. Moody’s advantage needs to be the risk layer Octus cannot easily replicate: PDs, defaults and recoveries, ratings/research, private-company coverage and scenario analytics.

[Rogo / Octus announcement](https://rogo.com/news/announcing-rogo-s-partnership-with-octus?utm_source=chatgpt.com)

---

## Model ML

### 24 Sep — Daloopa integration — **HIGH**

Model ML integrated **Daloopa** through MCP. Daloopa provides audit-linked fundamentals across **6,000+ public companies**, with individual datapoints linked back to filings, investor presentations and press releases.

Model ML users can now use that data directly when building models, pitchbooks, diligence reports and investment memos. The integration is **available today** to customers with an active Daloopa licence.

**Deployment:** live.  
**Partner:** Daloopa.  
**Outcome:** no quantified customer ROI disclosed.  
**Source quality:** primary — High.  
**Why HIGH:** Model ML is increasingly behaving like a finance-specific orchestration layer where models and premium datasets are modular components rather than separate destinations.

**Commercial implication — inference:** This reinforces the argument that platforms such as Model ML should be viewed as potential distribution environments for Moody’s, not only as competitors.

[Model ML / Daloopa announcement](https://modelml.com/articles/model-ml-partners-with-daloopa-to-bring-audit-linked-financial-data-into-the-platform?utm_source=chatgpt.com)

### 24 Sep — Model ML Sites — **HIGH**

Model ML also introduced **Sites**, moving the output of agents beyond static Excel and PowerPoint files into live, interactive financial work products that remain connected to underlying sources. A Site can connect to a CRM, financial model, data room, meeting notes and third-party data.

Its examples are particularly interesting for financial workflows: a fund pipeline connected directly to **Salesforce or DealCloud**, a sell-side process combining the CIM, model and data room with differentiated access rights, and interactive scenario modelling where a client can change assumptions live.

**Deployment:** productised and actively marketed; the announcement does not explicitly call it GA.  
**Outcome:** no quantified ROI disclosed.  
**Source quality:** primary — High.  
**Why HIGH:** This is a more ambitious move than AI-generated presentations. Model ML is attempting to own the persistent work product itself.

**Commercial implication — inference:** If deliverables become live and agent-maintained, the value of Moody’s increasingly comes from keeping those outputs continuously refreshed with traceable, entitlement-aware intelligence rather than simply supplying data to a terminal.

[Model ML Sites](https://modelml.com/articles/model-ml-at-work-sites?utm_source=chatgpt.com)

---

### FactSet — 22 Sep — **MEDIUM**

FactSet acquired German fintech **BCC Group International**, whose ONE Platform manages ingestion, entitlements and distribution of market data across public cloud, private cloud, hybrid and on-premise environments. FactSet is integrating it into its Real-Time Solution Suite.

FactSet explicitly positions the architecture as **open, API-first and source-neutral**, targeting vendor lock-in and centralising entitlements, compliance and cost controls. It also links the need for this infrastructure to AI-driven and increasingly automated workflows.

**Deployment:** acquisition completed/announced; integration underway.  
**Partner/acquisition:** BCC Group International.  
**Outcome:** terms undisclosed; FactSet says the transaction is not expected to materially affect its financial results.  
**Source quality:** FactSet primary announcement — High.  
**Why MEDIUM:** Less directly competitive with private-credit agents, but strategically important because FactSet is moving deeper into the governed infrastructure through which financial data is distributed.

**Commercial implication — inference:** The competitive battle is not only over datasets. FactSet increasingly wants to own **content + distribution + entitlements + infrastructure + AI workflow**. Moody’s therefore benefits from remaining highly interoperable rather than relying on closed delivery.

[FactSet / BCC announcement](https://investor.factset.com/news-releases/news-release-details/factset-marks-new-era-enterprise-real-time-market-data-it?utm_source=chatgpt.com)

---

### Secondary signal

Rogo’s **Big Finance Bench** was added on 22 September to Fireworks AI’s Specialized Intelligence Index. BFB evaluates models on valuation, financial-statement analysis, forecasting and other financial workflows; Rogo uses it to route tasks to different models based on quality and cost.

I did **not** elevate this to a core item because it lacks a new client deployment, product launch or commercial outcome, but it reinforces Rogo’s model-agnostic routing strategy.

After both search passes, I found no additional qualifying 18–24 September development for **S&P Global Market Intelligence / Capital IQ Pro, Bloomberg, MSCI, 9fin, Debtwire, BlackRock Aladdin, LSEG, AlphaSense, Credit Benchmark, Hebbia, Perplexity Finance, Anthropic financial services or OpenAI / ChatGPT financial services**.

I excluded Anthropic’s **$2bn Accenture AI-safety evaluation commitment** because it is significant frontier-model news but not a financial-services/data-workflow development. I also excluded the 24 September Bloomberg post-trade automation event because I could not establish a distinct new product-launch or client-deployment event from the available evidence.

### The three that matter most

1. **D&B:** proprietary credit intelligence is now distributed directly into virtually every major enterprise-agent environment.
2. **Rogo + Octus:** probably the clearest new competitive threat to private-credit research, underwriting and monitoring workflows.
3. **Model ML:** Daloopa + Sites together show the company trying to own both the inputs to the agent and the persistent output produced by it.

The broader pattern is:

**premium data → governed MCP/API access → agents → persistent source-linked work products.**

That increasingly makes the standalone terminal **one consumption channel rather than the strategic moat itself**.
