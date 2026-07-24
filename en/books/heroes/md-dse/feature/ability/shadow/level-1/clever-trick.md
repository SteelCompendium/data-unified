---
action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
class: shadow
cost: 1 Insight
cost_amount: "1"
cost_resource: Insight
distance: Self
effects:
    - effect: Choose an enemy within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) of the triggering strike, including the enemy who targeted you. The [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) targets that enemy instead.
      name: Effect
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
trigger: An enemy targets you with a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
type: ability
---

```ds-feature
cost: 1 Insight
distance: Self
effects:
    - effect: Choose an enemy within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) of the triggering strike, including the enemy who targeted you. The [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) targets that enemy instead.
      name: Effect
feature_type: ability
flavor: You sow a moment of confusion in combat, to your enemy's peril.
keywords:
    - Magic
metadata:
    action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
    class: shadow
    cost: 1 Insight
    distance: Self
    effects:
        - effect: Choose an enemy within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) of the triggering strike, including the enemy who targeted you. The [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) targets that enemy instead.
          name: Effect
    flavor: You sow a moment of confusion in combat, to your enemy's peril.
    keywords:
        - Magic
    level: "1"
    name: Clever Trick
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/clever-trick
    subclass: harlequin-mask
    subtype: triggered
    target: Self
    trigger: An enemy targets you with a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
    type: ability
name: Clever Trick
target: Self
trigger: An enemy targets you with a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
type: feature
usage: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
```
