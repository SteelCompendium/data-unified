---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 9 Clarity
cost_amount: "9"
cost_resource: Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: You target a number of creatures with this ability determined by the outcome of your [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll). You and your allies are invisible to each target until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Effect
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: Two creatures
      tier2: Three creatures
      tier3: Five creatures
    - effect: The effect ends early if you take damage from an enemy's ability.
      name: Strained
feature_type: ability
file_basename: synaptic-dissipation
file_dpath: feature/ability/talent/level-6
flavor: You manipulate your enemies' minds and make them wonder if you were ever really there in the first place.
item_id: synaptic-dissipation
item_name: Synaptic Dissipation
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Telepathy
level: "6"
name: Synaptic Dissipation
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-6/synaptic-dissipation
source: mcdm.heroes.v1
subclass: telepathy
target: Special
tier1: Two creatures
tier2: Three creatures
tier3: Five creatures
type: ability
---

```ds-feature
cost: 9 Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: You target a number of creatures with this ability determined by the outcome of your [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll). You and your allies are invisible to each target until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Effect
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: Two creatures
      tier2: Three creatures
      tier3: Five creatures
    - effect: The effect ends early if you take damage from an enemy's ability.
      name: Strained
feature_type: ability
flavor: You manipulate your enemies' minds and make them wonder if you were ever really there in the first place.
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Telepathy
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: talent
    cost: 9 Clarity
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - effect: You target a number of creatures with this ability determined by the outcome of your [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll). You and your allies are invisible to each target until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
          name: Effect
        - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
          tier1: Two creatures
          tier2: Three creatures
          tier3: Five creatures
        - effect: The effect ends early if you take damage from an enemy's ability.
          name: Strained
    flavor: You manipulate your enemies' minds and make them wonder if you were ever really there in the first place.
    keywords:
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Telepathy
    level: "6"
    name: Synaptic Dissipation
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-6/synaptic-dissipation
    subclass: telepathy
    target: Special
    tier1: Two creatures
    tier2: Three creatures
    tier3: Five creatures
    type: ability
name: Synaptic Dissipation
target: Special
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
