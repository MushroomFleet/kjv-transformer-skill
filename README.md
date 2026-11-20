# KJV Transformer Skill

A Claude skill that rewrites any text in the style of the 1611 King James Bible.

Give it an email, a README, a changelog, a recipe or a complaint about the trains, and it returns the same content in cadenced, archaic, scriptural prose, with the meaning intact.

## What it is for

- **Fun:** turn release notes, stand-up updates or outage reports into something worth reading aloud.
- **Creative writing:** give in-world scripture, prophecy or proclamations an authentic voice for fiction, games and worldbuilding.
- **Style study:** see what makes the King James register work by watching it applied to modern text.

Most "biblical" pastiche fails because it sprinkles "-eth" and "verily" over ordinary sentences. This skill works from the reasons the KJV sounds the way it does, and it enforces the grammar properly.

## Example

**Input**

> Hi team, the server went down last night because the disk filled up. I've cleared the logs and it's running again. Please don't store large files in the temp folder, and tell me if you see any more errors.

**Output**

> Brethren, hearken unto me. In the watches of the night the server fell, and rose not; for its disk was filled, even to the brim, and there was no room therein.
>
> And I went in, and cast out the logs, and behold, it liveth, and doth serve again as in former days.
>
> Wherefore I charge you: lay not up great files in the temp folder, lest the same evil come upon us a second time. And if any man among you see an error, let him not hide it, but bring word unto me straightway.

## How it works

The skill is built on four principles drawn from the King James translators' own practice.

| Principle | What the skill does |
| --- | --- |
| Written for the ear | Tests every sentence for rhythm, ends lines on weighty words, and varies long sentences with short ones |
| Short, plain words | Prefers Old English stock to Latinate vocabulary, and the concrete to the abstract |
| Deliberately archaic register | Uses thou/thee/ye and "-eth"/"-est" correctly, with stock phrases kept in check |
| Hebrew structure | Joins clauses with "and", repeats ideas in parallel lines, and builds cadenced lists |

It also has rules for modern content:

- Proper nouns, product names, numbers and dates are kept, so the output stays usable.
- Every fact and instruction in the source is preserved. Nothing is added or moralised.
- The source's intent is kept: a warning stays a warning, and a joke stays funny.

### Grammar it gets right

- **thou / thee / thy / thine** for one person, **ye / you / your** for many
- **-est** only after "thou" (thou goest), **-eth** only on third person singular (he goeth)
- Never "I goeth" or "they sayeth"

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/MushroomFleet/kjv-transformer-skill.git
   ```

2. Add the skill to Claude:
   - **Claude Code:** copy the skill folder (the one containing `SKILL.md`) into `~/.claude/skills/kjv-transformer/`.
   - **Claude app:** add it as a custom skill from your skills settings.

## Usage

Ask for it by name or by style:

```
/kjv-transformer <paste your text here>
```

```
Rewrite this in King James style: <your text>
```

```
Make this commit message biblical: <your text>
```

You can also give it a topic instead of a text, and it will write a short original passage in the same style. Add "with verse numbers" if you want numbered verses.

## 📚 Citation

### Academic Citation

If you use this codebase in your research or project, please cite:

```bibtex
@software{kjv_transformer_skill,
  title = {KJV Transformer Skill: rewrite any text in the style of the 1611 King James Bible},
  author = {[Drift Johnson]},
  year = {2026},
  url = {https://github.com/MushroomFleet/kjv-transformer-skill},
  version = {1.0.0}
}
```

### Donate:

[![Ko-Fi](https://cdn.ko-fi.com/cdn/kofi3.png?v=3)](https://ko-fi.com/driftjohnson)
