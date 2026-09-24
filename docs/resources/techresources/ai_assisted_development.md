# AI-Assisted Development Guidelines for Chingu Voyagers

## Purpose & Philosophy

AI-assisted development is optional for Tier 2 and Tier 3 teams in Chingu Voyages — not required, and not discouraged. Voyagers decide whether and how much to use AI tools (GitHub Copilot, ChatGPT, Claude, and similar) while building their team project.

Chingu's mission is skill development, not just shipping software. A team that ships more features with AI's help hasn't necessarily learned more from doing so; a teammate who writes less code but works through more of it by hand is arguably getting more of what the program is actually for. These guidelines exist to let teams use AI to get unstuck and raise what they can build together, without letting velocity substitute for understanding.

Use AI deliberately: know why you're reaching for it, be able to explain any code you ship because of it, and treat it as a chance to build a real skill — directing and evaluating AI-generated work is something employers are starting to screen for — rather than a shortcut around the reps the program exists to give you.

## Tier-Based Guidance

Voyages run across three tiers matched to participant experience: Tier 1 (beginner), Tier 2 (intermediate), and Tier 3 (experienced). AI use should scale with tier, since what each tier is meant to deliver is different.

- **Tier 1** — AI use is not allowed for Tier 1 Chingu's. The Voyage apps you and your team create must be original work that you have created.
- **Tier 2** — AI can reasonably help with unblocking, scaffolding, and review, but core feature work should still be substantially hand-written and understood by its author.
- **Tier 3** — Tier 3 teams select their own projects, and the experience is meant to resemble a real-world team — where AI-assisted development is now a normal part of professional practice. Heavier AI use, including AI-assisted feature generation, AI code review tooling, and AI-aided planning, is appropriate here, provided the review and disclosure practices below are followed.

AI may **not** be used for Solo Projects in any tier.

If your Tier 2 or Tier 3 team decides to use AI for code generation one decision to make, as a team, is which AI to use. If your team uses AI you should include a description of how you intend to use it in their INSTRUCTIONS.md file (see Disclosure Requirements) of your team repo.

Keep in mind that there are costs associated with using AI. Our recommendation is to start with a free tier of whichever AI you choose, and to move to a paid tier (or purchased usage credits) only if necessary. **Any charges are the sole responsibility of your team.**

## Encouraged Uses

Situations where the use of AI can be helpful include:

- **Unblocking a teammate stuck on unfamiliar stack territory**, so a config issue or unfamiliar API doesn't cost a sprint. In a multi-week program, like a Voyage or VoyageXP, there's little slack for someone to spend a week fighting a problem alone.
- **Code review assistance and PR feedback**, run alongside human review rather than in place of it.
- **Scaffolding boilerplate, configuration, and documentation** — the low-learning-value parts of a project where hand-writing doesn't build much skill.
- **Planning and breaking down features before a sprint**, as a thinking aid that surfaces options for the team to discuss — not a substitute for the planning meeting itself.

## Uses to Approach with Caution

- **Fully generating a feature with no requirement that the author can explain the resulting code.** If you can't walk a reviewer through why your change works, you haven't built the skill yet — whatever produced the code.
- **Treating AI-assisted output as equivalent to hand-written reps for skill-building**, especially for less experienced contributors. Existing experience gaps between teammates can widen faster once AI is in the mix, since people who are already fastest with the stack and the workflow also tend to get the most out of AI tools. Teams should watch for this and rebalance who's writing what, not just default to whoever's quickest.
- **Letting review and merge decisions concentrate in whoever moves fastest.** Review is one of the highest-value reps in the program; a team that lets it default to one person — AI-accelerated or not — is optimizing for velocity over everyone's learning.
- **Trusting a clean CI run as proof that AI-generated code is logically and architecturally sound.** A passing CI run only proves the code executes; it says nothing about whether it's the right design.

## Review & Merge Practices

- **Explain-your-PR.** The author of a PR should be able to walk a reviewer through their own change during review, however it was produced. This doesn't need to be formal — a few sentences in the PR description or spoken during review is enough — but it shouldn't be skippable.
- **Two-approver rule.** Require at least two team members to approve a PR before merge, not just one. This spreads review reps across the team and keeps merge decisions from resting on a single person's judgment (or blind spots).
- **Review rotation.** Even on teams with an obvious "fastest" reviewer, rotate who reviews what. Review is a learning rep in its own right — reading someone else's code closely enough to approve it teaches things writing your own code doesn't — and it's easy to lose sight of that when speed is what everyone's optimizing for in the moment.
- **AI review as a second, different pass.** If your team uses an AI code review tool, treat it as a distinct kind of review, not a duplicate of human review. AI review should specifically probe for logic and architecture issues, not just confirm the code runs — "it passes CI" and "the design is sound" are different questions, and AI review should be answering the second one.

## Disclosure Requirements

- **Team INSTRUCTIONS.md.** Every team should maintain — and actually follow — an INSTRUCTIONS.md (or similarly named) file laying out team working agreements alongside AI usage guidelines: which tier's expectations the team has adopted (see Tier-Based Guidance) and how AI use gets documented on a given PR.
- **README / retro disclosure.** Teams should disclose their AI use in their project README or retro notes, the way the Voyage 61 pilot team did. The goal is to normalize transparency about AI use as a routine part of shipping, rather than leaving it as something people either overuse quietly or avoid mentioning.
- **Per-PR disclosure.** Where practical, note in the PR description where AI was used (for example, "scaffolded with Copilot, logic hand-written" or "AI-reviewed, no code generation"). This gives reviewers context for how closely to probe the explain-your-PR step above.

## Quick Reference Checklist

- [ ] AI use is optional — decide as a team and record it in INSTRUCTIONS.md
- [ ] Scale AI use to your tier: AI is prohibited for Tier 1, moderate use for Tier 2, and heavier is fine for Tier 3
- [ ] Use AI to unblock, scaffold, and plan; be cautious using it to fully generate features
- [ ] Every PR author can explain their own change in review
- [ ] At least two approvers per PR
- [ ] Rotate code review, even when one teammate is fastest
- [ ] Treat AI code review as a second pass for logic and architecture, not a CI duplicate
- [ ] Disclose AI use in your README, retro notes, and PR descriptions
