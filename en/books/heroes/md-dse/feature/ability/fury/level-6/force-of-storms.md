---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 7 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier2: 11 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
      tier3: 16 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
    - effect: When the target ends this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement), each creature within 2 squares of the target is [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3 squares.
      name: Effect
feature_type: ability
file_basename: force-of-storms
file_dpath: feature/ability/fury/level-6
flavor: You strike an enemy hard enough to be a projectile that knocks a crowd of creatures around.
item_id: force-of-storms
item_name: Force of Storms
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "6"
name: Force of Storms
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-6/force-of-storms
source: mcdm.heroes.v1
subclass: berserker
target: One creature
tier1: 7 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier2: 11 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
tier3: 16 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 7 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier2: 11 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
      tier3: 16 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
    - effect: When the target ends this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement), each creature within 2 squares of the target is [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3 squares.
      name: Effect
feature_type: ability
flavor: You strike an enemy hard enough to be a projectile that knocks a crowd of creatures around.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: fury
    cost: 9 Ferocity
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: 7 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
          tier2: 11 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
          tier3: 16 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
        - effect: When the target ends this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement), each creature within 2 squares of the target is [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3 squares.
          name: Effect
    flavor: You strike an enemy hard enough to be a projectile that knocks a crowd of creatures around.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "6"
    name: Force of Storms
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-6/force-of-storms
    subclass: berserker
    target: One creature
    tier1: 7 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    tier2: 11 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
    tier3: 16 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
    type: ability
name: Force of Storms
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
