---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: 3 [burst](../../../../rule/combat/burst.md)
effect: Each ally in the area deals fire damage equal to your [Intuition](../../../../rule/character/intuition.md) score with their next strike made before the end of their next [turn](../../../../rule/combat/turn.md).
feature_type: ability
file_basename: morning-light
file_dpath: feature/ability/conduit/level-2
flavor: Light shines at your command, burning your foes and blessing your allies.
item_id: morning-light
item_name: Morning Light
keywords:
    - Area
    - Magic
level: "2"
name: Morning Light
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-2/morning-light
source: mcdm.heroes.v1
subclass: sun
target: Each enemy in the area
tier1: 4 fire damage
tier2: 6 fire damage
tier3: 10 fire damage
type: ability
---

```ds-feature
cost: 5 Piety
distance: 3 [burst](../../../../rule/combat/burst.md)
effects:
    - effect: Each ally in the area deals fire damage equal to your [Intuition](../../../../rule/character/intuition.md) score with their next strike made before the end of their next [turn](../../../../rule/combat/turn.md).
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 4 fire damage
      tier2: 6 fire damage
      tier3: 10 fire damage
feature_type: ability
flavor: Light shines at your command, burning your foes and blessing your allies.
keywords:
    - Area
    - Magic
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: conduit
    cost: 5 Piety
    distance: 3 [burst](../../../../rule/combat/burst.md)
    effect: Each ally in the area deals fire damage equal to your [Intuition](../../../../rule/character/intuition.md) score with their next strike made before the end of their next [turn](../../../../rule/combat/turn.md).
    flavor: Light shines at your command, burning your foes and blessing your allies.
    keywords:
        - Area
        - Magic
    level: "2"
    name: Morning Light
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-2/morning-light
    subclass: sun
    target: Each enemy in the area
    tier1: 4 fire damage
    tier2: 6 fire damage
    tier3: 10 fire damage
    type: ability
name: Morning Light
target: Each enemy in the area
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
