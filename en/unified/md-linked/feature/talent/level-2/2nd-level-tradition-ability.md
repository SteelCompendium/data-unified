---
class: talent
level: "2"
name: 2nd-Level Tradition Ability
scc: mcdm.heroes.v1/feature.talent.level-2/2nd-level-tradition-ability
type: feature
---

Your [talent tradition](../level-1/talent-tradition.md) grants your choice of one of two [heroic abilities](../../../rule/general/heroic-ability.md).

## 2nd-Level Chronopathy Ability

Choose one of the following abilities.

### Applied Chronometrics {data-scc="mcdm.heroes.v1/feature.ability.talent.level-2/applied-chronometrics" data-cost="5 Clarity" data-subclass="chronopathy"}


*Time slows down around you. Your heartbeat is the only gauge of the extra moments you've gained.*

| **Chronopathy, Psionic, [Ranged](../../../rule/combat/ranged.md)** |   **[Maneuver](../../../rule/combat/turn.md)** |
|----------------------------------|---------------:|
| **📏 [Ranged](../../../rule/combat/ranged.md) 10**                 | **🎯 Special** |

**[Power Roll](../../../rule/dice/power-roll.md) + [Presence](../../../rule/character/presence.md):**

- **≤11:** You target two creatures, one of which can be you.
- **12-16:** You target three creatures, one of which can be you.
- **17+:** You target four creatures, one of which can be you.

**Effect:** Until the start of your next [turn](../../../rule/combat/turn.md), each target gains a +5 [bonus](../../../rule/dice/bonuses-and-penalties.md) to [speed](../../../rule/character/speed.md), they can't be made [dazed](../../../condition/dazed.md), and they can use an additional maneuver on their [turn](../../../rule/combat/turn.md). If a target is already [dazed](../../../condition/dazed.md), that [condition](../../../rule/combat/condition.md) ends for them.

**Strained:** Your [speed](../../../rule/character/speed.md) is halved until the end of the encounter.

### Slow {data-scc="mcdm.heroes.v1/feature.ability.talent.level-2/slow" data-cost="5 Clarity" data-subclass="chronopathy"}


*Perhaps they wonder why everyone else is moving so quickly?*

| **Chronopathy, Psionic, [Ranged](../../../rule/combat/ranged.md)** |                      **[Maneuver](../../../rule/combat/turn.md)** |
|----------------------------------|----------------------------------:|
| **📏 [Ranged](../../../rule/combat/ranged.md) 10**                 | **🎯 Three creatures or objects** |

**[Power Roll](../../../rule/dice/power-roll.md) + [Presence](../../../rule/character/presence.md):**

- **≤11:** The target's [speed](../../../rule/character/speed.md) is halved (save ends), or if P < WEAK, the target is [slowed](../../../condition/slowed.md) (save ends).
- **12-16:** The target is [slowed](../../../condition/slowed.md) (save ends), or if P < AVERAGE, the target's [speed](../../../rule/character/speed.md) is 0 (save ends).
- **17+:** The target is [slowed](../../../condition/slowed.md) (save ends), or if P < STRONG, the target's [speed](../../../rule/character/speed.md) is 0 (save ends).

**Effect:** A target can't use [triggered actions](../../../rule/combat/triggered-action.md) while their [speed](../../../rule/character/speed.md) is reduced this way.

**Strained:** The [potency](../../../rule/character/potency.md) of this ability increases by 1 and you take 1d6 damage. At the start of each [combat round](../../../rule/combat/combat-round.md) while any target is affected by this ability, you take 1d6 damage. You can end the effect on all affected targets at any time (no action required).

## 2nd-Level Telekinesis Ability

Choose one of the following abilities.

### Gravitic Burst {data-scc="mcdm.heroes.v1/feature.ability.talent.level-2/gravitic-burst" data-cost="5 Clarity" data-subclass="telekinesis"}


*Everyone get away from me!*

| **Area, Psionic, Telekinesis** |               **[Main action](../../../rule/combat/turn.md)** |
|--------------------------------|------------------------------:|
| **📏 1 [burst](../../../rule/combat/burst.md)**                 | **🎯 Each enemy in the area** |

**[Power Roll](../../../rule/dice/power-roll.md) + [Reason](../../../rule/character/reason.md):**

- **≤11:** 3 damage; vertical [push](../../../movement/forced-movement.md) 2
- **12-16:** 6 damage; vertical [push](../../../movement/forced-movement.md) 4
- **17+:** 9 damage; vertical [push](../../../movement/forced-movement.md) 6

**Strained:** The size of the [burst](../../../rule/combat/burst.md) increases by 1, and you are [weakened](../../../condition/weakened.md) until the end of your [turn](../../../rule/combat/turn.md).

### Levity and Gravity {data-scc="mcdm.heroes.v1/feature.ability.talent.level-2/levity-and-gravity" data-cost="5 Clarity" data-subclass="telekinesis"}


*You raise the target slightly into the air, then smother them against the ground.*

| **Psionic, [Ranged](../../../rule/combat/ranged.md), [Strike](../../../rule/combat/strike.md), Telekinesis** |               **[Main action](../../../rule/combat/turn.md)** |
|------------------------------------------|------------------------------:|
| **📏 [Ranged](../../../rule/combat/ranged.md) 10**                         | **🎯 One creature or object** |

**[Power Roll](../../../rule/dice/power-roll.md) + [Reason](../../../rule/character/reason.md):**

- **≤11:** 6 + R damage; M < WEAK[, prone](../../../condition/prone.md)
- **12-16:** 10 + R damage; M < AVERAGE[, prone](../../../condition/prone.md)
- **17+:** 14 + R damage; M < STRONG, [prone and](../../../condition/prone.md) can't stand (save ends)

**Strained:** You take half the damage the target takes.

## 2nd-Level Telepathy Ability

Choose one of the following abilities.

### Overwhelm {data-scc="mcdm.heroes.v1/feature.ability.talent.level-2/overwhelm" data-cost="5 Clarity" data-subclass="telepathy"}


*You overload their senses, turning all their subconscious thoughts into conscious ones.*

| **Psionic, [Ranged](../../../rule/combat/ranged.md), [Strike](../../../rule/combat/strike.md), Telepathy** |     **[Main action](../../../rule/combat/turn.md)** |
|----------------------------------------|--------------------:|
| **📏 [Ranged](../../../rule/combat/ranged.md) 10**                       | **🎯 One creature** |

**[Power Roll](../../../rule/dice/power-roll.md) + [Reason](../../../rule/character/reason.md):**

- **≤11:** 6 + R psychic damage; I < WEAK, [slowed](../../../condition/slowed.md) (save ends)
- **12-16:** 10 + R psychic damage; I < AVERAGE, [weakened](../../../condition/weakened.md) (save ends)
- **17+:** 14 + R psychic damage; I < STRONG, [dazed](../../../condition/dazed.md) (save ends)

**Strained:** You start crying, and you can't use [triggered actions](../../../rule/combat/triggered-action.md) or make [free strikes](../../common/main-actions/free-strike.md) until the end of the target's next [turn](../../../rule/combat/turn.md).

### Synaptic Override {data-scc="mcdm.heroes.v1/feature.ability.talent.level-2/synaptic-override" data-cost="5 Clarity" data-subclass="telepathy"}


*You control an enemy's nervous system. How pleasant for them.*

| **Psionic, [Ranged](../../../rule/combat/ranged.md), Telepathy** |  **[Main action](../../../rule/combat/turn.md)** |
|--------------------------------|-----------------:|
| **📏 [Ranged](../../../rule/combat/ranged.md) 10**               | **🎯 One enemy** |

**[Power Roll](../../../rule/dice/power-roll.md) + [Reason](../../../rule/character/reason.md):**

- **≤11:** The target makes a [free strike](../../common/main-actions/free-strike.md) against one enemy of your choice.
- **12-16:** The target shifts up to their [speed](../../../rule/character/speed.md) and uses their [signature ability](../../../rule/combat/signature-ability.md) against any enemies of your choice.
- **17+:** The target moves up to their [speed](../../../rule/character/speed.md) and uses their [signature ability](../../../rule/combat/signature-ability.md) against any enemies of your choice.

**Effect:** You control the target's movement. The target can't be moved in a way that would harm them (such as over a cliff), leave them [dying](../../../rule/health/dying.md), or result in them suffering a [condition](../../../rule/combat/condition.md) or other negative effect. However, you can move them to provoke [opportunity attacks](../../../rule/combat/opportunity-attack.md).

**Strained:** You take 1d6 damage and are [weakened](../../../condition/weakened.md) until the end of your [turn](../../../rule/combat/turn.md).
