# learn-claude-skills-with-phoebe

The Claude skills that 10x your workflow - on a token budget. A free, interactive course by
**Phoebe Fu**.

Most people use Claude like a very good chat box. The people who get 10x out of it use
**skills**: reusable instruction packs Claude loads only when a task needs them. Skills make a
workflow drastically better *and* spend fewer tokens doing it, because a skill's detail stays on
disk until the moment it fires (progressive disclosure). This course teaches the highest-leverage
skill stack, organized by all 17 of Phoebe's course-tracks.

## The arc (8 sessions + a reference matrix)

1. **The Core Stack & token economics** - what a skill is, progressive disclosure, the 8 skills every track inherits
2. **Build & ship** - TDD, systematic-debugging, git worktrees, cavecrew, deploy (prog / deng / sys / docs)
3. **Data & DS** - schema-to-insights, the data-skill factory, dataviz, profiling (data / ds)
4. **AI & agents** - prompt + API + caching, office docs, skill-creator, artifacts (ai / aiap)
5. **AI in your domain** - marketing-skills, content-multiplexer, design-partner, deep-research (aidm x12)
6. **Content, viz & comm** - sketch family, the impeccable taste gate, decks, humanizer (viz / comm / biz)
7. **Lead, ops & edge** - mentor-room, hooks + schedule, safe edge tracks (lead / gov / emrg / prod / move)
8. **Build your own skill** - skill-creator, a token-lean SKILL.md, the budget playbook (capstone)

Plus **The 17x10 matrix** - top skills for every one of the 17 tracks, on one browsable page.

## The thesis

Every technique reduces to five token moves: **don't load it** (progressive disclosure) ·
**offload it** (subagents, Explore) · **compress it** (caveman, deep-research) · **get it right
once** (grilling, verification) · **reuse it** (Projects, prompt caching).

## Sources

Built on Anthropic's Agent Skills material (DeepLearning.AI + Anthropic Academy), the prompt
engineering interactive tutorial, and Phoebe's own installed skill library. Each session covers
~80% of its sources' working content; certificates and videos stay with the originals.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 .

---

Part of [Learn with Phoebe](https://phoebefu6.github.io/learn-with-phoebe/). Built by Phoebe Fu.
