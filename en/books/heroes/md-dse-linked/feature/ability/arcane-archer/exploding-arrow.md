---
action_type: Main action
distance: '[Ranged](../../../rule/combat/ranged.md) 15'
effect: One creature or object of your choice within 2 squares of the target takes fire damage equal to the [characteristic](../../../rule/character/characteristic.md) score used for this ability's [power roll](../../../rule/dice/power-roll.md).
feature_type: ability
file_basename: exploding-arrow
file_dpath: feature/ability/arcane-archer
flavor: Your ammunition explodes with magical energy.
item_id: exploding-arrow
item_name: Exploding Arrow
keywords:
    - Magic
    - '[Ranged](../../../rule/combat/ranged.md)'
    - '[Strike](../../../rule/combat/strike.md)'
    - Weapon
kit: arcane-archer
name: Exploding Arrow
power_roll_characteristic: '[Agility](../../../rule/character/agility.md), [Reason](../../../rule/character/reason.md), [Intuition](../../../rule/character/intuition.md), or [Presence](../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.arcane-archer/exploding-arrow
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 5 + A, R, I, or P fire damage
tier2: 7 + A, R, I, or P fire damage
tier3: 10 + A, R, I, or P fire damage
type: ability
---

```ds-feature
distance: '[Ranged](../../../rule/combat/ranged.md) 15'
effects:
    - effect: One creature or object of your choice within 2 squares of the target takes fire damage equal to the [characteristic](../../../rule/character/characteristic.md) score used for this ability's [power roll](../../../rule/dice/power-roll.md).
    - roll: Power Roll + [Agility](../../../rule/character/agility.md), [Reason](../../../rule/character/reason.md), [Intuition](../../../rule/character/intuition.md), or [Presence](../../../rule/character/presence.md)
      tier1: 5 + A, R, I, or P fire damage
      tier2: 7 + A, R, I, or P fire damage
      tier3: 10 + A, R, I, or P fire damage
feature_type: ability
flavor: Your ammunition explodes with magical energy.
keywords:
    - Magic
    - '[Ranged](../../../rule/combat/ranged.md)'
    - '[Strike](../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Ranged](../../../rule/combat/ranged.md) 15'
    effect: One creature or object of your choice within 2 squares of the target takes fire damage equal to the [characteristic](../../../rule/character/characteristic.md) score used for this ability's [power roll](../../../rule/dice/power-roll.md).
    flavor: Your ammunition explodes with magical energy.
    keywords:
        - Magic
        - '[Ranged](../../../rule/combat/ranged.md)'
        - '[Strike](../../../rule/combat/strike.md)'
        - Weapon
    kit: arcane-archer
    name: Exploding Arrow
    power_roll_characteristic: '[Agility](../../../rule/character/agility.md), [Reason](../../../rule/character/reason.md), [Intuition](../../../rule/character/intuition.md), or [Presence](../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.arcane-archer/exploding-arrow
    subtype: signature
    target: One creature or object
    tier1: 5 + A, R, I, or P fire damage
    tier2: 7 + A, R, I, or P fire damage
    tier3: 10 + A, R, I, or P fire damage
    type: ability
name: Exploding Arrow
target: One creature or object
type: feature
usage: Main action
```
