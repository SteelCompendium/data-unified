---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: shadow
cost: 5 Insight
cost_amount: "5"
cost_resource: Insight
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 2 poison damage
      tier2: 5 poison damage
      tier3: 7 poison damage
    - effect: The gas remains in the area until the end of the encounter. Any creature who starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) in the area and has M < AVERAGE is [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends).
      name: Effect
feature_type: ability
file_basename: stink-bomb
file_dpath: feature/ability/shadow/level-2
flavor: Putrid yellow gas explodes from a bomb you toss.
item_id: stink-bomb
item_name: Stink Bomb
keywords:
    - Area
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "2"
name: Stink Bomb
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-2/stink-bomb
source: mcdm.heroes.v1
subclass: caustic-alchemy
target: Each creature in the area
tier1: 2 poison damage
tier2: 5 poison damage
tier3: 7 poison damage
type: ability
---

```ds-feature
cost: 5 Insight
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 2 poison damage
      tier2: 5 poison damage
      tier3: 7 poison damage
    - effect: The gas remains in the area until the end of the encounter. Any creature who starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) in the area and has M < AVERAGE is [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends).
      name: Effect
feature_type: ability
flavor: Putrid yellow gas explodes from a bomb you toss.
keywords:
    - Area
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: shadow
    cost: 5 Insight
    distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    effects:
        - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 2 poison damage
          tier2: 5 poison damage
          tier3: 7 poison damage
        - effect: The gas remains in the area until the end of the encounter. Any creature who starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) in the area and has M < AVERAGE is [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends).
          name: Effect
    flavor: Putrid yellow gas explodes from a bomb you toss.
    keywords:
        - Area
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "2"
    name: Stink Bomb
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-2/stink-bomb
    subclass: caustic-alchemy
    target: Each creature in the area
    tier1: 2 poison damage
    tier2: 5 poison damage
    tier3: 7 poison damage
    type: ability
name: Stink Bomb
target: Each creature in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
