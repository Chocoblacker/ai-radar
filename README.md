# 📡 AI 雷达（ai-radar）

每日 AI + 科技经济雷达，由 Muse 自动整理。

每天北京时间 05:00 自动生成一份中文日报，覆盖过去 24 小时（昨天 05:00 至今天 05:00）：

- **AI 主线**（约 65%）：模型与产品、Agent 与工具、AI 与工作、芯片与算力、资本与人事、政策监管
- **科技 · 经济 · 金融**（约 35%）：科技巨头、半导体产业链、央行与宏观、美股及港股/A 股科技板块、加密资产、能源与大宗商品
- **地缘与政策影响**：只收明确影响科技 / 供应链 / 市场 / AI 监管的动态

每条新闻至少 2 个独立来源交叉验证；新闻用自己的话概括，引用原文不超过一句，必附原链接，不转载全文。

日报是地基，在此之上持续沉淀故事线、概念卡和预判，目标是看懂事情怎么演变，并尽量提前判断接下来会发生什么。

## 最新 7 天

- [2026-11-01（周日）](daily/2026/11/2026-11-01.md) —— OpenAI 募资目标砍至约 200 亿美元、仅获约 110 亿承诺；特习釜山协议细则：稀土发通用许可；币安已补回约 80% 被盗资产
- [2026-10-31（周六）](daily/2026/10/2026-10-31.md) —— 纳指周五 -4%、英特尔 -29% 创 1974 年来最惨单日；12 月加息定价回落至约 70%；油轮遭水雷袭击、布油逼近 120
- [2026-10-30（周五）](daily/2026/10/2026-10-30.md) —— 科技巨头 Q3 迎"算账日"：Alphabet 再跌约 13%、亚马逊 AWS +39% 仍盘后大跌；9 月 PCE 3.6%、12 月加息定价约 85%；库珀上将赴白宫汇报对伊选项
- [2026-10-29（周四）](daily/2026/10/2026-10-29.md) —— 美联储按兵不动但 10-2 鹰派分裂；Alphabet 云翻倍仍因 EPS miss 盘后跌超 7%；Google 发布 Gemini 4 Carbon、GitHub Copilot Fusion 全面可用
- [2026-10-28（周三）](daily/2026/10/2026-10-28.md) —— Anthropic 拟募资至多 1000 亿美元、估值约 2 万亿美元；英伟达向 Meta 投 30 亿美元、Vera Rubin 扩至多吉瓦；DeepMind 发布世界模型 Genie 4
- [2026-10-27（周二）](daily/2026/10/2026-10-27.md) —— Anthropic 公开 S-1 冲刺上市；Meta 拟募资至多 950 亿美元、SpaceX 约 400 亿美元 GPU 租赁；巴西股汇债三杀、中国 AI 泡沫论
- [2026-10-26（周一）](daily/2026/10/2026-10-26.md) —— OpenAI 以 30%+ 折扣抢走 Replit 年超 1 亿美元合同；本周超级央行周，美联储 10 月 28 日议息；特朗普排除周日对伊动武、布伦特周涨近 7%

## 🔥 活跃故事线

- [Anthropic IPO 冲刺](threads/anthropic-ipo.md) — S-1 深挖：Q2 经营利润 9.74 亿美元转正、算力基建承诺约 7500 亿–9000 亿美元
- [AI 融资潮](threads/ai-funding-wave.md) — OpenAI 募资目标 300 亿→200 亿、DeepSeek 二轮约 27% 来自国资，一级市场也开始"算账"
- [美联储利率路径](threads/fed-rate-path.md) — Logan 称至少还需加息两次，12 月加息定价约 73%
- [中东局势与油价](threads/middle-east-oil.md) — 油轮再遭袭击，鲁比奥称特朗普尚未决定对伊动武、多哈谈判重启
- [存储/HBM 短缺](threads/memory-hbm-shortage.md) — SK 海力士利润率 79.7%，2027 年产能售罄；英特尔 18A 产能转向服务器
- [Agent 安全](threads/agent-security.md) — Chainalysis 遭 agentic AI 攻击；Anthropic 模型 53 分钟写出 Linux 内核远程利用
- [AI 出口管制](threads/ai-export-controls.md) — 釜山细则：稀土发通用许可、Nexperia 恢复供货、关税降至约 47%
- [AI 资本开支"算账"](threads/ai-capex-reckoning.md) — Alphabet 两日重挫、亚马逊 AWS +39% 仍被抛售，市场从增长故事转向现金流纪律

[完整故事线总览 →](threads/index.md)

## 目录结构

- `daily/YYYY/MM/YYYY-MM-DD.md` — 每日日报（地基）
- `threads/` — 故事线：跨越多天的事件追踪（[总览](threads/index.md)）
- `glossary/` — 概念卡：反复出现的专业概念解释（[索引](glossary/index.md)）
- `weekly/YYYY-Www.md` — 每周日发布的周报（本周 Top 10、故事线进展、预判复盘）
- `monthly/YYYY-MM.md` — 每月 1 日发布的月报（最重要的 5 条故事线、预判成绩单）
- `config/` — 规则配置：scope.md（日报结构）、knowledge.md（沉淀规则）、foresight.md（预判规则）
- `data/` — 结构化数据：history.json（近 14 天事件索引）、threads.json（故事线）、calls.json（预判）

