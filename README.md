# founders-playbook：AI Native 创业导航 Skill

> 基于 Anthropic 官方《创始人手册》(The Founder's Playbook) 的 AI Native 创业导航工具。
> 帮你把这本书的四阶段框架用在你的实际情况中。

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

### 核心框架：四阶段模型

| 阶段 | 核心任务 | 退出标准 |
|------|---------|---------|
| **Idea（想法阶段）** | 验证问题是否存在，而非急于构建 | Problem-Solution Fit |
| **MVP** | 聚焦核心交互，收集 PMF 证据 | Product-Market Fit |
| **Launch（上线阶段）** | 把早期流量转化为可持续增长引擎 | 增长可重复 / 运营不依赖创始人 |
| **Scale（规模化阶段）** | 构建护城河，从赌注变生意 | 可持续盈利 / IPO / 被收购 |

每个阶段都有对应的：退出标准 checklist、陷阱预警、可做的具体练习。

### 安装使用

这个 skill 是为 [Claude Code](https://claude.ai/code) 设计的。

**方式一：直接克隆**

```bash
git clone https://github.com/你的用户名/founders-playbook.git
cd founders-playbook
# 在 Claude Code 中使用
```

**方式二：放入 skills 目录**

如果你已经有一个 Claude Code skills 项目，直接把 `founders-playbook` 目录复制进去即可。Claude Code 会自动发现该 skill。

### 使用方式

在 Claude Code 中触发：

- `/founders-playbook` — 进入创业导航
- `/创业手册` — 同上
- `/创始人手册` — 同上
- 直接说 "帮我看看我的创业方向" — 如果匹配到关键词会自动触发

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

### 使用注意（重要）

1. **这不是通用创业顾问。** 这个 skill 的输出严格基于《创始人手册》的框架。如果你问的是框架覆盖不到的问题（比如具体融资条款、股权结构），skill 会告诉你"这个问题超出了本书范围"。

2. **先诊断再给方案。** Skill 一定会先确认你所在的阶段再给出建议。如果你跳过诊断直接问"我该怎么做"，它会倒回来问你当前情况。别急，这是为了保证建议的针对性。

3. **skill 不做权威断言。** 它的工作方式是引导你自己得出结论，而不是替你做决策。"你的目标用户有这个问题吗？" 而不是 "你的目标用户有这个问题"。

4. **陷阱是主动预警的。** 每个阶段都内置了陷阱清单。Skill 不会等你踩进去再说，而是在进入阶段时就主动打出预警。

5. **Idea 和 MVP 的边界可能模糊。** 如果你说"有个想法"但其实已经在写代码了，诊断阶段可能会有点偏移。坦诚地回答诊断问题就好。

### 测试案例

见 [EXAMPLES.md](./EXAMPLES.md)，包含四个阶段各一个完整的匿名的真实案例对话。

### 关于这本书

- 英文原名：*The Founder's Playbook: Building an AI-native Startup*
- 作者：Anthropic
- 发布日期：2026 年 5 月
- 官方地址：https://claude.com/blog/the-founders-playbook
- 本书的中文精读版在社区中广泛传播

### License

MIT

---

## English

### What is this?

In May 2026, Anthropic released **"The Founder's Playbook: Building an AI-native Startup"** — a practical guide on how to build a company from scratch in the AI era.

This skill translates the book's framework into an interactive diagnostic tool. You don't need to have read the book. Just describe your situation, and the skill will:

- Diagnose which startup stage you're in
- Flag the traps specific to your stage
- Give you actionable next steps

### The 4-Stage Framework

| Stage | Mission | Exit Criteria |
|-------|---------|--------------|
| **Idea** | Validate the problem before building | Problem-Solution Fit |
| **MVP** | Build the core interaction, find PMF | Product-Market Fit |
| **Launch** | Turn early traction into repeatable growth | Repeatable growth, founder-independent ops |
| **Scale** | Build moats, turn bets into businesses | Sustainable profitability / IPO / Acquisition |

### Usage

In Claude Code, trigger with:

- `/founders-playbook`
- "AI-native startup guide"
- "help me with my startup stage"

### Caveats

1. **This is not a general startup advisor.** Output is strictly based on the book's framework.
2. **Diagnosis first.** The skill will always confirm your stage before giving recommendations.
3. **No authoritative assertions.** The skill guides you to conclusions, it doesn't decide for you.
4. **Traps are proactively warned.** You don't have to fail first to hear about them.
5. **Idea/MVP boundary can blur.** Be honest about how much you've already built.

### Test Cases

See [EXAMPLES.md](./EXAMPLES.md) for 4 anonymized real-world conversations, one per stage.

### About the Book

- *The Founder's Playbook: Building an AI-native Startup*
- By Anthropic
- Published May 2026
- Official: https://claude.com/blog/the-founders-playbook

### License

MIT
