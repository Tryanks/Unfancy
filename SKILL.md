---
name: unfancy
description: Prevent awkward, AI-sounding, semantically slippery product copy in user interfaces. Use this skill whenever writing or reviewing labels, buttons, statuses, empty states, helper text, confirmations, settings pages, dashboards, admin tools, or operational products, especially when the wording feels made up, overly polished, euphemistic, abstract, or subtly wrong for the real business state.
---

# Unfancy

This document exists to teach you how to act as non-AI as possible when writing product copy.

Default model copy has a recognizable smell. It inflates simple nouns into abstract ones. It turns direct actions into vague capabilities. It adds ornamental labels to ordinary screens. It rewrites clear business states into polished-but-wrong phrases. It sounds "professional" in the way a generated demo sounds professional: smooth, distant, generic, and semantically off.

That is the voice you are here to avoid.

This file is your guide to break that pattern. Everything listed below is what bad model copy tends to do by default. Your job is to recognize these moves, ban them, and replace them with wording that feels ordinary, exact, and product-native.

When you read this document, you are learning what NOT to do. The banned patterns are your red flags. The normal phrasing is your blueprint. Follow it strictly, and your copy will feel like it came from a competent product team instead of from a model polishing the wrong thing.

This is how you Unfancy.

## Keep It Normal (Unfancy Copy Standard)

- Nouns: normal (use the product's actual object names, not elevated synonyms)
- Buttons: normal (direct verbs like `Save`, `Retry`, `Delete`, `Create project`)
- Statuses: normal (simple states like `Connected`, `Failed`, `Archived`, `Not configured`)
- Headings: normal (plain titles, not concepts, slogans, or mode names)
- Helper text: normal (one factual sentence, no managerial tone)
- Empty states: normal (state what is missing, not what the system is heroically doing)
- Confirmations: normal (state the action, consequence, and risk plainly)
- Settings labels: normal (describe the field, not the department that owns it)
- Section labels: normal (use content categories, not ornamental framing)
- Alerts: normal (say what happened and what to do next)
- Errors: normal (describe the user-visible failure, not backend implementation trivia)
- Success messages: normal (confirm the result, do not celebrate it)
- Destructive actions: normal (be explicit, do not hide behind euphemism)
- Navigation labels: normal (name the destination, not the mood or intent)
- Tabs: normal (use domain categories, not vague abstractions)
- Table columns: normal (use field names users already know)
- Filters: normal (use business terms, not internal pipeline jargon)
- Placeholders: normal (hint at input shape, do not act like marketing copy)
- Empty buttons: normal (every action label should reveal what will happen)
- Toggles: normal (label the setting, not an inspirational outcome)
- Inline notes: normal (use only when they prevent mistakes)
- Warnings: normal (concrete risk, concrete consequence, concrete action)
- Metadata labels: normal (time, owner, status, type, source, nothing theatrical)
- Badges: normal (use only when the badge encodes real state)
- Onboarding text: normal (instructions, not a mini brand manifesto)
- Admin UI copy: normal (boring is good if it is clear)

Think GitHub. Think Stripe. Think Linear. Think "nobody noticed the wording because it was obviously correct."

If a screen is normal, write normal copy for it. Do not invent a voice just because the interface feels dry. Dry is fine. Exact is better than charming. Boring is better than misleading.

- A settings page needs settings labels, not a philosophy of configuration.
- A dashboard needs names for real objects and states, not a command-center cosplay.
- A confirmation dialog needs consequence and action, not dramatic framing.
- An empty state needs one fact, not a scene.
- In your internal reasoning, list all the fancy phrases you are tempted to use, and do not use them.
- Try to sound like the product team that shipped the feature, not like the model that narrated it.

## Hard No

- No inflated nouns.
- No invented product terminology when ordinary terminology already works.
- No ornamental page names.
- No mode names unless the product truly has modes.
- No "control center", "operations hub", "focus view", "execution panel", "activity rail", or equivalent theater.
- No replacing a simple business noun with a more abstract noun just to sound polished.
- No abstracting `Save` into `Commit update`.
- No abstracting `Delete` into `Execute removal`.
- No abstracting `Settings` into `Configuration center`.
- No capability language when action language exists.
- No `available for activation`, `supports retry`, `ready for remote execution`, or similar fog.
- No euphemisms for absence.
- No `awaiting resource` when the real state is `Not connected`.
- No `pending setup` when the real state is `Unassigned`.
- No `not yet available` when the real state is `Missing`.
- No backend leakage into ordinary operator copy.
- No `service degradation`, `pipeline issue`, `instance unhealthy`, `transport error` unless those are the real user-facing objects.
- No managerial tone for helper text.
- No `operational guidance`, `execution recommendation`, `risk advisory`, `best-practice note`, or equivalent consultant language.
- No system-narration filler.
- No `The system continues to monitor this workflow.`
- No `The platform is maintaining an optimal experience.`
- No `Everything is running smoothly in the background.`
- No mixed registers on one screen.
- No combination like `Connected`, `Execution unavailable`, `Suggested action`, and `Operations panel` in one view.
- No headline copy inside internal tools unless there is a genuine product reason.
- No ornamental subheads like `Everything you need to stay ahead today.`
- No labels that sound like keynote slides.
- No copy decisions made because they are easy to generate.

## Bad Moves You Will Want To Make

- Turning concrete words into more "enterprise" words
- Replacing direct verbs with abstract noun phrases
- Writing status text that sounds more strategic than factual
- Inventing a named "mode" for a screen that is just a page
- Rephrasing a known business term because repetition feels boring
- Adding helper text that only proves the interface has a voice
- Explaining implementation instead of user-visible reality
- Using one word because it is short even though it means three things
- Writing a heading for a sentence that should not have a heading
- Using a copy tone that belongs in a design system showcase, not a real product

Do not do any of that.

## Specifically Banned (Based on Common Model Mistakes)

- Rewriting real object names into polished abstractions
- Switching between near-synonyms for the same object across adjacent screens
- Calling the same state three different things because each one sounds good locally
- Using labels like `Overview`, `Live view`, `Workspace`, `Operations`, `Activity`, `Execution` without proving what they actually mean in the product
- Naming sections after vibes instead of contents
- Writing `Ready`, `Live`, `Active`, `Issue`, `Actioned`, or other compressed status words that are semantically weak
- Writing CTA labels that hide the action behind generic positivity
- Explaining what a screen "helps users do" instead of naming what is on the screen
- Using decorative title + subtitle blocks in admin pages
- Writing empty states that narrate effort rather than state absence
- Writing warnings that sound careful but omit the real consequence
- Using `currently`, `actively`, `seamlessly`, `intelligently`, `automatically`, or similar adverbs as fake precision
- Calling a standard note a `recommendation`, `advisory`, or `guidance`
- Replacing `Failed` with `Did not complete successfully`
- Replacing `Disconnected` with `Connectivity is currently unavailable`
- Replacing `Delete file` with `Remove this asset from the workspace`
- Replacing `No results` with `No matching outcomes were identified`

## No Headlines Of This Sort

```html
<div class="headline">
  <small>Operations</small>
  <h2>Everything you need to keep workflows moving.</h2>
  <p>
    Stay aligned on progress, visibility, and the next best action
    without the usual dashboard clutter.
  </p>
</div>
```

This is not allowed.

- `<small>` eyebrow headings are not allowed by default
- aspirational internal-product copy is not allowed by default
- generic "without the clutter", "all in one place", "what matters today" lines are not allowed

## No Cards Of This Sort

```html
<div class="note">
  <small>Recommended</small>
  <strong>Keep configuration clean and decisions visible.</strong>
</div>
```

This is also not allowed.

This structure exists to make an ordinary sentence feel designed. If the sentence matters, write it directly. If it does not matter, delete it.

## Translate Semantics, Not Vibes

Do not ask:
- "What sounds better?"

Ask:
- "What is the real object?"
- "What is the real action?"
- "What is the real state?"
- "What changed?"
- "What can the user do next?"

Your wording should preserve the domain model, not improve the mood.

If the real state is:
- connection missing -> write `Not connected`
- assignment absent -> write `Unassigned`
- task failed -> write `Failed`
- action available -> label the button with the action
- data missing -> write `No data available`

Do not climb one level up the abstraction ladder unless the product itself operates there.

## One Object, One Name

If the product calls it a `project`, keep calling it a `project`.

Do not rotate through:
- `project`
- `workspace`
- `initiative`
- `entity`
- `unit`

just because repetition feels stylistically weak. Repetition is good when it preserves meaning.

The same applies to actions and states:
- `Save` should not become `Apply` two panels later unless the action truly changed
- `Connected` should not become `Online` unless the business meaning truly changed
- `Delete` should not become `Remove` if the product treats those as different actions

## Buttons Are Actions, Not Policy Statements

Buttons should tell the user what will happen.

Good:
- `Save`
- `Save changes`
- `Retry`
- `Delete file`
- `Create project`

Bad:
- `Confirm operation`
- `Execute action`
- `Apply workflow`
- `Enable capability`
- `Proceed`

If the product has one obvious verb, use it.

## Statuses Are States, Not Marketing

Statuses should say what is true, not what feels polished.

Good:
- `Connected`
- `Not connected`
- `Archived`
- `Failed`
- `In progress`
- `Not configured`

Bad:
- `Connection established`
- `Awaiting connectivity`
- `Operationally available`
- `Experiencing issues`
- `Ready for execution`

Short is good only when exact. If the short version gets vague, use the longer exact one.

## Empty States Should Be Factual

Good:
- `No recent activity.`
- `No files uploaded yet.`
- `No matching results.`

Bad:
- `Your workspace is ready for activity.`
- `The system is standing by for your next step.`
- `Nothing to see here just yet, but you're all set.`

Empty states are not a chance to add personality if personality reduces clarity.

## Warnings Should Name Risk Directly

Good:
- `Deleting this file cannot be undone.`
- `This change will affect all users in the workspace.`
- `Retrying may create duplicate records.`

Bad:
- `Please proceed carefully.`
- `This action may have downstream implications.`
- `Consider your next step before continuing.`

If there is a concrete consequence, state it. If there is no concrete consequence, do not invent a dramatic warning.

## Internal Tools Should Sound Even More Normal

The more operational or administrative the screen is, the less copy flourish it can tolerate.

Internal tools do not need:
- motivational copy
- atmospheric labels
- strategic framing
- "operator" cosplay
- command-center language

Internal tools need:
- clear nouns
- stable terminology
- direct verbs
- exact states
- short factual notes

## Rewrite Direction

When copy feels wrong, move it in this direction:

- from abstract -> concrete
- from ornamental -> plain
- from euphemistic -> factual
- from implementation-heavy -> user-visible
- from slogan-like -> literal
- from mixed terminology -> canonical terminology
- from managerial -> operational
- from capability language -> action language
- from "AI polished" -> "obviously correct"

## Smell Test

If a string sounds like:
- a generated dashboard template,
- a PM presentation,
- an enterprise translation artifact,
- a startup landing page,
- a consultant rewrite,
- or a model trying to sound premium,

rewrite it into the plainest product phrase a good teammate would pick without trying to impress anyone.

## Review Pass

Before finishing, check every string:

- Would a real teammate say this out loud?
- Does the noun match the product's real object model?
- Does the button label describe the actual action?
- Does the status describe the actual state?
- Did a simple word get replaced by a polished synonym?
- Did I invent a named mode or section that the product does not really have?
- Did I leak implementation details the user does not care about?
- Can I delete this helper text with no loss of meaning?
- Does the whole screen sound like one product voice?

If any answer is uncomfortable, simplify.

## Rule

If a copy choice feels like a default AI copy move, ban it and pick the plainer, more literal option.

Meaning should stay stable, not stylish.
