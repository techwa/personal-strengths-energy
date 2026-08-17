# Personal Strengths & Energy

> [中文文档](README.zh-CN.md)

More evidence-based than a personality test: it reads your past conversations with AI, asks a few personalized follow-up questions, and helps you understand your real strengths and what actually gives you energy.

> **No hundred-item questionnaires. No label you share with millions of other people.**
> Every conclusion comes from things that actually happened in your life.

## Why strengths and energy matter

When we ask others — or AI — for help, we assume the answer has to come from outside. More often it's already in us: either we already have what the problem needs, or the difficulty exists precisely because our situation doesn't match our strengths and energy sources.

Whether you're doing a serious round of self-exploration, trying to resolve a recurring anxiety, or looking for something worth investing in for years, understanding your strengths and energy is unavoidable groundwork — **strengths make you good at it, energy keeps you going. What sits in the overlap is what's worth betting on long-term.**

## ⚠️ Before you start

**The depth of the scan depends on how much the AI knows about you.** Use this in an AI agent that has accumulated a fair amount of personal memory — records of both work and life matter. With work records only, the energy dimensions won't be reliable.

**Not enough memory? Send it your own writing.** Past journals, year-end reviews, project retrospectives, weekly notes, essays — upload them and they'll be used as evidence. They often work better than chat logs, because that's you writing about yourself with intent. Anything you'd rather exclude, just say so before you begin.

If both are thin, it will tell you honestly and let you choose: answer a few questions for a preliminary version marked "to be verified," or come back after you've built up more history.

## How it works

```
Phase 0  Explain and get permission (asks what you'd rather leave out)
Phase 1  Scan memory: experience → behavior → ability → energy → pattern → hypothesis → counterexample check
Phase 2  Ask 5–9 conversational questions to verify
Phase 3  Deliver the report
```

While scanning, it follows three threads at once: **inclination** (how you naturally like to work), **evidence** (what you repeatedly do better than others — real events only, never self-assessment), and **energy** (what you still want to keep doing after it's done). Every dimension gets a forced call; where evidence is too thin to choose a side, it's marked "to be verified" rather than guessed.

## What you get

An eight-part report:

1. **Opening insight** — one line on how you create value and what puts you in flow
2. **Top 5 strengths** — each with an explanation of what it looks like in *you*, plus real examples
3. **Core energy sources** — clearly separating "good at it" from "recharged by it"; things you do well but that drain you get called out
4. **High-energy conditions** — core triggers, amplifiers, and the minimum viable combination, plus what reliably drains you
5. **You may not have seen yourself this way** — where your self-image conflicts with the behavioral evidence (often the most valuable part)
6. **How to use this** — every suggestion anchored to a confirmed strength, no generic advice
7. **About this scan** — which dimensions had solid evidence and which didn't, so you know how much to trust it
8. **Closing** — a few questions worth continuing with, drawn from your own report

## Install & use

**Option 1 — AI agents (Claude, ChatGPT, etc.)**

Download [`personal-strengths-energy.skill`](personal-strengths-energy.skill) → open Settings → Skills → upload the file.

Or download the `personal-strengths-energy/` folder → zip it → rename the extension to `.skill` → upload as above.

Once installed, use it in Codex, Claude Code, or any project or chat that holds a good amount of your personal history. Just say: "Analyze my strengths and energy sources" / "Generate my strengths report" / "What recharges me?"

**Option 2 — Other AI platforms**

Use [`PROMPT.md`](PROMPT.md), a single merged file. Start a new conversation → upload it → say "Follow this document and analyze my strengths and energy sources." Works on any platform without Agent Skills support.

## The framework

Built from scratch — it doesn't use or reproduce any commercial assessment:

- **Strengths**: 25 items across 5 dimensions — Thinking (acts on information and ideas), Execution (on tasks and resources), Connection (on relationships), Influence (on others' thinking and behavior), Self-command (on yourself)
- **Energy**: 24 items across 5 dimensions — inner needs, the work itself, people and relationships, meaning, body and environment

Every item comes with a plain-language definition and a **discrimination rule** — how to tell it apart from its nearest neighbor. That's what keeps categories from bleeding into each other. Full framework: [`personal-strengths-energy/references/framework.md`](personal-strengths-energy/references/framework.md).

## Design principles

Most of these rules exist because something went wrong in real use:

- **Memory supplies the evidence; questions only calibrate it** — conclusions come from long-term patterns in memory, not from what you just said
- **Answers are material, not conclusions** — repeating your own words back to you is not an insight
- **The abstraction ladder** — a strength must land at the mechanism level: not an outcome ("shipped X"), not a domain activity ("good at content"), but something that still holds when you strip the domain away
- **Confidence matches evidence** — thin evidence gets marked "to be verified"; better a Top 3 than a padded Top 5
- **Where you put the honesty matters** — insight first, limitations after: honesty at the door is a barrier, honesty inside the room is a feature

## Privacy

Memory is read only with your explicit permission, and whatever you exclude stays excluded. Being able to read something isn't the same as showing it — sensitive experiences aren't repeated back unless they're necessary evidence. No clinical diagnosis, no personality verdicts.

## License

MIT

# 我的优势与能量来源

比「心理测评」更循证：通过调取你与 AI 的历史聊天记忆、加上几个个性化补充提问，帮你了解你的个人优势与能量来源。

> **不用做几十上百道量表题，也不会被贴上和几百万人一样的标签。**
> 所有结论都来自你自己真实发生过的事——这里只想看见那个独一无二、闪闪发光的你。

## 个人优势与能量来源为什么重要？

很多时候我们向他人或 AI 求助，以为需要从外部获得解决方案。但答案往往在自身：我们可能本就具备解决问题的优势，或者当前的困扰恰恰源于处境与自己的优势和能量来源不匹配。

无论是想认真做一次自我探索、化解反复出现的焦虑，还是想找到值得长期投入、能产生"人生复利"的方向，了解自己的优势与能量来源都是绕不开的一步——**优势保证做得好，能量保证做得久，二者的交集才是值得长期押注的地方。**

同时，了解自己的优势和能量来源，也是非常重要的自我探索和自我觉察，有助于我们提升自己的内在能量！

## ⚠️ 使用前提

**扫描深度取决于 AI 对你的了解。** 请在积累了较多个人记忆的 AI agent中使用（工作与生活的记录都重要——只有工作记录时，能量维度会扫不准）。

**记忆不够？你也可以把个人记录、日记等等发给它。** 过往的日记、年终总结、项目复盘、周报、写过的文章——直接发过来，它们会作为证据一起纳入分析，效果往往比聊天记录更好，因为那是你认真写下的自己。你不希望纳入的部分，开始前说一声即可。

如果两样都少，它会如实告诉你，并让你选择：用几个问题做一份标注"待验证"的初步版，还是先积累一阵再来。

## 它怎么工作

```
Phase 0  说明与授权（先问你有没有不想纳入的内容）
Phase 1  回扫记忆：经历 → 行为 → 能力 → 能量 → 模式 → 优势假设 → 反例验证
Phase 2  追问 5–9 个生活化的问题验证假设
Phase 3  出报告
```

回扫时同时追三条线：**倾向**（你天然喜欢怎么做）、**证据**（你反复做得比别人好的事——只认真实事件，不认自我评价）、**能量**（你做完还想继续做的事）。全维度做强制归位判定，证据不足以选边的会被标为"待验证"，而不是猜一个。

## 你会得到什么

报告包含八节：

1. **开场洞察**：一句话总结你怎样创造价值、什么让你进入状态
2. **Top 5 核心优势**：每条附说明（这项优势在你身上是什么样子）和真实例子
3. **核心能量来源**：明确区分"擅长"和"充电"——很强但做完很耗的事会被指出来
4. **高能场景**：核心条件 + 放大器 + 最低可行组合，以及最容易掉电的情况
5. **你可能没这么看过自己**：自我认知与行为证据冲突的地方（往往是最有价值的发现）
6. **怎么用起来**：每条都挂在一项已确认的优势上，不写通用鸡汤
7. **这次扫描的情况**：哪些维度证据扎实、哪些记忆量不足——让你知道这份报告能信到什么程度
8. **结尾**：基于你的报告内容给出几个可以接着聊的问题


## 安装及使用

**方式一：AI Agent安装（如Claude、ChatGPT）等**：
下载本仓库的 [`personal-strengths-energy.skill`](personal-strengths-energy.skill) → 打开 Claude/ChatPGT设置 → Skills（能力）→ 上传该文件。

或下载整个 `personal-strengths-energy/` 文件夹 → 压缩为 zip → 将后缀改为 `.skill` → 按上述方式上传。

安装后，你可以在Codex、Claude Code，或是某个有较多你的个人记忆的项目、Chat中使用。如直接说："分析我的优势和能量来源" / "生成我的优势报告" / "什么给我充电"。


**方式二：（其他 AI 平台）**：用 [`PROMPT.md`](PROMPT.md) —— 这是合并好的单文件版。新建对话 → 上传该文件 → 说"请按这份文档帮我分析我的优势和能量来源"即可。适用于 DeepSeek、豆包、Kimi、ChatGPT 等不支持 Agent Skills 的平台。


## 分析框架

自研框架，不使用也不复刻任何商业测评：

- **个人优势**：5 个维度 25 项——思维（作用于信息观念）、成事（作用于任务资源）、联结（作用于关系）、影响（作用于他人认知行为）、自持（作用于自己）
- **能量来源**：5 个维度 24 项——内在需要、做事过程、关系与他人、意义与超越、身心与环境

每一项都配有大白话定义与**判别规则**（和最近邻项怎么区分），这是保证归类不打架的关键。完整框架见 [`personal-strengths-energy/references/framework.md`](personal-strengths-energy/references/framework.md)。

## 设计原则

这个 Skill 的大部分规则来自真实使用中踩过的坑：

- **记忆出证据，提问做校验**：结论主要来自记忆中的长期模式，问答只用于验证
- **回答是素材，不是结论**：禁止把用户刚说的话复述回去当"洞察"
- **抽象阶梯**：优势必须落在"机制层"——不是结果（做成过 X）、不是领域动作（擅长做内容），而是拿掉领域词依然成立的可迁移机制
- **结论强度 = 证据强度**：证据不足就标"待验证"，宁可 Top 3 也不凑满 Top 5
- **诚实的位置很重要**：先给洞察，后交代局限——诚实放在门口是拦路，放在正文里是加分

## 隐私

只有在你明确授权后才读取记忆，并严格遵守你排除的内容；能读取 ≠ 会展示，敏感经历若非必要证据不会被复述；不做心理诊断或人格评估。

## License

MIT
