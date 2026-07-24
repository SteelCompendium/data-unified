---
action_type: Main action
class: beastheart
cost: 3 Ferocity
cost_amount: "3"
cost_resource: Ferocity
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 5 + M damage; slide 1; I < WEAK [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier2: 8 + M damage; slide 2; I < AVERAGE [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier3: 11 + M damage; slide 4; I < STRONG [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    - effect: You and your companion can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to a number of squares equal to the number of squares the target was [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement).
      name: Effect
feature_type: ability
file_basename: herd-the-sheep
file_dpath: feature/ability/beastheart/level-1
flavor: Your companion circles your foe, luring them out of position with fake openings and unpredictable attacks.
item_id: herd-the-sheep
item_name: Herd the Sheep
keywords:
    - Companion
    - Melee
    - Strike
    - Weapon
level: "1"
name: Herd the Sheep
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/herd-the-sheep
source: mcdm.beastheart.v1
target: One creature
tier1: 5 + M damage; slide 1; I < WEAK [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier2: 8 + M damage; slide 2; I < AVERAGE [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier3: 11 + M damage; slide 4; I < STRONG [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
type: ability
---

```ds-feature
cost: 3 Ferocity
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 5 + M damage; slide 1; I < WEAK [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier2: 8 + M damage; slide 2; I < AVERAGE [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier3: 11 + M damage; slide 4; I < STRONG [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    - effect: You and your companion can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to a number of squares equal to the number of squares the target was [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement).
      name: Effect
feature_type: ability
flavor: Your companion circles your foe, luring them out of position with fake openings and unpredictable attacks.
keywords:
    - Companion
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    cost: 3 Ferocity
    distance: Melee 1
    effects:
        - roll: Power Roll + Might
          tier1: 5 + M damage; slide 1; I < WEAK [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
          tier2: 8 + M damage; slide 2; I < AVERAGE [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
          tier3: 11 + M damage; slide 4; I < STRONG [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
        - effect: You and your companion can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to a number of squares equal to the number of squares the target was [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement).
          name: Effect
    flavor: Your companion circles your foe, luring them out of position with fake openings and unpredictable attacks.
    keywords:
        - Companion
        - Melee
        - Strike
        - Weapon
    level: "1"
    name: Herd the Sheep
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/herd-the-sheep
    target: One creature
    tier1: 5 + M damage; slide 1; I < WEAK [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier2: 8 + M damage; slide 2; I < AVERAGE [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier3: 11 + M damage; slide 4; I < STRONG [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    type: ability
name: Herd the Sheep
target: One creature
type: feature
usage: Main action
```
