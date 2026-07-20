---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: conduit
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: One ally within [distance](../../../../rule/combat/distance.md) gains a number of [surges](../../../../rule/resource/surge.md) equal to the [tier outcome](../../../../rule/dice/tier-outcome.md) of your [power roll](../../../../rule/dice/power-roll.md).
feature_type: ability
file_basename: blessed-light
file_dpath: feature/ability/conduit/level-1
flavor: Burning radiance falls upon your foe, transferring some of their energy to a nearby ally.
item_id: blessed-light
item_name: Blessed Light
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
level: "1"
name: Blessed Light
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/blessed-light
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 3 + I holy damage
tier2: 5 + I holy damage
tier3: 8 + I holy damage
type: ability
---

```ds-feature
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: One ally within [distance](../../../../rule/combat/distance.md) gains a number of [surges](../../../../rule/resource/surge.md) equal to the [tier outcome](../../../../rule/dice/tier-outcome.md) of your [power roll](../../../../rule/dice/power-roll.md).
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 3 + I holy damage
      tier2: 5 + I holy damage
      tier3: 8 + I holy damage
feature_type: ability
flavor: Burning radiance falls upon your foe, transferring some of their energy to a nearby ally.
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: conduit
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: One ally within [distance](../../../../rule/combat/distance.md) gains a number of [surges](../../../../rule/resource/surge.md) equal to the [tier outcome](../../../../rule/dice/tier-outcome.md) of your [power roll](../../../../rule/dice/power-roll.md).
    flavor: Burning radiance falls upon your foe, transferring some of their energy to a nearby ally.
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
    level: "1"
    name: Blessed Light
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/blessed-light
    subtype: signature
    target: One creature or object
    tier1: 3 + I holy damage
    tier2: 5 + I holy damage
    tier3: 8 + I holy damage
    type: ability
name: Blessed Light
target: One creature or object
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
