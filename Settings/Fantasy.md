# D6 Fantasy — Mechanics Reference

> A supplement to the **OpenD6 / D6 Fantasy** system.  
> Based on *D6 Fantasy Creatures* (West End Games, WEG 51015e, v1.1, © 2005 Purgatory Publishing Inc.).  
> This document summarizes the mechanical framework for using, designing, and converting creatures in the D6 Fantasy system.

---

## Table of Contents

1. [Overview](#overview)
2. [Creature Stat Block Format](#creature-stat-block-format)
3. [Attributes & Skills](#attributes--skills)
4. [Animals vs. Sentient Beings](#animals-vs-sentient-beings)
5. [Natural Abilities](#natural-abilities)
6. [Advantages, Disadvantages & Special Abilities](#advantages-disadvantages--special-abilities)
7. [Fear Factor & Intimidation](#fear-factor--intimidation)
8. [Stampede](#stampede)
9. [Scale](#scale)
10. [Increased Attribute Special Ability](#increased-attribute-special-ability)
11. [Animal Control](#animal-control)
12. [Designing Custom Creatures](#designing-custom-creatures)
13. [Invocations & Spells](#invocations--spells)
14. [Genre Conversion](#genre-conversion)
    - [Attribute Conversion Table](#attribute-conversion-table)
    - [Skill Conversion Table](#skill-conversion-table)
15. [Creature Index](#creature-index)

---

## Overview

*D6 Fantasy Creatures* provides game statistics for over 80 creature types — from mundane animals to powerful monsters and mythological beings. Entries describe the **typical** member of a species; individual specimens may have abilities above, below, or entirely outside the norm due to magical or divine intervention.

**Required reading:** The *D6 Fantasy Rulebook* is the primary rules reference. This supplement is designed to extend it. A genre conversion section (see below) allows creatures to be used in *D6 Adventure* or *D6 Space* with minimal adjustment.

---

## Creature Stat Block Format

Each creature entry follows this structure:

```
Agility #D[+#]: [skills]
Coordination #D[+#]
Physique #D[+#]: [skills]
Intellect #D[+#]
Acumen #D[+#]: [skills]
Charisma #D[+#]: [skills]

Strength Damage: #D
Move: # (movement type)
Fate Points: #
Character Points: #
Body Points: #
Wound Levels: #

Natural Abilities: [list]
  — OR —
Advantages: [list]
Disadvantages: [list]
Special Abilities: [list]
```

**Example — Typical Alligator / Crocodile:**

```
Agility 1D+2: dodge 3D+1, fighting 6D, stealth 4D+2
Coordination 1D
Physique 4D+2: lifting 6D, running 4D+2, swimming 7D
Intellect 1D
Acumen 1D: hide: self only 5D+1, survival 4D, search 4D, tracking 4D
Charisma 1D: intimidation 5D, mettle 5D

Strength Damage: 3D
Move: 9 (land) / 16 (water)
Fate Points: 0
Character Points: 0
Body Points: 21
Wound Levels: 3

Natural Abilities: cold-blooded (+7 to difficulties of all actions until warmed
up); jaws (damage +1D); rending (damage +2D; water only, while clamping);
scaly hide (Armor Value +2); tail slap (damage +2); large size (scale value 3)
```

---

## Attributes & Skills

The six core attributes used throughout this supplement:

| Attribute | Covers |
|-----------|--------|
| **Agility** | Physical quickness, combat reflexes, stealth, flying |
| **Coordination** | Fine motor control, throwing, sleight of hand |
| **Physique** | Strength, endurance, swimming, lifting, running |
| **Intellect** | Reasoning, knowledge, healing, speaking, devices |
| **Acumen** | Perception, awareness, survival, tracking, hide |
| **Charisma** | Social influence, intimidation, mettle |

Skills are listed under their governing attribute. A skill listed without a separate die value defaults to the attribute's base dice.

---

## Animals vs. Sentient Beings

Creatures are categorized in one of two ways, which determines how their stats are presented:

### Animals & Non-Sentient Monsters
- Stats listed as **Natural Abilities**
- Act on instinct; prioritize self-preservation
- Do not actively use skills, though they may have some (e.g., `mettle`) to represent unconscious behavior
- No attribute maximum; minimum of 1D in any attribute
- Generally cannot be taken as player characters

### Sentient Beings
- Stats listed with **Advantages, Disadvantages, and Special Abilities**
- Capable of reasoning and deliberate action
- May be eligible as player characters at the GM's discretion

---

## Natural Abilities

Natural Abilities are the primary mechanical language for animal and monster traits. Common examples:

| Ability | Effect |
|---------|--------|
| `bite` / `teeth` | Damage bonus (e.g., `damage +1D` or `damage +2`) |
| `claws` | Damage bonus; may add to climbing totals |
| `jaws` | Damage bonus, often larger than bite |
| `rending` | Additional damage bonus; usually conditional (e.g., while clamped in water) |
| `thick fur` / `scaly hide` | Armor Value bonus |
| `wings` | Enables flight; Move value specifies flying speed |
| `large size` | Assigns a scale value (see Scale section) |
| `small size` | Assigns a negative scale value |
| `cold-blooded` | Difficulty penalty to all actions in cold conditions |
| `darkness` | Can create a sphere of magical darkness (roll required) |
| `fear` | Bonus to intimidation under specific conditions |
| `immune to nonmagical weapons` | Ignores damage from non-magical sources |
| `sensitive to light` | Cumulative difficulty penalty per round of light exposure |

> **Note:** The effects of **Reduce Attribute** and **Hindrance: Movement** Disadvantages are already factored into creature stat blocks — do not apply them a second time.

---

## Advantages, Disadvantages & Special Abilities

Sentient creatures use the standard Advantages/Disadvantages/Special Abilities framework from the *D6 Fantasy Rulebook*. These are written out explicitly in each creature's entry rather than converted to Natural Abilities.

Bonuses from the **Increased Attribute Special Ability** are shown in parentheses next to the relevant attribute or Strength Damage value. For example:

```
Physique 5D+2 (+1D)
Strength Damage: 3D (+1)
```

The number in parentheses is the modifier granted by that Special Ability — it is already included in the listed value.

---

## Fear Factor & Intimidation

Many creatures attempt to frighten opponents as an instinctual first response to intruders.

**Rules:**
- The creature makes a **threatening gesture** and an **intimidation attempt**
- This is an instinctual reaction: **may only be performed once per encounter**
- The attempt affects **all who witness it**
- If the intimidation succeeds, the target(s) flee; the creature may pursue if hungry or provoked

**Examples of fear displays:**
- Bears: rear up, growl or roar
- Bulls: stamp hooves, toss horns

For full intimidation mechanics, see *D6 Fantasy Rulebook*, page 73.

---

## Stampede

Herd animals become significantly more dangerous when frightened or enraged as a group.

**Rules:**
- A stampeding herd deals **standard Strength Damage** (plus any trampling modifiers)
- Receives **+5 to fighting** for one round per 5–20 animals in the group
- Larger animals require fewer participants to trigger the bonus

---

## Scale

Many creatures have a **scale value** listed in their Natural Abilities. Creatures without a listed scale value have a scale of **0**.

Scale reflects the relationship between size, hit probability, and damage resistance:

- **Large creatures** (positive scale): easier to hit, harder to injure
- **Small creatures** (negative scale): harder to hit, easier to injure

For full scale mechanics and combat modifiers, see *D6 Fantasy Rulebook*, page 71.

**Scale values seen in this supplement:**

| Scale Value | Example Creatures |
|-------------|-------------------|
| 6+ | Largest dragons, dinosaurs |
| 3–5 | Large dragons, roc, sea serpent, giant squid |
| 1–2 | Bears (grizzly/polar), bull, elephant, giants |
| 0 | Human-sized creatures (default) |
| −1 to −3 | Small creatures, sprites, pixies |

---

## Increased Attribute Special Ability

When a creature has the **Increased Attribute Special Ability**, its base attribute or Strength Damage value is higher than it would otherwise be. The bonus from this ability is shown in **parentheses** after the value in the stat block.

This is purely informational — the parenthetical modifier is already included in the die code. Do not add it again during play.

---

## Animal Control

The **Animal Control** ability (available to some player characters and NPCs) has the following restrictions when used against creatures in this supplement:

- May only be used on **ordinary creatures** (e.g., birds, cattle, common animals)
- **Cannot** be used on unusual creatures or monsters (e.g., perytons, giant bats, dragons)
- **Cannot** be used on any creature whose stat block includes Advantages, Disadvantages, and/or Special Abilities, unless otherwise noted

---

## Designing Custom Creatures

To create homebrew monsters and animals:

1. **Set attributes** — Monsters have no attribute maximum. Any attribute may be as low as 1D (commonly Intellect and Coordination for animals).
2. **Use Natural Abilities** as the mechanical expression of physical traits — reference existing entries for damage bonuses, armor values, movement types, and conditional modifiers.
3. **Use Disadvantages and Special Abilities as inspiration** — even if the creature isn't sentient, the mechanical building blocks (Increased Attribute, Hindrance, etc.) can guide how you model unusual traits.
4. **Track modifications** — The *D6 Fantasy Rulebook* (page 127) includes a sheet for recording modified and new monster stat blocks.

---

## Invocations & Spells

Several creatures in this supplement are associated with specific game mechanics beyond combat. These are listed here for quick reference:

### Invocations
| Name | Related Creature | Location |
|------|-----------------|----------|
| Bunyip Summoning Invocation | Bunyip | p. 12 |
| Insect Repellent Invocation | Swarms | p. 83 |

### Spells
| Name | Related Creature | Location |
|------|-----------------|----------|
| Shapechanging Potion Spell | Flying Cat | p. 35 |
| Bird's Eye Spell | Familiar (Owl) | p. 64 |
| Chatterbox Spell | Nymph | p. 66 |
| Simple Shapechanging Spell | Obayifo | p. 67 |
| Minor Raise Skeleton Spell | Skeleton | p. 74 |
| Stympalian Flying Potion Spell | Stymphalian Bird | p. 81 |

---

## Genre Conversion

Because skill resolution and damage mechanics are identical across the D6 System genre books, converting creatures to **D6 Adventure** or **D6 Space** only requires translating **attributes** and **skills**.

After converting, review the die codes and adjust pips to better reflect your interpretation of the creature in the new genre.

### Attribute Conversion Table

**For non-sentient beings (animals & monsters):**

| D6 Fantasy | D6 Adventure | D6 Space |
|------------|-------------|----------|
| Agility | Agility | Reflexes |
| Coordination | Agility | Coordination |
| Physique | Strength | Physique |
| Intellect | Knowledge | Knowledge |
| Acumen | Perception | Perception |
| Charisma | Presence | Presence |

### Skill Conversion Table

| D6 Fantasy | D6 Adventure | D6 Space |
|------------|-------------|----------|
| dodge (Agility) | dodge (Agility) | dodge (Reflexes) |
| fighting (Agility) | brawling (Agility) | brawling (Reflexes) |
| flying (Agility) | flying/0-G (Agility) | flying (Reflexes) |
| running (Physique) | running (Agility) | running (Physique) |
| stealth (Agility) | sneak (Perception) | sneak (Reflexes) |
| swimming (Physique) | swim (Strength) | swimming (Physique) |
| intimidation (Charisma) | intimidation (Knowledge) | intimidation (Presence) |
| mettle (Charisma) | mettle (Knowledge) | mettle (Presence) |
| search (Acumen) | search (Perception) | search (Perception) |
| hide (Acumen) | hide (Perception) | hide (Perception) |
| tracking (Acumen) | search (Perception) | tracking (Perception) |
| survival (Acumen) | survival (Knowledge) | survival (Perception) |
| scholar (Intellect) | scholar (Knowledge) | scholar (Knowledge) |
| healing (Intellect) | medicine (Technical) | medicine (Knowledge) |
| investigation (Acumen) | investigation (Perception) | investigation (Perception) |
| streetwise (Acumen) | streetwise (Knowledge) | streetwise (Perception) |
| jumping (Agility) | climb/jump (Strength) | jumping (Reflexes) |
| stamina (Physique) | stamina (Strength) | stamina (Physique) |
| gambling (Acumen) | gambling (Perception) | gambling (Perception) |
| lifting (Physique) | lifting (Strength) | lifting (Physique) |
| throwing (Coordination) | throwing (Agility) | throwing (Coordination) |
| sleight of hand (Coordination) | sleight of hand (Agility) | sleight of hand (Coordination) |
| trading (Intellect) | business (Knowledge) | business (Knowledge) |
| traps (Intellect) | security, demolitions (Technical) | security, demolitions (Knowledge) |
| speaking (Intellect) | languages (Knowledge) | languages (Knowledge) |
| disguise (Acumen) | con (Perception) | disguise (Presence) |
| know-how (Acumen) | know-how (Perception) | know-how (Perception) |

---

## Creature Index

All creature types included in this supplement, in alphabetical order:

| Creature | Notes |
|----------|-------|
| Alligator / Crocodile | |
| Bear | Black Bear, Grizzly, Polar Bear |
| Bird of Prey | Hawk, Eagle |
| Giant Boar | |
| Bogie | |
| Bogle | |
| Bull | |
| Bunyip | Includes summoning invocation |
| Cat | Domestic Cat, Lion, Tiger |
| Celestial | |
| Centaur | |
| Cyclops | |
| Demon | |
| Dinosaur | Tyrannosaurus Rex, Triceratops, Velociraptor, Pterosaur |
| Djinn | |
| Dog | Guard/Hunting Dog, Lap Dog |
| Dragon | Air, Earth, Fire, Water, Oriental, Skeleton |
| Dwarf | Dwende, Mynyd, Chanak, Wavelorn |
| Giant Bat | Giant Cave Bat, Hell Bat |
| Giant Eel | |
| Ekimmu | |
| Elemental | Air, Earth, Fire, Water |
| Elephant | |
| Elf | |
| Empusa | |
| Fairy | Green Folk, Glade Fairies |
| Familiar | Cat, Owl, Snake |
| Fiana | |
| Flying Cat | Includes shapechanging spell |
| The Furies | |
| Gargoyle | |
| Ghost Warrior | |
| Ghoul | |
| Giang Shi | |
| Giant | Air, Earth, Fire, Water Giants |
| Gnome | |
| Golem | Flesh, Iron, Stone, Wood |
| Gwyllion | |
| Harpy | |
| Horse | Riding/Draft, War Horse |
| Hydra | |
| Kelpie | |
| Leprechaun | |
| Lizard | Crimson Sandking, Rider-Lizard, Small Sand Lizard |
| Mermaid | |
| Minions of Evil | Goblin/Gnoll/Orc, Ogre/Bugbear |
| Minotaur | |
| Mummy | |
| Nymph | Includes chatterbox spell |
| Obayifo | Includes shapechanging spell |
| Oni | |
| Ooze | |
| Owl | |
| Pegasus | |
| Peryton | |
| Pixie | |
| Rakshasa | |
| Giant Rat | |
| Roc | |
| Sasquatch / Yeti | |
| Satyr | |
| Scorpion | Small, Giant |
| Sea Serpent | |
| Skeleton | Includes raise skeleton spell |
| Snake | Constrictor, Small Venomous, Giant Venomous |
| Snake-Woman | |
| Sphinx | |
| Giant Spider | Jump Spider, Tunnel Spider |
| Sprite | |
| Giant Squid | |
| Stymphalian Bird | Includes flying potion spell |
| Swarms | Small Animal Swarm, Insect Swarm |
| Toad | Small, Giant, Frost |
| Triton | |
| Troll | |
| White Unicorn | |
| Valkyrie | |
| Vampyr | |
| Wendigo | |
| Werewolf | |
| Wolf | |
| Yara-Ma-Yah-Who | |
| Zombie | |

---

*For full stat blocks, lore, and GM guidance on each creature, refer to the original D6 Fantasy Creatures PDF (WEG 51015e).*  
*D6 System is a trademark and property of Purgatory Publishing Inc.*
