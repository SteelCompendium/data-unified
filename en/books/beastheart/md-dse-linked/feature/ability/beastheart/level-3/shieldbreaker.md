---
action_type: Main action
class: beastheart
cost: 7 Ferocity
cost_amount: "7"
cost_resource: Ferocity
distance: Melee 1 or ranged 5
effect: The next creature who damages the target before the start of your next turn gains 3 surges, which they can use on the triggering damage.
feature_type: ability
file_basename: shieldbreaker
file_dpath: feature/ability/beastheart/level-3
flavor: You smash through their guard and shatter their armor, leaving them wide open.
item_id: shieldbreaker
item_name: Shieldbreaker
keywords:
    - Beastheart
    - Melee
    - Ranged
    - Strike
    - Weapon
level: "3"
name: Shieldbreaker
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-3/shieldbreaker
source: mcdm.beastheart.v1
target: One creature
tier1: 9 + M damage
tier2: 14 + M damage
tier3: 19 + M damage
type: ability
---

```ds-feature
cost: 7 Ferocity
distance: Melee 1 or ranged 5
effects:
    - effect: The next creature who damages the target before the start of your next turn gains 3 surges, which they can use on the triggering damage.
    - roll: Power Roll + Might
      tier1: 9 + M damage
      tier2: 14 + M damage
      tier3: 19 + M damage
feature_type: ability
flavor: You smash through their guard and shatter their armor, leaving them wide open.
keywords:
    - Beastheart
    - Melee
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    cost: 7 Ferocity
    distance: Melee 1 or ranged 5
    effect: The next creature who damages the target before the start of your next turn gains 3 surges, which they can use on the triggering damage.
    flavor: You smash through their guard and shatter their armor, leaving them wide open.
    keywords:
        - Beastheart
        - Melee
        - Ranged
        - Strike
        - Weapon
    level: "3"
    name: Shieldbreaker
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-3/shieldbreaker
    target: One creature
    tier1: 9 + M damage
    tier2: 14 + M damage
    tier3: 19 + M damage
    type: ability
name: Shieldbreaker
target: One creature
type: feature
usage: Main action
```
