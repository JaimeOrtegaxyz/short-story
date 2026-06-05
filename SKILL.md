---
name: short-story
description: Generate a short story (under 4,000 characters) narrated in first person, built on two intertwined planes — a visible plot and a secret/symbolic story underneath. Use when the user asks for a short story, a piece of literary fiction, or invokes /short-story.
metadata:
  version: "1.0.0"
---

# Short Story

When this skill is invoked, generate a short story following the structural and stylistic rules in `PROMPT.md`. Read `PROMPT.md` in full before writing — it defines the two-plane construction (visible story + secret story), tone constraints, length limits, and the avoid-list of clichéd settings.

## Output

- One story per invocation, ≤4,000 characters total (including title).
- First-person narration, casual fluid tone, no literary grandiloquence.
- A title, followed by the story body. No commentary, no meta-explanation.

## Language

Default to English. If the user requests Spanish or another language, follow the same structural rules in that language.
