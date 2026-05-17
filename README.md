# founders-playbook：AI Native 创业导航 Skill

> 基于 Anthropic 官方《创始人手册》(The Founder's Playbook) 的 AI Native 创业导航。
> 帮你把这本书的四阶段框架用在你的实际情况中——不管你是 startup 团队还是一人公司。

[English](#english) | [中文](#中文)

---

## 中文

### 这是什么？

2026 年 5 月，Anthropic 发布了 **《创始人手册》（The Founder's Playbook: Building an AI-native Startup）**——一本关于 AI 时代如何从零创建一家公司的操作指南。

这本书的核心洞察是：**AI 时代，判断力取代执行力，成为创始人最核心的竞争壁垒。**

但这个 skill 不是为了让你"读"这本书，而是让你**用**这本书。你不需要读过它，只需要说出你现在的情况，skill 会用书里的框架帮你：

- 诊断你现在处于创业的哪个阶段
- 提示你当前阶段最容易踩的坑
- 给出可执行的下一步行动

### 这本书适合谁？

| | **适合** | **不太适合** |
|---|---|---|
| **团队形态** | 1-10 人的 lean team / 一人公司 | 10 人以上的成熟组织 |
| **融资阶段** | 种子轮到 A 轮 / 未融资 | 成长期以后 |
| **创业类型** | AI Native / SaaS / 开发者工具 | 硬件 / 生物科技 / 重资产行业 |
| **心态** | 想用最小成本验证方向 | 已经有成熟商业模式只需执行 |

书中引用的真实案例：
- **Medvi** — 2 个全职员工，4.01 亿美元营收，16.2% 净利润率
- **Cal AI** — 7 个员工，4000 万美元营收，零融资

### 一人公司适配（这个 skill 的特色）

这本书原本是为**打算拿融资、建团队、冲规模**的公司写的。但 Anthropic CEO **Dario Amodei** 在 2025 年就说：

> *"2026 年会出现第一家单人十亿美元公司。"*（置信度 70-80%）

Anthropic CPO **Mike Krieger**（Instagram 联合创始人）也补充：

> *"当年我用 13 个人做出了 Instagram。现在 AI 能让 2 个人做到同样的事。"*

所以这个 skill 做了一个决定：**不走纯粹的 startup 叙事，而是同时支持两条线。**

| | **Startup 线** | **一人公司线** |
|---|---|---|
| 目标 | 融资、增长、IPO | 财务自由、被动收入、时间自主 |
| 团队形态 | 1-10 人，打算扩张 | 1 人（最多 1-2 个 AI agent）|
| Scale 的含义 | 建组织、建护城河 | 建系统、让自己可以消失 |
| 增长方式 | 融资 + 团队 + 销售 | Content-led + Product-led + AI 自动化 |

在入口处选择"一个人做"或"有团队"后，所有阶段的建议会自动校准。

### 核心框架：四阶段模型

| 阶段 | 核心任务 | 退出标准 |
|------|---------|---------|
| **Idea（想法阶段）** | 验证问题是否存在，而非急于构建 | Problem-Solution Fit |
| **MVP** | 聚焦核心交互，收集 PMF 证据 | Product-Market Fit |
| **Launch（上线阶段）** | 把早期流量转化为可持续增长引擎 | 增长可重复 / 运营不依赖创始人 |
| **Scale（规模化阶段）** | 构建护城河，从赌注变生意 | 可持续盈利 / IPO / 被收购 |

每个阶段都有对应的：退出标准 checklist、陷阱预警、可做的具体练习。一人公司用户会看到另一个版本的 Scale 阶段和额外的适配建议。

### 安装使用

这个 skill 是为 [Claude Code](https://claude.ai/code) 设计的。

**方式一：直接克隆**

```bash
git clone https://github.com/zhangxiaoqiang1991/founders-playbook.git
# 在 Claude Code 中使用
```

**方式二：放入 skills 目录**

如果你已经有一个 Claude Code skills 项目，直接把 `founders-playbook` 目录复制进去即可。Claude Code 会自动发现该 skill。

### 使用方式

在 Claude Code 中触发 `/founders-playbook`、`/创业手册` 或 `/创始人手册` 后，**直接说你现在的情况，skill 会自动路由到最合适的模式**：

| 你说 | 路由到 |
|------|--------|
| "我有个想法不知道行不行" | 魔鬼代言人分析 |
| "我做了个产品但没人用" | MVP 阶段 + PMF 诊断 |
| "产品上线了但增长很慢" | Launch 阶段诊断 |
| "几个产品线顾不过来" | Scale 阶段诊断 |
| "帮我看看竞品" | 竞品格局四层扫描 |
| "帮我看看定价" | 定价诊断（一人公司）|
| "我不知道我在哪个阶段" | 诊断模式 |

你也可以在路由表中查看所有模式。不需要记——说人话就行。

### 使用注意（重要）

1. **这不是通用创业顾问。** 输出严格基于《创始人手册》的框架。如果你问的是框架覆盖不到的问题（比如具体融资条款、股权结构），skill 会告诉你"这个问题超出了本书范围"。

2. **这本书是 Anthropic 写的。** 工具推荐（Claude Chat / Code / Cowork）都是自己的产品，并非中立第三方评估。框架本身是工具中立的，但操作指南确实假设你用了 Anthropic 的产品。

3. **四阶段是简化模型。** 现实中的创业不会四个阶段线性走完。你可能来回跳、同时处在两个阶段、或者不完全符合任何阶段。框架是导航地图，不是铁轨。

4. **一人公司适配是我们的延伸。** Scale 阶段的"一人公司版退出标准"、定价诊断等是我们基于 Dario Amodei 等人的观点做的延伸，不是原书内容。

5. **这个框架最适合 AI Native 产品。** 如果你的生意是传统服务业、硬件、或内容媒体，部分阶段（尤其是 MVP 和 Launch）需要你自己重新理解。

6. **阶段诊断是启发式的。** 三个诊断问题不是精密测量。如果你觉得诊断结果不符合你的感觉，直接说，skill 会重新校准。

7. **这本书写于 2026 年 5 月。** AI 行业变化很快，具体工具建议可能在 6 个月后有更优解。关注四阶段和验证逻辑，而不是具体工具名称。

### 测试案例

见 [EXAMPLES.md](./EXAMPLES.md)，包含四个阶段各一个完整的匿名真实案例对话。

### 跨工具使用

这个 skill 是标准 Markdown 格式，可以放在这些工具里使用：

| 工具 | 放置位置 | 触发方式 |
|------|---------|---------|
| **Claude Code** | `skills/founders-playbook/SKILL.md` | `/founders-playbook` 或直接说需求 |
| **Cursor** | `.cursor/rules/founders-playbook.md` | 自动匹配 |
| **Windsurf** | `.windsurf/rules/founders-playbook.md` | 自动匹配 |
| **GitHub Copilot** | `.github/copilot-instructions.md` 中引用 | 自动匹配 |
| **Codex CLI** | `CLAUDE.md` 中引用 | 自动匹配 |

核心内容（阶段知识库、路由表、输出规范）在所有平台通用。斜杠命令 `/founders-playbook` 目前仅 Claude Code 支持，其他平台直接说需求即可。

### 关于这本书

- 英文原名：*The Founder's Playbook: Building an AI-native Startup*
- 作者：Anthropic
- 发布日期：2026 年 5 月
- 官方地址：https://claude.com/blog/the-founders-playbook

### 关于我

**大厂转型人强哥**（全网同名）

曾就职腾讯、字节跳动。目前负责 AI + 内容增长、产品运营。关注 AI 内容运营、AI 培训布道、AI 内部提效三个方向。

- 微信：qianggegood123
- 小红书：[强哥 @andyxqzhang](https://www.xiaohongshu.com/user/profile/617395d8000000001f0362a3)
- Twitter：[@andyxqzhang001](https://x.com/andyxqzhang001)

如果你用这个 skill 拿到了启发，或者踩了坑发现哪里不对——欢迎告诉我。反馈比 star 值钱。

### License

MIT

---

## English

### What is this?

An AI-native startup navigation skill based on Anthropic's **"The Founder's Playbook: Building an AI-native Startup"** (May 2026). It helps you apply the book's 4-stage framework to your specific situation — whether you're a funded startup or a solopreneur.

The book's core insight: **In the AI era, judgment replaces execution as the founder's core competitive advantage.**

### Who is this for?

| | **Good fit** | **Less suitable** |
|---|---|---|
| **Team size** | 1-10 people lean team / solo founder | 10+ person org |
| **Funding** | Pre-seed to Series A / bootstrapped | Growth stage and beyond |
| **Type** | AI Native / SaaS / Dev tools | Hardware / Biotech / Capital-intensive |
| **Mindset** | Validate with minimum cost | Execute known business model |

### Solopreneur Adaptation (what makes this skill special)

The original book was written for VC-funded rocketships. But Anthropic's CEO **Dario Amodei** predicted (May 2025):

> *"The first billion-dollar one-person company will emerge by 2026."* (70-80% confidence)

And Anthropic CPO **Mike Krieger** (Instagram co-founder) added:

> *"I built Instagram with 13 people. AI could now let 2 people do the same."*

This skill adds a **solo/team branching path** at entry — all advice is calibrated based on whether you're building alone or with a team.

### The 4-Stage Framework

| Stage | Mission | Exit Criteria |
|-------|---------|--------------|
| **Idea** | Validate the problem before building | Problem-Solution Fit |
| **MVP** | Build the core interaction, find PMF | Product-Market Fit |
| **Launch** | Turn early traction into repeatable growth | Repeatable growth, founder-independent ops |
| **Scale** | Build moats, turn bets into businesses | Sustainable profitability / IPO / Acquisition |

Each stage includes exit criteria checklists, trap warnings, and actionable exercises. Solo founders get an alternative Scale stage with adapted exercises.

### Usage

Trigger with `/founders-playbook` or "AI-native startup guide". Then **just say what's on your mind** — the skill routes automatically:

| You say | Routed to |
|---------|-----------|
| "I have an idea but not sure" | Devil's Advocate analysis |
| "I built something but nobody uses it" | MVP stage + PMF check |
| "Product is live but growth is slow" | Launch stage diagnosis |
| "Multiple products running, overwhelmed" | Scale stage diagnosis |
| "Help me analyze competitors" | Competitive landscape scan |
| "I don't know what stage I'm at" | Diagnostic mode |

### Caveats

1. **Not a general startup advisor.** Output is strictly based on the book's framework.
2. **The book is by Anthropic.** Tool recommendations (Claude Chat/Code/Cowork) are their own products — not a neutral third-party evaluation.
3. **4-stage model is a simplification.** Real startups don't move linearly. You might loop back, straddle stages, or not fit neatly.
4. **Solo founder adaptation is our addition.** The alternative Scale stage and pricing diagnosis are extensions we built, not from the original book.
5. **Best for AI-native products.** If you're in services, hardware, or media, some stages need reinterpretation.
6. **Stage diagnosis is heuristic.** Three questions won't capture everything. Speak up if the result doesn't feel right.
7. **Published May 2026.** AI moves fast. Focus on the framework (validation logic, stage transitions), not the specific tool names.

### Test Cases

See [EXAMPLES.md](./EXAMPLES.md) for 4 anonymized conversations, one per stage.

### About the Book

- *The Founder's Playbook: Building an AI-native Startup*
- By Anthropic — Published May 2026
- Official: https://claude.com/blog/the-founders-playbook

### License

MIT
