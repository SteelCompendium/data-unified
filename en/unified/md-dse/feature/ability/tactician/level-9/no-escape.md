---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: tactician
cost: 11 Focus
cost_amount: "11"
cost_resource: Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You mark the target.
      name: Effect
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 11 + M damage
      tier2: 16 + M damage
      tier3: 21 + M damage
    - effect: If you use this ability as part of the [Charge](scc.v1:mcdm.heroes.v1/feature.common.main-actions/charge) main action, enemies' spaces don't count as [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for your movement. Additionally, if you move through any creature's space, you can [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) that creature 1 square out of the path of your charge.
      name: Effect
feature_type: ability
file_basename: no-escape
file_dpath: feature/ability/tactician/level-9
flavor: Nothing will stop you from reaching your foe.
item_id: no-escape
item_name: No Escape
keywords:
    - Charge
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "9"
name: No Escape
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
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
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You mark the target.
      name: Effect
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 11 + M damage
      tier2: 16 + M damage
      tier3: 21 + M damage
    - effect: If you use this ability as part of the [Charge](scc.v1:mcdm.heroes.v1/feature.common.main-actions/charge) main action, enemies' spaces don't count as [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for your movement. Additionally, if you move through any creature's space, you can [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) that creature 1 square out of the path of your charge.
      name: Effect
feature_type: ability
flavor: Nothing will stop you from reaching your foe.
keywords:
    - Charge
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: tactician
    cost: 11 Focus
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - effect: You mark the target.
          name: Effect
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: 11 + M damage
          tier2: 16 + M damage
          tier3: 21 + M damage
        - effect: If you use this ability as part of the [Charge](scc.v1:mcdm.heroes.v1/feature.common.main-actions/charge) main action, enemies' spaces don't count as [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for your movement. Additionally, if you move through any creature's space, you can [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) that creature 1 square out of the path of your charge.
          name: Effect
    flavor: Nothing will stop you from reaching your foe.
    keywords:
        - Charge
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "9"
    name: No Escape
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
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
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
