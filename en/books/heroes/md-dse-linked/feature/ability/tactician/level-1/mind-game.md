---
action_type: Main action
class: tactician
cost: 5 Focus
cost_amount: "5"
cost_resource: Focus
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effect: You mark the target.
feature_type: ability
file_basename: mind-game
file_dpath: feature/ability/tactician/level-1
flavor: Your attack demoralizes your foe. Your allies begin to think you can win.
item_id: mind-game
item_name: Mind Game
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Mind Game
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/mind-game
source: mcdm.heroes.v1
target: One creature or object
tier1: 4 + M damage; R < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
tier2: 6 + M damage; R < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
tier3: 10 + M damage; R < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
type: ability
---

```ds-feature
cost: 5 Focus
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - effect: You mark the target.
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 4 + M damage; R < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
      tier2: 6 + M damage; R < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
      tier3: 10 + M damage; R < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
feature_type: ability
flavor: Your attack demoralizes your foe. Your allies begin to think you can win.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: tactician
    cost: 5 Focus
    distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
    effect: You mark the target.
    flavor: Your attack demoralizes your foe. Your allies begin to think you can win.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Mind Game
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/mind-game
    target: One creature or object
    tier1: 4 + M damage; R < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
    tier2: 6 + M damage; R < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
    tier3: 10 + M damage; R < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
    type: ability
name: Mind Game
target: One creature or object
type: feature
usage: Main action
```
