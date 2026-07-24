---
action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
class: tactician
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: At any time during the target's movement, one ally can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them.
      name: Effect
    - cost: Spend 1 Focus
      effect: If the target has R < AVERAGE, they are [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)).
feature_type: ability
file_basename: overwatch
file_dpath: feature/ability/tactician/level-1
flavor: Under your direction, an ally waits for just the right moment to strike.
item_id: overwatch
item_name: Overwatch
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Overwatch
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/overwatch
source: mcdm.heroes.v1
subclass: mastermind
subtype: triggered
target: One creature
trigger: The target moves.
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: At any time during the target's movement, one ally can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them.
      name: Effect
    - cost: Spend 1 Focus
      effect: If the target has R < AVERAGE, they are [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)).
feature_type: ability
flavor: Under your direction, an ally waits for just the right moment to strike.
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
    class: tactician
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - effect: At any time during the target's movement, one ally can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them.
          name: Effect
        - cost: Spend 1 Focus
          effect: If the target has R < AVERAGE, they are [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)).
    flavor: Under your direction, an ally waits for just the right moment to strike.
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Overwatch
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/overwatch
    subclass: mastermind
    subtype: triggered
    target: One creature
    trigger: The target moves.
    type: ability
name: Overwatch
target: One creature
trigger: The target moves.
type: feature
usage: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
```
