---
action_type: Main action
distance: '[Melee](../../../rule/combat/melee.md) 1'
effect: If the target dealt damage to you since the end of your last [turn](../../../rule/combat/turn.md), this [strike](../../../rule/combat/strike.md) deals additional damage equal to your [Might](../../../rule/character/might.md) or [Agility](../../../rule/character/agility.md) score (your choice).
feature_type: ability
file_basename: pain-for-pain
file_dpath: feature/ability/mountain
flavor: An enemy who tagged you will pay for that.
item_id: pain-for-pain
item_name: Pain for Pain
keywords:
    - '[Melee](../../../rule/combat/melee.md)'
    - '[Strike](../../../rule/combat/strike.md)'
    - Weapon
kit: mountain
name: Pain for Pain
power_roll_characteristic: '[Might](../../../rule/character/might.md) or [Agility](../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.mountain/pain-for-pain
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 3 + M or A damage
tier2: 5 + M or A damage
tier3: 13 + M or A damage
type: ability
---

```ds-feature
distance: '[Melee](../../../rule/combat/melee.md) 1'
effects:
    - effect: If the target dealt damage to you since the end of your last [turn](../../../rule/combat/turn.md), this [strike](../../../rule/combat/strike.md) deals additional damage equal to your [Might](../../../rule/character/might.md) or [Agility](../../../rule/character/agility.md) score (your choice).
    - roll: Power Roll + [Might](../../../rule/character/might.md) or [Agility](../../../rule/character/agility.md)
      tier1: 3 + M or A damage
      tier2: 5 + M or A damage
      tier3: 13 + M or A damage
feature_type: ability
flavor: An enemy who tagged you will pay for that.
keywords:
    - '[Melee](../../../rule/combat/melee.md)'
    - '[Strike](../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](../../../rule/combat/melee.md) 1'
    effect: If the target dealt damage to you since the end of your last [turn](../../../rule/combat/turn.md), this [strike](../../../rule/combat/strike.md) deals additional damage equal to your [Might](../../../rule/character/might.md) or [Agility](../../../rule/character/agility.md) score (your choice).
    flavor: An enemy who tagged you will pay for that.
    keywords:
        - '[Melee](../../../rule/combat/melee.md)'
        - '[Strike](../../../rule/combat/strike.md)'
        - Weapon
    kit: mountain
    name: Pain for Pain
    power_roll_characteristic: '[Might](../../../rule/character/might.md) or [Agility](../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.mountain/pain-for-pain
    subtype: signature
    target: One creature
    tier1: 3 + M or A damage
    tier2: 5 + M or A damage
    tier3: 13 + M or A damage
    type: ability
name: Pain for Pain
target: One creature
type: feature
usage: Main action
```
