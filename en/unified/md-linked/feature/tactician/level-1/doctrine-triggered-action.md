---
class: tactician
level: "1"
name: Doctrine Triggered Action
scc: mcdm.heroes.v1/feature.tactician.level-1/doctrine-triggered-action
type: feature
---

Your [tactical doctrine](tactical-doctrine.md) grants you a [triggered action](../../../rule/combat/triggered-action.md), as shown on the Doctrine [Triggered Actions](../../../rule/combat/triggered-action.md) table.

### Doctrine Triggered Actions Table

| Doctrine   | [Triggered Action](../../../rule/combat/triggered-action.md) |
|------------|------------------|
| Insurgent  | [Advanced Tactics](../../ability/tactician/level-1/advanced-tactics.md) |
| Mastermind | [Overwatch](../../ability/tactician/level-1/overwatch.md)        |
| Vanguard   | [Parry](../../ability/tactician/level-1/parry.md)            |

### Advanced Tactics {data-scc="mcdm.heroes.v1/feature.ability.tactician.level-1/advanced-tactics" data-subclass="insurgent"}


*Your leadership aids an ally.*

| **[Ranged](../../../rule/combat/ranged.md)**       |   **[Triggered](../../../rule/combat/triggered-action.md)** |
|------------------|----------------:|
| **📏 [Ranged](../../../rule/combat/ranged.md) 10** | **🎯 One ally** |

**Trigger:** The target deals damage to another creature.

**Effect:** The target gains 2 [surges](../../../rule/resource/surge.md), which they can use on the triggering damage.

**Spend 1 Focus:** If the damage has any [potency](../../../rule/character/potency.md) effect associated with it, the [potency](../../../rule/character/potency.md) is increased by 1.

### Overwatch {data-scc="mcdm.heroes.v1/feature.ability.tactician.level-1/overwatch" data-subclass="mastermind"}


*Under your direction, an ally waits for just the right moment to strike.*

| **[Ranged](../../../rule/combat/ranged.md)**       |       **[Triggered](../../../rule/combat/triggered-action.md)** |
|------------------|--------------------:|
| **📏 [Ranged](../../../rule/combat/ranged.md) 10** | **🎯 One creature** |

**Trigger:** The target moves.

**Effect:** At any time during the target's movement, one ally can make a [free strike](../../common/main-actions/free-strike.md) against them.

**Spend 1 Focus:** If the target has R < AVERAGE, they are [slowed](../../../condition/slowed.md) ([EoT](../../../rule/combat/end-of-turn.md)).

### Parry {data-scc="mcdm.heroes.v1/feature.ability.tactician.level-1/parry" data-subclass="vanguard"}


*Your quick reflexes cost an enemy the precision they seek.*

| **[Melee](../../../rule/combat/melee.md), Weapon** |            **[Triggered](../../../rule/combat/triggered-action.md)** |
|-------------------|-------------------------:|
| **📏 [Melee](../../../rule/combat/melee.md) 2**    |  **🎯 Self or one ally** |

**Trigger:** A creature deals damage to the target.

**Effect:** You can [shift](../../../movement/shifting.md) 1 square. If the target is you, or if you end this [shift](../../../movement/shifting.md) [adjacent](../../../rule/combat/adjacent.md) to the target, the target takes half the damage. If the damage has any [potency](../../../rule/character/potency.md) effect associated with it, the [potency](../../../rule/character/potency.md) is decreased by 1.

**Spend 1 Focus:** This ability's [distance](../../../rule/combat/distance.md) becomes [Melee](../../../rule/combat/melee.md) 1 + your [Reason](../../../rule/character/reason.md) score, and you can [shift](../../../movement/shifting.md) up to a number of squares equal to your [Reason](../../../rule/character/reason.md) score instead of 1 square.
