---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 5 Wrath
cost_amount: "5"
cost_resource: Wrath
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effect: Each target takes holy damage equal to twice your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score. Additionally, each hidden target is automatically revealed and can't become hidden again until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). You can then use your [Judgment](scc.v1:mcdm.heroes.v1/feature.ability.censor.level-1/judgment) ability against one target as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action).
feature_type: ability
file_basename: revelator
file_dpath: feature/ability/censor/level-2
flavor: You channel holy energy to harm unbelievers and reveal those hidden from your [judgment](scc.v1:mcdm.heroes.v1/feature.ability.censor.level-1/judgment).
item_id: revelator
item_name: Revelator
keywords:
    - Area
    - Magic
level: "2"
name: Revelator
scc: mcdm.heroes.v1/feature.ability.censor.level-2/revelator
source: mcdm.heroes.v1
subclass: exorcist
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 5 Wrath
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: Each target takes holy damage equal to twice your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score. Additionally, each hidden target is automatically revealed and can't become hidden again until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). You can then use your [Judgment](scc.v1:mcdm.heroes.v1/feature.ability.censor.level-1/judgment) ability against one target as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action).
feature_type: ability
flavor: You channel holy energy to harm unbelievers and reveal those hidden from your [judgment](scc.v1:mcdm.heroes.v1/feature.ability.censor.level-1/judgment).
keywords:
    - Area
    - Magic
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: censor
    cost: 5 Wrath
    distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effect: Each target takes holy damage equal to twice your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score. Additionally, each hidden target is automatically revealed and can't become hidden again until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). You can then use your [Judgment](scc.v1:mcdm.heroes.v1/feature.ability.censor.level-1/judgment) ability against one target as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action).
    flavor: You channel holy energy to harm unbelievers and reveal those hidden from your [judgment](scc.v1:mcdm.heroes.v1/feature.ability.censor.level-1/judgment).
    keywords:
        - Area
        - Magic
    level: "2"
    name: Revelator
    scc: mcdm.heroes.v1/feature.ability.censor.level-2/revelator
    subclass: exorcist
    target: Each enemy in the area
    type: ability
name: Revelator
target: Each enemy in the area
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
