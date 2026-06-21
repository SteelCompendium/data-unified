---
action_type: Free triggered
class: shadow
cost: 5 Insight
cost_amount: "5"
cost_resource: Insight
distance: Self; see below
effect: You ignore any effects associated with the damage that triggered your [In All This Confusion](scc.v1:mcdm.heroes.v1/feature.ability.shadow.level-1/in-all-this-confusion) ability. Before you [teleport](scc.v1:mcdm.heroes.v1/movement/teleport), you can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a creature who damaged you to trigger [In All This Confusion](scc.v1:mcdm.heroes.v1/feature.ability.shadow.level-1/in-all-this-confusion). After you [teleport](scc.v1:mcdm.heroes.v1/movement/teleport), you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
file_basename: too-slow
file_dpath: feature/ability/shadow/level-2
flavor: Your foe made a big mistake.
item_id: too-slow
item_name: Too Slow
keywords:
    - '-'
level: "2"
name: Too Slow
scc: mcdm.heroes.v1/feature.ability.shadow.level-2/too-slow
source: mcdm.heroes.v1
subtype: triggered
target: Self
trigger: You use your [In All This Confusion](scc.v1:mcdm.heroes.v1/feature.ability.shadow.level-1/in-all-this-confusion) ability.
type: ability
---

```ds-feature
cost: 5 Insight
distance: Self; see below
effects:
    - effect: You ignore any effects associated with the damage that triggered your [In All This Confusion](scc.v1:mcdm.heroes.v1/feature.ability.shadow.level-1/in-all-this-confusion) ability. Before you [teleport](scc.v1:mcdm.heroes.v1/movement/teleport), you can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a creature who damaged you to trigger [In All This Confusion](scc.v1:mcdm.heroes.v1/feature.ability.shadow.level-1/in-all-this-confusion). After you [teleport](scc.v1:mcdm.heroes.v1/movement/teleport), you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
flavor: Your foe made a big mistake.
keywords:
    - '-'
metadata:
    action_type: Free triggered
    class: shadow
    cost: 5 Insight
    distance: Self; see below
    effect: You ignore any effects associated with the damage that triggered your [In All This Confusion](scc.v1:mcdm.heroes.v1/feature.ability.shadow.level-1/in-all-this-confusion) ability. Before you [teleport](scc.v1:mcdm.heroes.v1/movement/teleport), you can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a creature who damaged you to trigger [In All This Confusion](scc.v1:mcdm.heroes.v1/feature.ability.shadow.level-1/in-all-this-confusion). After you [teleport](scc.v1:mcdm.heroes.v1/movement/teleport), you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    flavor: Your foe made a big mistake.
    keywords:
        - '-'
    level: "2"
    name: Too Slow
    scc: mcdm.heroes.v1/feature.ability.shadow.level-2/too-slow
    subtype: triggered
    target: Self
    trigger: You use your [In All This Confusion](scc.v1:mcdm.heroes.v1/feature.ability.shadow.level-1/in-all-this-confusion) ability.
    type: ability
name: Too Slow
target: Self
trigger: You use your [In All This Confusion](scc.v1:mcdm.heroes.v1/feature.ability.shadow.level-1/in-all-this-confusion) ability.
type: feature
usage: Free triggered
```
