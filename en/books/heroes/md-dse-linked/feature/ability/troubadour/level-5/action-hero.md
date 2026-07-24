---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: troubadour
cost: 9 Drama
cost_amount: "9"
cost_resource: Drama
distance: 3 [burst](../../../../rule/combat/burst.md)
effects:
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 10 damage
      tier2: 14 damage
      tier3: 20 damage
    - effect: Unless you score a [critical hit](../../../../rule/combat/critical-hit.md), this ability can't reduce a non-minion target below 1 [Stamina](../../../../rule/health/stamina.md).
      name: Effect
feature_type: ability
file_basename: action-hero
file_dpath: feature/ability/troubadour/level-5
flavor: You wield your weapon at blistering [speed](../../../../rule/character/speed.md), leaving everyone around you fighting for their lives.
item_id: action-hero
item_name: Action Hero
keywords:
    - Area
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
level: "5"
name: Action Hero
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-5/action-hero
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 10 damage
tier2: 14 damage
tier3: 20 damage
type: ability
---

```ds-feature
cost: 9 Drama
distance: 3 [burst](../../../../rule/combat/burst.md)
effects:
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 10 damage
      tier2: 14 damage
      tier3: 20 damage
    - effect: Unless you score a [critical hit](../../../../rule/combat/critical-hit.md), this ability can't reduce a non-minion target below 1 [Stamina](../../../../rule/health/stamina.md).
      name: Effect
feature_type: ability
flavor: You wield your weapon at blistering [speed](../../../../rule/character/speed.md), leaving everyone around you fighting for their lives.
keywords:
    - Area
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: troubadour
    cost: 9 Drama
    distance: 3 [burst](../../../../rule/combat/burst.md)
    effects:
        - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
          tier1: 10 damage
          tier2: 14 damage
          tier3: 20 damage
        - effect: Unless you score a [critical hit](../../../../rule/combat/critical-hit.md), this ability can't reduce a non-minion target below 1 [Stamina](../../../../rule/health/stamina.md).
          name: Effect
    flavor: You wield your weapon at blistering [speed](../../../../rule/character/speed.md), leaving everyone around you fighting for their lives.
    keywords:
        - Area
        - '[Melee](../../../../rule/combat/melee.md)'
        - Weapon
    level: "5"
    name: Action Hero
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-5/action-hero
    target: Each enemy in the area
    tier1: 10 damage
    tier2: 14 damage
    tier3: 20 damage
    type: ability
name: Action Hero
target: Each enemy in the area
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
