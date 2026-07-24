---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: fury
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 4 damage; I < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
      tier2: 6 damage; I < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
      tier3: 10 damage; I < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
    - effect: The target can't be hidden from you for 24 hours. Until the end of the encounter, whenever the target willingly moves, you can use a free [triggered action](../../../../rule/combat/triggered-action.md) to move.
      name: Effect
feature_type: ability
file_basename: apex-predator
file_dpath: feature/ability/fury/level-2
flavor: I will hunt you down.
item_id: apex-predator
item_name: Apex Predator
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "2"
name: Apex Predator
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.fury.level-2/apex-predator
source: mcdm.heroes.v1
target: One creature
tier1: 4 damage; I < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
tier2: 6 damage; I < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
tier3: 10 damage; I < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 4 damage; I < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
      tier2: 6 damage; I < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
      tier3: 10 damage; I < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
    - effect: The target can't be hidden from you for 24 hours. Until the end of the encounter, whenever the target willingly moves, you can use a free [triggered action](../../../../rule/combat/triggered-action.md) to move.
      name: Effect
feature_type: ability
flavor: I will hunt you down.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: fury
    cost: 5 Ferocity
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effects:
        - roll: Power Roll + [Might](../../../../rule/character/might.md)
          tier1: 4 damage; I < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
          tier2: 6 damage; I < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
          tier3: 10 damage; I < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
        - effect: The target can't be hidden from you for 24 hours. Until the end of the encounter, whenever the target willingly moves, you can use a free [triggered action](../../../../rule/combat/triggered-action.md) to move.
          name: Effect
    flavor: I will hunt you down.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "2"
    name: Apex Predator
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-2/apex-predator
    target: One creature
    tier1: 4 damage; I < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
    tier2: 6 damage; I < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
    tier3: 10 damage; I < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
    type: ability
name: Apex Predator
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
