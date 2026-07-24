---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 11 Clarity
cost_amount: "11"
cost_resource: Clarity
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 6 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
      tier2: 9 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10
      tier3: 13 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 15
    - effect: On a [critical hit](scc.v1:mcdm.heroes.v1/rule.combat/critical-hit), the size of the area increases by 3, and this ability deals an extra 10 damage.
      name: Effect
    - effect: You are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends). If you scored a [critical hit](scc.v1:mcdm.heroes.v1/rule.combat/critical-hit) with this ability, you die.
      name: Strained
feature_type: ability
file_basename: gravitic-nova
file_dpath: feature/ability/talent/level-9
flavor: Unbridled psionic energy erupts from your body and flashes outward, hurling your foes back.
item_id: gravitic-nova
item_name: Gravitic Nova
keywords:
    - Area
    - Psionic
    - Telekinesis
level: "9"
name: Gravitic Nova
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-9/gravitic-nova
source: mcdm.heroes.v1
subclass: telekinesis
target: Each enemy and object in the area
tier1: 6 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
tier2: 9 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10
tier3: 13 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 15
type: ability
---

```ds-feature
cost: 11 Clarity
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 6 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
      tier2: 9 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10
      tier3: 13 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 15
    - effect: On a [critical hit](scc.v1:mcdm.heroes.v1/rule.combat/critical-hit), the size of the area increases by 3, and this ability deals an extra 10 damage.
      name: Effect
    - effect: You are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends). If you scored a [critical hit](scc.v1:mcdm.heroes.v1/rule.combat/critical-hit) with this ability, you die.
      name: Strained
feature_type: ability
flavor: Unbridled psionic energy erupts from your body and flashes outward, hurling your foes back.
keywords:
    - Area
    - Psionic
    - Telekinesis
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: talent
    cost: 11 Clarity
    distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effects:
        - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
          tier1: 6 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
          tier2: 9 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10
          tier3: 13 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 15
        - effect: On a [critical hit](scc.v1:mcdm.heroes.v1/rule.combat/critical-hit), the size of the area increases by 3, and this ability deals an extra 10 damage.
          name: Effect
        - effect: You are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends). If you scored a [critical hit](scc.v1:mcdm.heroes.v1/rule.combat/critical-hit) with this ability, you die.
          name: Strained
    flavor: Unbridled psionic energy erupts from your body and flashes outward, hurling your foes back.
    keywords:
        - Area
        - Psionic
        - Telekinesis
    level: "9"
    name: Gravitic Nova
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-9/gravitic-nova
    subclass: telekinesis
    target: Each enemy and object in the area
    tier1: 6 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
    tier2: 9 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10
    tier3: 13 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 15
    type: ability
name: Gravitic Nova
target: Each enemy and object in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
