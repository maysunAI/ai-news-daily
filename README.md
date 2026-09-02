# AI News Daily

An auto-generated daily digest of what's happening in AI: model & product releases, open-source projects, research papers, company moves, policy & safety, opinion, and protocols / interoperability.

Every item carries a **primary-source link**, a short summary, an **original-language tag**, and a transparent **0–100 importance score** (rules are public — see [Scoring](#scoring) below). Summaries are written in Chinese first and machine-translated to English; both are kept.

- 🌐 Web version (today): https://ainews.maysuns.uk/digest.html
- 📅 Archive: one file per day in [`archive/`](archive/)
- 🤖 Collection: Anthropic Claude's native web-search tool, run automatically at 03:00 (UTC+9)
- 👤 By: https://maysuns.uk

> Fully auto-generated. It only compiles public news links and short summaries — it does not reproduce article bodies. The score reflects "importance to a reader who follows AI", not a rating of the outlet's credibility.

_（中文说明：每天自动整理 AI 领域的最新发展，每条附一手来源链接、摘要、原文语言标注和 0–100 透明评分。摘要先用中文写、再机器翻译成英文，两种语言都保留。网页版见 https://ainews.maysuns.uk/digest.html ，历史存档在 archive/ 目录。）_

---

## Latest (2026-09-02)

> Auto-compiled daily by [PJ09](https://ainews.maysuns.uk/) via web search + a custom score. Batch time 2026-09-03T03:00:00.000Z. 7 item(s). English is machine-translated from the Chinese summary; the original Chinese is in each item's collapsible block.

### ⭐ [Path to Astra: critical capabilities and frontier safeguards](https://openai.com/index/path-to-astra/)

`score 100` · Policy & safety · 🇬🇧 English · via OpenAI 官方博客

OpenAI announced on September 1 that its next-generation model, Astra, has reached the highest "Critical" cybersecurity capability level in the Preparedness Framework, making it the first model to be designated this level - meaning that when given the tools and permissions, it can discover and exploit unknown vulnerabilities in multiple high-protection real systems without step-by-step guidance. During the evaluation, Astra concatenated two zero-day vulnerabilities on a hardened browser/operating system, escaped the sandbox, and executed commands on the host machine. OpenAI has delayed some development and releases of Astra to install stronger protections against network abuse and model breaches.

<details><summary>中文摘要</summary>

OpenAI 于 9 月 1 日宣布，其下一代模型 Astra 已达到《准备度框架》(Preparedness Framework) 中最高的“关键”(Critical) 网络安全能力等级，是首个被定为该级别的模型——意味着在有工具和权限时，它可在无人逐步指导下发现并利用多个高防护真实系统的未知漏洞。评估中 Astra 曾在加固浏览器/操作系统上串联两个零日漏洞、逃出沙箱并在宿主机执行命令。OpenAI 已推迟 Astra 部分开发与发布，加装针对网络滥用和模型越权行为的更强防护。

</details>

---

### ⭐ [Anthropic's Claude Fable 5.1 and Mythos 5.1 arrive with a 75% cost reduction for Fable cache reads](https://venturebeat.com/technology/anthropics-claude-fable-5-1-and-mythos-5-1-arrive-with-a-75-cost-reduction-for-fable-cache-reads)

`score 85` · Model & product releases · 🇬🇧 English · via VentureBeat

Anthropic released Claude Fable 5.1 and Mythos 5.1 on September 1, calling it "the world's most advanced coding and knowledge working model"; the two are the same underlying model, but have different levels of security protection - Fable 5.1 is fully open and online through API, Claude.ai, Claude Code, Cowork AWS/Google Cloud/Azure, Mythos 5.1 Only for moderated trusted access projects such as cybersecurity defenders and life science researchers. Both models support 1 million token contexts and a single output limit of 128,000 tokens. The cache read price is reduced by 75% (from US$1 to US$0.25 per million tokens). Typical load costs are reduced by approximately 25%, and high-intelligence tasks are reduced by up to 45%.

<details><summary>中文摘要</summary>

Anthropic 于 9 月 1 日发布 Claude Fable 5.1 与 Mythos 5.1，称其为“全球最先进的编码与知识工作模型”；两者是同一底层模型、只是安全防护级别不同——Fable 5.1 通过 API、Claude.ai、Claude Code、Cowork 全面开放并上线 AWS/Google Cloud/Azure，Mythos 5.1 仅面向网络安全防御者和生命科学研究者等受审核的可信访问项目。两款模型均支持 100 万 token 上下文、单次输出上限 12.8 万 token，缓存读取价格下调 75%（每百万 token 从 1 美元降至 0.25 美元），典型负载成本约降 25%、高智能体化任务最高降 45%。

</details>

---

### ⭐ [Commission designates ChatGPT, Reddit, Roblox under Digital Services Act](https://digital-strategy.ec.europa.eu/en/news/commission-designates-chatgpt-reddit-roblox-under-digital-services-act)

`score 85` · Policy & safety · 🇬🇧 English · via European Commission（Shaping Europe's digital future）

On August 31, the European Commission recognized ChatGPT as a "very large online search engine" (VLOSE) under the Digital Services Act (DSA), and also recognized Reddit and Roblox as "very large online platforms" (VLOP). This is the first time an AI chatbot has received this classification because its hybrid service can retrieve network information and has about 159 million monthly users in the EU. The designated party must perform additional obligations such as assessing and mitigating systemic risks and algorithm accountability within four months (that is, before the end of 2026).

<details><summary>中文摘要</summary>

欧盟委员会于 8 月 31 日依据《数字服务法》(DSA) 将 ChatGPT 认定为“超大型在线搜索引擎”(VLOSE)，同时将 Reddit、Roblox 认定为“超大型在线平台”(VLOP)。这是首次有 AI 聊天机器人获此分类，因其混合服务可检索网络信息、且在欧盟月活约 1.59 亿。被认定方须在四个月内（即 2026 年底前）履行评估并缓解系统性风险、算法问责等额外义务。

</details>

---

### ⭐ [Anthropic Strikes $35 Billion Cloud Deal With Nvidia-Backed Lambda](https://www.bloomberg.com/news/articles/2026-08-31/anthropic-seals-35-billion-cloud-deal-with-nvidia-backed-lambda)

`score 60` · Company moves · 🇬🇧 English · via Bloomberg

Anthropic finalized a six-year, approximately US$35 billion cloud computing agreement on August 31 to rent computing power from Lambda, a cloud service provider invested in Nvidia, to expand the computing resources required for Claude products. The data center in question is located in Nueces County, Texas, and was built by Hut 8, which converted from Bitcoin mining, and Nvidia holds the lease for the data center. This order is another large computing power commitment made by Anthropic in the past week, following the US$45 billion agreement with Nscale. Its cumulative computing power contracts this year have reached at least US$135 billion.

<details><summary>中文摘要</summary>

Anthropic 于 8 月 31 日敲定一项为期六年、约 350 亿美元的云计算协议，向英伟达投资的云服务商 Lambda 租用算力以扩充 Claude 产品所需的计算资源。相关数据中心位于得克萨斯州 Nueces 县、由从比特币挖矿转型的 Hut 8 建设，英伟达持有该数据中心租约。此单是 Anthropic 近一周内继与 Nscale 的 450 亿美元协议之后的又一笔大额算力承诺，其今年累计算力合同已至少达 1350 亿美元。

</details>

---

### ⭐ [DeepSeek nears $7.4 billion funding round at $74 billion valuation ahead of 2027 IPO](https://techstartups.com/2026/08/28/deepseek-nears-7-4-billion-funding-round-at-74-billion-valuation-ahead-of-2027-ipo/)

`score 60` · Company moves · 🇬🇧 English · via Tech Startups

According to multiple media reports, Chinese AI company DeepSeek is close to completing a round of financing of about 50 billion yuan (about 7.4 billion U.S. dollars), with a pre-money valuation of about 74 billion U.S. dollars. It is preparing to be listed on the Shanghai Science and Technology Innovation Board. The IPO may be submitted as early as the end of 2026 and listed in 2027. Existing shareholders Monolith, Shixiang Capital, and CATL are participating in the investment, and CPE, Lenovo Venture Capital, and Hefei State-owned Assets Background Fund are in negotiations; the company disclosed that revenue in the first seven months of 2026 will be approximately 475 million yuan, approximately ten times that of 2025.

<details><summary>中文摘要</summary>

据多家媒体报道，中国 AI 公司深度求索 (DeepSeek) 正接近完成一轮约 500 亿元人民币（约 74 亿美元）的融资，投前估值约 740 亿美元，为在上海科创板上市做准备，IPO 最早可能于 2026 年底提交、2027 年挂牌。现有股东 Monolith、时象资本、宁德时代参投，CPE、联想创投及合肥国资背景基金等在洽谈中；公司披露 2026 年前七个月营收约 4.75 亿元人民币，约为 2025 全年的十倍。

</details>

---

### [Alibaba upgrades Qwen3.8-Max with a new 0902 snapshot](https://technode.com/2026/09/02/alibaba-upgrades-qwen38-max-with-new-0902-snapshot/)

`score 45` · Model & product releases · 🇬🇧 English · via TechNode

Alibaba launched Qwen3.8-Max-0902 on QwenCloud from September 1st to 2nd. It is an upgraded snapshot of the flagship model Qwen3.8-Max. It is post-trained for coding and Cowork-style agent tasks, retaining a 2.4 trillion parameter base, 1 million token context and thinking mode. Alibaba said its front-end CodeArena score rose to 1691 to reach the top, and TerminalBench 3.0 increased from 11.3 to 29.0; pricing remained unchanged (input $2 per million tokens, output $6).

<details><summary>中文摘要</summary>

阿里巴巴于 9 月 1—2 日在 QwenCloud 上线 Qwen3.8-Max-0902，是旗舰模型 Qwen3.8-Max 的升级快照，针对编码和 Cowork 式智能体任务做了后训练，保留 2.4 万亿参数底座、100 万 token 上下文与思考模式。阿里称其前端 CodeArena 得分升至 1691 登顶，TerminalBench 3.0 从 11.3 提升到 29.0；定价维持不变（输入每百万 token 2 美元、输出 6 美元）。

</details>

---

### [G20 live updates: OpenAI's Altman says the use of AI is 'non-negotiable'](https://www.cnbc.com/2026/09/02/g20-innovation-ministerial-live-updates.html)

`score 40` · Opinion & commentary · 🇬🇧 English · via CNBC

At the G20 Innovation Ministerial Meeting held in Chapel Hill, North Carolina, on September 1-2, OpenAI CEO Sam Altman told ministers that "the use of AI is unavoidable," saying that the economic growth and national value it brings are too high to be ignored, and predicted that this will bring "the largest boom in entrepreneurship and small and micro businesses in history." He also warned that cybersecurity is one of the biggest challenges in the AI ​​era and that "something is going to go seriously wrong" if all parties don't act urgently.

<details><summary>中文摘要</summary>

在 9 月 1—2 日于北卡罗来纳州教堂山举行的 G20 创新部长级会议上，OpenAI CEO 山姆·奥尔特曼对各国部长表示“使用 AI 已是不可回避的”，称其带来的经济增长与国家价值高到无法忽视，并预测这将带来“史上最大的创业与小微企业繁荣”。他同时警告网络安全是 AI 时代最大挑战之一，若各方不紧急行动“有些事会严重出错”。

</details>


---

## Scoring

Each item accumulates from 0:

1. **Source tier**: official primary source (AI company blog / announcement / paper) +40; major tech media (TechCrunch / The Verge / VentureBeat, etc.) +25; other (secondary reposts / forum threads) +10
2. **Category event weight**: a per-category cap, split into "major / normal" within a category (e.g. "model & product releases" major +45; "opinion & commentary" capped at +15)
3. **Keyword hits**: title or summary contains "released / open-source / funding / incident", etc. +15

Capped at 100 per item; **≥60 is flagged ⭐**. Full rationale (journalism's primary/secondary/tertiary source tiers + NewsGuard's 0–100/60 threshold + OpenSSF weighted-signal scoring) is below.

---

## Archive (last 30 days)

- [2026-09-02](archive/2026-09-02.md)

Full list in [`archive/`](archive/).

---

## Scoring

Each item accumulates from 0:

1. **Source tier**: official primary source (AI company blog / announcement / paper) +40; major tech media (TechCrunch / The Verge / VentureBeat, etc.) +25; other (secondary reposts / forum threads) +10
2. **Category event weight**: a per-category cap, split into "major / normal" within a category (e.g. "model & product releases" major +45; "opinion & commentary" capped at +15)
3. **Keyword hits**: title or summary contains "released / open-source / funding / incident", etc. +15

Capped at 100 per item; **≥60 is flagged ⭐**. Full rationale (journalism's primary/secondary/tertiary source tiers + NewsGuard's 0–100/60 threshold + OpenSSF weighted-signal scoring) is below.

### Why it's designed this way

- **Source tiers** = journalism's primary / secondary / tertiary source model.
- **0–100 + a 60 threshold** mirrors [NewsGuard](https://www.newsguardtech.com/ratings/rating-process-criteria/)'s rating shape (≥60 = meets the basic bar).
- **Summing weighted signals** = the standard approach of [OpenSSF Criticality Score](https://github.com/ossf/criticality_score) for open-source projects.
- The specific numbers are custom-tuned for "AI news importance" and have no direct industry standard.

---

_Maintained automatically by PJ09_ai_news_search. Spot an error? Open an issue._
