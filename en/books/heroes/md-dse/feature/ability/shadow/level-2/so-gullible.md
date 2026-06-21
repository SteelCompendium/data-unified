---
action_type: Free triggered
class: shadow
cost: 5 Insight
cost_amount: "5"
cost_resource: Insight
distance: Self
effect: You use your [Clever Trick](scc.v1:mcdm.heroes.v1/feature.ability.shadow.level-1/clever-trick) ability with no insight cost against the triggering creature and strike. You can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to an unoccupied space within 3 squares of that creature and can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them. You can then spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
file_basename: so-gullible
file_dpath: feature/ability/shadow/level-2
flavor: When your enemy strikes, you reveal you were in a different place all along.
item_id: so-gullible
item_name: So Gullible
keywords:
    - Magic
level: "2"
name: So Gullible
scc: mcdm.heroes.v1/feature.ability.shadow.level-2/so-gullible
source: mcdm.heroes.v1
subtype: triggered
target: Self
trigger: Another creature targets you with a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
type: ability
---

```ds-feature
cost: 5 Insight
distance: Self
effects:
    - effect: You use your [Clever Trick](scc.v1:mcdm.heroes.v1/feature.ability.shadow.level-1/clever-trick) ability with no insight cost against the triggering creature and strike. You can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to an unoccupied space within 3 squares of that creature and can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them. You can then spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
flavor: When your enemy strikes, you reveal you were in a different place all along.
keywords:
    - Magic
metadata:
    action_type: Free triggered
    class: shadow
    cost: 5 Insight
    distance: Self
    effect: You use your [Clever Trick](scc.v1:mcdm.heroes.v1/feature.ability.shadow.level-1/clever-trick) ability with no insight cost against the triggering creature and strike. You can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to an unoccupied space within 3 squares of that creature and can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them. You can then spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    flavor: When your enemy strikes, you reveal you were in a different place all along.
    keywords:
        - Magic
    level: "2"
    name: So Gullible
    scc: mcdm.heroes.v1/feature.ability.shadow.level-2/so-gullible
    subtype: triggered
    target: Self
    trigger: Another creature targets you with a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
    type: ability
name: So Gullible
target: Self
trigger: Another creature targets you with a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
type: feature
usage: Free triggered
```
