# 更新日志 / Changelog

*Offensive AI Agentic Landscape*
仓库地址 / Repository: [Yeti-791/Awesome-Offensive-AI-Agentic-Landscape](https://github.com/Yeti-791/Awesome-Offensive-AI-Agentic-Landscape)

> 本日志基于对每次 commit 实际 diff 内容的逐一读取与分析整理而成（非提交信息原文翻译），按周（周一至周日）组织，最新一周置于最前。
> *This changelog is compiled by reading and analyzing the actual diff content of each commit (not a literal translation of commit messages), organized by week (Monday–Sunday), most recent week first.*

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

- **总提交次数 / Total commits**：19
- **首次提交 / First commit**：2026-06-11（仓库初始化，仅 LICENSE）
- **首个内容版本 / First content version**：2026-06-11（`a530c6e`，392 行完整文档）
- **最新提交 / Latest commit**：2026-07-20
- **核心演进脉络 / Key evolution**：
  1. 06-11：文档框架首发（项目/论文/Benchmark/商业产品四大板块）
  2. 07-13：新增"开源模型"独立章节，论文库首次大扩充
  3. 07-14 ~ 07-15：密集迭代（新项目/新模型/新Benchmark/建立社区贡献规范/收紧收录标准）
  4. 07-20：新增"Skill"与"MCP Server"两大生态维度，商业产品表提纯为 Top 20

---

*本日志基于逐一读取 GitHub 仓库各 commit 的 diff 内容分析整理，而非直接使用 commit message，数据采集时点：2026-07-20 13:48。*
