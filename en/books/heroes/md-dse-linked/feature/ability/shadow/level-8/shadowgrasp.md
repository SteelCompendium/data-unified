---
action_type: Main action
class: shadow
cost: 11 Insight
cost_amount: "11"
cost_resource: Insight
distance: 2 [burst](../../../../rule/combat/burst.md)
feature_type: ability
file_basename: shadowgrasp
file_dpath: feature/ability/shadow/level-8
flavor: The shadows around you give way, allowing the shadow creature within you to grasp at your foes.
item_id: shadowgrasp
item_name: Shadowgrasp
keywords:
    - Area
    - Magic
level: "8"
name: Shadowgrasp
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-8/shadowgrasp
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 11 corruption damage; A < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
tier2: 16 corruption damage; A < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
tier3: 21 corruption damage; A < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
type: ability
---

```ds-feature
cost: 11 Insight
distance: 2 [burst](../../../../rule/combat/burst.md)
effects:
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 11 corruption damage; A < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
      tier2: 16 corruption damage; A < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
      tier3: 21 corruption damage; A < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
feature_type: ability
flavor: The shadows around you give way, allowing the shadow creature within you to grasp at your foes.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: shadow
    cost: 11 Insight
    distance: 2 [burst](../../../../rule/combat/burst.md)
    flavor: The shadows around you give way, allowing the shadow creature within you to grasp at your foes.
    keywords:
        - Area
        - Magic
    level: "8"
    name: Shadowgrasp
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-8/shadowgrasp
    target: Each enemy in the area
    tier1: 11 corruption damage; A < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
    tier2: 16 corruption damage; A < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
    tier3: 21 corruption damage; A < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
    type: ability
name: Shadowgrasp
target: Each enemy in the area
type: feature
usage: Main action
```
