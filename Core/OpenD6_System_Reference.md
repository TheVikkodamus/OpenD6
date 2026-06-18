# OpenD6 System Reference Document

> A community reference for the OpenD6 roleplaying game system, compiled from *D6 Space* (West End Games, 2004) and the *Star Wars Roleplaying Game: Revised, Expanded and Updated* (REUP Team, 2015). OpenD6 mechanics are open and license-free; this document is provided for fans and hobbyists.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Core Concepts](#core-concepts)
3. [Characters](#characters)
   - [Attributes](#attributes)
   - [Skills](#skills)
   - [Specializations](#specializations)
   - [Advanced Skills](#advanced-skills)
   - [Starting Characters](#starting-characters)
   - [Character Options (Advantages, Disadvantages, Special Abilities)](#character-options)
4. [The Dice System](#the-dice-system)
   - [Die Codes](#die-codes)
   - [The Wild Die](#the-wild-die)
   - [Difficulty Numbers](#difficulty-numbers)
   - [Opposed Rolls](#opposed-rolls)
   - [Modifiers](#modifiers)
   - [Untrained Skill Use](#untrained-skill-use)
   - [Die Code Simplification](#die-code-simplification)
5. [Scenes and Rounds](#scenes-and-rounds)
   - [Scenes](#scenes)
   - [Rounds](#rounds)
   - [Initiative](#initiative)
   - [Actions in a Round](#actions-in-a-round)
   - [Multiple Actions](#multiple-actions)
   - [Reaction Skills](#reaction-skills)
   - [Free Actions](#free-actions)
   - [Combined Actions](#combined-actions)
6. [Task Resolution](#task-resolution)
   - [Preparing](#preparing)
   - [Rushing](#rushing)
   - [Multiple-Roll Tasks](#multiple-roll-tasks)
7. [Combat](#combat)
   - [Ranged Combat](#ranged-combat)
   - [Melee Combat](#melee-combat)
   - [Reaction Skills in Combat](#reaction-skills-in-combat)
   - [Cover and Protection](#cover-and-protection)
   - [Armor](#armor)
   - [Scale](#scale)
   - [Surprise](#surprise)
   - [Combat Modifiers](#combat-modifiers)
   - [Combat Options](#combat-options)
8. [Damage](#damage)
   - [Character Damage Chart](#character-damage-chart)
   - [Wound Levels](#wound-levels)
   - [Body Points (Optional)](#body-points-optional)
   - [Stun Damage](#stun-damage)
   - [Damage Options](#damage-options)
9. [Healing](#healing)
   - [Natural Healing](#natural-healing)
   - [Medpacs / First Aid](#medpacs--first-aid)
   - [Advanced Medical Care](#advanced-medical-care)
10. [Character Points and Force/Fate Points](#character-points-and-forcefate-points)
    - [Character Points](#character-points)
    - [Force Points / Fate Points](#force-points--fate-points)
    - [Dark Side Points (Optional)](#dark-side-points-optional)
11. [Character Advancement](#character-advancement)
    - [Improving Skills](#improving-skills)
    - [Learning New Skills](#learning-new-skills)
    - [Improving Attributes](#improving-attributes)
12. [Complications](#complications)
13. [Gamemaster Tips](#gamemaster-tips)

---

## Introduction

OpenD6 is a fast, flexible, and cinematic tabletop roleplaying game system built on a simple core mechanic: **roll a pool of six-sided dice and add them up**. The system was originally developed by West End Games for their *Star Wars* roleplaying line and later released as an open system under the name OpenD6.

The system is designed to keep the action moving. Dice pools are straightforward, difficulty numbers are easy to estimate, and the game rewards clever roleplay alongside mechanical skill. Characters feel competent from the start and grow meaningfully over time.

This document is a system-agnostic reference. It covers the core rules and mechanics common across OpenD6 titles. Setting-specific content (species, equipment, Force powers, etc.) belongs in separate setting documents.

---

## Core Concepts

- **Die Code** — The number of six-sided dice you roll for a skill or attribute (e.g., `4D`, `3D+2`).
- **Attribute** — A broad, innate characteristic common to all characters (e.g., Strength, Perception).
- **Skill** — A more specific application of an attribute that improves with practice.
- **Wild Die** — One specially colored die in every roll that introduces dramatic swings of luck.
- **Difficulty Number** — The target number you must meet or beat on a dice roll to succeed.
- **Character Points** — A resource spent to improve rolls and, between adventures, to advance skills.
- **Force Points / Fate Points** — A rarer, more powerful resource representing moments of extraordinary effort or destiny.

---

## Characters

### Attributes

Every character has a set of core **attributes** representing their fundamental physical and mental abilities. Attributes are rated in die codes (e.g., `3D`, `4D+1`). All skills under an attribute begin at that attribute's die code.

The standard OpenD6 attribute set is:

| Attribute | Description |
|---|---|
| **Agility** (or **Dexterity**) | Physical coordination, reflexes, and eye-hand coordination. Covers combat skills, dodging, and acrobatics. |
| **Strength** | Physical power and toughness. Used to resist damage and for feats of brute force. |
| **Mechanical** | Ability to operate mechanical equipment: vehicles, starships, sensors, shields. |
| **Knowledge** | Overall intelligence, education, and breadth of information. |
| **Perception** | Awareness of self and surroundings; ability to interact with, read, and influence others. |
| **Technical** | Ability to repair, modify, and construct technology. |
| **Extranormal** *(optional)* | Extraordinary abilities beyond normal human capacity (psionics, magic, the Force, etc.). Most characters begin at `0D` in this attribute. |

> **Note for Gamemasters:** Different OpenD6 settings may use slightly different attribute names or groupings. The concepts remain the same.

### Skills

Skills are specific applications of attributes. A character who hasn't trained in a particular skill uses their governing attribute instead.

When a skill is **improved**, the player adds dice or pips to the base attribute value. Improved skills are written separately on the character sheet alongside their die code.

**Example:** A character with Perception `3D` who improves *search* by `1D` has *search* `4D`. All other Perception skills remain at `3D`.

### Specializations

A **specialization** is a narrow focus within a skill, granting a bonus when that specific focus is used. Specializations cost half as much to advance as the base skill (rounded up).

- When using the specialization, roll the specialization's die code.
- When doing anything else covered by the base skill, roll the base skill (or attribute).
- Improving the base skill does **not** improve the specialization, and vice versa.

**Example:** A character with *blaster* `5D` and *blaster: pistol* `6D` rolls `6D` when firing a pistol and `5D` when firing any other blaster.

Specialization suggestions are listed under each skill in the setting's skill chapter. New specializations may be created with Gamemaster approval.

### Advanced Skills

Advanced skills (marked with **(A)** in skill lists) represent highly specialized expertise requiring dedicated study. They **cannot** be attempted by untrained characters.

- Advanced skills must have prerequisite skills at a minimum die code.
- An advanced skill begins at `1D` when first learned, not at the attribute level.
- Costs and training times for advanced skills are higher (see [Character Advancement](#character-advancement)).

**Examples:** (A) Medicine, (A) Starship Engineering, (A) Droid Programming.

### Starting Characters

#### Using a Template

The simplest way to begin is to select a **template** — a pre-built character archetype that defines starting attribute die codes and lists relevant skills. Templates provide a name, background, personality, and starting equipment.

**To finish a template:**
1. Pick skills to add your starting skill dice to.
2. Note any special abilities or extranormal traits.
3. Purchase or note starting equipment.
4. Assign Force/Fate Points (all characters start with 1) and Character Points (all characters start with 5).

#### Building from Scratch (Defined Limits)

For a standard Human character:

- **Attributes:** Distribute `18D` among all attributes (minimum `1D`, maximum `5D` per attribute, except Extranormal which begins at `0D`).
- **Skills:** Distribute `7D` among skills. No more than `3D` added to any single skill at creation.
- **Move:** `10` meters per round (standard).
- **Body Points:** Roll Strength and add 20 (if using the Body Points system).
- **Strength Damage:** Drop pips from Strength, divide by 2, round up (e.g., `3D+2` → `3 ÷ 2 = 1D+2` → `2D`).
- **Character Points:** `5`
- **Fate/Force Points:** `1`

#### Creation Point Pool (Alternative)

For point-buy character creation, a novice character receives **79 creation points**:

| Option | Cost |
|---|---|
| 1 attribute die | 4 points |
| 1 skill die | 1 point |
| 3 specialization dice | 1 point |
| Advantages / Special Abilities | See [Character Options](#character-options) |

Up to `10` additional creation points may be gained by taking Disadvantages. Non-Human species may have different totals and starting options.

### Character Options

Many OpenD6 settings allow characters to take **Advantages**, **Disadvantages**, and **Special Abilities** that further customize them.

- **Advantages** — Positive traits, contacts, resources, or circumstances that help the character. Each has a Rank that reflects its power and cost.
- **Disadvantages** — Negative traits, obligations, or weaknesses that complicate the character's life. Taking Disadvantages provides bonus creation points.
- **Special Abilities** — Extraordinary capabilities beyond normal human limits (enhanced senses, natural weapons, unusual resistances, etc.). These may have Enhancements (improving them) and Limitations (restricting them).

---

## The Dice System

### Die Codes

A **die code** tells you how many six-sided dice to roll and add together, sometimes with a small modifier.

- `3D` — Roll 3 dice, add the results.
- `3D+1` — Roll 3 dice, add results, then add 1.
- `3D+2` — Roll 3 dice, add results, then add 2.
- Adding 3 pips (`+3`) is the same as gaining another full die. So `3D+3 = 4D`.

When comparing die codes, the same progression applies: `1D`, `1D+1`, `1D+2`, `2D`, `2D+1`, and so on.

### The Wild Die

Every time a character rolls dice, **one die must be a different color** — this is the **Wild Die**. It is not an extra die; it is simply one of the rolled dice designated as special.

| Wild Die Result | Effect |
|---|---|
| **2–5** | Add normally to the total. |
| **6** | Add 6 to the total, then roll the Wild Die again and add that result. If another 6 appears, keep rolling. |
| **1** | Inform the Gamemaster. The GM may choose one of three options (see below). |

**When a 1 appears on the Wild Die (first roll only), the GM may:**
1. **Add normally** — Total the dice as usual; no complication occurs.
2. **Complication** — The roll may still succeed, but something goes wrong (see [Complications](#complications)).
3. **Subtract and penalize** — Remove the 1 and also subtract the highest other die from the total.

**Example (subtract and penalize):** A player rolls `6D` and gets `3, 4, 2, 5, 3` on the regular dice and `1` on the Wild Die. The GM subtracts the `1` and the highest other die (`5`), leaving `3 + 4 + 2 + 3 = 12`.

The Wild Die rule applies to **all** dice rolls in the game: skills, attributes, weapon damage, and initiative.

### Difficulty Numbers

When a character attempts a task, the GM sets a difficulty. The player must roll **equal to or greater than** the difficulty number to succeed.

| Difficulty Level | Difficulty Number Range |
|---|---|
| **Very Easy** | 1–5 |
| **Easy** | 6–10 |
| **Moderate** | 11–15 |
| **Difficult** | 16–20 |
| **Very Difficult** | 21–30 |
| **Heroic** | 31+ |

**Guidelines for choosing a difficulty:**

- **Very Easy** — Almost anyone can do this most of the time. No real chance of failure.
- **Easy** — Most characters succeed, but there's a real chance of failure.
- **Moderate** — Requires focus and skill. Average characters fail about half the time.
- **Difficult** — Only skilled characters succeed regularly.
- **Very Difficult** — Even experts have to work for it. Reserved for exceptional feats.
- **Heroic** — Near-impossible. Reserved for legendary, climactic moments.

#### Random Difficulties (Optional)

Instead of choosing a fixed difficulty number, the GM may roll dice to determine it:

| Task Difficulty | Dice to Roll |
|---|---|
| Very Easy | `1D` |
| Easy | `2D` |
| Moderate | `3D–4D` |
| Difficult | `5D–6D` |
| Very Difficult | `7D–8D` |
| Heroic | `9D+` |

### Opposed Rolls

When one character acts **directly against** another, both roll their relevant skills. The higher roll succeeds. In the event of a tie, the **initiating character** wins.

**Examples of opposed rolls:**
- Two characters haggling — both roll *bargain*.
- A character firing a blaster vs. a target dodging — attacker rolls attack skill, defender rolls *dodge*. If the dodge roll is higher, the attack misses.
- Sneaking past a guard — sneaking character rolls *sneak*, guard rolls *search* or *Perception*.

### Modifiers

Modifiers adjust a die roll when one side has a clear advantage or disadvantage beyond raw skill.

| Modifier | Situation |
|---|---|
| `+1 to +5` | Slight advantage |
| `+6 to +10` | Good advantage |
| `+11 to +15` | Decisive advantage |
| `+16+` | Overpowering advantage |

Modifiers may be added to either side's roll or to a difficulty number.

### Untrained Skill Use

If a character attempts a skill they have no dice in, they roll the governing **attribute** instead. The GM may add an **unskilled modifier** to the difficulty — typically `+5`, though it can range from `+1` (simple tasks) to much higher for complex ones.

Some tasks (brain surgery, building a starship) may be impossible to attempt without appropriate skills and training.

> **Exception:** Do not apply the untrained modifier for resisting damage, most uses of *dodge* and *brawling* in combat, attempts to find clues with *search*, or resisting interaction attempts with *willpower*.

### Die Code Simplification

When a die code grows very large, tracking dozens of dice becomes cumbersome. Use this shortcut:

- Roll **5 dice** (including the Wild Die) and add a bonus number based on the original die code.
- Alternatively, roll **only the Wild Die** and add a larger bonus.

| Original Die Code | Bonus (5D method) | Bonus (Wild Die only) |
|---|---|---|
| 5D | +0 | +0 |
| 6D | +4 | +4 |
| 7D | +7 | +7 |
| 10D | +18 | +32 |
| 15D | +35 | +49 |
| 20D | +53 | +67 |
| 25D | +70 | +84 |
| 30D | +88 | +102 |

For codes beyond `50D`, subtract 5 from the die code and multiply by 3.5 (round up) to get the bonus.

Character Points spent on a roll should be rolled separately from the bonus.

---

## Scenes and Rounds

OpenD6 tracks time in two modes: **scenes** for everyday moments and **rounds** for moment-by-moment action.

### Scenes

A **scene** is used when precise timing doesn't matter. The GM describes the situation, players declare what their characters do, and the GM describes the outcome. A scene can cover seconds, hours, or weeks of in-game time.

Use scenes for travel, investigation, socializing, and other non-critical activities. Skill rolls happen in scenes when there's meaningful risk of failure; simple or automatic tasks don't require rolls.

### Rounds

A **round** represents approximately **five seconds** of in-game time. Rounds are used:

- During combat
- During chases
- When precise timing is critical (e.g., defusing a bomb)
- When it matters who acts first

Each round has two phases, which repeat until the round-by-round action ends:
1. **Initiative**
2. **Roll Actions**

### Initiative

At the start of each round:

1. Each **side** nominates its character with the highest Perception to roll that attribute.
2. The side with the **highest initiative roll** chooses whether to act **first or last** that round.
3. Reroll on a tie.

**Initiative does not count as an action.** Character Points and Force Points may not be used to boost initiative, but wound penalties apply.

**Tie-breaking order (if needed):**
1. Ability or talent that grants acting first
2. Perception
3. *Search* skill
4. Dexterity/Agility
5. *Dodge* skill
6. Special equipment

### Actions in a Round

Characters on the winning side act in **Perception order** (highest first). Each player declares the number of actions their character takes and accepts any multiple-action penalties, then rolls.

After all characters on one side have taken their first action, the other side acts. After all first actions are resolved, characters with second actions act, and so on until all actions are complete.

> Characters **cannot skip** actions and wait to go later in a round.

### Multiple Actions

A character may attempt more than one action in a round, but each additional action **beyond the first** imposes a `−1D` penalty to **all** skill and attribute rolls that round (not to damage, damage resistance, or initiative).

| Actions Taken | Penalty to All Rolls |
|---|---|
| 1 | None |
| 2 | −1D |
| 3 | −2D |
| 4 | −3D |

**A character may not use any skill or attribute reduced to 0D.**

If a character has a special ability granting extra free actions, the penalty only kicks in once those free actions are used.

### Reaction Skills

When a character is attacked, they may **react** to defend themselves. Reaction skills include:

- **Dodge** — Against ranged attacks (blasters, bullets, missiles, etc.)
- **Melee Parry** — Against melee attacks, when the defender has a weapon.
- **Brawling Parry** — Against melee and brawling attacks, when the defender is unarmed.
- **Lightsaber** — Against melee attacks when the defender wields a lightsaber.
- **Vehicle Operation Skills** — "Vehicle dodge" when piloting a vehicle.
- **Starship Piloting Skills** — "Starship dodge" when piloting a vessel.

**Using a reaction skill:**
- A character may react at any point during the round, spending one of their remaining actions (or declaring it as an additional action with its associated penalty).
- The reaction roll becomes the new difficulty number the attacker must beat.
- This difficulty applies to **all attacks of that type** made against the defender for the rest of the round.
- A poor reaction roll can actually **lower** the effective difficulty, making the character easier to hit than before.

**Full Reaction:** A character may forgo all other actions to make a full reaction. Their reaction roll is **added** to the base difficulty of all incoming attacks of that type.

### Free Actions

Free actions are simple, nearly automatic activities that don't require a roll and do not count as an action. Examples:

- Rolling Perception for initiative
- Shouting a sentence or two across a room
- Taking a quick glance around (may warrant a Perception roll at GM's discretion)
- Grabbing something off a nearby counter (in non-stressful situations)
- Walking very slowly over easy terrain (cautious movement)
- Rolling Strength to resist damage in combat
- Rolling to resist mental powers or Force abilities

### Combined Actions

Multiple characters may work together on a single task. One character is designated the **leader**, who rolls a *command* (or Perception) skill against a difficulty chosen by the GM based on task complexity, character experience, and group cohesion.

**If the command roll succeeds**, add a combined action bonus to the character with the highest relevant skill:

- `+1D` per 3 characters combining, plus `+1` for 1 extra, `+2` for 2 extra.
- **Example:** 8 characters = `+2D+2` bonus.

**If the command roll fails**, subtract `−1D` from the bonus for every point the roll missed by. The bonus cannot go below `0D`.

If combining on a combat task, the bonus may be split between the attack roll and damage roll.

---

## Task Resolution

### Preparing

A character who spends **twice the normal time** on a task receives a `+1D` bonus per doubling of time, up to a maximum of `+3D`. The character must focus entirely on the task — no other actions, no being shot at.

**Maximum bonus from preparation: `+3D`.**

Common uses: aiming (spending an extra round sighting before shooting), carefully reading technical manuals before a repair, extensive planning before a heist.

### Rushing

A character may attempt to complete a task (requiring two or more rounds) in **half the normal time** by rolling only **half their normal skill dice** (round down).

The GM has final say on whether rushing is possible for a given task.

### Multiple-Roll Tasks

Some tasks are too complex for a single roll. The GM may break them into several smaller rolls, each covering a stage of the work. Each roll may have a different skill, difficulty, and time requirement. Failure at one stage may complicate later stages.

---

## Combat

### Ranged Combat

Any weapon used at a distance uses a ranged attack skill (e.g., *blaster*, *firearms*, *thrown weapons*, *missile weapons*). The attacker rolls their attack skill against a difficulty based on **range**.

**Standard Range Difficulties:**

| Range Band | Difficulty |
|---|---|
| Point-blank (within ~3m) | Very Easy |
| Short range | Easy |
| Medium range | Moderate |
| Long range | Difficult |

Each weapon lists its specific range bands in meters in the equipment section. If the attacker's roll meets or exceeds the difficulty, the attack hits and the attacker rolls damage.

**Estimating Range (Quick Reference):**
- Targets within arm's reach or just beyond: **point-blank** (Very Easy)
- Most indoor combat: **short range** (Easy)
- Most outdoor combat: **medium range** (Moderate)
- Sniping across open terrain: **long range** (Difficult)

### Melee Combat

Melee attacks cover weapons used in close combat. Most use the *melee combat* skill (or the Dexterity/Agility attribute). Each melee weapon has a difficulty to use.

**Brawling** (unarmed combat) uses the *brawling* skill or Strength and has a base difficulty of **Very Easy**.

If the attack roll equals or exceeds the difficulty, the attack hits and the attacker rolls damage (usually `STR + weapon bonus`).

### Reaction Skills in Combat

When attacked, a defender may roll a reaction skill:

- **Ranged attack:** Defender rolls *dodge*. Result becomes new difficulty for the attack.
- **Melee attack (armed defender):** Defender rolls *melee parry*. Armed defenders vs. unarmed attackers gain `+5` to their parry.
- **Melee/brawling attack (unarmed defender):** Defender rolls *brawling parry*. Unarmed defenders vs. armed attackers suffer `+10` to the attacker's roll.

The reaction roll is in effect for **all attacks of that type** for the rest of the round.

### Cover and Protection

**Lighting and Visibility Modifiers (added to difficulty to hit):**

| Condition | Modifier |
|---|---|
| Light smoke | `+1D` |
| Thick smoke | `+2D` |
| Very thick smoke | `+4D` |
| Poor light | `+1D` |
| Moonlit night | `+2D` |
| Complete darkness | `+4D` |

**Physical Cover Modifiers (added to difficulty to hit):**

| Coverage | Modifier |
|---|---|
| ¼ covered | `+1D` |
| ½ covered | `+2D` |
| ¾ covered | `+4D` |
| Fully covered | Cannot hit directly; must destroy cover |

If an attack roll beats the base difficulty but not the cover modifier, the shot hits the cover object. Roll the attack's damage against the cover's **Body Strength** to determine damage to the cover — and whether any damage bleeds through to the character behind it.

**Sample Cover Body Strength:**

| Cover | Body Strength |
|---|---|
| Flimsy wooden door | `1D` |
| Standard wooden door | `2D` |
| Standard metal door | `3D` |
| Reinforced door | `4D` |
| Blast door | `6D` |

**Damage to Cover / Damage Passed Through:**

| Damage Roll Exceeds Body Strength Roll By | Cover Condition | Damage Reduction |
|---|---|---|
| 0–3 | Not seriously damaged | No damage to character |
| 4–8 | Lightly damaged | `−4D` to weapon damage |
| 9–12 | Heavily damaged | `−2D` to weapon damage |
| 13–15 | Severely damaged | `−1D` to weapon damage |
| 16+ | Destroyed | Full weapon damage |

### Armor

Armor adds to a character's **Strength roll when resisting damage**. It does not add to other Strength rolls (except armored powersuits that assist lifting).

Armor may provide different protection against **physical** and **energy** attacks. Some armor also imposes **Dexterity penalties** due to bulk.

**Example:** Stormtrooper armor grants `+2D` vs. physical attacks, `+1D` vs. energy attacks, and `−1D` to Dexterity and related skills.

**Armor Damage:** When a wearer takes damage through an armored area, the armor itself degrades:

| Injury to Wearer | Armor Damage |
|---|---|
| Wounded | Lightly damaged (`−1 pip`) |
| Incapacitated | Heavily damaged (`−1D`) |
| Mortally Wounded | Severely damaged (useless, may be repaired) |
| Killed | Destroyed |

### Scale

The game uses a **scale** system to handle conflicts between objects and beings of vastly different sizes. Scales from smallest to largest:

| Scale | Modifier |
|---|---|
| Character / Creature | — |
| Speeder | `2D` |
| Walker | `4D` |
| Starfighter | `6D` |
| Capital Ship | `12D` |
| Death Star / Superweapon | `24D` |

When comparing scales, find the **adjusted modifier** — the difference between the two scales.

**Lower vs. Higher:**
- The lower-scale attacker adds the adjusted modifier to their **attack roll**.
- The higher-scale target adds the adjusted modifier to their **damage resistance roll**.

**Higher vs. Lower:**
- The higher-scale attacker rolls normally; the lower-scale target adds the adjusted modifier to their **dodge/defense roll**.
- The higher-scale attacker adds the adjusted modifier to their **damage roll**.

### Surprise

When characters are caught off guard, attackers may automatically act **before the surprised side** on the first round. The surprised side cannot use reaction skills against those first actions.

**Determining surprise:** Attackers roll *sneak*; potential targets roll *search* or Perception. Any target whose detection roll equals or exceeds any attacker's sneak roll is **not surprised** by that attacker.

### Combat Modifiers

| Situation | Modifier |
|---|---|
| Attacker is blind / blinded | `−4D` to attack |
| Target is blind, blinded, or attacked from behind | `+4D` to attack |
| Low gravity | `−1D` to attack |
| Zero gravity | `−2D` to attack |
| Heavy gravity | `−2D` to attack (varies) |
| Target is crouching / prone (Short or PB range) | `−2D` to attack difficulty (easier to hit) |
| Target is crouching / prone (Medium or Long range) | `+2D` to attack difficulty (harder to hit) |
| Target is moving while crouching | `+2D` to attack difficulty |

**Drawing Weapons:** Drawing a weapon counts as **one action**. Drawing and using in the same round incurs a multiple-action penalty.

**Fire Control:** Some weapons (vehicle and starship weapons, artillery) have a **fire control** die code that is added to the operator's attack roll.

**Fire Rate:** Weapons with a fire rate may be fired multiple times per round (or only once every several rounds if the rate is a fraction). No listed fire rate means the weapon can be fired as many times per round as actions permit.

**Ammunition:** Weapons with an ammo rating can fire that many times before reloading. Reloading takes one action.

**Blast Radius:** Weapons with a blast radius affect everything within that radius. Different radii may have different damage values (decreasing with distance from the blast center).

### Combat Options

#### Acrobatics

Acrobatics may enhance brawling or melee attacks. Roll acrobatics alongside the attack in the same round. If successful, add half the margin of success (rounded up) to the damage total — not to the attack roll itself. One acrobatics roll affects one attack only.

#### Called Shots

A character may aim at a specific small target:

| Target Size | Difficulty Modifier |
|---|---|
| 10–50 cm long | `+1D` |
| 1–10 cm long | `+4D` |
| Less than 1 cm | `+8D` |

On success, the attacker may knock an item from the target's hand, grab a limb, pin the target to a wall, or deal `+1D` (or more) bonus damage. Exact effects are at GM discretion.

#### Hit Locations

| Location | Difficulty Modifier | Damage Modifier |
|---|---|---|
| Head | `+1D` | `+12` |
| Heart | `+4D` | `+12` |
| Chest/Abdomen | None | None |
| Arm (L or R) | `+1D` | `−2` |
| Leg (L or R) | `+1D` | `−1` |
| Hand (L or R) | `+4D` | `−2` |

Sufficient damage to a specific location may impair use of that body part until healed.

#### Quick Draw

The attacker declares a Quick Draw, dividing their attack skill between **speed draw dice** and **accuracy dice**. The attacker may do nothing else in the round (including dodge). Both parties roll speed draw dice; the higher roll shoots first. Only the accuracy dice are used for the actual attack roll.

#### Suppression Fire

Instead of aiming to hit, a character lays down fire to force enemies into cover. Difficulty to hit the suppressing character increases `+1` per shot fired (or `+1 level` per burst with automatic weapons).

#### Martial Arts

Characters trained in *brawling: martial arts* (a specialization) may unlock specific techniques for every full `1D` of martial arts skill improvement. One technique may be selected per die of skill gained. Example techniques:

- **Blindfighting** *(Very Difficult)* — Fight effectively using senses other than sight.
- **Disarm** *(Moderate)* — Force an opponent to drop their weapon.
- **Elbow Smash** *(Very Easy)* — Deal `+1D` bonus damage.
- **Flip** *(Moderate)* — Hurl an attacker who has grappled you; deals `3D` damage.
- **Instant Wound** *(Difficult)* — Strike to maximum effect; inflict severe damage.

---

## Damage

When an attack hits, the attacker rolls damage. The defender rolls their Strength (plus any armor bonuses) to resist. The **difference** between the damage roll and the resistance roll determines the wound level.

### Character Damage Chart

| Damage Roll Exceeds Resistance Roll By | Effect |
|---|---|
| 0 (tied or lower) | No effect |
| 1–3 | **Stunned** |
| 4–8 | **Wounded** |
| 9–12 | **Incapacitated** |
| 13–15 | **Mortally Wounded** |
| 16+ | **Killed** |

Melee weapons do `STR + weapon bonus` damage. A character spending a Force Point doubles their Strength dice (not the weapon bonus) for damage.

### Wound Levels

**Stunned**
- Suffer `−1D` to all skill and attribute rolls for the rest of the current round and the next round.
- After two rounds, the penalty lifts, but the character is still mildly shaken for about 30 minutes unless they rest for one minute.
- If a character accumulates stuns equal to the number before the "D" in their Strength, they are knocked **unconscious for 2D minutes**. A character can be revived with an Easy first aid roll.

**Wounded**
- Fall prone; no actions for the rest of the round.
- Suffer `−1D` to all skill and attribute rolls until healed.
- A second wound becomes **Wounded Twice** (`−2D` to all rolls).

**Wounded Twice**
- Fall prone; no actions for the rest of the round.
- Suffer `−2D` to all skill and attribute rolls until healed.
- A third wound becomes **Incapacitated**.

**Incapacitated**
- Fall prone and lose consciousness for `10D` minutes.
- Cannot take any actions until healed.
- A Moderate first aid roll can revive the character, who is groggy and can only move at half their cautious rate.
- Taking additional damage becomes **Mortally Wounded**.

**Mortally Wounded**
- Fall prone and lose consciousness.
- At the end of each round, roll `2D`. If the result is **less than the number of rounds the character has been mortally wounded**, the character **dies**.
- A Moderate first aid roll can **stabilize** the character. They remain mortally wounded but will survive if treated within one hour.
- Taking additional damage while mortally wounded is **Killed**.

**Killed**
- The character is dead. Time to make a new character.

### Body Points (Optional)

An alternative damage track. Characters begin with **Strength roll + 20** Body Points.

Damage reduces Body Points by the difference between the damage roll and the character's damage resistance total. Wound levels are determined by remaining Body Points as a percentage of the total.

Example ranges (from the D6 Space bounty hunter template with 33 Body Points):

| Wound Level | Body Points Range |
|---|---|
| Stunned | 19–26 |
| Wounded | 13–18 |
| Severely Wounded | 6–12 |
| Incapacitated | 3–5 |
| Mortally Wounded | 1–2 |
| Dead | 0 |

The GM may use Wounds only, Body Points only, or both.

### Stun Damage

Weapons set to **stun** roll damage normally, but any result more severe than Stunned is treated as **unconscious for 2D minutes** instead of applying the worse wound level.

### Damage Options

**Severe Injuries:** A character who deals enough damage to kill an opponent may instead choose to inflict a serious permanent injury (severed limb, major disability). In addition, the target is Wounded, Wounded Twice, or Incapacitated (GM's choice).

**Massive Damage:** If a character suffers two wound levels in a single round, they can only defend or flee for the next two rounds (unless they make an Easy *stamina* or *willpower* roll as an action).

**Miscellaneous Damage (no attack roll needed):**

| Hazard | Damage |
|---|---|
| Falling 3–6 m | `2D` |
| Falling 7–12 m | `3D` |
| Falling 13–18 m | `4D` |
| Falling 19–30 m | `5D` |
| Falling 31–50 m | `7D` |
| Falling 51+ m | `9D` |
| Fire (torch-size) | `1D` per round |
| Electricity (wall outlet) | `1D` |
| Electricity (major power line) | `9D` |
| General poison (fatal dose) | `8D+2` |

---

## Healing

### Natural Healing

A character heals by resting. After the required rest period, the character rolls their **full Strength** and consults the table for their current wound level.

Characters who attempt to work or adventure during healing subtract `−1D` from their Strength roll. Characters who rest completely for twice the required period add `+1D` to their roll.

**Wounded** (rest 3 standard days, then roll):

| Strength Roll | Result |
|---|---|
| 2–4 | Worsens to Wounded Twice |
| 5–6 | Remains Wounded |
| 7+ | Fully healed |

**Wounded Twice** (rest 3 days, then roll):

| Strength Roll | Result |
|---|---|
| 2–4 | Worsens to Incapacitated |
| 5–6 | Remains Wounded Twice |
| 7+ | Improves to Wounded |

**Incapacitated** (rest 2 weeks, then roll):

| Strength Roll | Result |
|---|---|
| 2–6 | Worsens to Mortally Wounded |
| 7–8 | Remains Incapacitated |
| 9+ | Improves to Wounded Twice |

**Mortally Wounded** (rest 1 month / 35 days, then roll):

| Strength Roll | Result |
|---|---|
| 2–6 | Dies |
| 7–8 | Remains Mortally Wounded |
| 9+ | Improves to Incapacitated |

### Medpacs / First Aid

A standard medpac contains medicines, coagulants, and diagnostic hardware for battlefield treatment. A *first aid* (or *Technical*) roll is needed to use one.

| Degree of Injury | Difficulty |
|---|---|
| Stunned / Unconscious | Very Easy |
| Wounded / Wounded Twice | Easy |
| Incapacitated | Moderate |
| Mortally Wounded | Difficult |

**On success:** The patient heals **one wound level**. Unconscious characters are revived.

**On failure:** The character's condition is unchanged.

**Failure by more than 10:** No further medpacs may be used on this character for 24 hours.

Multiple medpacs may be used in a day, but each additional use **increases the difficulty by one level**. A character applying a medpac to themselves suffers an extra `−1D` penalty.

### Advanced Medical Care

**Bacta Tanks / Rejuvenation Tanks:** Require the advanced skill *(A) Medicine*. A Very Easy *(A) Medicine* roll allows the character to enter treatment. If successful, healing is guaranteed — it's just a matter of time.

| Wound Level | Treatment Time |
|---|---|
| Wounded | `1D` hours |
| Incapacitated | `4D` hours |
| Mortally Wounded | `1D` days |

Without *(A) Medicine*, a character must make a **Heroic** first aid or Technical roll to use the tank. Failure worsens the patient's condition by two levels.

**Surgery:** Required for major internal injuries or when no bacta tank is available. Requires *(A) Medicine*, a surgery kit, and a medical facility. A successful roll fully heals the patient (base difficulty: Easy, modified upward for field conditions and injury complexity). Healing time: `1D` days (Wounded), `3D` days (Incapacitated), `6D` days (Mortally Wounded). Failure worsens the patient two levels.

---

## Character Points and Force/Fate Points

### Character Points

**Character Points** represent a character pushing themselves beyond their normal limits — a subtle, largely unconscious connection to luck and will.

**Spending Character Points during play:**
- Declare after a roll but before anyone else takes an action.
- Spend one Character Point to roll **one additional die** and add it to the total. Keep spending for additional dice (up to the limits below).
- If the extra die shows a 6, add 6 and roll again. Keep rolling on 6s.
- Character Points and Force Points **cannot** be spent in the same round/scene.

**Limits on Character Points in a single roll:**
- Up to **2** to improve a skill or attribute roll
- Up to **2** to increase attack damage (may be considered evil in some settings)
- Up to **5** to improve a specialization roll
- Up to **5** on *acrobatics*, *dodge*, *melee parry*, *brawling parry*, lightsaber parries, or vehicle/starship dodge rolls
- Up to **5** to improve a Strength roll to resist damage
- A character **cannot** spend Character Points on another character's rolls

In scenes (non-combat), Character Points may be spent for a continuous action (the bonus ends as soon as the character switches to something else).

**Earning Character Points:** Characters receive Character Points at the end of each adventure. The GM awards them based on performance, creativity, heroism, and roleplay quality.

### Force Points / Fate Points

Force Points (called **Fate Points** in some OpenD6 settings) represent a character giving everything they have — skill, talent, and luck combined in a single extraordinary moment.

**Spending a Force/Fate Point:**
- Declare at the start of a round.
- All of the character's **skill, attribute, and special ability die codes are doubled** for the rest of that round.
- Weapon damage die codes, hull points, and other non-character die codes are **not** doubled.
- For melee weapons (damage = `STR + bonus`), double the Strength but not the weapon bonus.
- Character Points **cannot** be spent in the same round.

In scenes, a Force/Fate Point may be spent for one continuous action (bonus ends when the character does something else).

**Non-Force-sensitive (non-Fate-touched) characters:** Maximum of 5 Force/Fate Points.
**Force-sensitive / exceptional characters:** No maximum.

**Recovering Force/Fate Points:**
Spending a Force/Fate Point does not guarantee its return. The outcome depends on how it was used:

| How the Point Was Used | Result |
|---|---|
| For evil (killing innocents, gratuitous harm, using power in anger) | Point is lost permanently; character gains a **Dark Side Point** |
| For a mundane, selfish, or unheroic purpose | Point is lost permanently |
| For a genuinely heroic action | Point returns at end of adventure |
| For a heroic action at a dramatically appropriate moment (climax, vital turning point) | Point returns **and** character gains a new Point |
| No Points held — character acts heroically at the right moment | May earn one Point at adventure's end |

### Dark Side Points (Optional)

When a character commits an evil act — especially while spending a Force Point — they earn a **Dark Side Point**. As Dark Side Points accumulate, the character is increasingly drawn toward darkness, potentially becoming a villain or losing their heroic qualities.

The GM should warn a player before their character risks earning a Dark Side Point.

---

## Character Advancement

Characters improve between adventures by spending **Character Points**.

### Improving Skills

- **Cost:** Character Points equal to the number before the "D" in the current skill die code.
- **Limit:** A skill may only improve by **one pip** between adventures.
- A character may improve **multiple different skills** between adventures.
- Improving from `XD+2` to `(X+1)D` counts as one pip.

**Training Time:**
- If the character **used the skill** in the last adventure: no training required; spend the Character Points and the skill improves immediately.
- If the character did **not** use the skill: training is required.
  - With a teacher: 1 day per Character Point spent.
  - Without a teacher: 2 days per Character Point spent.
  - Each additional Character Point spent may reduce training time by 1 day (minimum: 1 day).

**Teachers:** A teacher must have a skill die code at least equal to what the student's skill will be **after** improvement. Teachers may demand payment, service, or favors.

**Specializations:** Cost = half the number before the "D" (rounded up). Training time rules are the same as for base skills.

### Learning New Skills

A character learns a new skill by paying Character Points to advance it **one pip above the governing attribute**.

- Training rules are the same as for improvement.
- The character is considered to have "used" the skill if they used the governing attribute for something that skill covers.

### Advanced Skills

- **Cost to improve:** 2 × the number before the "D".
- **Cost to learn (starting at 1D):** 2 Character Points.
- **Training Time (with teacher):** 1 week per Character Point spent.
- **Training Time (without teacher):** 2 weeks per Character Point spent.
- Reducing training time costs 1 additional Character Point per day cut (minimum: 1 week).
- The prerequisite skill must meet the required die code before the advanced skill can be learned.

### Improving Attributes

- **Cost:** The number before the "D" × 10.
- **Training Time (with teacher):** 1 week per Character Point spent.
- **Training Time (without teacher):** 2 weeks per Character Point spent.
- Reducing training time costs 1 additional Character Point per day cut (minimum: 1 week).
- When an attribute improves by one pip, **all skills under that attribute** (except advanced skills) also improve by one pip.

---

## Complications

A complication occurs when the Wild Die shows a **1** and the GM chooses to apply one. Complications make life more interesting — they are not necessarily punishments, but consequences that advance the story.

**Principles of good complications:**
- They should be **directly related** to the failed action.
- They should **challenge** characters without being unfair death traps.
- They should make players ask, "What do we do now?"
- They should occur **a few times per adventure**, most often at dramatic moments.
- They may be used to **balance powerful characters** or advance plot threads.

**Examples:**
- A character sneaking through a forest steps on a twig, alerting a patrol.
- A character successfully hacks a computer, but accidentally triggers an alarm.
- A character's weapon jams at a critical moment.
- A grenade lands short of its target.
- A character slips while moving through difficult terrain, twisting an ankle.
- A negotiation succeeds, but a rival overhears the deal.

---

## Gamemaster Tips

### Speeding Play

- Seat players in Perception order to move around the table quickly during combat.
- Occasionally reverse order (lowest Perception first) so the same player isn't always last.
- Use a count of three for hesitant players — if they haven't decided by three, their character hesitates and loses their action. (Be lenient with new players.)

### Roleplaying vs. Rules

- Reward creative roleplay and good plans with bonus modifiers.
- If players make poor tactical decisions, grant enemies corresponding bonuses.
- Use die rolls to **confirm** good roleplay, not to overrule it entirely.

### Interpreting Rolls

- A roll that **barely beats** the difficulty: marginal success with complications.
- A roll that **exceeds** the difficulty by 15+: spectacular, cinematic success.
- A roll that **barely misses**: near-miss, close call.
- A roll that **misses by 15+**: catastrophic failure, potential complications.

### Secret Checks

When you don't want to alert players that something is happening (detection, ambush, etc.):
- Pre-roll several die codes before the session.
- Use a pre-rolled result when a character's Perception or search is tested, without asking the player to roll.

### Mixing Scenes and Rounds

Don't play out every moment in rounds — it drains tension from climactic scenes. Instead:
- Use **scenes** to narrate travel and general movement.
- Shift to **rounds** for specific dramatic events: the door won't open, an enemy appears, a bomb is about to go off.
- Alternate freely to keep the pacing dynamic.

### Difficulty Numbers as Story Tools

You don't always have to reveal difficulty numbers to players. Describe difficulty in narrative terms:

- "This looks pretty tough."
- "You're confident you can handle this."
- "I don't know — this is going to be tricky."

Only reveal the number when tension or clarity demands it.

---

*This document is a fan-compiled reference for the OpenD6 system. OpenD6 mechanics are open and no copyright is asserted on the system mechanics. All setting-specific content remains the property of its respective rights holders. The REUP project is a fan work provided under Creative Commons for free exchange of information.*

---

## Sources

The rules and mechanics in this document were compiled and adapted from the following sources:

1. **Star Wars Roleplaying Game: Revised, Expanded and Updated (REUP)**
   - Design: The REUP Team
   - Previous Edition Designers: Greg Costikayn, Steven Crane, Greg Farshtey, Greg Gorden, Bill Smith, Peter Schweighofer, Bill Slavicsek, Ed Stark, George R. Strayton, Paul Sudlow, Eris S. Trautmann
   - Second Printing: February 2015
   - A fan work provided as a free exchange of information under a Creative Commons license. Based on the *Star Wars Roleplaying Game: Second Edition Revised and Expanded* by West End Games.

2. **D6 Space Rulebook** *(WEG 51012, Version 2.0)*
   - Design: Nikola Vrtis
   - Editor: Steven Marsh
   - Publisher: Eric Gibson / Purgatory Publishing Inc.
   - First Printing: June 2004
   - ISBN: 1-932867-01-5
   - © 2004 Purgatory Publishing Inc. West End Games, WEG, and D6 System are trademarks and properties of Purgatory Publishing Inc.

3. **D6 Fantasy Creatures**
   - Published under the West End Games / OpenD6 product line.
   - © Purgatory Publishing Inc. West End Games, WEG, and D6 System are trademarks and properties of Purgatory Publishing Inc.

4. **The D6 System** *(WEG 51005)*
   - Design & Development: George Strayton
   - Editing: Greg Farshtey
   - Cover Design & Graphics: Tom ONeill
   - Cover Art: Ron Kulp
   - Publisher: West End Games / Purgatory Publishing Inc.
   - First Published: 1996
   - ISBN: 0-87431-372-4
   - © 1996 West End Games. West End Games, WEG, and D6 System are trademarks and properties of Purgatory Publishing Inc.
   - This volume includes the **Open Game License v1.0a** (Copyright 2000, Wizards of the Coast, Inc.), under which the D6 System game mechanics are designated as Open Game Content.

---

### Open Game License Notice

This document is produced under the terms of the **Open Game License Version 1.0a** (Copyright 2000, Wizards of the Coast, Inc.).

**Open Game Content:** All game mechanics and materials compiled in this reference document are designated Open Game Content under the OGL, as originally designated in *The D6 System* (WEG 51005).

**Product Identity:** The D6 System name and trademark, the D6 logo, OpenD6 and related logos, and all cover and interior art from the source materials are Product Identity and properties of Purgatory Publishing Inc. These are not reproduced here. Use of the D6 System trademark is subject to the D6 System/OpenD6 System Trademark License (D6STL).

**COPYRIGHT NOTICE**
- Open Game License v1.0a — Copyright 2000, Wizards of the Coast, Inc.
- The D6 System (WEG 51005) — Copyright 1996, West End Games

> **Note:** Star Wars and all related properties are trademarks of Lucasfilm Ltd. and The Walt Disney Corporation. No challenge to any trademark or copyright is intended. This document is a fan reference compiled for community use.
