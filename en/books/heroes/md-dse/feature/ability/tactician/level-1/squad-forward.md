---
action_type: Maneuver
class: tactician
cost: 3 Focus
cost_amount: "3"
cost_resource: Focus
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: Each target can move up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed).
feature_type: ability
file_basename: squad-forward
file_dpath: feature/ability/tactician/level-1
flavor: On your command, you and your allies force back the enemy line.
item_id: squad-forward
item_name: Squad! Forward!
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Squad! Forward!
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/squad-forward
source: mcdm.heroes.v1
target: Self and two allies
type: ability
---

```ds-feature
cost: 3 Focus
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: Each target can move up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed).
feature_type: ability
flavor: On your command, you and your allies force back the enemy line.
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Maneuver
    class: tactician
    cost: 3 Focus
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: Each target can move up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed).
    flavor: On your command, you and your allies force back the enemy line.
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Squad! Forward!
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/squad-forward
    target: Self and two allies
    type: ability
name: Squad! Forward!
target: Self and two allies
type: feature
usage: Maneuver
```
