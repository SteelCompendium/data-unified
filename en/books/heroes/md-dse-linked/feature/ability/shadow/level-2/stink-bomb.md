---
action_type: Main action
class: shadow
cost: 5 Insight
cost_amount: "5"
cost_resource: Insight
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
effect: The gas remains in the area until the end of the encounter. Any creature who starts their [turn](../../../../rule/combat/turn.md) in the area and has M < AVERAGE is [weakened](../../../../condition/weakened.md) (save ends).
feature_type: ability
file_basename: stink-bomb
file_dpath: feature/ability/shadow/level-2
flavor: Putrid yellow gas explodes from a bomb you toss.
item_id: stink-bomb
item_name: Stink Bomb
keywords:
    - Area
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "2"
name: Stink Bomb
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-2/stink-bomb
source: mcdm.heroes.v1
target: Each creature in the area
tier1: 2 poison damage
tier2: 5 poison damage
tier3: 7 poison damage
type: ability
---

```ds-feature
cost: 5 Insight
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - effect: The gas remains in the area until the end of the encounter. Any creature who starts their [turn](../../../../rule/combat/turn.md) in the area and has M < AVERAGE is [weakened](../../../../condition/weakened.md) (save ends).
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 2 poison damage
      tier2: 5 poison damage
      tier3: 7 poison damage
feature_type: ability
flavor: Putrid yellow gas explodes from a bomb you toss.
keywords:
    - Area
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: Main action
    class: shadow
    cost: 5 Insight
    distance: 3 [cube](../../../../rule/combat/cube.md) within 10
    effect: The gas remains in the area until the end of the encounter. Any creature who starts their [turn](../../../../rule/combat/turn.md) in the area and has M < AVERAGE is [weakened](../../../../condition/weakened.md) (save ends).
    flavor: Putrid yellow gas explodes from a bomb you toss.
    keywords:
        - Area
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "2"
    name: Stink Bomb
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-2/stink-bomb
    target: Each creature in the area
    tier1: 2 poison damage
    tier2: 5 poison damage
    tier3: 7 poison damage
    type: ability
name: Stink Bomb
target: Each creature in the area
type: feature
usage: Main action
```
