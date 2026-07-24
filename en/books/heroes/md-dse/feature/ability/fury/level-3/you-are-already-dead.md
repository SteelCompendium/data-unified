---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 7 Ferocity
cost_amount: "7"
cost_resource: Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: If the target is not a leader or solo creature, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) at the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). If the target is a leader or solo creature, you gain 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge) and can make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them.
      name: Effect
feature_type: ability
file_basename: you-are-already-dead
file_dpath: feature/ability/fury/level-3
flavor: Slash. Walk away.
item_id: you-are-already-dead
item_name: You Are Already Dead
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "3"
name: You Are Already Dead
scc: mcdm.heroes.v1/feature.ability.fury.level-3/you-are-already-dead
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 7 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: If the target is not a leader or solo creature, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) at the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). If the target is a leader or solo creature, you gain 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge) and can make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them.
      name: Effect
feature_type: ability
flavor: Slash. Walk away.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: fury
    cost: 7 Ferocity
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - effect: If the target is not a leader or solo creature, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) at the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). If the target is a leader or solo creature, you gain 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge) and can make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them.
          name: Effect
    flavor: Slash. Walk away.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "3"
    name: You Are Already Dead
    scc: mcdm.heroes.v1/feature.ability.fury.level-3/you-are-already-dead
    target: One creature
    type: ability
name: You Are Already Dead
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
