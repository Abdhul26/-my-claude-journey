# My Claude Usage Strategy

Based on: **Professional** · Daily user · Coding + Interview Prep + Business Planning · Primary need: **Learning Support**

---

## Recommended Primary Model

**Claude Sonnet 5** — this is now the default model on claude.ai (since July 1, 2026) and handles the majority of professional work well, including a lot of what used to require Opus.

## Why This Model Fits Me

- Your work mix (coding + learning/interview prep + business planning) is exactly Sonnet 5's sweet spot: strong reasoning, good teaching/explanation quality, solid code generation — without burning through your rate limit.
- Daily usage means efficiency matters. Sonnet uses your usage limit far more conservatively than Opus for comparable quality on most tasks.
- Deep, step-by-step teaching (your preferred learning format) doesn't need Opus-level reasoning for most fundamentals — Sonnet 5 explains internals, mental models, and edge cases very well.

## When to Use Haiku

- Quick syntax lookups ("what's the Python list comprehension syntax again?")
- Formatting/renaming/boilerplate
- Fast fact-checks during interview prep drilling
- Anything where speed > depth

## When to Use Sonnet

- Your default for almost everything: concept teaching, coding help, interview question walkthroughs, business plan drafting, resume/content work
- Multi-step explanations following your structured teaching format
- Day-to-day debugging and code review

## When to Use Opus

- Genuinely hard system-design or algorithm problems (the kind that show up in senior backend interviews — distributed systems tradeoffs, concurrency edge cases, complex DB internals)
- Long multi-step agentic coding sessions (e.g., building a full project scaffold)
- Business strategy work with many interacting variables (pricing models, market entry analysis)
- Fable 5 (Opus-tier, restored July 1, 2026) is an option too, but Opus 4.8 is the more practical everyday "hard mode" pick

## Recommended Effort Level

### Low

Quick lookups, simple yes/no or definitional questions, Haiku-tier tasks.

### Standard (Medium/High — Sonnet 5's default)

Your everyday setting. Concept teaching, coding help, interview Q&A, drafting — this is where you'll live 80%+ of the time.

### High/xhigh

Reserve for dense system-design questions, tricky debugging, or when a Sonnet answer feels shallow and you need it to reason harder before answering.

### Max

Rare — save for genuinely hard, high-stakes problems: a mock system-design interview simulation, a full business plan with financial modeling, or a gnarly production bug with many interacting causes.

---

## My Personalized Claude Workflow

| Task                                          | Best Model                        | Best Effort   | Reason                                             |
| --------------------------------------------- | --------------------------------- | ------------- | -------------------------------------------------- |
| Learning a new backend concept (fundamentals) | Sonnet 5                          | Standard      | Strong step-by-step teaching without overkill      |
| Debugging tricky code                         | Sonnet 5                          | High          | Needs deeper reasoning but not full Opus           |
| System design interview prep (senior-level)   | Opus 4.8                          | High/xhigh    | Complex tradeoffs need max capability              |
| Quick syntax/API lookup                       | Haiku 4.5                         | Low           | Speed over depth                                   |
| Resume/LinkedIn content drafting              | Sonnet 5                          | Standard      | Good writing quality, efficient                    |
| Business plan / pricing strategy              | Sonnet 5 (Opus if multi-variable) | Standard–High | Sonnet handles most; escalate for complex modeling |
| Mock interview Q&A drilling                   | Sonnet 5                          | Standard      | Fast iteration, good explanations                  |
| Long coding session (building a project)      | Opus 4.8                          | xhigh         | Sustained agentic reasoning over many steps        |

---

## Biggest Mistakes I Should Avoid

- **Defaulting to Opus for everything** — wastes your daily limit fast; you'll hit rate caps before finishing real work.
- **Using Max effort for routine questions** — slows responses down for no quality gain on simple tasks.
- **Using Haiku for concept teaching** — it's fast but shallow; your learning-heavy workflow needs Sonnet's depth.
- **Never switching up to Opus** — for the hardest interview-style system design questions, staying on Sonnet can leave gaps in your prep.

---

## Final Recommendation

**One model, one effort level for most work: Sonnet 5 at Standard (High) effort.**

It's the current default for a reason — strong enough for deep technical teaching, coding help, and business planning, while staying efficient enough for daily heavy use. Reserve Opus 4.8 at high/xhigh specifically for senior-level system-design interview simulations and complex multi-step coding sessions — that's the 10-15% of your work where the extra capability actually pays off.
