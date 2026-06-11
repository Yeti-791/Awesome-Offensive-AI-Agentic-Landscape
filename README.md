# Offensive AI Agentic 全景：项目 / 论文 / Benchmark / 商业产品 一览
*Offensive AI Agentic Landscape: Projects, Papers, Benchmarks & Commercial Solutions*
<img width="1073" height="564" alt="Clipboard_Screenshot_1780047912" src="https://github.com/user-attachments/assets/793799dc-53e7-4fee-8959-654fbc09c902" />

<div align="center">

| 🛠️ Projects | 📑 Papers | 🧪 Benchmarks | 📚 Awesome Lists | 💼 Commercial |
|:---:|:---:|:---:|:---:|:---:|
| **61** | **67** | **12** | **6** | **48** |
| 渗透 / 红队 / CTF / AIxCC Agent | 2023-06 → 2026-01 | 2023-06 → 2025-08 | 资源索引 | 国外 39 + 国内 9 |

</div>

> 本文档系统整理了 **AI 渗透测试 / LLM 红队 / 自主攻击 Agent / 漏洞挖掘** 领域的开源项目、学术论文、能力评测 Benchmark 与国内外商业化解决方案，旨在帮助研究者、安全工程师与企业安全决策者快速建立领域全景认知。
>
> *This document curates open-source projects, academic papers, capability benchmarks, and commercial solutions (international & China) in the field of **AI penetration testing, LLM red teaming, autonomous offensive agents, and vulnerability discovery**, aimed at helping researchers, security engineers, and enterprise decision-makers quickly form a holistic view.*
>
> 数据采集时点：2026-05-29 ｜ Star 数 ≥ 1000 统一以 `k` 为单位（保留一位小数）。

---

## 📋 项目总表
*Project Master Table (61 repos after merging)*

> 按 Star 数降序排列。
> ⭐**新补充** = 本次新增（含三个 awesome list 互补的项目）
> Awesome List 类项目独立成表（见下文章节），AIxCC 决赛 CRS 系统因为属于赛事专项也单列在 AIxCC 表中、不在此表重复。
> *Sorted by stars (desc); items marked "⭐ 新补充" are newly merged in this round.*

| # | 项目 | Stars | 语言 | 类型 | 简介 |
|---|------|-------|------|------|------|
| 1 | [KeygraphHQ/shannon](https://github.com/KeygraphHQ/shannon) | 43.9k | TypeScript | 渗透 Agent | 面向 Web 应用和 API 的自主白盒 AI 渗透测试工具 |
| 2 | [usestrix/strix](https://github.com/usestrix/strix) | 25.7k | Python | 渗透 Agent | 开源 AI 黑客，发现并修复应用漏洞 |
| 3 | [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) | 21.7k | TypeScript | LLM 红队 | LLM 应用红队/渗透/漏洞扫描，OpenAI、Anthropic 在用 |
| 4 | [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi) | 17.3k | Go | 渗透 Agent | 全自主 AI 代理系统，执行复杂渗透测试任务 |
| 5 | [GreyDGL/PentestGPT](https://github.com/GreyDGL/PentestGPT) | 13.3k | Python | 渗透 Agent | LLM 驱动的自动化渗透测试代理框架（早期标杆） |
| 6 | [0x4m4/hexstrike-ai](https://github.com/0x4m4/hexstrike-ai) | 9.0k | Python | MCP / 渗透 | MCP 服务器，让 AI Agent 自主运行 150+ 安全工具 |
| 7 | [aliasrobotics/cai](https://github.com/aliasrobotics/cai) | 8.8k | Python | 安全 AI 框架 | Cybersecurity AI（CAI）安全框架 |
| 8 | [NVIDIA/garak](https://github.com/NVIDIA/garak) | 8.0k | Python | LLM 红队 | LLM 漏洞扫描器（"LLM 界的 nmap"） |
| 9 | [OWASP/Nettacker](https://github.com/OWASP/Nettacker) | 5.2k | Python | 自动化扫描 | OWASP 自动化渗透测试 / 漏扫框架 |
| 10 | [Ed1s0nZ/CyberStrikeAI](https://github.com/Ed1s0nZ/CyberStrikeAI) | 4.0k | Go | 渗透 Agent | Go 构建的 AI 原生安全测试平台 |
| 11 | [microsoft/PyRIT](https://github.com/microsoft/PyRIT) | 3.9k | Python | LLM 红队 | 生成式 AI 风险识别工具（Microsoft） |
| 12 | [protectai/vulnhuntr](https://github.com/protectai/vulnhuntr) | 2.7k | Python | 漏洞挖掘 | LLM 零样本漏洞发现，"首个 AI 自主发现 0day" |
| 13 | [GH05TCREW/pentestagent](https://github.com/GH05TCREW/pentestagent) | 2.5k | Python | 渗透 Agent | 黑盒安全测试 AI Agent 框架（GHOSTCREW） |
| 14 | [samugit83/redamon](https://github.com/samugit83/redamon) | 1.9k | Python | 红队 Agent | AI 驱动的代理式红队框架 |
| 15 | [msoedov/agentic_security](https://github.com/msoedov/agentic_security) | 1.9k | Python | LLM 红队 | Agentic LLM 漏洞扫描器 |
| 16 | [confident-ai/deepteam](https://github.com/confident-ai/deepteam) | 1.8k | Python | LLM 红队 | DeepTeam — LLM 红队测试框架 |
| 17 | [0xSteph/pentest-ai-agents](https://github.com/0xSteph/pentest-ai-agents) | 1.6k | Shell | Claude SubAgent | 将 Claude Code 转为攻击性安全研究助手 |
| 18 | [trailofbits/buttercup](https://github.com/trailofbits/buttercup) | 1.6k | Python | 漏洞修复 | Trail of Bits 出品（也是 AIxCC 第二名 CRS） |
| 19 | [zakirkun/guardian-cli](https://github.com/zakirkun/guardian-cli) | 1.4k | Python | 渗透 Agent | 生产级 AI 渗透 CLI（Gemini + LangChain） |
| 20 | [oritera/Cairn](https://github.com/oritera/Cairn) | 1.3k | Python | 渗透 Agent | 通用状态空间搜索引擎，自主渗透 |
| 21 | [utkusen/promptmap](https://github.com/utkusen/promptmap) | 1.2k | Python | LLM 红队 | LLM Prompt Injection 自动化扫描器 |
| 22 | [Gowtham-Darkseid/AutoPentestX](https://github.com/Gowtham-Darkseid/AutoPentestX) | 1.2k | Python | 渗透 Agent | 自动化渗透测试与漏洞报告 |
| 23 | [ipa-lab/hackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT) | 1.1k | Python | 渗透 Agent | 50 行代码内调用 LLM 协助伦理黑客 |
| 24 | [splx-ai/agentic-radar](https://github.com/splx-ai/agentic-radar) ⭐**新补充** | 973 | Python | Agent 安全扫描 | LLM Agentic 工作流安全扫描器（OpenAI Agents、CrewAI、LangGraph 等）|
| 25 | [berylliumsec/nebula](https://github.com/berylliumsec/nebula) | 964 | Python | 渗透助手 | AI 渗透助手，自动侦察 / 笔记 / 漏洞分析 |
| 26 | [SanMuzZzZz/LuaN1aoAgent](https://github.com/SanMuzZzZz/LuaN1aoAgent) | 961 | Python | 渗透 Agent | 全自主 AI 渗透 Agent，XBOW >90% |
| 27 | [bugbasesecurity/pentest-copilot](https://github.com/bugbasesecurity/pentest-copilot) | 847 | JavaScript | 浏览器助手 | 浏览器端的道德黑客辅助工具 |
| 28 | [ghostsecurity/reaper](https://github.com/ghostsecurity/reaper) ⭐**新补充** | 864 | Go | 测试代理 | Ghost Security 出品的实时验证代理工具，对人 / Agent 双友好 |
| 29 | [verialabs/ctf-agent](https://github.com/verialabs/ctf-agent) | 539 | Python | CTF Agent | 自主 CTF solver，BSidesSF 2026 第一名 |
| 30 | [westonbrown/Cyber-AutoAgent](https://github.com/westonbrown/Cyber-AutoAgent) ⭐**新补充** | 530 | TypeScript | 渗透 Agent | XBOW 验证基准 85%，已归档但代表性强 |
| 31 | [xalgord/xalgorix](https://github.com/xalgord/xalgorix) | 510 | Go | 渗透 Agent | 开源 AI 渗透测试 Agent |
| 32 | [crond-jaist/AutoPentest-DRL](https://github.com/crond-jaist/AutoPentest-DRL) | 431 | Python | 强化学习渗透 | 使用深度强化学习的自动化渗透测试 |
| 33 | [0ca/BoxPwnr](https://github.com/0ca/BoxPwnr) ⭐**新补充** | 401 | Python | 渗透 Agent / 多平台基准 | HackTheBox / TryHackMe / picoCTF / Cybench / XBOW 等 15 个平台基准框架 |
| 34 | [ARCANGEL0/EVA](https://github.com/ARCANGEL0/EVA) | 402 | Python | 渗透 Agent | AI 辅助渗透测试代理，多后端 AI 集成 |
| 35 | [SHAdd0WTAka/Zen-Ai-Pentest](https://github.com/SHAdd0WTAka/Zen-Ai-Pentest) | 380 | Python | 渗透 Agent | 多代理 AI 渗透框架 + 合规报告 |
| 36 | [aielte-research/HackSynth](https://github.com/aielte-research/HackSynth) ⭐**新补充** | 310 | Python | 渗透 Agent | Planner + Summarizer 双模块，PicoCTF / OverTheWire 200 题（arXiv:2412.01778）|
| 37 | [transilienceai/communitytools](https://github.com/transilienceai/communitytools) | 307 | Python | Claude 工具集 | 开源 Claude Code skills/agents/slash command |
| 38 | [m-sec-org/BreachWeave](https://github.com/m-sec-org/BreachWeave) | 276 | TypeScript | 渗透 Agent | Manager/Observer/Solver 多角色架构 |
| 39 | [yz9yt/BugTrace-AI](https://github.com/yz9yt/BugTrace-AI) | 250 | TypeScript | 漏洞追踪 | （已归档，演进为 BugTraceAI v2） |
| 40 | [xoxruns/deadend-cli](https://github.com/xoxruns/deadend-cli) ⭐**新补充** | 244 | Python | 渗透 Agent | XBOW 黑盒 81%，约 $122 API 成本，本地化执行 |
| 41 | [simon-p-j-r/LLM4Pentest](https://github.com/simon-p-j-r/LLM4Pentest) | 201 | - | 研究项目 | LLM4Pentest 研究代码 |
| 42 | [GitHubSecurityLab/seclab-taskflow-agent](https://github.com/GitHubSecurityLab/seclab-taskflow-agent) ⭐**新补充** | 199 | Python | Agent 框架 | GitHub Security Lab 出品，YAML 驱动多 Agent + CodeQL |
| 43 | [chainreactors/tinyctfer](https://github.com/chainreactors/tinyctfer) | 169 | Python | CTF Agent | antix 微型意图运行时 + 元工具设计 |
| 44 | [KHenryAegis/VulnBot](https://github.com/KHenryAegis/VulnBot) | 167 | Python | 渗透 Agent | 多代理协作框架的自主渗透测试 |
| 45 | [NYU-LLM-CTF/nyuctf_agents](https://github.com/NYU-LLM-CTF/nyuctf_agents) | 147 | Python | CTF Agent | NYU CTF Bench 配套的 D-CIPHER + Baseline |
| 46 | [antoninoLorenzo/AI-OPS](https://github.com/antoninoLorenzo/AI-OPS) | 139 | Python | 渗透助手 | 基于开源 LLM 的渗透测试 AI 助手 |
| 47 | [andreashappe/cochise](https://github.com/andreashappe/cochise) | 117 | Python | AD 渗透 Agent | 自主 Assumed Breach AD 渗透（TOSEM 2025）|
| 48 | [arthurgervais/mapta](https://github.com/arthurgervais/mapta) ⭐**新补充** | 102 | Python | 渗透 Agent | 多 Agent Web 应用安全评估 + 端到端漏洞利用验证（arXiv:2508.20816）|
| 49 | [vikramrajkumarmajji/AI-VAPT](https://github.com/vikramrajkumarmajji/AI-VAPT) | 96 | TypeScript | VAPT 框架 | 自主 AI 漏洞评估与渗透测试框架 |
| 50 | [amazon-science/Cyber-Zero](https://github.com/amazon-science/Cyber-Zero) | 91 | Python | 训练框架 | 无运行时训练网络安全代理（Amazon Science） |
| 51 | [RamKansal/pentestMCP](https://github.com/RamKansal/pentestMCP) | 68 | Python | MCP | 面向渗透测试的 MCP |
| 52 | [AI-secure/UDora](https://github.com/AI-secure/UDora) | 36 | Python | LLM 红队 | [ICML 2025] 针对 LLM Agents 的统一红队框架 |
| 53 | [yashab-cyber/hackbot](https://github.com/yashab-cyber/hackbot) | 23 | Python | 渗透助手 | 生产级 AI 渗透 / 安全助手，三种工作模式 |
| 54 | [ARESHAmohanad/BugHunter-AI](https://github.com/ARESHAmohanad/BugHunter-AI) | 15 | Python | 渗透 Agent | 赛博朋克风 AI 渗透 Agent，未来感 GUI |
| 55 | [chainreactors/aide-for-pentest](https://github.com/chainreactors/aide-for-pentest) | 13 | Python | 渗透助手 | （无简介） |
| 56 | [gfranrp/Auto-Pentest-LLM](https://github.com/gfranrp/Auto-Pentest-LLM) | 5 | Python | 渗透 Agent | 本地 LLM + Kali 自动化渗透 |
| 57 | [umangkartikey/forge](https://github.com/umangkartikey/forge) | 3 | Python | 自治框架 | 自主 AI 安全框架，自我复制蜂群 |

> 备注：1k–10k 区间的 Star 数为 GitHub 网页缩写值的换算结果；万级以上误差更大。
> *Note: stars in the 1k–10k range are converted from GitHub's abbreviated values; 10k+ may carry larger errors.*

---

## 🏆 DARPA AIxCC 2025 决赛 CRS 系统
*DARPA AIxCC 2025 Final CRS Systems*

> 美国 DARPA 在 2025 年举办的 **AI Cyber Challenge（AIxCC）** 决赛中，7 支队伍各自开源了完整的 Cyber Reasoning System（CRS），代表当前自动化漏洞发现 + 修复 Agent 的最高工程水准。
> *The 7 finalist Cyber Reasoning Systems from DARPA's AI Cyber Challenge represent today's state-of-the-art in automated vulnerability discovery & patching agents.*

| 排名 | 队伍 | CRS 系统 | Stars | 仓库 |
|:----:|------|---------|:-----:|------|
| 🥇 1 | Team Atlanta | **ATLANTIS** | 613 | [Team-Atlanta/aixcc-afc-atlantis](https://github.com/Team-Atlanta/aixcc-afc-atlantis) |
| 🥈 2 | Trail of Bits | **Buttercup** | 1.6k | [trailofbits/buttercup](https://github.com/trailofbits/buttercup) |
| 🥉 3 | Theori | **RoboDuck** | — | [theori-io/aixcc-afc-archive](https://github.com/theori-io/aixcc-afc-archive) |
| 4 | All You Need Is A Fuzzing Brain | **FuzzingBrain** | — | [o2lab/afc-crs-all-you-need-is-a-fuzzing-brain](https://github.com/o2lab/afc-crs-all-you-need-is-a-fuzzing-brain) |
| 5 | Shellphish | **ARTIPHISHELL** | 137 | [shellphish/artiphishell](https://github.com/shellphish/artiphishell) |
| 6 | 42-b3yond-6ug | **BugBuster** | — | [42-b3yond-6ug/42-b3yond-6ug-crs](https://github.com/42-b3yond-6ug/42-b3yond-6ug-crs) |
| 7 | Lacrosse (SIFT) | **Lacrosse CRS** | — | [siftech/afc-crs-lacrosse](https://github.com/siftech/afc-crs-lacrosse) |

## 🏆 TCH - 腾讯云智能渗透黑客松2025-2026
*Tencent Cloud Intelligent Penetration Agent Hackathon*
> 腾讯云智能渗透黑客松由腾讯云鼎实验室主办，是国内 **首个聚焦 LLM 智能体全流程自动化渗透** 的顶级专业赛事。赛事已连续成功举办两届，持续引领「AI + 安全」前沿技术探索与高端安全人才培养方向。赛事秉持 **铸刃止戈、以智御危** 理念，深度推动大模型与网络安全场景融合创新，探索智能渗透技术落地实践路径，同时面向产学研各界搭建高端 AI 安全竞技舞台，为行业持续输送顶尖 AI 安全实战人才。
> ###### _Tencent Cloud Intelligent Penetration Hackathon, hosted by Tencent Cloud Yunding Lab, is China’s first top-tier professional competition focusing on full-process automated penetration based on LLM agents.Successfully held for two consecutive sessions, the event keeps spearheading cutting-edge exploration in AI + cybersecurity and the cultivation of high-end security talents.Upholding the philosophy of Forging Blades to Defend Threats, Guarding Risks with Intelligence, the competition deeply drives the integrated innovation of large models and cybersecurity scenarios, and explores the practical implementation path of intelligent penetration technologies.It also builds a high-end AI security arena for industry, academia and research communities, continuously delivering top practical AI security talents to the industry._

- **赛事首页**：[https://zc.tencent.com/hackathon](https://zc.tencent.com/hackathon)
- **比赛平台**：[https://challenge.zc.tencent.com](https://challenge.zc.tencent.com/)
- **智能体社交论坛**：[https://nullzone.zc.tencent.com/feed](https://nullzone.zc.tencent.com/feed)
- **答辩视频列表**：[https://space.bilibili.com/3690981341792399/lists/5042715?type=series](https://space.bilibili.com/3690981341792399/lists/5042715?type=series)

### 🔥两届赛事高Star作品 
- **第一届CyberStrikeAI（4.1k）**：[https://github.com/Ed1s0nZ/CyberStrikeAI](https://github.com/Ed1s0nZ/CyberStrikeAI)
- **第二届Cairn（1.5k）**：[https://github.com/oritera/Cairn](https://github.com/oritera/Cairn)
- **第一届LuaN1ao鸾鸟（1k）**：[https://github.com/SanMuzZzZz/LuaN1aoAgent](https://github.com/SanMuzZzZz/LuaN1aoAgent)

---

## 📚 Awesome List 资源汇编
*Awesome List Collection*

> 本节汇总专门收录 Offensive AI / AI 安全相关精选资源的 Awesome List 仓库，本文档大量内容来自这几个 list 的交叉合并。
> *This section gathers Awesome List–style repositories. This document is largely derived from cross-merging the following lists.*

| # | 仓库 | Stars | 维护者 | 内容定位 |
|---|------|-------|--------|---------|
| 1 | [jiep/offensive-ai-compilation](https://github.com/jiep/offensive-ai-compilation) | 1.4k | jiep | 攻击性 AI 综合资源（对抗 ML / 渗透 / 钓鱼 / 生成式 AI 滥用） |
| 2 | [ottosulin/awesome-ai-security](https://github.com/ottosulin/awesome-ai-security) | 1.0k | ottosulin | 通用 AI 安全资源集合（攻防兼顾） |
| 3 | [TalEliyahu/Awesome-AI-Security](https://github.com/TalEliyahu/Awesome-AI-Security) | 714 | TalEliyahu | 偏 AI 系统防御侧的资源、研究与工具 |
| 4 | [EvanThomasLuke/Awesome-AI-Hacking-Agents](https://github.com/EvanThomasLuke/Awesome-AI-Hacking-Agents) ⭐**新补充** | 258 | EvanThomasLuke | AI Hacking Agent 全景 + AIxCC 决赛队伍 + 商业产品 + 论文 |
| 5 | [gmh5225/awesome-ai-security](https://github.com/gmh5225/awesome-ai-security) | 21 | gmh5225 | 面向渗透测试者 / 漏洞猎人 / 安全研究的 AI 安全精选 |
| 6 | [ox01024/awesome-offensive-security-ai](https://github.com/ox01024/awesome-offensive-security-ai) ⭐**新补充** | 22 | ox01024 | 偏 Benchmark + 评估 / 竞赛 / 学术资源（含中英双语 README）|

---

## 📑 相关学术论文
*Related Academic Papers (grouped by topic; within each group, newest first)*

> 在原有基础上，融合了 [tmylla/Awesome-LLM4Cybersecurity](https://github.com/tmylla/Awesome-LLM4Cybersecurity/blob/main/LITERATURES.md) 中渗透测试、进攻 AI、漏洞挖掘相关章节。共收录 **55 篇**代表性论文，按主题拆为 3 个子表：
> - **A. 渗透测试 & 红队 Agent**
> - **B. 漏洞挖掘 / 利用 / 修复**
> - **C. 评测基准 & 训练方法 & 奠基论文**
>
> 时间以 arXiv v1 提交日期为准；ⓝ 表示本次新补充。
>
> *Three sub-tables: (A) Pentesting & Red-Team Agents · (B) Vulnerability Discovery / Exploitation / Repair · (C) Evaluation, Training & Foundational. ⓝ marks newly added in this round.*

### A. 渗透测试 & 红队 Agent
*Pentesting & Red-Team Agents*

| # | 时间 | 论文 | 作者 / 机构 | 发表渠道 | 关联项目 / 主题 |
|---|------|------|-----------|---------|---------------|
| A1 | 2026-01 | [PenForge: On-the-Fly Expert Agent Construction for Automated Penetration Testing](https://arxiv.org/abs/2601.06910) ⓝ | — | arXiv | 动态构造领域专家 Agent |
| A2 | 2025-12 | [PentestEval: Benchmarking LLM-based Penetration Testing with Modular and Stage-Level Design](https://arxiv.org/abs/2512.14233) ⓝ | — | arXiv | 模块化 / 阶段化渗透测试评估 |
| A3 | 2025-12 | [Comparing AI Agents to Cybersecurity Professionals in Real-World Penetration Testing](https://arxiv.org/abs/2512.09882) ⓝ | — | arXiv | AI Agent vs 人类渗透测试师 |
| A4 | 2025-10 | [AutoPentester: An LLM Agent-based Framework for Automated Pentesting](https://arxiv.org/abs/2510.05605) ⓝ | — | arXiv | 通用自动化渗透 Agent |
| A5 | 2025-09 | [xOffense: Autonomous Penetration Testing with Offensive Knowledge-enhanced LLMs and Multi-Agent Systems](https://arxiv.org/abs/2509.13021) | Luong, Bao et al. | arXiv | 微调 Qwen3-32B 多 Agent |
| A6 | 2025-09 | [Guided Reasoning in LLM-Driven Penetration Testing Using Structured Attack Trees](https://arxiv.org/abs/2509.07939) ⓝ | — | arXiv | 攻击树结构化推理 |
| A7 | 2025-08 | [MAPTA: Multi-Agent Web Application Security Assessment](https://arxiv.org/abs/2508.20816) | Arthur Gervais 等 | arXiv | [arthurgervais/mapta](https://github.com/arthurgervais/mapta) |
| A8 | 2025-08 | [Pentest-R1: Towards Autonomous Penetration Testing Reasoning Optimized via Two-Stage RL](https://arxiv.org/abs/2508.07382) ⓝ | — | arXiv | 两阶段强化学习渗透推理 |
| A9 | 2025-07 | [PenTest2.0: Towards Autonomous Privilege Escalation Using GenAI](https://arxiv.org/abs/2507.06742) ⓝ | — | arXiv | 自主提权 |
| A10 | 2025-07 | [On the Surprising Efficacy of LLMs for Penetration-Testing](https://arxiv.org/abs/2507.00829) ⓝ | — | arXiv | LLM 渗透有效性实证 |
| A11 | 2025-05 | [AutoPentest: Enhancing Vulnerability Management With Autonomous LLM Agents](https://arxiv.org/abs/2505.10321) ⓝ | — | arXiv | 漏洞管理 Agent |
| A12 | 2025-05 | [RedTeamLLM: an Agentic AI framework for offensive security](https://arxiv.org/abs/2505.06913) | LRE Security Systems Team | arXiv | 含错误恢复机制 |
| A13 | 2025-04 | [CAI: An Open, Bug Bounty-Ready Cybersecurity AI](https://arxiv.org/abs/2504.06017) ⓝ | aliasrobotics | arXiv | [aliasrobotics/cai](https://github.com/aliasrobotics/cai) |
| A14 | 2025-02 | [Construction and Evaluation of LLM-based Agents for Semi-Autonomous Penetration Testing](https://arxiv.org/abs/2502.15506) ⓝ | — | arXiv | 半自主渗透 Agent 构造与评估 |
| A15 | 2025-02 | [RapidPen: Fully Automated IP-to-Shell Penetration Testing with LLM-based Agents](https://arxiv.org/abs/2502.16730) ⓝ | — | arXiv | IP → Shell 全自动渗透 |
| A16 | 2025-02 | [PenTest++: Elevating Ethical Hacking with AI and Automation](https://arxiv.org/abs/2502.09484) ⓝ | — | arXiv | 道德黑客 AI 自动化升级 |
| A17 | 2025-02 | [Can LLMs Hack Enterprise Networks? Autonomous Assumed Breach Penetration-Testing AD](https://arxiv.org/abs/2502.04227) | Andreas Happe, Jürgen Cito | ACM TOSEM 2025 | [andreashappe/cochise](https://github.com/andreashappe/cochise) |
| A18 | 2025-02 | [D-CIPHER: Dynamic Collaborative Intelligent Multi-Agent System for CTF](https://arxiv.org/abs/2502.10931) | NYU LLM CTF Team | arXiv | [NYU-LLM-CTF/nyuctf_agents](https://github.com/NYU-LLM-CTF/nyuctf_agents) |
| A19 | 2025-01 | [Incalmo: An Autonomous LLM-assisted System for Red Teaming Multi-Host Networks](https://arxiv.org/abs/2501.16466) | Singer, Ben et al. | arXiv | 多主机企业红队 |
| A20 | 2025-01 | [VulnBot: Autonomous Penetration Testing for A Multi-Agent Collaborative Framework](https://arxiv.org/abs/2501.13411) | KHenryAegis 等 | arXiv | [KHenryAegis/VulnBot](https://github.com/KHenryAegis/VulnBot) |
| A21 | 2024-12 | [HackSynth: LLM Agent and Evaluation Framework for Autonomous Penetration Testing](https://arxiv.org/abs/2412.01778) | Lajos Muzsai et al. (ELTE) | arXiv | [aielte-research/HackSynth](https://github.com/aielte-research/HackSynth) |
| A22 | 2024-12 | [Hacking CTFs with Plain Agents](https://arxiv.org/abs/2412.02776) ⓝ | — | arXiv | 朴素 Agent + 简单脚手架打 CTF |
| A23 | 2024-11 | [PentestAgent: Incorporating LLM Agents to Automated Penetration Testing](https://arxiv.org/abs/2411.05185) | Xiangmin Shen et al. | ASIA CCS 2025 | [GH05TCREW/pentestagent](https://github.com/GH05TCREW/pentestagent) |
| A24 | 2024-11 | [AutoPT: How Far Are We from the End2End Automated Web Penetration Testing?](https://arxiv.org/abs/2411.01236) ⓝ | — | arXiv | 端到端 Web 渗透 |
| A25 | 2024-09 | [BreachSeek: A Multi-Agent Automated Penetration Tester](https://arxiv.org/abs/2409.03789) | Ibrahim Alshehri et al. | arXiv | 多 Agent 渗透 |
| A26 | 2024-09 | [Hacking, The Lazy Way: LLM Augmented Pentesting](https://arxiv.org/abs/2409.09493) ⓝ | — | arXiv | "懒人"式 LLM 增强渗透 |
| A27 | 2024-09 | [EnIGMA: Interactive Tools Substantially Assist LM Agents in Finding Security Vulnerabilities](https://arxiv.org/abs/2409.16165) | Talor Abramovich et al. (Princeton/NYU) | ICML 2025 | CTF 自主求解 LM Agent |
| A28 | 2024-08 | [CIPHER: Cybersecurity Intelligent Penetration-testing Helper for Ethical Researcher](https://arxiv.org/abs/2408.11650) ⓝ | — | Sensors 2024 | 道德渗透助手 |
| A29 | 2024-07 | [PenHeal: A Two-Stage LLM Framework for Automated Pentesting and Optimal Remediation](https://arxiv.org/abs/2407.17788) ⓝ | — | ACSW 2024 | 两阶段：渗透 + 修复 |
| A30 | 2024-07 | [From Sands to Mansions: Enabling Automatic Full-Life-Cycle Cyberattack Construction with LLM](https://arxiv.org/abs/2407.16928) ⓝ | — | arXiv | 全生命周期攻击构造 |
| A31 | 2024-03 | [AutoAttacker: A Large Language Model Guided System to Implement Automatic Cyber-attacks](https://arxiv.org/abs/2403.01038) | Jiacen Xu et al. (UC Irvine) | arXiv | 后渗透阶段 LLM 自动化攻击 |
| A32 | 2023-08 | [PentestGPT: An LLM-empowered Automatic Penetration Testing Tool](https://arxiv.org/abs/2308.06782) | Gelei Deng et al. (NTU) | USENIX Security 2024 | [GreyDGL/PentestGPT](https://github.com/GreyDGL/PentestGPT) |
| A33 | 2023-08 | [Getting pwn'd by AI: Penetration Testing with Large Language Models](https://arxiv.org/abs/2308.00121) | Andreas Happe, Jürgen Cito (TU Wien) | ESEC/FSE 2023 | 奠基论文，hackingBuddyGPT 前身 |

### B. 漏洞挖掘 / 利用 / 修复
*Vulnerability Discovery / Exploitation / Repair*

| # | 时间 | 论文 | 作者 / 机构 | 发表渠道 | 关联项目 / 主题 |
|---|------|------|-----------|---------|---------------|
| B1 | 2025-10 | [LLM Agents for Automated Web Vulnerability Reproduction: Are We There Yet?](https://arxiv.org/abs/2510.14700) ⓝ | — | arXiv | Web 漏洞自动复现实证 |
| B2 | 2025-09 | [VulnRepairEval: An Exploit-Based Evaluation Framework for Assessing LLM Vulnerability Repair](https://arxiv.org/abs/2509.03331) ⓝ | — | arXiv | 基于 exploit 的修复评测 |
| B3 | 2025-09 | [Synergizing Static Analysis with Large Language Models for Vulnerability Discovery and beyond](https://arxiv.org/abs/2509.15433) ⓝ | — | arXiv | SAST + LLM 协同 |
| B4 | 2025-09 | [ATLANTIS: AI-driven Threat Localization, Analysis, and Triage Intelligence System](https://arxiv.org/abs/2509.14589) ⓝ | Team Atlanta | arXiv | AIxCC 决赛冠军 CRS 论文 |
| B5 | 2025-09 | [All You Need Is A Fuzzing Brain: An LLM-Powered System for Automated Vulnerability Detection and Patching](https://arxiv.org/abs/2509.07225) ⓝ | — | arXiv | AIxCC 决赛 4 队系统论文 |
| B6 | 2025-08 | [Prompt to Pwn: Automated Exploit Generation for Smart Contracts](https://arxiv.org/abs/2508.01371) ⓝ | — | arXiv | 智能合约自动 Exploit 生成 |
| B7 | 2025-07 | [LLMxCPG: Context-Aware Vulnerability Detection Through Code Property Graph-Guided LLMs](https://arxiv.org/abs/2507.16585) ⓝ | — | USENIX Security 2025 | CPG 引导的上下文感知漏洞检测 |
| B8 | 2025-07 | [MalCodeAI: Autonomous Vulnerability Detection and Remediation via Language Agnostic Code Reasoning](https://arxiv.org/abs/2507.10898) ⓝ | — | arXiv | 跨语言自治漏洞检测 + 修复 |
| B9 | 2025-05 | [VADER: A Human-Evaluated Benchmark for Vulnerability Assessment, Detection, Explanation, and Remediation](https://arxiv.org/abs/2505.19395) ⓝ | — | arXiv | 漏洞评估 / 解释 / 修复人评基准 |
| B10 | 2025-04 | [PwnGPT: Automatic Exploit Generation Based on Large Language Models](https://aclanthology.org/2025.acl-long.562.pdf) ⓝ | — | ACL 2025 | 自动 Exploit 生成 |
| B11 | 2025-03 | [CVE-Bench: A Benchmark for AI Agents' Ability to Exploit Real-World Vulnerabilities](https://arxiv.org/abs/2503.17332) | UIUC Kang Lab | ICML 2025 | [uiuc-kang-lab/cve-bench](https://github.com/uiuc-kang-lab/cve-bench) |
| B12 | 2025-03 | [CVE-Bench (NAACL): Benchmarking LLM-based Software Engineering Agent's Ability to Repair Real-World CVE Vulnerabilities](https://aclanthology.org/2025.naacl-long.212/) ⓝ | — | NAACL 2025 | 真实 CVE 修复评测（注：与 ICML 版同名不同任务）|
| B13 | 2025-03 | [CASTLE: Benchmarking Dataset for Static Code Analyzers and LLMs towards CWE Detection](https://arxiv.org/abs/2503.09433) ⓝ | — | arXiv | CWE 检测基准 |
| B14 | 2024-12 | [AI Cyber Risk Benchmark: Automated Exploitation Capabilities](https://arxiv.org/abs/2410.21939) ⓝ | — | arXiv | 自动化漏洞利用能力基准 |
| B15 | 2024-07 | [eyeballvul: a future-proof benchmark for vulnerability detection in the wild](https://arxiv.org/abs/2407.08708) ⓝ | — | arXiv | 防训练泄漏的漏洞检测基准 |
| B16 | 2024-06 | [Teams of LLM Agents can Exploit Zero-Day Vulnerabilities](https://arxiv.org/abs/2406.01637) | Richard Fang et al. (UIUC) | arXiv | 多 Agent 协作 0day 利用 |
| B17 | 2024-04 | [LLM Agents can Autonomously Exploit One-day Vulnerabilities](https://arxiv.org/abs/2404.08144) | Richard Fang et al. (UIUC) | arXiv | 已知 CVE 报告 → 自动利用 |
| B18 | 2024-02 | [LLM Agents can Autonomously Hack Websites](https://arxiv.org/abs/2402.06664) | Richard Fang et al. (UIUC) | arXiv | LLM Agent 自主攻击网站（早期工作）|

### C. 评测基准 & 训练方法 & 综述 & 奠基
*Evaluation Benchmarks, Training Methods, Surveys & Foundational*

| # | 时间 | 论文 | 作者 / 机构 | 发表渠道 | 关联项目 / 主题 |
|---|------|------|-----------|---------|---------------|
| C1 | 2025-10 | [PACEbench: A Framework for Evaluating Practical AI Cyber-Exploitation Capabilities](https://arxiv.org/abs/2510.11688) ⓝ | — | arXiv | 实战 AI 网络利用能力评测 |
| C2 | 2025-08 | [Towards Effective Offensive Security LLM Agents (CTFTiny + CTFJudge)](https://arxiv.org/abs/2508.05674) | Shao, Rani et al. | AAAI 2026 | CTFTiny / CTFJudge |
| C3 | 2025-07 | [Cyber-Zero: Training Cybersecurity Agents without Runtime](https://arxiv.org/abs/2508.00910) | Terry Yue Zhuo et al. (Amazon AGI / Monash) | arXiv | [amazon-science/Cyber-Zero](https://github.com/amazon-science/Cyber-Zero) |
| C4 | 2025-06 | [CyberGym: Evaluating AI Agents on Real-World Vulnerability Analysis](https://arxiv.org/abs/2506.02548) | Zhun Wang et al. (UC Berkeley Sunblaze) | ICLR 2026 | [sunblaze-ucb/cybergym](https://github.com/sunblaze-ucb/cybergym) |
| C5 | 2025-06 | [SEC-bench: Automated Benchmarking of LLM Agents on Real-World Software Security Tasks](https://arxiv.org/abs/2506.11791) | SEC-bench Team | NeurIPS 2025 | [SEC-bench/SEC-bench](https://github.com/SEC-bench/SEC-bench) |
| C6 | 2025-06 | [UDora: A Unified Red Teaming Framework against LLM Agents](https://arxiv.org/abs/2503.01908) | AI-secure 团队 | ICML 2025 | [AI-secure/UDora](https://github.com/AI-secure/UDora) |
| C7 | 2025-04 | [Benchmarking Practices in LLM-driven Offensive Security: Testbeds, Metrics, and Experiment Design](https://arxiv.org/abs/2504.10112) ⓝ | — | arXiv | LLM 进攻安全评测方法学 |
| C8 | 2025-02 | [OCCULT: Evaluating Large Language Models for Offensive Cyber Operation Capabilities](https://arxiv.org/abs/2502.15797) ⓝ | — | arXiv | 进攻性网络作战能力评测 |
| C9 | 2024-10 | [AutoPenBench: Benchmarking Generative Agents for Penetration Testing](https://arxiv.org/abs/2410.03225) | Luca Gioacchini et al. (Politecnico di Torino) | EMNLP Industry 2025 | [lucagioacchini/auto-pen-bench](https://github.com/lucagioacchini/auto-pen-bench) |
| C10 | 2024-10 | [Towards Automated Penetration Testing: Introducing LLM Benchmark, Analysis, and Improvements](https://arxiv.org/abs/2410.17141) ⓝ | — | arXiv | 渗透测试 LLM 基准 + 改进 |
| C11 | 2024-08 | [CYBERSECEVAL 3: Advancing the Evaluation of Cybersecurity Risks and Capabilities in LLMs](https://arxiv.org/abs/2408.10627) | Meta Purple Llama Team | arXiv | [meta-llama/PurpleLlama](https://github.com/meta-llama/PurpleLlama) v3 |
| C12 | 2024-08 | [Cybench: A Framework for Evaluating Cybersecurity Capabilities and Risk of Language Models](https://arxiv.org/abs/2408.08926) | Andy K. Zhang et al. (Stanford CRFM) | ICLR 2025 | [andyzorigin/cybench](https://github.com/andyzorigin/cybench) |
| C13 | 2024-07 | [AgentPoison: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases](https://arxiv.org/abs/2407.12784) | Zhaorun Chen et al. (UChicago) | NeurIPS 2024 | LLM Agent 后门 / 记忆投毒 |
| C14 | 2024-06 | [NYU CTF Bench: A Scalable Open-Source Benchmark for Evaluating LLMs in Offensive Security](https://arxiv.org/abs/2406.05590) | Talor Abramovich et al. (NYU) | NeurIPS 2024 D&B | [NYU-LLM-CTF/NYU_CTF_Bench](https://github.com/NYU-LLM-CTF/NYU_CTF_Bench) |
| C15 | 2023-12 | [Purple Llama CyberSecEval: A Secure Coding Benchmark for Language Models](https://arxiv.org/abs/2312.04724) | Meta Purple Llama Team | arXiv | [meta-llama/PurpleLlama](https://github.com/meta-llama/PurpleLlama) v1 |
| C16 | 2023-06 | [InterCode: Standardizing and Benchmarking Interactive Coding with Execution Feedback](https://arxiv.org/abs/2306.14898) | John Yang et al. (Princeton NLP) | NeurIPS 2023 D&B | [princeton-nlp/intercode](https://github.com/princeton-nlp/intercode) |

> 注：会议/期刊年份为论文实际收录会议届期；arXiv 时间为 v1 提交月份。来源致谢：[tmylla/Awesome-LLM4Cybersecurity](https://github.com/tmylla/Awesome-LLM4Cybersecurity)、[EvanThomasLuke/Awesome-AI-Hacking-Agents](https://github.com/EvanThomasLuke/Awesome-AI-Hacking-Agents)、[ox01024/awesome-offensive-security-ai](https://github.com/ox01024/awesome-offensive-security-ai)。
> *Note: conference years refer to actual proceedings; arXiv dates are v1. Credits to the three awesome lists above.*

---

## 🧪 Agent 能力评测 Benchmark
*Agent Capability Benchmarks (sorted by stars, desc)*

> 用于评估渗透测试 / 网络安全 / CTF / 红队 Agent 能力的开源 benchmark。
> *Open-source benchmarks for evaluating pentest / cybersecurity / CTF / red-team Agent capabilities.*

| # | Benchmark | 仓库 | Stars | 时间 | 任务规模 | 评测重点 | 关联论文 |
|---|-----------|------|-------|------|---------|---------|---------|
| 1 | **CyberSecEval (1/2/3/4)** | [meta-llama/PurpleLlama](https://github.com/meta-llama/PurpleLlama) | 4.2k | 2023-12 | 跨多类任务（不安全代码 / Prompt Injection / 攻击辅助 / AutoPatchBench 等） | Meta 出品，覆盖 LLM "防/攻"两端 | [arXiv:2312.04724](https://arxiv.org/abs/2312.04724) / [arXiv:2408.10627](https://arxiv.org/abs/2408.10627) |
| 2 | **XBOW Validation Benchmarks** | [xbow-engineering/validation-benchmarks](https://github.com/xbow-engineering/validation-benchmarks) | 611 | 2025-06 | 104 道 Web 漏洞挑战（Jeopardy CTF） | XBOW（首个登顶 HackerOne 的 AI）出品，覆盖真实渗透 / 赏金漏洞 | XBOW Engineering Blog |
| 3 | **CyberGym** ⭐**新补充** | [sunblaze-ucb/cybergym](https://github.com/sunblaze-ucb/cybergym) | 375 | 2025-06 | 真实世界漏洞分析任务（240GB 数据集） | UC Berkeley 出品，强调 real-world，配 4 个示例 Agent | [arXiv:2506.02548](https://arxiv.org/abs/2506.02548)（ICLR 2026）|
| 4 | **Cybench** | [andyzorigin/cybench](https://github.com/andyzorigin/cybench) | 256 | 2024-08 | 40 道专业级 CTF 任务（17 个子任务） | Stanford CRFM，支持 Unguided / Subtask 双模式 | [arXiv:2408.08926](https://arxiv.org/abs/2408.08926)（ICLR 2025）|
| 5 | **InterCode-CTF** | [princeton-nlp/intercode](https://github.com/princeton-nlp/intercode) | 248 | 2023-06 | 100 道 picoCTF 题 | Bash/SQL/Python/CTF 交互式代码 Agent 评测 | [arXiv:2306.14898](https://arxiv.org/abs/2306.14898)（NeurIPS 2023 D&B）|
| 6 | **NYU CTF Bench** | [NYU-LLM-CTF/NYU_CTF_Bench](https://github.com/NYU-LLM-CTF/NYU_CTF_Bench) | 153 | 2024-06 | 200 题正式 + 55 题开发集，6 大类 | CSAW CTF 历年题目 + Docker 化部署 | [arXiv:2406.05590](https://arxiv.org/abs/2406.05590)（NeurIPS 2024 D&B）|
| 7 | **AutoPenBench** | [lucagioacchini/auto-pen-bench](https://github.com/lucagioacchini/auto-pen-bench) | 86 | 2024-10 | 33 个任务（22 In-Vitro + 11 真实 CVE） | 生成式 Agent 渗透测试通用评测 | [arXiv:2410.03225](https://arxiv.org/abs/2410.03225)（EMNLP Industry 2025）|
| 8 | **inspect_cyber** ⭐**新补充** | [UKGovernmentBEIS/inspect_cyber](https://github.com/UKGovernmentBEIS/inspect_cyber) | 29 | 2025-06 | 通用扩展（任务可插拔） | UK AI Security Institute 官方 Agentic Cyber 评估扩展 | — |
| 9 | **CVE-Bench** | [uiuc-kang-lab/cve-bench](https://github.com/uiuc-kang-lab/cve-bench) | — | 2025-03 | 40 个 critical 严重程度 CVE | 首个基于真实 CVE 的 Web 漏洞利用 Agent 评测 | [arXiv:2503.17332](https://arxiv.org/abs/2503.17332)（ICML 2025）|
| 10 | **BountyBench** | [bountybench/bountybench](https://bountybench.github.io/) | — | 2025-05 | 25 个真实 GitHub 项目 + Bug Bounty | 用美元金额量化攻防影响力 | Stanford CRFM Blog（2025-05）|
| 11 | **SEC-bench** | [SEC-bench/SEC-bench](https://github.com/SEC-bench/SEC-bench) | — | 2025-06 | 200 个 C/C++ 真实 CVE，PoC + 补丁双任务 | 首个全自动化的真实安全工程评测 | [arXiv:2506.11791](https://arxiv.org/abs/2506.11791)（NeurIPS 2025）|
| 12 | **CTFTiny** | [NYU-LLM-CTF/CTFTiny](https://github.com/NYU-LLM-CTF/CTFTiny) | — | 2025-08 | 50 题轻量 CTF 子集 | 配套 CTFJudge（LLM-as-a-Judge），降低复现成本 | [arXiv:2508.05674](https://arxiv.org/abs/2508.05674)（AAAI 2026）|

> 备注：标 `—` 的 Stars 表示数据缺失或仓库较新。许多 Agent 项目（PentestGPT、cochise、xOffense、Cyber-Zero、deadend-cli 等）会在自己 README 中报告在 NYU CTF Bench / Cybench / AutoPenBench / XBOW 等 Benchmark 上的得分。
> *Note: "—" means missing data or a new repo. Many agent projects report scores against these benchmarks in their own READMEs.*

### Benchmark 选型小贴士｜*Selection Cheatsheet*

| 评测目标 / Goal | 推荐 Benchmark / Recommendation |
|---|---|
| 通用 CTF 能力 / General CTF | NYU CTF Bench（200 题）、Cybench（40 题精选）、InterCode-CTF（轻量起步）|
| 真实漏洞利用 / Real-world Exploit | XBOW（104 Web）、CyberGym（真实漏洞 240GB）、AutoPenBench（CVE 任务）、CVE-Bench（Web）、SEC-bench（C/C++ CVE）|
| LLM 安全 / 红队基础 / LLM Safety & Red Team | CyberSecEval（Meta 全家桶）|
| 经济影响量化 / Economic Impact | BountyBench |
| 政府级评估扩展 / Government-grade | inspect_cyber（UK AISI）|
| 快速回归 / Lightweight Regression | CTFTiny |

---

## 💼 商业化解决方案
*Commercial Solutions*

> 本节盘点全球范围内主流的 **AI / Agentic 智能渗透测试 / 自主攻击安全** 商业化产品。分为「国外」与「国内」两个子表，按市场知名度 / 关注度排序。
> *This section enumerates representative commercial AI / Agentic penetration testing & autonomous offensive security products worldwide, split into international and domestic tables.*

### 🌍 国外厂商
*International Vendors*

| # | 公司 | 产品 | 官网 | 产品定位与特色 |
|---|------|------|------|---------------|
| 1 | **XBOW** | XBOW | [xbow.com](https://xbow.com/) | 自主攻击性安全平台，"黑客的智慧 + 机器的速度"。首个登顶 HackerOne 排行榜的 AI；通过真实 exploit 独立验证每一发现，专为 AI 原生开发节奏设计 |
| 2 | **Horizon3.ai** | NodeZero® | [horizon3.ai](https://horizon3.ai/) | 自称 "World's Best AI Hacker"，无 Agent 部署，可在生产环境安全运行。已在生产中执行 24 万+ 次自主渗透测试，客户含 NSA 与 4 家财富 10 强 |
| 3 | **Pentera** | Pentera AVP | [pentera.io](https://pentera.io/) | AI 驱动的暴露验证平台（Exposure Validation），覆盖身份/终端/网络/云。1000+ 企业客户，持续真实攻击模拟（含 LockBit / BlackCat 等勒索家族） |
| 4 | **Strix (Usestrix)** | Strix | [usestrix.com](https://usestrix.com/) | 开源 + 商业双栈，AI 黑客发现并修复应用漏洞，2.5 万 GitHub Stars 的开源版本是入口 |
| 5 | **RunSybil** | Sybil | [runsybil.com](https://www.runsybil.com/) | 自主 Web 应用渗透 AI Agent，强调与人工 pentester 协作 |
| 6 | **Hadrian** | Hadrian | [hadrian.io](https://hadrian.io/) | 持续攻击面管理 + AI 自主渗透；Gartner Peer Insights 榜单常客 |
| 7 | **Hacktron** | Hacktron AI | [hacktron.ai](https://www.hacktron.ai/) | 端到端 AI 渗透 / 漏洞挖掘平台，融资速度快 |
| 8 | **Mindgard** | Mindgard | [mindgard.ai](https://mindgard.ai/) | 专注于 AI / LLM 红队（不是测应用，是测 AI 模型本身），含 Mindgard Lite 自助平台 |
| 9 | **Dreadnode** | Dreadnode | [dreadnode.io](https://dreadnode.io/) | 攻击性 AI 研究平台，前 Microsoft AI Red Team 核心成员创办 |
| 10 | **Pensar** | Pensar AI | [pensarai.app](https://www.pensarai.app/) | 智能合约 / Web3 渗透 Agent，开源版本 apex |
| 11 | **CalypsoAI** | Calypso | [calypsoai.com](https://calypsoai.com/) | 企业级 GenAI 安全 + 红队评估，老牌厂商 |
| 12 | **Aikido Security** | Aikido AI Pentest | [aikido.dev/attack/aipentest](https://www.aikido.dev/attack/aipentest) | All-in-one 应用安全平台中的 AI Pentest 模块 |
| 13 | **MindFort** | MindFort | [mindfort.ai](https://mindfort.ai/) | 自主红队 AI Agent，专注 SaaS 应用 |
| 14 | **Hex Security** | Hex | [hex.co](https://hex.co/) | AI 驱动的暴露面验证 |
| 15 | **AISLE** | AISLE | [aisle.com](https://aisle.com/) | 自主 AppSec Agent，强调与开发流程集成 |
| 16 | **Veria Labs** | Veria CTF Agent | [verialabs.com](https://verialabs.com/) | 出自 CTFTime 美国第一战队 ".;,;.（smiley）"，BSidesSF 2026 CTF 自主夺冠 |
| 17 | **Penligent** | Penligent | [penligent.ai](https://penligent.ai/) | 一站式 AI Pentesting 平台，主打 EU / APAC 市场 |
| 18 | **Theori** | Xint / Xint Code | [xint.io](https://xint.io/) / [code.xint.io](https://code.xint.io/) | DARPA AIxCC 决赛 RoboDuck 团队所属公司，一线攻防专家创办 |
| 19 | **Terra Security** | Terra | [terra.security](https://www.terra.security/) | 持续渗透 + 攻击面管理 |
| 20 | **bugbunny ai** | bugbunny | [bugbunny.ai](https://bugbunny.ai/) | 漏洞赏金 / Bug Hunting 自动化 Agent |
| 21 | **Origin / Prelude** | Origin / Prelude | [originhq.com](https://www.originhq.com/) / [preludesecurity.com](https://www.preludesecurity.com/) | 持续安全验证 / BAS（与 Prelude 合并）|
| 22 | **Hound** | CyberHound | [cyberhound.ai](https://cyberhound.ai/) | AI 驱动的攻击面 + 渗透 |
| 23 | **Shinobi Security** | Shinobi | [shinobi.security](https://shinobi.security/) | AI Pentest，专注初创/中型企业 |
| 24 | **SPLX** | SPLX (含 agentic-radar) | [splx.ai](https://splx.ai/) | LLM Agent 工作流安全扫描 + 红队，开源 [agentic-radar](https://github.com/splx-ai/agentic-radar) 973 Stars |
| 25 | **Sec1** | Sec1 AI Pentest | [sec1.io/ai-pentest](https://sec1.io/ai-pentest/) | 自主理解应用工作流，发现需要"人类级推理"的逻辑漏洞 |
| 26 | **PentestGPT (商业版)** | PentestGPT Pro | [pentestgpt.com](https://pentestgpt.com/) | 从开源 PentestGPT 演化而来，全自主渗透 Agent SaaS |
| 27 | **Astra Security** | Astra Pentest | [getastra.com/autonomous-pentesting](https://www.getastra.com/autonomous-pentesting) | 80× 加速的自主渗透，与人工服务搭配 |
| 28 | **Zentinel** | Zentinel | [zentinel.dev](https://zentinel.dev/) | 自主 AI 渗透 + 修复，主打 SOC2 / ISO27001 合规 |
| 29 | **AutoVAPT.ai** | AutoVAPT | [autovapt.ai](https://autovapt.ai/) | 持续自主 VAPT 平台 |
| 30 | **RedVeil.ai** | RedVeil | [redveil.ai](https://www.redveil.ai/) | 兼具人工渗透深度的 AI 自动化 |
| 31 | **PAIStrike** | PAIStrike | [scantist.com](https://scantist.com/) | Scantist 推出的 AI Pentest 模块 |
| 32 | **Harmony Intelligence** | Harmony | [harmonyintelligence.com](https://www.harmonyintelligence.com/) | AI 红队 + 安全评估 |
| 33 | **KinoSec** | KinoSec | [kinosec.ai](https://kinosec.ai/) | AI Pentest 早期初创 |
| 34 | **Casco** | Casco | [casco.com](https://casco.com/) | AI 驱动的安全验证 |
| 35 | **Corridor dev** | Corridor | [corridor.dev](https://corridor.dev/) | AppSec + AI 渗透 |
| 36 | **Novee** | Novee Security | [novee.security](https://novee.security/) | AI 自主渗透 |
| 37 | **PentX** | PentX | [pentx.ai](https://pentx.ai/) | AI Pentest 早期初创 |
| 38 | **Revelion ai** | Revelion | [revelion.ai](https://www.revelion.ai/) | AI 红队 |
| 39 | **qriousec** | qriousec | [qriousec.github.io](https://qriousec.github.io/) | AI Agent 红队研究 |

### 🇨🇳 国内厂商
*Domestic Vendors (China)*

| # | 公司 | 产品 | 官网 | 产品定位与特色 |
|---|------|------|------|---------------|
| 1 | **绿盟科技** | 绿盟智能渗透系统 **AI-PTS** | [AI-PTS 产品页](https://www.nsfocus.com.cn/html/2026/651_0528/289.html) | 基于"风云卫大模型 SecLLM + 多智能体（MAS）"，2025-08 正式发布。聚焦 Web 应用安全测试与自动化渗透，含 8.8 万+ 漏洞知识图谱、8600+ POC 库 |
| 2 | **万径安全（Yaklang）** | **万径千机 / 小智** 智能渗透机器人 | [megavector.cn](https://www.megavector.cn/safetyProduct/xiaozhi/) | 国内首款融合知识图谱与大模型的智能渗透机器人，"AI+YAK" 双引擎（YAK 为自研网络安全语言）|
| 3 | **长亭科技** | 无锋 | [chaitin.com](https://www.chaitin.cn/xblade)  |--|
| 4 | **斗象科技（漏洞盒子）** | **蛙池AI** | [digpool.cn](https://www.digpool.cn/) | 全球首款"原生 AI"漏洞挖掘工具 / 白帽工作台。对话式挖洞，AI 自主拆解渗透意图，内置 SQLi/XSS/RCE/上传等漏洞检测专家技能矩阵 |
| 5 | **奇安信** | **AI 加特林** 自动化渗透测试系统 | [qianxin.com / AI](https://www.qianxin.com/topics/aiforsecurity) | "自动化漏洞攻击的火力平台"，能在数分钟内将漏洞公告转为可执行的渗透链；与 QAX-GPT 安全大模型联动 |
| 6 | **安恒信息** | **AI 渗透测试智能体**（基于恒脑 3.0） | [dbappsecurity.com.cn](https://www.dbappsecurity.com.cn/) | 国内首个安全垂域大模型"恒脑"驱动的渗透 Agent，三大能力：自动化风险发现 + 任务规划、智能调度渗透工具、深度解析被动流量 |
| 7 | **悬镜安全** | **灵脉 PTE** AI 自动化渗透测试平台 | [pte.xmirror.cn](https://pte.xmirror.cn/) | 结合漏扫工具与专家渗透优势，将专家能力训练为 AI，半自动化 / 自动化检测业务逻辑漏洞 |


### 🎯 选型对照（按典型场景）
*Pick by Scenario*

| 场景 / Scenario | 推荐产品（国外）| 推荐产品（国内）|
|---|---|---|
| Web App / API 自主渗透 | XBOW、Pentera、Strix | 绿盟 AI-PTS、斗象蛙池AI、安恒 AI 渗透 Agent |
| 生产环境安全验证 | Horizon3.ai NodeZero、Pentera | 绿盟 AI-PTS、墨云天查 |
| 漏洞赏金 / Bug Hunting | XBOW、Strix、bugbunny ai | 斗象蛙池AI、长亭 chainreactors |
| 持续攻击面 + 攻击模拟 | Hadrian、Pentera、Horizon3.ai | 华云安灵刃 |
| 业务逻辑 / 复杂渗透 | XBOW、Sec1 | 悬镜灵脉 PTE、万径千机 / 小智 |
| 火力打击型自动化漏洞利用 | Horizon3.ai NodeZero | 奇安信 AI 加特林 |
| LLM / Agent 红队（测 AI 本身）| Mindgard、Dreadnode、SPLX agentic-radar | — |
| 智能合约 / Web3 | Pensar、Hacktron | — |

---

> 🕐 **最后更新时间 / Last updated**：2026-05-29 17:40 (UTC+8)

---

## 📊 统计概览
*Statistics Overview*

- **项目总数 / Total projects**：61（项目主表 49 个 + AIxCC CRS 系统 7 个 + Awesome List 6 个，去重后 ≈ 61）
- **收录论文 / Papers**：**67** 篇（A. 渗透 & 红队 33 篇 / B. 漏洞挖掘 18 篇 / C. 评测 & 训练 16 篇；覆盖 2023-06 → 2026-01）
- **收录 Benchmark / Benchmarks**：12 个（覆盖 2023-06 → 2025-08）
- **商业产品 / Commercial products**：46 个（国外 39 + 国内 7）
- **Awesome List**：6 个
- **主要语言 / Languages**：Python ≈ 70%，TypeScript ≈ 12%，Go ≈ 8%，其他 ≈ 10%
- **领域趋势 / Trends**：
  - **2023**：方向探索（Happe & Cito、PentestGPT、InterCode-CTF）
  - **2024**：基础工作落地 + 评测基准建立（Cybench、NYU CTF Bench、AutoPenBench、EnIGMA、Fang 三部曲、PenHeal、AutoPT）
  - **2025**：多 Agent 协作 + 训练方法 + 自主 AD 渗透 + 真实 CVE 评测 + AIxCC 决赛 + RL 渗透 + 实证研究（VulnBot、cochise、D-CIPHER、Cyber-Zero、xOffense、CVE-Bench、SEC-bench、CyberGym、ATLANTIS、Buttercup、RapidPen、Pentest-R1、OCCULT、PACEbench）
  - **2026 起**：商业化加速（XBOW、Pentera、Horizon3.ai、Hacktron、MindFort 等纷纷涌现）+ 持续基准化（PentestEval、PenForge）

---

## ⚠️ 免责声明
*Disclaimer*

> 本文档汇总的所有项目、论文与 Benchmark **仅供学习研究、企业内部安全防护与授权渗透测试使用**。
> 在任何情况下，使用者均须严格遵守所在国家和地区的法律法规以及目标组织的授权范围；**严禁将其用于未经授权的攻击、入侵、破坏或其他任何违法活动**。任何因滥用本文档收录内容而引发的法律责任、经济损失或安全后果，均由使用者自行承担，与本文档作者及所列项目维护者无关。
>
> *All projects, papers, and benchmarks compiled in this document are intended **solely for learning, internal enterprise security hardening, and authorized penetration testing**. Users must strictly comply with the laws and regulations of their jurisdiction as well as the authorization scope granted by the target organization. **Any unauthorized attack, intrusion, sabotage, or other illegal activities are strictly prohibited.** Any legal liability, financial loss, or security consequence resulting from misuse of the contents herein shall be borne entirely by the user, and is unrelated to the authors of this document or the maintainers of the listed projects.*
