---
action_type: Free [triggered](../../../../rule/combat/triggered-action.md)
class: tactician
cost: 11 Focus
cost_amount: "11"
cost_resource: Focus
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: The target is killed. Additionally, the creature who caused the target to be [winded](../../../../rule/health/winded.md) can spend a [Recovery](../../../../rule/health/recoveries.md).
      name: Effect
feature_type: ability
file_basename: finish-them
file_dpath: feature/ability/tactician/level-8
flavor: You point out an opening to your ally so they can land a killing blow.
item_id: finish-them
item_name: Finish Them!
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "8"
name: Finish Them!
scc: mcdm.heroes.v1/feature.ability.tactician.level-8/finish-them
source: mcdm.heroes.v1
subtype: triggered
target: One creature
trigger: The target is not a leader or solo creature, and becomes [winded](../../../../rule/health/winded.md).
type: ability
---

```ds-feature
cost: 11 Focus
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: The target is killed. Additionally, the creature who caused the target to be [winded](../../../../rule/health/winded.md) can spend a [Recovery](../../../../rule/health/recoveries.md).
      name: Effect
feature_type: ability
flavor: You point out an opening to your ally so they can land a killing blow.
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: Free [triggered](../../../../rule/combat/triggered-action.md)
    class: tactician
    cost: 11 Focus
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effects:
        - effect: The target is killed. Additionally, the creature who caused the target to be [winded](../../../../rule/health/winded.md) can spend a [Recovery](../../../../rule/health/recoveries.md).
          name: Effect
    flavor: You point out an opening to your ally so they can land a killing blow.
    keywords:
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "8"
    name: Finish Them!
    scc: mcdm.heroes.v1/feature.ability.tactician.level-8/finish-them
    subtype: triggered
    target: One creature
    trigger: The target is not a leader or solo creature, and becomes [winded](../../../../rule/health/winded.md).
    type: ability
name: Finish Them!
target: One creature
trigger: The target is not a leader or solo creature, and becomes [winded](../../../../rule/health/winded.md).
type: feature
usage: Free [triggered](../../../../rule/combat/triggered-action.md)
```
