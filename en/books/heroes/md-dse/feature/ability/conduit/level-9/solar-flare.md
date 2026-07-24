---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 11 Piety
cost_amount: "11"
cost_resource: Piety
distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 9 fire damage
      tier2: 14 fire damage
      tier3: 19 fire damage
feature_type: ability
file_basename: solar-flare
file_dpath: feature/ability/conduit/level-9
flavor: You call down a sphere of fire that burns your foes to ash.
item_id: solar-flare
item_name: Solar Flare
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "9"
name: Solar Flare
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-9/solar-flare
source: mcdm.heroes.v1
subclass: sun
target: Each enemy in the area
tier1: 9 fire damage
tier2: 14 fire damage
tier3: 19 fire damage
type: ability
---

```ds-feature
cost: 11 Piety
distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 9 fire damage
      tier2: 14 fire damage
      tier3: 19 fire damage
feature_type: ability
flavor: You call down a sphere of fire that burns your foes to ash.
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    cost: 11 Piety
    distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    effects:
        - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
          tier1: 9 fire damage
          tier2: 14 fire damage
          tier3: 19 fire damage
    flavor: You call down a sphere of fire that burns your foes to ash.
    keywords:
        - Area
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "9"
    name: Solar Flare
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-9/solar-flare
    subclass: sun
    target: Each enemy in the area
    tier1: 9 fire damage
    tier2: 14 fire damage
    tier3: 19 fire damage
    type: ability
name: Solar Flare
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
