# 更新日志 / Changelog

*Offensive AI Agentic Landscape*
仓库地址 / Repository: [Yeti-791/Awesome-Offensive-AI-Agentic-Landscape](https://github.com/Yeti-791/Awesome-Offensive-AI-Agentic-Landscape)

> 本日志基于对每次 commit 实际 diff 内容的逐一读取与分析整理而成（非提交信息原文翻译），按周（周一至周日）组织，最新一周置于最前；未关联 commit 的本地文档修订轮次以日期 + 时间标注。
> *This changelog is compiled by reading and analyzing the actual diff content of each commit (not a literal translation of commit messages), organized by week (Monday–Sunday), most recent week first; local document-revision rounds without an associated commit are marked by date + time.*

---

## 2026-11-23 ~ 11-29

### 2026-11-25（第六轮）— 新增「D. 蜜罐与欺骗防御（防御侧）」论文小节（129 → 139）

本条为本地文档修订记录，依据实际文件修改与更新前后表格行数整理，**不是新增 Git commit**。**未运行任何代码或安装命令**，仅只读检索与抓取 arXiv 摘要页、DOI 落地页与 USENIX 论文页。

**背景与意图**：此前论文表只覆盖进攻侧，未考虑针对 LLM 攻击者的防御措施。本轮检索蜜罐、欺骗防御相关关键词，新增独立「D. 蜜罐与欺骗防御（防御侧）」小节，让做进攻 AI 的人也能对照了解对手的防御手段；并确认文档虽已有 6 篇进攻侧综述，但缺蜜罐/欺骗防御方向的综述，一并补上 `SoK: Honeypots & LLMs`。

**新增 D 段 10 篇（论文 129 → 139，A 70 / B 20 / C 39 / D 10；覆盖范围 → 2026-11）**：
1. Adaptive LLM-Driven Honeypots vs. LLM-Driven Attackers（arXiv:2611.22589，v1 2026-11-17）
2. A Gingerbread House for LLM Agents（arXiv:2611.07611，v1 2026-11-05）
3. Make the Adversary Spend More Energy: Generative Deception（arXiv:2610.27739，v1 2026-10-20）
4. AgentSnare（arXiv:2607.26998，v1 2026-07-29 / v5 11-01）
5. Honeyquest for LLMs（arXiv:2606.21037，v1 2026-06-19 / v3 10-23）
6. AIWAF（DOI 10.20172/j.issn.2097-3136.260922，中文期刊，DOI 注册 2026-11，仅确认到年）
7. SoK: Honeypots & LLMs（arXiv:2510.25939，v1 2025-10-29 / v4 2026-04-07，综述）
8. Cloak, Honey, Trap（USENIX Security 2025，BGU）
9. Perry（arXiv:2506.20770，v1 2025-06-25 / v2 09-25）
10. Hacking Back the AI-Hacker（arXiv:2410.20911，v1 2024-10-28，Mantis，附代码）

**重新审查纳入**：上一轮（第五轮）按「排除防御治理」口径排除的 `SoK Honeypots & LLMs`、`AIWAF`、`AgentSnare`、`Perry`、`Hacking Back the AI-Hacker` 五篇，本轮按用户要求重新审查后**转入 D 段**；仍排除 `Ethics Statements`（伦理治理）、Poster 合规审计，以及属「AI 系统自身安全 / 能力综述」的 RedTeamCUA、Cyber-Capable AI Agents、Rethinking PT for AI-Enabled Systems、A Survey on Agentic Security。

**核验**：10 篇均回查 arXiv 摘要页 / DOI / USENIX 页面取得标题、作者、日期与渠道；AIWAF 为中文期刊，日期仅确认到年（DOI 注册 2026-11），未补造月份；Cloak/Honey/Trap 与 AIWAF 无 arXiv，分别以 USENIX 页面与 DOI 为准。

**同步项**：顶部统计条论文数 129 → 139；统计概览「论文 / Papers」139 篇（A 70 / B 20 / C 39 / D 10）、覆盖范围 2023-06 → 2026-11；论文表英文分段说明更新为 139；论文表脚注追加本轮来源、转入 D 段的五篇与仍排除清单。D 段编号 D1–D10 连续、每行 7 竖线、日期降序。

## 2026-11-16 ~ 11-22

### 2026-11-18（第五轮）— 按 LLM4Pentest 清单去重补录 7 篇论文（122 → 129）

本条为同日第五轮的**本地文档修订**记录，依据实际文件修改与更新前后表格行数整理，**不是新增 Git commit**。**未运行任何代码或安装命令**，仅只读抓取仓库 README、arXiv 摘要页、ACM/Springer DOI 落地页与 NDSS 录用名单。

**来源**：[simon-p-j-r/LLM4Pentest](https://github.com/simon-p-j-r/LLM4Pentest) README 最新清单，现收录 **123 篇**（SYSTEM & AGENT 55 / BENCHMARK & RANGE 23 / EMPIRICAL & HUMAN FACTORS 23 / SURVEY 13 / DEFENSE & GOVERNANCE 9）。文档此前已于 2026-09-11 按该清单逐篇核对过一轮，故本轮**实际新增仅 7 篇**，而非按清单总量整批补入。

**新增（论文 122 → 129，A 64 → 70、B 20 不变、C 38 → 39）**：
1. CyberEvolver（arXiv:2605.26195，v1 2026-05-25 / v2 06-16，Yihe Fan 等）→ 2026-05
2. MazeRunner（arXiv:2608.14216，v1 2026-08-14，Zhenyuan Li 等）→ 2026-08
3. On the Adversarial Planning Capabilities of LLMs（ARES 2026 Workshops，DOI 10.1007/978-3-032-35579-9_4，08-24 出版）→ 2026-08
4. Context Relay for Long-Running Penetration-Testing Agents（NDSS Workshop LAST-X 2026 录用名单，KTH / FOI）→ 2026-02
5. Perses: Unlocking Privilege Escalation for Small LLMs via Extensible Heterogeneity（AsiaCCS 2025，DOI 10.1145/3708821.3736189，pp. 344-357）→ 2025-08
6. Using Large Language Models for Cybersecurity CTF Challenges and Certification Questions（arXiv:2308.10443，v1 2023-08-21）→ 2023-08
7. Large Language Models for Cyber Security: A Systematic Literature Review（TOSEM 2025，DOI 10.1145/3769676，accepted 09-22）→ 2025-09，归 C 段

**核验与判定**：
- 七篇均回查原文取得标题、作者、日期与渠道，**未采信清单的年份与分类标注**；README 中 `AWE` 等条目在文档中已有（A16/A33 等），**未重复新增**。
- 易误判项已逐条排除：AutoPT（A54，`2411.01236`）、Getting pwn'd by AI（A70，`2308.00121`）、cochise（A46）、IEEE Access ARM（A22，原为 A22 现编号未变）均已在表内。
- Context Relay 条目注明其配套框架为 `marvang/ctf-agent`，**与 Agent 表 `verialabs/ctf-agent` 不是同一仓库**；论文 PDF 直链未取得，链接指向 NDSS 录用名单页。
- 日期仅能确认到月的按「年-月」记录；未出现仅有年份且强行补月的情况。

**排除项（不收录，理由已写入论文表脚注）**：
- AI 系统自身安全 / 防御治理：RedTeamCUA（2505.21936）、Cyber-Capable AI Agents（2607.25379）、Rethinking PT for AI-Enabled Systems（2607.14006）、A Survey on Agentic Security（2510.06445）、SoK Honeypots（2510.25939）、AIWAF、AgentSnare、Ethics Statements、Perry、Hacking Back。
- 非同行评议 / 学位论文：两篇孟加拉国高校机构库论文、Research Square 预印本（PentestMCP 已在 A31）。
- 非进攻主线：CTF 新手学习研究（2602.18172）、CTF 环境配置综述（JNCA）。

**Benchmark 表**：BountyBench 条目补入 `arXiv:2505.15216` 链接（已核验为该论文本身，v1 2025-05-21），**不新增行、Stars 与计数不变**，Benchmark 仍为 15 个。

**同步项**：顶部统计条论文数 122 → 129；统计概览「论文 / Papers」改为 129 篇（A 70 / B 20 / C 39）；A 段与 C 段**整段重编号**（1..70 / 1..39，校验连续无重复、每行 7 竖线）；论文表脚注新增本轮来源、去重结论与排除项说明。

### 2026-11-18（第四轮）— 商业章节调整为国内优先：新增腾讯云「无境」、微步在线置首

本条为同日第四轮的**本地文档修订**记录，依据实际文件修改整理，**不是新增 Git commit**；工作区无可用 Git 仓库，未提交、未复核远端历史。**未运行任何代码或安装命令**，仅只读检索腾讯云/腾讯安全的公开发布信息。

**结构顺序**：
- 「🇨🇳 国内厂商」整节（标题、英文副标题、5 列表格）前移至「🌍 国外厂商 Top 20」之前；国外节的说明段与两段替换脚注随节移动，未拆分、未改写。
- 「🎯 选型对照」仍保留在两个厂商小节之后，表头与每行内容左右对调为「场景 / Scenario | 国内候选 / 状态 | 国外候选」，列名与内容逐行核对无错位。
- 国内表末尾的两个连续空行合并为单空行。

**厂商变更（商业 31 → 32，国内 11 → 12）**：
- 新增 **腾讯云「无境」**，列国内表第 2 位。依据公开信息：2026-09-04 发布，AI 自主渗透测试产品，以「自主发现、自主利用、自主验证、输出证据」为核心，面向上线前检测、常态化持续渗透、攻防演练前置、业务逻辑漏洞专项四类场景；SaaS 交付、零部署零运维，按授权目标与资产范围发起，面向企业开放试用。**未取得独立产品页与公开价格**，已在条目中注明；厂商宣传的「43 分钟」「平均 9 个漏洞」「百元级成本」等量化口径**未写入表格**。来源为腾讯云开发者社区转载的腾讯安全发布介绍，非第三方评测。
- **微步在线**由第 11 位调整至第 1 位，其余 10 家顺延为第 3–12 位，条目文案、链接与「新补充」标记逐字保留（含「Artex Pro 不是原 ARTEX 开源版」「2026-11-06 官方声明确认原版 10-08 闭源」）。
- 未删除任何既有厂商；国外 20 家编号与内容未改动。

**同步项**：
- 顶部统计条第 9 行末格 31 → 32；第 10 行末格文案「国外精选 20 + 国内 11」→「国内 12 + 国外精选 20」。
- 统计概览「商业产品 / Commercial」31 → 32，括号改为「国内 12 + 海外精选 20」，并保留海外表此前替换 2 条的说明。
- 国内表新增一段脚注，说明本次扩充为 12 家、无境的证据边界与未采用的自述指标。

### 2026-11-18（第三轮）— 依据 45 个 AI 渗透工具盘点 PDF 扩充主表 10 个项目（50 → 60）

本条为同日第三轮的**本地文档修订**记录，依据实际文件修改与更新前后表格行数整理，**不是新增 Git commit**；工作区无可用 Git 仓库，未提交、未复核远端历史。**未运行任何被收录仓库的代码、脚本、安装命令**，仅只读抓取 GitHub 仓库页面；PDF 文本通过 macOS 内置 PDFKit 只读提取，未安装任何工具。

**来源**：`/Users/emileli/Desktop/45个渗透Agent概览.pdf`，元数据为《Beyond ARTEX: 45 AI Pentesting Tools and How to Find Them》，作者署名 `nasa`，生成时间 2026-11-10（Producer: `Microsoft: Print To PDF`）。该文件为**个人审计盘点与自查报告，不是独立评测机构发布**，已在主表核验说明中具名标注。

**采用与不采用**：
- 仅采用其**项目名单与仓库地址**作为候选来源。PDF 文本层多列并排导致 `TOOL` 与 `STARS` 交错，且 `Armur-Ai`、`SanMuzZzZz`、`my/Incalmo` 等存在跨行断字，故任何数值均未采信，全部改为逐项访问仓库页取当次值。
- **未采用** PDF 的 `SECRET-HUNTING CLASS`、`EXPOSURE CLASS`、Shodan 查询与匹配数等审计结论。
- **未采用** PDF 的 Stars / LAST PUSH 快照（2026-11-07 前后）。例如 PDF 记 Strix 74.2k、Shannon 51.4k、PentAGI 33.6k，而文档现值为 76.4k / 52.0k / 34.5k，**不以其覆盖当前值**。
- PDF 第 1–3 页为图片页，文本层为空，封面与方法论未能核对，作者与标题仅取自文档元数据。

**新增 10 项（均 ≥ 90 Stars 且此前未收录）**：`gadievron/raptor`（4.0k，缩写）、`pikpikcu/airecon`（1.1k，缩写）、`s0ld13rr/pentestcode`（1.1k，缩写）、`Zyrexnn/Cybermes`（1.0k，缩写）、`cdxiaodong/cain-agent`（953）、`chainreactors/cyber-harness`（423）、`martian56/redcell`（414）、`chu0119/Pojun`（367）、`pensarai/apex`（327）、`Coff0xc/AutoRedTeam-Orchestrator`（270）。主表由 50 → **60**，已整表重编号 1..60 并复查 Stars 单调不增、每行竖线数一致（10 处缩写标注）。
- 关于 `Pojun`：其 README 自述为原百度 `Agent+` 冠军项目 ARTEX 的**独立演进分支**，文档按此表述记录，不认定其为 ARTEX 本体，也不改变 ARTEX 于 2026-10-08 起闭源的既有记载。
- 关于 `cyber-harness`：`harness` 指编排外壳，简介中已注明不等同完整自主渗透产品。

**未收录及原因（已写入主表核验说明）**：
- 低于 90 Stars：`r74tech/virga`（10）、`F0ran9/forang`（15）、`TiaMEOWS/mergen`（3，且为 CyberStrike 的 fork）。
- Stars 未能取得：`cskwork/scopeweaver`、`MythicAgents/sage` 的仓库页未渲染 Star 计数，第三方镜像口径相差过大（约 0.6k–1.1k），无法与门槛比对，本轮不收录。
- 仓库未定位：`echidna`（Mythic agent 类型）、`ycode`，**不填零、不臆测**。
- 已收录不重复：Strix、Shannon、PentAGI、PentestGPT、HexStrike、CAI、Cairn、T3MP3ST、Decepticon、sapper-v2、xalgorix、PentesterFlow、LuaN1aoAgent、Pentest-Swarm-AI、deadend-cli、Incalmo、redamon、nebula 等。

**同步项**：顶部统计条 Agent 50 → 60；统计概览「Agent / 关联项目主表」50 → 60、合计 57 → 67；主表核验说明新增 PDF 来源段与三份排除名单；文末证据限制段补充本轮缩写 Stars 与来源边界。

### 2026-11-18（补充轮次）— 延迟研究结果落地：Mistral Large 4、KaliBench、逆向 MCP 与 2 个 Skills

本条为同日第二轮的**本地文档修订**记录，依据实际文件修改与更新前后表格行数整理，**不是新增 Git commit**；工作区无可用 Git 仓库，未提交、未复核远端历史。**未运行任何被收录仓库的代码、脚本、安装命令或模型推理**，仅只读抓取官方页面、RSS、GitHub 页面与 arXiv 摘要页。

**模型（11 → 12）**：
- 新增 **RedSage 家族**（B 类第 7 条），按家族合并计 1 条：`RedSage-Qwen3-8B-CFW → -Base → -Ins / -DPO`，另有基于 KaliBench 训练的 `RedSage-K-SFT` / `K-GRPO`。8B、Qwen3-8B-Base 基座，论文《RedSage: A Cybersecurity Generalist LLM》标注 ICLR 2026。**三个模型卡均未见许可标签**，故不写作"已明确开源许可"。K-SFT 在 KaliBench 5,000 测试集自报 Total 77.4（unrestricted 65.9 / restricted 73.2 / hinted 93.2），为单基准、作者自报。
- 新增**关联说明**（不计入模型数）：Mistral Large 4 (Le Chonk)，约 1T 总参数 / 49B 激活 per token（含嵌入与输出层 52B）、128 routed experts（4 active）+ 1 shared。权重发布 **2026-10-29**（取自官方 RSS `pubDate`；公告正文与 `/news` 索引页均无日期字段，仅有 "earlier this month / today" 相对表述），公开预览为 2026-10-06。许可为 **Mistral Ecosystem Open-Weight License**（modified MIT，提供 MaaS 需另签商业许可），**不是 Apache-2.0**。
- **修正一处不成立的断言**：原研究材料中的 **"Cybench 93%"** 在官方公告页与 HF 模型卡 `mistralai/Mistral-Large-4-1T-A52B` 中**均未出现**，未予采用。官方实际给出的是 **Artificial Analysis Cyber Index 51%**，原文口径为发现代码库漏洞、复现并验证、再打补丁（**防御向**），不能表述为进攻渗透能力；该 51% 仅见于新闻页，模型卡只列 Intelligence Index v5 = 26 与 Coding Agent Index 48%，两页指标不可混用。

**Skills（4 → 6）**：
- 新增 `SnailSploit/Claude-Red`（Stars 页面显示 `11.2k`，缩写）与 `yaklang/hack-skills`（`2.7k`，缩写），均 MIT、均 ≥ 100 Stars。判定为**纯 Skill 形态**：前者的 `install.sh` 与索引脚本、后者的 1 主入口 + 6 类别入口路由，都属技能包自身组织方式，**不构成子代理编排**；`hack-skills` 为 Yaklang 生态独立仓，非 `yaklang/yaklang` 本体。因未取得精确整数，Stars 以 `≈` 标注，排序按显示值近似。

**MCP（7 → 10）**：
- 新增 3 个**逆向工程 MCP**：`mrexodia/ida-pro-mcp`（≈13.5k，MIT）、`bethington/ghidra-mcp`（≈6.3k，Apache-2.0）、`HexRaysSA/ida-mcp`（≈1.6k，MIT，README 原文 "Official Hex-Rays IDA MCP Server"）。区分**弃用范围**：`ida-pro-mcp` 仅 GUI 插件"不再推荐并计划弃用"、改推同仓 `idalib-mcp`，项目整体未弃用、未归档；桥接许可**只覆盖桥接代码**，不代表 IDA Pro 本体免费或获授权，Ghidra 侧亦需 12.2 + Java 25 服务端。README 中 219 工具、批处理降 93% 调用量等为作者自报。

**论文与 Benchmark（121 → 122；14 → 15）**：
- 新增 **KaliBench**（论文 C2；Benchmark #15）：arXiv:2610.02206 v1 **2026-10-01**，**NeurIPS 2026 Evaluations & Datasets Track**（arXiv Comments 原文），作者 Pengfei Li 等（Khalifa University / UWA）。8,504 对 NL→CLI query–command、1,642 工具、23 维度、5 安全阶段，训练 3,504 / 测试 5,000。
- **明确评测粒度**：评的是**单条命令的工具选择与参数构造**（exact-command、alias 感知、确定性规范化），**不是端到端渗透完成率**；三设置 unrestricted / restricted / hinted，论文结论为开源权重在 unrestricted 下 exact-command 未超 42%。已在 Benchmark 表、选型小贴士与统计中标注不可与端到端基准横向比较。
- 论文表 C2–C37 **顺移为 C3–C38** 后插入 C2，编号连续（C1–C38 已校验无重复、无缺号），历史条目内容未改。此前怀疑的"arXiv 编号异常"经摘要页核实**可排除**：2610 对应 2026-10，与 NeurIPS 2026 标注并存无矛盾。
- **许可区分**：仓库实际公开（含 `KaliBench_data/`、`Scoring/`、`src/`、`demo/`、`docker/`），但**无 LICENSE / COPYING，About 侧栏无 License 条目**；arXiv 页面的 **CC BY 4.0 仅覆盖论文文本**，不覆盖代码与数据。Stars **6**（精确值）、Forks 1、未归档；Languages 栏为空，未取得语言占比。CyberArena 的"网站仓库 ≠ Octagon 引擎、未取得引擎地址"修正为上一轮成果，本轮复核后保留不动。

**商业（31 条，海外仍 20）**：
- 海外表**替换 2 条**：新增 **Veria Labs**（verialabs.com，自主渗透 Agent，YC F25，无公开价格，仅 demo/contact）与 **Dreadnode**（dreadnode.io，自托管为主，Web 渗透 83 个技术 playbook、网络发现与 AD 评估；**其 AI Red Teaming 面向 AI 系统自身，不属主线**，只按 Web / 网络模块计入）。移出 **Theori（Xint）** 与 **Cohere Cyber（原 AISLE）**，理由为产品主体为代码审计与专家咨询，相关度低于新增项；**移出仅表示退出本表精选，不等于该厂商没有商业服务**，链接保留可追溯。
- **Parameter（hex.co）复核**：域名仍为 hex.co，全站品牌与邮箱已为 Parameter，页脚版权 © 2026 Anytool, Inc.，页面**未见更名或收购声明原文**，故只记录现状、不推断 Hex → Parameter 关系；价格锚点在 `/pentesting#pricing`，未取得公开金额。

**资源汇编（10 → 11）**：
- 新增 `skyvanguard/awesome-ai-pentesting`（**119**，精确值，MIT）：主体为自主渗透 Agent / 安全 MCP / 侦察 / CTF / 漏洞分析，但另含 AI 系统自身安全与 LLM 红队大类，按主线只取渗透相关部分，仅作辅助来源。

**一致性与未完成项**：
- 顶部统计条、概述、各章小节说明、选型小贴士与统计概览已同步：50 / 12 / 6 / 10 / 3 / 122 / 15 / 11 / 31，并逐表核对行数与编号（Skills 6、MCP 10、Papers 38、Benchmark 15、Awesome 11、海外商业 20、国内 11、主表 50）。
- 未完成：Synack / Astra 的专属价格页未取得金额；HackerOne / Cobalt 产品入口仅确认演示与销售路径；GitHub REST API 触发未认证限流，精确 Stars 未能补齐；部分条目（Titus 本体卡、`hack-skills` 加密 ZIP 包完整性、Dreadnode 客户与融资数据）未核实。

### 2026-11-18 — 按章节更新资源、赛事、Stars 与商业服务证据

本条依据本轮实际文件修改与更新前后表格行数整理，**不是新增 Git commit 记录**；工作区没有可用 Git 仓库，本轮没有提交或复核远端最新历史。资料重点覆盖上次采集后变化，并补漏重要研究。未运行项目代码、模型、扫描或论文实验。

**Agent 与 Stars**：
- 查询更新前文档中 98 个不同 GitHub 仓库页面，并核验新增候选；采用当次页面精确计数，先按整数排序，再格式化为一位小数 `k`。查询失败不填零或沿用旧值冒充最新数据。
- 主表新增 `BitterSecurity/Decepticon`（6,634）、`N1nEmAn/sapper-v2`（2,329）、`JoasASantos/NeuroSploit`（1,508）、`Stanford-Trinity/ARTEMIS`（552）、`BugTraceAI/BugTraceAI`（389）、`kpolley/redai`（356）。
- 移出偏 AI 系统自身安全的 `agentic-radar`，旧 `yz9yt/BugTrace-AI` 不再列于主表；当前 BugTraceAI 套件是新条目，不将两个仓库认定为直接改名或合并 Stars。**46 → 50**。
- 刷新并重排：Strix **76,355**、Shannon **51,975**、PentAGI **34,546**、PentestGPT **16,476**、HexStrike **13,712**、Cairn **5,348** 等；保留归档状态，删除没有独立证据的能力保证。
- 原 `Ed1s0nZ/CyberStrikeAI` 重定向至 `AIPentest/CyberStrikeAI`；原 `xalgord/xalgorix` 重定向至 `xalgorix/xalgorix`，链接同步更正。

**重点作品与赛事**：
- **ARTEX / Artex**：收录百度安全 `Agent+` 综合总冠军作品；区分百度发起与腾讯 Yunding Lab 独家技术战略合作角色。[微步官方版权声明](https://threatbook.cn/threatbookNews/fcd1bd02-0d7e-4736-abfd-22fdbce6f4c1)确认 2026-10-08 闭源；原仓库本次不可读取。保留历史来源，商业版 **Artex Pro / RedAgents** 单独进入国内表，不以非官方 fork 替代原项目。
- **sapper-v2 / 女娲**：收录作者仓库和架构；第三届腾讯云线上赛第一、80.18 分等是作者声明，本次没有取得其官方授奖公示，**不写作线下总冠军**。
- 腾讯云赛事扩充至第三届：收官报道记录主赛道线下冠军 **alkaerr**、安全智子专项一等奖金银湖队；补充 **634 支初赛战队**、AI-KOH 同场攻防及本地模型离线赛。微信公告正文验证受限的内容单独标注。
- 七个 AIxCC CRS 刷新 Stars；前三名之外改标“决赛入围”，不把列表顺序冒充正式名次。赛事系列 **2 → 3**，新增百度 `Agent+` 子节。

**模型**：
- 新增 [Altar-1](https://huggingface.co/AikidoSec/altar-1)、[Feyospace-v1-small](https://huggingface.co/feyospace/feyospace-v1-small)；移出主线之外的 `Meta-SecAlign` 与缺少安全任务评测的通用推理实验 `Qwythos`，保留出处及移出说明。总数仍 **11**，分类由 **6 + 5 → 5 + 6**。
- 修正 BaronLLM v2 参数/Trendyol 作者归属、VulnLLM-R 原模型卡、CyberSecQwen 原模型卡；Titus 区分原权重与当前可读量化仓库。
- CyberStrike-OffSec 当前模型卡为小规模工具行为 LoRA SFT，不再沿用 SFT+DPO、无对齐、超越 GPT-4 等旧断言；模型许可证缺失、作者自报、小样本评测和量化变体分别说明。

**Skills、MCP 与资源汇编**：
- Skills 新增 `Arenbai/SecSkills`（266），为技能包而非自主 Agent 框架；作者声明停更但仓库未归档，标为历史方法论资源。**3 → 4**；现有三个技能库刷新 Stars、作者和许可描述，删除“全球最大/唯一”宣传。Agent/Subagent 混合候选不因热度破例加入。
- MCP 补入主表交叉资源 `hexstrike-ai` 和 `w0h1v/mcp-virustotal`（155）；后者为独立情报工具桥接。`PortSwigger/mcp-server` 当前 **12** Stars，低于门槛移出；`FuzzingLabs/mcp-security-hub` 当前 404，官方仍引用旧地址但未核实迁移，暂移出。总数仍 **7**，保持 Stars ≥ 100。
- `pentest-mcp` 当前 README 的 AGPL-3.0、stdio/HTTP 与 SSE 禁用状态同步修正；工具白名单/范围检查不当作生产安全认证。
- Awesome Lists 新增此前已引用为论文来源的 `tmylla/Awesome-LLM4Cybersecurity`，**9 → 10**，重排精确 Stars。`ox01024/awesome-offensive-security-ai` 当前可读、29 Stars，纠正历史“404即作者删除”断言，暂不回到精选表。

**论文与 Benchmark**：
- 新增 5 篇，均核对 arXiv 原始标题、首作与 v1 日期：`Big Enough to Break Out`（2609.10780）、`Staying on the Attack Path`（2609.07344）、`CyberArena`（2610.19005）、`Toward Secure AI-Powered Penetration Testing Agents`（2609.16694）、`Feyospace-v1`（2609.08418）。
- 论文 **116 → 121**，A **62 → 64**、B **20 → 20**、C **34 → 37**；组内保留首次日期顺序并连续重编号。本轮未重审全部存量论文。
- 修订 PentestEval 的 2026-11-02 v2 与演示仓库状态、ARTEMIS 的修订日期及未核实录用断言，不把演示代码视作完整实验复现。
- Benchmark 新增 **PentestEval** 与 **CyberArena**、移出模型安全为主的 **CyberSecEval**，**13 → 14**；刷新已有 Stars 并补齐缺失数据。TSecBench 是托管入口、PentestEval 是公开演示、CyberArena 链接仓库是网站源码，未取得其 Octagon 引擎地址；三者不冒充已复现完整开源基准。

**商业服务与统计**：
- 海外仍精选 **20** 项，逐项回查官方产品、演示/采购与可读定价页；补入 Synack、HackerOne、Cobalt、Novee、Astra、Cohere Cyber（原 AISLE）、Penligent，撤下主线不匹配或未核实独立采购服务的七项。`hex.co` 当前品牌为 Parameter，未沿用旧 Hex 融资身份。
- 增补 Aikido、Strix、Hacktron、Penligent 的公开价格与计费区别；按次测试、席位订阅、免费摘要和企业询价不混为一谈。撤下无原始出处的财务数据，**不声称已建立可比市值/估值排行榜**。
- 国内新增微步 **RedAgents / Artex Pro**；补齐长亭无锋简介，区分邀测、现有商务入口与交付待核。旧国内表实有 **10** 项而概览为 **12**，新增一项后应为 **11**，商业总数按实表为 **31**（20 + 11），而非从旧错误统计简单加一。
- 同步中英文标题/概述、九列导航（新增赛事）、选型表、统计与 2026-11-18 采集日期；清理往轮新增标记，仅保留本轮实际新增/交叉纳入标记。

| 维度 | 更新前实际数量 | 更新后实际数量 |
|---|---:|---:|
| Agent / 关联项目主表 | 46 | 50 |
| 模型 | 11 | 11 |
| Skills | 3 | 4 |
| 独立 MCP | 7 | 7 |
| 赛事系列 | 2 | 3 |
| 论文 | 116 | 121 |
| Benchmark | 13 | 14 |
| Awesome Lists | 9 | 10 |
| 商业表 | 30（旧统计误写32） | 31 |

**核验限制**：部分微信公告验证受限、TSecBench 仅加载页；公开 X/Twitter 检索未取得可独立核实的重点作品官方获奖原帖。若缺少许可、最新交付状态或原始成绩公示，已在主文档标注，未用近似值或猜测填充。Markdown 表格列数、各表编号、Stars 排序及统计按文件内容核对。

---

## 📅 第 6 周：2026-09-07 ~ 09-13

### 2026-09-11 — 论文章节全量核验：勘误 + 删减 + 经 LLM4Pentest 交叉核对补充 47 篇（73→116）
对全部 73 篇存量论文逐一通过官方源（arXiv API / ACL Anthology / Crossref / NDSS / USENIX / Springer / IEEE / Elsevier）核验元数据，并与 [simon-p-j-r/LLM4Pentest](https://github.com/simon-p-j-r/LLM4Pentest)（108 篇分类清单）逐篇交叉核对：

**勘误（多项标题 / 作者 / 链接 / 日期错误）**：
- 🔴 **C12 CyberSecEval 3 链接完全错误**：`arXiv:2408.10627` 实际指向一篇视频分割论文，正确编号为 `2408.01605`（Benchmark 表中的同源错链一并修复）
- A1 综述标题错误（"From Foundations to Agents4Pentest" → 实际为 *Taxonomy, Co-Evolution, and Open Challenges*），补作者 Zheyuan He et al.
- A11 MAPTA 实际标题为 *Multi-Agent Penetration Testing AI for the Web*（作者 Isaac David, Arthur Gervais）
- A22 D-CIPHER 更新为 v2 全称，第一作者实为 Meet Udeshi（NYU，原误记为"NYU LLM CTF Team"）
- A34 Aurora 更新为 v4 标题（*Towards Automated Cyberattack Emulation with Classical Planning and LLMs*，ACNS 2026）
- B4 更名为 SAST-Genius；B15 更名为 HonestCyberEval（日期 2024-12→10）；B11 PwnGPT PDF 直链改为 ACL 落地页（日期 2025-04→07）；B17 第一作者实为 Yuxuan Zhu（非 Richard Fang）；A37 日期修正为 2023-07
- 多篇补齐此前缺失的作者与正式发表渠道（ICLR / TOSEM / TrustCom / ACISP / IRI / UMAP 等）

**删除 4 篇"攻击 AI 系统 / LLM 自身安全"类论文**：
- `UDora`（劫持 LLM Agent 推理的红队框架）、`AgentPoison`（LLM Agent 记忆投毒后门）、`CyberSecEval 1/3`（LLM 安全编码与风险评测；其基准本体保留于 Benchmark 章节，仅移除论文条目）

**补充 47 篇遗漏论文（按研究任务人工筛选，排除 LLM4Pentest 中的模型安全类条目）**：
- **A 表 +25**（37→62）：Red-MIRROR、Excalibur、APT-Agent、Pen-Strategist、CHECKMATE、AWE（NDSS'26）、Chimera（NDSS'26）、RefPentester、ARACNE、STRIATUM-CTF、WiFiPenTester、PTFusion、PrivEsc-LLM、LLMs as Hackers（EMSE）、ChainReactor（USENIX'24，AI 规划）、PentestMCP（预印本）等
- **B 表 +1**（19→20）：FirmAgent（NDSS'26，IoT 固件漏洞发现）
- **C 表 +21**（17→34）：RangeFactory、CyberForge、ExploitGym、AgentCyberRange、CyberGym-E2E（ICML'26）、HackWorld（ICLR'26）、CTF-Dojo、3CB、Got Root?、CCS/EMNLP 2025 两篇、SoK（ARES）、Forewarned 综述、《软件学报》中文综述等

**同步更新**：论文章节导语与图例（⭐新补充 = 本轮新增）、来源致谢（新增 LLM4Pentest）、顶部导航（73→116）、统计概览与 2026 趋势（新增"靶场与训练数据基建"方向）、时间戳

### 2026-09-07（19:13）— LLM4Pentest 迁入 Awesome List 章节
- 主表 #35 `simon-p-j-r/LLM4Pentest`（352 Stars）经核实实为基于《Hackers or Hallucinators?》论文整理的资源合集（105 篇学术论文 + 开源工具 / 博客 / 评测基准链接），并非 Agent 项目，自主表迁出
- 以 #8 位置插入 Awesome List 资源汇编章节（按 Star 排序：374 → 352 → 44），并标注"自项目主表迁入"
- 计数同步：主表 47→46，Awesome List 8→9，项目总数 54→53（主表 46 + AIxCC CRS 7）
- 论文表 A3（Hackers or Hallucinators?）中对 LLM4Pentest 的关联链接保留

### 2026-09-07（18:18）— 主表精简：移除 9 个偏离主线的项目（56→47）
- 删除对象：`promptfoo`、`garak`、`PyRIT`、`vulnhuntr`、`deepteam`、`agentic_security`、`buttercup`、`promptmap`、`reaper`
- 聚焦"渗透 / 红队 / CTF Agent"主线：其中 6 个为"测 AI 系统"型 LLM 红队工具，与文档"用 AI 做攻击，而非攻击 AI 系统"的定位不符；另移除漏洞挖掘 / 漏洞修复 / 测试代理类条目
- 主表重新编号 1-47，项目总数 63→54；表格备注与统计概览同步记录精简原因（中英文）
- `trailofbits/buttercup` 在「DARPA AIxCC 2025」赛事表中保留（独立章节，不算重复）

---

## 📅 第 5 周：2026-08-31 ~ 09-06

### 2026-09-02（19:35）— 全量 Star 刷新（84 个仓库）+ 全表重排序
距上次数据采集（07-20）一个多月，通过 GitHub API 与仓库网页逐一核查全部 84 个含 Star 数的仓库：

**主表排名重大变化**：
- 🚀 `usestrix/strix` 41.0k → **60.1k**（激增 19k），反超 `KeygraphHQ/shannon`（45.6k→47.6k）登顶第一
- `CyberStrikeus/CyberStrike` 1.2k → 2.2k（近乎翻倍，升至 #20）
- `oritera/Cairn` 2.0k→2.5k、`confident-ai/deepteam` 2.1k→2.6k、`0xSteph/pentest-ai` 1.3k→1.6k
- `splx-ai/agentic-radar`（998→1.0k）、`PentesterFlow/agent`（863→1.3k）跨过 1k 门槛
- `xalgord/xalgorix` 732→953、`ASCIT31/Dark-Moon` 728→887（反超 `reaper` 882）、`verialabs/ctf-agent` 613→757
- `0ca/BoxPwnr`（428→450）与 `crond-jaist/AutoPentest-DRL`（438→448）位次互换

**归档 / 迁移 / 删除标注**：
- ⚠️ `aliasrobotics/cai` 已于 2026-08-28 归档（表内标注：曾产出 18 篇论文、30+ CVE）
- ⚠️ `amazon-science/Cyber-Zero` 已于 2026-07-10 归档
- 🔄 `deadend-cli` 迁移至 `straylabs-ai` 组织（原 xoxruns，链接已更新）
- 🔄 `mcp-shodan` 迁移至 `w0h1v`（原 BurtTheCoder，链接已更新）
- ❌ `ox01024/awesome-offensive-security-ai` 已被作者删除（404），Awesome List 章节 9→8，论文致谢中的失效链接同步移除

**其他章节同步刷新**：
- Skill：`Anthropic-Cybersecurity-Skills` 26.1k→**32.0k**、`ctf-skills` 2.8k→3.2k、`awesome-skills-security` 337→374
- MCP：`PortSwigger/mcp-server` 990→1.1k、`MCP-Kali-Server` 775→808、`mcp-security-hub` 742→776、`MetasploitMCP` 696→722、`BloodHound-MCP-AI` 369→375、`mcp-shodan` 145→161、`pentest-mcp` 139→143
- Benchmark：`CyberGym` 375→**784**（翻倍，反超 XBOW 升至第 3）；`XBOW Validation Benchmarks` 611→694 并标注"已被主流模型刷至约 100% 饱和，仓库转为历史保留"；`PurpleLlama` 4.2k→4.4k、`Cybench` 256→317、`InterCode-CTF` 248→255、`NYU CTF Bench` 153→171、`AutoPenBench` 86→97、`inspect_cyber` 29→38
- AIxCC：`ATLANTIS` 613→642、`Buttercup` 1.6k→1.7k、`ARTIPHISHELL` 137→141
- Awesome List：`TalEliyahu` 714→861、`EvanThomasLuke/Awesome-AI-Hacking-Agents` 258→**653**（升至第 5）、`raphabot` 514→578、`gmh5225` 21→44
- 商业表：Strix 行"开源影响力"数据 34k+ → **60k+**
- 主表备注新增本轮刷新要点说明（中英文），数据采集时点与最后更新时间同步更新

---

## 📅 第 4 周：2026-07-20 ~ 07-26

### `1874c13` — 新增 Skill / MCP Server 两大生态章节，商业产品表"提纯"为 Top 20

这是迄今**结构变动最大**的一次更新：

- **标题升级**：主标题新增"Skill / MCP"两个维度，顶部导航表由 6 列扩展为 8 列
- **新增章节「🧩 进攻型 AI Skill 资源精选」**：收录 3 个 Star ≥ 100 的纯 Skill 仓库，含全球最大开源网安 Skill 库 `Anthropic-Cybersecurity-Skills`（26.1k Star，817 个技能覆盖 29 大安全域）
- **新增章节「🔌 进攻型 AI MCP Server 精选」**：收录 7 个 Star ≥ 100 的安全工具集合类 MCP，包括 PortSwigger 官方 Burp 扩展、Kali 官方 MCP 服务器、MetasploitMCP、BloodHound-MCP-AI 等
- **赛事章节升级**：原"DARPA AIxCC 2025 决赛 CRS 系统"升级为「🏆 知名 AI 攻防 / 智能渗透赛事」，新增**腾讯云智能渗透黑客松**子节（两届数据：238队/518人 → 610队/1345人）
- **商业化解决方案重大调整**：
  - 国外厂商表从 40 家精简为**融资/估值/影响力核查后的 Top 20**，新增"融资 / 估值 / 影响力证据"列，剔除约 20 家缺乏可查融资证据的长尾条目
  - 国内厂商表从 7 家扩展至 10 家，新增京东云 AIPTS、360"破阵子"、阿里云 Agentic BAS
- **格式统一**：全文 `⭐**新补充**` 标记统一改为小字号斜体 `<small>*⭐新补充*</small>`

---

## 📅 第 3 周：2026-07-13 ~ 07-19

> 🔥 本周为提交最密集的一周（16 次提交），核心工作是**新增"进攻型/安全专用开源模型"章节**、**大幅扩充论文库**、**建立社区贡献规范**，以及**多轮 Star 数据校对与项目增减**。

### `53ef0f4`（07-17）— 修正英文副标题遗漏
副标题补充 "Models" 一词，使其与已更新的中文标题（项目/模型/论文...）保持一致（此前中文标题已含"模型"但英文标题遗漏）。

### `d4a4994`（07-15）— 明确文档定位："进攻型 AI" ≠ "LLM 自身安全"
中英文导语大幅重写：
- 标题补充"模型"要素
- 核心定位从"渗透测试/LLM红队/漏洞挖掘"收窄为"AI 渗透测试 / 自主红队 Agent"
- **新增关键澄清**：本文档聚焦"用 AI 做攻击"，而非"攻击 AI 系统"（prompt injection / jailbreak 等 LLM 自身安全话题不在主线范围）

### `872f51f`（07-15）— 新增 3 个渗透 Agent + 2 个 Awesome List
- 开源 Agent 表新增：`Pentest-Swarm-AI`（首个"蜂群"架构渗透平台）、`pentest-ai`（MCP 封装 205+ 工具）、`PentesterFlow/agent`（终端内 Agentic 安全）；项目数 53→56
- Awesome List 新增：`Awesome-GPT-Agents`（6.6k Star）、`awesome-cybersecurity-agentic-ai`；列表数 6→8
- 模型统计同步更新（新增 Qwythos，无对齐进攻型 5→6）

### `8f97d72`（07-15）— 收紧收录标准，清理长尾项目
- 顶部导航改为锚点跳转链接，提升可读性
- 章节重命名："项目总表" → "📋 开源Agent列表"
- **明确收录门槛为 Star ≥ 90**，删除 6 个低于此门槛的项目（pentestMCP、BugHunter-AI、UDora、hackbot、aide-for-pentest、forge）
- 统一"🆕"与"⭐新补充"两种标记为单一标识，避免语义混淆
- 移除标题与描述中的"AIxCC"字样（因赛事系统已单独成表，避免重复语义）

### `14a5740`（07-15）— 新增无审查推理模型 Qwythos
模型表新增 `Qwythos-9B-Claude-Mythos-5-1M`（Empero AI 出品，"Claude 平替"级无审查模型，1M 上下文，MMLU +34.3）；模型总数 10→11。

### `6970386`（07-15）— 建立社区 Issue 导流配置
新增 `.github/config.yml`，禁用空白 Issue，引导用户前往 Discussions / CONTRIBUTING.md / Tsec-Hackathon 仓库。

### `26bbae9` / `1fb642d` / `7fabc3e` / `1164256`（07-15）— 建立四类 Issue 推荐表单
新增 4 个结构化 Issue Forms 模板（`.github/*.yml`），分别用于社区推荐**商业产品 / Benchmark / 论文 / 开源项目**，每个表单含仓库链接、Star 数、分类下拉框、简介字数限制、合规确认勾选项等标准字段。

### `92cdb4c`（07-15）— 建立社区治理文档
新增 `CODE_OF_CONDUCT.md`（基于 Contributor Covenant v2.0，4 级违规处罚阶梯）与 `CONTRIBUTING.md`（中英双语贡献指南，定义 6 大收录类别、PR 规范、表格字段格式、Emoji 标记规则）。

### `256d4a1`（07-15）— 项目增减：新增 Dark-Moon，移除 ctf-agent
开源 Agent 表新增 `ASCIT31/Dark-Moon`（728 Star，覆盖 Web/云/AD/K8s 的渗透引擎），同时移除 `verialabs/ctf-agent`（613 Star）；项目数 65→66。

### `8774b13`（07-14）— 新增 CyberStrike 项目 + 3 个模型 + Mythos + TSecBench
本周第二次较大规模更新：
- 新增开源项目 `CyberStrikeus/CyberStrike`（1.2k Star，7,300+ 安全技能）
- 新增模型 3 个：`CyberStrike-OffSec-35B`、`BugTraceAI-CORE-Ultra-27B`、`Titus-CybersecurityLLM-v1.0`；模型数 7→10
- 新增 Benchmark：`TSecBench`（腾讯安全云鼎实验室出品，源自腾讯云黑客松）
- 商业产品表新增 `Anthropic Claude Mythos`（列为国外厂商首位），国外厂商数 39→40
- 多个应用场景推荐表追加 Mythos

### `9db7385`（07-14）— 更换顶部配图
仅替换 README 顶部展示图片资源（尺寸不变）。

### `e32d155`（07-14）— 标题首次加入"模型"
主标题由"项目 / 论文 / Benchmark / 商业产品"改为"项目 / **模型** / 论文 / Benchmark / 商业产品"。

### `29e75aa`（07-13）— 单日最大规模内容扩充
本次更新奠定了此后版本的核心结构，主要变化：
- 副标题措辞由 *Agentic* 改为 *Agents*
- **新增独立章节「🧬 进攻型 / 安全专用开源模型」**：分 A 类（无安全对齐，3 个：WhiteRabbitNeo/DeepHat、Lily-Cybersecurity、BaronLLM）与 B 类（安全专用/防御对齐，4 个：VulnLLM-R、Foundation-Sec-8B、CyberSecQwen-4B、Meta-SecAlign）
- 全量刷新项目 Star 数据（如 `usestrix/strix` 从 25.7k 涨至 41.0k）
- 新增项目 `elder-plinius/T3MP3ST`（4.6k Star，红队 Agent 元框架）
- 学术论文库从 67 篇扩充至 73 篇，新增 6 篇 2026 年最新研究（含综述 Agents4Pentest、闭环框架 ZERO-APT、实战挖洞 FuzzingBrain V2、评测框架 CTFusion 等）
- Awesome List 章节位置从项目表后移至文档末尾

---

## 📅 第 2 周：2026-06-08 ~ 06-14

### `a530c6e`（06-11）— 首个完整版本正式发布
虽然仓库的 `f691286` 是"初始提交"，但仅创建了 MIT LICENSE 文件；**真正意义上的项目内容首发是本次 commit**，一次性新增 392 行 `README.md`，建立起完整的文档框架：
- 顶部统计：项目 61 个 / 论文 67 篇 / Benchmark 12 个 / Awesome List 6 个 / 商业产品 48 个（国外 39 + 国内 9）
- 开源 Agent 总表（57 条，从 43.9k Star 的 `KeygraphHQ/shannon` 到 3 Star 的 `forge`）
- DARPA AIxCC 2025 决赛 CRS 系统表（7 支决赛队伍）
- 腾讯云智能渗透黑客松介绍
- 学术论文三分表（A 渗透红队 33 篇 / B 漏洞挖掘 18 篇 / C 评测训练 16 篇）
- Agent 能力评测 Benchmark 表（12 个）+ 选型小贴士
- 商业化解决方案（国外 39 家 + 国内 6 家）+ 场景选型对照表
- 统计概览 + 免责声明

### `f691286`（06-11）— 仓库初始化
仅新增 `LICENSE` 文件（MIT License，21 行），未包含任何实质性文档内容。

> 🎉 **本周为项目起点。**

---

## 📊 统计总结 / Summary

- **历史已记载提交 / Recorded historical commits**：19（本轮未复核远端提交数量）；另有 **10** 轮本地文档修订：2026-09-02 / 09-07×2 / 09-11 / 11-18 / 11-18（补充轮次）/ 11-18（第三轮）/ 11-18（第四轮）/ 11-18（第五轮）/ 11-25（第六轮）。
- **首次提交 / First commit**：2026-06-11（仓库初始化，仅 LICENSE）
- **首个内容版本 / First content version**：2026-06-11（`a530c6e`，392 行完整文档）
- **日志中最近记载的提交 / Latest recorded commit**：2026-07-20（非远端最新提交断言）；**最新本地修订 / Latest local revision**：2026-11-18（补充轮次）。
- **核心演进脉络 / Key evolution**：
  1. 06-11：文档框架首发（项目/论文/Benchmark/商业产品四大板块）
  2. 07-13：新增"开源模型"独立章节，论文库首次大扩充
  3. 07-14 ~ 07-15：密集迭代（新项目/新模型/新Benchmark/建立社区贡献规范/收紧收录标准）
  4. 07-20：新增"Skill"与"MCP Server"两大生态维度，商业产品表提纯为 Top 20
  5. 09-02：全量 Star 刷新（84 仓库），strix 反超 shannon 登顶，标注归档/迁移/删除条目
  6. 09-07：主表精简（移除 9 个偏离主线项目，56→47）+ LLM4Pentest 迁入 Awesome List
  7. 09-11：论文章节全量核验（勘误多项错链/标题/作者 + 移除 4 篇 LLM 自身安全类 + 交叉补充 47 篇，73→116）
  8. 11-18：按章节资源更新（Agent 46→50、Skills 3→4、论文116→121、Benchmark13→14）；核对 ARTEX 闭源/商用与 sapper-v2 线上赛声明，新增百度赛事、修正商业服务与实际统计。
  9. 11-18（补充轮次）：延迟研究结果落地（模型 11→12、Skills 4→6、MCP 7→10、论文 121→122、Benchmark 14→15、Awesome 10→11，商业海外替换 2 条）；剔除以官方来源无法证实的 "Cybench 93%"，改记 Artificial Analysis Cyber Index 51%（防御口径）；新增 KaliBench 并明确其为单命令工具调用评测、仓库无许可证文件。
  10. 11-18（第三轮）：依个人审计盘点 PDF 扩充主表 10 个项目（Agent 50→60）；仅取候选名单与仓库地址，未采用其审计分类与 Stars 快照，低星与无法核验者列名不收录。
  11. 11-18（第四轮）：商业章节改为国内优先（国内节前置、选型对照换列），新增腾讯云「无境」并调至国内第 2，微步在线置首，商业 31→32。
  12. 11-18（第五轮）：按 LLM4Pentest 清单去重补录 7 篇论文（论文 122→129，A 70 / B 20 / C 39），BountyBench 补 arXiv 链接；AI 系统安全与防御治理类整体排除。
  13. 11-25（第六轮）：新增「D. 蜜罐与欺骗防御（防御侧）」10 篇（论文 129→139，A 70 / B 20 / C 39 / D 10），重新审查纳入上轮排除的蜜罐/欺骗类防御论文，补上蜜罐方向综述。

---

*历史提交条目保留此前的 diff 分析记录；2026-11-18 条目依据本轮实际文件修改和前后表格行数整理，未重新审计历史提交内容或远端最新历史。日志更新时间：2026-11-18。*
