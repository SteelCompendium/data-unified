---
class: shadow
level: "1"
name: College Triggered Action
scc: mcdm.heroes.v1/feature.shadow.level-1/college-triggered-action
type: feature
---

Your [shadow college](shadow-college.md) grants you a [triggered action](../../../rule/combat/triggered-action.md), as shown on the College [Triggered Actions](../../../rule/combat/triggered-action.md) table.

### College Triggered Actions Table

| College         | [Triggered Action](../../../rule/combat/triggered-action.md)      |
|-----------------|-----------------------|
| Black Ash       | [In All This Confusion](../../ability/shadow/level-1/in-all-this-confusion.md) |
| Caustic Alchemy | [Defensive Roll](../../ability/shadow/level-1/defensive-roll.md)        |
| Harlequin Mask  | [Clever Trick](../../ability/shadow/level-1/clever-trick.md)          |

### Clever Trick {data-scc="mcdm.heroes.v1/feature.ability.shadow.level-1/clever-trick" data-cost="1 Insight" data-subclass="harlequin-mask"}


*You sow a moment of confusion in combat, to your enemy's peril.*

| **Magic**   | **Triggered** |
|-------------|--------------:|
| **📏 Self** |     **🎯 Self** |

**Trigger:** An enemy targets you with a [strike](../../../rule/combat/strike.md).

**Effect:** Choose an enemy within [distance](../../../rule/combat/distance.md) of the triggering strike, including the enemy who targeted you. The [strike](../../../rule/combat/strike.md) targets that enemy instead.

### Defensive Roll {data-scc="mcdm.heroes.v1/feature.ability.shadow.level-1/defensive-roll" data-subclass="caustic-alchemy"}


*When an enemy attacks, you roll with the impact to reduce the harm.*

| **-**       | **Triggered** |
|-------------|--------------:|
| **📏 Self** |   **🎯 Self** |

**Trigger:** Another creature damages you.

**Effect:** You take half the triggering damage, then can [shift](../../../movement/shifting.md) up to 2 squares after the triggering effect resolves. If you end this [shift](../../../movement/shifting.md) with [concealment](../../../rule/combat/concealment.md) or [cover](../../../rule/combat/cover.md), you can use the [Hide](../../common/maneuvers/hide.md) maneuver even if you are observed.

**Spend 1 Insight:** The [potency](../../../rule/character/potency.md) of any effects associated with the damage are reduced by 1 for you.

### In All This Confusion {data-scc="mcdm.heroes.v1/feature.ability.shadow.level-1/in-all-this-confusion" data-subclass="black-ash"}


*You vanish in a plume of black smoke to avoid danger.*

| **Magic**   | **Triggered** |
|-------------|--------------:|
| **📏 Self** |     **🎯 Self** |

**Trigger:** You take damage.

**Effect:** You take half the damage, then can [teleport](../../../movement/teleport.md) up to 4 squares after the triggering effect resolves.

**Spend 1+ Insight:** You [teleport](../../../movement/teleport.md) 1 additional square for each insight spent.
