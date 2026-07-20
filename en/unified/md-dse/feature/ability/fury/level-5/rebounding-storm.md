---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: When a target would end this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) by colliding with a creature or object, they take damage as usual, then are [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) the remaining [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) away from the creature or object in the direction they came from. As long as [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) remains, this effect continues if the target collides with another creature or object.
feature_type: ability
file_basename: rebounding-storm
file_dpath: feature/ability/fury/level-5
flavor: You knock around enemies like playthings.
item_id: rebounding-storm
item_name: Rebounding Storm
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "5"
name: Rebounding Storm
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-5/rebounding-storm
source: mcdm.heroes.v1
target: Two creatures or objects
tier1: 9 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier2: 14 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
tier3: 19 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: When a target would end this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) by colliding with a creature or object, they take damage as usual, then are [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) the remaining [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) away from the creature or object in the direction they came from. As long as [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) remains, this effect continues if the target collides with another creature or object.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 9 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier2: 14 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
      tier3: 19 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
feature_type: ability
flavor: You knock around enemies like playthings.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: fury
    cost: 9 Ferocity
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: When a target would end this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) by colliding with a creature or object, they take damage as usual, then are [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) the remaining [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) away from the creature or object in the direction they came from. As long as [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) remains, this effect continues if the target collides with another creature or object.
    flavor: You knock around enemies like playthings.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "5"
    name: Rebounding Storm
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-5/rebounding-storm
    target: Two creatures or objects
    tier1: 9 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    tier2: 14 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
    tier3: 19 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
    type: ability
name: Rebounding Storm
target: Two creatures or objects
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
