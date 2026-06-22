---
class: tactician
level: "2"
name: 2nd-Level Doctrine Ability
scc: mcdm.heroes.v1/feature.tactician.level-2/2nd-level-doctrine-ability
type: feature
---

Your [tactical doctrine](../level-1/tactical-doctrine.md) grants your choice of one of two [heroic abilities](../../../rule/general/heroic-ability.md).

## 2nd-Level Insurgent Ability

Choose one of the following abilities.

### Fog of War {data-scc="mcdm.heroes.v1/feature.ability.tactician.level-2/fog-of-war" data-cost="5 Focus" data-subclass="insurgent"}


*Your unorthodox strategy causes enemies to lash out in fear, heedless of who they might be attacking.*

| **[Ranged](../../../rule/combat/ranged.md)**       |         **Maneuver** |
|------------------|---------------------:|
| **📏 [Ranged](../../../rule/combat/ranged.md) 10** | **🎯 Two creatures** |

**Effect:** Each target is marked by you, and must immediately make a [free strike](../../common/main-actions/free-strike.md) against a creature of your choice within 5 squares of them.

**Mark Benefit:** Until the end of the encounter, whenever you or any ally makes a [strike](../../../rule/combat/strike.md) against a creature marked by you, you can spend 2 focus to force that target to make a [free strike](../../common/main-actions/free-strike.md) against a creature of your choice within 5 squares of them.

### Try Me Instead {data-scc="mcdm.heroes.v1/feature.ability.tactician.level-2/try-me-instead" data-cost="5 Focus" data-subclass="insurgent"}


*"Try picking on someone my [size](../../../rule/character/size.md)."*

| **[Melee](../../../rule/combat/melee.md), [Strike](../../../rule/combat/strike.md), Weapon** | **Main action** |
|---------------------------|----------------:|
| **📏 Self; see below**    |     **🎯 Self** |

**Effect:** You [shift](../../../movement/shifting.md) up to your [speed](../../../rule/character/speed.md) directly toward an ally, ending [adjacent](../../../rule/combat/adjacent.md) to them, then swapping locations with that ally as long as you can fit into each other's spaces. The ally can spend a [Recovery](../../../rule/health/recoveries.md), and you can make the following weapon [strike](../../../rule/combat/strike.md) with a [distance](../../../rule/combat/distance.md) of [melee](../../../rule/combat/melee.md) 1 against a creature.

**[Power Roll](../../../rule/dice/power-roll.md) + [Reason](../../../rule/character/reason.md):**

- **≤11:** 2 + R damage; R < WEAK, [frightened](../../../condition/frightened.md) (save ends)
- **12-16:** 3 + R damage; R < AVERAGE, [frightened](../../../condition/frightened.md) (save ends)
- **17+:** 4 + R damage; R < STRONG, [frightened](../../../condition/frightened.md) (save ends)

## 2nd-Level Mastermind Ability

Choose one of the following abilities.

### I've Got Your Back {data-scc="mcdm.heroes.v1/feature.ability.tactician.level-2/ive-got-your-back" data-cost="5 Focus" data-subclass="mastermind"}


*Your enemy will think twice about attacking your friend.*

| **[Ranged](../../../rule/combat/ranged.md), [Strike](../../../rule/combat/strike.md), Weapon** |     **Main action** |
|----------------------------|--------------------:|
| **📏 [Ranged](../../../rule/combat/ranged.md) 5**            | **🎯 One creature** |

**[Power Roll](../../../rule/dice/power-roll.md) + [Reason](../../../rule/character/reason.md):**

- **≤11:** 5 + R damage; [taunted](../../../condition/taunted.md) ([EoT](../../../rule/combat/end-of-turn.md))
- **12-16:** 9 + R damage; [taunted](../../../condition/taunted.md) ([EoT](../../../rule/combat/end-of-turn.md))
- **17+:** 12 + R damage; [taunted](../../../condition/taunted.md) ([EoT](../../../rule/combat/end-of-turn.md))

**Effect:** One ally [adjacent](../../../rule/combat/adjacent.md) to the target can spend a [Recovery](../../../rule/health/recoveries.md).

### Targets of Opportunity {data-scc="mcdm.heroes.v1/feature.ability.tactician.level-2/targets-of-opportunity" data-cost="5 Focus" data-subclass="mastermind"}


*You point out easy targets to your friends, allowing them to include more enemies in their attacks.*

| **[Ranged](../../../rule/combat/ranged.md)**      |         **Maneuver** |
|-----------------|---------------------:|
| **📏 [Ranged](../../../rule/combat/ranged.md) 5** | **🎯 Two creatures** |

**Effect:** Each target is marked by you, and you gain two [surges](../../../rule/resource/surge.md).

**Mark Benefit:** Until the end of the encounter, whenever you or any ally makes a [strike](../../../rule/combat/strike.md) against a creature marked by you, you can spend 2 focus to add one additional target to the [strike](../../../rule/combat/strike.md).

## 2nd-Level Vanguard Ability

Choose one of the following abilities.

### No Dying on My Watch {data-scc="mcdm.heroes.v1/feature.ability.tactician.level-2/no-dying-on-my-watch" data-cost="5 Focus" data-subclass="vanguard"}


*You prioritize saving an ally over your own safety.*

| **[Ranged](../../../rule/combat/ranged.md), [Strike](../../../rule/combat/strike.md), Weapon** |    **Triggered** |
|----------------------------|-----------------:|
| **📏 [Ranged](../../../rule/combat/ranged.md) 5**            | **🎯 One enemy** |

**Trigger:** The target deals damage to an ally.

**Effect:** You move up to your [speed](../../../rule/character/speed.md) toward the triggering ally, ending this movement [adjacent](../../../rule/combat/adjacent.md) to them or in the nearest square if you can't reach an [adjacent](../../../rule/combat/adjacent.md) square. The triggering ally can spend a [Recovery](../../../rule/health/recoveries.md) and gains 5 [temporary Stamina](../../../rule/health/temporary-stamina.md) for each enemy you came [adjacent](../../../rule/combat/adjacent.md) to during the move. You then make a [power roll](../../../rule/dice/power-roll.md) against the target.

**[Power Roll](../../../rule/dice/power-roll.md) + [Might](../../../rule/character/might.md):**

- **≤11:** R < WEAK, the target is [frightened](../../../condition/frightened.md) of the triggering ally (save ends)
- **12-16:** R < AVERAGE, the target is [frightened](../../../condition/frightened.md) of the triggering ally (save ends)
- **17+:** R < STRONG, the target is [frightened](../../../condition/frightened.md) of the triggering ally (save ends)

### Squad! On Me! {data-scc="mcdm.heroes.v1/feature.ability.tactician.level-2/squad-on-me" data-cost="5 Focus" data-subclass="vanguard"}


*Together we are invincible!*

| **Area**       |                          **Maneuver** |
|----------------|--------------------------------------:|
| **📏 1 [burst](../../../rule/combat/burst.md)** | **🎯 Self and each ally in the area** |

**Effect:** Until the start of your next [turn](../../../rule/combat/turn.md), each target has a [bonus](../../../rule/dice/bonuses-and-penalties.md) to [stability](../../../rule/character/stability.md) equal to your [Might](../../../rule/character/might.md) score. Additionally, each target gains 2 [surges](../../../rule/resource/surge.md).
