---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: fury
cost: 3 Ferocity
cost_amount: "3"
cost_resource: Ferocity
distance: Self; see below
effects:
    - effect: You move up to your [speed](../../../../rule/character/speed.md) in a straight line, and enemy squares are not [difficult terrain](../../../../movement/difficult-terrain.md) for this movement. You can end this movement in a creature's space and move them to an [adjacent](../../../../rule/combat/adjacent.md) unoccupied space. You make one [power roll](../../../../rule/dice/power-roll.md) that targets each enemy whose space you move through.
      name: Effect
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 2 damage
      tier2: 3 damage
      tier3: 5 damage
    - effect: The last target you damage takes extra damage equal to your [Might](../../../../rule/character/might.md) score for each [opportunity attack](../../../../rule/combat/opportunity-attack.md) you trigger during your move.
      name: Effect
feature_type: ability
file_basename: tide-of-death
file_dpath: feature/ability/fury/level-1
flavor: Teach them the folly of lining up for you.
item_id: tide-of-death
item_name: Tide of Death
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
level: "1"
name: Tide of Death
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.fury.level-1/tide-of-death
source: mcdm.heroes.v1
target: Self
tier1: 2 damage
tier2: 3 damage
tier3: 5 damage
type: ability
---

```ds-feature
cost: 3 Ferocity
distance: Self; see below
effects:
    - effect: You move up to your [speed](../../../../rule/character/speed.md) in a straight line, and enemy squares are not [difficult terrain](../../../../movement/difficult-terrain.md) for this movement. You can end this movement in a creature's space and move them to an [adjacent](../../../../rule/combat/adjacent.md) unoccupied space. You make one [power roll](../../../../rule/dice/power-roll.md) that targets each enemy whose space you move through.
      name: Effect
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 2 damage
      tier2: 3 damage
      tier3: 5 damage
    - effect: The last target you damage takes extra damage equal to your [Might](../../../../rule/character/might.md) score for each [opportunity attack](../../../../rule/combat/opportunity-attack.md) you trigger during your move.
      name: Effect
feature_type: ability
flavor: Teach them the folly of lining up for you.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: fury
    cost: 3 Ferocity
    distance: Self; see below
    effects:
        - effect: You move up to your [speed](../../../../rule/character/speed.md) in a straight line, and enemy squares are not [difficult terrain](../../../../movement/difficult-terrain.md) for this movement. You can end this movement in a creature's space and move them to an [adjacent](../../../../rule/combat/adjacent.md) unoccupied space. You make one [power roll](../../../../rule/dice/power-roll.md) that targets each enemy whose space you move through.
          name: Effect
        - roll: Power Roll + [Might](../../../../rule/character/might.md)
          tier1: 2 damage
          tier2: 3 damage
          tier3: 5 damage
        - effect: The last target you damage takes extra damage equal to your [Might](../../../../rule/character/might.md) score for each [opportunity attack](../../../../rule/combat/opportunity-attack.md) you trigger during your move.
          name: Effect
    flavor: Teach them the folly of lining up for you.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - Weapon
    level: "1"
    name: Tide of Death
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/tide-of-death
    target: Self
    tier1: 2 damage
    tier2: 3 damage
    tier3: 5 damage
    type: ability
name: Tide of Death
target: Self
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
