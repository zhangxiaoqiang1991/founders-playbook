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

在 Claude Code 中触发：

- `/founders-playbook` — 进入创业导航
- `/创业手册` — 同上
- `/创始人手册` — 同上

你也可以绕过阶段诊断直接使用专项功能：

| 说出关键词 | 进入模式 |
|-----------|---------|
| "帮我分析一下这个方向/想法" | 魔鬼代言人分析 |
| "帮我看看竞品" | 竞品格局四层扫描 |
| "帮我设计客户访谈" | 客户发现访谈设计 |
| "帮我看看我的产品有没有 PMF" | PMF 诊断（Sean Ellis 测试）|
| "帮我看看我的增长" | 增长引擎诊断 |
| "帮我看看我的护城河" | 三层护城河诊断 |
| "我的运营卡住了" | 运营瓶颈诊断 |
| "帮我看看定价" | 定价诊断（一人公司）|

### 使用注意（重要）

1. **这不是通用创业顾问。** 输出严格基于《创始人手册》的框架。如果你问的是框架覆盖不到的问题（比如具体融资条款、股权结构），skill 会告诉你"这个问题超出了本书范围"。

2. **先诊断再给方案。** Skill 一定会先确认你所在的阶段和团队模式再给出建议。

3. **Skill 不做权威断言。** 它的工作方式是引导你自己得出结论，而不是替你做决策。

4. **陷阱是主动预警的。** 每个阶段都内置了陷阱清单，不等你踩进去再说。

5. **Idea 和 MVP 的边界可能模糊。** 坦诚地回答诊断问题就好。

### 测试案例

见 [EXAMPLES.md](./EXAMPLES.md)，包含四个阶段各一个完整的匿名真实案例对话。

### 关于这本书

- 英文原名：*The Founder's Playbook: Building an AI-native Startup*
- 作者：Anthropic
- 发布日期：2026 年 5 月
- 官方地址：https://claude.com/blog/the-founders-playbook

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

In Claude Code, trigger with `/founders-playbook` or "AI-native startup guide".

### Caveats

1. **Not a general startup advisor.** Output is strictly based on the book's framework.
2. **Diagnosis + team-mode first.** The skill confirms both before recommending.
3. **No authoritative assertions.** Guides you to conclusions, doesn't decide for you.
4. **Traps are proactively warned.**
5. **Idea/MVP boundary can blur.** Be honest about what you've built.

### Test Cases

See [EXAMPLES.md](./EXAMPLES.md) for 4 anonymized conversations, one per stage.

### About the Book

- *The Founder's Playbook: Building an AI-native Startup*
- By Anthropic — Published May 2026
- Official: https://claude.com/blog/the-founders-playbook

### License

MIT
