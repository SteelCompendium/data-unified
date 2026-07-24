---
action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
class: censor
cost: 11 Wrath
cost_amount: "11"
cost_resource: Wrath
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target obtains a tier 1 or tier 3 outcome on their [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) (your choice). You can then choose another target within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance), who obtains the opposite outcome on their next [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
      name: Effect
feature_type: ability
file_basename: blessing-and-a-curse
file_dpath: feature/ability/censor/level-9
flavor: The gods bless and damn in equal measure.
item_id: blessing-and-a-curse
item_name: Blessing and a Curse
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "9"
name: Blessing and a Curse
scc: mcdm.heroes.v1/feature.ability.censor.level-9/blessing-and-a-curse
source: mcdm.heroes.v1
subclass: oracle
subtype: triggered
target: One creature
trigger: The target makes a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
type: ability
---

```ds-feature
cost: 11 Wrath
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target obtains a tier 1 or tier 3 outcome on their [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) (your choice). You can then choose another target within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance), who obtains the opposite outcome on their next [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
      name: Effect
feature_type: ability
flavor: The gods bless and damn in equal measure.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
    class: censor
    cost: 11 Wrath
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - effect: The target obtains a tier 1 or tier 3 outcome on their [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) (your choice). You can then choose another target within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance), who obtains the opposite outcome on their next [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
          name: Effect
    flavor: The gods bless and damn in equal measure.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "9"
    name: Blessing and a Curse
    scc: mcdm.heroes.v1/feature.ability.censor.level-9/blessing-and-a-curse
    subclass: oracle
    subtype: triggered
    target: One creature
    trigger: The target makes a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    type: ability
name: Blessing and a Curse
target: One creature
trigger: The target makes a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
type: feature
usage: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
```
