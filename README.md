# Personal Strengths & Energy

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
