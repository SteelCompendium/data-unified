---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: Self; see below
effects:
    - effect: You move up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) in a straight line. During this movement, you can move through mundane structures, including walls, which are [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for you. You automatically destroy each square of structure you move through and leave behind a square of [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).
      name: Effect
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1'
      tier2: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2'
      tier3: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3'
feature_type: ability
file_basename: wrecking-ball
file_dpath: feature/ability/fury/level-2
flavor: It's easier to destroy than to create. Much easier, in fact!
item_id: wrecking-ball
item_name: Wrecking Ball
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
level: "2"
name: Wrecking Ball
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-2/wrecking-ball
source: mcdm.heroes.v1
target: Self
tier1: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1'
tier2: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2'
tier3: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3'
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: Self; see below
effects:
    - effect: You move up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) in a straight line. During this movement, you can move through mundane structures, including walls, which are [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for you. You automatically destroy each square of structure you move through and leave behind a square of [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).
      name: Effect
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1'
      tier2: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2'
      tier3: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3'
feature_type: ability
flavor: It's easier to destroy than to create. Much easier, in fact!
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: fury
    cost: 5 Ferocity
    distance: Self; see below
    effects:
        - effect: You move up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) in a straight line. During this movement, you can move through mundane structures, including walls, which are [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for you. You automatically destroy each square of structure you move through and leave behind a square of [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).
          name: Effect
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1'
          tier2: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2'
          tier3: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3'
    flavor: It's easier to destroy than to create. Much easier, in fact!
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Weapon
    level: "2"
    name: Wrecking Ball
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-2/wrecking-ball
    target: Self
    tier1: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1'
    tier2: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2'
    tier3: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3'
    type: ability
name: Wrecking Ball
target: Self
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
