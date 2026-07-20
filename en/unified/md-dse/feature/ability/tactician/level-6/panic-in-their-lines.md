---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: tactician
cost: 9 Focus
cost_amount: "9"
cost_resource: Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effect: If a target is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) into another creature, they must make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against that creature.
feature_type: ability
file_basename: panic-in-their-lines
file_dpath: feature/ability/tactician/level-6
flavor: You confuse your foes, causing them to turn on each other.
item_id: panic-in-their-lines
item_name: Panic in Their Lines
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "6"
name: Panic in Their Lines
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-6/panic-in-their-lines
source: mcdm.heroes.v1
subclass: insurgent
target: Two creatures
tier1: 6 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier2: 9 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier3: 13 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
type: ability
---

```ds-feature
cost: 9 Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - effect: If a target is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) into another creature, they must make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against that creature.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 6 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier2: 9 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier3: 13 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
feature_type: ability
flavor: You confuse your foes, causing them to turn on each other.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: tactician
    cost: 9 Focus
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
    effect: If a target is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) into another creature, they must make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against that creature.
    flavor: You confuse your foes, causing them to turn on each other.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "6"
    name: Panic in Their Lines
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-6/panic-in-their-lines
    subclass: insurgent
    target: Two creatures
    tier1: 6 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier2: 9 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    tier3: 13 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
    type: ability
name: Panic in Their Lines
target: Two creatures
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
