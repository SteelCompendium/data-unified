---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: tactician
cost: 11 Focus
cost_amount: "11"
cost_resource: Focus
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: You mark the target.
      name: Effect
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 11 + M damage
      tier2: 16 + M damage
      tier3: 21 + M damage
    - effect: If you use this ability as part of the [Charge](../../../common/main-actions/charge.md) main action, enemies' spaces don't count as [difficult terrain](../../../../movement/difficult-terrain.md) for your movement. Additionally, if you move through any creature's space, you can [slide](../../../../movement/forced-movement.md) that creature 1 square out of the path of your charge.
      name: Effect
feature_type: ability
file_basename: no-escape
file_dpath: feature/ability/tactician/level-9
flavor: Nothing will stop you from reaching your foe.
item_id: no-escape
item_name: No Escape
keywords:
    - Charge
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "9"
name: No Escape
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-9/no-escape
source: mcdm.heroes.v1
subclass: vanguard
target: One creature
tier1: 11 + M damage
tier2: 16 + M damage
tier3: 21 + M damage
type: ability
---

```ds-feature
cost: 11 Focus
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: You mark the target.
      name: Effect
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 11 + M damage
      tier2: 16 + M damage
      tier3: 21 + M damage
    - effect: If you use this ability as part of the [Charge](../../../common/main-actions/charge.md) main action, enemies' spaces don't count as [difficult terrain](../../../../movement/difficult-terrain.md) for your movement. Additionally, if you move through any creature's space, you can [slide](../../../../movement/forced-movement.md) that creature 1 square out of the path of your charge.
      name: Effect
feature_type: ability
flavor: Nothing will stop you from reaching your foe.
keywords:
    - Charge
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: tactician
    cost: 11 Focus
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effects:
        - effect: You mark the target.
          name: Effect
        - roll: Power Roll + [Might](../../../../rule/character/might.md)
          tier1: 11 + M damage
          tier2: 16 + M damage
          tier3: 21 + M damage
        - effect: If you use this ability as part of the [Charge](../../../common/main-actions/charge.md) main action, enemies' spaces don't count as [difficult terrain](../../../../movement/difficult-terrain.md) for your movement. Additionally, if you move through any creature's space, you can [slide](../../../../movement/forced-movement.md) that creature 1 square out of the path of your charge.
          name: Effect
    flavor: Nothing will stop you from reaching your foe.
    keywords:
        - Charge
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "9"
    name: No Escape
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-9/no-escape
    subclass: vanguard
    target: One creature
    tier1: 11 + M damage
    tier2: 16 + M damage
    tier3: 21 + M damage
    type: ability
name: No Escape
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
