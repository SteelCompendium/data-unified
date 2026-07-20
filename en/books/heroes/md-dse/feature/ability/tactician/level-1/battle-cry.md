---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: tactician
cost: 3 Focus
cost_amount: "3"
cost_resource: Focus
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: battle-cry
file_dpath: feature/ability/tactician/level-1
flavor: You shout a phrase that galvanizes your team.
item_id: battle-cry
item_name: Battle Cry
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Battle Cry
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/battle-cry
source: mcdm.heroes.v1
target: Three allies
tier1: Each target gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
tier2: Each target gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
tier3: Each target gains 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
type: ability
---

```ds-feature
cost: 3 Focus
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: Each target gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
      tier2: Each target gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
      tier3: Each target gains 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
feature_type: ability
flavor: You shout a phrase that galvanizes your team.
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: tactician
    cost: 3 Focus
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: You shout a phrase that galvanizes your team.
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Battle Cry
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/battle-cry
    target: Three allies
    tier1: Each target gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
    tier2: Each target gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
    tier3: Each target gains 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
    type: ability
name: Battle Cry
target: Three allies
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
