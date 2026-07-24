---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 5 Clarity
cost_amount: "5"
cost_resource: Clarity
distance: 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 3 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier2: 6 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
      tier3: 9 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
    - effect: The size of the [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst) increases by 1, and you are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) until the end of your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Strained
feature_type: ability
file_basename: gravitic-burst
file_dpath: feature/ability/talent/level-2
flavor: Everyone get away from me!
item_id: gravitic-burst
item_name: Gravitic Burst
keywords:
    - Area
    - Psionic
    - Telekinesis
level: "2"
name: Gravitic Burst
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-2/gravitic-burst
source: mcdm.heroes.v1
subclass: telekinesis
target: Each enemy in the area
tier1: 3 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
tier2: 6 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
tier3: 9 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
type: ability
---

```ds-feature
cost: 5 Clarity
distance: 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 3 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier2: 6 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
      tier3: 9 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
    - effect: The size of the [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst) increases by 1, and you are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) until the end of your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Strained
feature_type: ability
flavor: Everyone get away from me!
keywords:
    - Area
    - Psionic
    - Telekinesis
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: talent
    cost: 5 Clarity
    distance: 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effects:
        - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
          tier1: 3 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier2: 6 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
          tier3: 9 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
        - effect: The size of the [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst) increases by 1, and you are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) until the end of your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
          name: Strained
    flavor: Everyone get away from me!
    keywords:
        - Area
        - Psionic
        - Telekinesis
    level: "2"
    name: Gravitic Burst
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-2/gravitic-burst
    subclass: telekinesis
    target: Each enemy in the area
    tier1: 3 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    tier2: 6 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
    tier3: 9 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
    type: ability
name: Gravitic Burst
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
