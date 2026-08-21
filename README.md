# Adversary Forge

A build tool for Daggerheart adversaries. Pick a role and a tier, get a stat block that
sits inside the SRD benchmarks, then edit any part of it by clicking on it.

## What it does

- All ten SRD roles, with Battle Point costs and an encounter budget calculator
- Tier benchmarks for Difficulty, damage thresholds, HP, Stress, attack modifier and damage dice
- Every field editable, with a nudge when a value leaves its tier range
- Roles that remove a stat remove it outright, so Minions have no thresholds at all
- A live damage threshold band showing what a hit actually costs
- Attack range and physical/magic damage type as pickers
- A feature library of 147 entries ordered Passive, then Action, then Reaction, including
  92 drawn from the SRD's own example adversaries and labelled with their source
- Parameterised features stay in sync: rename `Minion (7)` to `Minion (2)` and the body follows
- Write and save your own features, reusable across adversaries
- Motives and Tactics suggestions taken from the SRD's example adversaries, sorted by role
- Copy the block as Markdown, or export a transparent-cornered PNG in the current theme
- A browser-local roster that flags the entry you just saved and confirms before deleting

## Running it

No build step. One HTML file, no dependencies.

```
npx serve public
```

## Deploying

Static. On Vercel, import the repo and accept the defaults.

## Licence and attribution

Tier benchmarks, role names, Battle Point costs, attack ranges, the Motives and Tactics
suggestions and the SRD example features come from the Daggerheart System Reference
Document 1.0. The per-role stat adjustments and the generic feature text are original
to this project.

This product includes materials from the Daggerheart System Reference Document 1.0,
(c) Critical Role, LLC, under the terms of the Darrington Press Community Gaming License.

Compatible with Daggerheart. Not official, and not endorsed by Darrington Press or Critical Role.
