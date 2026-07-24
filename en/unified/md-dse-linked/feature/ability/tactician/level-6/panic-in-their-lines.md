---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: tactician
cost: 9 Focus
cost_amount: "9"
cost_resource: Focus
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 6 + M damage; [slide](../../../../movement/forced-movement.md) 1
      tier2: 9 + M damage; [slide](../../../../movement/forced-movement.md) 3
      tier3: 13 + M damage; [slide](../../../../movement/forced-movement.md) 5
    - effect: If a target is [force moved](../../../../movement/forced-movement.md) into another creature, they must make a [free strike](../../../common/main-actions/free-strike.md) against that creature.
      name: Effect
feature_type: ability
file_basename: panic-in-their-lines
file_dpath: feature/ability/tactician/level-6
flavor: You confuse your foes, causing them to turn on each other.
item_id: panic-in-their-lines
item_name: Panic in Their Lines
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "6"
name: Panic in Their Lines
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-6/panic-in-their-lines
source: mcdm.heroes.v1
subclass: insurgent
target: Two creatures
tier1: 6 + M damage; [slide](../../../../movement/forced-movement.md) 1
tier2: 9 + M damage; [slide](../../../../movement/forced-movement.md) 3
tier3: 13 + M damage; [slide](../../../../movement/forced-movement.md) 5
type: ability
---

```ds-feature
cost: 9 Focus
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 6 + M damage; [slide](../../../../movement/forced-movement.md) 1
      tier2: 9 + M damage; [slide](../../../../movement/forced-movement.md) 3
      tier3: 13 + M damage; [slide](../../../../movement/forced-movement.md) 5
    - effect: If a target is [force moved](../../../../movement/forced-movement.md) into another creature, they must make a [free strike](../../../common/main-actions/free-strike.md) against that creature.
      name: Effect
feature_type: ability
flavor: You confuse your foes, causing them to turn on each other.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: tactician
    cost: 9 Focus
    distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
    effects:
        - roll: Power Roll + [Might](../../../../rule/character/might.md)
          tier1: 6 + M damage; [slide](../../../../movement/forced-movement.md) 1
          tier2: 9 + M damage; [slide](../../../../movement/forced-movement.md) 3
          tier3: 13 + M damage; [slide](../../../../movement/forced-movement.md) 5
        - effect: If a target is [force moved](../../../../movement/forced-movement.md) into another creature, they must make a [free strike](../../../common/main-actions/free-strike.md) against that creature.
          name: Effect
    flavor: You confuse your foes, causing them to turn on each other.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "6"
    name: Panic in Their Lines
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-6/panic-in-their-lines
    subclass: insurgent
    target: Two creatures
    tier1: 6 + M damage; [slide](../../../../movement/forced-movement.md) 1
    tier2: 9 + M damage; [slide](../../../../movement/forced-movement.md) 3
    tier3: 13 + M damage; [slide](../../../../movement/forced-movement.md) 5
    type: ability
name: Panic in Their Lines
target: Two creatures
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
