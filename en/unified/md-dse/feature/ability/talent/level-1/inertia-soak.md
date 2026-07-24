---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 5 Clarity
cost_amount: "5"
cost_resource: Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target ignores [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) and takes no damage from [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Whenever the target enters a square while under this effect, they can [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) one [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) creature up to a number of squares equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score. When [pushing](scc.v1:mcdm.heroes.v1/movement/forced-movement) an ally, the target can ignore that ally's [stability](scc.v1:mcdm.heroes.v1/rule.character/stability). A creature can only be force moved this way once a [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Effect
    - effect: You are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends). While you are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) this way, whenever you are force moved, the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a +5 [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties).
      name: Strained
feature_type: ability
file_basename: inertia-soak
file_dpath: feature/ability/talent/level-1
flavor: Your psionic energy surrounds the target and pushes everything else away from them.
item_id: inertia-soak
item_name: Inertia Soak
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Telekinesis
level: "1"
name: Inertia Soak
scc: mcdm.heroes.v1/feature.ability.talent.level-1/inertia-soak
source: mcdm.heroes.v1
target: Self or one ally
type: ability
---

```ds-feature
cost: 5 Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target ignores [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) and takes no damage from [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Whenever the target enters a square while under this effect, they can [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) one [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) creature up to a number of squares equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score. When [pushing](scc.v1:mcdm.heroes.v1/movement/forced-movement) an ally, the target can ignore that ally's [stability](scc.v1:mcdm.heroes.v1/rule.character/stability). A creature can only be force moved this way once a [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Effect
    - effect: You are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends). While you are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) this way, whenever you are force moved, the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a +5 [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties).
      name: Strained
feature_type: ability
flavor: Your psionic energy surrounds the target and pushes everything else away from them.
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Telekinesis
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: talent
    cost: 5 Clarity
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - effect: The target ignores [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) and takes no damage from [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Whenever the target enters a square while under this effect, they can [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) one [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) creature up to a number of squares equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score. When [pushing](scc.v1:mcdm.heroes.v1/movement/forced-movement) an ally, the target can ignore that ally's [stability](scc.v1:mcdm.heroes.v1/rule.character/stability). A creature can only be force moved this way once a [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
          name: Effect
        - effect: You are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends). While you are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) this way, whenever you are force moved, the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a +5 [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties).
          name: Strained
    flavor: Your psionic energy surrounds the target and pushes everything else away from them.
    keywords:
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - Telekinesis
    level: "1"
    name: Inertia Soak
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/inertia-soak
    target: Self or one ally
    type: ability
name: Inertia Soak
target: Self or one ally
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
