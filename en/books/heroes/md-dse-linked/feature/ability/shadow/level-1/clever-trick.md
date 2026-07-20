---
action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
class: shadow
cost: 1 Insight
cost_amount: "1"
cost_resource: Insight
distance: Self
effect: Choose an enemy within [distance](../../../../rule/combat/distance.md) of the triggering strike, including the enemy who targeted you. The [strike](../../../../rule/combat/strike.md) targets that enemy instead.
feature_type: ability
file_basename: clever-trick
file_dpath: feature/ability/shadow/level-1
flavor: You sow a moment of confusion in combat, to your enemy's peril.
item_id: clever-trick
item_name: Clever Trick
keywords:
    - Magic
level: "1"
name: Clever Trick
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/clever-trick
source: mcdm.heroes.v1
subclass: harlequin-mask
subtype: triggered
target: Self
trigger: An enemy targets you with a [strike](../../../../rule/combat/strike.md).
type: ability
---

```ds-feature
cost: 1 Insight
distance: Self
effects:
    - effect: Choose an enemy within [distance](../../../../rule/combat/distance.md) of the triggering strike, including the enemy who targeted you. The [strike](../../../../rule/combat/strike.md) targets that enemy instead.
feature_type: ability
flavor: You sow a moment of confusion in combat, to your enemy's peril.
keywords:
    - Magic
metadata:
    action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
    class: shadow
    cost: 1 Insight
    distance: Self
    effect: Choose an enemy within [distance](../../../../rule/combat/distance.md) of the triggering strike, including the enemy who targeted you. The [strike](../../../../rule/combat/strike.md) targets that enemy instead.
    flavor: You sow a moment of confusion in combat, to your enemy's peril.
    keywords:
        - Magic
    level: "1"
    name: Clever Trick
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/clever-trick
    subclass: harlequin-mask
    subtype: triggered
    target: Self
    trigger: An enemy targets you with a [strike](../../../../rule/combat/strike.md).
    type: ability
name: Clever Trick
target: Self
trigger: An enemy targets you with a [strike](../../../../rule/combat/strike.md).
type: feature
usage: '[Triggered](../../../../rule/combat/triggered-action.md)'
```
