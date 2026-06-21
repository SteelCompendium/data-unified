---
action_type: Main action
distance: '[Ranged](../../../rule/combat/ranged.md) 10'
feature_type: ability
file_basename: hamstring-shot
file_dpath: feature/ability/ranger
flavor: A well-placed shot leaves your enemy struggling to move.
item_id: hamstring-shot
item_name: Hamstring Shot
keywords:
    - '[Ranged](../../../rule/combat/ranged.md)'
    - '[Strike](../../../rule/combat/strike.md)'
    - Weapon
kit: ranger
name: Hamstring Shot
power_roll_characteristic: '[Might](../../../rule/character/might.md) or [Agility](../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.ranger/hamstring-shot
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 3 + M or A damage; A < WEAK, [slowed](../../../condition/slowed.md) (save ends)
tier2: 5 + M or A damage; A < AVERAGE, [slowed](../../../condition/slowed.md) (save ends)
tier3: 7 + M or A damage; A < STRONG, [slowed](../../../condition/slowed.md) (save ends)
type: ability
---

```ds-feature
distance: '[Ranged](../../../rule/combat/ranged.md) 10'
effects:
    - roll: Power Roll + [Might](../../../rule/character/might.md) or [Agility](../../../rule/character/agility.md)
      tier1: 3 + M or A damage; A < WEAK, [slowed](../../../condition/slowed.md) (save ends)
      tier2: 5 + M or A damage; A < AVERAGE, [slowed](../../../condition/slowed.md) (save ends)
      tier3: 7 + M or A damage; A < STRONG, [slowed](../../../condition/slowed.md) (save ends)
feature_type: ability
flavor: A well-placed shot leaves your enemy struggling to move.
keywords:
    - '[Ranged](../../../rule/combat/ranged.md)'
    - '[Strike](../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Ranged](../../../rule/combat/ranged.md) 10'
    flavor: A well-placed shot leaves your enemy struggling to move.
    keywords:
        - '[Ranged](../../../rule/combat/ranged.md)'
        - '[Strike](../../../rule/combat/strike.md)'
        - Weapon
    kit: ranger
    name: Hamstring Shot
    power_roll_characteristic: '[Might](../../../rule/character/might.md) or [Agility](../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.ranger/hamstring-shot
    subtype: signature
    target: One creature
    tier1: 3 + M or A damage; A < WEAK, [slowed](../../../condition/slowed.md) (save ends)
    tier2: 5 + M or A damage; A < AVERAGE, [slowed](../../../condition/slowed.md) (save ends)
    tier3: 7 + M or A damage; A < STRONG, [slowed](../../../condition/slowed.md) (save ends)
    type: ability
name: Hamstring Shot
target: One creature
type: feature
usage: Main action
```
