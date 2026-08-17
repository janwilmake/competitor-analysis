# Competitor Intelligence Wiki — Promptwatch.com

*Maintained by automated analysis. Last updated: 2026-08-17 (run 9).*

---

## What Is Promptwatch.com?

**[Promptwatch.com](https://promptwatch.com)** is an **AI Search Visibility / GEO platform** (also called AEO — Answer Engine Optimization; the company now brands itself "Agentic AI Search Optimization"). It helps brands and agencies track, understand, and improve how they appear inside AI-generated responses from ChatGPT, Gemini, Claude, Perplexity, Google AI Overviews, and related AI search engines — and increasingly to *act* on that data via autonomous content agents.

**Not** an LLM developer tool or model observability platform (not LangSmith/Langfuse) — it is squarely a *marketing/SEO* tool for brands wanting to appear in AI answers.

### Key Product Capabilities (as of August 2026)
- Prompt-level brand visibility tracking across **9+ AI platforms** (ChatGPT, Perplexity, Gemini, Claude, Google AI Overviews, Google AI Mode, Meta/Llama, DeepSeek, Grok)
- **AI crawler log analysis (Agent Analytics)** — which pages AI bots read and cite; Cloudflare + Fastly log ingestion; published AI crawler user-agent list. **⚠️ No longer unique as of Aug 2026 — Peec AI shipped Crawl Insights (server-log tracking, 8 integrations, 40+ bots) matching/exceeding this capability. See run 9 headline.**
- **Reddit citation tracking** — Reddit threads cited in AI responses about your brand (unique in category)
- **YouTube citation tracking** — which videos are cited and by which AI models (unique in category)
- **Unified Actions** (May–June 2026) — a kanban "AI-generated GEO to-do list" surfacing content gaps, untracked/untapped pages, Reddit social opportunities, setup gaps, and offsite mentions; **Sentiment Actions + Weekly AI Insights** (June 9); **Weekly Action Digest emails** (June 6). This is Promptwatch's execution-layer answer to Profound Aim/Projects and Peec Actions.
- **Content Agents** — articles optimized for AI citation (5–30/month depending on plan); git-diff style page-update suggestions from content gaps
- **Agentic AI Search Optimization** (announced July 14, 2026) — connect a website and Promptwatch's Agents continuously optimize AI visibility autonomously. Direct counter-positioning to Profound Aim.
- **Agent Chat** (August 2026) — "Your AI Search Analyst"; manage the entire AI Search workflow in one chat; ask about performance and act without leaving the conversation. Counter to geotoolbox "Ask GeoToolBox" and Profound's "Ask Profound" roadmap.
- **Ads Radar** (August 2026, new) — see who is advertising inside AI answers. Launched the same week Peec added its own Ads page (Aug 3) — a head-to-head feature race.
- **MCP server integration** (March 2026) — programmatic access to Promptwatch data from Cursor, Claude Desktop, ChatGPT. *Note: MCP is now table stakes — Peec, Otterly, LLM Pulse, and others also ship MCP servers as of mid-2026.*
- **Branded Knowledge Base** — ask Promptwatch anything and reference your docs inline
- Offsite citation tracking — which third-party sources drive AI recommendations of your brand
- Answer Gap analysis — prompts where competitors appear but you don't
- Google Search Console integration (per project) + Looker Studio
- Agency/white-label tier (custom pricing)
- Visitor analytics with AI traffic attribution
- AI Shopping tracking (ChatGPT product recommendations)
- Entity tracker, sentiment analysis, competitor benchmarking
- **4,520,200,000 (4.52B) citations, clicks, and prompts** in dataset (self-reported; cited by WSJ, Yahoo Finance, Axios, Seeking Alpha). ⚠️ **As of August 2026 the homepage counter now reads 26,520,890,000 (26.52B)** — a ~5.8x jump in ~one month that is not credible as organic growth and should be treated as a marketing claim / counter ratchet (likely a broadened "citations + clicks + prompts" definition). Methodology still unpublished.

### Company Snapshot
| | |
|---|---|
| **Founded / Launched** | 2025 (launched April 2025; raised pre-seed Sep 2025) |
| **HQ** | Amsterdam, Netherlands (New York office planned, announced July 2026) |
| **Founders** | Gijs de Groot (CEO), Klaas Foppen |
| **Funding** | **~€7.2M total** — €1.2M pre-seed (Arches Capital, Sep 2025) + **€6M seed (Jul 14, 2026, led by Seed + Speed Ventures; Blum Ventures + Arches Capital)** |
| **ARR** | €2M+ (April–May 2026, ~12 months after launch) |
| **Team** | ~15 employees (Tracxn, May 31, 2026) — expanding with the raise |
| **Customers** | **~1,840+ paying organizations** (per seed-round press); homepage body says "1,780+ brands and agencies"; homepage meta claims "7,000+ brands" *(the 7,000 figure is a broader marketing claim, not a verified paying-customer count)*. Adding 150+ new customers/month. |
| **Key Customers** | Duolingo, Fireflies, Monks, ABN AMRO, WPP, iO Digital, Booking.com, Center Parcs, Elaboratum, Wortell |
| **G2 Rating** | 4.7/5 |

### Pricing (August 2026 — unchanged since July)
| Plan | Price | Prompts | Websites | Articles/mo |
|---|---|---|---|---|
| Essential | $95/mo | 50 | 1 | 5 |
| Professional | $245/mo | 150 | 2 | 15 |
| Business | $579/mo | 350 | 5 | 30 |
| Agency/Enterprise | Custom | Custom | Custom | Custom |

*7-day free trial on Essential and Professional. Annual billing discount applies. Pricing also available in EUR. Essential dropped from $99→$95 earlier in 2026 (likely a competitive response to HubSpot AEO at $50 and Peec matching at $95).*

---

## Wiki Structure

```
README.md              — this file: what Promptwatch is + key findings
competitors/           — one file per established competitor
  profound.md          — market leader / unicorn ($155M raised, $1B valuation); launched Aim (always-on agent, Jul 2026)
  peec-ai.md           — ~$39M raised; $10M ARR; in talks at $200M valuation (Jun 2026); European #2 threat
  scrunch-ai.md        — narrative/sentiment + AXP infrastructure ($26M total)
  otterly-ai.md        — 30,000+ users; G2 Rookie of Year; European Search Awards 2026; bootstrapped; Austria
  evertune.md          — enterprise; Shopping Intelligence; $20M raised
  athenahq.md          — YC-backed; $295/mo; 4.9/5 G2; Google/DeepMind founders; Shopify revenue attribution
  brandlight.md        — Israeli enterprise; $36M raised; $4K–15K/mo
  llm-pulse.md         — bootstrapped European; white-label; MCP integration
  bluefish-ai.md       — enterprise; AI Brand Vault; ~$24M funded
  aiclicks.md          — Lithuanian; 10+ LLMs from entry; 4.9/5 G2
  vismore.md           — execution-layer AEO ($99–$399/mo); Reddit/Medium publishing
  orchly.md            — lowest-price AEO+SEO combined ($49/mo); 14-day trial
  gracker-ai.md        — B2B SaaS/cybersecurity specialist; vertical AEO
  hubspot-aeo.md       — ⚠️ $50/mo; 238,000+ customer base; launched Apr 14, 2026 (top-3 horizontal threat)
  ahrefs-brand-radar.md
  semrush-ai-toolkit.md — ✅ Adobe acquisition closed Apr 28, 2026 (now Adobe CX Enterprise)
  se-ranking-visible.md
new-entrants.md        — emerging tools not yet fully profiled (HeyAmos, Searchable, AirOps, Visiblie, etc.)
comparison.md          — master feature/pricing comparison table
changelog.md           — running log of all changes and key findings
```

---

## Summary of Key Findings (August 2026 — Run 9)

### 🔥 This Run's Headline: Peec Erased Promptwatch's Crawler-Log Moat (Aug 2026)
The single most strategically significant event this cycle is **not** a Promptwatch update — it's a competitor one. **Peec AI shipped Crawlability + Crawl Insights (Agent Analytics)**, a server-log AI-crawler tracking capability that directly and credibly removes the feature Promptwatch has most aggressively marketed as "uniquely differentiated." Peec's implementation is arguably *beyond* parity: 8 log-ingestion integrations (AWS CloudFront, Google Cloud CDN, Cloudflare Workers, Vercel Log Drains, WordPress, Akamai DataStream, webhook, CSV/CLF), 40+ AI bots / 20+ vendors, URL/folder-level breakdowns by bot/platform/type (Training/Search/User Query/Other), and — critically — it *joins* crawl data to prompt-tracking to answer "is this bot's interest translating into actual retrieval+citation?" Peec expanded the integration set again on Aug 3, signaling active investment. **Promptwatch's remaining unmatched differentiators now narrow to: Reddit citation tracking, YouTube citation tracking, content generation, and the (contested) dataset.** The "lean into the crawler-log moat" advice from prior runs is now half-closed.

### 🔴 Critical Threats

**1. Peec AI — Crawler-Log Moat Erased + $200M Valuation Talks — Now the Sharpest Direct Threat**
Peec ($10M ARR, ~$39M raised, ~85–93 employees, ~2,500 customers) is in talks for ~$10M at a $200M pre-money valuation (still open as of Aug). In August it shipped server-log crawler tracking (see headline), **Brand Perception** GA (association-scoring sentiment, competing with Promptwatch sentiment), and an **Ads page** (competing with Promptwatch's new Ads Radar — launched the same week). Peec now publishes direct comparison pages vs Ahrefs/Profound/Semrush and is hiring aggressively in Berlin + NYC. For the EU mid-market, Peec is the default comparison to Promptwatch — and it just closed the last feature gap that favored Promptwatch.

**2. Profound — Unicorn + Aim + Profound Index (benchmark product)**
Profound's $96M Series C / $1B valuation remains the defining capital event. **Profound Aim** (Jul 2, always-on autonomous marketer) is still unmatched. This run also surfaces the **Profound Index** (launched June 16/29, missed in run 8's news capture): a published industry-wide AI-Search leaderboard built on 1.5B real-user prompts across 50+ industries, weekly, six core metrics. This turns Profound's dataset into a *benchmark product* — a direct contest of Promptwatch's "real-prompt dataset" positioning. Profound's data is now cited as the category reference (MarketingDive, Aug 7). Combined with the Semrush integration (10M+ users), Profound is the benchmark Promptwatch must answer.

**3. Horizontal Platform Threat (Adobe/Semrush + Sitecore/Scrunch + HubSpot)**
- **Adobe/Semrush acquisition closed April 28, 2026** — Adobe CX Enterprise bundles SEO + GEO + ASO.
- **⚠️ Sitecore acquired Scrunch (~$225M, June 3, 2026)** — *propagated to the wiki this run* (was in scrunch-ai.md but missing from this summary). This is the **second** major DXP-bundles-AEO acquisition. Sitecore's enterprise base now gets Scrunch's AEO + AXP "insight→action" as a bundled capability. Scrunch clients include Lenovo, Skims, Headspace, Penn State. Enterprise CMS/DXP buyers face no new procurement to access AEO.
- **HubSpot AEO ($50/mo, launched April 14, 2026)** remains the most dangerous *entry-tier* bundling threat (238,000+ customers).

### 🟠 Growing Threats

**4. Incumbent log-analysis specialist moving in: JetOctopus**
JetOctopus — an established enterprise technical-SEO/log-analysis platform — is now actively pitching "AI Search Visibility" by combining **server logs + crawl + GSC + GA4** in one platform. This is a *different* threat to Promptwatch's crawler moat: an incumbent that already does server-log analysis at enterprise scale. If JetOctopus leans in, it competes with Promptwatch's Agent Analytics from a position of log-analysis depth most AEO startups lack.

**5. Budget/vertical entrants proliferating**
geotoolbox ($99/mo, leads with AI-crawler reachability, white-label, "Ask GeoToolBox" chat, Reddit/forum citations), CrawlPact (free vendor-neutral robots.txt/crawler-policy auditor), GeoVector, EchoWi (€29), Mentions.so ($49). echowi's Aug-verified catalogue counts 66 AI-visibility tools (53 buyable, 1 shut down); 32 of 42 priced tools sit under $100/mo. Pure monitoring is fully commoditized; the entry tier is under heavy price pressure.

### ✅ Promptwatch's Genuine Differentiators (as of August 2026 — honest, narrowed)

1. **Crawler log analysis (Agent Analytics)** — ⚠️ **no longer unique.** Peec now matches/exceeds it (Crawl Insights, Aug 2026). Promptwatch's edge is integration depth (Cloudflare/Fastly today) — *temporary* unless expanded to Vercel/AWS/GCP/etc. to match Peec's 8 methods.
2. **Reddit citation tracking** — still unique as a per-brand monitoring feature (Peec and others do not yet ship this).
3. **YouTube citation reports** — still unique in category.
4. **Real-prompt dataset** — claimed 26.52B (up from 4.52B in ~1 month — ⚠️ implausible jump; treat as marketing claim; methodology unpublished). A genuine moat *if* published and validated, but Profound's Profound Index (1.5B, published as a product) and Peec's research team are actively contesting this narrative. The dataset is now a *credibility risk* as much as an asset.
5. **Agency + white-label tier at scale** — true multi-client support at custom pricing.
6. **Execution layer** — Unified Actions + Content Agents + Agent Chat + Ads Radar + Agentic AI Search Optimization. Shipping fast, but no longer differentiated vs Profound Aim / Peec Actions.

*Honest caveat:* MCP, the crawler moat, and "chat analyst" features have all commoditized in 2026. The durable plays left are integration depth, agency workflows, EUR pricing, and Reddit/YouTube niche depth — all of which need active investment or erode within 6–12 months.

### 📊 Market Context (August 2026)

- **Digiday (Aug 13):** "CMOs are struggling to link AI visibility with sales" — the revenue-attribution gap remains unsolved; validates AthenaHQ's Shopify/GA4 moat and is a weakness for most players including Promptwatch.
- **MarketingDive (Aug 7):** Reddit/YouTube are the favored UGC sources for AI models; cites Profound data (ChatGPT→Reddit 2.4%, YouTube 0.99%). Validates Promptwatch's Reddit/YouTube focus *and* shows Profound already owns the reference-data narrative.
- **Gartner:** organic search traffic could fall 50%+ by 2028; the macro thesis underwriting the funding wave continues.
- **Category consolidation accelerating:** Adobe/Semrush (Apr 28), Sitecore/Scrunch (Jun 3), Promptwatch (€6M, Jul 14), Peec ($200M talks), Profound ($1B) — DXP/CMS giants are buying AEO; well-funded pure-plays are racing on data + agents.

### 🟢 Where Promptwatch Stands (Honest Assessment — Run 9)

Promptwatch is a capital-efficient, fast-shipping mid-market tool that just secured VC validation (€6M seed, Jul 14) and shipped Agent Chat + Ads Radar in August. But **this run Promptwatch's position is honestly weaker than run 8's**: the funding gap narrowed, but the *feature-uniqueness* gap narrowed *faster*. Peec took the crawler-log moat (Promptwatch's most-marketed unique feature) and Profound turned its dataset into a published benchmark product. Promptwatch is now defending on features competitors are actively replicating.

**The honest risks:**
1. **The crawler-log moat — the single most-recommended strategic asset in prior runs — is gone.** Peec matched/exceeded it in August.
2. **The dataset narrative is contested and now carries credibility risk** (26.52B claimed, 5.8x jump in a month, no methodology).
3. **Funding gap still large:** ~€7.2M vs Profound's $155M (≈20x) and Peec's ~$39M + $200M-valuation talks (≈5x+). They outspend on R&D, sales, data.
4. **US expansion (NYC office) is contested ground.** Profound (NYC HQ) and Peec (NYC office) are already entrenched.
5. **"Why not just use Adobe/Sitecore?"** is becoming the default enterprise procurement question.

**Promptwatch's best path (revised):**
1. **Re-anchor the moat** — crawler logs alone are no longer defensible; extend integration depth (Vercel/AWS/GCP/Cloudflare-Workers to match Peec's 8 methods) and *publish* the dataset methodology to convert the credibility risk back into a moat.
2. **Own the agency/mid-market segment** — defender on white-label, Reddit/YouTube tracking (still unique), EUR pricing for the EU mid-market.
3. **Win on integration depth, not feature uniqueness** — the differentiator is now "how many places can I ingest logs from / how many systems do I plug into," not "I have a feature others don't."
4. **Don't try to match Profound feature-for-feature** — fight where the big players won't or can't go (agency workflows, Reddit/YouTube signals, EUR pricing).
5. **Honest internal note:** stop marketing the crawler-log feature as "unique" and the 26.52B number as a verified dataset — both are now contestable and a sharp reviewer will call them out.

*Run 8 (July 18, 2026) findings are preserved in `changelog.md`. Prior-run headline: Promptwatch's €6M seed round (July 14, 2026) led by Seed + Speed Ventures.*
