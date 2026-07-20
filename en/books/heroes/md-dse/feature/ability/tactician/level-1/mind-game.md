---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: tactician
cost: 5 Focus
cost_amount: "5"
cost_resource: Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effect: You mark the target.
feature_type: ability
file_basename: mind-game
file_dpath: feature/ability/tactician/level-1
flavor: Your attack demoralizes your foe. Your allies begin to think you can win.
item_id: mind-game
item_name: Mind Game
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Mind Game
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/mind-game
source: mcdm.heroes.v1
target: One creature or object
tier1: 4 + M damage; R < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier2: 6 + M damage; R < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier3: 10 + M damage; R < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
type: ability
---

```ds-feature
cost: 5 Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - effect: You mark the target.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 4 + M damage; R < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier2: 6 + M damage; R < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier3: 10 + M damage; R < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
feature_type: ability
flavor: Your attack demoralizes your foe. Your allies begin to think you can win.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: tactician
    cost: 5 Focus
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
    effect: You mark the target.
    flavor: Your attack demoralizes your foe. Your allies begin to think you can win.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Mind Game
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/mind-game
    target: One creature or object
    tier1: 4 + M damage; R < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier2: 6 + M damage; R < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier3: 10 + M damage; R < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    type: ability
name: Mind Game
target: One creature or object
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
