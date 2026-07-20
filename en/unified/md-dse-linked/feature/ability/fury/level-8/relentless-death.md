---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: fury
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: Self; see below
effect: You [shift](../../../../movement/shifting.md) up to your [speed](../../../../rule/character/speed.md). Each enemy you move [adjacent](../../../../rule/combat/adjacent.md) to during this movement takes damage equal to twice your [Might](../../../../rule/character/might.md) score. Then make one [power roll](../../../../rule/dice/power-roll.md) that targets each enemy you move [adjacent](../../../../rule/combat/adjacent.md) to during this [shift](../../../../movement/shifting.md). You gain 1 ferocity for each target who dies as a result of this ability (maximum 11 ferocity).
feature_type: ability
file_basename: relentless-death
file_dpath: feature/ability/fury/level-8
flavor: You won't escape your fate.
item_id: relentless-death
item_name: Relentless Death
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "8"
name: Relentless Death
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.fury.level-8/relentless-death
source: mcdm.heroes.v1
target: Self
tier1: Any target whose [Stamina](../../../../rule/health/stamina.md) is equal to or less than 8 dies.
tier2: Any target whose [Stamina](../../../../rule/health/stamina.md) is equal to or less than 11 dies.
tier3: Any target whose [Stamina](../../../../rule/health/stamina.md) is equal to or less than 17 dies.
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: Self; see below
effects:
    - effect: You [shift](../../../../movement/shifting.md) up to your [speed](../../../../rule/character/speed.md). Each enemy you move [adjacent](../../../../rule/combat/adjacent.md) to during this movement takes damage equal to twice your [Might](../../../../rule/character/might.md) score. Then make one [power roll](../../../../rule/dice/power-roll.md) that targets each enemy you move [adjacent](../../../../rule/combat/adjacent.md) to during this [shift](../../../../movement/shifting.md). You gain 1 ferocity for each target who dies as a result of this ability (maximum 11 ferocity).
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: Any target whose [Stamina](../../../../rule/health/stamina.md) is equal to or less than 8 dies.
      tier2: Any target whose [Stamina](../../../../rule/health/stamina.md) is equal to or less than 11 dies.
      tier3: Any target whose [Stamina](../../../../rule/health/stamina.md) is equal to or less than 17 dies.
feature_type: ability
flavor: You won't escape your fate.
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: fury
    cost: 11 Ferocity
    distance: Self; see below
    effect: You [shift](../../../../movement/shifting.md) up to your [speed](../../../../rule/character/speed.md). Each enemy you move [adjacent](../../../../rule/combat/adjacent.md) to during this movement takes damage equal to twice your [Might](../../../../rule/character/might.md) score. Then make one [power roll](../../../../rule/dice/power-roll.md) that targets each enemy you move [adjacent](../../../../rule/combat/adjacent.md) to during this [shift](../../../../movement/shifting.md). You gain 1 ferocity for each target who dies as a result of this ability (maximum 11 ferocity).
    flavor: You won't escape your fate.
    keywords:
        - Magic
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "8"
    name: Relentless Death
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-8/relentless-death
    target: Self
    tier1: Any target whose [Stamina](../../../../rule/health/stamina.md) is equal to or less than 8 dies.
    tier2: Any target whose [Stamina](../../../../rule/health/stamina.md) is equal to or less than 11 dies.
    tier3: Any target whose [Stamina](../../../../rule/health/stamina.md) is equal to or less than 17 dies.
    type: ability
name: Relentless Death
target: Self
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
