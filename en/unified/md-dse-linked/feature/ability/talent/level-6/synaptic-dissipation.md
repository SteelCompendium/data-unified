---
action_type: Maneuver
class: talent
cost: 9 Clarity
cost_amount: "9"
cost_resource: Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: You target a number of creatures with this ability determined by the outcome of your [power roll](../../../../rule/dice/power-roll.md). You and your allies are invisible to each target until the start of your next [turn](../../../../rule/combat/turn.md).
feature_type: ability
file_basename: synaptic-dissipation
file_dpath: feature/ability/talent/level-6
flavor: You manipulate your enemies' minds and make them wonder if you were ever really there in the first place.
item_id: synaptic-dissipation
item_name: Synaptic Dissipation
keywords:
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Telepathy
level: "6"
name: Synaptic Dissipation
power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-6/synaptic-dissipation
source: mcdm.heroes.v1
target: Special
tier1: Two creatures
tier2: Three creatures
tier3: Five creatures
type: ability
---

```ds-feature
cost: 9 Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: You target a number of creatures with this ability determined by the outcome of your [power roll](../../../../rule/dice/power-roll.md). You and your allies are invisible to each target until the start of your next [turn](../../../../rule/combat/turn.md).
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: Two creatures
      tier2: Three creatures
      tier3: Five creatures
feature_type: ability
flavor: You manipulate your enemies' minds and make them wonder if you were ever really there in the first place.
keywords:
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Telepathy
metadata:
    action_type: Maneuver
    class: talent
    cost: 9 Clarity
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: You target a number of creatures with this ability determined by the outcome of your [power roll](../../../../rule/dice/power-roll.md). You and your allies are invisible to each target until the start of your next [turn](../../../../rule/combat/turn.md).
    flavor: You manipulate your enemies' minds and make them wonder if you were ever really there in the first place.
    keywords:
        - Psionic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Telepathy
    level: "6"
    name: Synaptic Dissipation
    power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-6/synaptic-dissipation
    target: Special
    tier1: Two creatures
    tier2: Three creatures
    tier3: Five creatures
    type: ability
name: Synaptic Dissipation
target: Special
type: feature
usage: Maneuver
```
