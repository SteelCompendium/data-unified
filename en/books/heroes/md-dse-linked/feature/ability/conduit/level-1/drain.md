---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: conduit
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 2 + I corruption damage
      tier2: 5 + I corruption damage
      tier3: 7 + I corruption damage
    - effect: You or one ally within [distance](../../../../rule/combat/distance.md) can spend a [Recovery](../../../../rule/health/recoveries.md).
      name: Effect
feature_type: ability
file_basename: drain
file_dpath: feature/ability/conduit/level-1
flavor: You drain the energy from your target to revitalize yourself or an ally.
item_id: drain
item_name: Drain
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
level: "1"
name: Drain
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/drain
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 2 + I corruption damage
tier2: 5 + I corruption damage
tier3: 7 + I corruption damage
type: ability
---

```ds-feature
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 2 + I corruption damage
      tier2: 5 + I corruption damage
      tier3: 7 + I corruption damage
    - effect: You or one ally within [distance](../../../../rule/combat/distance.md) can spend a [Recovery](../../../../rule/health/recoveries.md).
      name: Effect
feature_type: ability
flavor: You drain the energy from your target to revitalize yourself or an ally.
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: conduit
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effects:
        - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
          tier1: 2 + I corruption damage
          tier2: 5 + I corruption damage
          tier3: 7 + I corruption damage
        - effect: You or one ally within [distance](../../../../rule/combat/distance.md) can spend a [Recovery](../../../../rule/health/recoveries.md).
          name: Effect
    flavor: You drain the energy from your target to revitalize yourself or an ally.
    keywords:
        - Magic
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
    level: "1"
    name: Drain
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/drain
    subtype: signature
    target: One creature
    tier1: 2 + I corruption damage
    tier2: 5 + I corruption damage
    tier3: 7 + I corruption damage
    type: ability
name: Drain
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
