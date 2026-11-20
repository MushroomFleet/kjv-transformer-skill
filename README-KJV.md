# KJV Transformer Skill

A skill of Claude, which taketh any writing and writeth it anew after the manner of the King James Bible of 1611.

Give unto it an email, or a README, or a changelog, or a recipe, or a complaint against the trains; and it shall give back the same matter in the speech of the fathers, slow of step and grave of voice. And the meaning thereof shall not be changed.

## Wherefore it was made

- **For mirth:** that thy release notes, and thy stand-up updates, and thy outage reports may be worthy to be read aloud.
- **For the making of tales:** to give a true voice unto the scriptures, and the prophecies, and the proclamations of worlds that are not; in fiction, and in games, and in worldbuilding.
- **For the study of style:** that thou mayest see what maketh the King James tongue to stand, beholding it laid upon the writings of this present day.

For many have sought to write after this manner, and have failed; for they scatter "-eth" and "verily" upon common sentences, and call it scripture. But this skill buildeth upon the causes whereby the KJV soundeth as it doth, and it keepeth the grammar with a strong hand.

## An example

**What is given**

> Hi team, the server went down last night because the disk filled up. I've cleared the logs and it's running again. Please don't store large files in the temp folder, and tell me if you see any more errors.

**What is given back**

> Brethren, hearken unto me. In the watches of the night the server fell, and rose not; for its disk was filled, even to the brim, and there was no room therein.
>
> And I went in, and cast out the logs, and behold, it liveth, and doth serve again as in former days.
>
> Wherefore I charge you: lay not up great files in the temp folder, lest the same evil come upon us a second time. And if any man among you see an error, let him not hide it, but bring word unto me straightway.

## How it worketh

The skill is founded upon four stones, hewn from the labour of the King James translators themselves.

| The stone | What the skill doeth |
| --- | --- |
| Written for the ear | It trieth every sentence by the sound thereof, and endeth each line upon a word of weight, and setteth the short sentence beside the long |
| Short, plain words | It chooseth the old English word before the Latin, and the thing that may be touched before the thing that is only thought |
| A tongue made old of purpose | It useth thou and thee and ye, and "-eth" and "-est", each in its own place; and the stock phrases it holdeth in check |
| The Hebrew frame | It joineth clause unto clause with "and", and saith a thing twice in lines that answer one another, and telleth its lists in measure |

Moreover it hath statutes for the things of this present day:

- Proper nouns, and the names of products, and numbers, and dates are kept, that the writing may yet be of use.
- Every fact of the source is kept whole, and every instruction likewise. Nothing is added thereto, neither is any sermon preached.
- The purpose of the source abideth: a warning is yet a warning, and a jest is yet a jest.

### The grammar which it keepeth aright

- **thou / thee / thy / thine** unto one, **ye / you / your** unto many
- **-est** only after "thou" (thou goest), **-eth** only upon the third person singular (he goeth)
- Never "I goeth", neither "they sayeth"

## The setting up thereof

1. Clone the repository:

   ```bash
   git clone https://github.com/MushroomFleet/kjv-transformer-skill.git
   ```

2. Add the skill unto Claude:
   - **Claude Code:** copy the skill folder (even that wherein `SKILL.md` dwelleth) into `~/.claude/skills/kjv-transformer/`.
   - **Claude app:** add it as a custom skill from thy skills settings.

## The use thereof

Call upon it by its name, or by its manner:

```
/kjv-transformer <paste your text here>
```

```
Rewrite this in King James style: <your text>
```

```
Make this commit message biblical: <your text>
```

And if thou have no text, but a matter only, give it the matter; and it shall write a short passage of its own after the same manner. And if thou desire numbered verses, say "with verse numbers", and it shall be so.

## 📚 Citation

### Academic Citation

If thou use this codebase in thy research, or in thy project, cite it thus, I pray thee:

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
