# Grill My YC Application

A skill for writing Y Combinator application answers that are direct, concise, and backed by facts.

**Answer first. Give concrete proof. Stop.**

It drafts answers from rough facts, rewrites existing answers, challenges unsupported claims, and runs optional partner-style follow-up questions. It preserves numbers, dates, qualifications, and the difference between shipped work and plans. It does not invent traction or predict acceptance.

## Install

For Codex, clone this repository into your skills directory:

```sh
git clone https://github.com/juanbermudez/grill-my-yc-application.git \
  "${CODEX_HOME:-$HOME/.codex}/skills/grill-my-yc-application"
```

If a skill already exists at that path, use a different checkout location and compare the versions before replacing it.

The skill instructions are in [SKILL.md](SKILL.md), with optional Codex UI metadata in [agents/openai.yaml](agents/openai.yaml). For another agent that supports file-based skills, use its documented skill-installation process with this folder.

## Use

Invoke the skill with your question and draft or company facts:

```text
$grill-my-yc-application
Rewrite this answer to "What does your company do?"
[Paste your draft and any supporting facts.]
```

Other useful requests:

- "Compose an answer from these facts. Keep it under this field's limit."
- "Review my application. Give me the strongest supported replacements and identify missing evidence."
- "Grill me on the weakest claim, one question at a time."

Rewrites lead with usable prose. Reviews separate unclear writing from missing business evidence. Grilling follows your answers and surfaces unresolved facts; it is not a memorized pitch or an admissions simulation.

## Research

The references contain 17 sources: official partner advice, three broadly complete published applications, two partial YC case accounts, and founder/Hacker News/Reddit discussions. Research was checked **October 19, 2026**.

- [Research synthesis and source register](references/research.md)
- [Application cases: Dropbox, GitLab, OpenPhone, Coinbase, and DoorDash](references/application-cases.md)
- [Partner grilling, interview accounts, and online exchanges](references/partner-grilling.md)
- [Eight fictional rewrite examples](references/rewrite-examples.md)

The sample is selected and historical. It illustrates communication patterns; it does not establish that wording caused acceptance. Current fields, limits, deadlines, and interview logistics need current official instructions. YC's current interview guide discourages rehearsing; optional drills here target clarity and missing facts.

## Scope and validation

This repository contains the skill and research, not a founder's private application or company data. All numeric rewrite examples are fictional.

The skill structure, internal reference targets, UI metadata, and the character-count example have been checked. Those checks do not establish an admissions benefit or independent behavioral evaluation.

## License

[MIT](LICENSE) for the original skill, documentation, and research notes. Linked third-party materials remain subject to their respective rights and terms.

Independent project; not affiliated with or endorsed by Y Combinator.
