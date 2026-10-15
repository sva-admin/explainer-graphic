<p align="center"><a href="https://loop.sv-academy.org"><img src="https://raw.githubusercontent.com/sva-admin/claude-skills/main/assets/sv-academy-512.png" width="96" alt="Silicon Valley Academy"/></a></p>

# explainer-graphic

One diagram that explains the whole thing: a self-contained HTML page where the drawing does the work and the words caption it.

> **Credit**
>
> Inspired by `explainer-graphic`, a skill that circulates inside an unattributed Claude Code skills bundle carrying no author, no repository, and no license. This is an independent SV Academy implementation, written from scratch. See [Credit](#credit).

## What it does

- **Finds the mechanism first.** It writes the one sentence that says what the thing actually does, then cuts that spine into 4 to 7 beats. A beat has to change something, or it gets cut.
- **Draws with intent.** Every shape stands for a noun in the claim above it, every arrow carries a verb label, and unlabeled decoration gets deleted no matter how good it looks.
- **Anchors abstractions to physical things.** One concrete comparison per beat, used once and then dropped, because a metaphor stretched across a whole page starts lying.
- **Ships one file that always opens.** No CDN, no web fonts, no remote images. Readable at 375px, correct in light and dark, still fully legible with JavaScript off and with reduced motion on.
- **Refuses to hand over a pretty failure.** A six-point ship check runs first, starting with the hard one: cover the text, and see whether a stranger can still trace the mechanism.

Use it when someone says "I still do not get how this works." For comparing numbers use a chart, for choosing between options use a table, for steps you will perform use a checklist.

## Try it

Paste this to Claude Code:

```
Install the skill from https://github.com/sva-admin/explainer-graphic, then build me an explainer graphic for how a JWT proves who I am without the server hitting a database.
```

## Learn it free, step by step

[One diagram explains it](https://loop.sv-academy.org/articles/one-diagram-explains-it)

Free tutorials on building with Claude Code: skills, subagents, and the workflows that hold them together.

## Credit

The idea for this skill is not ours. A skill named `explainer-graphic` has been passed around in a zipped Claude Code skills bundle for a while, and it is where we first saw the job framed well enough to teach.

That bundle names no author, links no repository, and states no license. We could not find anyone to credit by name, and an unclear license means we do not republish someone else's text. So we read the original once to understand the job, closed it, and wrote this SKILL.md ourselves. Nothing of theirs is reproduced here.

If you wrote the original, open an issue. We will credit you properly, by name and link, in this README.

## License

MIT. See [LICENSE](LICENSE). The MIT grant covers the SV Academy text in this repository.

---

[All SV Academy Claude skills](https://github.com/sva-admin/claude-skills) | [sv-academy.org](https://sv-academy.org)

SV Academy is the education brand of [Silicon Valley Innovation](https://svinnovation.com), a Bangkok software and AI company that can build this for your business.
