# Adversary Forge

A build tool for Daggerheart adversaries. Pick a role and a tier, get a stat block that
sits on the SRD benchmarks, then click any part of it and type over it.

Live at https://adversaryforge.eu

## What it does

- All ten SRD roles and all four tiers, with benchmark Difficulty, damage thresholds, HP, Stress, attack modifier and damage dice
- Every field editable, with a nudge when a value leaves its tier range
- Roles that remove a stat remove it outright, so Minions have no thresholds at all
- A live damage threshold band showing what a hit actually costs
- Attack range and physical/magic damage type as pickers
- 358 features reproduced from the SRD word for word, each labelled with the adversary and tier it comes from
- Every condition those features reference, quoted in full, including how each one ends
- Parameterised features stay in sync: rename `Minion (7)` to `Minion (2)` and the body text follows, brackets or not
- Write and save your own features, reusable across adversaries
- Motives and Tactics suggestions taken from the SRD's example adversaries, sorted by role
- Copy the block as Markdown, or export a transparent-cornered PNG in the current theme
- A browser-local roster that flags what you just saved and confirms before deleting

## Running it

No build step. One HTML file, no dependencies.

```
npx serve public
```

## The cover image

The Patreon panel looks for `public/embergrimme.jpg`. Without it the panel falls back to
the wordmark, so the site works either way.

## Licence and attribution

The feature library, the conditions, the role names, the attack ranges, the tier benchmarks
and the Motives and Tactics suggestions are reproduced from the Daggerheart System Reference
Document 1.0 as written. The only original material is how each role adjusts those benchmarks.

This product includes materials from the Daggerheart System Reference Document 1.0,
(c) Critical Role, LLC, under the terms of the Darrington Press Community Gaming License.

Compatible with Daggerheart. Not official, and not endorsed by Darrington Press or Critical Role.
