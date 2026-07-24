---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: tactician
cost: 5 Focus
cost_amount: "5"
cost_resource: Focus
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: Each target is marked by you, and must immediately make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a creature of your choice within 5 squares of them.
      name: Effect
    - effect: Until the end of the encounter, whenever you or any ally makes a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) against a creature marked by you, you can spend 2 focus to force that target to make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a creature of your choice within 5 squares of them.
      name: Mark Benefit
feature_type: ability
file_basename: fog-of-war
file_dpath: feature/ability/tactician/level-2
flavor: Your unorthodox strategy causes enemies to lash out in fear, heedless of who they might be attacking.
item_id: fog-of-war
item_name: Fog of War
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "2"
name: Fog of War
scc: mcdm.heroes.v1/feature.ability.tactician.level-2/fog-of-war
source: mcdm.heroes.v1
subclass: insurgent
target: Two creatures
type: ability
---

```ds-feature
cost: 5 Focus
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: Each target is marked by you, and must immediately make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a creature of your choice within 5 squares of them.
      name: Effect
    - effect: Until the end of the encounter, whenever you or any ally makes a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) against a creature marked by you, you can spend 2 focus to force that target to make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a creature of your choice within 5 squares of them.
      name: Mark Benefit
feature_type: ability
flavor: Your unorthodox strategy causes enemies to lash out in fear, heedless of who they might be attacking.
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: tactician
    cost: 5 Focus
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - effect: Each target is marked by you, and must immediately make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a creature of your choice within 5 squares of them.
          name: Effect
        - effect: Until the end of the encounter, whenever you or any ally makes a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) against a creature marked by you, you can spend 2 focus to force that target to make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a creature of your choice within 5 squares of them.
          name: Mark Benefit
    flavor: Your unorthodox strategy causes enemies to lash out in fear, heedless of who they might be attacking.
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "2"
    name: Fog of War
    scc: mcdm.heroes.v1/feature.ability.tactician.level-2/fog-of-war
    subclass: insurgent
    target: Two creatures
    type: ability
name: Fog of War
target: Two creatures
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
