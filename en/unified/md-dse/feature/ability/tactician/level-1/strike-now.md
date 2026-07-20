---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: tactician
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: The target can use a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action).
feature_type: ability
file_basename: strike-now
file_dpath: feature/ability/tactician/level-1
flavor: Your foe left an opening. You point this out to an ally!
item_id: strike-now
item_name: '"Strike Now!"'
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: '"Strike Now!"'
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/strike-now
source: mcdm.heroes.v1
spend: '5 Focus: You target two allies instead of one.'
target: One ally
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target can use a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action).
    - effect: '5 Focus: You target two allies instead of one.'
      name: Spend
feature_type: ability
flavor: Your foe left an opening. You point this out to an ally!
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: tactician
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: The target can use a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action).
    flavor: Your foe left an opening. You point this out to an ally!
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: '"Strike Now!"'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/strike-now
    spend: '5 Focus: You target two allies instead of one.'
    target: One ally
    type: ability
name: '"Strike Now!"'
target: One ally
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
