---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: tactician
cost: 3 Focus
cost_amount: "3"
cost_resource: Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 3 + M damage; M < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier2: 5 + M damage; M < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier3: 8 + M damage; M < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
feature_type: ability
file_basename: concussive-strike
file_dpath: feature/ability/tactician/level-1
flavor: Your precise strike leaves your foe struggling to respond.
item_id: concussive-strike
item_name: Concussive Strike
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Concussive Strike
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/concussive-strike
source: mcdm.heroes.v1
target: One creature or object
tier1: 3 + M damage; M < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier2: 5 + M damage; M < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier3: 8 + M damage; M < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
type: ability
---

```ds-feature
cost: 3 Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 3 + M damage; M < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier2: 5 + M damage; M < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier3: 8 + M damage; M < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
feature_type: ability
flavor: Your precise strike leaves your foe struggling to respond.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: tactician
    cost: 3 Focus
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: 3 + M damage; M < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
          tier2: 5 + M damage; M < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
          tier3: 8 + M damage; M < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    flavor: Your precise strike leaves your foe struggling to respond.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Concussive Strike
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/concussive-strike
    target: One creature or object
    tier1: 3 + M damage; M < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    tier2: 5 + M damage; M < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    tier3: 8 + M damage; M < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    type: ability
name: Concussive Strike
target: One creature or object
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
