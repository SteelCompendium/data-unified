---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 11 Piety
cost_amount: "11"
cost_resource: Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: You conjure a [size](scc.v1:mcdm.heroes.v1/rule.character/size) 4 dragon that appears in an unoccupied space within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). The dragon has [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) 6 and can [fly](scc.v1:mcdm.heroes.v1/movement/fly), [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) 4, 100 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), immunity all to fire damage, and uses your [characteristics](scc.v1:mcdm.heroes.v1/rule.character/characteristic). The dragon disappears at the end of the encounter, if their [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) drops to 0, or if you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying).
      name: Effect
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 5 fire damage
      tier2: 9 fire damage
      tier3: 12 fire damage
feature_type: ability
file_basename: divine-dragon
file_dpath: feature/ability/conduit/level-9
flavor: From nothing but divine will, you create a powerful ally.
item_id: divine-dragon
item_name: Divine Dragon
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "9"
name: Divine Dragon
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-9/divine-dragon
source: mcdm.heroes.v1
subclass: creation
target: Special
tier1: 5 fire damage
tier2: 9 fire damage
tier3: 12 fire damage
type: ability
---

```ds-feature
cost: 11 Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: You conjure a [size](scc.v1:mcdm.heroes.v1/rule.character/size) 4 dragon that appears in an unoccupied space within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). The dragon has [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) 6 and can [fly](scc.v1:mcdm.heroes.v1/movement/fly), [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) 4, 100 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), immunity all to fire damage, and uses your [characteristics](scc.v1:mcdm.heroes.v1/rule.character/characteristic). The dragon disappears at the end of the encounter, if their [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) drops to 0, or if you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying).
      name: Effect
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 5 fire damage
      tier2: 9 fire damage
      tier3: 12 fire damage
feature_type: ability
flavor: From nothing but divine will, you create a powerful ally.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    cost: 11 Piety
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - effect: You conjure a [size](scc.v1:mcdm.heroes.v1/rule.character/size) 4 dragon that appears in an unoccupied space within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). The dragon has [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) 6 and can [fly](scc.v1:mcdm.heroes.v1/movement/fly), [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) 4, 100 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), immunity all to fire damage, and uses your [characteristics](scc.v1:mcdm.heroes.v1/rule.character/characteristic). The dragon disappears at the end of the encounter, if their [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) drops to 0, or if you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying).
          name: Effect
        - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
          tier1: 5 fire damage
          tier2: 9 fire damage
          tier3: 12 fire damage
    flavor: From nothing but divine will, you create a powerful ally.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "9"
    name: Divine Dragon
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-9/divine-dragon
    subclass: creation
    target: Special
    tier1: 5 fire damage
    tier2: 9 fire damage
    tier3: 12 fire damage
    type: ability
name: Divine Dragon
target: Special
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
