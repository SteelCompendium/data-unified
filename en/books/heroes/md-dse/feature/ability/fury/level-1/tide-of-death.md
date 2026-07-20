---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 3 Ferocity
cost_amount: "3"
cost_resource: Ferocity
distance: Self; see below
effect: You move up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) in a straight line, and enemy squares are not [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for this movement. You can end this movement in a creature's space and move them to an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) unoccupied space. You make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each enemy whose space you move through.
feature_type: ability
file_basename: tide-of-death
file_dpath: feature/ability/fury/level-1
flavor: Teach them the folly of lining up for you.
item_id: tide-of-death
item_name: Tide of Death
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
level: "1"
name: Tide of Death
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
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
    - effect: You move up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) in a straight line, and enemy squares are not [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for this movement. You can end this movement in a creature's space and move them to an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) unoccupied space. You make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each enemy whose space you move through.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 2 damage
      tier2: 3 damage
      tier3: 5 damage
feature_type: ability
flavor: Teach them the folly of lining up for you.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: fury
    cost: 3 Ferocity
    distance: Self; see below
    effect: You move up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) in a straight line, and enemy squares are not [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for this movement. You can end this movement in a creature's space and move them to an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) unoccupied space. You make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each enemy whose space you move through.
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
name: Tide of Death
target: Self
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
