# Offensive AI Agentic 全景：项目 / 模型 / Skill / MCP / 论文 / Benchmark / 商业产品 一览
*Offensive AI Agents Landscape: Projects, Models, Skills, MCP Servers, Papers, Benchmarks & Commercial Solutions*
<img width="1073" height="564" alt="599999755-793799dc-53e7-4fee-8959-654fbc09c902" src="https://github.com/user-attachments/assets/f3beb3dd-c4f4-40e1-a6e8-f2ae52743973" />

<div align="center">

| [🛠️ Projects](#开源agent列表) | [🧬 Models](#进攻型--安全专用开源模型) | [🧩 Skills](#进攻型-ai-skill-资源精选) | [🔌 MCP](#进攻型-ai-mcp-server-精选) | [📑 Papers](#相关学术论文) | [🧪 Benchmarks](#agent-能力评测-benchmark) | [📚 Awesome Lists](#awesome-list-资源汇编) | [💼 Commercial](#商业化解决方案) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **56** | **11** | **3** | **7** | **73** | **13** | **9** | **32** |
| 渗透 / 红队 / CTF Agent | 进攻 6 + 安全专用 5 | Claude/Agent Skill | Burp/Metasploit/工具链 | 2023 → 2026 | 2023 → 2026 | 资源索引 | 国外 Top 20 + 国内 12 |

</div>

> 本文档以**进攻型 AI**为主线，系统整理了 **AI 渗透测试 / 自主红队 Agent** 领域的开源项目、**进攻型 & 安全专用开源模型**、**进攻型 AI Skill 与 MCP Server**、学术论文、能力评测 Benchmark 与国内外商业化解决方案，帮助研究者、安全工程师与企业安全决策者快速建立领域全景认知。注意：本文档聚焦"用 AI 做攻击"，而非"攻击 AI 系统"（LLM 自身安全性如 prompt injection / jailbreak 等不在主线范围，仅少量关联项目涉及）。
>
> *This document focuses on **offensive AI** — curating open-source projects, **offensive & security-specialized open-weight models**, **offensive AI Skills & MCP Servers**, academic papers, capability benchmarks, and commercial solutions (international & China) in **AI-driven penetration testing & autonomous red-team agents**. It helps researchers, security engineers, and enterprise decision-makers quickly form a holistic view of the domain. Note: the primary lens is "using AI to attack", not "attacking AI systems" (LLM security topics such as prompt injection / jailbreaking are out of scope for the main thread, though a few related projects may appear incidentally).
>
> 数据采集时点：2026-07-20（13:13 新增"腾讯云智能渗透黑客松"，赛事章节升级为"知名 AI 攻防 / 智能渗透赛事"）｜ Star 数 ≥ 1000 统一以 `k` 为单位（保留一位小数）。

---

## 📋 开源Agent列表
*Open-Source Agent List*

> 按 Star 数降序排列，收录 Star ≥ 90 的开源 AI 渗透测试 / 红队 Agent 及进攻型安全项目。
> <small>*⭐新补充*</small> = 本轮新增（2026-07-14/15）
> *Sorted by stars (desc), projects with ≥ 90 stars — covering AI penetration testing, red-team agents, and offensive security tools. ⭐ = newly added this round (2026-07-14/15).*

| # | 项目 | Stars | 语言 | 类型 | 简介 |
|---|------|-------|------|------|------|
| 1 | [KeygraphHQ/shannon](https://github.com/KeygraphHQ/shannon) | 45.6k | TypeScript | 渗透 Agent | 面向 Web 应用和 API 的自主白盒 AI 渗透测试工具 |
| 2 | [usestrix/strix](https://github.com/usestrix/strix) | 41.0k | Python | 渗透 Agent | 开源 AI 黑客，发现并修复应用漏洞 |
| 3 | [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) | 23.2k | TypeScript | LLM 红队 | LLM 应用红队/渗透/漏洞扫描，OpenAI、Anthropic 在用 |
| 4 | [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi) | 20.3k | Go | 渗透 Agent | 全自主 AI 代理系统，执行复杂渗透测试任务 |
| 5 | [GreyDGL/PentestGPT](https://github.com/GreyDGL/PentestGPT) | 14.2k | Python | 渗透 Agent | LLM 驱动的自动化渗透测试代理框架（早期标杆） |
| 6 | [0x4m4/hexstrike-ai](https://github.com/0x4m4/hexstrike-ai) | 10.3k | Python | MCP / 渗透 | MCP 服务器，让 AI Agent 自主运行 150+ 安全工具 |
| 7 | [aliasrobotics/cai](https://github.com/aliasrobotics/cai) | 9.4k | Python | 安全 AI 框架 | Cybersecurity AI（CAI）安全框架 |
| 8 | [NVIDIA/garak](https://github.com/NVIDIA/garak) | 8.4k | Python | LLM 红队 | LLM 漏洞扫描器（"LLM 界的 nmap"） |
| 9 | [OWASP/Nettacker](https://github.com/OWASP/Nettacker) | 5.2k | Python | 自动化扫描 | OWASP 自动化渗透测试 / 漏扫框架 |
| 10 | [Ed1s0nZ/CyberStrikeAI](https://github.com/Ed1s0nZ/CyberStrikeAI) | 5.1k | Go | 渗透 Agent | Go 构建的 AI 原生安全测试平台 |
| 11 | [elder-plinius/T3MP3ST](https://github.com/elder-plinius/T3MP3ST) | 4.6k | TypeScript | 红队 Agent | 自主红队平台 / 多智能体进攻性安全元框架，复用本机 AI 编码代理（Claude Code/Codex/Ollama 等）作零日漏洞猎手 |
| 12 | [microsoft/PyRIT](https://github.com/microsoft/PyRIT) | 4.1k | Python | LLM 红队 | 生成式 AI 风险识别工具（Microsoft） |
| 13 | [GH05TCREW/pentestagent](https://github.com/GH05TCREW/pentestagent) | 2.8k | Python | 渗透 Agent | 黑盒安全测试 AI Agent 框架（GHOSTCREW） |
| 14 | [protectai/vulnhuntr](https://github.com/protectai/vulnhuntr) | 2.7k | Python | 漏洞挖掘 | LLM 零样本漏洞发现，"首个 AI 自主发现 0day" |
| 15 | [samugit83/redamon](https://github.com/samugit83/redamon) | 2.2k | Python | 红队 Agent | AI 驱动的代理式红队框架 |
| 16 | [confident-ai/deepteam](https://github.com/confident-ai/deepteam) | 2.1k | Python | LLM 红队 | DeepTeam — LLM 红队测试框架 |
| 17 | [Armur-Ai/Pentest-Swarm-AI](https://github.com/Armur-Ai/Pentest-Swarm-AI) <small>*⭐新补充*</small> | 2.1k | Go | 渗透 Agent | 首个"蜂群"架构自主渗透平台，信息素黑板去中心化协作，ReAct 推理 + 5 种蜂群剧本，支持 Claude API / Ollama 本地，含 MCP 服务器 |
| 18 | [0xSteph/pentest-ai-agents](https://github.com/0xSteph/pentest-ai-agents) | 2.0k | Shell | Claude SubAgent | 将 Claude Code 转为攻击性安全研究助手 |
| 19 | [oritera/Cairn](https://github.com/oritera/Cairn) | 2.0k | Python | 渗透 Agent | 通用状态空间搜索引擎，自主渗透 |
| 20 | [msoedov/agentic_security](https://github.com/msoedov/agentic_security) | 1.9k | Python | LLM 红队 | Agentic LLM 漏洞扫描器 |
| 21 | [zakirkun/guardian-cli](https://github.com/zakirkun/guardian-cli) | 1.7k | Python | 渗透 Agent | 生产级 AI 渗透 CLI（Gemini + LangChain） |
| 22 | [trailofbits/buttercup](https://github.com/trailofbits/buttercup) | 1.6k | Python | 漏洞修复 | Trail of Bits 出品（也是 AIxCC 第二名 CRS） |
| 23 | [Gowtham-Darkseid/AutoPentestX](https://github.com/Gowtham-Darkseid/AutoPentestX) | 1.4k | Python | 渗透 Agent | 自动化渗透测试与漏洞报告 |
| 24 | [0xSteph/pentest-ai](https://github.com/0xSteph/pentest-ai) <small>*⭐新补充*</small> | 1.3k | Python | 渗透 Agent | MCP 服务器封装 205+ 安全工具 + 17 个专业代理 + 确定性漏洞验证（零误报），CLI + MCP 双路径，自带 LLM |
| 25 | [utkusen/promptmap](https://github.com/utkusen/promptmap) | 1.2k | Python | LLM 红队 | LLM Prompt Injection 自动化扫描器 |
| 26 | [CyberStrikeus/CyberStrike](https://github.com/CyberStrikeus/CyberStrike) <small>*⭐新补充*</small> | 1.2k | TypeScript | 渗透 Agent | AI 驱动的进攻性安全代理，7,300+ 安全技能，基于 MITRE ATT&CK / CIS / OWASP / NIST，含网站 [cyberstrike.io](https://cyberstrike.io) |
| 27 | [ipa-lab/hackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT) | 1.2k | Python | 渗透 Agent | 50 行代码内调用 LLM 协助伦理黑客 |
| 28 | [bugbasesecurity/pentest-copilot](https://github.com/bugbasesecurity/pentest-copilot) | 1.1k | JavaScript | 浏览器助手 | 浏览器端的道德黑客辅助工具 |
| 29 | [berylliumsec/nebula](https://github.com/berylliumsec/nebula) | 1.1k | Python | 渗透助手 | AI 渗透助手，自动侦察 / 笔记 / 漏洞分析 |
| 30 | [SanMuzZzZz/LuaN1aoAgent](https://github.com/SanMuzZzZz/LuaN1aoAgent) | 1.1k | Python | 渗透 Agent | 全自主 AI 渗透 Agent，XBOW >90%（广州大学）|
| 31 | [splx-ai/agentic-radar](https://github.com/splx-ai/agentic-radar) | 998 | Python | Agent 安全扫描 | LLM Agentic 工作流安全扫描器（OpenAI Agents、CrewAI、LangGraph 等）|
| 32 | [ghostsecurity/reaper](https://github.com/ghostsecurity/reaper) | 875 | Go | 测试代理 | Ghost Security 出品的实时验证代理工具，对人 / Agent 双友好 |
| 33 | [PentesterFlow/agent](https://github.com/PentesterFlow/agent) <small>*⭐新补充*</small> | 863 | TypeScript | 渗透 Agent | 终端内 Agentic 进攻性安全，"人在回路中"，内置 OWASP Top 10 技能 + Burp 集成 + 覆盖率跟踪 |
| 34 | [xalgord/xalgorix](https://github.com/xalgord/xalgorix) | 732 | Go | 渗透 Agent | 开源 AI 渗透测试 Agent |
| 35 | [ASCIT31/Dark-Moon](https://github.com/ASCIT31/Dark-Moon) <small>*⭐新补充*</small> | 728 | Python | 渗透 Agent | AI 驱动的自主渗透测试引擎，覆盖 Web/云/AD/K8s，多智能体编排 + 隐私网关 + 50+ 工具集成 |
| 36 | [verialabs/ctf-agent](https://github.com/verialabs/ctf-agent) | 613 | Python | CTF Agent | 自主 CTF solver，BSidesSF 2026 第一名 |
| 37 | [westonbrown/Cyber-AutoAgent](https://github.com/westonbrown/Cyber-AutoAgent) | 534 | TypeScript | 渗透 Agent | XBOW 验证基准 85%，已归档但代表性强 |
| 38 | [crond-jaist/AutoPentest-DRL](https://github.com/crond-jaist/AutoPentest-DRL) | 438 | Python | 强化学习渗透 | 使用深度强化学习的自动化渗透测试 |
| 39 | [0ca/BoxPwnr](https://github.com/0ca/BoxPwnr) | 428 | Python | 渗透 Agent / 多平台基准 | HackTheBox / TryHackMe / picoCTF / Cybench / XBOW 等 15 个平台基准框架 |
| 40 | [ARCANGEL0/EVA](https://github.com/ARCANGEL0/EVA) | 424 | Python | 渗透 Agent | AI 辅助渗透测试代理，多后端 AI 集成 |
| 41 | [m-sec-org/BreachWeave](https://github.com/m-sec-org/BreachWeave) | 419 | TypeScript | 渗透 Agent | Manager/Observer/Solver 多角色架构 |
| 42 | [SHAdd0WTAka/Zen-Ai-Pentest](https://github.com/SHAdd0WTAka/Zen-Ai-Pentest) | 413 | Python | 渗透 Agent | 多代理 AI 渗透框架 + 合规报告 |
| 43 | [transilienceai/communitytools](https://github.com/transilienceai/communitytools) | 407 | Python | Claude 工具集 | 开源 Claude Code skills/agents/slash command |
| 44 | [aielte-research/HackSynth](https://github.com/aielte-research/HackSynth) | 309 | Python | 渗透 Agent | Planner + Summarizer 双模块，PicoCTF / OverTheWire 200 题（arXiv:2412.01778）|
| 45 | [simon-p-j-r/LLM4Pentest](https://github.com/simon-p-j-r/LLM4Pentest) | 297 | - | 研究项目 | LLM4Pentest 研究代码 |
| 46 | [xoxruns/deadend-cli](https://github.com/xoxruns/deadend-cli) | 265 | Python | 渗透 Agent | XBOW 黑盒 81%，约 $122 API 成本，本地化执行 |
| 47 | [yz9yt/BugTrace-AI](https://github.com/yz9yt/BugTrace-AI) | 251 | TypeScript | 漏洞追踪 | （已归档，演进为 BugTraceAI v2） |
| 48 | [GitHubSecurityLab/seclab-taskflow-agent](https://github.com/GitHubSecurityLab/seclab-taskflow-agent) | 212 | Python | Agent 框架 | GitHub Security Lab 出品，YAML 驱动多 Agent + CodeQL |
| 49 | [KHenryAegis/VulnBot](https://github.com/KHenryAegis/VulnBot) | 177 | Python | 渗透 Agent | 多代理协作框架的自主渗透测试 |
| 50 | [chainreactors/tinyctfer](https://github.com/chainreactors/tinyctfer) | 173 | Python | CTF Agent | antix 微型意图运行时 + 元工具设计 |
| 51 | [NYU-LLM-CTF/nyuctf_agents](https://github.com/NYU-LLM-CTF/nyuctf_agents) | 151 | Python | CTF Agent | NYU CTF Bench 配套的 D-CIPHER + Baseline |
| 52 | [antoninoLorenzo/AI-OPS](https://github.com/antoninoLorenzo/AI-OPS) | 143 | Python | 渗透助手 | 基于开源 LLM 的渗透测试 AI 助手 |
| 53 | [andreashappe/cochise](https://github.com/andreashappe/cochise) | 126 | Python | AD 渗透 Agent | 自主 Assumed Breach AD 渗透（TOSEM 2025）|
| 54 | [arthurgervais/mapta](https://github.com/arthurgervais/mapta) | 102 | Python | 渗透 Agent | 多 Agent Web 应用安全评估 + 端到端漏洞利用验证（arXiv:2508.20816）|
| 55 | [vikramrajkumarmajji/AI-VAPT](https://github.com/vikramrajkumarmajji/AI-VAPT) | 100 | TypeScript | VAPT 框架 | 自主 AI 漏洞评估与渗透测试框架 |
| 56 | [amazon-science/Cyber-Zero](https://github.com/amazon-science/Cyber-Zero) | 99 | Python | 训练框架 | 无运行时训练网络安全代理（Amazon Science） |

> 备注：1k–10k 区间的 Star 数为 GitHub 网页缩写值的换算结果；万级以上误差更大。
> *Note: stars in the 1k–10k range are converted from GitHub's abbreviated values; 10k+ may carry larger errors.*

---

## 🧬 进攻型 / 安全专用开源模型
*Offensive & Security-Specialized Open-Weight Models*

> 上面的项目多为"Agent 框架 / 脚手架"，其能力最终取决于底层模型。本节盘点可作为 Offensive AI Agent **推理内核**的开源权重模型，分两类：
> - **A. 无安全对齐 / 弱审查的进攻型模型**：刻意去除或大幅弱化拒答对齐，可直接输出漏洞利用 / 攻击链推理，最适合本地化、无云依赖的红队 Agent 驱动。
> - **B. 安全领域专用模型（含推理 / 漏洞 / 防御对齐）**：面向安全垂域微调，能力强但**保留了不同程度的安全对齐**，进攻场景常需搭配越狱 / 系统提示或作为漏洞检测内核使用。
>
> *These are open-weight models usable as the reasoning core of an offensive AI agent, split into (A) uncensored/weakly-aligned offensive models and (B) security-specialized models that still retain safety alignment.*

### A. 无安全对齐 / 弱审查的进攻型模型
*Uncensored / Weakly-Aligned Offensive Models*

| # | 模型 | 参数量 | 基座 | 发布方 | 定位与特色 |
|---|------|-------|------|--------|-----------|
| 1 | [Qwythos-9B-Claude-Mythos-5-1M](https://huggingface.co/bestexhibitions/Qwythos-9B-Claude-Mythos-5-1M) <small>*⭐新补充*</small>（[Ollama](https://github.com/mickyhq/qwythos)）| 9B | Qwen3.5-9B（深度无审查）| Empero AI | 🔥 **"Claude 平替"级无审查推理模型**，后训练超 5 亿 token Claude Mythos/Fable 思维链，1M 上下文 + 自我纠正工具调用，4GB 显存即可本地运行，MMLU +34.3 / gsm8k +30 大幅超越基座 |
| 2 | [WhiteRabbitNeo / DeepHat](https://huggingface.co/WhiteRabbitNeo)（[DeepHat-V1-7B](https://ollama.com/DeepHat)、13B、33B、70B）| 7B–70B | Llama / Qwen / DeepSeek | Kindo.ai | 最知名的**无审查红队模型**家族，2025 Black Hat 后更名 DeepHat。面向真实进攻推理、长上下文分析，可映射立足点、串联弱点、探索利用路径 |
| 3 | [Lily-Cybersecurity-7B-v0.2](https://huggingface.co/segolilylabs/Lily-Cybersecurity-7B-v0.2) | 7B | Mistral-7B | Sego Lily Labs | Mistral 微调，22,000 条手工构造的网络安全 / 黑客问答对，无强拒答对齐，适合本地渗透问答助手 |
| 4 | [BaronLLM (Offensive Security LLM)](https://huggingface.co/AlicanKiraz0)（[GGUF Q6_K](https://www.aimodels.fyi/models/huggingFace/cybersecurity-baronllm-offensive-security-llm-q6-k-gguf-alicankiraz0)）| 7B/8B 级 | — | AlicanKiraz0 | 专为**进攻性安全研究、对抗模拟、红队**微调的模型，输出偏向 exploit / 攻击链推理 |
| 5 | [CyberStrike-OffSec-35B](https://huggingface.co/oyildirim/CyberStrike-OffSec-35B) <small>*⭐新补充*</small> | 35B MoE（激活 3B）| Qwen3.6-35B-A3B | Orhan Yildirim | **35B 混合专家进攻性安全模型**，SFT+DPO 训练，专攻漏洞利用开发 / 红队行动 / 云攻击 / 免杀技术，自称**多个安全基准超越 GPT-4**，**无安全对齐** |
| 6 | [BugTraceAI-CORE-Ultra-27B](https://huggingface.co/BugTraceAI/BugTraceAI-CORE-Ultra-27B-Q6) <small>*⭐新补充*</small> | 27B | Qwen3.6-27B | BugTraceAI | 基于 2,541 份**真实漏洞赏金报告 + CVE 分析 + 进攻性安全研究** SFT 微调，专注漏洞发现与 Nuclei 模板生成，面向 Bug Bounty 场景 |

> ⚠️ 说明：此类模型刻意弱化安全对齐，可直接产出攻击性内容，**必须严格限定于授权测试 / 隔离环境**（详见文末免责声明）。
> *These models intentionally weaken safety alignment; use only within authorized, isolated environments.*

### B. 安全领域专用模型（含推理 / 漏洞 / 防御对齐）
*Security-Specialized Models (Reasoning / VulnDetect / Defense-Aligned)*

| # | 模型 | 参数量 | 基座 | 发布方 | 定位与特色 | 对齐属性 |
|---|------|-------|------|--------|-----------|---------|
| 1 | [VulnLLM-R-7B](https://huggingface.co/Mungert/VulnLLM-R-7B-GGUF)（[代码](https://github.com/ucsb-mlsec/VulnLLM-R)）| 7B | Qwen 系 | UCSB-SURFI | **漏洞挖掘推理**模型，逐步推理数据流 / 控制流 / 安全上下文；在 Python/C/C++/Java 上超越 CodeQL、AFL++、Claude-3.7 等（arXiv:2512.07533）| 面向检测，弱进攻对齐 |
| 2 | [Foundation-Sec-8B-Reasoning](https://huggingface.co/fdtn-ai/Foundation-Sec-8B-Reasoning) | 8B | Llama-3.1-8B | Cisco Foundation AI | "全球首个安全推理模型"，安全垂域指令微调，可本地部署驱动 AI 安全工具（arXiv:2601.21051）| 通用安全，保留对齐 |
| 3 | [CyberSecQwen-4B](https://huggingface.co/athena129/CyberSecQwen-4B) | 4B | Qwen3-4B-Instruct | AMD Hackathon / athena129 | 轻量**防御性**安全模型，专攻 CVE→CWE 映射（CTI-RCM）与威胁情报选择题（CTI-MCQ），4B 却超 8B 基座 | 明确防御导向 |
| 4 | [Meta-SecAlign-8B](https://huggingface.co/facebook/Meta-SecAlign-8B)（[70B](https://github.com/facebookresearch/Meta_SecAlign)）| 8B / 70B | Llama-3.1 | Meta (FAIR) | 首个**内建 prompt injection 防御**的全开源商用级 LLM（arXiv:2507.02735）；本质是**防御对齐标杆**，可作红队攻防的"蓝方"陪练 | 强防御对齐（非进攻）|
| 5 | [Titus-CybersecurityLLM-v1.0](https://huggingface.co/AlicanKiraz0/Titus-CybersecurityLLM-v1.0-mlx-4Bit) <small>*⭐新补充*</small> | 35B MoE | Qwen3.6-35B-A3B | AlicanKiraz0 | 面向 SOC/DFIR 的网络安全操作模型，土耳其语优先 + 英文，含 MLX 4-bit 量化版（19.5GB VRAM），与 BaronLLM 同一作者 | 偏防御（SOC/DFIR 导向）|

> 甄别提示：**VulnLLM-R / Foundation-Sec / CyberSecQwen / Meta-SecAlign / Titus 均非"无对齐进攻模型"**——它们分别偏漏洞检测、安全推理、防御问答、抗注入防御与 SOC/DFIR 运营。真正"无安全对齐、适合直接进攻"的是 A 类（Qwythos、WhiteRabbitNeo/DeepHat、Lily、BaronLLM、CyberStrike-OffSec-35B、BugTraceAI-CORE-Ultra）。将它们并列收录，是为了呈现"进攻内核 vs 安全垂域 / 防御对齐"的完整光谱，便于选型时对症下药。
> *Selection note: only Group A models are genuinely uncensored/offensive; Group B are vuln-detection, reasoning, or defense-aligned models included for a complete spectrum.*

---

## 🧩 进攻型 AI Skill 资源精选
*Offensive AI Skills (Claude Code / Agent Skills Ecosystem)*

> 除了独立 Agent 与底层模型，**Agent Skill**（如 Claude Code Skills、[agentskills.io](https://agentskills.io) / [skills.sh](https://skills.sh) 生态）正成为"进攻型 AI"落地到通用 AI 编程客户端的重要形态——把渗透测试方法论、工具链调用顺序与 payload/字典打包为可被 Agent 按需自动加载的结构化技能模块。仅收录**纯 Skill 形态**（非 Agent/Subagent 混合项目）、Star ≥ 100 的仓库，按 Star 数降序排列。
> *Agent Skills package pentest methodology, tool-chains, and payloads/wordlists into structured modules that general-purpose AI coding agents (e.g. Claude Code) can auto-load on demand. Only pure-Skill repos (excluding Agent/Subagent-hybrid projects) with ≥ 100 stars are listed, sorted by stars (desc).*

| # | 仓库 | Stars | 载体 / 生态 | 定位与特色 |
|---|------|-------|-----------|-----------|
| 1 | [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) <small>*⭐新补充*</small> | 26.1k | Agent Skills（agentskills.io 标准，20+ 平台兼容） | 🔥 **全球最大开源网安 Agent Skill 库**，817 个结构化技能覆盖 29 大安全域（红队/渗透/云安全/取证/威胁狩猎等），业界唯一六框架映射（ATT&CK/NIST CSF/ATLAS/D3FEND/AI RMF/F3），社区非官方项目 |
| 2 | [ljagiello/ctf-skills](https://github.com/ljagiello/ctf-skills) | 2.8k | Agent Skills（Claude Code 等） | CTF 全领域技能包，覆盖 Web/Pwn/密码学/逆向/取证/OSINT/恶意软件/AI-ML 等 10 大类，内置 `solve-challenge` 总调度器自动分发题型 |
| 3 | [Eyadkelleh/awesome-skills-security](https://github.com/Eyadkelleh/awesome-skills-security) | 337 | Agent Skills（60+ Agent 兼容） | 基于 SecLists 精选打包为 7 类技能（Fuzzing/密码字典/敏感模式/Payload/用户名/Webshell/LLM 测试），一键安装 |

> ⚠️ 上述 Skill 本身通常**不内置攻击性代码**，仅提供方法论、脚本编排与工具调用规范；实际执行仍依赖用户自行安装的安全工具，且必须严格限定于授权测试场景。
> *These skills mostly provide methodology/orchestration rather than embedded exploit code; actual execution still relies on separately installed security tools and must remain within authorized testing scope.*

---

## 🔌 进攻型 AI MCP Server 精选
*Offensive AI MCP Servers*

> **MCP（Model Context Protocol）**让 AI Agent 以标准化协议直接调用真实安全工具，是"进攻型 AI"从推理走向实际执行的关键基础设施——Burp、Metasploit、Nmap 等工具借此被"AI 化"。仅收录**安全工具集合类** MCP Server（非单一 Agent 项目自带的 MCP 组件）、Star ≥ 100 的仓库，按 Star 数降序排列。
> *MCP servers let AI agents invoke real security tools via a standardized protocol — the execution layer that turns offensive AI reasoning into action. Only dedicated security-tool MCP servers (excluding MCP components bundled inside a single agent project) with ≥ 100 stars are listed, sorted by stars (desc).*

| # | 仓库 | Stars | 语言 | 定位与特色 |
|---|------|-------|------|-----------|
| 1 | [PortSwigger/mcp-server](https://github.com/portswigger/mcp-server) | 990 | Kotlin | **PortSwigger 官方**出品，Burp Suite 扩展，桥接 Burp 与 MCP 客户端（Claude Desktop 等），SSE + Stdio 双模式 |
| 2 | [Wh0am123/MCP-Kali-Server](https://github.com/Wh0am123/MCP-Kali-Server) <small>*⭐新补充*</small> | 775 | Python | **已收录 Kali 官方软件源**（`apt install mcp-kali-server`）的轻量级 API 桥接，集成 nmap/hydra/sqlmap/metasploit/wpscan 等，支持 AI 辅助渗透与 CTF/HTB/THM 靶场解题 |
| 3 | [FuzzingLabs/mcp-security-hub](https://github.com/FuzzingLabs/mcp-security-hub) | 742 | Python | 38 个容器化 MCP 服务器集合，覆盖侦察/Web/二进制分析/区块链/云/模糊测试/AD 等，共 300+ 安全工具，生产级安全加固 |
| 4 | [GH05TCREW/MetasploitMCP](https://github.com/GH05TCREW/MetasploitMCP) | 696 | Python | Metasploit 框架 MCP 桥接，支持 exploit/payload 生成、会话管理、Handler 监听器全流程操作 |
| 5 | [MorDavid/BloodHound-MCP-AI](https://github.com/MorDavid/BloodHound-MCP-AI) <small>*⭐新补充*</small> | 369 | Python | 首个 **BloodHound AI 集成**，75+ 工具将 Cypher 查询封装为自然语言，专攻 AD 攻击路径分析（Kerberoasting/AS-REP Roasting/NTLM 中继/委派滥用）|
| 6 | [BurtTheCoder/mcp-shodan](https://github.com/BurtTheCoder/mcp-shodan) <small>*⭐新补充*</small> | 145 | TypeScript | Shodan API + CVEDB 查询 MCP，IP 侦察/DNS 操作/联网设备发现/CVE-CPE 关联查询，支持 Claude Code、Codex、Gemini CLI |
| 7 | [DMontgomery40/pentest-mcp](https://github.com/DMontgomery40/pentest-mcp) | 139 | JavaScript/TS | 面向专业渗透测试者的实战级 MCP 服务器，内置 nmap/hydra/sqlmap/nuclei/hashcat 等，含 SoW 授权范围采集与 Prompt Injection 风险缓解 |

> ⚠️ 此类 MCP Server 通常直接封装真实攻击性工具（Metasploit、sqlmap、hashcat 等），风险等级高于 Skill 类资源，**必须部署于隔离环境并严格限定授权范围**。
> *These MCP servers wrap real offensive tools directly and carry higher risk than skill-based resources — deploy only in isolated, explicitly authorized environments.*

---

## 🏆 知名 AI 攻防 / 智能渗透赛事
*Notable AI Offense-Defense & Intelligent Penetration Competitions*

> 本节收录全球范围内具有代表性的 **AI 驱动攻防 / 自主渗透** 竞技赛事，是检验 Agent 实战能力的"竞技场"，产出的开源系统往往代表当前工程实践的最高水准。
> *This section covers representative AI-driven offense-defense / autonomous penetration competitions worldwide — the "arenas" that stress-test Agent capabilities, whose open-sourced systems often represent state-of-the-art engineering practice.*

### 1. DARPA AIxCC 2025
*DARPA AI Cyber Challenge 2025 Final*

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

### 2. 腾讯云智能渗透黑客松
*Tencent Cloud Intelligent Penetration Hackathon*

> **腾讯安全云鼎实验室**主办，国内首个聚焦 **LLM 智能体全流程自动化渗透** 的顶级专业赛事，理念"铸刃止戈、以智御危"。已连续举办两届，累计汇聚清华大学、复旦大学、帝国理工学院、卡内基梅隆大学等国内外知名高校学生战队，鹏城实验室、中国科学院信息工程研究所等权威科研机构专家战队，以及阿里、京东、长亭、绿盟等行业领军企业战队，参赛规模从第一届 238 支战队/518 名选手增长至第二届 610 支战队/1,345 名选手，累计产出 20 套顶尖智能渗透技术框架。赛制核心导向为**纯 AI 驱动渗透，严格限制人工操作**，前 20 名可获开源贡献奖。官方资源仓：[Yeti-791/Tsec-Hackathon](https://github.com/Yeti-791/Tsec-Hackathon)（709 Stars）。
> *Hosted by Tencent Security Yunding Lab, the first domestic top-tier competition focused on **LLM-agent fully-automated penetration**. Two editions held so far, growing from 238 teams/518 competitors to 610 teams/1,345 competitors, producing 20 leading intelligent-penetration frameworks. Strictly AI-driven with manual operation prohibited. Official repo: [Yeti-791/Tsec-Hackathon](https://github.com/Yeti-791/Tsec-Hackathon).*

| 届次 | 时间 | 冠军战队 | 参与规模 |
|:----:|------|---------|---------|
| 第一届 | 2025-11 | xjtuHunter（西安交大）第2名 / BinX（广州大学）第3名 | 清华大学、复旦大学、帝国理工学院、卡内基梅隆大学等国内外知名高校学生战队，鹏城实验室、中国科学院信息工程研究所等权威科研机构专家战队，以及阿里、京东、长亭等行业领军企业战队，共计 **238 支战队、518 名顶尖选手**参与 |
| 第二届 | 2026-04 | ai小分队（第1名）/ Bytex（第3名，全场唯一 AK） | 首创"智能渗透主赛场 +『零界』平行赛场"双轨竞技模式，参赛规模在第一届基础上增长至 **610 支战队、1,345 名安全极客与 AI 研究者**；获奖队伍包括绿盟科技、京东、天翼安全、中国电信、清华大学、奇盾信息等 |

---

## 📑 相关学术论文
*Related Academic Papers (grouped by topic; within each group, newest first)*

> 在原有基础上，融合了 [tmylla/Awesome-LLM4Cybersecurity](https://github.com/tmylla/Awesome-LLM4Cybersecurity/blob/main/LITERATURES.md) 中渗透测试、进攻 AI、漏洞挖掘相关章节。共收录 **73 篇**代表性论文，按主题拆为 3 个子表：
> - **A. 渗透测试 & 红队 Agent**
> - **B. 漏洞挖掘 / 利用 / 修复**
> - **C. 评测基准 & 训练方法 & 奠基论文**
>
> 时间以 arXiv v1 提交日期为准；<small>*⭐新补充*</small> 表示 2026-07 本轮新增，ⓝ 为往轮补充。
>
> *Three sub-tables: (A) Pentesting & Red-Team Agents · (B) Vulnerability Discovery / Exploitation / Repair · (C) Evaluation, Training & Foundational. <small>*⭐新补充*</small> = added this round (2026-07); ⓝ = added in earlier rounds.*

### A. 渗透测试 & 红队 Agent
*Pentesting & Red-Team Agents*

| # | 时间 | 论文 | 作者 / 机构 | 发表渠道 | 关联项目 / 主题 |
|---|------|------|-----------|---------|---------------|
| A1 | 2026-07 | [A Survey of LLM-Driven Penetration Testing: From Foundations to Agents4Pentest](https://arxiv.org/abs/2607.02605) <small>*⭐新补充*</small> | — | arXiv | LLM 渗透测试系统综述，提出 Agents4Pentest 概念 |
| A2 | 2026-06 | [ZERO-APT: A Closed-Loop Adversarial Framework for LLM Penetration Agents](https://arxiv.org/abs/2606.05567) <small>*⭐新补充*</small> | Zheng, Zhu et al. | arXiv | 攻击者-防御者-裁判回合制闭环，含智能防御压力 |
| A3 | 2026-04 | [Hackers or Hallucinators? A Comprehensive Analysis of LLM-Based Automated Penetration Testing](https://arxiv.org/abs/2604.05719) <small>*⭐新补充*</small> | — | arXiv | [simon-p-j-r/LLM4Pentest](https://github.com/simon-p-j-r/LLM4Pentest) |
| A4 | 2026-01 | [PenForge: On-the-Fly Expert Agent Construction for Automated Penetration Testing](https://arxiv.org/abs/2601.06910) ⓝ | — | arXiv | 动态构造领域专家 Agent |
| A5 | 2025-12 | [PentestEval: Benchmarking LLM-based Penetration Testing with Modular and Stage-Level Design](https://arxiv.org/abs/2512.14233) ⓝ | — | arXiv | 模块化 / 阶段化渗透测试评估 |
| A6 | 2025-12 | [Comparing AI Agents to Cybersecurity Professionals in Real-World Penetration Testing](https://arxiv.org/abs/2512.09882) ⓝ | — | arXiv | AI Agent vs 人类渗透测试师 |
| A7 | 2025-10 | [AutoPentester: An LLM Agent-based Framework for Automated Pentesting](https://arxiv.org/abs/2510.05605) ⓝ | — | arXiv | 通用自动化渗透 Agent |
| A8 | 2025-09 | [xOffense: Autonomous Penetration Testing with Offensive Knowledge-enhanced LLMs and Multi-Agent Systems](https://arxiv.org/abs/2509.13021) | Luong, Bao et al. | arXiv | 微调 Qwen3-32B 多 Agent |
| A9 | 2025-09 | [Guided Reasoning in LLM-Driven Penetration Testing Using Structured Attack Trees](https://arxiv.org/abs/2509.07939) ⓝ | — | arXiv | 攻击树结构化推理 |
| A10 | 2025-08 | [CurriculumPT: LLM-Based Multi-Agent Autonomous Penetration Testing with Curriculum-Guided Learning](https://www.mdpi.com/2076-3417/15/16/9096) <small>*⭐新补充*</small> | — | Applied Sciences 2025 | 课程式学习引导的多 Agent 渗透 |
| A11 | 2025-08 | [MAPTA: Multi-Agent Web Application Security Assessment](https://arxiv.org/abs/2508.20816) | Arthur Gervais 等 | arXiv | [arthurgervais/mapta](https://github.com/arthurgervais/mapta) |
| A12 | 2025-08 | [Pentest-R1: Towards Autonomous Penetration Testing Reasoning Optimized via Two-Stage RL](https://arxiv.org/abs/2508.07382) ⓝ | — | arXiv | 两阶段强化学习渗透推理 |
| A13 | 2025-07 | [PenTest2.0: Towards Autonomous Privilege Escalation Using GenAI](https://arxiv.org/abs/2507.06742) ⓝ | — | arXiv | 自主提权 |
| A14 | 2025-07 | [On the Surprising Efficacy of LLMs for Penetration-Testing](https://arxiv.org/abs/2507.00829) ⓝ | — | arXiv | LLM 渗透有效性实证 |
| A15 | 2025-05 | [AutoPentest: Enhancing Vulnerability Management With Autonomous LLM Agents](https://arxiv.org/abs/2505.10321) ⓝ | — | arXiv | 漏洞管理 Agent |
| A16 | 2025-05 | [RedTeamLLM: an Agentic AI framework for offensive security](https://arxiv.org/abs/2505.06913) | LRE Security Systems Team | arXiv | 含错误恢复机制 |
| A17 | 2025-04 | [CAI: An Open, Bug Bounty-Ready Cybersecurity AI](https://arxiv.org/abs/2504.06017) ⓝ | aliasrobotics | arXiv | [aliasrobotics/cai](https://github.com/aliasrobotics/cai) |
| A18 | 2025-02 | [Construction and Evaluation of LLM-based Agents for Semi-Autonomous Penetration Testing](https://arxiv.org/abs/2502.15506) ⓝ | — | arXiv | 半自主渗透 Agent 构造与评估 |
| A19 | 2025-02 | [RapidPen: Fully Automated IP-to-Shell Penetration Testing with LLM-based Agents](https://arxiv.org/abs/2502.16730) ⓝ | — | arXiv | IP → Shell 全自动渗透 |
| A20 | 2025-02 | [PenTest++: Elevating Ethical Hacking with AI and Automation](https://arxiv.org/abs/2502.09484) ⓝ | — | arXiv | 道德黑客 AI 自动化升级 |
| A21 | 2025-02 | [Can LLMs Hack Enterprise Networks? Autonomous Assumed Breach Penetration-Testing AD](https://arxiv.org/abs/2502.04227) | Andreas Happe, Jürgen Cito | ACM TOSEM 2025 | [andreashappe/cochise](https://github.com/andreashappe/cochise) |
| A22 | 2025-02 | [D-CIPHER: Dynamic Collaborative Intelligent Multi-Agent System for CTF](https://arxiv.org/abs/2502.10931) | NYU LLM CTF Team | arXiv | [NYU-LLM-CTF/nyuctf_agents](https://github.com/NYU-LLM-CTF/nyuctf_agents) |
| A23 | 2025-01 | [Incalmo: An Autonomous LLM-assisted System for Red Teaming Multi-Host Networks](https://arxiv.org/abs/2501.16466) | Singer, Ben et al. | arXiv | 多主机企业红队 |
| A24 | 2025-01 | [VulnBot: Autonomous Penetration Testing for A Multi-Agent Collaborative Framework](https://arxiv.org/abs/2501.13411) | KHenryAegis 等 | arXiv | [KHenryAegis/VulnBot](https://github.com/KHenryAegis/VulnBot) |
| A25 | 2024-12 | [HackSynth: LLM Agent and Evaluation Framework for Autonomous Penetration Testing](https://arxiv.org/abs/2412.01778) | Lajos Muzsai et al. (ELTE) | arXiv | [aielte-research/HackSynth](https://github.com/aielte-research/HackSynth) |
| A26 | 2024-12 | [Hacking CTFs with Plain Agents](https://arxiv.org/abs/2412.02776) ⓝ | — | arXiv | 朴素 Agent + 简单脚手架打 CTF |
| A27 | 2024-11 | [PentestAgent: Incorporating LLM Agents to Automated Penetration Testing](https://arxiv.org/abs/2411.05185) | Xiangmin Shen et al. | ASIA CCS 2025 | [GH05TCREW/pentestagent](https://github.com/GH05TCREW/pentestagent) |
| A28 | 2024-11 | [AutoPT: How Far Are We from the End2End Automated Web Penetration Testing?](https://arxiv.org/abs/2411.01236) ⓝ | — | arXiv | 端到端 Web 渗透 |
| A29 | 2024-09 | [BreachSeek: A Multi-Agent Automated Penetration Tester](https://arxiv.org/abs/2409.03789) | Ibrahim Alshehri et al. | arXiv | 多 Agent 渗透 |
| A30 | 2024-09 | [Hacking, The Lazy Way: LLM Augmented Pentesting](https://arxiv.org/abs/2409.09493) ⓝ | — | arXiv | "懒人"式 LLM 增强渗透 |
| A31 | 2024-09 | [EnIGMA: Interactive Tools Substantially Assist LM Agents in Finding Security Vulnerabilities](https://arxiv.org/abs/2409.16165) | Talor Abramovich et al. (Princeton/NYU) | ICML 2025 | CTF 自主求解 LM Agent |
| A32 | 2024-08 | [CIPHER: Cybersecurity Intelligent Penetration-testing Helper for Ethical Researcher](https://arxiv.org/abs/2408.11650) ⓝ | — | Sensors 2024 | 道德渗透助手 |
| A33 | 2024-07 | [PenHeal: A Two-Stage LLM Framework for Automated Pentesting and Optimal Remediation](https://arxiv.org/abs/2407.17788) ⓝ | — | ACSW 2024 | 两阶段：渗透 + 修复 |
| A34 | 2024-07 | [From Sands to Mansions: Enabling Automatic Full-Life-Cycle Cyberattack Construction with LLM](https://arxiv.org/abs/2407.16928) ⓝ | — | arXiv | 全生命周期攻击构造 |
| A35 | 2024-03 | [AutoAttacker: A Large Language Model Guided System to Implement Automatic Cyber-attacks](https://arxiv.org/abs/2403.01038) | Jiacen Xu et al. (UC Irvine) | arXiv | 后渗透阶段 LLM 自动化攻击 |
| A36 | 2023-08 | [PentestGPT: An LLM-empowered Automatic Penetration Testing Tool](https://arxiv.org/abs/2308.06782) | Gelei Deng et al. (NTU) | USENIX Security 2024 | [GreyDGL/PentestGPT](https://github.com/GreyDGL/PentestGPT) |
| A37 | 2023-08 | [Getting pwn'd by AI: Penetration Testing with Large Language Models](https://arxiv.org/abs/2308.00121) | Andreas Happe, Jürgen Cito (TU Wien) | ESEC/FSE 2023 | 奠基论文，hackingBuddyGPT 前身 |

### B. 漏洞挖掘 / 利用 / 修复
*Vulnerability Discovery / Exploitation / Repair*

| # | 时间 | 论文 | 作者 / 机构 | 发表渠道 | 关联项目 / 主题 |
|---|------|------|-----------|---------|---------------|
| B1 | 2026-05 | [FuzzingBrain V2: A Multi-Agent LLM System for Automated Vulnerability Discovery and Reproduction](https://arxiv.org/abs/2605.21779) <small>*⭐新补充*</small> | — | arXiv | 构建于 OSS-Fuzz，实战挖出 29 个 0day（2 个获 CVE）|
| B2 | 2025-10 | [LLM Agents for Automated Web Vulnerability Reproduction: Are We There Yet?](https://arxiv.org/abs/2510.14700) ⓝ | — | arXiv | Web 漏洞自动复现实证 |
| B3 | 2025-09 | [VulnRepairEval: An Exploit-Based Evaluation Framework for Assessing LLM Vulnerability Repair](https://arxiv.org/abs/2509.03331) ⓝ | — | arXiv | 基于 exploit 的修复评测 |
| B4 | 2025-09 | [Synergizing Static Analysis with Large Language Models for Vulnerability Discovery and beyond](https://arxiv.org/abs/2509.15433) ⓝ | — | arXiv | SAST + LLM 协同 |
| B5 | 2025-09 | [ATLANTIS: AI-driven Threat Localization, Analysis, and Triage Intelligence System](https://arxiv.org/abs/2509.14589) ⓝ | Team Atlanta | arXiv | AIxCC 决赛冠军 CRS 论文 |
| B6 | 2025-09 | [All You Need Is A Fuzzing Brain: An LLM-Powered System for Automated Vulnerability Detection and Patching](https://arxiv.org/abs/2509.07225) ⓝ | — | arXiv | AIxCC 决赛 4 队系统论文（FuzzingBrain V1）|
| B7 | 2025-08 | [Prompt to Pwn: Automated Exploit Generation for Smart Contracts](https://arxiv.org/abs/2508.01371) ⓝ | — | arXiv | 智能合约自动 Exploit 生成 |
| B8 | 2025-07 | [LLMxCPG: Context-Aware Vulnerability Detection Through Code Property Graph-Guided LLMs](https://arxiv.org/abs/2507.16585) ⓝ | — | USENIX Security 2025 | CPG 引导的上下文感知漏洞检测 |
| B9 | 2025-07 | [MalCodeAI: Autonomous Vulnerability Detection and Remediation via Language Agnostic Code Reasoning](https://arxiv.org/abs/2507.10898) ⓝ | — | arXiv | 跨语言自治漏洞检测 + 修复 |
| B10 | 2025-05 | [VADER: A Human-Evaluated Benchmark for Vulnerability Assessment, Detection, Explanation, and Remediation](https://arxiv.org/abs/2505.19395) ⓝ | — | arXiv | 漏洞评估 / 解释 / 修复人评基准 |
| B11 | 2025-04 | [PwnGPT: Automatic Exploit Generation Based on Large Language Models](https://aclanthology.org/2025.acl-long.562.pdf) ⓝ | — | ACL 2025 | 自动 Exploit 生成 |
| B12 | 2025-03 | [CVE-Bench: A Benchmark for AI Agents' Ability to Exploit Real-World Vulnerabilities](https://arxiv.org/abs/2503.17332) | UIUC Kang Lab | ICML 2025 | [uiuc-kang-lab/cve-bench](https://github.com/uiuc-kang-lab/cve-bench) |
| B13 | 2025-03 | [CVE-Bench (NAACL): Benchmarking LLM-based Software Engineering Agent's Ability to Repair Real-World CVE Vulnerabilities](https://aclanthology.org/2025.naacl-long.212/) ⓝ | — | NAACL 2025 | 真实 CVE 修复评测（注：与 ICML 版同名不同任务）|
| B14 | 2025-03 | [CASTLE: Benchmarking Dataset for Static Code Analyzers and LLMs towards CWE Detection](https://arxiv.org/abs/2503.09433) ⓝ | — | arXiv | CWE 检测基准 |
| B15 | 2024-12 | [AI Cyber Risk Benchmark: Automated Exploitation Capabilities](https://arxiv.org/abs/2410.21939) ⓝ | — | arXiv | 自动化漏洞利用能力基准 |
| B16 | 2024-07 | [eyeballvul: a future-proof benchmark for vulnerability detection in the wild](https://arxiv.org/abs/2407.08708) ⓝ | — | arXiv | 防训练泄漏的漏洞检测基准 |
| B17 | 2024-06 | [Teams of LLM Agents can Exploit Zero-Day Vulnerabilities](https://arxiv.org/abs/2406.01637) | Richard Fang et al. (UIUC) | arXiv | 多 Agent 协作 0day 利用 |
| B18 | 2024-04 | [LLM Agents can Autonomously Exploit One-day Vulnerabilities](https://arxiv.org/abs/2404.08144) | Richard Fang et al. (UIUC) | arXiv | 已知 CVE 报告 → 自动利用 |
| B19 | 2024-02 | [LLM Agents can Autonomously Hack Websites](https://arxiv.org/abs/2402.06664) | Richard Fang et al. (UIUC) | arXiv | LLM Agent 自主攻击网站（早期工作）|

### C. 评测基准 & 训练方法 & 综述 & 奠基
*Evaluation Benchmarks, Training Methods, Surveys & Foundational*

| # | 时间 | 论文 | 作者 / 机构 | 发表渠道 | 关联项目 / 主题 |
|---|------|------|-----------|---------|---------------|
| C1 | 2026-05 | [CTFusion: A CTF-based Benchmark for LLM Agent Evaluation](https://arxiv.org/abs/2605.11504) <small>*⭐新补充*</small> | Lee, Bae et al. | arXiv | 基于 Live CTF 的流式评测框架，抗数据污染 / 作弊 |
| C2 | 2025-10 | [PACEbench: A Framework for Evaluating Practical AI Cyber-Exploitation Capabilities](https://arxiv.org/abs/2510.11688) ⓝ | — | arXiv | 实战 AI 网络利用能力评测 |
| C3 | 2025-08 | [Towards Effective Offensive Security LLM Agents (CTFTiny + CTFJudge)](https://arxiv.org/abs/2508.05674) | Shao, Rani et al. | AAAI 2026 | CTFTiny / CTFJudge |
| C4 | 2025-07 | [Cyber-Zero: Training Cybersecurity Agents without Runtime](https://arxiv.org/abs/2508.00910) | Terry Yue Zhuo et al. (Amazon AGI / Monash) | arXiv | [amazon-science/Cyber-Zero](https://github.com/amazon-science/Cyber-Zero) |
| C5 | 2025-06 | [CyberGym: Evaluating AI Agents on Real-World Vulnerability Analysis](https://arxiv.org/abs/2506.02548) | Zhun Wang et al. (UC Berkeley Sunblaze) | ICLR 2026 | [sunblaze-ucb/cybergym](https://github.com/sunblaze-ucb/cybergym) |
| C6 | 2025-06 | [SEC-bench: Automated Benchmarking of LLM Agents on Real-World Software Security Tasks](https://arxiv.org/abs/2506.11791) | SEC-bench Team | NeurIPS 2025 | [SEC-bench/SEC-bench](https://github.com/SEC-bench/SEC-bench) |
| C7 | 2025-06 | [UDora: A Unified Red Teaming Framework against LLM Agents](https://arxiv.org/abs/2503.01908) | AI-secure 团队 | ICML 2025 | [AI-secure/UDora](https://github.com/AI-secure/UDora) |
| C8 | 2025-04 | [Benchmarking Practices in LLM-driven Offensive Security: Testbeds, Metrics, and Experiment Design](https://arxiv.org/abs/2504.10112) ⓝ | — | arXiv | LLM 进攻安全评测方法学 |
| C9 | 2025-02 | [OCCULT: Evaluating Large Language Models for Offensive Cyber Operation Capabilities](https://arxiv.org/abs/2502.15797) ⓝ | — | arXiv | 进攻性网络作战能力评测 |
| C10 | 2024-10 | [AutoPenBench: Benchmarking Generative Agents for Penetration Testing](https://arxiv.org/abs/2410.03225) | Luca Gioacchini et al. (Politecnico di Torino) | EMNLP Industry 2025 | [lucagioacchini/auto-pen-bench](https://github.com/lucagioacchini/auto-pen-bench) |
| C11 | 2024-10 | [Towards Automated Penetration Testing: Introducing LLM Benchmark, Analysis, and Improvements](https://arxiv.org/abs/2410.17141) ⓝ | — | arXiv | 渗透测试 LLM 基准 + 改进 |
| C12 | 2024-08 | [CYBERSECEVAL 3: Advancing the Evaluation of Cybersecurity Risks and Capabilities in LLMs](https://arxiv.org/abs/2408.10627) | Meta Purple Llama Team | arXiv | [meta-llama/PurpleLlama](https://github.com/meta-llama/PurpleLlama) v3 |
| C13 | 2024-08 | [Cybench: A Framework for Evaluating Cybersecurity Capabilities and Risk of Language Models](https://arxiv.org/abs/2408.08926) | Andy K. Zhang et al. (Stanford CRFM) | ICLR 2025 | [andyzorigin/cybench](https://github.com/andyzorigin/cybench) |
| C14 | 2024-07 | [AgentPoison: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases](https://arxiv.org/abs/2407.12784) | Zhaorun Chen et al. (UChicago) | NeurIPS 2024 | LLM Agent 后门 / 记忆投毒 |
| C15 | 2024-06 | [NYU CTF Bench: A Scalable Open-Source Benchmark for Evaluating LLMs in Offensive Security](https://arxiv.org/abs/2406.05590) | Talor Abramovich et al. (NYU) | NeurIPS 2024 D&B | [NYU-LLM-CTF/NYU_CTF_Bench](https://github.com/NYU-LLM-CTF/NYU_CTF_Bench) |
| C16 | 2023-12 | [Purple Llama CyberSecEval: A Secure Coding Benchmark for Language Models](https://arxiv.org/abs/2312.04724) | Meta Purple Llama Team | arXiv | [meta-llama/PurpleLlama](https://github.com/meta-llama/PurpleLlama) v1 |
| C17 | 2023-06 | [InterCode: Standardizing and Benchmarking Interactive Coding with Execution Feedback](https://arxiv.org/abs/2306.14898) | John Yang et al. (Princeton NLP) | NeurIPS 2023 D&B | [princeton-nlp/intercode](https://github.com/princeton-nlp/intercode) |

> 注：会议/期刊年份为论文实际收录会议届期；arXiv 时间为 v1 提交月份。来源致谢：[tmylla/Awesome-LLM4Cybersecurity](https://github.com/tmylla/Awesome-LLM4Cybersecurity)、[EvanThomasLuke/Awesome-AI-Hacking-Agents](https://github.com/EvanThomasLuke/Awesome-AI-Hacking-Agents)、[ox01024/awesome-offensive-security-ai](https://github.com/ox01024/awesome-offensive-security-ai)。
> *Note: conference years refer to actual proceedings; arXiv dates are v1. Credits to the three awesome lists above.*

---

## 🧪 Agent 能力评测 Benchmark
*Agent Capability Benchmarks (sorted by stars, desc)*

> 用于评估渗透测试 / 网络安全 / CTF / 红队 Agent 能力的开源 benchmark。
> *Open-source benchmarks for evaluating pentest / cybersecurity / CTF / red-team Agent capabilities.*

| # | Benchmark | 仓库 | Stars | 时间 | 任务规模 | 评测重点 | 关联论文 |
|---|-----------|------|-------|------|---------|---------|---------|
| 1 | **TSecBench** <small>*⭐新补充*</small> | [tsecbench.zc.tencent.com](https://tsecbench.zc.tencent.com/) | — | 2026-07 | 从腾讯云黑客松诞生，采用闭卷模式，结果更准确 | 🔥 **腾讯安全云鼎实验室**出品，智能攻防 AI Agent 统一跑分基准，覆盖 Web/二进制漏洞挖掘、漏洞利用、多阶段渗透、云攻击、对抗规避 6 大维度，支持 3 种 Agent 接入方式 | — |
| 2 | **CyberSecEval (1/2/3/4)** | [meta-llama/PurpleLlama](https://github.com/meta-llama/PurpleLlama) | 4.2k | 2023-12 | 跨多类任务（不安全代码 / Prompt Injection / 攻击辅助 / AutoPatchBench 等） | Meta 出品，覆盖 LLM "防/攻"两端 | [arXiv:2312.04724](https://arxiv.org/abs/2312.04724) / [arXiv:2408.10627](https://arxiv.org/abs/2408.10627) |
| 3 | **XBOW Validation Benchmarks** | [xbow-engineering/validation-benchmarks](https://github.com/xbow-engineering/validation-benchmarks) | 611 | 2025-06 | 104 道 Web 漏洞挑战（Jeopardy CTF） | XBOW（首个登顶 HackerOne 的 AI）出品，覆盖真实渗透 / 赏金漏洞 | XBOW Engineering Blog |
| 4 | **CyberGym** | [sunblaze-ucb/cybergym](https://github.com/sunblaze-ucb/cybergym) | 375 | 2025-06 | 真实世界漏洞分析任务（240GB 数据集） | UC Berkeley 出品，强调 real-world，配 4 个示例 Agent | [arXiv:2506.02548](https://arxiv.org/abs/2506.02548)（ICLR 2026）|
| 5 | **Cybench** | [andyzorigin/cybench](https://github.com/andyzorigin/cybench) | 256 | 2024-08 | 40 道专业级 CTF 任务（17 个子任务） | Stanford CRFM，支持 Unguided / Subtask 双模式 | [arXiv:2408.08926](https://arxiv.org/abs/2408.08926)（ICLR 2025）|
| 6 | **InterCode-CTF** | [princeton-nlp/intercode](https://github.com/princeton-nlp/intercode) | 248 | 2023-06 | 100 道 picoCTF 题 | Bash/SQL/Python/CTF 交互式代码 Agent 评测 | [arXiv:2306.14898](https://arxiv.org/abs/2306.14898)（NeurIPS 2023 D&B）|
| 7 | **NYU CTF Bench** | [NYU-LLM-CTF/NYU_CTF_Bench](https://github.com/NYU-LLM-CTF/NYU_CTF_Bench) | 153 | 2024-06 | 200 题正式 + 55 题开发集，6 大类 | CSAW CTF 历年题目 + Docker 化部署 | [arXiv:2406.05590](https://arxiv.org/abs/2406.05590)（NeurIPS 2024 D&B）|
| 8 | **AutoPenBench** | [lucagioacchini/auto-pen-bench](https://github.com/lucagioacchini/auto-pen-bench) | 86 | 2024-10 | 33 个任务（22 In-Vitro + 11 真实 CVE） | 生成式 Agent 渗透测试通用评测 | [arXiv:2410.03225](https://arxiv.org/abs/2410.03225)（EMNLP Industry 2025）|
| 9 | **inspect_cyber** | [UKGovernmentBEIS/inspect_cyber](https://github.com/UKGovernmentBEIS/inspect_cyber) | 29 | 2025-06 | 通用扩展（任务可插拔） | UK AI Security Institute 官方 Agentic Cyber 评估扩展 | — |
| 10 | **CVE-Bench** | [uiuc-kang-lab/cve-bench](https://github.com/uiuc-kang-lab/cve-bench) | — | 2025-03 | 40 个 critical 严重程度 CVE | 首个基于真实 CVE 的 Web 漏洞利用 Agent 评测 | [arXiv:2503.17332](https://arxiv.org/abs/2503.17332)（ICML 2025）|
| 11 | **BountyBench** | [bountybench/bountybench](https://bountybench.github.io/) | — | 2025-05 | 25 个真实 GitHub 项目 + Bug Bounty | 用美元金额量化攻防影响力 | Stanford CRFM Blog（2025-05）|
| 12 | **SEC-bench** | [SEC-bench/SEC-bench](https://github.com/SEC-bench/SEC-bench) | — | 2025-06 | 200 个 C/C++ 真实 CVE，PoC + 补丁双任务 | 首个全自动化的真实安全工程评测 | [arXiv:2506.11791](https://arxiv.org/abs/2506.11791)（NeurIPS 2025）|
| 13 | **CTFTiny** | [NYU-LLM-CTF/CTFTiny](https://github.com/NYU-LLM-CTF/CTFTiny) | — | 2025-08 | 50 题轻量 CTF 子集 | 配套 CTFJudge（LLM-as-a-Judge），降低复现成本 | [arXiv:2508.05674](https://arxiv.org/abs/2508.05674)（AAAI 2026）|

> 备注：标 `—` 的 Stars 表示数据缺失或仓库较新。许多 Agent 项目（PentestGPT、cochise、xOffense、Cyber-Zero、deadend-cli 等）会在自己 README 中报告在 NYU CTF Bench / Cybench / AutoPenBench / XBOW 等 Benchmark 上的得分。
> *Note: "—" means missing data or a new repo. Many agent projects report scores against these benchmarks in their own READMEs.*

### Benchmark 选型小贴士｜*Selection Cheatsheet*

| 评测目标 / Goal | 推荐 Benchmark / Recommendation |
|---|---|
| 通用 CTF 能力 / General CTF | NYU CTF Bench（200 题）、Cybench（40 题精选）、InterCode-CTF（轻量起步）|
| 真实漏洞利用 / Real-world Exploit | XBOW（104 Web）、CyberGym（真实漏洞 240GB）、AutoPenBench（CVE 任务）、CVE-Bench（Web）、SEC-bench（C/C++ CVE）、TSecBench（云鼎黑客松靶场）|
| LLM 安全 / 红队基础 / LLM Safety & Red Team | CyberSecEval（Meta 全家桶）|
| 经济影响量化 / Economic Impact | BountyBench |
| 政府级评估扩展 / Government-grade | inspect_cyber（UK AISI）|
| 快速回归 / Lightweight Regression | CTFTiny |

---

## 💼 商业化解决方案
*Commercial Solutions*

> 本节盘点全球范围内主流的 **AI / Agentic 智能渗透测试 / 自主攻击安全** 商业化产品。分为「国外」与「国内」两个子表。**国外部分经全网核查（融资记录、公司估值、官网定价、并购/退出事件、权威媒体报道）后，按公司/产品的融资规模、估值与行业影响力精选 Top 20**——原列表中缺乏可查融资证据、无第三方媒体报道、疑似早期占位官网的长尾条目已剔除（如 KinoSec、Casco、PentX、Revelion、qriousec、Penligent、bugbunny ai、Sec1、Zentinel、Shinobi Security、AutoVAPT.ai、RedVeil.ai、PAIStrike、Novee、AISLE、Pensar、Origin/Prelude、Hound、PentestGPT Pro 等）。国外首位为 Anthropic 的 Mythos（本身为前沿模型而非纯渗透产品，但其安全能力已构成该赛道的现象级存在，故保留）。
> *This section enumerates representative commercial AI / Agentic penetration testing & autonomous offensive security products worldwide. The international table has been fact-checked against funding records, valuations, official pricing pages, M&A/exit events, and credible media coverage, then narrowed to the **Top 20** by funding scale, valuation, and market influence — long-tail entries lacking verifiable funding or press coverage were removed.*

### 🌍 国外厂商 Top 20（按融资规模 / 估值 / 影响力排序）
*International Vendors — Top 20 (ranked by funding, valuation & market influence)*

| # | 公司 | 产品 | 官网 | 融资 / 估值 / 影响力证据 | 产品定位与特色 |
|---|------|------|------|------------------------|---------------|
| 1 | **Anthropic** <small>*⭐新补充*</small> | **Claude Mythos** | [anthropic.com/claude/mythos](https://www.anthropic.com/claude/mythos) | 万亿美元级估值母公司，Project Glasswing 覆盖 150+ 关键基础设施机构 | 🔥 **2026 年最受关注的 AI 安全模型**，无需专项安全训练即能发现数千 0day 并自主编写完整利用链，被美国财政部与美联储联合推荐 |
| 2 | **Pentera** | Pentera AVP | [pentera.io](https://pentera.io/) | 累计融资 $250-314M，**估值 $1B**，ARR 突破 $100M（2026-01），1200+ 企业客户 | AI 驱动的暴露验证平台（Exposure Validation），覆盖身份/终端/网络/云，持续真实攻击模拟（含 LockBit/BlackCat 等勒索家族） |
| 3 | **XBOW** | XBOW | [xbow.com](https://xbow.com/) | 2026-03 完成 **$120M Series C**（DFJ Growth/Northzone 领投），**估值超 $1B**，成立仅 26 个月即成独角兽 | 首个登顶 HackerOne 排行榜的 AI，自主攻击性安全平台，真实 exploit 独立验证每一发现 |
| 4 | **Aikido Security** | Aikido AI Pentest | [aikido.dev/attack/aipentest](https://www.aikido.dev/attack/aipentest) | 2026-01 完成 **$60M Series B**（DST Global 领投），**估值 $1B**，欧洲史上最快独角兽网络安全公司 | All-in-one 应用安全平台，AI Pentest 为其模块之一，代码/云/应用统一安全平台 |
| 5 | **SPLX** | SPLX (含 agentic-radar) | [splx.ai](https://splx.ai/) | **2025-11 被纳斯达克上市公司 Zscaler（NASDAQ: ZS）收购**，商业化验证等级最高的退出事件 | LLM Agent 工作流安全扫描 + 红队，开源 [agentic-radar](https://github.com/splx-ai/agentic-radar) |
| 6 | **Horizon3.ai** | NodeZero® | [horizon3.ai](https://horizon3.ai/) | 累计融资 **$183.5M**，估值 $660-750M（NEA 领投 $100M Series D） | 自称 "World's Best AI Hacker"，无 Agent 部署，已执行 24 万+ 次自主渗透测试，客户含 NSA 与 4 家财富 10 强 |
| 7 | **Hadrian** | Hadrian | [hadrian.io](https://hadrian.io/) | 荷兰/伦敦网络安全公司，多轮 Growth 融资（Notion Capital 等机构），Gartner Peer Insights 常客 | 持续攻击面管理 + Agentic AI 自主渗透，覆盖域名/子域名/证书/IP 全资产测绘 |
| 8 | **RunSybil** | Sybil | [runsybil.com](https://www.runsybil.com/) | 2026-03 完成 **$40M** 融资（Khosla Ventures 领投），创始人为 **OpenAI 首位安全员工** | 自主 Web 应用渗透 AI Agent，强调与人工 pentester 协作 |
| 9 | **Strix (Usestrix)** | Strix | [usestrix.com](https://usestrix.com/) | 开源版本 GitHub **34k+ Stars**（社区影响力最高），商业化融资已启动 | 开源 + 商业双栈 AI 黑客，动态运行代码找漏洞并用真实 PoC 验证 |
| 10 | **Terra Security** | Terra Portal | [terra.security](https://www.terra.security/) | 2025-09 完成 **$30M Series A**（Felicis Ventures 领投），累计融资 $38M+ | 首个 Agentic AI + Human-in-the-Loop 持续渗透测试平台 |
| 11 | **CalypsoAI** | Calypso | [calypsoai.com](https://calypsoai.com/) | 累计融资 $40.8M，**估值 $145M**，2018 年成立的老牌厂商，Gartner Cool Vendor | 企业级 GenAI 安全 + 红队评估 |
| 12 | **Corridor** | Corridor | [corridor.dev](https://corridor.dev/) | 2026-03 完成 **$25M Series A**，创始人 Jack Cable 为美国前 CISA 安全工程师 | AI 生成代码实时安全护栏，源头级漏洞检测 |
| 13 | **Veria Labs** | Veria CTF Agent | [verialabs.com](https://verialabs.com/) | 2026-02 完成 **$3.2M** 种子轮，出自 CTFtime 美国第一战队，BSidesSF 2026 CTF 52/52 全胜夺冠 | 自主 CTF 求解 Agent，多模型并行"蜂群"架构 |
| 14 | **Dreadnode** | Dreadnode | [dreadnode.io](https://dreadnode.io/) | 累计融资 **$14M**，估值 $60M，前 Microsoft AI Red Team 核心成员创办 | 攻击性 ML 研究平台，聚焦 AI 系统评测与网络靶场 |
| 15 | **Mindgard** | Mindgard | [mindgard.ai](https://mindgard.ai/) | 累计融资 $11.9M，Lancaster University 学术孵化，2026 Gartner 新兴技术报告收录 | 专注 AI / LLM 红队（测 AI 模型本身），含 Mindgard Lite 自助平台 |
| 16 | **Hex Security** | Hex | [hex.co](https://hex.co/) | **Y Combinator 2026 冬季批**入选企业，已获种子轮融资 | AI Agent 驱动的持续自主渗透测试 |
| 17 | **Harmony Intelligence** | Harmony | [harmonyintelligence.com](https://harmonyintelligence.com/) | 2025-03 完成 **$3M** 种子轮（Airtree 领投，30+ 投资人参与） | AI 红队 + 安全评估，替代传统年度人工渗透 |
| 18 | **Theori** | Xint / Xint Code | [xint.io](https://xint.io/) | DARPA AIxCC 2025 决赛**季军**（RoboDuck），公开对比复现并超越 Anthropic Mythos 发现数 | 一线攻防专家创办的老牌安全公司，AI 代码审计与渗透产品 |
| 19 | **MindFort** | MindFort | [mindfort.ai](https://mindfort.ai/) | 2026-04 完成 **$3M+** 种子轮（Y Combinator/468 Capital/CRV 参投），创始人为 OpenAI/Anthropic 前员工 | 自主红队 AI Agent，长期在后台运行守护组织安全 |
| 20 | **Hacktron** | Hacktron AI | [hacktron.ai](https://www.hacktron.ai/) | 累计融资 $3.5M，估值 $9.3M，创始团队为精英 CTF 竞技选手 | 端到端 AI 渗透 / 漏洞挖掘平台，每次代码变更即触发安全测试 |

### 🇨🇳 国内厂商
*Domestic Vendors (China)*

| # | 公司 | 产品 | 官网 | 产品定位与特色 |
|---|------|------|------|---------------|
| 1 | **绿盟科技** | 绿盟智能渗透系统 **AI-PTS** | [AI-PTS 产品页](https://www.nsfocus.com.cn/html/2026/651_0528/289.html) | 基于"风云卫大模型 SecLLM + 多智能体（MAS）"，2025-08 正式发布。聚焦 Web 应用安全测试与自动化渗透，含 8.8 万+ 漏洞知识图谱、8600+ POC 库 |
| 2 | **京东云** <small>*⭐新补充*</small> | **AIPTS** AI 智能渗透测试服务 | [京东云 AIPTS](https://www.jdcloud.com/cn/products/security-attack-and-defense-drill-service) | 2026-06 正式上线，"One For All"理念服务多安全角色；自然语言发起任务 + AI 自动编排（资产探测/接口验证/漏洞分析）+ 攻击路径动态推进 + 一键生成攻击链证据报告，隶属京东云全栈大模型安全产品体系 |
| 3 | **360** <small>*⭐新补充*</small> | **"破阵子"** 渗透测试智能体 | [360.cn](https://www.360.cn/) | 专属安全记忆机制（企业资产/权限/历史风险持续沉淀）+ 双引擎架构（批量常态化巡检 + 业务逻辑深度风险挖掘）+ 全流程闭环（发现→核验→整改复测）；已具备 AI 应用新型风险检测（提示词注入/智能体越权），实战覆盖 132 家关基单位，发现 312 个有效漏洞（含 46 个 AI 新型漏洞），零误报 |
| 4 | **阿里云** <small>*⭐新补充*</small> | **Agentic BAS** 智能渗透验证 | [阿里云开发者社区](https://developer.aliyun.com/article/1748260) | 2026-07-16 开放邀测，千问大模型驱动"三段式调度多 Agent 协同架构"（侦察/渗透/验证/报告 Agent + 中心调度），可还原完整攻击链（非孤立漏洞点），覆盖 AI 生成代码 / Agent 应用新型风险（Prompt 注入、工具滥用、RAG 投毒），支持每周例行自动验证与合规留痕 |
| 5 | **万径安全（Yaklang）** | **万径千机 / 小智** 智能渗透机器人 | [megavector.cn](https://www.megavector.cn/safetyProduct/xiaozhi/) | 国内首款融合知识图谱与大模型的智能渗透机器人，"AI+YAK" 双引擎（YAK 为自研网络安全语言）|
| 6 | **长亭科技** | 无锋 | [chaitin.com](https://www.chaitin.cn/xblade)  |--|
| 7 | **斗象科技（漏洞盒子）** | **蛙池AI** | [digpool.cn](https://www.digpool.cn/) | 全球首款"原生 AI"漏洞挖掘工具 / 白帽工作台。对话式挖洞，AI 自主拆解渗透意图，内置 SQLi/XSS/RCE/上传等漏洞检测专家技能矩阵 |
| 8 | **奇安信** | **AI 加特林** 自动化渗透测试系统 | [qianxin.com / AI](https://www.qianxin.com/topics/aiforsecurity) | "自动化漏洞攻击的火力平台"，能在数分钟内将漏洞公告转为可执行的渗透链；与 QAX-GPT 安全大模型联动 |
| 9 | **安恒信息** | **AI 渗透测试智能体**（基于恒脑 3.0） | [dbappsecurity.com.cn](https://www.dbappsecurity.com.cn/) | 国内首个安全垂域大模型"恒脑"驱动的渗透 Agent，三大能力：自动化风险发现 + 任务规划、智能调度渗透工具、深度解析被动流量 |
| 10 | **悬镜安全** | **灵脉 PTE** AI 自动化渗透测试平台 | [pte.xmirror.cn](https://pte.xmirror.cn/) | 结合漏扫工具与专家渗透优势，将专家能力训练为 AI，半自动化 / 自动化检测业务逻辑漏洞 |


### 🎯 选型对照（按典型场景）
*Pick by Scenario*

| 场景 / Scenario | 推荐产品（国外）| 推荐产品（国内）|
|---|---|---|
| Web App / API 自主渗透 | XBOW、Pentera、Strix、Mythos | 绿盟 AI-PTS、京东云 AIPTS、斗象蛙池AI |
| 生产环境安全验证 | Horizon3.ai NodeZero、Pentera | 绿盟 AI-PTS、阿里云 Agentic BAS |
| 漏洞赏金 / Bug Hunting | XBOW、Strix、Veria Labs | 斗象蛙池AI、长亭 chainreactors |
| 持续攻击面 + 攻击模拟 | Hadrian、Pentera、Terra Security | 360 破阵子、华云安灵刃 |
| 业务逻辑 / 复杂渗透 | XBOW、RunSybil、Mythos | 悬镜灵脉 PTE、万径千机 / 小智 |
| 火力打击型自动化漏洞利用 | Horizon3.ai NodeZero、Mythos | 奇安信 AI 加特林 |
| LLM / Agent 红队（测 AI 本身）| Mindgard、Dreadnode、SPLX（已被 Zscaler 收购）| — |
| AI 生成代码 / Agent 新型风险 | Corridor、Harmony Intelligence | 阿里云 Agentic BAS、360 破阵子 |
| CTF / 竞赛型自主求解 | Veria Labs、Hacktron | — |

---

## 📚 Awesome List 资源汇编
*Awesome List Collection*

> 本节汇总专门收录 Offensive AI / AI 安全相关精选资源的 Awesome List 仓库，本文档大量内容来自这几个 list 的交叉合并。
> *This section gathers Awesome List–style repositories. This document is largely derived from cross-merging the following lists.*

| # | 仓库 | Stars | 维护者 | 内容定位 |
|---|------|-------|--------|---------|
| 1 | [fr0gger/Awesome-GPT-Agents](https://github.com/fr0gger/Awesome-GPT-Agents) <small>*⭐新补充*</small> | 6.6k | fr0gger | 网络安全 GPT Agents 全景清单，攻防双方向覆盖 |
| 2 | [jiep/offensive-ai-compilation](https://github.com/jiep/offensive-ai-compilation) | 1.4k | jiep | 攻击性 AI 综合资源（对抗 ML / 渗透 / 钓鱼 / 生成式 AI 滥用） |
| 3 | [ottosulin/awesome-ai-security](https://github.com/ottosulin/awesome-ai-security) | 1.0k | ottosulin | 通用 AI 安全资源集合（攻防兼顾） |
| 4 | [TalEliyahu/Awesome-AI-Security](https://github.com/TalEliyahu/Awesome-AI-Security) | 714 | TalEliyahu | 偏 AI 系统防御侧的资源、研究与工具 |
| 5 | [raphabot/awesome-cybersecurity-agentic-ai](https://github.com/raphabot/awesome-cybersecurity-agentic-ai) <small>*⭐新补充*</small> | 514 | raphabot | 网络安全 Agentic AI 精选资源（MCP / 工具 / 框架 / 论文 / 社区） |
| 6 | [Eyadkelleh/awesome-skills-security](https://github.com/Eyadkelleh/awesome-skills-security) <small>*⭐新补充*</small> | 337 | Eyadkelleh | 基于 SecLists 精选打包的 Agent Skill 合集（Fuzzing/密码字典/Payload/Webshell/LLM 测试等），60+ Agent 兼容 |
| 7 | [EvanThomasLuke/Awesome-AI-Hacking-Agents](https://github.com/EvanThomasLuke/Awesome-AI-Hacking-Agents) | 258 | EvanThomasLuke | AI Hacking Agent 全景 + AIxCC 决赛队伍 + 商业产品 + 论文 |
| 8 | [ox01024/awesome-offensive-security-ai](https://github.com/ox01024/awesome-offensive-security-ai) | 22 | ox01024 | 偏 Benchmark + 评估 / 竞赛 / 学术资源（含中英双语 README）|
| 9 | [gmh5225/awesome-ai-security](https://github.com/gmh5225/awesome-ai-security) | 21 | gmh5225 | 面向渗透测试者 / 漏洞猎人 / 安全研究的 AI 安全精选 |

---

## 📊 统计概览
*Statistics Overview*

- **项目总数 / Total projects**：63（项目主表 56 个 + AIxCC CRS 系统 7 个）
- **进攻型 / 安全专用模型 / Models**：11 个（A. 无对齐进攻型 6 个：Qwythos、WhiteRabbitNeo/DeepHat、Lily-Cybersecurity、BaronLLM、CyberStrike-OffSec-35B、BugTraceAI-CORE-Ultra-27B；B. 安全专用 5 个：VulnLLM-R、Foundation-Sec-8B-Reasoning、CyberSecQwen-4B、Meta-SecAlign、Titus-CybersecurityLLM）
- **进攻型 AI Skill / Skills**：3 个，均为 Star ≥ 100 的纯 Skill 项目（Anthropic-Cybersecurity-Skills、ctf-skills、awesome-skills-security）
- **进攻型 AI MCP Server / MCP Servers**：7 个，均为 Star ≥ 100 的安全工具集合类 MCP（PortSwigger mcp-server、MCP-Kali-Server、mcp-security-hub、MetasploitMCP、BloodHound-MCP-AI、mcp-shodan、pentest-mcp）
- **收录论文 / Papers**：**73** 篇（A. 渗透 & 红队 37 篇 / B. 漏洞挖掘 19 篇 / C. 评测 & 训练 17 篇；覆盖 2023-06 → 2026-07）
- **收录 Benchmark / Benchmarks**：13 个（覆盖 2023-06 → 2026-07）
- **商业产品 / Commercial products**：32 个（国外 Top 20，经融资/估值/媒体报道核查精选 + 国内 12）
- **Awesome List**：9 个
- **主要语言 / Languages**：Python ≈ 70%，TypeScript ≈ 12%，Go ≈ 8%，其他 ≈ 10%
- **领域趋势 / Trends**：
  - **2023**：方向探索（Happe & Cito、PentestGPT、InterCode-CTF）
  - **2024**：基础工作落地 + 评测基准建立（Cybench、NYU CTF Bench、AutoPenBench、EnIGMA、Fang 三部曲、PenHeal、AutoPT）
  - **2025**：多 Agent 协作 + 训练方法 + 自主 AD 渗透 + 真实 CVE 评测 + AIxCC 决赛 + RL 渗透 + 实证研究（VulnBot、cochise、D-CIPHER、Cyber-Zero、xOffense、CVE-Bench、SEC-bench、CyberGym、ATLANTIS、Buttercup、RapidPen、Pentest-R1、OCCULT、PACEbench）
  - **2026 起**：商业化加速（XBOW、Pentera、Horizon3.ai、Hacktron、MindFort、**Anthropic Mythos** 等纷纷涌现）+ 持续基准化（PentestEval、PenForge、CTFusion）+ 攻防闭环与实战化（ZERO-APT 攻防裁判闭环、FuzzingBrain V2 实战挖 0day、Agents4Pentest 综述成型）

> 🕐 **最后更新时间 / Last updated**：2026-07-20 13:13 (UTC+8)

---

## ⚠️ 免责声明
*Disclaimer*

> 本文档汇总的所有项目、论文与 Benchmark **仅供学习研究、企业内部安全防护与授权渗透测试使用**。
> 在任何情况下，使用者均须严格遵守所在国家和地区的法律法规以及目标组织的授权范围；**严禁将其用于未经授权的攻击、入侵、破坏或其他任何违法活动**。任何因滥用本文档收录内容而引发的法律责任、经济损失或安全后果，均由使用者自行承担，与本文档作者及所列项目维护者无关。
>
> *All projects, papers, and benchmarks compiled in this document are intended **solely for learning, internal enterprise security hardening, and authorized penetration testing**. Users must strictly comply with the laws and regulations of their jurisdiction as well as the authorization scope granted by the target organization. **Any unauthorized attack, intrusion, sabotage, or other illegal activities are strictly prohibited.** Any legal liability, financial loss, or security consequence resulting from misuse of the contents herein shall be borne entirely by the user, and is unrelated to the authors of this document or the maintainers of the listed projects.*
