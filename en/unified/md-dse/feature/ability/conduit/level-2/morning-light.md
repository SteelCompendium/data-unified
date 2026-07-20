---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effect: Each ally in the area deals fire damage equal to your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score with their next strike made before the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
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
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
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
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: Each ally in the area deals fire damage equal to your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score with their next strike made before the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 4 fire damage
      tier2: 6 fire damage
      tier3: 10 fire damage
feature_type: ability
flavor: Light shines at your command, burning your foes and blessing your allies.
keywords:
    - Area
    - Magic
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    cost: 5 Piety
    distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effect: Each ally in the area deals fire damage equal to your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score with their next strike made before the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    flavor: Light shines at your command, burning your foes and blessing your allies.
    keywords:
        - Area
        - Magic
    level: "2"
    name: Morning Light
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
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
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
