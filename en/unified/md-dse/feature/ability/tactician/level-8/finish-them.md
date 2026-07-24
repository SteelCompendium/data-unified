---
action_type: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
class: tactician
cost: 11 Focus
cost_amount: "11"
cost_resource: Focus
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target is killed. Additionally, the creature who caused the target to be [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
      name: Effect
feature_type: ability
file_basename: finish-them
file_dpath: feature/ability/tactician/level-8
flavor: You point out an opening to your ally so they can land a killing blow.
item_id: finish-them
item_name: Finish Them!
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "8"
name: Finish Them!
scc: mcdm.heroes.v1/feature.ability.tactician.level-8/finish-them
source: mcdm.heroes.v1
subtype: triggered
target: One creature
trigger: The target is not a leader or solo creature, and becomes [winded](scc.v1:mcdm.heroes.v1/rule.health/winded).
type: ability
---

```ds-feature
cost: 11 Focus
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target is killed. Additionally, the creature who caused the target to be [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
      name: Effect
feature_type: ability
flavor: You point out an opening to your ally so they can land a killing blow.
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
    class: tactician
    cost: 11 Focus
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - effect: The target is killed. Additionally, the creature who caused the target to be [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
          name: Effect
    flavor: You point out an opening to your ally so they can land a killing blow.
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "8"
    name: Finish Them!
    scc: mcdm.heroes.v1/feature.ability.tactician.level-8/finish-them
    subtype: triggered
    target: One creature
    trigger: The target is not a leader or solo creature, and becomes [winded](scc.v1:mcdm.heroes.v1/rule.health/winded).
    type: ability
name: Finish Them!
target: One creature
trigger: The target is not a leader or solo creature, and becomes [winded](scc.v1:mcdm.heroes.v1/rule.health/winded).
type: feature
usage: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
```
