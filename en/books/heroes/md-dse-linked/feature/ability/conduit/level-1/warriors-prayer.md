---
action_type: Main action
class: conduit
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: You or one ally within [distance](../../../../rule/combat/distance.md) gains [temporary Stamina](../../../../rule/health/temporary-stamina.md) equal to your [Intuition](../../../../rule/character/intuition.md) score.
feature_type: ability
file_basename: warriors-prayer
file_dpath: feature/ability/conduit/level-1
flavor: Your quickly uttered prayer lends aggressive divine energy to a friend engaged in [melee](../../../../rule/combat/melee.md).
item_id: warriors-prayer
item_name: Warrior's Prayer
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
level: "1"
name: Warrior's Prayer
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/warriors-prayer
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 3 + I holy damage
tier2: 6 + I holy damage
tier3: 9 + I holy damage
type: ability
---

```ds-feature
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: You or one ally within [distance](../../../../rule/combat/distance.md) gains [temporary Stamina](../../../../rule/health/temporary-stamina.md) equal to your [Intuition](../../../../rule/character/intuition.md) score.
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 3 + I holy damage
      tier2: 6 + I holy damage
      tier3: 9 + I holy damage
feature_type: ability
flavor: Your quickly uttered prayer lends aggressive divine energy to a friend engaged in [melee](../../../../rule/combat/melee.md).
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: Main action
    class: conduit
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: You or one ally within [distance](../../../../rule/combat/distance.md) gains [temporary Stamina](../../../../rule/health/temporary-stamina.md) equal to your [Intuition](../../../../rule/character/intuition.md) score.
    flavor: Your quickly uttered prayer lends aggressive divine energy to a friend engaged in [melee](../../../../rule/combat/melee.md).
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
    level: "1"
    name: Warrior's Prayer
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/warriors-prayer
    subtype: signature
    target: One creature
    tier1: 3 + I holy damage
    tier2: 6 + I holy damage
    tier3: 9 + I holy damage
    type: ability
name: Warrior's Prayer
target: One creature
type: feature
usage: Main action
```
