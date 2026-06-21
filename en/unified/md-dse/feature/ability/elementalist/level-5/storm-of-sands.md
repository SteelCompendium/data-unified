---
action_type: Main action
class: elementalist
cost: 9 Essence
cost_amount: "9"
cost_resource: Essence
distance: 4 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effect: The area lasts until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). It is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies, and you and your allies have [concealment](scc.v1:mcdm.heroes.v1/rule.combat/concealment) while in the area.
feature_type: ability
file_basename: storm-of-sands
file_dpath: feature/ability/elementalist/level-5
flavor: Dirt and debris swirl into a dark, pulsing hurricane.
item_id: storm-of-sands
item_name: Storm of Sands
keywords:
    - Area
    - Earth
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "5"
name: Storm of Sands
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-5/storm-of-sands
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 2 damage
tier2: 5 damage
tier3: 7 damage
type: ability
---

```ds-feature
cost: 9 Essence
distance: 4 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - effect: The area lasts until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). It is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies, and you and your allies have [concealment](scc.v1:mcdm.heroes.v1/rule.combat/concealment) while in the area.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 damage
      tier2: 5 damage
      tier3: 7 damage
feature_type: ability
flavor: Dirt and debris swirl into a dark, pulsing hurricane.
keywords:
    - Area
    - Earth
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Main action
    class: elementalist
    cost: 9 Essence
    distance: 4 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    effect: The area lasts until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). It is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies, and you and your allies have [concealment](scc.v1:mcdm.heroes.v1/rule.combat/concealment) while in the area.
    flavor: Dirt and debris swirl into a dark, pulsing hurricane.
    keywords:
        - Area
        - Earth
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "5"
    name: Storm of Sands
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-5/storm-of-sands
    target: Each enemy in the area
    tier1: 2 damage
    tier2: 5 damage
    tier3: 7 damage
    type: ability
name: Storm of Sands
target: Each enemy in the area
type: feature
usage: Main action
```
