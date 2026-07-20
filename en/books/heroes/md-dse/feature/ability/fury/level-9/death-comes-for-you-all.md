---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effect: If this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) causes a target to be hurled through an object, that target takes an extra 10 damage.
feature_type: ability
file_basename: death-comes-for-you-all
file_dpath: feature/ability/fury/level-9
flavor: You use your weapon to create a destructive shockwave.
item_id: death-comes-for-you-all
item_name: Death Comes for You All!
keywords:
    - Area
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
level: "9"
name: Death Comes for You All!
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-9/death-comes-for-you-all
source: mcdm.heroes.v1
subclass: berserker
target: Each enemy in the area
tier1: 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier2: 10 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
tier3: 15 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: If this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) causes a target to be hurled through an object, that target takes an extra 10 damage.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier2: 10 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
      tier3: 15 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
feature_type: ability
flavor: You use your weapon to create a destructive shockwave.
keywords:
    - Area
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: fury
    cost: 11 Ferocity
    distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effect: If this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) causes a target to be hurled through an object, that target takes an extra 10 damage.
    flavor: You use your weapon to create a destructive shockwave.
    keywords:
        - Area
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Weapon
    level: "9"
    name: Death Comes for You All!
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-9/death-comes-for-you-all
    subclass: berserker
    target: Each enemy in the area
    tier1: 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    tier2: 10 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
    tier3: 15 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
    type: ability
name: Death Comes for You All!
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
