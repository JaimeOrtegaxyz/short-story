---
name: short-story
description: Generate a short story (under 4,000 characters) narrated in first person, built on two intertwined planes — a visible plot and a secret/symbolic story underneath — cast from a specific occasion, narrator, region, place, and tone chosen before writing. Use when the user asks for a short story, a piece of literary fiction, or invokes /short-story.
metadata:
  version: "2.3.0"
---

# Short Story

When this skill is invoked, generate a short story following the structural and stylistic rules in `PROMPT.md`. Read `PROMPT.md` in full before writing — it defines the casting step (the occasion and whom it happens to, the narrator, the part of the world, a corner of the city from another sphere of life, other people, ages and names, time, tone), the two-plane construction (visible story + secret story), the tone and length limits, and the ending.

## Procedure

1. Cast first, silently: choose the occasion and whom it is happening to, and tell the story from that person; decide which part of the world the unnamed city is in and let names, foods, prices, weather and procedures follow; choose a corner of the city from a different sphere of life than the occasion; give at least two other people concrete wants; settle ages, names, the time, how long the narrator has known these people, and the tone. Sketch three premises that differ in occasion, region, place, and tone; write the one you can render with the most particular knowledge.
2. Let the setting follow from the world, and the plot from the occasion. The narrator acts and the action has a consequence inside the story.
3. Build the secret story with a vehicle native to that world, then close with apparent resolution plus a residue.

## Output

- One story per invocation: 450 to 600 words, and never more than 4,000 characters including the title.
- First-person narration in a plain, spoken, fluid voice.
- A title, followed by the story body. No commentary, no meta-explanation, no casting notes.

## Language

Default to English. If the user requests Spanish or another language, follow the same structural rules in that language.
