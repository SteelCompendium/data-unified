---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: fury
cost: 3 Ferocity
cost_amount: "3"
cost_resource: Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 3 + M damage; [slide](../../../../movement/forced-movement.md) 2
      tier2: 5 + M damage; [slide](../../../../movement/forced-movement.md) 3
      tier3: 8 + M damage; [slide](../../../../movement/forced-movement.md) 5
    - effect: When you [slide](../../../../movement/forced-movement.md) the target, you can move into any square they leave. If you take damage from an [opportunity attack](../../../../rule/combat/opportunity-attack.md) by moving this way, the target takes the same damage.
      name: Effect
feature_type: ability
file_basename: out-of-the-way
file_dpath: feature/ability/fury/level-1
flavor: Your enemies will clear your path—whether they want to or not.
item_id: out-of-the-way
item_name: Out of the Way!
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Out of the Way!
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.fury.level-1/out-of-the-way
source: mcdm.heroes.v1
target: One creature
tier1: 3 + M damage; [slide](../../../../movement/forced-movement.md) 2
tier2: 5 + M damage; [slide](../../../../movement/forced-movement.md) 3
tier3: 8 + M damage; [slide](../../../../movement/forced-movement.md) 5
type: ability
---

```ds-feature
cost: 3 Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 3 + M damage; [slide](../../../../movement/forced-movement.md) 2
      tier2: 5 + M damage; [slide](../../../../movement/forced-movement.md) 3
      tier3: 8 + M damage; [slide](../../../../movement/forced-movement.md) 5
    - effect: When you [slide](../../../../movement/forced-movement.md) the target, you can move into any square they leave. If you take damage from an [opportunity attack](../../../../rule/combat/opportunity-attack.md) by moving this way, the target takes the same damage.
      name: Effect
feature_type: ability
flavor: Your enemies will clear your path—whether they want to or not.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: fury
    cost: 3 Ferocity
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effects:
        - roll: Power Roll + [Might](../../../../rule/character/might.md)
          tier1: 3 + M damage; [slide](../../../../movement/forced-movement.md) 2
          tier2: 5 + M damage; [slide](../../../../movement/forced-movement.md) 3
          tier3: 8 + M damage; [slide](../../../../movement/forced-movement.md) 5
        - effect: When you [slide](../../../../movement/forced-movement.md) the target, you can move into any square they leave. If you take damage from an [opportunity attack](../../../../rule/combat/opportunity-attack.md) by moving this way, the target takes the same damage.
          name: Effect
    flavor: Your enemies will clear your path—whether they want to or not.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Out of the Way!
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/out-of-the-way
    target: One creature
    tier1: 3 + M damage; [slide](../../../../movement/forced-movement.md) 2
    tier2: 5 + M damage; [slide](../../../../movement/forced-movement.md) 3
    tier3: 8 + M damage; [slide](../../../../movement/forced-movement.md) 5
    type: ability
name: Out of the Way!
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
