---
action_type: Main action
distance: '[Melee](../../../rule/combat/melee.md) 1'
effect: The target is [taunted](../../../condition/taunted.md) until the end of their next [turn](../../../rule/combat/turn.md).
feature_type: ability
file_basename: protective-attack
file_dpath: feature/ability/shining-armor
flavor: The strength of your assault makes it impossible for your foe to ignore you.
item_id: protective-attack
item_name: Protective Attack
keywords:
    - '[Melee](../../../rule/combat/melee.md)'
    - '[Strike](../../../rule/combat/strike.md)'
    - Weapon
kit: shining-armor
name: Protective Attack
power_roll_characteristic: '[Might](../../../rule/character/might.md) or [Agility](../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.shining-armor/protective-attack
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 5 + M or A damage
tier2: 8 + M or A damage
tier3: 11 + M or A damage
type: ability
---

```ds-feature
distance: '[Melee](../../../rule/combat/melee.md) 1'
effects:
    - effect: The target is [taunted](../../../condition/taunted.md) until the end of their next [turn](../../../rule/combat/turn.md).
    - roll: Power Roll + [Might](../../../rule/character/might.md) or [Agility](../../../rule/character/agility.md)
      tier1: 5 + M or A damage
      tier2: 8 + M or A damage
      tier3: 11 + M or A damage
feature_type: ability
flavor: The strength of your assault makes it impossible for your foe to ignore you.
keywords:
    - '[Melee](../../../rule/combat/melee.md)'
    - '[Strike](../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](../../../rule/combat/melee.md) 1'
    effect: The target is [taunted](../../../condition/taunted.md) until the end of their next [turn](../../../rule/combat/turn.md).
    flavor: The strength of your assault makes it impossible for your foe to ignore you.
    keywords:
        - '[Melee](../../../rule/combat/melee.md)'
        - '[Strike](../../../rule/combat/strike.md)'
        - Weapon
    kit: shining-armor
    name: Protective Attack
    power_roll_characteristic: '[Might](../../../rule/character/might.md) or [Agility](../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.shining-armor/protective-attack
    subtype: signature
    target: One creature
    tier1: 5 + M or A damage
    tier2: 8 + M or A damage
    tier3: 11 + M or A damage
    type: ability
name: Protective Attack
target: One creature
type: feature
usage: Main action
```
