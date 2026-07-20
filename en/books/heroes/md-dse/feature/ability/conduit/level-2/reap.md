---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: Until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), each time a target kills an enemy, they regain [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to 5 + your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score.
feature_type: ability
file_basename: reap
file_dpath: feature/ability/conduit/level-2
flavor: The gods reward those who smite their foes.
item_id: reap
item_name: Reap
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "2"
name: Reap
scc: mcdm.heroes.v1/feature.ability.conduit.level-2/reap
source: mcdm.heroes.v1
subclass: death
target: Each ally
type: ability
---

```ds-feature
cost: 5 Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: Until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), each time a target kills an enemy, they regain [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to 5 + your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score.
feature_type: ability
flavor: The gods reward those who smite their foes.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    cost: 5 Piety
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: Until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), each time a target kills an enemy, they regain [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to 5 + your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score.
    flavor: The gods reward those who smite their foes.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "2"
    name: Reap
    scc: mcdm.heroes.v1/feature.ability.conduit.level-2/reap
    subclass: death
    target: Each ally
    type: ability
name: Reap
target: Each ally
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
