---
action_type: Main action
class: shadow
cost: 9 Insight
cost_amount: "9"
cost_resource: Insight
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: You ready, hand, or lob a potion to each target, who can immediately quaff the potion (no action required). If they don't drink the potion right away, they must use the [Use Consumable](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/use-consumable) maneuver to consume it later. The potion loses its [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) at the end of the encounter.
feature_type: ability
file_basename: one-vial-makes-you-faster
file_dpath: feature/ability/shadow/level-6
flavor: Each ally who catches a potion you throw can take the battle to the next level.
item_id: one-vial-makes-you-faster
item_name: One Vial Makes You Faster
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "6"
name: One Vial Makes You Faster
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-6/one-vial-makes-you-faster
source: mcdm.heroes.v1
target: Three creatures
tier1: The creature's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is increased by 2 until the end of the encounter.
tier2: The creature can [fly](scc.v1:mcdm.heroes.v1/movement/fly) until the end of the encounter.
tier3: The creature [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn) invisible until the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
type: ability
---

```ds-feature
cost: 9 Insight
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: You ready, hand, or lob a potion to each target, who can immediately quaff the potion (no action required). If they don't drink the potion right away, they must use the [Use Consumable](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/use-consumable) maneuver to consume it later. The potion loses its [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) at the end of the encounter.
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: The creature's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is increased by 2 until the end of the encounter.
      tier2: The creature can [fly](scc.v1:mcdm.heroes.v1/movement/fly) until the end of the encounter.
      tier3: The creature [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn) invisible until the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
feature_type: ability
flavor: Each ally who catches a potion you throw can take the battle to the next level.
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Main action
    class: shadow
    cost: 9 Insight
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: You ready, hand, or lob a potion to each target, who can immediately quaff the potion (no action required). If they don't drink the potion right away, they must use the [Use Consumable](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/use-consumable) maneuver to consume it later. The potion loses its [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) at the end of the encounter.
    flavor: Each ally who catches a potion you throw can take the battle to the next level.
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "6"
    name: One Vial Makes You Faster
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-6/one-vial-makes-you-faster
    target: Three creatures
    tier1: The creature's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is increased by 2 until the end of the encounter.
    tier2: The creature can [fly](scc.v1:mcdm.heroes.v1/movement/fly) until the end of the encounter.
    tier3: The creature [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn) invisible until the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    type: ability
name: One Vial Makes You Faster
target: Three creatures
type: feature
usage: Main action
```
