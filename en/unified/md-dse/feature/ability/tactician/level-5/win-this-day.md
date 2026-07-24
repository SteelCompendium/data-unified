---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: tactician
cost: 9 Focus
cost_amount: "9"
cost_resource: Focus
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: Each target gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge). Additionally, they can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries), remove any [conditions](scc.v1:mcdm.heroes.v1/rule.combat/condition) or effects on them, and stand up if they [are prone](scc.v1:mcdm.heroes.v1/condition/prone).
      name: Effect
feature_type: ability
file_basename: win-this-day
file_dpath: feature/ability/tactician/level-5
flavor: You inspire your allies to recover and gather their strength.
item_id: win-this-day
item_name: Win This Day!
keywords:
    - Area
level: "5"
name: Win This Day!
scc: mcdm.heroes.v1/feature.ability.tactician.level-5/win-this-day
source: mcdm.heroes.v1
target: Self and each ally in the area
type: ability
---

```ds-feature
cost: 9 Focus
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: Each target gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge). Additionally, they can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries), remove any [conditions](scc.v1:mcdm.heroes.v1/rule.combat/condition) or effects on them, and stand up if they [are prone](scc.v1:mcdm.heroes.v1/condition/prone).
      name: Effect
feature_type: ability
flavor: You inspire your allies to recover and gather their strength.
keywords:
    - Area
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: tactician
    cost: 9 Focus
    distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effects:
        - effect: Each target gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge). Additionally, they can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries), remove any [conditions](scc.v1:mcdm.heroes.v1/rule.combat/condition) or effects on them, and stand up if they [are prone](scc.v1:mcdm.heroes.v1/condition/prone).
          name: Effect
    flavor: You inspire your allies to recover and gather their strength.
    keywords:
        - Area
    level: "5"
    name: Win This Day!
    scc: mcdm.heroes.v1/feature.ability.tactician.level-5/win-this-day
    target: Self and each ally in the area
    type: ability
name: Win This Day!
target: Self and each ally in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
