---
action_type: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
class: tactician
cost: 9 Focus
cost_amount: "9"
cost_resource: Focus
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: If the target of the triggering ability is not a leader or solo creature, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina). If the target of the triggering ability is a minion, the entire squad is killed. If the target of the triggering ability is a leader or solo creature, the triggering ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) automatically obtains a tier 3 outcome.
feature_type: ability
file_basename: coordinated-execution
file_dpath: feature/ability/tactician/level-6
flavor: You direct your ally to make a killing blow.
item_id: coordinated-execution
item_name: Coordinated Execution
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "6"
name: Coordinated Execution
scc: mcdm.heroes.v1/feature.ability.tactician.level-6/coordinated-execution
source: mcdm.heroes.v1
subclass: insurgent
subtype: triggered
target: One ally
trigger: The target uses an ability to deal [rolled damage](scc.v1:mcdm.heroes.v1/rule.damage/rolled-damage) to a creature while hidden.
type: ability
---

```ds-feature
cost: 9 Focus
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: If the target of the triggering ability is not a leader or solo creature, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina). If the target of the triggering ability is a minion, the entire squad is killed. If the target of the triggering ability is a leader or solo creature, the triggering ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) automatically obtains a tier 3 outcome.
feature_type: ability
flavor: You direct your ally to make a killing blow.
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
    class: tactician
    cost: 9 Focus
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: If the target of the triggering ability is not a leader or solo creature, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina). If the target of the triggering ability is a minion, the entire squad is killed. If the target of the triggering ability is a leader or solo creature, the triggering ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) automatically obtains a tier 3 outcome.
    flavor: You direct your ally to make a killing blow.
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "6"
    name: Coordinated Execution
    scc: mcdm.heroes.v1/feature.ability.tactician.level-6/coordinated-execution
    subclass: insurgent
    subtype: triggered
    target: One ally
    trigger: The target uses an ability to deal [rolled damage](scc.v1:mcdm.heroes.v1/rule.damage/rolled-damage) to a creature while hidden.
    type: ability
name: Coordinated Execution
target: One ally
trigger: The target uses an ability to deal [rolled damage](scc.v1:mcdm.heroes.v1/rule.damage/rolled-damage) to a creature while hidden.
type: feature
usage: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
```
