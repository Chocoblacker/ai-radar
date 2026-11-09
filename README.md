# 📡 AI 雷达（ai-radar）

每日 AI + 科技经济雷达，由 Muse 自动整理。

每天北京时间 05:00 自动生成一份中文日报，覆盖过去 24 小时（昨天 05:00 至今天 05:00）：

- **AI 主线**（约 65%）：模型与产品、Agent 与工具、AI 与工作、芯片与算力、资本与人事、政策监管
- **科技 · 经济 · 金融**（约 35%）：科技巨头、半导体产业链、央行与宏观、美股及港股/A 股科技板块、加密资产、能源与大宗商品
- **地缘与政策影响**：只收明确影响科技 / 供应链 / 市场 / AI 监管的动态

每条新闻至少 2 个独立来源交叉验证；新闻用自己的话概括，引用原文不超过一句，必附原链接，不转载全文。

日报是地基，在此之上持续沉淀故事线、概念卡和预判，目标是看懂事情怎么演变，并尽量提前判断接下来会发生什么。

## 最新 7 天

- [2026-11-10（周二）](daily/2026/11/2026-11-10.md) —— Anthropic 发布 Claude Fable 5.2（降价 20%）、Meta 推出 Muse Ember；美股周一大涨、英伟达逆势跌约 4.9%；中美稀土与 BIS 规则暂停双双延至 2027 年 1 月 10 日

- [2026-11-09（周一）](daily/2026/11/2026-11-09.md) —— 英伟达董事会启动独立调查黄仁勋遭 targeting；Claude Code 泄露 2,539 个密钥；比特币 ETF 单周净流出 12.8 亿美元

- [2026-11-08（周日）](daily/2026/11/2026-11-08.md) —— WorkOS 失控 Agent 真实得手、协作实验泄露 token；美股周五芯片领涨反弹、全周仍跌 3.4%；NYT 调查 H200 许可审查现漏洞
- [2026-11-07（周六）](daily/2026/11/2026-11-07.md) —— 非农新增 16.5 万远超预期、12 月加息定价升至约 77%–78%；亚洲股市暴跌、美股周五反弹；Kakao 与 Salesforce 同日推决策模型
- [2026-11-06（周五）](daily/2026/11/2026-11-06.md) —— 美股周四暴跌、纳指 -5.5% 进入技术性修正；OpenAI 发布 GPT-6 Cyber；英国央行加息 25bp 至 4%
- [2026-11-05（周四）](daily/2026/11/2026-11-05.md) —— 民主党横扫参众两院，美元大跌、美股油市一日重定价；对华算力管控同日两连击；Canva 因 AI 成本裁员 22%
- [2026-11-04（周三）](daily/2026/11/2026-11-04.md) —— Anthropic Q3 增速放缓、机构要求 IPO 估值压到 1.5–1.6 万亿美元；FT 独家：英伟达云合同设 51% 对华限制；苹果毛利率指引塌陷、AI 概念股遭抛售



## 🔥 活跃故事线

- [Anthropic IPO 冲刺](threads/anthropic-ipo.md) — Fable 5.2 发布、路演仍未启动，估值讨论降至 1.2–1.3 万亿美元
- [AI 融资潮](threads/ai-funding-wave.md) — Anthropic 被曝 34 亿美元接手 1.7GW 燃气发电机订单（待证实）；OpenAI 修订目标仍无新进展
- [美联储利率路径](threads/fed-rate-path.md) — 10 月 CPI 今晚公布（只公布环比、无同比）；12 月加息定价约 77%–80%
- [中东局势与油价](threads/middle-east-oil.md) — 特朗普称极不可能再打击伊朗，布伦特单日跌约 4% 至约 94 美元
- [存储/HBM 短缺](threads/memory-hbm-shortage.md) — 台积电否认应英伟达要求生产 3D DRAM；DDR5 大宗价连涨 9 个月达 2025 年底约 2 倍
- [Agent 安全](threads/agent-security.md) — GitGuardian 称密钥泄露历史全量达 31,088 个，另波及 Docker Hub
- [AI 出口管制](threads/ai-export-controls.md) — 中美稀土与 BIS 关联企业规则暂停双双延至 2027 年 1 月 10 日
- [AI 资本开支"算账"](threads/ai-capex-reckoning.md) — 美股周一大涨、英伟达逆势跌约 4.9%；11 月 17 日英伟达 Q3 财报在即
- [数据中心监管](threads/data-center-regulation.md) — 参议院辩论 BAAJA，要求数据中心承担更多电网升级成本；通过概率被下调至 25%

[完整故事线总览 →](threads/index.md)

## 目录结构

- `daily/YYYY/MM/YYYY-MM-DD.md` — 每日日报（地基）
- `threads/` — 故事线：跨越多天的事件追踪（[总览](threads/index.md)）
- `glossary/` — 概念卡：反复出现的专业概念解释（[索引](glossary/index.md)）
- `weekly/YYYY-Www.md` — 每周日发布的周报（本周 Top 10、故事线进展、预判复盘）
- `monthly/YYYY-MM.md` — 每月 1 日发布的月报（最重要的 5 条故事线、预判成绩单）
- `config/` — 规则配置：scope.md（日报结构）、knowledge.md（沉淀规则）、foresight.md（预判规则）
- `data/` — 结构化数据：history.json（近 14 天事件索引）、threads.json（故事线）、calls.json（预判）

