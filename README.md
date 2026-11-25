# Offensive AI Agentic 全景：项目 / 模型 / Skills / MCP / 赛事 / 论文 / Benchmark / 资源汇编 / 商业产品
*Offensive AI Agents Landscape: Projects, Models, Skills, MCP Servers, Competitions, Papers, Benchmarks, Resource Lists & Commercial Solutions*
<img width="1073" height="564" alt="599999755-793799dc-53e7-4fee-8959-654fbc09c902" src="https://github.com/user-attachments/assets/f3beb3dd-c4f4-40e1-a6e8-f2ae52743973" />

<div align="center">

| [🛠️ Projects](#开源agent列表) | [🧬 Models](#进攻型--安全专用开源模型) | [🧩 Skills](#进攻型-ai-skill-资源精选) | [🔌 MCP](#进攻型-ai-mcp-server-精选) | [Competitions](#知名-ai-攻防--智能渗透赛事) | [📑 Papers](#相关学术论文) | [🧪 Benchmarks](#agent-能力评测-benchmark) | [📚 Awesome Lists](#awesome-list-资源汇编) | [💼 Commercial](#商业化解决方案) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **60** | **12** | **6** | **10** | **3** | **139** | **15** | **11** | **32** |
| 渗透 / 红队 / CTF 与关联框架 | 安全研究 5 + 专用 7 | 纯 Skill · ≥100 Stars | 独立工具桥接 · ≥100 Stars | 赛事系列 · 区分届次阶段 | 2023 → 2026 | 2023 → 2026 | 交叉检索索引 | 国内 12 + 国外精选 20 |

</div>

> **🚀 一个持续维护的「进攻型 AI」全景地图**——聚焦**用 AI 做授权渗透测试与自主红队**，把开源 Agent、开放权重模型、Skills 与安全工具 MCP、攻防赛事、论文、Benchmark、资源汇编和国内外商业产品放在一张表里。无论你是做 **AI 红队、漏洞研究、CTF**，还是AI 渗透产品，都能在这里快速定位值得跟进的项目、模型与数据。主线是**用 AI 攻**，而非攻击 LLM 自身安全；关联防御资源明确标注。
>
> **为什么要看这里**：AI 正把渗透测试从「人工提权」推向「自主攻防」，但哪些项目真能用、哪些只有 demo、哪些已经闭源，信息高度分散。本文档按 **精确 Stars 排序 + 逐项核验**整理，并明确区分 **开放权重 / 开源代码 / 托管评测 / 闭源商用**，帮你穿透宣传话术。2026-11 起还新增了**防御侧**视角——蜜罐、欺骗防御与对抗 LLM 攻击者的措施（见论文 D 段），让进攻方也能看清对手会怎么布防。
>
> **🔍 亮点速览**：🛠️ 开源 Agent **60+** ｜ 🧬 模型 **12** ｜ 🧩 Skills **6** ｜ 🔌 MCP **10** ｜ 🏆 赛事 **3** 系列 ｜ 📑 论文 **139** 篇（含综述与防御侧）｜ 🧪 Benchmark **15** ｜ 📚 资源汇编 **11** ｜ 💼 商业产品 **32** 家——全部中英双语、持续更新。
>
> *A continuously maintained **offensive AI landscape** for **authorized AI-driven penetration testing and autonomous red teaming**: open-source agents, open-weight models, Skills & security-tool MCP servers, competitions, papers, benchmarks, curated lists, and commercial products — all in one place. Built for offensive-AI researchers, red teamers, vulnerability researchers, CTF players, and security engineers to quickly find projects, models and datasets worth tracking. Using AI to attack is the main scope, not attacking LLM safety; defensive resources are clearly labeled.*
>
> *Why it matters: AI is turning penetration testing from manual exploitation into autonomous offense-and-defense. Stars-sorted and entry-by-entry verified, this list separates open weights from open source and hosted evaluation from closed commercial products, so you can cut through marketing noise. Since late 2026 it also covers the defensive side — honeypots, cyber deception, and anti-LLM-attacker defenses (paper section D) — so offensive builders can see how defenders counter them.*
>
> 数据采集时点：**2026-11-25**｜持续更新；Stars 取 GitHub 当次精确值排序，≥ 1000 显示一位小数 `k`。来源可能晚于本文历史版本，失败/受限项在相应章节说明；未逐项运行被收录代码，作者自报成绩已标注。

---

## 📋 开源Agent列表
*Open-Source Agent List*

> 按精确 Star 数降序排列后格式化，收录 Star ≥ 90 的开源 AI 渗透测试 / 红队 Agent 及关联进攻型安全项目；归档项目保留历史状态，不意味着推荐当前部署。
> <small>*⭐新补充*</small> = 本轮新增（2026-11-18）；简介中的功能为项目文档描述，未经独立验证的跑分注明为作者自报。
> *Sorted by exact stars before formatting; repositories must have ≥ 90 stars. Archived projects are labeled as historical references. The small italic marker denotes additions on 2026-11-18; project-reported capabilities are not independent evaluations.*

| # | 项目 | Stars | 语言 | 类型 | 简介 |
|---|------|-------|------|------|------|
| 1 | [usestrix/strix](https://github.com/usestrix/strix) | 76.4k | Python | 渗透 Agent | 开源 AI 应用安全测试工具，发现、验证与修复应用漏洞 |
| 2 | [KeygraphHQ/shannon](https://github.com/KeygraphHQ/shannon) | 52.0k | TypeScript | 渗透 Agent | 面向 Web 应用和 API 的自主白盒 AI 渗透测试工具 |
| 3 | [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi) | 34.5k | Go | 渗透 Agent | 自主 AI 代理系统，组织工具调用与复杂渗透测试任务 |
| 4 | [GreyDGL/PentestGPT](https://github.com/GreyDGL/PentestGPT) | 16.5k | Python | 渗透 Agent | LLM 驱动的自动化渗透测试框架（早期标杆） |
| 5 | [0x4m4/hexstrike-ai](https://github.com/0x4m4/hexstrike-ai) | 13.7k | Python | MCP / 渗透 | 独立安全工具 MCP 桥接；亦见 MCP 章节，不将工具数量视为 Agent 能力证据 |
| 6 | [aliasrobotics/cai](https://github.com/aliasrobotics/cai) | 9.9k | Python | 安全 AI 框架 | Cybersecurity AI（CAI）安全框架，当前归档，保留作历史参考 |
| 7 | [AIPentest/CyberStrikeAI](https://github.com/AIPentest/CyberStrikeAI)（原 Ed1s0nZ） | 8.8k | Go | 渗透 Agent | AI 原生安全测试平台；原地址已重定向至 AIPentest 组织 |
| 8 | [elder-plinius/T3MP3ST](https://github.com/elder-plinius/T3MP3ST) | 7.1k | TypeScript | 红队 Agent | 多智能体安全研究框架，复用本机 AI 编码客户端进行授权测试 |
| 9 | [BitterSecurity/Decepticon](https://github.com/BitterSecurity/Decepticon) <small>*⭐新补充*</small> | 6.6k | — | 红队 Agent | LangGraph / LiteLLM 编排，多角色协作、隔离沙箱与会话恢复；Apache-2.0，部分 main 分支功能尚未发布 |
| 10 | [OWASP/Nettacker](https://github.com/OWASP/Nettacker) | 5.7k | Python | 自动化扫描 | OWASP 自动化安全测试工具，非纯 LLM Agent，作为关联工具收录 |
| 11 | [oritera/Cairn](https://github.com/oritera/Cairn) | 5.3k | Python | 渗透 Agent | Fact / Intent / Hint 显式图与共享黑板；动态 Worker 进行状态空间搜索，AGPLv3，另提供商业授权 |
| 12 | [gadievron/raptor](https://github.com/gadievron/raptor) <small>*⭐新补充*</small> | 4.0k | — | 攻防研究框架 | 基于 Claude Code 的自主攻防研究框架（RAPTOR），串联静态 / 二进制分析、漏洞验证与 PoC、补丁生成；MIT。Stars 为页面缩写，未取得精确整数 |
| 13 | [CyberStrikeus/CyberStrike](https://github.com/CyberStrikeus/CyberStrike) | 3.6k | TypeScript | 渗透 Agent | AI 驱动的安全测试代理，结合安全知识与任务编排；[项目网站](https://cyberstrike.io) |
| 14 | [samugit83/redamon](https://github.com/samugit83/redamon) | 3.4k | Python | 红队 Agent | AI 驱动的代理式红队框架 |
| 15 | [GH05TCREW/pentestagent](https://github.com/GH05TCREW/pentestagent) | 3.3k | Python | 渗透 Agent | 黑盒安全测试 AI Agent 框架，面向渗透、漏洞赏金与红队工作流 |
| 16 | [Armur-Ai/Pentest-Swarm-AI](https://github.com/Armur-Ai/Pentest-Swarm-AI) | 3.3k | Go | 渗透 Agent | 多 Agent 渗透工作流，黑板协调、模型接入与任务观察；不将路线图功能视为已实现 |
| 17 | [0xSteph/pentest-ai-agents](https://github.com/0xSteph/pentest-ai-agents) | 2.5k | Shell | Claude SubAgent | Claude Code 安全研究子代理集合，非纯 Skill 项目 |
| 18 | [N1nEmAn/sapper-v2](https://github.com/N1nEmAn/sapper-v2) <small>*⭐新补充*</small> | 2.3k | — | 渗透 / CTF 多 Agent | 女娲基础（nvwabase）上的竞赛型自主渗透编排：指挥官/执行者分层、共享事实图与自恢复；MIT。作者声明第三届腾讯云线上赛第一、80.18 分、8 小时无人值守，**非线下总冠军** |
| 19 | [zakirkun/guardian-cli](https://github.com/zakirkun/guardian-cli) | 1.9k | Python | 渗透 Agent | Gemini / LangChain 驱动的安全测试 CLI |
| 20 | [0xSteph/pentest-ai](https://github.com/0xSteph/pentest-ai) | 1.8k | Python | 渗透 Agent | 集成安全工具、专项代理与漏洞验证，CLI / MCP 双入口；非独立工具桥接，不重复列入 MCP 精选 |
| 21 | [Gowtham-Darkseid/AutoPentestX](https://github.com/Gowtham-Darkseid/AutoPentestX) | 1.6k | Python | 渗透 Agent | 自动化安全测试与漏洞报告 |
| 22 | [bugbasesecurity/pentest-copilot](https://github.com/bugbasesecurity/pentest-copilot) | 1.6k | JavaScript | 浏览器助手 | 浏览器端的授权安全测试辅助工具 |
| 23 | [JoasASantos/NeuroSploit](https://github.com/JoasASantos/NeuroSploit) <small>*⭐新补充*</small> | 1.5k | Rust | 渗透 Agent | 当前 README 为 Rust-only v4.4.2，任务编排、证据复核与复测报告；MIT，旧 Python 版单独保留在历史分支 |
| 24 | [SanMuzZzZz/LuaN1aoAgent](https://github.com/SanMuzZzZz/LuaN1aoAgent) | 1.5k | Python | 渗透 Agent | 自主安全测试 Agent；历史 XBOW >90% 为项目自报，非统一条件的独立排名 |
| 25 | [PentesterFlow/agent](https://github.com/PentesterFlow/agent) | 1.5k | TypeScript | 渗透 Agent | 终端内安全测试工作台，人在回路、技能与 Burp 集成 |
| 26 | [xalgorix/xalgorix](https://github.com/xalgorix/xalgorix)（原 xalgord） | 1.4k | Go | 渗透 Agent | 自托管 AI Web / API 安全测试与报告，原仓库地址已重定向 |
| 27 | [ipa-lab/hackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT) | 1.3k | Python | 渗透 Agent | 简洁的 LLM 授权测试研究框架 |
| 28 | [ASCIT31/Dark-Moon](https://github.com/ASCIT31/Dark-Moon) | 1.3k | Python | 渗透 Agent | Web / 云 / AD / K8s 场景的多智能体安全测试与工具集成 |
| 29 | [berylliumsec/nebula](https://github.com/berylliumsec/nebula) | 1.2k | Python | 渗透助手 | AI 辅助侦察、笔记与漏洞分析 |
| 30 | [pikpikcu/airecon](https://github.com/pikpikcu/airecon) <small>*⭐新补充*</small> | 1.1k | Python | 渗透 Agent | 面向 Kali Linux Docker 沙箱的自主安全测试 Agent，兼容 OpenAI 协议的本地 / 托管模型网关，内置 Caido 代理与「侦察 → 分析 → 利用 → 报告」流水线；MIT。Stars 为页面缩写 |
| 31 | [s0ld13rr/pentestcode](https://github.com/s0ld13rr/pentestcode) <small>*⭐新补充*</small> | 1.1k | TypeScript | 渗透 Agent | OpenCode 硬分叉改造的多 Agent 自主渗透系统，持久化「交战状态」并支持并行操作；MIT。Stars 为页面缩写；同 `k` 值不表示与上一行精确值相同 |
| 32 | [Zyrexnn/Cybermes](https://github.com/Zyrexnn/Cybermes) <small>*⭐新补充*</small> | 1.0k | Python | 渗透 Agent | Hermes 推理引擎 + 200+ 技能手册 + Go 工具链，另提供原生 Go MCP Server；Apache-2.0，第三方技能与工具保留各自许可。Stars 为页面缩写；README 含赞助与推广内容，与本表收录判定无关 |
| 33 | [cdxiaodong/cain-agent](https://github.com/cdxiaodong/cain-agent) <small>*⭐新补充*</small> | 953 | — | 渗透 Agent | 基于 Claude Agent SDK 的确定性流水线，以工程约束强制 scope，内置 AWS / Azure / GCP 与阿里云 / 腾讯云 / 华为云云渗透模块；Apache-2.0 |
| 34 | [verialabs/ctf-agent](https://github.com/verialabs/ctf-agent) | 939 | Python | CTF Agent | 自主 CTF solver，竞赛结果按项目对应资料理解 |
| 35 | [m-sec-org/BreachWeave](https://github.com/m-sec-org/BreachWeave) | 769 | TypeScript | 渗透 Agent | Manager / Observer / Solver 多角色架构，第二届腾讯云赛事代表作品 |
| 36 | [transilienceai/communitytools](https://github.com/transilienceai/communitytools) | 625 | Python | Claude 工具集 | skills / agents / slash command 混合集合，非纯 Skill 精选 |
| 37 | [westonbrown/Cyber-AutoAgent](https://github.com/westonbrown/Cyber-AutoAgent) | 552 | TypeScript | 渗透 Agent | 当前归档；历史 XBOW 85% 为项目自报 |
| 38 | [Stanford-Trinity/ARTEMIS](https://github.com/Stanford-Trinity/ARTEMIS) <small>*⭐新补充*</small> | 552 | Rust / Python | 研究型渗透 Agent | Stanford Trinity 项目，基于 Codex 改造、Supervisor 协调测试；Apache-2.0，源码公开不等同完整复现实验已验证 |
| 39 | [ARCANGEL0/EVA](https://github.com/ARCANGEL0/EVA) | 541 | Python | 渗透 Agent | 多后端 AI 安全测试助手 |
| 40 | [SHAdd0WTAka/Zen-Ai-Pentest](https://github.com/SHAdd0WTAka/Zen-Ai-Pentest) | 507 | Python | 渗透 Agent | 多代理安全测试与合规报告 |
| 41 | [0ca/BoxPwnr](https://github.com/0ca/BoxPwnr) | 471 | Python | 渗透 / CTF 基准 | HackTheBox / TryHackMe / picoCTF / Cybench 等多平台框架 |
| 42 | [crond-jaist/AutoPentest-DRL](https://github.com/crond-jaist/AutoPentest-DRL) | 448 | Python | 强化学习渗透 | 深度强化学习驱动的自动化安全测试 |
| 43 | [chainreactors/cyber-harness](https://github.com/chainreactors/cyber-harness) <small>*⭐新补充*</small> | 423 | — | Agent Harness | 通用安全 Agent harness，单二进制用于渗透、红队与漏洞赏金工作流；AGPL-3.0。「harness」指编排外壳，不等同完整自主渗透产品 |
| 44 | [martian56/redcell](https://github.com/martian56/redcell) <small>*⭐新补充*</small> | 414 | Python | 渗透 Agent | LangGraph plan/act 引擎驱动的 AI 红队平台，在 Kali 容器内端到端执行测试并输出 PDF / JSON / SARIF；MIT |
| 45 | [BugTraceAI/BugTraceAI](https://github.com/BugTraceAI/BugTraceAI) <small>*⭐新补充*</small> | 389 | Shell（入口仓库） | 渗透套件 | 关联 CLI / WEB / API 多个子模块的自托管 Web 安全套件；Apache-2.0，各组件与模型许可单独核对，部分版本仍为 beta |
| 46 | [chu0119/Pojun](https://github.com/chu0119/Pojun) <small>*⭐新补充*</small> | 367 | Go | 渗透 Agent | 多 Agent 自主渗透与后渗透 C2 平台，攻击链全程留痕；AGPL-3.0。自述为原百度 `Agent+` 冠军项目 ARTEX 的**独立演进分支**，非 ARTEX 本体，也不改变其闭源现状 |
| 47 | [kpolley/redai](https://github.com/kpolley/redai) <small>*⭐新补充*</small> | 356 | — | 验证工作台 | 源码发现与运行时验证分工的 AI 安全工作台，支持 Web / iOS 环境；MIT，项目演示不等于第三方评测 |
| 48 | [straylabs-ai/deadend-cli](https://github.com/straylabs-ai/deadend-cli)（原 xoxruns） | 331 | Python | 渗透 Agent | 本地化执行；历史 XBOW 黑盒 81%、约 $122 为项目自报 |
| 49 | [pensarai/apex](https://github.com/pensarai/apex) <small>*⭐新补充*</small> | 327 | TypeScript | 渗透 Agent | 终端内运行的自主渗透 Agent，支持黑盒 / 白盒与多模型接入；Apache-2.0。语言取自仓库文件构成，页面未渲染语言占比 |
| 50 | [aielte-research/HackSynth](https://github.com/aielte-research/HackSynth) | 324 | Python | 渗透 Agent | Planner + Summarizer，PicoCTF / OverTheWire 研究框架（arXiv:2412.01778） |
| 51 | [GitHubSecurityLab/seclab-taskflow-agent](https://github.com/GitHubSecurityLab/seclab-taskflow-agent) | 287 | Python | Agent 框架 | YAML 驱动多 Agent 与 CodeQL，作为安全研究关联框架收录 |
| 52 | [Coff0xc/AutoRedTeam-Orchestrator](https://github.com/Coff0xc/AutoRedTeam-Orchestrator) <small>*⭐新补充*</small> | 270 | Python | 渗透编排 / 审计 | 本地 MCP / AI 攻击面审计与证据门控工具，按 safe → scan → active-lab → full 四级权限执行，默认对自身配置做只读审计；MIT |
| 53 | [KHenryAegis/VulnBot](https://github.com/KHenryAegis/VulnBot) | 236 | Python | 渗透 Agent | 多代理协作的自主安全测试研究框架 |
| 54 | [NYU-LLM-CTF/nyuctf_agents](https://github.com/NYU-LLM-CTF/nyuctf_agents) | 181 | Python | CTF Agent | NYU CTF Bench 配套 D-CIPHER 与基线 |
| 55 | [chainreactors/tinyctfer](https://github.com/chainreactors/tinyctfer) | 174 | Python | CTF Agent | antix 意图运行时与元工具设计，腾讯云往届代表作品 |
| 56 | [antoninoLorenzo/AI-OPS](https://github.com/antoninoLorenzo/AI-OPS) | 172 | Python | 渗透助手 | 基于开源 LLM 的安全测试助手 |
| 57 | [andreashappe/cochise](https://github.com/andreashappe/cochise) | 153 | Python | AD 渗透 Agent | 自主 Assumed Breach AD 安全测试（TOSEM 2025） |
| 58 | [arthurgervais/mapta](https://github.com/arthurgervais/mapta) | 136 | Python | 渗透 Agent | 多 Agent Web 应用安全评估与验证（arXiv:2508.20816） |
| 59 | [vikramrajkumarmajji/AI-VAPT](https://github.com/vikramrajkumarmajji/AI-VAPT) | 108 | TypeScript | VAPT 框架 | AI 漏洞评估与安全测试框架 |
| 60 | [amazon-science/Cyber-Zero](https://github.com/amazon-science/Cyber-Zero) | 100 | Python | 训练框架 | 当前归档的网络安全 Agent 训练研究，历史参考 |

> 核验说明（2026-11-18）：Stars 来自当次 GitHub 页面内精确计数，先按整数排序、再以一位小数 `k` 展示；同一 `k` 值不表示精确值相同。**本轮据下列 PDF 补充 10 个项目（50 → 60）**：`gadievron/raptor`（4.0k，缩写）、`pikpikcu/airecon`（1.1k，缩写）、`s0ld13rr/pentestcode`（1.1k，缩写）、`Zyrexnn/Cybermes`（1.0k，缩写）、`cdxiaodong/cain-agent`（953）、`chainreactors/cyber-harness`（423）、`martian56/redcell`（414）、`chu0119/Pojun`（367）、`pensarai/apex`（327）、`Coff0xc/AutoRedTeam-Orchestrator`（270）。`splx-ai/agentic-radar` 聚焦 AI 系统自身安全，不在主表；旧 [yz9yt/BugTrace-AI](https://github.com/yz9yt/BugTrace-AI)（251 Stars）退出精选，另收录当前 BugTraceAI 套件，**不将二者 Stars 合并或认定为直接改名**。语言 `—` 表示本次未取得可靠语言信息。
>
> **来源与筛选边界**：上述候选取自一份个人审计盘点 PDF《Beyond ARTEX: 45 AI Pentesting Tools and How to Find Them》（作者署名 `nasa`，2026-11-10，由 Print To PDF 生成）。该 PDF 为**个人整理与自查报告，不是独立评测**，其能力判断与审计结论本文**未逐条复核**，也未采用其中的 `SECRET-HUNTING` / `EXPOSURE` 分类与 Shodan 匹配数；PDF 的 Stars 与最后推送时间为 2026-11-07 前后快照，**一律不用其覆盖本轮实时值**。按 90 Stars 门槛，以下未收录：[r74tech/virga](https://github.com/r74tech/virga)（10）、[F0ran9/forang](https://github.com/F0ran9/forang)（15）、[TiaMEOWS/mergen](https://github.com/TiaMEOWS/mergen)（3，且为 CyberStrike 的 fork）；[cskwork/scopeweaver](https://github.com/cskwork/scopeweaver) 与 [MythicAgents/sage](https://github.com/MythicAgents/sage) 的 Stars 未能从仓库页渲染取得（镜像口径相差过大），未与门槛比对故不收录；`echidna`（Mythic agent 类型）与 `ycode` 未定位到可核验仓库，同样不收录，**不填零、不臆测**。
> *Stars are point-in-time exact GitHub counts, sorted before rounding. Ten entries were added (50 → 60) from a personal audit-style PDF whose capability and exposure findings were not re-verified and whose star snapshots were not carried over. Projects below the 90-star bar, unrendered star counts, and unlocatable repositories are listed above with reasons rather than zero-filled. A dash means language data was not verified.*

---

## 🧬 进攻型 / 安全专用开源模型
*Offensive & Security-Specialized Open-Weight Models*

> 上面的项目多为 Agent 框架 / 脚手架，能力同时受模型、工具、记忆与编排机制影响。本节收录用于**授权安全研究**的开放权重模型，分为：
> - **A. 面向进攻型安全研究的模型**：模型卡将授权渗透、红队或漏洞研究列为用途；弱拒答/无审查声明仅代表作者的对齐定位，**不等于更强的安全能力**。
> - **B. 安全领域专用模型（含推理 / 漏洞 / 防御对齐）**：用于漏洞检测、安全分析或防御研究；不能仅据名称认定进攻能力或对齐属性。
>
> *Open-weight models for authorized security research, grouped by documented use rather than assumed offensive capability. Model quality depends on evaluation evidence, tooling and orchestration; reduced refusal alone is not a capability metric. Model licenses and quantized mirrors must be checked separately.*

### A. 面向进攻型安全研究的模型
*Models for Authorized Offensive Security Research*

| # | 模型 | 参数量 | 基座 | 发布方 | 定位与证据边界 |
|---|------|-------|------|--------|----------------|
| 1 | [WhiteRabbitNeo](https://huggingface.co/WhiteRabbitNeo) / [DeepHat-V1-7B](https://huggingface.co/DeepHat/DeepHat-V1-7B) | 7B–70B（不同成员） | Llama / Qwen；DeepHat-V1 为 Qwen2.5-Coder-7B | WhiteRabbitNeo / DeepHat（Kindo） | 安全研究模型系列；官方集合收录 DeepHat-V1，不据此认定全系列直接更名。V1 卡声明 Apache-2.0 附扩展限制，逐模型核对许可；本次未核实 DeepHat V2 |
| 2 | [Lily-Cybersecurity-7B-v0.2](https://huggingface.co/segolilylabs/Lily-Cybersecurity-7B-v0.2) | 7B | Mistral-7B-Instruct-v0.2 | segolilylabs | 作者报告使用 22,000 组网安问答；未公开完整数据集、拒答评测或许可正文，不再标为已证实“无对齐” |
| 3 | [BaronLLM v2 / Q8](https://huggingface.co/Trendyol/Qwen3-14B-BaronLLM-v2-Q8) | 14B 级 | Qwen3-14B | Trendyol Group Security Team | 修正旧版 7B/8B 与个人作者归属；官方 Q8_0 GGUF 卡明确保留安全约束，自报 CS-Eval / SecBench 结果非独立验证。卡载 Apache-2.0 及权重授权要求，不能简化为无条件开放 |
| 4 | [CyberStrike-OffSec-35B](https://huggingface.co/oyildirim/CyberStrike-OffSec-35B) | 35B MoE（卡中 A3B） | Qwen3.6-35B-A3B | oyildirim | 当前卡为 300 条工具调用样本、LoRA SFT，重在路由与终止行为；24 场景评测是作者自报，对基座并非全面领先。删除旧 SFT+DPO、超越 GPT-4、无对齐断言；许可未核实 |
| 5 | [BugTraceAI-CORE-Ultra-27B / Q6](https://huggingface.co/BugTraceAI/BugTraceAI-CORE-Ultra-27B-Q6) | 27B | DavidAU/Qwen3.6-27B-Heretic2-Uncensored-Finetune-Thinking | BugTraceAI | 当前卡声明 2,541 条安全研究样本、LoRA SFT；Q6_K 是量化形式，非独立新模型。Apache-2.0 为作者声明，上游许可链另核；不将训练样本数写作端到端能力证据 |

> 模型卡提供的是发布方声明；安全能力需要在同一任务、工具与预算下评测。严格限定授权范围，并核查权重与数据的许可链。
> *Model cards are publisher statements, not independent capability certification. Compare under matched tasks, tools and budgets; review weight and data licenses.*

### B. 安全领域专用模型（含推理 / 漏洞 / 防御对齐）
*Security-Specialized Models (Reasoning / VulnDetect / Defense-Aligned)*

| # | 模型 | 参数量 | 基座 | 发布方 | 定位与证据边界 | 用途 |
|---|------|-------|------|--------|----------------|------|
| 1 | [Altar-1](https://huggingface.co/AikidoSec/altar-1) <small>*⭐新补充*</small> | 卡称 504B（平台统计约 501B）MoE | GLM-5.3 | AikidoSec | REAP 专家剪枝与 AWQ W4A16 权重，服务代码审计 / Deep Review；继承上游许可。卡中 KL 保真度测试不是渗透成功率；不得将量化后文件大小误作参数规模 | 代码审计 / 安全分析 |
| 2 | [Feyospace-v1-small](https://huggingface.co/feyospace/feyospace-v1-small) <small>*⭐新补充*</small> | 卡称 28B | Qwen3.8-27B | feyospace | 初始公开 checkpoint，长上下文 SFT 与网络安全 Agent 研究；[原始论文](https://arxiv.org/abs/2609.08418)。页面未给本 checkpoint 的独立评测与许可，论文家族成绩不可直接套用 | 网络安全 Agent 研究 |
| 3 | [VulnLLM-R-7B](https://huggingface.co/Virtue-AI-HUB/VulnLLM-R-7B)（[代码](https://github.com/ucsb-mlsec/VulnLLM-R)） | 7B 级 | Qwen2.5-7B-Instruct | Virtue-AI-HUB / 论文作者 | 改用原模型卡而非第三方 GGUF 镜像；[arXiv:2512.07533](https://arxiv.org/abs/2512.07533) 漏洞检测推理，效果限定论文任务与设置 | 漏洞检测 |
| 4 | [Foundation-Sec-8B-Reasoning](https://huggingface.co/fdtn-ai/Foundation-Sec-8B-Reasoning) | 8B | Foundation-Sec-8B / Llama-3.1-8B | Cisco Foundation AI | 2026-01-28 发布，领域推理与安全运营；[技术报告](https://arxiv.org/abs/2601.21051)。卡称指令微调 / RLHF，许可指向 NOTICE.md；不再使用“全球首个”等绝对宣传 | 安全推理 / 运营 |
| 5 | [CyberSecQwen-4B](https://huggingface.co/lablab-ai-amd-developer-hackathon/CyberSecQwen-4B) | 4B | Qwen3-4B-Instruct-2507 | Samuel Mulia / lablab-ai AMD 项目 | 更正官方卡归属；14,776 条训练数据，Apache-2.0，CTI-RCM / MCQ 为作者自报；防御问答不能视为自主渗透评测 | 威胁情报辅助 |
| 6 | [Titus-CybersecurityLLM-v1.0 / Q4_K_M](https://huggingface.co/AlicanKiraz0/Titus-CybersecurityLLM-v1.0-Q4_K_M-No-MTP-GGUF) | 35B MoE | Qwen3.6-35B-A3B | AlicanKiraz0 | 土耳其语优先的 SOC / DFIR 助手；本次可读的是作者量化仓库，原本体卡不可读取。GGUF / MLX 是发布格式，不重复计模型；许可及本体训练声明未完整核实 | SOC / DFIR（补充） |
| 7 | [RedSage 家族](https://huggingface.co/RISys-Lab/RedSage-Qwen3-8B-Ins)（[K-SFT](https://huggingface.co/RISys-Lab/RedSage-K-SFT) / [K-GRPO](https://huggingface.co/RISys-Lab/RedSage-K-GRPO)） <small>*⭐新补充*</small> | 8B | Qwen3-8B-Base | RISys-Lab（Khalifa University） | 网络安全通用模型家族，**按家族合并计 1 条**：CFW → Base → Ins / DPO，另有基于 KaliBench 训练的 K-SFT / K-GRPO 变体。论文《RedSage: A Cybersecurity Generalist LLM》标注 ICLR 2026；**模型卡未见任何许可标签**，不得写作已明确开放许可。K-SFT 在 KaliBench 5,000 测试集自报 Total 77.4（unrestricted 65.9 / restricted 73.2 / hinted 93.2），为单基准、作者自报结果 | 安全问答 / 工具调用 |

> 本轮移出 [Meta-SecAlign](https://huggingface.co/facebook/Meta-SecAlign-8B)（主要是模型抗提示注入防御）与 [Qwythos](https://huggingface.co/bestexhibitions/Qwythos-9B-Claude-Mythos-5-1M)（当前卡主要是通用推理实验，未见进攻能力评测）。Qwythos 的 Claude 轨迹来源与 1M 上限属作者声明，不代表 Claude 官方关系或实测完整 1M 能力；两者仍可由这里的链接追溯。本轮新增 RedSage 家族后为 **12 个：A 类 5、B 类 7**。
> *Meta-SecAlign and the general-reasoning Qwythos experiment are no longer in the main model tables. With the RedSage family added, the total is 12 (5 + 7). Publisher claims, quantized formats, research-family results and individual checkpoint evaluations are distinguished.*
>
> **关联说明｜通用模型的安全评测**：[Mistral Large 4 (Le Chonk)](https://mistral.ai/news/mistral-large-4-oss/) 为原生多模态 MoE 通用模型（约 1T 总参数、49B 激活/token、含嵌入与输出层 52B），**非安全专用模型，故不并入本节 12 条计数**。权重发布于 **2026-10-29**（[官方 RSS](https://mistral.ai/news/rss) `pubDate`；公告正文无日期，仅"earlier this month / today"相对表述）；许可为 **Mistral Ecosystem Open-Weight License**（modified MIT，提供 MaaS 需另签商业许可），**不是 Apache-2.0**。公告页给出 *Artificial Analysis Cyber Index* **51%**，原文口径为发现代码库漏洞、复现并验证、再打补丁（**防御向**）；公告页与 HF 模型卡**均未出现 Cybench 成绩**，不得转写为 Cybench 分数。模型卡仅列 Intelligence Index v5 = 26 与 Coding Agent Index 48%，与新闻页的 Cyber 51% 属不同页面、不同指标，不可混用。
> *Note: Mistral Large 4 is a general-purpose model listed only for its published defensive cyber evaluation; it is not counted among the 12 security-specialized models. The 51% figure is the Artificial Analysis Cyber Index (vulnerability discovery, reproduction and patching); no Cybench result appears in the official announcement or the model card.*

---

## 🧩 进攻型 AI Skill 资源精选
*Offensive AI Skills (Claude Code / Agent Skills Ecosystem)*

> 除了独立 Agent 与底层模型，**Agent Skill**（如 Claude Code Skills、[agentskills.io](https://agentskills.io) / [skills.sh](https://skills.sh) 生态）正成为"进攻型 AI"落地到通用 AI 编程客户端的重要形态——把渗透测试方法论、工具链调用顺序与 payload/字典打包为可被 Agent 按需自动加载的结构化技能模块。仅收录**纯 Skill 形态**（非 Agent/Subagent 混合项目）、Star ≥ 100 的仓库，按 Star 数降序排列。
> *Agent Skills package pentest methodology, tool-chains, and payloads/wordlists into structured modules that general-purpose AI coding agents (e.g. Claude Code) can auto-load on demand. Only pure-Skill repos (excluding Agent/Subagent-hybrid projects) with ≥ 100 stars are listed, sorted by stars (desc).*

| # | 仓库 | Stars | 载体 / 生态 | 定位与特色 |
|---|------|-------|-----------|-----------|
| 1 | [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) | 36.3k | agentskills.io 技能库 | Mahipal Jangra 的社区项目，**非 Anthropic 官方**；技能文档及附带脚本，Apache-2.0。页面标题称 817 项、正文称 818，未逐目录确认，不再使用全球最大/唯一等宣传；按授权渗透相关技能选用 |
| 2 | [SnailSploit/Claude-Red](https://github.com/SnailSploit/Claude-Red) <small>*⭐新补充*</small> | ≈11.2k | Claude Code Skill | Kai Aizen 维护的进攻技能库，`Skills/<类别>/<技能>/SKILL.md`，MIT；根目录含索引 JSON、`install.sh` 与 Python 索引脚本，**无 subagent/MCP 层**，故按纯 Skill 收。页面仅显示 `11.2k`（缩写），未取得精确整数；README 分类相加为 78 项 / 23 类，路线图目标 ~130 项，作者自述数量不作已核验计数 |
| 3 | [ljagiello/ctf-skills](https://github.com/ljagiello/ctf-skills) | 3.7k | Agent Skills | CTF Web / Pwn / 密码 / 逆向 / 取证等技能文档与脚本，另有检索、调度与题解技能；调度依赖宿主 Agent，非自主渗透框架。MIT |
| 4 | [yaklang/hack-skills](https://github.com/yaklang/hack-skills) <small>*⭐新补充*</small> | ≈2.7k | Agent Skills（`npx skills add`） | Yaklang 生态**独立技能仓**，非 `yaklang/yaklang` 本体，MIT；`skills/<id>/SKILL.md`，102 个深度主题技能 + 1 主入口 + 6 类别入口，覆盖 14 个安全域。条目路由是技能内索引，**不构成子代理编排**；另提供离线加密 ZIP 与静态站，使用前须自行核对包完整性。Stars 显示 `2.7k`（缩写） |
| 5 | [Eyadkelleh/awesome-skills-security](https://github.com/Eyadkelleh/awesome-skills-security) | 407 | Agent Skills | SecLists 精选子集封装为 7 类技能，README 声明 MIT；“60+”来自安装生态支持，非逐客户端验证结果。LLM 测试部分不属本文主线 |
| 6 | [Arenbai/SecSkills](https://github.com/Arenbai/SecSkills) <small>*⭐新补充*</small> | 266 | Claude Code Skill | `SKILL.md` 与 26 个参考文件的 PTES 技能模块，当前 v1.3.0、MIT；**作者已声明停更，仓库未归档**，作为可审阅的历史方法论资源，不宣传为持续维护产品 |

> 本轮新增 `Claude-Red` 与 `yaklang/hack-skills`，表由 4 → **6**；两者 Stars 页面只显示 `11.2k` / `2.7k` 缩写，未取得精确整数，标注为 `≈`，排序按显示值近似处理。判定依据是**交付主体为 SKILL.md 技能包**：`Claude-Red` 的 `install.sh` 与索引脚本、`hack-skills` 的主入口/类别入口路由均属技能自身组织方式，**不构成子代理编排**，故未按 Agent 框架排除；反过来，热度也不构成纳入理由。
> 使用前检查每个 Skill 的正文、附带脚本、依赖与权限；**Skill 形态不代表无代码或低风险**，数量和 Stars 也不等于技能质量。执行仅限明确授权范围，不直接运行未经审查的下载脚本。
> *Two skill packs were added (4 → 6). Installs scripts and entry-skill routing belong to the skill package itself and are not sub-agent orchestration. Abbreviated star counts are marked approximate. Review instructions, bundled code, dependencies and permissions before use; a skill format is not a guarantee of low risk or quality.*

---

## 🔌 进攻型 AI MCP Server 精选
*Offensive AI MCP Servers*

> **MCP（Model Context Protocol）**让 AI Agent 以标准化协议直接调用真实安全工具，是"进攻型 AI"从推理走向实际执行的关键基础设施——Burp、Metasploit、Nmap 等工具借此被"AI 化"。仅收录**安全工具集合类** MCP Server（非单一 Agent 项目自带的 MCP 组件）、Star ≥ 100 的仓库，按 Star 数降序排列。
> *MCP servers let AI agents invoke real security tools via a standardized protocol — the execution layer that turns offensive AI reasoning into action. Only dedicated security-tool MCP servers (excluding MCP components bundled inside a single agent project) with ≥ 100 stars are listed, sorted by stars (desc).*

| # | 仓库 | Stars | 语言 | 定位与特色 |
|---|------|-------|------|-----------|
| 1 | [0x4m4/hexstrike-ai](https://github.com/0x4m4/hexstrike-ai) <small>*⭐新补充*</small> | 13.7k | Python | 独立安全工具 MCP 桥接，授权测试中的工具接口与结果整理；由 Agent 主表交叉纳入此章，**不是本轮新发现仓库** |
| 2 | [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) <small>*⭐新补充*</small> | ≈13.5k | Python（页面未给语言占比） | IDA Pro ↔ LLM 的逆向 MCP，MIT；stdio 与 HTTP/SSE 两种传输。**区分弃用范围**：GUI 插件已“不再推荐并计划弃用”，改推同仓 `idalib-mcp`，项目整体未弃用、未归档；README 要求 IDA Pro ≥ 8.3（不支持 IDA Free），**桥接为 MIT 不代表 IDA 本体免费**。页面 Stars 为 `13.5k` 缩写 |
| 3 | [bethington/ghidra-mcp](https://github.com/bethington/ghidra-mcp) <small>*⭐新补充*</small> | ≈6.3k | Java + Python（页面未给占比） | Ghidra MCP Server，Apache-2.0；GUI 插件与 headless 双形态，支持 stdio / streamable-http，SSE 已弃用；需 Ghidra 本体（README 要求 12.2 + Java 25）。README 称 219 个工具（GUI 216 / headless 201）与批处理降 93% 调用量，均为**作者自报**，未独立复测 |
| 4 | [HexRaysSA/ida-mcp](https://github.com/HexRaysSA/ida-mcp) <small>*⭐新补充*</small> | ≈1.6k | —（页面未给语言） | **Hex-Rays 官方** IDA MCP Server（README 原文 "Official Hex-Rays IDA MCP Server"），MIT；stdio 与 Streamable HTTP，需 IDA ≥ 9.4 + idalib + Python 3.11。与上一行社区项目并存：官方项目不等于对本表其他桥接的替代或功能超集 |
| 5 | [Wh0am123/MCP-Kali-Server](https://github.com/Wh0am123/MCP-Kali-Server) | 879 | Python | Linux 终端 / 安全工具与 AI 客户端的 API 桥接，MIT；[Kali 工具页](https://www.kali.org/tools/mcp-kali-server/)收录，**软件源收录不等于官方开发或安全认证** |
| 6 | [GH05TCREW/MetasploitMCP](https://github.com/GH05TCREW/MetasploitMCP) | 765 | Python | 独立 MCP 服务通过 Metasploit RPC 管理模块、任务与测试会话；Apache-2.0，依赖外部框架 |
| 7 | [MorDavid/BloodHound-MCP-AI](https://github.com/MorDavid/BloodHound-MCP-AI) | 385 | Python | BloodHound CE / Neo4j 查询的社区 MCP 桥接，面向 AD 权限与攻击路径分析；MIT 为 README 声明，75+ 工具为作者统计，不再写“首个” |
| 8 | [w0h1v/mcp-shodan](https://github.com/w0h1v/mcp-shodan)（原 BurtTheCoder） | 191 | TypeScript | Shodan API / CVEDB 资产与漏洞信息查询，第三方社区桥接，不是 Shodan 官方服务 |
| 9 | [w0h1v/mcp-virustotal](https://github.com/w0h1v/mcp-virustotal) <small>*⭐新补充*</small> | 155 | — | VirusTotal 文件、URL、IP 与域名证据查询，MIT；为授权侦察/验证提供情报上下文，非自主漏洞利用 Agent、非 VirusTotal 官方项目 |
| 10 | [DMontgomery40/pentest-mcp](https://github.com/DMontgomery40/pentest-mcp) | 151 | TypeScript | 当前 README 为 AGPL-3.0、stdio / HTTP，SSE 禁用；范围/时间窗/白名单约束不等于网络隔离或独立生产安全认证 |

> 本轮新增 **3 个逆向工程 MCP**（`ida-pro-mcp`、`ghidra-mcp`、Hex-Rays 官方 `ida-mcp`），表由 7 → **10**；三者均需商业逆向工具本体（IDA Pro / Ghidra 服务端），桥接仓库的 MIT / Apache-2.0 **只覆盖桥接代码**，不构成对 IDA 商业许可或 Ghidra 上游的授权。三个项目的 13.5k / 6.3k / 1.6k 为页面缩写，未取得精确整数，故顺序为近似排序。
> 本轮查询 [PortSwigger/mcp-server](https://github.com/portswigger/mcp-server) 得到 **12 Stars**，低于门槛，移出精选；历史 1.1k 与当前值不能用于推断仓库重建或迁移。[FuzzingLabs/mcp-security-hub](https://github.com/FuzzingLabs/mcp-security-hub) 当前返回 404，虽[官方演讲页](https://fuzzinglabs.com/?p=12400)仍引用原地址，但未找到经核实的迁移地址，暂不列入可用清单，不填零。`nuclei-mcp`（50）、`mcp-dnstwist`（51）、`pentestMCP`（88）仍未达到门槛。
> *Three reverse-engineering MCP servers were added (7 → 10). Their permissive licenses cover the bridge code only, not the proprietary host tools. Abbreviated star counts mean the ordering is approximate, not exact. A 404 establishes only current unavailability, not deletion or a verified move.*
>
> 部署于隔离环境、限制权限和网络可达性，并核查目标授权；Skill 与 MCP 的风险取决于实际代码及权限，不能仅按资源形态排序。
> *Review actual code and permissions, isolate execution and enforce authorization. Format alone does not determine risk.*

---

## 🏆 知名 AI 攻防 / 智能渗透赛事
*Notable AI Offense-Defense & Intelligent Penetration Competitions*

> 本节收录全球范围内具有代表性的 **AI 驱动攻防 / 自主渗透** 竞技赛事，是检验 Agent 实战能力的"竞技场"，产出的开源系统往往代表当前工程实践的最高水准。
> *This section covers representative AI-driven offense-defense / autonomous penetration competitions worldwide — the "arenas" that stress-test Agent capabilities, whose open-sourced systems often represent state-of-the-art engineering practice.*

### 1. DARPA AIxCC 2025
*DARPA AI Cyber Challenge 2025 Final*

> 美国 DARPA 在 2025 年举办的 **AI Cyber Challenge（AIxCC）** 决赛中，7 支队伍各自开源了完整的 Cyber Reasoning System（CRS），代表当前自动化漏洞发现 + 修复 Agent 的最高工程水准。
> *The 7 finalist Cyber Reasoning Systems from DARPA's AI Cyber Challenge represent today's state-of-the-art in automated vulnerability discovery & patching agents.*

| 名次 / 入围 | 队伍 | CRS 系统 | Stars | 仓库 |
|:----:|------|---------|:-----:|------|
| 🥇 1 | Team Atlanta | **ATLANTIS** | 664 | [Team-Atlanta/aixcc-afc-atlantis](https://github.com/Team-Atlanta/aixcc-afc-atlantis) |
| 🥈 2 | Trail of Bits | **Buttercup** | 1.8k | [trailofbits/buttercup](https://github.com/trailofbits/buttercup) |
| 🥉 3 | Theori | **RoboDuck** | 274 | [theori-io/aixcc-afc-archive](https://github.com/theori-io/aixcc-afc-archive) |
| 决赛入围 | All You Need Is A Fuzzing Brain | **FuzzingBrain** | 152 | [o2lab/afc-crs-all-you-need-is-a-fuzzing-brain](https://github.com/o2lab/afc-crs-all-you-need-is-a-fuzzing-brain) |
| 决赛入围 | Shellphish | **ARTIPHISHELL** | 143 | [shellphish/artiphishell](https://github.com/shellphish/artiphishell) |
| 决赛入围 | 42-b3yond-6ug | **BugBuster** | 31 | [42-b3yond-6ug/42-b3yond-6ug-crs](https://github.com/42-b3yond-6ug/42-b3yond-6ug-crs) |
| 决赛入围 | Lacrosse (SIFT) | **Lacrosse CRS** | 11 | [siftech/afc-crs-lacrosse](https://github.com/siftech/afc-crs-lacrosse) |

### 2. 腾讯云智能渗透黑客松 / 智能攻防挑战赛
*Tencent Cloud Intelligent Penetration Hackathon / Intelligent Attack-Defense Challenge*

> **腾讯云安全、腾讯安全云鼎实验室（Yunding Lab）**组织的 AI 安全竞技赛事，前两届聚焦 LLM 智能体自主渗透，第三届升级为**腾讯云智能攻防挑战赛**，加入多 Agent 同场攻防和本地模型离线渗透。不同届次、赛道及线上/线下阶段的名次不可直接合并。官方入口：[赛事主页](https://zc.tencent.com/hackathon)；开源作品与往届资料：[Yeti-791/Tsec-Hackathon](https://github.com/Yeti-791/Tsec-Hackathon)（888 Stars，仓库本次抓取仍主要收录前两届）。
> *Organized by Tencent Cloud Security and Tencent Security Yunding Lab. The first two editions focused on autonomous penetration testing; the third expanded to multi-agent attack-defense and offline local-model testing. Rankings are specific to an edition, track and online/offline stage.*

| 届次 | 时间 | 获奖作品 / 阶段说明 | 参与规模与赛制 |
|:----:|------|-------------------|---------------|
| 第一届 | 2025-11 | 往届资源列出 xjtuHunter（第 2 名）、BinX（第 3 名），不将其标为冠军 | 清华大学、复旦大学、帝国理工学院、卡内基梅隆大学等国内外高校，鹏城实验室、中国科学院信息工程研究所等科研机构，以及阿里、京东、长亭等企业战队；**238 支战队、518 名选手**（沿用此前提供的赛事口径） |
| 第二届 | 2026-04 | ai小分队 / [BreachWeave](https://github.com/m-sec-org/BreachWeave)（往届资源列第 1 名）；Bytex（第 3 名） | "智能渗透主赛场 +『零界』平行赛场"双轨模式，**610 支战队、1,345 名选手**（沿用此前提供的赛事口径）；获奖机构包括绿盟、京东、天翼安全、电信、清华大学、奇盾信息等 |
| 第三届 | 2026-10；线下决赛 10-30 | **线下王座协议主赛道冠军：四川大学 alkaerr**；安全智子专项赛一等奖：金银湖队。**线上赛：[sapper-v2](https://github.com/N1nEmAn/sapper-v2)** 作者声明排名第一、80.18/100；本次未获得其官方授奖公示，不等同线下总冠军 | **634 支初赛战队**；线上十强与两支往届冠军队参加线下角逐。王座协议主赛场采用 **AI-KOH** 多 Agent 据点争夺；另设安全智子本地离线模型赛、授权真实业务智能漏洞挖掘赛 |

> 第三届来源：[腾讯安全线上十强公告](https://mp.weixin.qq.com/s?__biz=Mzg5OTE4NTczMQ&mid=2247530914&idx=1&sn=483ad6def6ad75fcda4626c635a021b3)（本次正文访问遇验证页，搜索索引显示 10-18 初赛结束及 634 队）；[赛事收官报道](https://new.qq.com/rain/a/20261110A08OVL00)；[sapper-v2 作者 README](https://github.com/N1nEmAn/sapper-v2)。成绩与 Token 消耗为特定赛场口径，不代表普遍能力排名。
> *The sapper-v2 online result is attributed to its author; the offline main-track winner is alkaerr. Public-source limitations and stage distinctions are preserved.*

### 3. 百度安全「Agent+」攻防能力挑战赛 2026
*Baidu Security Agent+ Challenge 2026*

> 2026-09-03 成都线下决赛，**ARTEX 获综合总冠军**。百度安全应急响应中心发起、多家 SRC 协办；**腾讯云鼎实验室是独家技术战略合作伙伴**，提供 TSecBench 靶场、Agent 托管运行与自动化评测，不将其笼统写作同等主办。官方公告的搜索索引显示 150 余支报名队伍、8 支晋级决赛队伍；综合评审获奖不等同靶场单项跑分第一。
> *ARTEX won the overall final in Chengdu on 2026-09-03. Baidu Security initiated the event with partner SRCs; Tencent Security Yunding Lab provided the range, agent hosting and automated evaluation as the exclusive strategic technology partner. Overall judging and range-only scores are distinct.*

| 作品 | 当前状态 | 来源 |
|------|----------|------|
| **ARTEX / Artex** <small>*⭐新补充*</small> | 曾公开的自主渗透项目；[原仓库](https://github.com/Autumn-27/ARTEX)本次不可公开访问。微步 2026-11-06 声明确认 10-08 闭源，历史开源版受 AGPL-3.0 约束；**Artex Pro** 为经 RedAgents 提供的企业商用版。不开列不可核验的原仓库 Stars，不把非官方 fork 计为官方项目 | [百度安全决赛公告](https://mp.weixin.qq.com/s?__biz=MjM5MTAwNzUzNQ&mid=2650512227&idx=1&sn=9acc4a9bf87086d58fbcfdbc06470cc6)（正文验证受限，赛事信息据公告搜索索引）；[微步官方版权声明](https://threatbook.cn/threatbookNews/fcd1bd02-0d7e-4736-abfd-22fdbce6f4c1)；[商用产品页](https://threatbook.cn/redagents) |

---

## 📑 相关学术论文
*Related Academic Papers (grouped by topic; within each group, newest first)*

> 来源交叉检索：[tmylla/Awesome-LLM4Cybersecurity](https://github.com/tmylla/Awesome-LLM4Cybersecurity/blob/main/LITERATURES.md)、[simon-p-j-r/LLM4Pentest](https://github.com/simon-p-j-r/LLM4Pentest)，新增内容回查论文原文。本轮补充 **5 篇**，并修订 PentestEval / ARTEMIS 的来源与状态；**不声称重新逐篇核验全部存量论文**。现收录 **121 篇**：
> - **A. 渗透测试 & 红队 Agent**（64 篇）
> - **B. 漏洞挖掘 / 利用 / 修复**（20 篇）
> - **C. 评测基准 & 训练方法 & 综述 & 奠基**（37 篇）
>
> 时间以 arXiv v1 / 首发日期为准，后续修订另注；仅有年份的存量条目不补造月份。<small>*⭐新补充*</small> = 本轮新增（2026-11-18），ⓝ 为历史补充。预印本、正式录用及作者自报结果分别表述，论文修订日期不改变首次发表排序。
>
> *The paper list totals **139**: (A) Pentesting & Red-Team Agents (70), (B) Vulnerability Research/Repair (20), (C) Evaluation/Training/Surveys & Foundational (39), and (D) Honeypots, Cyber Deception & Anti-LLM-Attacker Defenses (10, defensive side). Existing entries were not all re-audited this round. First submission dates and later revisions are distinguished; publisher-reported results are not independent replication.*

### A. 渗透测试 & 红队 Agent
*Pentesting & Red-Team Agents*

| # | 时间 | 论文 | 作者 / 机构 | 发表渠道 | 关联项目 / 主题 |
|---|------|------|-----------|---------|---------------|
| A1 | 2026-09 | [Big Enough to Break Out: Tracking the Rising Capability of LLM Penetration-Testing Agents](https://arxiv.org/abs/2609.10780) <small>*⭐新补充*</small> | Victoria Lovelace et al. | arXiv（v1 09-09） | 跟踪渗透 Agent 能力变化与规划瓶颈；本轮补漏，不把预印本表述为独立认证 |
| A2 | 2026-09 | [Staying on the Attack Path: Structured State for Long-Horizon Automated Penetration Testing](https://arxiv.org/abs/2609.07344) <small>*⭐新补充*</small> | Weizhe Wang et al. | arXiv（v1 09-07；v2 09-18） | 事实—意图 DAG 持久状态，降低长任务上下文丢失；按首次提交日期排列 |
| A3 | 2026-08 | [On the Adversarial Planning Capabilities of LLMs](https://doi.org/10.1007/978-3-032-35579-9_4) <small>*⭐新补充*</small> | Bikash Saha, Nanda Rani, Sandeep Kumar Shukla | ARES 2026 International Workshops（Linköping，08-24 出版，pp. 59-78） | 实证 LLM 在攻击规划上的能力边界；属规划能力评估，不外推为端到端渗透效果 |
| A4 | 2026-08 | [MazeRunner: Nonlinear Task and Clue Orchestration for LLM-driven Black-Box Automated Penetration Testing](https://arxiv.org/abs/2608.14216) <small>*⭐新补充*</small> | Zhenyuan Li, Yi Jiang, Junjie Cheng, Yaokun Li et al. | arXiv（v1 08-14，仅一版） | 三 Agent 分工做任务/线索编排；10 个新发 HTB 目标、单次 2,000 万 token 上限下 Sonnet 4.5 完成 47.7% 标注子任务（PentestGPT-V2 36.2%、Claude Code 34.2%），6 台取得 user 级或更高（含 2 台 root）；页面未给代码链接 |
| A5 | 2026-07 | [A Survey of LLM-Driven Penetration Testing: Taxonomy, Co-Evolution, and Open Challenges](https://arxiv.org/abs/2607.02605) | Zheyuan He et al. | arXiv | 系统综述 81 篇文献：Agents4Pentest 分类学与四阶段架构演进（RLVR 转折） |
| A6 | 2026-07 | [Intelligent Penetration Testing Through Integrated Knowledge Graph and Historical Decision Enhancement](https://doi.org/10.1109/TDSC.2026.3694384) | Qianyu Li | IEEE TDSC 2026 | 知识图谱 + 历史决策增强的智能渗透 |
| A7 | 2026-06 | [ZERO-APT: A Closed-Loop Adversarial Framework for LLM-Driven Automated Penetration Testing under Intelligent Defense](https://arxiv.org/abs/2606.05567) | Anlan Zheng, Tiantian Zhu | arXiv | 攻击者-防御者-裁判回合制闭环，含实时智能防御 |
| A8 | 2026-05 | [CyberEvolver: Structured Self-Evolution for Cybersecurity Agents On the Fly](https://arxiv.org/abs/2605.26195) <small>*⭐新补充*</small> | Yihe Fan, Changyi Li, Lichen Xu, Xudong Pan et al. | arXiv（v1 05-25；v2 06-16） | 用失败执行轨迹迭代改写自身 scaffold，CTF / 漏洞利用 / 渗透三类任务成功率平均 +13.6%，优于 6 个人工设计的安全 Agent |
| A9 | 2026-05 | [APT-Agent: Automated Penetration Testing using Large Language Models](https://arxiv.org/abs/2605.24949) | William Guanting Li et al. | arXiv | 幻觉矫正 + 命令记忆，Metasploitable 2 端到端成功率 84.29% |
| A10 | 2026-05 | [Pen-Strategist: A Reasoning Framework for Penetration Testing Strategy Formation and Analysis](https://arxiv.org/abs/2605.04499) | Yasod Ginige et al. | arXiv | RL 微调策略推理模型，策略推导 +87%、子任务 +47.5% |
| A11 | 2026-05 | [From Intent to Invocation: A Reasoning-First Framework for Natural Language to Penetration Testing Commands](https://doi.org/10.1109/ICASSP55912.2026.11464572) | He Kong et al. | ICASSP 2026 | 自然语言 → 渗透命令的推理优先框架 |
| A12 | 2026-04 | [Hackers or Hallucinators? A Comprehensive Analysis of LLM-Based Automated Penetration Testing](https://arxiv.org/abs/2604.05719) | Jiaren Peng et al. | arXiv | [simon-p-j-r/LLM4Pentest](https://github.com/simon-p-j-r/LLM4Pentest)：SoK + 13 框架统一基准实测（超 100 亿 token） |
| A13 | 2026-04 | [Automation-Exploit: A Multi-Agent LLM Framework for Adaptive Offensive Security with Digital Twin-Based Risk-Mitigated Exploitation](https://arxiv.org/abs/2604.22427) | Biagio Andreucci, Arcangelo Castiglione | arXiv | 数字孪生隔离调试的"风险缓解型"多 Agent 黑盒攻击链 |
| A14 | 2026-03 | [Red-MIRROR: Agentic LLM-based Autonomous Penetration Testing with Reflective Verification and Knowledge-augmented Interaction](https://arxiv.org/abs/2603.27127) | Tran Vy Khang et al. | arXiv | 记忆-反思骨干 + RAG，XBOW 基准 86% |
| A15 | 2026-03 | [STRIATUM-CTF: A Protocol-Driven Agentic Framework for General-Purpose CTF Solving](https://arxiv.org/abs/2603.22577) | James Hugglestone et al. | arXiv | MCP 协议驱动通用 CTF Agent，真实赛事击败 21 支人类战队夺冠 |
| A16 | 2026-03 | [Towards Reliable Local Security Agents: Verifiable Post-Training for Linux Privilege Escalation](https://arxiv.org/abs/2603.17673) | Philipp Normann, Andreas Happe et al. | arXiv | SFT+RLVR 后训练 4B 本地模型，Linux 提权 93.3%、成本降 80× |
| A17 | 2026-03 | [PTFusion: LLM-driven context-aware knowledge fusion for web penetration testing](https://www.sciencedirect.com/science/article/pii/S1566253525007936) | Wang et al. | Information Fusion 2026 | 上下文感知知识融合的 Web 渗透策略规划 |
| A18 | 2026-03 | [Building adaptative and transparent cyber agents with local language models](https://doi.org/10.1016/j.eswa.2025.129987) | Maria Rigaki | Expert Systems with Applications 2026 | 本地 LLM 构建自适应、可解释攻击 Agent |
| A19 | 2026-02 | [AWE: Adaptive Agents for Dynamic Web Penetration Testing](https://www.ndss-symposium.org/ndss-paper/auto-draft-680/) | Akshat Singh Jaswal et al. | NDSS 2026 | [stuxlabs/AWE](https://github.com/stuxlabs/AWE)：记忆增强多 Agent 动态 Web 渗透 |
| A20 | 2026-02 | [What Makes a Good LLM Agent for Real-world Penetration Testing?](https://arxiv.org/abs/2602.17622) | Gelei Deng et al. | arXiv | Excalibur：难度感知规划 + 证据引导攻击树搜索，GOAD 攻陷 4/5 主机 |
| A21 | 2026-02 | [LLMs as Hackers: Autonomous Linux Privilege Escalation Attacks](https://doi.org/10.1007/s10664-025-10758-3) | Andreas Happe | Empirical Software Engineering 2026 | 自主 Linux 提权攻击实证 |
| A22 | 2026-02 | [Context Relay for Long-Running Penetration-Testing Agents](https://www.ndss-symposium.org/?p=23943) <small>*⭐新补充*</small> | Marius Vangeli, Joel Brynielsson, Mika Cohen, Farzad Kamrani（KTH / FOI） | NDSS Workshop LAST-X 2026（录用名单） | CHAP：把压缩后的状态接力给新 Agent 实例，缓解长任务上下文上限；配套框架为 [marvang/ctf-agent](https://github.com/marvang/ctf-agent)，与 Agent 表中的 `verialabs/ctf-agent` **不是同一仓库**。页面未提供论文 PDF 直链 |
| A23 | 2026-01 | [PenForge: On-the-Fly Expert Agent Construction for Automated Penetration Testing](https://arxiv.org/abs/2601.06910) | Huihui Huang et al. | ICSE-NIER 2026 | 动态构造领域专家 Agent，CVE-Bench 零日设定 30%（SOTA 3×） |
| A24 | 2026-01 | [WiFiPenTester: Advancing Wireless Ethical Hacking with Governed GenAI](https://arxiv.org/abs/2601.23092) | Haitham S. Al-Sinani, Chris J. Mitchell | arXiv | 治理型 GenAI 无线渗透（人在回路） |
| A25 | 2026-01 | [CTFAgent: An LLM-powered Agent for CTF Challenge Solving](https://doi.org/10.1016/j.jisa.2025.104305) | Yuwen Zou | JISA 2026 | LLM 驱动 CTF 解题 Agent |
| A26 | 2026 | [AI-Driven Penetration Testing for ARM Systems: Experimental Evaluation and Deployment Framework Across Four Paradigms](https://doi.org/10.1109/ACCESS.2026.3687448) | Matthew Ragsdale | IEEE Access 2026 | ARM 平台四范式 AI 渗透评估 |
| A27 | 2025-12 | [PentestEval: Benchmarking LLM-based Penetration Testing with Modular and Stage-Level Design](https://arxiv.org/abs/2512.14233) ⓝ | Ruozhao Yang et al. | arXiv（v1 2025-12-16；v2 2026-11-02） | 六阶段建模、五阶段评分，346 任务；[公开仓库](https://github.com/Richael-y/PentestEval)为演示版，非已验证完整复现 |
| A28 | 2025-12 | [Comparing AI Agents to Cybersecurity Professionals in Real-World Penetration Testing](https://arxiv.org/abs/2512.09882) ⓝ | Justin W. Lin et al.（Stanford） | arXiv（v1 2025-12-10；v2 2026-03-03；正式录用待核） | [ARTEMIS](https://github.com/Stanford-Trinity/ARTEMIS)：真实环境人与 Agent 对照；结果与较高误报率均限定该实验，不直接推导普遍超越人类 |
| A29 | 2025-12 | [Automated Penetration Testing with LLM Agents and Classical Planning](https://arxiv.org/abs/2512.11143) | Lingzhi Wang et al. | arXiv | CHECKMATE：经典规划作外置"结构化大脑"，超 Claude Code 20% |
| A30 | 2025-11 | [Controller Makes Pentesting Better: An Improved Multi-Agent Automated Penetration Testing Framework](https://ieeexplore.ieee.org/document/11354714) | Geng et al. | IEEE TrustCom 2025 | Controller 跨阶段调度多 Agent 渗透 |
| A31 | 2025-11 | [Automated tactics planning for cyber attack and defense based on large language model agents](https://doi.org/10.1016/j.neunet.2025.107842) | Yimo Ren | Neural Networks 2025 | LLM Agent 攻防战术自动规划 |
| A32 | 2025-10 | [AutoPentester: An LLM Agent-based Framework for Automated Pentesting](https://arxiv.org/abs/2510.05605) ⓝ | Yasod Ginige et al. | IEEE TrustCom 2025 | 全自动渗透，子任务完成率较 PentestGPT +27% |
| A33 | 2025-09 | [xOffense: An Autonomous Multi-Agent Framework for Penetration Testing with Domain-Adapted Large Language Models](https://arxiv.org/abs/2509.13021) | Phung Duc Luong et al. | arXiv | 微调 Qwen3-32B 多 Agent，子任务 79.17% |
| A34 | 2025-09 | [Guided Reasoning in LLM-Driven Penetration Testing Using Structured Attack Trees](https://arxiv.org/abs/2509.07939) ⓝ | Katsuaki Nakano et al. | arXiv | MITRE ATT&CK 攻击树约束推理，查询量大幅下降 |
| A35 | 2025-09 | [PentestMCP: LLM and MCP Based Multi-Agent Framework for Automated Penetration Testing](https://doi.org/10.21203/rs.3.rs-7582841/v1) | Jiqiang Zhai et al. | Research Square（预印本·在审） | LLM + MCP + RAG 端到端自动渗透 |
| A36 | 2025-08 | [Multi-Agent Penetration Testing AI for the Web (MAPTA)](https://arxiv.org/abs/2508.20816) | Isaac David, Arthur Gervais | arXiv | [arthurgervais/mapta](https://github.com/arthurgervais/mapta)：XBOW 76.9%，10 项发现进入 CVE 评审 |
| A37 | 2025-08 | [Chimera: Harnessing Multi-Agent LLMs for Automatic Insider Threat Simulation](https://arxiv.org/abs/2508.07745) | — | NDSS 2026 | [fish98/Chimera](https://github.com/fish98/Chimera)：多 Agent 内部威胁自动化模拟 |
| A38 | 2025-08 | [Perses: Unlocking Privilege Escalation for Small LLMs via Extensible Heterogeneity](https://doi.org/10.1145/3708821.3736189) <small>*⭐新补充*</small> | Dominik M. Weber, Ioannis Tzachristas, Aifen Sui | AsiaCCS 2025（Hanoi，pp. 344-357） | 以可扩展异构让小模型完成提权利用，降低对超大模型的依赖 |
| A39 | 2025-08 | [CurriculumPT: LLM-Based Multi-Agent Autonomous Penetration Testing with Curriculum-Guided Task Scheduling](https://www.mdpi.com/2076-3417/15/16/9096) | Xingyu Wu et al. | Applied Sciences 2025 | 课程式由易到难任务调度 + 经验知识库 |
| A40 | 2025-08 | [Pentest-R1: Towards Autonomous Penetration Testing Reasoning Optimized via Two-Stage RL](https://arxiv.org/abs/2508.07382) ⓝ | He Kong et al. | arXiv | 离线+在线两阶段 RL，8B 模型比肩 GPT-4o |
| A41 | 2025-08 | [Automated penetration testing: Formalization and realization](https://doi.org/10.1016/j.cose.2025.104454) | Charilaos Skandylas | Computers & Security 2025 | 自动化渗透测试的形式化与实现 |
| A42 | 2025-07 | [PenTest2.0: Towards Autonomous Privilege Escalation Using GenAI](https://arxiv.org/abs/2507.06742) ⓝ | Haitham S. Al-Sinani, Chris J. Mitchell | arXiv | RAG + CoT + 任务树自主提权 |
| A43 | 2025-07 | [On the Surprising Efficacy of LLMs for Penetration-Testing](https://arxiv.org/abs/2507.00829) ⓝ | Andreas Happe, Jürgen Cito | arXiv | LLM 渗透有效性实证（含恶意采用视角） |
| A44 | 2025-05 | [AutoPentest: Enhancing Vulnerability Management With Autonomous LLM Agents](https://arxiv.org/abs/2505.10321) ⓝ | Julius Henke | arXiv | GPT-4o + LangChain 黑盒渗透 |
| A45 | 2025-05 | [RedTeamLLM: an Agentic AI framework for offensive security](https://arxiv.org/abs/2505.06913) | Brian Challita, Pierre Parrend | arXiv | 总结-推理-行动循环，含错误恢复 |
| A46 | 2025-05 | [RefPentester: A Knowledge-Informed Self-Reflective Penetration Testing Framework Based on Large Language Models](https://arxiv.org/abs/2505.07089) | Hanzheng Dai et al. | arXiv | [ipa-lab/hackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT)：七状态机自反思渗透 |
| A47 | 2025-04 | [CAI: An Open, Bug Bounty-Ready Cybersecurity AI](https://arxiv.org/abs/2504.06017) ⓝ | Víctor Mayoral-Vilches et al.（aliasrobotics） | arXiv | [aliasrobotics/cai](https://github.com/aliasrobotics/cai)：首个网络安全自主等级分类 |
| A48 | 2025-02 | [Construction and Evaluation of LLM-based agents for Semi-Autonomous penetration testing](https://arxiv.org/abs/2502.15506) ⓝ | Masaya Kobayashi et al. | arXiv | 多 LLM 模块半自主渗透 |
| A49 | 2025-02 | [RapidPen: Fully Automated IP-to-Shell Penetration Testing with LLM-based Agents](https://arxiv.org/abs/2502.16730) ⓝ | Sho Nakatani（SecDevLab） | arXiv | IP→Shell 全自动，单次 $0.3-0.6 |
| A50 | 2025-02 | [PenTest++: Elevating Ethical Hacking with AI and Automation](https://arxiv.org/abs/2502.09484) ⓝ | Haitham S. Al-Sinani, Chris J. Mitchell | arXiv | 道德黑客 AI 自动化升级 |
| A51 | 2025-02 | [Can LLMs Hack Enterprise Networks? Autonomous Assumed Breach Penetration-Testing Active Directory Networks](https://arxiv.org/abs/2502.04227) | Andreas Happe, Jürgen Cito | ACM TOSEM 2025 | [andreashappe/cochise](https://github.com/andreashappe/cochise)：GOAD 全自主 AD 渗透 |
| A52 | 2025-02 | [D-CIPHER: Dynamic Collaborative Intelligent Multi-Agent System with Planner and Heterogeneous Executors for Offensive Security](https://arxiv.org/abs/2502.10931) | Meet Udeshi et al.（NYU） | arXiv | [NYU-LLM-CTF/nyuctf_agents](https://github.com/NYU-LLM-CTF/nyuctf_agents)：Planner-Executor 架构 |
| A53 | 2025-02 | [ARACNE: An LLM-Based Autonomous Shell Pentesting Agent](https://arxiv.org/abs/2502.18528) | Tomas Nieponice et al. | arXiv | 多 LLM 自主 Shell 渗透，OTW Bandit 57.58% |
| A54 | 2025-01 | [Incalmo: An Autonomous LLM-assisted System for Red Teaming Multi-Host Networks](https://arxiv.org/abs/2501.16466) | Brian Singer et al.（CMU） | arXiv | 多主机红队，MHBench 40 网络 37 成功 |
| A55 | 2025-01 | [VulnBot: Autonomous Penetration Testing for A Multi-Agent Collaborative Framework](https://arxiv.org/abs/2501.13411) | He Kong et al. | arXiv | [KHenryAegis/VulnBot](https://github.com/KHenryAegis/VulnBot)：渗透任务图 PTG |
| A56 | 2024-12 | [HackSynth: LLM Agent and Evaluation Framework for Autonomous Penetration Testing](https://arxiv.org/abs/2412.01778) | Lajos Muzsai et al.（ELTE） | arXiv | [aielte-research/HackSynth](https://github.com/aielte-research/HackSynth)：PicoCTF/OTW 200 题 |
| A57 | 2024-12 | [Hacking CTFs with Plain Agents](https://arxiv.org/abs/2412.02776) ⓝ | Rustem Turtayev et al. | arXiv | 朴素 Agent 饱和 InterCode-CTF（95%） |
| A58 | 2024-11 | [PentestAgent: Incorporating LLM Agents to Automated Penetration Testing](https://arxiv.org/abs/2411.05185) | Xiangmin Shen et al. | AsiaCCS 2025 | [GH05TCREW/pentestagent](https://github.com/GH05TCREW/pentestagent) |
| A59 | 2024-11 | [AutoPT: How Far Are We from the End2End Automated Web Penetration Testing?](https://arxiv.org/abs/2411.01236) ⓝ | Benlong Wu et al. | arXiv | 渗透状态机 PSM，任务完成 22%→41% |
| A60 | 2024-09 | [BreachSeek: A Multi-Agent Automated Penetration Tester](https://arxiv.org/abs/2409.03789) | Ibrahim Alshehri et al. | arXiv | LangGraph 多 Agent 渗透 |
| A61 | 2024-09 | [Hacking, The Lazy Way: LLM Augmented Pentesting](https://arxiv.org/abs/2409.09493) ⓝ | Dhruva Goyal et al. | arXiv | [bugbasesecurity/pentest-copilot](https://github.com/bugbasesecurity/pentest-copilot)：浏览器内 LLM 增强渗透 |
| A62 | 2024-09 | [EnIGMA: Interactive Tools Substantially Assist LM Agents in Finding Security Vulnerabilities](https://arxiv.org/abs/2409.16165) | Talor Abramovich et al.（NYU） | ICML 2025 | 交互式工具（gdb 等）CTF Agent，识别"独白"幻觉现象 |
| A63 | 2024-08 | [CIPHER: Cybersecurity Intelligent Penetration-testing Helper for Ethical Researcher](https://arxiv.org/abs/2408.11650) ⓝ | Derry Pratama et al. | Sensors 2024 | 300+ writeup 训练的渗透垂域模型 + FARR 基准 |
| A64 | 2024-08 | [ChainReactor: Automated Privilege Escalation Chain Discovery via AI Planning](https://www.usenix.org/conference/usenixsecurity24/presentation/de-pasquale) | Giulio De Pasquale et al. | USENIX Security 2024 | PDDL 经典规划（非 LLM）自动提权链发现 |
| A65 | 2024-07 | [PenHeal: A Two-Stage LLM Framework for Automated Pentesting and Optimal Remediation](https://arxiv.org/abs/2407.17788) ⓝ | Junjie Huang, Quanyan Zhu | ACSW 2024 | 两阶段：渗透 + 最优修复 |
| A66 | 2024-07 | [From Sands to Mansions: Towards Automated Cyberattack Emulation with Classical Planning and Large Language Models](https://arxiv.org/abs/2407.16928) ⓝ | Lingzhi Wang et al. | ACNS 2026 | Aurora：CTI 报告→攻击链自动编排（250 报告数据集） |
| A67 | 2024-03 | [AutoAttacker: A Large Language Model Guided System to Implement Automatic Cyber-attacks](https://arxiv.org/abs/2403.01038) | Jiacen Xu et al.（UC Irvine） | arXiv | 后渗透"hands-on-keyboard"自动化攻击 |
| A68 | 2023-08 | [PentestGPT: An LLM-empowered Automatic Penetration Testing Tool](https://arxiv.org/abs/2308.06782) | Gelei Deng et al.（NTU） | USENIX Security 2024 | [GreyDGL/PentestGPT](https://github.com/GreyDGL/PentestGPT)：奠基之作 |
| A69 | 2023-08 | [Using Large Language Models for Cybersecurity Capture-The-Flag Challenges and Certification Questions](https://arxiv.org/abs/2308.10443) <small>*⭐新补充*</small> | Wesley Tann, Yuancheng Liu, Jun Heng Sim, Choon Meng Seah | arXiv（v1 08-21，仅一版） | 早期能力评估：ChatGPT / Bard / Bing 在 Cisco 认证问答与 CTF 上的表现，并讨论越狱提示与学术诚信影响；属评测而非攻击框架 |
| A70 | 2023-07 | [Getting pwn'd by AI: Penetration Testing with Large Language Models](https://arxiv.org/abs/2308.00121) | Andreas Happe, Jürgen Cito（TU Wien） | ESEC/FSE 2023 | 奠基论文，hackingBuddyGPT 前身 |

### B. 漏洞挖掘 / 利用 / 修复
*Vulnerability Discovery / Exploitation / Repair*

| # | 时间 | 论文 | 作者 / 机构 | 发表渠道 | 关联项目 / 主题 |
|---|------|------|-----------|---------|---------------|
| B1 | 2026-05 | [FuzzingBrain V2: A Multi-Agent LLM System for Automated Vulnerability Discovery and Reproduction](https://arxiv.org/abs/2605.21779) | Ze Sheng et al. | arXiv | 构建于 OSS-Fuzz，实战挖出 29 个 0day（2 个获 CVE），AIxCC 数据集 90% 检出 |
| B2 | 2026-02 | [FirmAgent: Leveraging Fuzzing to Assist LLM Agents with IoT Firmware Vulnerability Discovery](https://www.ndss-symposium.org/ndss-paper/firmagent-leveraging-fuzzing-to-assist-llm-agents-with-iot-firmware-vulnerability-discovery) | Jiangan Ji et al.（清华/信息工程大学） | NDSS 2026 | [AxiaoJJ/FirmAgent](https://github.com/AxiaoJJ/FirmAgent)：Fuzzing + 双 LLM Agent 的 IoT 固件漏洞发现与 PoC 生成 |
| B3 | 2025-10 | [LLM Agents for Automated Web Vulnerability Reproduction: Are We There Yet?](https://arxiv.org/abs/2510.14700) ⓝ | Bin Liu et al. | arXiv | 20 个 Agent × 80 真实 CVE 漏洞复现实证 |
| B4 | 2025-09 | [VulnRepairEval: An Exploit-Based Evaluation Framework for Assessing LLM Vulnerability Repair](https://arxiv.org/abs/2509.03331) ⓝ | Weizhe Wang et al. | arXiv | 基于 PoC exploit 的修复评测（12 LLM，最高仅 21.7%） |
| B5 | 2025-09 | [All You Need Is A Fuzzing Brain: An LLM-Powered System for Automated Vulnerability Detection and Patching](https://arxiv.org/abs/2509.07225) ⓝ | Ze Sheng et al.（o2lab） | arXiv | AIxCC 决赛第 4 名 CRS 论文，28 漏洞（含 6 个 0day），附公开榜单 |
| B6 | 2025-09 | [LLM-Driven SAST-Genius: A Hybrid Static Analysis Framework for Comprehensive and Actionable Security](https://arxiv.org/abs/2509.15433) ⓝ | Vaibhav Agrawal, Kiarash Ahi | arXiv | SAST + LLM 混合静态分析，误报降约 91% |
| B7 | 2025-09 | [ATLANTIS: AI-driven Threat Localization, Analysis, and Triage Intelligence System](https://arxiv.org/abs/2509.14589) ⓝ | Taesoo Kim et al.（Team Atlanta） | arXiv | AIxCC 决赛冠军 CRS 论文（符号执行 + 定向 fuzz + LLM） |
| B8 | 2025-08 | [Prompt to Pwn: Automated Exploit Generation for Smart Contracts](https://arxiv.org/abs/2508.01371) ⓝ | ZeKe Xiao et al. | ACISP 2026 | ReX 框架：LLM + Foundry 端到端智能合约 Exploit 生成 |
| B9 | 2025-07 | [LLMxCPG: Context-Aware Vulnerability Detection Through Code Property Graph-Guided Large Language Models](https://arxiv.org/abs/2507.16585) ⓝ | Ahmed Lekssays et al. | USENIX Security 2025 | CPG 切片 + LLM，代码量降 67-91%、F1 +15-40% |
| B10 | 2025-07 | [MalCodeAI: Autonomous Vulnerability Detection and Remediation via Language Agnostic Code Reasoning](https://arxiv.org/abs/2507.10898) ⓝ | Jugal Gajjar et al. | IEEE IRI 2025 | 跨 14 语言漏洞检测 + 修复（LoRA 微调 Qwen2.5-Coder-3B） |
| B11 | 2025-07 | [PwnGPT: Automatic Exploit Generation Based on Large Language Models](https://aclanthology.org/2025.acl-long.562/) ⓝ | Wanzong Peng et al. | ACL 2025 | CTF 二进制 pwn 自动 Exploit 生成（分析-生成-验证三模块） |
| B12 | 2025-05 | [VADER: A Human-Evaluated Benchmark for Vulnerability Assessment, Detection, Explanation, and Remediation](https://arxiv.org/abs/2505.19395) ⓝ | Ethan TS. Liu et al. | arXiv | 漏洞处理四维人评基准（174 真实漏洞） |
| B13 | 2025-04 | [CVE-Bench (NAACL): Benchmarking LLM-based Software Engineering Agent's Ability to Repair Real-World CVE Vulnerabilities](https://aclanthology.org/2025.naacl-long.212/) ⓝ | Peiran Wang et al. | NAACL 2025 | 509 个真实 CVE 修复评测（注：与 ICML 版同名不同任务） |
| B14 | 2025-03 | [CVE-Bench: A Benchmark for AI Agents' Ability to Exploit Real-World Vulnerabilities](https://arxiv.org/abs/2503.17332) | Yuxuan Zhu et al.（UIUC Kang Lab） | ICML 2025 | [uiuc-kang-lab/cve-bench](https://github.com/uiuc-kang-lab/cve-bench)：真实 Web CVE 利用评测 |
| B15 | 2025-03 | [CASTLE: Benchmarking Dataset for Static Code Analyzers and LLMs towards CWE Detection](https://arxiv.org/abs/2503.09433) ⓝ | Richard A. Dubniczky et al. | arXiv | 25 类 CWE × 250 微基准程序 |
| B16 | 2024-10 | [HonestCyberEval: An AI Cyber Risk Benchmark for Automated Software Exploitation](https://arxiv.org/abs/2410.21939) ⓝ | Dan Ristea, Vasilios Mavroudis | arXiv | 自动化利用能力风险基准（o1-preview 92.85%） |
| B17 | 2024-07 | [eyeballvul: a future-proof benchmark for vulnerability detection in the wild](https://arxiv.org/abs/2407.08708) ⓝ | Timothee Chauvin | arXiv | 每周更新、防训练泄漏的漏洞检测基准 |
| B18 | 2024-06 | [Teams of LLM Agents can Exploit Zero-Day Vulnerabilities](https://arxiv.org/abs/2406.01637) | Yuxuan Zhu et al.（UIUC） | arXiv | HPTSA：规划 Agent + 子 Agent 协作 0day 利用（+4.3×） |
| B19 | 2024-04 | [LLM Agents can Autonomously Exploit One-day Vulnerabilities](https://arxiv.org/abs/2404.08144) | Richard Fang et al.（UIUC） | arXiv | GPT-4 给定 CVE 描述利用 87%，无描述仅 7% |
| B20 | 2024-02 | [LLM Agents can Autonomously Hack Websites](https://arxiv.org/abs/2402.06664) | Richard Fang et al.（UIUC） | arXiv | 早期工作：GPT-4 自主盲注/SQLi 攻击网站 |

### C. 评测基准 & 训练方法 & 综述 & 奠基
*Evaluation Benchmarks, Training Methods, Surveys & Foundational*

| # | 时间 | 论文 | 作者 / 机构 | 发表渠道 | 关联项目 / 主题 |
|---|------|------|-----------|---------|---------------|
| C1 | 2026-10 | [CyberArena: Benchmarking AI Agents in Live Symmetric Attack-and-Defense Combat](https://arxiv.org/abs/2610.19005) <small>*⭐新补充*</small> | Bangya Liu et al. | arXiv（v1 10-13） | [项目主页](https://cyber-arena.ai)：40 挑战、466 有效对局的实时对称攻防；[网站仓库](https://github.com/cyber-arena-ai/cyber-arena)不是评测引擎 |
| C2 | 2026-10 | [KaliBench: A Fine-Grained Benchmark for Cybersecurity Tool Use on Kali Linux with Runtime-Free Verifiable Rewards](https://arxiv.org/abs/2610.02206) <small>*⭐新补充*</small> | Pengfei Li, Naufal Suryanto, Sicheng Zhang, Muzammal Naseer（Khalifa University / UWA） | NeurIPS 2026 Evaluations & Datasets Track（arXiv v1 10-01） | 8,504 条 NL→CLI query–command 对、1,642 工具、23 能力维度、5 安全阶段；训练 3,504 / 测试 5,000。**评的是单条命令的工具选择与参数构造，不是端到端渗透完成率**；unrestricted / restricted / hinted 三设置，论文结论为开源权重在 unrestricted 下 exact-command 均未超 42%。代码与数据实际公开，但仓库**无 LICENSE 文件**，arXiv 的 CC BY 4.0 仅覆盖论文文本 |
| C3 | 2026-09 | [Toward Secure AI-Powered Penetration Testing Agents: Security Threats, Guardrails, and Architectural Perspectives](https://arxiv.org/abs/2609.16694) <small>*⭐新补充*</small> | Rahul Dev T Y et al. | arXiv（v1 09-15） | 渗透 Agent 自身运行安全、威胁与架构护栏；非 LLM 越狱技术清单 |
| C4 | 2026-09 | [Feyospace-v1: How the Cyber Mercury Seven Trained Frontier Cyber Models](https://arxiv.org/abs/2609.08418) <small>*⭐新补充*</small> | Zongjie Li et al. | arXiv（v1 09-08） | 164,269 条执行验证轨迹的训练框架；家族评测与公开 small checkpoint 分别看待 |
| C5 | 2026-08 | [RangeFactory: Scalable Construction of Multi-Hop Cyber Ranges](https://arxiv.org/abs/2608.09526) | Hanlin Jiang et al.（北大） | arXiv | 多跳靶场自动编排，RangeBench 1,148 实例 × 287 攻击链 |
| C6 | 2026-08 | [CyberForge: Verified Vulnerability Injection at Repository Level for Cybersecurity Agent Training](https://arxiv.org/abs/2608.06471) | Amine Lbath et al.（NIST/UMD） | arXiv | [Cyb3rForge/CyberForge](https://github.com/Cyb3rForge/CyberForge)：仓库级漏洞注入合成训练数据（1,034 实例） |
| C7 | 2026-07 | [Baselines Before Architecture: Evaluating Coding Agents for Autonomous Penetration Testing](https://arxiv.org/abs/2607.13085) | Ananda Dhakal et al. | arXiv | 同模型 plain-agent 基线对照，质疑安全 harness 增益归因 |
| C8 | 2026-06 | [AgentCyberRange: Benchmarking Frontier AI Systems in Realistic Cyber Ranges](https://arxiv.org/abs/2606.14295) | Fengyu Liu et al.（复旦） | arXiv | [AgentCyberRange](https://github.com/AgentCyberRange)：110 漏洞 × 8 企业级靶场，GPT-5.5+Codex 最优 |
| C9 | 2026-06 | [CyberGym-E2E: Scalable Real-World Benchmark for AI Agents' End-to-End Cybersecurity Capabilities](https://arxiv.org/abs/2606.04460) | Tianneng Shi et al.（UC Berkeley） | ICML 2026 | 920 真实漏洞端到端（发现→PoC→补丁） |
| C10 | 2026-05 | [CTFusion: A CTF-based Benchmark for LLM Agent Evaluation](https://arxiv.org/abs/2605.11504) | Dongjun Lee, Ga-eun Bae, Insu Yun | ICML 2026 AIWILD Workshop | 基于 Live CTF 的流式评测，抗数据污染/作弊 |
| C11 | 2026-05 | [ExploitGym: Can AI Agents Turn Security Vulnerabilities into Real Attacks?](https://arxiv.org/abs/2605.11086) | Zhun Wang et al.（UC Berkeley） | arXiv | 898 实例"漏洞→利用"基准（用户态/V8/内核），Claude Mythos Preview 157 题 |
| C12 | 2026-05 | [How Reliable Are AI Attackers Against a Fixed Vulnerable Target? A 400-Run Empirical Study of LLM Penetration Testing Consistency](https://arxiv.org/abs/2605.30096) | Galip Tolga Erdem | arXiv | 4 模型 × 100 次同目标攻击一致性实证 |
| C13 | 2026-04 | [Autonomous LLM Agents & CTFs: A Second Look](https://arxiv.org/abs/2605.21497) | Youness Bouchari et al. | EuroS&P 2026 Workshop | 复检"接近人类"论断：claude-code 通用 Agent 即强基线 |
| C14 | 2026-04 | [Towards Optimal Agentic Architectures for Offensive Security Tasks](https://arxiv.org/abs/2604.18718) | Isaac David, Arthur Gervais | arXiv | 600 次运行的架构族消融（白盒 vs 黑盒、Web vs 二进制） |
| C15 | 2026-03 | [Measuring AI Agents' Progress on Multi-Step Cyber Attack Scenarios](https://arxiv.org/abs/2603.11214) | Linus Folkerts et al. | arXiv | 32 步企业网 + 7 步工控攻击链，性能随算力对数线性扩展 |
| C16 | 2025-11 | [From Capabilities to Performance: Evaluating Key Functional Properties of LLM Architectures in Penetration Testing](https://aclanthology.org/2025.emnlp-main.802/) | Lanxiao Huang et al. | EMNLP 2025 | 记忆/通信/规划/监控五类功能增强对渗透成功率的影响 |
| C17 | 2025-11 | [Measuring and Augmenting Large Language Models for Solving Capture-the-Flag Challenges](https://doi.org/10.1145/3719027.3744855) | Zimo Ji et al. | ACM CCS 2025 | CTF 求解能力测量与增强 |
| C18 | 2025-10 | [PACEbench: A Framework for Evaluating Practical AI Cyber-Exploitation Capabilities](https://arxiv.org/abs/2510.11688) ⓝ | Zicheng Liu et al. | ICLR 2026 | 实战 AI 网络利用能力评测（单点/混合/链式/带防御） |
| C19 | 2025-10 | [HackWorld: Evaluating Computer-Use Agents on Exploiting Web Application Vulnerabilities](https://arxiv.org/abs/2510.12200) | Xiaoxue Ren et al. | ICLR 2026 | [GUI-Agent/HackWorld](https://github.com/GUI-Agent/HackWorld)：CUA 视觉交互漏洞利用评测 |
| C20 | 2025-09 | [Large Language Models for Cyber Security: A Systematic Literature Review](https://doi.org/10.1145/3769676) <small>*⭐新补充*</small> | Hanxiang Xu, Shenao Wang, Ningke Li, Kailong Wang et al.（9 人） | TOSEM 2025（accepted 09-22，online 09-29） | 系统性文献综述，同时覆盖攻防两侧应用；同文另有 arXiv:2405.04760，引用时以 TOSEM 版本为准 |
| C21 | 2025-08 | [Towards Effective Offensive Security LLM Agents: Hyperparameter Tuning, LLM as a Judge, and a Lightweight CTF Benchmark](https://arxiv.org/abs/2508.05674) | Minghao Shao et al.（NYU） | AAAI 2026 | CTFTiny + CTFJudge + CCI 部分正确性指标 |
| C22 | 2025-08 | [Training Language Model Agents to Find Vulnerabilities with CTF-Dojo](https://arxiv.org/abs/2508.18370) | Terry Yue Zhuo et al.（Amazon） | arXiv | [amazon-science/CTF-Dojo](https://github.com/amazon-science/CTF-Dojo)：658 个容器化 CTF 可执行训练环境 |
| C23 | 2025-07 | [Cyber-Zero: Training Cybersecurity Agents without Runtime](https://arxiv.org/abs/2508.00910) | Terry Yue Zhuo et al.（Amazon AGI） | ICLR 2026 | [amazon-science/Cyber-Zero](https://github.com/amazon-science/Cyber-Zero)：无运行时轨迹合成训练 |
| C24 | 2025-06 | [CyberGym: Evaluating AI Agents' Real-World Cybersecurity Capabilities at Scale](https://arxiv.org/abs/2506.02548) | Zhun Wang et al.（UC Berkeley Sunblaze） | ICLR 2026 | [sunblaze-ucb/cybergym](https://github.com/sunblaze-ucb/cybergym)：1,507 真实漏洞，衍生 34 个 0day |
| C25 | 2025-06 | [SEC-bench: Automated Benchmarking of LLM Agents on Real-World Software Security Tasks](https://arxiv.org/abs/2506.11791) | Hwiwon Lee et al. | NeurIPS 2025 | [SEC-bench/SEC-bench](https://github.com/SEC-bench/SEC-bench)：PoC 生成 + 补丁全自动评测 |
| C26 | 2025-05 | [Forewarned is Forearmed: A Survey on Large Language Model-based Agents in Autonomous Cyberattacks](https://arxiv.org/abs/2505.12786) | Minrui Xu et al. | arXiv | LLM Agent 自主网络攻击综述（"网络威胁通胀"） |
| C27 | 2025-04 | [Benchmarking Practices in LLM-driven Offensive Security: Testbeds, Metrics, and Experiment Design](https://arxiv.org/abs/2504.10112) ⓝ | Andreas Happe, Jürgen Cito | arXiv | 19 篇原型评测方法学批判 |
| C28 | 2025 | [A Unified Modeling Framework for Automated Penetration Testing](https://www.sciencedirect.com/science/article/abs/pii/S0167404825004766) | — | Computers & Security 2025 | AutoPT 统一建模框架 |
| C29 | 2025-02 | [OCCULT: Evaluating Large Language Models for Offensive Cyber Operation Capabilities](https://arxiv.org/abs/2502.15797) ⓝ | Michael Kouremetis et al. | arXiv | 进攻性网络作战能力评测（TACTL/CyberLayer） |
| C30 | 2024-10 | [AutoPenBench: Benchmarking Generative Agents for Penetration Testing](https://arxiv.org/abs/2410.03225) | Luca Gioacchini et al.（Politecnico di Torino） | EMNLP Industry 2025 | [lucagioacchini/auto-pen-bench](https://github.com/lucagioacchini/auto-pen-bench)：33 任务 |
| C31 | 2024-10 | [Catastrophic Cyber Capabilities Benchmark (3CB): Robustly Evaluating LLM Agent Cyber Offense Capabilities](https://arxiv.org/abs/2410.09114) | Andrey Anurin et al.（Apart Research） | arXiv | [apartresearch/3cb](https://github.com/apartresearch/3cb)：进攻能力稳健评测 |
| C32 | 2024-10 | [Towards Automated Penetration Testing: Introducing LLM Benchmark, Analysis, and Improvements](https://arxiv.org/abs/2410.17141) ⓝ | Isamu Isozaki et al. | ACM UMAP 2025 | 渗透 LLM 基准 + PentestGPT 消融改进 |
| C33 | 2024-08 | [Cybench: A Framework for Evaluating Cybersecurity Capabilities and Risks of Language Models](https://arxiv.org/abs/2408.08926) | Andy K. Zhang et al.（Stanford CRFM） | ICLR 2025 Oral | [andyzorigin/cybench](https://github.com/andyzorigin/cybench)：40 道专业 CTF |
| C34 | 2024-07 | [SoK: A Comparison of Autonomous Penetration Testing Agents](https://doi.org/10.1145/3664476.3664484) | Raphael Simon | ARES 2024 | AutoPT Agent 系统化对比 SoK |
| C35 | 2024-06 | [NYU CTF Bench: A Scalable Open-Source Benchmark for Evaluating LLMs in Offensive Security](https://arxiv.org/abs/2406.05590) | Minghao Shao et al.（NYU） | NeurIPS 2024 D&B | [NYU-LLM-CTF/NYU_CTF_Bench](https://github.com/NYU-LLM-CTF/NYU_CTF_Bench)：CSAW 200 题 |
| C36 | 2024-05 | [Got Root? A Linux Priv-Esc Benchmark](https://arxiv.org/abs/2405.02106) | Andreas Happe, Jürgen Cito | arXiv | Linux 提权能力标准化基准 |
| C37 | 2024-02 | [An Empirical Evaluation of LLMs for Solving Offensive Security Challenges](https://arxiv.org/abs/2402.11814) | Minghao Shao et al.（NYU） | NeurIPS 2024 | [NickNameInvalid/LLM_CTF](https://github.com/NickNameInvalid/LLM_CTF)：早期全自动 CTF 工作流实证，超人类平均 |
| C38 | 2024 | [自动化渗透测试技术研究综述](http://www.jos.org.cn/1000-9825/7038.htm) | — | 软件学报 2024 | 中文视角的自动化渗透测试技术综述 |
| C39 | 2023-06 | [InterCode: Standardizing and Benchmarking Interactive Coding with Execution Feedback](https://arxiv.org/abs/2306.14898) | John Yang et al.（Princeton NLP） | NeurIPS 2023 D&B | [princeton-nlp/intercode](https://github.com/princeton-nlp/intercode)：交互式执行反馈奠基基准 |

### D. 蜜罐与欺骗防御（防御侧）
*Honeypots, Cyber Deception & Anti-LLM-Attacker Defenses*

> 本节收录**针对 LLM 自主攻击的防御侧**研究（蜜罐、欺骗、诱捕与反制），供进攻型研究对照了解对手会如何布防；与 A/B/C 的进攻主线分开，不并入能力排序。arXiv 时间为 v1 提交月，与录用渠道分列。

| # | 时间 | 论文 | 作者 / 机构 | 发表渠道 | 关联项目 / 主题 |
|---|------|------|-----------|---------|---------------|
| D1 | 2026-11 | [Adaptive LLM-Driven Honeypots vs. LLM-Driven Attackers: Does Narrative Coherence Improve Deception?](https://arxiv.org/abs/2611.22589) <small>*⭐新补充*</small> | Pedro Beltrán-López, Raul Gonzalez Jimenez, Dario Maddaloni, Manuel Gil Pérez | arXiv（v1 11-17） | 叙事连贯蜜罐：命令映射 ATT&CK、部署 MITRE Engage 相互指涉制品；1,150 SSH 会话下高级攻击者中位会话 40→165 命令、放弃率 86%→52% |
| D2 | 2026-11 | [A Gingerbread House for LLM Agents: Source-Planned Honeypots That Lure Autonomous Attackers into an Isolated Shadow](https://arxiv.org/abs/2611.07611) <small>*⭐新补充*</small> | Seungdeok Roh, Seokjun Ryu, Sohee Park, Daeseon Choi | arXiv（v1 11-05） | 按应用源码规划静态蜜罐、把确认攻击者请求路由到隔离影子副本；CVE-Bench 40 任务真实攻陷 Claude Opus 4.8 26/40→5/40、ARTEX 20/40→0/40，20 个新任务 15/20→0/20 |
| D3 | 2026-10 | [Make the Adversary Spend More Energy: Generative Deception against Language-Model Attackers in Critical Infrastructure](https://arxiv.org/abs/2610.27739) <small>*⭐新补充*</small> | Vlad Mihal, Hosam Alamleh, Alessandro Cantelli-Forti | arXiv（v1 10-20） | 评估 LLM 攻击者与防御诱饵的能耗不对称，提出面向 SCADA 的生成式欺骗架构 |
| D4 | 2026-07 | [AgentSnare: Learning to Delay, Divert, and Defuse Autonomous Web Penetration Agents](https://arxiv.org/abs/2607.26998) <small>*⭐新补充*</small> | Ruoyu Wang, Heng Zhao, Renjie Wu, Tianhang Zheng | arXiv（v1 07-29；v5 11-01） | 轨迹自适应欺骗：ShadowOS + 离线训练的小型 LLM 生成动态诱饵，延迟/转移/化解自主 Web 渗透 Agent |
| D5 | 2026-06 | [Honeyquest for LLMs: Rethinking Cyber Deception for AI Attackers](https://arxiv.org/abs/2606.21037) <small>*⭐新补充*</small> | Kerri Prinos, Lilianne Brush, Cameron Denton | arXiv（v1 06-19；v3 10-23） | 21 模型、10,962 条响应 vs 47 名人类基线、174 侦察查询；73.4% 出现「推理识别陷阱却仍利用」的认知-行动鸿沟 |
| D6 | 2026 | [AIWAF：针对大语言模型渗透智能体的认知对抗型 WAF](https://doi.org/10.20172/j.issn.2097-3136.260922) <small>*⭐新补充*</small> | 李啸林、高见、邹宇宸、李明锋 等（6 人） | 中文期刊（CNKI 收录，DOI 注册 2026-11） | 面向 LLM 渗透智能体的认知对抗型 Web 应用防火墙 |
| D7 | 2025-10 | [SoK: Honeypots & LLMs, More Than the Sum of Their Parts?](https://arxiv.org/abs/2510.25939) <small>*⭐新补充*</small> | Robert A. Bridges, Thomas R. Mitchell, Mauricio Muñoz, Ted Henriksson | arXiv（v1 2025-10-29；v4 2026-04-07） | LLM 蜜罐领域首个系统化综述：检测向量分类、典型架构、评估框架与自主欺骗路线图 |
| D8 | 2025-08 | [Cloak, Honey, Trap: Proactive Defenses Against LLM Agents](https://www.usenix.org/conference/usenixsecurity25/presentation/ayzenshteyn) <small>*⭐新补充*</small> | Daniel Ayzenshteyn, Roy Weiss, Yisroel Mirsky（BGU） | USENIX Security 2025 | CHeaT：利用 LLM 的偏见、记忆限制与分词问题，干扰、检测或压制恶意 LLM Agent |
| D9 | 2025-06 | [Perry: A High-level Framework for Accelerating Cyber Deception Experimentation](https://arxiv.org/abs/2506.20770) <small>*⭐新补充*</small> | Brian Singer, Yusuf Saquib, Lujo Bauer, Vyas Sekar | arXiv（v1 06-25；v2 09-25） | 高层欺骗实验框架，降低实现成本、支持评估欺骗策略的权衡 |
| D10 | 2024-10 | [Hacking Back the AI-Hacker: Prompt Injection as a Defense Against LLM-driven Cyberattacks](https://arxiv.org/abs/2410.20911) <small>*⭐新补充*</small> | Dario Pasquini, Evgenios M. Kornaropoulos, Giuseppe Ateniese | arXiv（v1 10-28；v2 11-18） | Mantis：以提示注入干扰/反制 LLM 驱动的自动化攻击；[项目代码](https://github.com/pasquini-dario/project_mantis) |

> 注：会议/期刊年份为论文实际收录会议届期；arXiv 时间为 v1 提交月份。来源致谢：[tmylla/Awesome-LLM4Cybersecurity](https://github.com/tmylla/Awesome-LLM4Cybersecurity)、[EvanThomasLuke/Awesome-AI-Hacking-Agents](https://github.com/EvanThomasLuke/Awesome-AI-Hacking-Agents)、[simon-p-j-r/LLM4Pentest](https://github.com/simon-p-j-r/LLM4Pentest)（2026-09-11 逐篇交叉核对）。本轮移除的 4 篇"攻击 AI 系统 / LLM 自身安全"类论文：UDora（劫持 LLM Agent 推理的红队框架）、AgentPoison（LLM Agent 记忆投毒后门）、CyberSecEval 1/3（LLM 安全编码与风险评测，其基准本体仍保留于 Benchmark 章节）。
> 本轮新增 **KaliBench**（C2），按 v1 首次提交时间排入 2026-10；其正式渠道为 NeurIPS 2026 Evaluations & Datasets Track（arXiv Comments 原文），与 CyberArena 的 arXiv v1（10-13）分列，不合并为同一来源。**C1–C38 已按首次发表时间重排重编号**，历史条目内容未改动。
> **本轮补录（2026-11-18）**：按 [simon-p-j-r/LLM4Pentest](https://github.com/simon-p-j-r/LLM4Pentest) 最新清单（现 123 篇，分 SYSTEM & AGENT 55 / BENCHMARK 23 / EMPIRICAL 23 / SURVEY 13 / DEFENSE 9）逐条去重后**实际新增 7 篇**——本表此前已于 2026-09-11 按该清单核对过一轮，故 AWE、CHIMERA、FirmAgent、PTFusion、CTFAgent、AutoPT、Comparing AI Agents、LLMs as Hackers、AutoPentester、Controller 等**均已在表内，未重复新增**。新增：CyberEvolver（arXiv 2605.26195）、MazeRunner（2608.14216）、CTF/认证问答能力评估（2308.10443）、Perses（AsiaCCS 2025）、Context Relay（LAST-X 2026）、On the Adversarial Planning Capabilities of LLMs（ARES 2026 Workshops）、LLMs for Cyber Security 系统综述（TOSEM 2025）。每篇均回查 arXiv 摘要页或 DOI 落地页取得标题、作者、日期与渠道，**不采信清单的年份与分类标注**；日期无法确认者不插入，也未虚构作者。**排除项**：属「AI 系统自身安全 / 防御治理」的 RedTeamCUA、Cyber-Capable AI Agents、Rethinking PT for AI-Enabled Systems、Agentic Security 综述、SoK Honeypots、AIWAF、AgentSnare、Ethics Statements、Perry、Hacking Back 一律不收录；Research Square 预印本（PentestMCP 已收）、两篇孟加拉国高校学位论文、CTF 新手教育研究（2602.18172）与非 LLM 的 CTF 环境配置综述亦不收录。**A1–A70 与 C1–C39 已整段重编号**，历史条目内容未改。
> *Note: conference years refer to actual proceedings; arXiv dates are v1. Credits to the awesome lists above. Four "attacking-AI / LLM-safety" papers removed previously: UDora, AgentPoison, CyberSecEval 1/3. A 2026-11-18 refresh against the LLM4Pentest list (123 entries) added 7 papers after de-duplication — most entries were already present from the 2026-09-11 cross-check. Each addition was verified against its arXiv abstract or DOI landing page; AI-system-security, defense-governance, preprint, thesis and non-LLM items were excluded. Tables A and C were renumbered; no historical entry content changed.*
>
> **本轮新增 D 段（2026-11-25）**：检索蜜罐/欺骗防御关键词后，新增独立「D. 蜜罐与欺骗防御（防御侧）」小节 10 篇，让进攻型研究也能对照了解针对 LLM 攻击者的防御措施（蜜罐、欺骗、诱捕、反制、WAF）。其中 **SoK: Honeypots & LLMs（2510.25939）、AIWAF、AgentSnare、Perry、Hacking Back the AI-Hacker** 为上轮「排除防御治理」清单中的条目，**本轮重新审查后转入 D 段**。仍排除（非蜜罐/欺骗防御技术）：Ethics Statements（2506.08693，伦理治理）、Poster 合规审计（10.1145/3719027.3760713），以及属「AI 系统自身安全 / 能力综述」的 RedTeamCUA（2505.21936）、Cyber-Capable AI Agents（2607.25379）、Rethinking PT for AI-Enabled Systems（2607.14006）、A Survey on Agentic Security（2510.06445）。10 篇均已回查 arXiv 摘要页 / DOI / USENIX 页面取得标题、作者、日期与渠道；AIWAF 为中文期刊（CNKI），仅确认到年（DOI 注册 2026-11），未补造月份。
> *Note: section D (Honeypots, Cyber Deception & Anti-LLM-Attacker Defenses) was added on 2026-11-25 with 10 papers so offensive readers can see how defenders counter LLM attackers. Five previously excluded defense items (SoK Honeypots, AIWAF, AgentSnare, Perry, Hacking Back) were re-reviewed and moved into D; ethics/governance and AI-system-security surveys remain excluded. Each entry was verified against its arXiv abstract, DOI or USENIX page.*

---

## 🧪 Agent 能力评测 Benchmark
*Agent Capability Benchmarks (sorted by stars, desc)*

> 用于评估渗透测试 / 网络安全 / CTF / 红队 Agent 能力的开源 benchmark。
> *Open-source benchmarks for evaluating pentest / cybersecurity / CTF / red-team Agent capabilities.*

| # | Benchmark | 仓库 / 平台 | Stars | 时间 | 任务规模 | 评测重点 | 关联论文 |
|---|-----------|-------------|-------|------|---------|---------|---------|
| 1 | **TSecBench** | [官方平台](https://tsecbench.zc.tencent.com/) | —（托管平台） | 2026-07 | 腾讯云赛事靶场与托管评测 | Yunding Lab；本次入口仅取得加载页，未重新确认六维度/三接入方式等旧描述，不把闭卷直接写作“更准确” | — |
| 2 | **CyberGym** | [sunblaze-ucb/cybergym](https://github.com/sunblaze-ucb/cybergym) | 955 | 2025-06 | 真实漏洞分析与测试环境 | 数据版本、已知漏洞与未知漏洞设置需区分 | [arXiv:2506.02548](https://arxiv.org/abs/2506.02548) |
| 3 | **XBOW Validation Benchmarks** | [官方仓库](https://github.com/xbow-engineering/validation-benchmarks) | 748 | 2025-06 | 104 道 Web 挑战 | 静态公开题适合回归；较高分数不能直接证明真实业务能力或无污染 | XBOW Engineering Blog |
| 4 | **Cybench** | [andyzorigin/cybench](https://github.com/andyzorigin/cybench) | 325 | 2024-08 | 40 道 CTF 任务 | Unguided / Subtask 分开比较 | [arXiv:2408.08926](https://arxiv.org/abs/2408.08926) |
| 5 | **CVE-Bench** | [uiuc-kang-lab/cve-bench](https://github.com/uiuc-kang-lab/cve-bench) | 304 | 2025-03 | 40 个高严重性 Web CVE | 真实 CVE 场景，不使用未经证实“首个”标签 | [arXiv:2503.17332](https://arxiv.org/abs/2503.17332) |
| 6 | **InterCode-CTF** | [princeton-nlp/intercode](https://github.com/princeton-nlp/intercode) | 260 | 2023-06 | 100 道 picoCTF 题 | 交互式代码执行能力与 CTF 子集 | [arXiv:2306.14898](https://arxiv.org/abs/2306.14898) |
| 7 | **NYU CTF Bench** | [NYU_CTF_Bench](https://github.com/NYU-LLM-CTF/NYU_CTF_Bench) | 183 | 2024-06 | 200 正式题 + 55 开发题 | CSAW 历年题，区分数据集版本 | [arXiv:2406.05590](https://arxiv.org/abs/2406.05590) |
| 8 | **BountyBench** | [官方仓库](https://github.com/bountybench/bountybench) / [主页](https://bountybench.github.io/) / [arXiv:2505.15216](https://arxiv.org/abs/2505.15216) | 135 | 2025-05 | 25 个项目的安全研究任务 | 漏洞发现、验证与修复的经济影响口径 | Stanford CRFM Blog |
| 9 | **AutoPenBench** | [lucagioacchini/auto-pen-bench](https://github.com/lucagioacchini/auto-pen-bench) | 99 | 2024-10 | 33 任务 | 实验任务与真实 CVE 分组报告 | [arXiv:2410.03225](https://arxiv.org/abs/2410.03225) |
| 10 | **SEC-bench** | [SEC-bench/SEC-bench](https://github.com/SEC-bench/SEC-bench) | 49 | 2025-06 | 200 个 C/C++ CVE | PoC 与补丁双任务 | [arXiv:2506.11791](https://arxiv.org/abs/2506.11791) |
| 11 | **inspect_cyber** | [inspect_cyber](https://github.com/UKGovernmentBEIS/inspect_cyber) | 43 | 2025-06 | 可插拔任务扩展 | 通用 Agentic Cyber 评估组件，不能单凭机构归属赋予可靠性等级 | — |
| 12 | **PentestEval** <small>*⭐新补充*</small> | [公开演示](https://github.com/Richael-y/PentestEval) | 18 | 2025-12（v2 2026-11） | 论文 346 任务、12 场景 | 六阶段建模、五阶段评分；仓库为 Python 演示版，非完整端到端复现 | [arXiv:2512.14233](https://arxiv.org/abs/2512.14233) |
| 13 | **CTFTiny** | [NYU-LLM-CTF/CTFTiny](https://github.com/NYU-LLM-CTF/CTFTiny) | 16 | 2025-08 | 50 道轻量任务 | CTFJudge 与低成本回归 | [arXiv:2508.05674](https://arxiv.org/abs/2508.05674) |
| 14 | **CyberArena** <small>*⭐新补充*</small> | [主页](https://cyber-arena.ai) / [网站源码](https://github.com/cyber-arena-ai/cyber-arena) | 14（网站仓库） | 2026-10 | 40 挑战、466 有效对局（论文口径） | 实时对称攻防、多维评分；**网站仓库不等于 Octagon 引擎**，未取得引擎官方地址，运行轨迹部分有发布限制 | [arXiv:2610.19005](https://arxiv.org/abs/2610.19005) |
| 15 | **KaliBench** <small>*⭐新补充*</small> | [RISys-Lab/KaliBench](https://github.com/RISys-Lab/KaliBench) / [主页](https://risys-lab.github.io/KaliBench/) | 6 | 2026-10 | 8,504 对（训练 3,504 / 测试 5,000）、1,642 工具、23 维度、5 阶段 | **非端到端**：评 NL→单条 CLI 命令的工具选择与参数构造，含 alias 感知与确定性规范化打分，故不与渗透完成率类基准横向比高低；**仓库无 LICENSE**，论文 CC BY 4.0 不覆盖代码数据 | [arXiv:2610.02206](https://arxiv.org/abs/2610.02206)（NeurIPS 2026 D&B） |

> 托管平台单列在前，其余按当次精确仓库 Stars 排序；Benchmark 不沿用 Agent / Skills / MCP 的 Stars 门槛。新增 PentestEval、CyberArena 与 KaliBench，移出主要用于模型自身安全评测的 [CyberSecEval](https://github.com/meta-llama/PurpleLlama)；**15 个条目不意味着 15 套均已验证可完整运行的开源环境**（KaliBench 仓库 6 Stars、无许可证文件，CyberArena 引擎地址未取得）。成绩须附版本、模型、任务模式、时间/Token/工具预算与评测日期；不同粒度（单命令 / 端到端）不可直接比较。
> *Hosted and public research resources are distinguished; repository stars are not benchmark quality scores. Stars and licensing vary widely — KaliBench carries no license file and CyberArena's engine is not publicly addressed. Results must specify version, model, task mode, budget and evaluation date; single-command and end-to-end benchmarks are not directly comparable.*

### Benchmark 选型小贴士｜*Selection Cheatsheet*

| 评测目标 / Goal | 候选与限制 / Candidates & Caveats |
|---|---|
| 通用 CTF / General CTF | NYU CTF Bench、Cybench、InterCode-CTF；区分题库与模式 |
| 漏洞分析与验证 / Vulnerability Tasks | CyberGym、CVE-Bench、SEC-bench、AutoPenBench；XBOW 适合公开题回归 |
| 阶段级诊断 / Stage-Level Diagnostics | PentestEval；公开仓库为演示版，不能当完整端到端基准 |
| 单命令工具调用 / Command-Level Tool Use | KaliBench；评 NL→CLI 的工具选择与参数构造（exact-command / alias 感知），**不代表端到端渗透成功率**，仓库无许可证文件 |
| 动态同场攻防 / Live Attack-Defense | CyberArena；网站源码、评测引擎与公开轨迹分开核对 |
| 托管竞赛评测 / Hosted Competition | TSecBench；需确认平台访问及版本 |
| 经济影响 / Economic Impact | BountyBench |
| 自定义任务扩展 / Custom Tasks | inspect_cyber |
| 轻量回归 / Lightweight Regression | CTFTiny |

---

## 💼 商业化解决方案
*Commercial Solutions*

> 收录 **AI 渗透、攻击面验证及安全漏洞研究**的商业服务，明确区分自主测试、AI 辅助人工服务、源码审计和开放邀测。本轮逐项回查产品页、销售/演示及可读定价页；**预约演示是采购入口证据，不是已完成交易或实际能力证明**。没有公开价格、融资信息，不等于没有商业服务。
> *Commercial offerings for AI penetration testing, exposure validation and vulnerability research. Product scope, procurement access and public pricing are distinguished; a demo form is not evidence of a completed sale or independently measured capability.*

### 🇨🇳 国内厂商
*Domestic Vendors (China)*

| # | 公司 | 产品 | 官网 | 产品定位与特色 |
|---|------|------|------|---------------|
| 1 | **微步在线** <small>*⭐新补充*</small> | **RedAgents / Artex Pro** | [官方产品页](https://threatbook.cn/redagents) / [版权声明](https://threatbook.cn/threatbookNews/fcd1bd02-0d7e-4736-abfd-22fdbce6f4c1) | 企业级自主渗透 / 攻击面验证；Artex Pro 不是原 ARTEX 开源版，官网有联系我们/免费体检活动，未公开常规价格。**2026-11-06 官方声明确认原版 10-08 闭源**，赛事关联见前文 |
| 2 | **腾讯云** <small>*⭐新补充*</small> | **无境** AI 自主渗透测试 | [发布介绍](https://cloud.tencent.com/developer/article/2738844) | 2026-09-04 发布，以「自主发现、自主利用、自主验证、输出证据」为核心，面向上线前检测、常态化持续渗透、攻防演练前置与业务逻辑漏洞专项四类场景；SaaS 交付、零部署零运维，按授权目标与资产范围发起，面向企业开放试用。**本次未取得独立产品页与公开价格**；官方宣传的时长、漏洞数与成本数据属厂商自述口径，不在此列表述 |
| 3 | **绿盟科技** | **AI-PTS** | [官方产品页](https://www.nsfocus.com.cn/html/2026/651_0528/289.html) | 当前页面侧重多 Agent 的 AI 应用安全测试；AI 系统安全与普通 Web 渗透范围区分，不沿用未核实知识库/POC 数量；有商务/试用入口，未公开价格 |
| 4 | **京东云** | **AIPTS** AI 智能渗透测试服务 | [官方产品文档](https://docs.jdcloud.com/cn/security-attack-and-defense-drill-service/product-overview) | 智能任务拆解、长时记忆、并发测试及审计报告；当前文档未给原先宣称的上线日期、独立购买/计费页或价格，服务状态需向供应商确认 |
| 5 | **360** | **破阵子** 渗透测试智能体 | [介绍报道](https://m.sohu.com/a/1050707516_362042) / [官网](https://www.360.cn/) | 保留原有记忆、双引擎与复测闭环介绍作为报道口径；本次未取得新版官方产品/价格页，撤下“零误报”及未复核实战统计，**不视为本轮完成商业交付核验** |
| 6 | **阿里云** | **Agentic BAS** | [发布文章](https://developer.aliyun.com/article/1748260) | 2026-07-16 邀测；千问驱动多 Agent 的渗透与验证。原文邀测不等于当前全面商用，本次未取得独立采购/价格页 |
| 7 | **万径安全（Yaklang）** | **万径千机 / 小智** | [官方产品页](https://www.megavector.cn/safetyProduct/xiaozhi/) | RAG 知识问答、任务拆解、Yak 工具执行与结构化报告，专家辅助模式；商务试用，未公开价格，不使用“国内首款”断言 |
| 8 | **长亭科技** | **无锋** | [官方产品页](https://www.chaitin.cn/xblade) | 自然语言任务编排、专家库与任务管理；补齐此前空白简介。预约演示/销售咨询，未公开金额 |
| 9 | **斗象科技（漏洞盒子）** | **蛙池AI** | [官方产品页](https://www.digpool.cn/) | 对话式安全测试与白帽研究工作台；支持试用和报价咨询，未公开标准金额，不使用“全球首款”宣传 |
| 10 | **奇安信** | **AI 加特林** | [官方 AI 专题页](https://www.qianxin.com/topics/aiforsecurity) | 原条目暂保留；本次专题页未取得加特林具体产品/采购信息，不沿用“数分钟公告转完整链”能力保证 |
| 11 | **安恒信息** | **AI 渗透测试智能体** | [公司官网](https://www.dbappsecurity.com.cn/) | 恒脑安全模型关联渗透规划、工具调度与流量分析；本次未取得专属产品/定价页，旧发布介绍不等同最新交付状态 |
| 12 | **悬镜安全** | **灵脉 PTE** | [官方平台](https://pte.xmirror.cn/) | AI 自动化黑盒安全测试及报告工作台；注册入口，未公开标准价格，作者功能声明不等于第三方可靠性认证 |

> 国内表本轮扩充为 **12 家**：新增 **腾讯云「无境」**（2026-09-04 发布，SaaS 形态，面向企业开放试用），并将 **微步在线**调整至首位、其余条目顺延重编号，文案与链接未改。无境的独立产品页与公开价格本次未取得，量化效果数据为厂商自述，不写入定位列。
> *Twelve domestic vendors; Tencent Cloud's Wujing was added and ThreatBook moved to the top. No public pricing or standalone product page was obtained for Wujing, and vendor-reported performance figures are excluded.*

### 🌍 国外厂商 Top 20（商业服务精选，非估值排行榜）
*International Vendors — 20 Selected Commercial Offerings, Not a Valuation Ranking*

> 以现有安全测试平台、可采购产品、社区影响力及与本文主线的相关性综合选取；本次未取得 20 家可比的同期市值/估值/营收数据，**撤下旧表没有原始出处的融资、估值、客户数与“全球第一”断言**，不伪造数字排名。主模型厂商、纯模型安全评测工具、仅有竞赛开源成果不作为独立可采购渗透方案。下列官网为逐行来源；金额是本次页面快照，不含税费或合同附加项保证。
> *Selection emphasizes relevant products and procurement evidence. Comparable current valuation/revenue data was not established, so unsupported financial estimates and numerical market rankings are not retained. Prices are point-in-time page observations, not quotes.*

| # | 公司 / 品牌 | 产品 | 官方来源 | 商业化核验 / 公开价格 | 产品范围 |
|---|-------------|------|----------|----------------------|----------|
| 1 | **Pentera** | Exposure Validation / AVP | [产品页](https://pentera.io/) | 预约商业演示；金额未公开 | 企业持续暴露验证与自动化安全测试 |
| 2 | **XBOW** | XBOW | [产品页](https://xbow.com/) | 预约演示；本页未见自助购买价格 | Web / API 自主测试与验证证据 |
| 3 | **Horizon3.ai** | NodeZero | [产品页](https://horizon3.ai/) / [演示](https://horizon3.ai/contact-us/schedule-demo/) | 商业演示/询价；未公开金额 | 企业环境自主渗透与复测 |
| 4 | **Aikido Security** | AI Pentest / Deep Review | [AI Pentest](https://www.aikido.dev/attack/aipentest) | 页示标准单次 **$4,000**，按规模另计；免费摘要/试跑与完整付费报告区分 | AI 渗透、代码审计；开放权重 Altar-1 另见模型章节 |
| 5 | **Synack** <small>*⭐新补充*</small> | Sara AI Pentesting / PTaaS | [官网](https://www.synack.com/) / [Sara 演示](https://www.synack.com/interactive-demos/sara-ai-pentesting/) | 演示入口；价格未公开 | AI 与人工测试结合，不把全平台等同无人自主测试 |
| 6 | **HackerOne** <small>*⭐新补充*</small> | Hai / AI-assisted Pentesting | [官网](https://www.hackerone.com/) | 销售咨询；未公开统一单价 | AI 编排、验证与辅助人工渗透/赏金平台 |
| 7 | **Cobalt** <small>*⭐新补充*</small> | Sage AI / Offensive Security | [官网](https://www.cobalt.io/) / [演示](https://www.cobalt.io/get-started) | 商业演示；未公开金额 | 平台 AI 智能层及测试代理；人工 PTaaS 与自主模块分开看待 |
| 8 | **Hadrian** | Atlas / Nova | [官网](https://hadrian.io/) / [演示](https://hadrian.io/demo) | 测试申请/演示；未核实 Nova 的普遍交付条件 | 攻击面发现/验证与 AI 代理渗透 |
| 9 | **Terra Security** | Terra | [产品页](https://www.terra.security/) / [价格页](https://www.terra.security/pricing) | 按攻击面/部署方式年度订阅询价；无公开金额 | 人工监督的持续 Agentic 安全测试 |
| 10 | **RunSybil** | Sybil | [官网](https://www.runsybil.com/) | 预约 Demo 与样例报告；价格未公开 | 面向代码、API、云和基础设施的持续测试 |
| 11 | **Strix** | Strix Pro / Enterprise | [产品页](https://usestrix.com/) / [价格页](https://usestrix.com/pricing) | Pro **$29/席位/月**、7 天试用；渗透测试按次另收费、单价未公开；企业询价 | 开源/商业双栈；订阅席位费不是单次渗透总价 |
| 12 | **Dreadnode** <small>*⭐新补充*</small> | Dreadnode Platform（Web Security / Network Operations / AI Red Teaming） | [官网](https://dreadnode.io/) / [演示](https://dreadnode.io/) | 未公开定价，仅 "Book a demo"；on-prem 需单独联系 | 以自托管交付为主的 AI 基础设施，Web 渗透含 **83 个攻击技术 playbook**、网络发现与 AD 评估；**其 AI Red Teaming 面向 AI 系统自身，不属本文主线**，此处只按 Web / 网络模块计入，不把模块总和当作单一渗透产品 |
| 13 | **Novee** <small>*⭐新补充*</small> | Novee | [官网](https://novee.security/) / [演示](https://novee.security/demo/) | 演示/商务入口；价格未公开 | 持续 AI 渗透，SaaS / 本地部署；不再因无公开融资而剔除 |
| 14 | **MindFort** | Autonomous Security Swarms | [官网](https://mindfort.ai/) | Demo / 注册入口；价格未公开 | 多 Agent 应用测试与修复复测 |
| 15 | **Hacktron** | Hacktron AI | [官网](https://hacktron.ai/) / [咨询](https://hacktron.ai/contact) | 页示白盒 **$50–$25,000/次**；PR 审查 **$40/开发者/月起**，两项分开计费 | 白盒测试、AI 红队及 PR 审查 |
| 16 | **Harmony Intelligence** | Harmony | [官网](https://harmonyintelligence.com/) / [演示](https://harmonyintelligence.com/book-a-demo) | 商务演示；价格未公开 | 专家托管的持续 AI 渗透测试 |
| 17 | **Parameter（Anytool, Inc.）** | AI Pentesting & Continuous Security | [当前 hex.co 页面](https://hex.co/) | 页脚有 Pricing 锚点（`/pentesting#pricing`），**未取得公开金额**；入口为 Book a call 与注册 | 域名仍为 hex.co，全站品牌与邮箱已为 Parameter（app / support@parameter.ai），页脚版权 **© 2026 Anytool, Inc.**；页面**未见更名或收购声明原文**，故只记录现状，不推断 Hex → Parameter 的关系，也不沿用旧 Hex 融资归属。功能含 Web/API/云/供应链与 PR 审查 |
| 18 | **Astra Security** <small>*⭐新补充*</small> | Autonomous Pentesting | [官方产品页](https://getastra.com/autonomous-pentesting) | 个性化演示/定价入口；本页无金额 | Web / API 持续 AI 测试结合人工验证；此前“域名混淆/无服务”结论不再沿用 |
| 19 | **Veria Labs** <small>*⭐新补充*</small> | Veria（自主渗透 Agent） | [官网](https://verialabs.com/) | 无公开价格，仅 "Get a demo" / contact；未见自助注册下单 | 自主映射攻击面、在 staging 复现可利用漏洞并自动生成修复 PR；YC F25。"Backed by Y Combinator" 为页面自我表述，"#1 US hacking team" 与客户案例中的数据未独立核验，不作为能力证据 |
| 20 | **Penligent** <small>*⭐新补充*</small> | Penligent | [官网](https://penligent.ai/) / [价格页](https://penligent.ai/pricing) | Free **$0/月**；Pro **$99.9/月**；Team **$399/月**；企业询价，按计划配额 | AI 辅助渗透、验证与报告；套餐价格不代表无限制授权或保证漏洞发现 |

> 本轮海外表**替换 2 条、总数保持 20**：新增 **Veria Labs** 与 **Dreadnode**（均为当次可访问的官方产品页），移出 **Theori（Xint / Xint Code）** 与 **Cohere Cyber（原 AISLE）**。移出理由是产品主体为**代码审计与专家咨询**，与"可采购的自主渗透 / 攻击面验证"相关度低于新增项，其中 AISLE 页面本身即未证实自主网络渗透；**移出仅表示退出本表精选，不等于该厂商没有商业服务**，两者的历史链接保留以便追溯：[xint.io](https://xint.io/)、[aisle.com](https://aisle.com/)（其 2026-11-10 被 Cohere 收购的公告记录仍见上一版本）。价格口径仍按平台费 / 单次费 / 席位费分别记录，未取得公开金额者标注"未公开"，不填估算值。
> *Two international entries were swapped to keep 20 selected offerings: Veria Labs and Dreadnode in, Theori (Xint) and Cohere Cyber (formerly AISLE) out. Removal reflects lower relevance to purchasable autonomous pentesting — not the absence of a commercial offering. Fees are recorded per unit (platform / per-engagement / per-seat); unknown amounts are marked as not public rather than estimated.*

### 🎯 选型对照（按典型场景）
*Pick by Scenario*

| 场景 / Scenario | 国内候选 / 状态 | 国外候选 |
|---|---|---|
| Web / API 自主测试 | RedAgents / Artex Pro、腾讯云无境、长亭无锋、蛙池AI；需确认合同测试范围 | XBOW、Strix、RunSybil、Novee |
| 企业持续验证 | RedAgents；京东云 AIPTS 当前采购条件待确认 | Horizon3.ai NodeZero、Pentera、Terra |
| AI + 人工服务 | 万径千机 / 小智、悬镜 PTE；按实际人工介入模式核对 | Synack Sara、HackerOne Hai、Cobalt Sage、Astra |
| 源码审计 / 修复验证 | 蛙池AI / 无锋的具体模块向供应商确认 | Aikido Deep Review、Xint Code、Cohere Cyber |
| 攻击面与长期测试 | RedAgents；360 破阵子当前产品交付信息待核 | Hadrian Atlas / Nova、MindFort、Harmony |
| 竞赛研究（非采购推荐） | sapper-v2、BreachWeave、ARTEX 历史作品（见赛事章节） | ARTEMIS、Veria ctf-agent（见 Agent 表） |
| 开放邀测（非全面商用） | 阿里云 Agentic BAS：沿用官方邀测状态，不承诺公开交付 | 按各供应商实际申请条件 |

---

## 📚 Awesome List 资源汇编
*Awesome List Collection*

> 本节汇总专门收录 Offensive AI / AI 安全相关精选资源的 Awesome List 仓库，本文档大量内容来自这几个 list 的交叉合并。
> *This section gathers Awesome List–style repositories. This document is largely derived from cross-merging the following lists.*

| # | 仓库 | Stars | 维护者 | 内容定位 |
|---|------|-------|--------|---------|
| 1 | [fr0gger/Awesome-GPT-Agents](https://github.com/fr0gger/Awesome-GPT-Agents) | 6.6k | fr0gger | 网络安全 GPTs / Agent 索引；与可部署 Skills / MCP 项目区分 |
| 2 | [tmylla/Awesome-LLM4Cybersecurity](https://github.com/tmylla/Awesome-LLM4Cybersecurity) <small>*⭐新补充*</small> | 1.8k | tmylla | LLM 网络安全研究资料；按渗透、漏洞、评测主题筛选，非全部内容都属于本文主线 |
| 3 | [ottosulin/awesome-ai-security](https://github.com/ottosulin/awesome-ai-security) | 1.6k | ottosulin | 通用 AI 安全资源集合（攻防兼顾，补充索引） |
| 4 | [jiep/offensive-ai-compilation](https://github.com/jiep/offensive-ai-compilation) | 1.4k | jiep | 进攻型 AI 综合研究资源，需按授权安全研究用途筛选 |
| 5 | [TalEliyahu/Awesome-AI-Security](https://github.com/TalEliyahu/Awesome-AI-Security) | 914 | TalEliyahu | 偏 AI 系统防御侧，作为补充索引而非主线工具推荐 |
| 6 | [EvanThomasLuke/Awesome-AI-Hacking-Agents](https://github.com/EvanThomasLuke/Awesome-AI-Hacking-Agents) | 767 | EvanThomasLuke | AI 安全 Agent、赛事作品、商业产品与论文；本轮候选发现入口 |
| 7 | [raphabot/awesome-cybersecurity-agentic-ai](https://github.com/raphabot/awesome-cybersecurity-agentic-ai) | 611 | raphabot | 网络安全 Agentic AI 资源（MCP / 工具 / 框架 / 论文） |
| 8 | [Eyadkelleh/awesome-skills-security](https://github.com/Eyadkelleh/awesome-skills-security) | 407 | Eyadkelleh | SecLists 衍生的 Agent Skill 合集；与 Skills 章节交叉收录，不合并计数 |
| 9 | [simon-p-j-r/LLM4Pentest](https://github.com/simon-p-j-r/LLM4Pentest) | 388 | simon-p-j-r | 《Hackers or Hallucinators?》关联资源汇编：论文、工具与基准；不是可执行 Agent |
| 10 | [skyvanguard/awesome-ai-pentesting](https://github.com/skyvanguard/awesome-ai-pentesting) <small>*⭐新补充*</small> | 119 | skyvanguard | 主体为自主渗透 Agent、安全 MCP、侦察 / CTF / 漏洞分析，MIT；**另含 AI 系统自身安全（提示注入、越狱、护栏）与 LLM 红队测试大类**，按本文主线只取渗透相关部分，不整体当作进攻资源。README 列出 12 个月无提交的 Unmaintained 区，引用前需核对条目现状 |
| 11 | [gmh5225/awesome-ai-security](https://github.com/gmh5225/awesome-ai-security) | 66 | gmh5225 | 面向安全研究的 AI 资源索引 |

> 本轮按精确 Stars 重排，新增此前已作为论文来源引用、但未进入此表的 tmylla 清单。原 [ox01024/awesome-offensive-security-ai](https://github.com/ox01024/awesome-offensive-security-ai) 本次可访问、29 Stars；修正此前将 404 直接断言为“作者删除”的表述，暂不重新纳入精选。本轮增补 `skyvanguard/awesome-ai-pentesting`（119，精确值），**10 → 11**；其“AI Security / Securing AI Systems”与“Red Team & Offensive AI”分区主要面向 LLM 自身安全，仅作辅助来源，不据此计入本文章节。资源汇编是发现入口，不替代项目官方文档与论文原文核验。
> *Lists are discovery sources, not primary evidence. One list was added (10 → 11); its AI-system-security sections serve only as secondary leads. The previously inaccessible ox01024 repository is now reachable; a prior 404 did not establish deletion. Stars are sorted before rounding; cross-listed resources are counted per section.*

---

## 📊 统计概览
*Statistics Overview*

- **Agent / 关联项目主表**：**60** 个；另列 **AIxCC CRS 7** 个，二者合计 **67** 个仓库项目。赛事其他引用不再次加到此合计。本轮据 PDF 盘点新增 10 个达标项目（50 → 60），低星与无法核验者未收录，见主表核验说明。
- **模型 / Models**：**12** 个（安全研究 A 类 5 + 安全专用 B 类 7）；量化变体不重复计模型，RedSage 家族按 1 条合并计。Mistral Large 4 为通用模型，仅在 B 类下作关联说明，**不计入 12**。
- **Skills**：**6** 个，Stars ≥ 100；以技能包为交付主体，不收自主 Agent/Subagent 框架。SecSkills 已声明停更；Claude-Red 与 hack-skills 的 Stars 为页面缩写（`≈11.2k` / `≈2.7k`），未取得精确整数。
- **独立工具 MCP**：**10** 个，Stars ≥ 100；hexstrike-ai 与主表交叉出现，章节计数不等于去重项目总数。新增 3 个逆向工程 MCP，其桥接许可不覆盖 IDA Pro / Ghidra 本体。
- **赛事 / Competitions**：**3** 个赛事系列（AIxCC 2025、腾讯云赛事、百度 Agent+）；腾讯云第一至第三届属于同一系列，各阶段获奖分别表述。
- **论文 / Papers**：**139** 篇（A 70 / B 20 / C 39 / D 10），覆盖 **2023-06 → 2026-11**；本轮新增 D 段「蜜罐与欺骗防御（防御侧）」10 篇（含 SoK 综述），供进攻型研究对照防御措施，A/B/C 历史条目未改。
- **Benchmark**：**15** 个，覆盖 **2023-06 → 2026-10**；包括托管平台、完整研究资源、演示和网站入口，公开/复现状态见表。KaliBench 为单命令工具调用评测，不与端到端渗透基准横向比较。
- **商业产品 / Commercial**：**32** 条（国内 12 + 海外精选 20）。国内表新增腾讯云「无境」并把微步在线调至首位，国内节整体前置到国外节之前；海外表此前替换 2 条（Veria、Dreadnode 进；Theori、Cohere Cyber 原 AISLE 出），行数保持 20。国内部分多处仍处邀测或交付待核，不等于 32 项都可自助购买。
- **Awesome Lists**：**11** 个；索引与 Skills 可交叉计入各章，不冒充独立可执行 Agent。新增 `skyvanguard/awesome-ai-pentesting`（119），其 AI 系统安全分区仅作辅助来源。
- **主要语言**：Python、TypeScript、Go，以及新增 Rust 项目；本轮未完整统计语言占比，撤下旧估计比例。
- **领域趋势 / Trends**：
  - **2023–2024**：从工具调用探索到 CTF、交互式与真实漏洞基准。
  - **2025**：多 Agent、规划/记忆、AIxCC 漏洞发现与修复、真实环境对照。
  - **2026**：显式状态与事实图（Cairn、sapper-v2）；模块级诊断（PentestEval）；从静态单机测试走向动态同场攻防（CyberArena、腾讯云 AI-KOH）；**粒度继续下探到单条命令行**（KaliBench 的 NL→CLI 与无运行时奖励）；逆向工程侧由社区桥接走向官方 MCP（`ida-pro-mcp` / `ghidra-mcp` / Hex-Rays 官方 `ida-mcp`）；执行验证数据训练（Feyospace）；开源、开放权重与闭源商业服务并存（ARTEX → Artex Pro、Altar-1）。不将单一赛事名次或付费席位价格视为普遍能力排名。

> **本轮证据限制**：部分微信公告遇验证页、TSecBench 仅加载页，已分别注明；公开 X/Twitter 检索未取得可独立核实的 Artex / sapper-v2 官方获奖原帖，不以社交热度替代官方或作者来源。**新增条目的 Stars 中，Claude-Red（11.2k）、hack-skills（2.7k）、ida-pro-mcp（13.5k）、ghidra-mcp（6.3k）、ida-mcp（1.6k）、raptor（4.0k）、airecon / pentestcode（1.1k）、Cybermes（1.0k）为页面缩写，未取得精确整数，排序因此为近似；KaliBench、skyvanguard 与其余主表新增项（953 / 423 / 414 / 367 / 327 / 270）为精确值。** 主表新增 10 项来自个人审计盘点 PDF，仅取其项目名单与仓库地址，**未采用其能力判断、暴露面分类与 Stars 快照**；PDF 第 1–3 页为图片页，封面与方法论无法从文本层核对，作者信息仅来自文档元数据。Mistral Large 4 的发布日期取自官方 RSS `pubDate`，公告正文与新闻索引页均无日期字段。没有运行模型、扫描目标或复现论文，未执行任何仓库脚本；全部存量论文及部分国内产品没有重新全量核验。变更明细见 [CHANGELOG.md](CHANGELOG.md)。
> *Limitations: several newly added star counts are page abbreviations rather than exact integers, so their ordering is approximate; KaliBench, skyvanguard and the other new agent rows (953 / 423 / 414 / 367 / 327 / 270) are exact. The ten agent additions derive from a personal audit-style PDF; only its project list and repository URLs were used — not its capability findings, exposure classes or star snapshots. Its first three pages are images, so cover and methodology could not be checked from the text layer. No models, scans or paper reproductions were executed, and no repository script was run.*
>
> 🕐 **最后更新时间 / Last updated**：2026-11-18 (UTC+8)

---

## ⚠️ 免责声明
*Disclaimer*

> 本文档汇总的所有项目、论文与 Benchmark **仅供学习研究、企业内部安全防护与授权渗透测试使用**。
> 在任何情况下，使用者均须严格遵守所在国家和地区的法律法规以及目标组织的授权范围；**严禁将其用于未经授权的攻击、入侵、破坏或其他任何违法活动**。任何因滥用本文档收录内容而引发的法律责任、经济损失或安全后果，均由使用者自行承担，与本文档作者及所列项目维护者无关。
>
> *All projects, papers, and benchmarks compiled in this document are intended **solely for learning, internal enterprise security hardening, and authorized penetration testing**. Users must strictly comply with the laws and regulations of their jurisdiction as well as the authorization scope granted by the target organization. **Any unauthorized attack, intrusion, sabotage, or other illegal activities are strictly prohibited.** Any legal liability, financial loss, or security consequence resulting from misuse of the contents herein shall be borne entirely by the user, and is unrelated to the authors of this document or the maintainers of the listed projects.*
