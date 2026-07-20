---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: conduit
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: Choose yourself or one ally within [distance](../../../../rule/combat/distance.md). That character can impose a [bane](../../../../rule/dice/bane.md) on one [power roll](../../../../rule/dice/power-roll.md) made against them before the end of their next [turn](../../../../rule/combat/turn.md).
feature_type: ability
file_basename: sacrificial-offer
file_dpath: feature/ability/conduit/level-1
flavor: Divine magic tears at your foe and defends a nearby friend.
item_id: sacrificial-offer
item_name: Sacrificial Offer
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
level: "1"
name: Sacrificial Offer
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/sacrificial-offer
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 2 + I corruption damage
tier2: 4 + I corruption damage
tier3: 6 + I corruption damage
type: ability
---

```ds-feature
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: Choose yourself or one ally within [distance](../../../../rule/combat/distance.md). That character can impose a [bane](../../../../rule/dice/bane.md) on one [power roll](../../../../rule/dice/power-roll.md) made against them before the end of their next [turn](../../../../rule/combat/turn.md).
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 2 + I corruption damage
      tier2: 4 + I corruption damage
      tier3: 6 + I corruption damage
feature_type: ability
flavor: Divine magic tears at your foe and defends a nearby friend.
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: conduit
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: Choose yourself or one ally within [distance](../../../../rule/combat/distance.md). That character can impose a [bane](../../../../rule/dice/bane.md) on one [power roll](../../../../rule/dice/power-roll.md) made against them before the end of their next [turn](../../../../rule/combat/turn.md).
    flavor: Divine magic tears at your foe and defends a nearby friend.
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
    level: "1"
    name: Sacrificial Offer
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/sacrificial-offer
    subtype: signature
    target: One creature
    tier1: 2 + I corruption damage
    tier2: 4 + I corruption damage
    tier3: 6 + I corruption damage
    type: ability
name: Sacrificial Offer
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
