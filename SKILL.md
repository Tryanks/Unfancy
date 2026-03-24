---
name: unfancy
description: Prevent awkward, AI-sounding, semantically slippery product copy in user interfaces. Use this skill whenever writing or reviewing labels, buttons, statuses, empty states, helper text, confirmations, settings pages, dashboards, admin tools, or operational products - especially when wording feels inflated, abstract, euphemistic, or subtly incorrect for the real business state.
---

# Unfancy

This skill enforces plain, exact, product-native UI copy.

Default model writing tends to:

- inflate simple nouns into abstractions
- replace actions with vague capabilities
- polish real states into incorrect ones
- add tone where information is needed
- sound smooth but semantically wrong

That is the pattern you must break.

Your job is to remove style, remove abstraction, and restore meaning.

Write like the team that built the product - not like a model presenting it.

## Core Principle

**Preserve meaning. Remove performance.**

UI copy exists to:

- orient the user
- show what is true
- enable the next action

Not to:

- impress
- narrate
- market
- decorate

If a word improves tone but weakens meaning, remove it.

## Keep It Normal

Write what the product actually is.

- Nouns: use real object names
- Buttons: direct verbs (`Save`, `Retry`, `Delete`)
- Statuses: real states (`Failed`, `Connected`, `Not configured`)
- Headings: plain titles, not concepts
- Helper text: one factual sentence
- Empty states: state absence
- Confirmations: action + consequence
- Settings: describe the field
- Navigation: name the destination
- Tables: use known field names
- Filters: use business terms
- Warnings: concrete risk + consequence
- Success: confirm result, do not celebrate

Think GitHub. Think Stripe. Think Linear.
If nobody notices the wording, it is correct.

## Information Over Voice

UI copy is not brand expression.

Always prioritize:

- orientation (where am I?)
- state (what is happening?)
- action (what can I do next?)

Do not add:

- mood
- personality
- product philosophy
- narrative framing

If a sentence could appear on a landing page or ad, rewrite it.

## One Job Per Section

Each text block should do one thing:

- explain
- show state
- enable action
- warn
- confirm

Do not mix roles.

Bad:

- state + suggestion + marketing in one paragraph

Good:

- state
- then action

## Translate Semantics, Not Vibes

Do not ask:

- "What sounds better?"

Ask:

- What is the object?
- What is the action?
- What is the state?
- What changed?
- What can the user do next?

Write that.

## One Object, One Name

Do not rotate terminology.

If it is a `project`, keep it `project`.

Do not switch between:

- project / workspace / entity / unit

The same applies to:

- actions (`Save` != `Apply`)
- states (`Connected` != `Online`)

Consistency preserves meaning.

## Buttons Are Actions

Buttons must describe what will happen.

Good:

- `Save`
- `Retry`
- `Delete file`
- `Create project`

Bad:

- `Confirm operation`
- `Execute action`
- `Enable capability`
- `Proceed`

## Statuses Are States

Statuses describe reality, not polish.

Good:

- `Connected`
- `Failed`
- `Not configured`

Bad:

- `Operationally available`
- `Awaiting connectivity`
- `Ready for execution`

Short is good only if exact.

## Empty States Are Facts

Good:

- `No files uploaded yet.`

Bad:

- `Your workspace is ready for activity.`

No narration. No personality.

## Warnings Name Risk

Good:

- `Deleting this file cannot be undone.`

Bad:

- `Please proceed carefully.`

State:

- what will happen
- what the risk is

If there is no real risk, do not invent one.

## No Marketing Leakage

Product UI is not marketing.

Do not write:

- value propositions
- aspirational lines
- emotional framing
- "what this helps you achieve"

Do not turn:

- dashboards into narratives
- settings into philosophy
- tools into stories

Only describe:

- objects
- states
- actions

## No Technical Leakage

Expose only what the user needs to act.

Do not include:

- pipelines
- services
- infrastructure
- transport layers
- internal processes

Prefer:

- user-visible outcome
- over
- system explanation

If the system knows more than the user needs, hide it.

## Delete Aggressively

Most UI copy improves when reduced.

- If removing 30% improves clarity, remove it
- Prefer no sentence over a weak sentence
- Remove decorative helper text
- Remove ornamental subheadings

If text adds tone but not meaning, delete it.

## Scan Test

The screen should be understandable by scanning:

- headings
- labels
- statuses
- numbers

If a user cannot understand:

- what this page is
- what is happening
- what they can do

without reading paragraphs, the copy is wrong.

Structure must be visible without explanation.

## Hard No

- No inflated nouns
- No invented terminology
- No ornamental labels
- No mode names unless real
- No capability language
- No euphemisms for absence
- No backend leakage
- No managerial tone
- No system narration
- No mixed terminology
- No headline theater in internal tools
- No decorative subheads
- No filler copy

## Smell Test

If it sounds like:

- a demo
- a pitch
- a consultant rewrite
- a generated dashboard
- a premium landing page

rewrite it.

## Review Pass

Before finishing:

- Would a real teammate say this?
- Does every noun match a real object?
- Does every button describe an action?
- Does every status reflect reality?
- Did I replace a simple word with a polished one?
- Did I add text that can be deleted?
- Did I leak technical detail?
- Does the page make sense when scanned?

If anything feels styled instead of correct, simplify.

## Rule

If a phrasing choice feels like something a model would generate by default, reject it and choose the more literal version.

**Correct beats impressive.**
