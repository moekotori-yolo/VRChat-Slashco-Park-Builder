# VRChat Slashco Park Builder

A web-based perks/build randomizer tool for **VRChat's "Slashco" world**.

![Language](https://img.shields.io/badge/language-HTML-orange)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-unlicense-blue)

## Overview

**Slashco Perk Randomizer** is an interactive web application that helps players create and experiment with character builds for the VRChat Slashco experience. The tool allows you to:

- 🎲 **Randomize perks** based on your character level
- 🎯 **Manually select or exclude perks** from your build
- 📊 **View detailed stat calculations** based on selected perks
- 🔒 **Level-lock perks** (perks become available only at specific levels)
- ⚡ **Real-time build updates** with effect descriptions

## Features

### Core Gameplay
- **6 Perk Tiers** with progression from Tier I to Tier VI
- **Perk Points (PP) System** — Limited by character level (max 15 PP at Lv30)
- **Level-Based Progression** — Adjust your character level from 1-30 and see available perks
- **Interactive Perk Cards** — Click to exclude/include perks in your build

### Build Analysis
- **Status Summary Panel** — Shows calculated stat changes:
  - Item healing amount
  - Footstep volume
  - Movement speed
  - Damage taken
  - Refuel speed
- **Active Perks Display** — Detailed description of selected perks with buffs and debuffs
- **Smart Debuff Handling** — Some debuffs are cancelled out by specific perk combinations

### User Controls
- **Level Slider** — Quickly adjust your character level
- **Randomize Button** — Auto-generate a random build that fits your PP budget
- **Reset Button** — Clear all selections and exclusions

## How to Use

1. **Set Your Level** — Use the level slider (1-30) to determine which perks are available
2. **Build Your Setup** — Either:
   - Click the **RANDOMIZE** button for a random build
   - Manually click perk cards to include/exclude them
3. **Review Your Build** — Check the right panel for:
   - Stat modifiers
   - Active perk descriptions
   - Buff/debuff effects
4. **Adjust as Needed** — Exclude perks you don't want and randomize again

## Perks Overview

### Tier I (1 PP) - Level 1+
Basic perks for survival and utility
- **Mechanic** — +50% refuel speed
- **Health** — +50% consumable recovery
- **Adrenaline Rush** — Post-landing buffs
- **Hyper Senses** — Enhanced Slasher audio cues
- And more...

### Tier II (2 PP) - Level 3+
Intermediate perks with more powerful effects
- **Mechanic II** — Improved battery insertion
- **Bounty Hunter** — Quest item visibility
- **Shadow Born** — Enhanced dark vision
- And more...

### Tier III (2 PP) - Level 5+
More specialized and situational perks

### Tier IV (3 PP) - Level 10+
Powerful late-game perks

### Tier V (3 PP) - Level 15+
High-impact perks for advanced players

### Tier VI (4 PP) - Level 20+
Endgame perks with game-changing effects
- **GROUCH化** — Locker regeneration
- **Lead Belly** — 50% damage reduction
- **Anomalous Doctor** — Team-wide healing
- And more...

## Technical Details

### Technology Stack
- **HTML5** — Markup and structure
- **CSS3** — Responsive grid layout with dark theme
- **Vanilla JavaScript** — All interactivity and calculations

### Dark Theme
The app features a sleek dark theme with:
- Neon green accents (`#44ff44`) for selected items
- Dark background for reduced eye strain
- Clear visual distinctions for locked, excluded, and selected perks

### Responsive Design
- Desktop: Two-column layout (perk grid + info panels)
- Mobile: Single-column layout (automatically adapts at 800px)

## File Structure
