---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 3 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier2: 5 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
      tier3: 8 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
    - effect: If this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) causes a target to slam into you, you take no damage from the collision and the target takes the damage you would have taken.
      name: Effect
feature_type: ability
file_basename: primordial-vortex
file_dpath: feature/ability/fury/level-9
flavor: You channel the power of the Primordial Chaos to pull foes to you.
item_id: primordial-vortex
item_name: Primordial Vortex
keywords:
    - Area
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
level: "9"
name: Primordial Vortex
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-9/primordial-vortex
source: mcdm.heroes.v1
subclass: berserker
target: Each enemy in the area
tier1: 3 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier2: 5 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
tier3: 8 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 3 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier2: 5 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
      tier3: 8 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
    - effect: If this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) causes a target to slam into you, you take no damage from the collision and the target takes the damage you would have taken.
      name: Effect
feature_type: ability
flavor: You channel the power of the Primordial Chaos to pull foes to you.
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
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: 3 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
          tier2: 5 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
          tier3: 8 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
        - effect: If this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) causes a target to slam into you, you take no damage from the collision and the target takes the damage you would have taken.
          name: Effect
    flavor: You channel the power of the Primordial Chaos to pull foes to you.
    keywords:
        - Area
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Weapon
    level: "9"
    name: Primordial Vortex
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-9/primordial-vortex
    subclass: berserker
    target: Each enemy in the area
    tier1: 3 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    tier2: 5 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
    tier3: 8 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
    type: ability
name: Primordial Vortex
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
