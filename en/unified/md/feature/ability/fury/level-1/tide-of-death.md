---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 3 Ferocity
distance: Self; see below
effects:
    - effect: You move up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) in a straight line, and enemy squares are not [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for this movement. You can end this movement in a creature's space and move them to an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) unoccupied space. You make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each enemy whose space you move through.
      name: Effect
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 2 damage
      tier2: 3 damage
      tier3: 5 damage
    - effect: The last target you damage takes extra damage equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score for each [opportunity attack](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack) you trigger during your move.
      name: Effect
flavor: Teach them the folly of lining up for you.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
level: "1"
name: Tide of Death
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-1/tide-of-death
target: Self
tier1: 2 damage
tier2: 3 damage
tier3: 5 damage
type: ability
---


*Teach them the folly of lining up for you.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), Weapon**      | **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|------------------------|----------------:|
| **📏 Self; see below** |     **🎯 Self** |

**Effect:** You move up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) in a straight line, and enemy squares are not [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for this movement. You can end this movement in a creature's space and move them to an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) unoccupied space. You make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each enemy whose space you move through.

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 2 damage
- **12-16:** 3 damage
- **17+:** 5 damage

**Effect:** The last target you damage takes extra damage equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score for each [opportunity attack](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack) you trigger during your move.
