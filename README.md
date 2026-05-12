# Horadric Forge Challenge

**Horadric Forge Challenge** is a small browser-based gear crafting minigame inspired by the addictive item-crafting loop found in ARPGs.

It is built around the fun of taking basic gear, spending limited resources, chasing better affixes, locking in lucky rolls, gambling with risky upgrades, and finishing with a scored build.

This is **not** an exact Diablo 4 simulator. It is a fan-style crafting challenge inspired by the general feel of ARPG item systems rather than a strict recreation of any official game.

## Play It

You can play the hosted version here:

https://istreamsandwich.github.io/horadric-forge/

## Why I Made This

I have always enjoyed the crafting side of games like Diablo.

The part that really grabs me is the decision-making:  
Do I reroll this stat?  
Do I lock this affix?  
Do I spend more gold?  
Do I risk the item with one final gamble?

I wanted to capture that loop in a small, self-contained browser game.

The basic idea is:

> Start with basic gear, spend limited resources, craft each item, protect your best rolls, gamble with the Cube, then complete your build for a final score, rank, badge list, and compact share summary.

It started as a fun little project to play around with gear crafting ideas, but it has gradually grown into a more complete minigame.

## Important Note

I am not a professional coder.

This project was made with help from AI, mainly ChatGPT. That means the code may not be structured the way an experienced developer would build it from scratch.

At the moment, it is deliberately kept as a **single HTML file** with the CSS and JavaScript included together. That makes it easy to open, share, edit, and host without needing a backend or build tools.

The goal was not technical perfection.  
The goal was to make something playable, understandable, and fun.

## Current Version

The current version is:

**V2.31 - Enchanting**

This version builds on the previous **V2.30 - Forge Omens** update and adds a new Occultist-style Enchanting system.

## Features

- Single-file HTML/CSS/JavaScript project.
- Runs directly in a browser.
- No backend required.
- Can be hosted on GitHub Pages.
- Character name, class, difficulty, weapon style, modifier, and seed selection.
- Seeded runs for replayable challenge attempts.
- Multiple playable classes:
  - Barbarian
  - Sorcerer
  - Rogue
  - Necromancer
  - Druid
  - Spiritborn
  - Paladin
  - Warlock
- One-handed + offhand or two-handed weapon setups.
- Full gear panel with multiple equipment slots.
- Class-flavoured item types.
- Item Power and base item stats.
- Magic, Rare, and Legendary item progression.
- Normal affixes and class-specific affixes.
- All gear slots can roll all affix categories.
- Tuning Prisms that hard-target specific affix categories.
- Cube recipes for adding, removing, rerolling, upgrading, and transfiguring items.
- Occultist Enchanting system for locking and rerolling one affix.
- Tempering with limited charges.
- Masterworking up to rank 25.
- Capstones that empower specific affixes.
- Expanded Transfiguration system with risk and reward.
- Entropic Prism for safer but lower-ceiling Transfiguration.
- Rare Forge Omen events after successful crafting actions.
- Greater Affix chances on adding, enchanting, tempering, Transfiguration, and Forge Omens.
- Final Gear Score and rank system.
- Earned badges and almost-badge feedback.
- Local run history stored in the browser.
- Compact Discord-friendly summary copy button.

## How to Play

1. Start a new run.
2. Choose your character name, class, difficulty, weapon setup, modifier, and optional seed.
3. Improve each gear slot using Cube recipes and Blacksmith actions.
4. Use Tuning Prisms to target specific affix categories.
5. Add and reroll affixes until you find stats worth keeping.
6. Use Enchanting to lock and reroll one chosen affix on an item.
7. Upgrade items to Legendary.
8. Temper, Masterwork, and add Capstones.
9. Decide whether to risk Transfiguration.
10. Complete the build to see your final score, rank, badges, MVP item, build identity, and run history.

## Crafting Systems

### Cube Recipes

The Cube is used for the main crafting loop.

Current Cube actions include:

- **Add Affix**  
  Adds a normal affix to the item, up to the normal affix limit.

- **Chaotic Reroll**  
  Rerolls one affix into a different category.

- **Focused Reroll**  
  Uses a Tuning Prism to reroll within a targeted category.

- **Remove Affix**  
  Removes an affix, optionally targeted by prism category.

- **Upgrade Legendary**  
  Upgrades a Rare item into a Legendary item.

- **Transfigure**  
  A risky final gamble that can improve or damage the item.

### Tuning Prisms

Tuning Prisms allow more targeted crafting.

They currently hard-target their listed categories 100% of the time.

Examples:

- Aggressive Prism targets Offensive affixes.
- Protector Prism targets Defensive affixes.
- Resourceful Prism targets Resource affixes.
- Pragmatic Prism targets Mobility and Utility affixes.
- Adept Prism targets Core Stat and Skill affixes.
- Chromatic Prism targets Resistance affixes.
- Entropic Prism modifies Transfiguration only.

### Occultist Enchanting

Enchanting lets you select one normal affix on an item and lock it.

Once locked, that affix is protected from normal rerolls, removal, and Cube distortion. It can still be enchanted again, which rerolls it within its current affix category for an increasing gold cost.

The lock cannot be removed manually.

The only way to clear an enchanted lock is to reset the entire item slot.

Enchanting gives you a way to preserve a lucky roll before taking bigger risks later in the crafting process.

### Tempering

Tempering adds or rerolls one tempered affix on an item.

Each item has limited temper charges, so you cannot reroll forever. Tempering can also roll a Greater Affix.

### Masterworking

Masterworking increases an item’s affix values over time.

Items can be Masterworked up to rank 25. Reaching rank 25 unlocks Capstone crafting.

### Capstones

Capstones empower one affix on an item.

They can target normal affixes or the tempered affix. Some rare outcomes, such as Transfiguration or Forge Omens, can create extra Capstone effects.

### Transfiguration

Transfiguration is the big risky gamble.

It can improve the item through effects like:

- Item Power increases
- Affix value boosts
- Greater Affix upgrades
- Bonus affixes
- Extra Capstones
- Rare Mythic Echo outcomes

But it can also damage the item through effects like:

- Item Power loss
- Affix scrambling
- Affix removal
- Capstone removal
- Catastrophic item outcomes

Most Transfigured items become locked afterwards.

### Entropic Prism

The Entropic Prism changes Transfiguration.

It makes Transfiguration safer by removing the worst outcomes, but it also removes the highest-ceiling rewards.

In simple terms:

> Entropic is safer, but less explosive.

### Forge Omens

Forge Omens are rare events that can trigger after successful crafting actions.

They can bless or complicate a run in unexpected ways. Some may grant resources, improve gear, add Greater Affixes, affect Masterworking, or trigger special Cube-like effects.

They are designed to make runs feel less predictable without turning the game into pure randomness.

## Greater Affixes

Greater Affixes are stronger versions of normal affixes.

They can appear through several systems, including:

- Normal affix adding
- Occultist Enchanting
- Tempering
- Transfiguration
- Forge Omens

The chance depends on the system. Some methods are low-chance, while others are more specialised or risky.

## Difficulty Modes

### Casual

A relaxed mode with effectively unlimited crafting resources.

Good for testing, experimenting, learning the systems, or making silly builds.

### Standard

The main intended mode.

It gives enough resources to build properly while still requiring decisions around gold, dust, prisms, temper charges, Masterworking, and Transfiguration risk.

### Harsh

A tighter challenge mode.

Resources are more limited, mistakes matter more, and you probably cannot perfect every item.

## Run Modifiers

Run modifiers add optional twists to a run.

Examples include extra dust, more gold, fewer prisms, stronger Transfiguration, or cheaper Masterworking.

They are designed to change the feel of a run without requiring a completely separate game mode.

## Scoring and Results

When you complete a build, the game shows a compact result dashboard with:

- Final Gear Score
- Rank
- Best saved score
- Badge count
- Build identity
- MVP item
- Top stats
- Almost badges
- Gear summary
- Affix totals
- Local run history
- Compact Discord summary

The result screen is meant to feel like a dashboard, not a giant report.

## Local Run History

Completed runs are saved locally in your browser.

This means:

- No account is required.
- No backend is used.
- Your history only exists on the device/browser where you played.

## Discord Summary

The game includes a compact summary that can be copied and pasted into Discord.

It includes the character, class, score, rank, badges, seed, build identity, MVP item, and top stats.

## Current Design Rules

Some design choices are intentional:

- All gear slots can roll all affix categories.
- Class-specific affixes stay class-specific.
- Tuning Prisms hard-target their listed categories.
- Entropic Prism only affects Transfiguration.
- Enchant locks are only removed by resetting the item slot.
- Badges are calculated only when the build is completed.
- The result screen should stay compact.
- The Discord summary should stay short and readable.
- The game is inspired by ARPG crafting, but it is not trying to exactly copy Diablo 4.

## Planned / Possible Future Ideas

Ideas that may be added later:

- Sockets
- Gems or rune-style bonuses
- More Forge Omen events
- More run modifiers
- More badge types
- Better animations and polish
- Extra result-card visuals
- More class flavour
- Improved mobile layout
- Better balancing across difficulties
- Possible split into separate files once the project grows larger

## What This Is Not

This is not an official Diablo project.

It is not affiliated with Blizzard Entertainment.

It does not use official Diablo systems exactly and should not be treated as a simulator or build planner.

It is just a small fan-style crafting minigame made for fun.

## Tech Notes

Current structure:

- HTML
- CSS
- JavaScript
- Single-file format
- No backend
- No build tools
- Browser localStorage for run history

This makes it easy to host, edit, and share, but it also means the code is not as cleanly separated as a larger production project would be.

## Credits

Made by **IStreamSandwich**.

Built with a mix of personal ideas, ARPG crafting inspiration, lots of trial and error, and help from AI.
