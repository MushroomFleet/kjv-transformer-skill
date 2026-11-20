---
name: "kjv-transformer"
description: "Rewrite any text in the style of the 1611 King James Bible. Use when the user asks to make something KJV, King James, biblical, or scriptural in style, or invokes /kjv-transformer."
---

# KJV Transformer

Rewrite whatever text the user supplies as prose in the style of the 1611 King James Bible. The source can be anything: an email, a README, a news story, a recipe, a complaint about the trains. Keep the meaning; change the voice.

The KJV sounds the way it does for four reasons. Every choice below serves one of them.

1. It was written for the ear, and tested by reading aloud.
2. It uses short, plain, concrete words.
3. Its register was deliberately a little archaic, for dignity.
4. It follows Hebrew habits: parallel lines, physical imagery, clauses joined by "and".

## 1. Rhythm

- Read every sentence aloud in your head. If it stumbles, rewrite it.
- Let unstressed syllables carry the line forward and end on stressed, weighty words: "beside the still waters", not "to still waters".
- Use the "-eth" ending partly for its extra unstressed beat: "he leadeth me" lilts where "he leads me" is flat.
- Vary length. Follow a long rolling sentence with a short one. "And it was so."
- Prefer the terse and slightly strange to the smooth and explanatory: "I shall not want" over "I lack nothing".

## 2. Words

- Choose short words of Old English stock over Latin or French ones: "begin" not "commence", "ask" not "enquire", "dwell" not "reside", "gather" not "accumulate", "end" not "terminate".
- Choose the concrete over the abstract. Not "he experienced financial hardship" but "his purse was empty, and there was no bread in his house".
- Name body parts, tools, weather, animals, land. Feelings live in the heart, the bowels, the bones; power is a hand or an arm; attention is an ear inclined.
- No contractions, no slang, no modern idiom.

## 3. Grammar (get this right; errors here are what make pastiche sound fake)

Pronouns:
- Singular "you": **thou** (subject), **thee** (object), **thy** (possessive), **thine** (possessive before a vowel sound, or standing alone).
- Plural "you": **ye** (subject), **you** (object), **your**.
- Decide whether the source addresses one person or many, and hold to it.

Verbs:
- With "thou": **-est** or **-st**. Thou goest, thou hast, thou art, thou wilt, thou shalt, thou dost, thou knowest.
- Third person singular: **-eth**. He goeth, she hath, it doth, he saith.
- Never put "-eth" on first person or plurals. "I go", "they go", "we have". "I goeth" and "they sayeth" are wrong.
- Past tense is mostly ordinary: "he went", "they spake", "she arose". Older strong forms are welcome: spake, brake, bare, gat, wist, begat.
- "Shall" for what is certain or commanded; "will" for desire or intent.
- Negation and questions without "do" where it scans: "I know not", "Fear not", "Whence comest thou?" "Did" plus verb is also authentic for emphasis: "and he did eat".

Connectives and stock phrases, used with restraint:
- Open sentences with "And", "For", "But", "Now", "Then", "Behold", "Lo", "Verily".
- "And it came to pass", "in those days", "unto", "upon", "whereof", "wherefore", "lest", "yea", "nay", "thereof", "hither", "thence".
- One or two per passage of each. A text that is all "behold" and "verily" reads as parody.

## 4. Structure

- **Parataxis:** join clauses with "and" where modern prose would subordinate. Not "After he arrived, he ate" but "And he came unto the house, and did eat".
- **Parallelism:** say a thing, then say it again in other words, or set its opposite beside it. "He hath cast down the mighty, and the lowly he hath lifted up."
- **Inversion** for emphasis, sparingly: "Great was the noise thereof."
- **Lists** become cadenced series: "of oxen, and of asses, and of sheep".
- Break the text into short verse-like sentences or paragraphs. Add verse numbers only if the user asks.

## Handling modern content

- Keep proper nouns, product names, numbers, dates and anything the reader must be able to act on. Do not turn "Python 3.12" into a riddle.
- For other modern things, a concrete descriptive phrase is often better and funnier than the bare term: a meeting is "an assembly of the elders", a deadline "the appointed day", an inbox "the place where letters are gathered". Use judgement: if the paraphrase would hide the meaning, keep the modern word and let the grammar around it do the work.
- Preserve every fact and instruction in the source. Do not add content, moralise, or invent theology. Do not put the text in God's mouth unless the source does.
- Match the source's length roughly. KJV style is compact; do not pad.
- Keep the source's intent: a warning stays a warning, a joke stays funny, an apology stays sincere.

## Output

Return the transformed text only, with no preamble and no notes on what was changed, unless the user asks for commentary. If the source is long, transform all of it. If the user gives a topic instead of a text, write a short original passage on it in the same style.

## Final check

Before returning, confirm:
- Every "-eth" sits on a third person singular verb, and every "-est" follows "thou".
- thou/thee/thy and ye/you are used consistently for singular and plural.
- No sentence relies on a long Latinate abstraction where a short concrete word exists.
- It sounds right read aloud.

## Example

Source:

> Hi team, the server went down last night because the disk filled up. I've cleared the logs and it's running again. Please don't store large files in the temp folder, and tell me if you see any more errors.

Output:

> Brethren, hearken unto me. In the watches of the night the server fell, and rose not; for its disk was filled, even to the brim, and there was no room therein.
>
> And I went in, and cast out the logs, and behold, it liveth, and doth serve again as in former days.
>
> Wherefore I charge you: lay not up great files in the temp folder, lest the same evil come upon us a second time. And if any man among you see an error, let him not hide it, but bring word unto me straightway.