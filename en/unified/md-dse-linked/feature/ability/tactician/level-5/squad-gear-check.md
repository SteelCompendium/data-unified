---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: tactician
cost: 9 Focus
cost_amount: "9"
cost_resource: Focus
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 9 + M damage
      tier2: 13 + M damage
      tier3: 18 + M damage
    - effect: You and each ally [adjacent](../../../../rule/combat/adjacent.md) to the target gain 10 [temporary Stamina](../../../../rule/health/temporary-stamina.md).
      name: Effect
feature_type: ability
file_basename: squad-gear-check
file_dpath: feature/ability/tactician/level-5
flavor: You distract a foe while your allies secure their defensive gear.
item_id: squad-gear-check
item_name: Squad! Gear Check!
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "5"
name: Squad! Gear Check!
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-5/squad-gear-check
source: mcdm.heroes.v1
target: One creature
tier1: 9 + M damage
tier2: 13 + M damage
tier3: 18 + M damage
type: ability
---

```ds-feature
cost: 9 Focus
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 9 + M damage
      tier2: 13 + M damage
      tier3: 18 + M damage
    - effect: You and each ally [adjacent](../../../../rule/combat/adjacent.md) to the target gain 10 [temporary Stamina](../../../../rule/health/temporary-stamina.md).
      name: Effect
feature_type: ability
flavor: You distract a foe while your allies secure their defensive gear.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: tactician
    cost: 9 Focus
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effects:
        - roll: Power Roll + [Might](../../../../rule/character/might.md)
          tier1: 9 + M damage
          tier2: 13 + M damage
          tier3: 18 + M damage
        - effect: You and each ally [adjacent](../../../../rule/combat/adjacent.md) to the target gain 10 [temporary Stamina](../../../../rule/health/temporary-stamina.md).
          name: Effect
    flavor: You distract a foe while your allies secure their defensive gear.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "5"
    name: Squad! Gear Check!
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-5/squad-gear-check
    target: One creature
    tier1: 9 + M damage
    tier2: 13 + M damage
    tier3: 18 + M damage
    type: ability
name: Squad! Gear Check!
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
