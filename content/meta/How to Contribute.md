---
title: How to Contribute
status: sourced
requires: ["[[index]]"]
tags: [meta]
---

# How to Contribute

You do not need to know how to code. You do need a free GitHub account.

## Add a new note (about 2 minutes)

1. **[Click here to start a new note](https://github.com/glennonymous/infinite-jest-garden/new/v5/content/community?filename=My-note-title.md&value=---%0Atitle%3A%20Short%20claim%20or%20topic%0Astatus%3A%20ai-claim%0Arequires%3A%20%5B%5D%0Atags%3A%20%5B%5D%0A---%0A%0AThe%20claim%2C%20in%20plain%20sentences.%0A%0A%23%23%20Evidence%0APage%20numbers%20%28say%20which%20edition%29.%20Quotations%20under%2015%20words.%0A%0A%23%23%20Dispute%0A%28empty%20until%20someone%20disputes%20it%29%0A)** (it opens with the template filled in).
2. Change the filename at the top (keep `.md` at the end), then replace the template text with your note.
3. Scroll down and click **Propose new file**, then **Create pull request**.
4. A maintainer reviews it and merges or declines.

## Fix or dispute an existing note

1. Open the note's file in the repository (`content/` folder).
2. Click the pencil icon ("Edit this file").
3. Make your change and click **Propose changes**.

## Draft with your own AI

1. Open `vault.md` (linked from the front page) and paste all of it into your own AI chat.
2. Ask it to draft a note in the format below on your idea. Tell it that `ai-claim` and `disputed` notes are unverified.
3. **Check every page number and quotation against the book yourself.** AI drafts often invent page numbers and quotes.
4. Paste the result into the new-note link above.

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

Readers are encouraged to paste the whole vault into their own AI and ask questions. Notes marked `ai-claim` are unverified.
