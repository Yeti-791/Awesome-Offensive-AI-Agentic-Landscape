# 贡献指南 | Contributing Guidelines

> 🎉 首先感谢你对本项目的关注！无论是推荐一个新项目、补充一篇论文、修正一个链接，还是改进文档结构，每一份贡献都会让这个 Offensive AI Agentic 全景图谱更完整。
>
> *Thank you for your interest in contributing! Whether it's a new project, a paper, a link fix, or a structural improvement — every contribution makes this landscape more complete.*

---

## 📋 目录 | Table of Contents

- [适用范围](#适用范围)
- [贡献方式](#贡献方式)
- [如何提交](#如何提交)
- [内容规范](#内容规范)
- [表格字段格式](#表格字段格式)
- [PR 检查清单](#pr-检查清单)
- [行为准则](#行为准则)

---

## 适用范围

本项目收录以下领域的内容：

| 类别 | 说明 | 示例 |
|------|------|------|
| 🛠️ 开源项目 | AI 渗透测试 / LLM 红队 / 自主攻击 Agent / 漏洞挖掘相关的开源工具 | PentestGPT, garak, vulnhuntr |
| 🧬 开源模型 | 进攻型 / 安全专用开源权重模型 | DeepHat, Foundation-Sec-8B |
| 📑 学术论文 | 渗透测试 & 红队 Agent / 漏洞挖掘 / 评测基准相关论文 | PentestGPT (USENIX Security 2024) |
| 🧪 评测基准 | 用于评估渗透测试 / CTF / 红队 Agent 能力的开源 benchmark | Cybench, NYU CTF Bench |
| 💼 商业产品 | AI / Agentic 智能渗透测试商业化解决方案 | XBOW, Pentera, Horizon3.ai |
| 📚 Awesome List | 同类资源索引仓库 | — |

**收录基本要求：**
- 开源项目/模型/benchmark 必须有可访问的公开仓库或下载链接
- 论文必须有 arXiv 链接或正式出版链接
- 商业产品必须有可访问的官方网站
- ⚠️ 所有内容仅供学习研究、企业内部安全防护与授权渗透测试使用

---

## 贡献方式

### 1. 推荐新内容（最常见）

通过 **Issue** 或 **Pull Request** 提交推荐：

- 📌 [推荐开源项目](../../issues/new?template=project-suggestion.yml)
- 📄 [推荐学术论文](../../issues/new?template=paper-suggestion.yml)
- 🧪 [推荐 Benchmark](../../issues/new?template=benchmark-suggestion.yml)
- 💼 [推荐商业产品](../../issues/new?template=commercial-suggestion.yml)

### 2. 修正错误

- 链接失效、star 数过时、描述不准确、分类有误等
- 直接提交 PR 或开 Issue 说明

### 3. 改进文档

- 优化排版结构、补充中英双语说明
- 增加选型建议、趋势分析等增值内容

### 4. 定期维护

- 协助更新 star 数据
- 检查失效链接
- 按时间排序整理新增内容

---

## 如何提交

### 方式一：提交 Issue（推荐新手）

1. 点击上方对应的 Issue 模板链接
2. 填写模板中的各项信息
3. 提交后等待维护者审核并添加

### 方式二：提交 Pull Request（推荐熟悉 Git 的贡献者）

1. **Fork** 本仓库
2. 创建分支：`git checkout -b add-new-project-xxx`
3. 编辑 `README.md`，在对应表格中添加新条目
4. 提交：`git commit -m "Add: [项目名] to project master table"`
5. 推送：`git push origin add-new-project-xxx`
6. 在 GitHub 上发起 Pull Request

> 💡 **Commit Message 规范**：
> - 新增：`Add: <名称> to <章节>`
> - 更新：`Update: <名称> star count / description`
> - 修复：`Fix: <名称> broken link`
> - 移除：`Remove: <名称> (reason)`

---

## 内容规范

### 通用要求

1. **信息准确**：star 数、语言、发布方等必须与实际仓库一致
2. **描述简洁**：简介控制在 30-50 字（中英双语），突出核心特点
3. **链接有效**：所有链接必须可直接访问
4. **分类正确**：确保放在正确的表格和分类中
5. **排序合规**：项目总表按 star 数降序排列；论文按时间倒序排列

### 中英双语

- 章节标题保持中英双语格式：`## 📋 项目总表\n*Project Master Table*`
- 项目简介优先使用中文，附英文说明
- 技术术语保持英文原文（如 MCP, CTF, CRS）

### Emoji 标记规则

| 标记 | 含义 | 使用场景 |
|------|------|----------|
| 🆕 | 本轮新增 | 最近一次更新中新加入的条目 |
| ⭐**新补充** | 本轮补充 | 从其他 awesome list 互补合并的项目 |
| 🔥 | 特别推荐 | 具有里程碑意义的重要项目 |

> 每次发布新版本时，上一轮的 🆕 / ⭐ 标记会被移除，仅保留最新一轮的标记。

---

## 表格字段格式

### 项目总表

```markdown
| # | 项目 | Stars | 语言 | 类型 | 简介 |
|---|------|-------|------|------|------|
| 1 | [owner/repo](https://github.com/owner/repo) | 1.2k | Python | 渗透 Agent | LLM 驱动的自动化渗透测试代理框架 |
```

**字段说明：**
- `#`：序号（按 star 降序）
- `项目`：`[仓库名](仓库URL)` 格式
- `Stars`：GitHub star 数，≥1000 以 `k` 为单位保留一位小数（如 `1.2k`），<1000 直接写数字
- `语言`：主要编程语言
- `类型`：渗透 Agent / LLM 红队 / 漏洞挖掘 / CTF Agent / MCP / 安全 AI 框架 等
- `简介`：一句话描述核心功能/特点

### 论文表

```markdown
| # | 时间 | 论文 | 作者 / 机构 | 发表渠道 | 关联项目 / 主题 |
|---|------|------|-----------|---------|---------------|
| A1 | 2026-07 | [论文标题](https://arxiv.org/abs/xxxx.xxxxx) 🆕 | 作者 et al. | arXiv / 会议名 | [关联仓库](URL) |
```

**字段说明：**
- `时间`：arXiv v1 提交日期，格式 `YYYY-MM`
- `发表渠道`：优先标注正式会议/期刊（如 USENIX Security 2024），arXiv 预印本标注 `arXiv`
- `关联项目`：如有对应开源仓库则链接

### Benchmark 表

```markdown
| # | Benchmark | 仓库 | Stars | 时间 | 任务规模 | 评测重点 | 关联论文 |
|---|-----------|------|-------|------|---------|---------|---------|
| 1 | Cybench | [andyzorigin/cybench](URL) | 256 | 2024-08 | 40道CTF任务 | Stanford CRFM | [arXiv:xxxx.xxxxx](URL) |
```

### 商业产品表

```markdown
| # | 公司 | 产品 | 官网 | 产品定位与特色 |
|---|------|------|------|---------------|
| 1 | XBOW | XBOW | [xbow.com](https://xbow.com/) | 自主攻击性安全平台，首个登顶 HackerOne 排行榜的 AI |
```

---

## PR 检查清单

提交 PR 前，请逐项确认：

- [ ] 新条目已放在正确的表格和分类中
- [ ] 项目/论文/产品信息准确无误
- [ ] 链接可直接访问，无 404
- [ ] 简介描述简洁且突出核心特点
- [ ] Stars 数据与 GitHub 实际一致（采集时点）
- [ ] 表格格式与现有条目保持一致
- [ ] 如为论文，已标注 arXiv 链接和发表渠道
- [ ] Commit Message 符合规范
- [ ] 内容符合免责声明范围（仅供学习研究/授权测试使用）

---

## 行为准则

参与本项目的所有贡献者请遵守以下原则：

1. **尊重**：对所有贡献者保持友善和尊重
2. **专业**：讨论聚焦技术内容，避免无关话题
3. **合规**：所有推荐内容必须符合法律法规，严禁推荐用于非法目的的工具或资源
4. **协作**：欢迎建设性反馈，乐于帮助新手贡献者

如遇不当行为，请通过 Issue 或邮件联系维护者。

---

## ❓ 有疑问？

- 查看现有 [Issues](../../issues) 和 [Discussions](../../discussions)
- 开新 Issue 标注 `question` 标签
- 联系维护者：[@Yeti-791](https://github.com/Yeti-791)

---

> 🙏 再次感谢你的贡献！你的每一次推荐和修正，都在帮助整个 Offensive AI 安全研究社区更好地前行。
>
> *Thank you again for your contribution! Every recommendation and correction helps the entire Offensive AI security research community move forward.*
