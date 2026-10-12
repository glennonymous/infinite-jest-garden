---
title: How to Contribute
status: sourced
requires: ["[[index]]"]
tags: [meta]
---

# How to Contribute

You do not need to know how to code.

## Easiest: edit on GitHub

1. Open any note on the repository page.
2. Click the pencil icon ("Edit this file").
3. Make your change. Click **Propose changes**.
4. A maintainer reviews it and merges or declines.

## What makes a good contribution

- **Cite pages.** "p. 1063" beats "somewhere near the end." Say which edition.
- **One claim per note.** If a note makes three claims, split it.
- **Flag, don't delete.** If a claim looks wrong, change `status:` to `disputed` and add a "Dispute" section with your evidence. Leave the original text so others can judge.
- **Promote to `sourced`** only when you have checked the book yourself.
- **Mark speculation as speculation.** Fan theory is welcome. Fan theory stated as fact is not.

## Note template

```
---
title: Short claim or topic
status: ai-claim
requires: ["[[Note a reader should read first]]"]
tags: []
---

The claim, in plain sentences.

## Evidence
Page numbers, quotations under 15 words.

## Dispute
(empty until someone disputes it)
```

## What the AI is for

Readers are encouraged to paste the whole vault (`vault.md`, linked from the front page) into their own AI and ask questions. The AI should be told that notes marked `ai-claim` are unverified.
