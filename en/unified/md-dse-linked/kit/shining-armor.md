---
equipment_text: You wear heavy armor and wield a shield and a medium weapon.
file_basename: shining-armor
file_dpath: kit
flavor: The Shining Armor kit provides the most protection a kit can afford, providing you with the sword, shield, and armor necessary to play the prototypical knight.
item_id: shining-armor
item_name: Shining Armor
kit_type: Martial
melee_damage_bonus: +2/+2/+2
name: Shining Armor
scc: mcdm.heroes.v1/kit/shining-armor
source: mcdm.heroes.v1
stability_bonus: "+1"
stamina_bonus: +12 per [echelon](../rule/general/echelon.md)
type: kit
---

The [Shining Armor](shining-armor.md) kit provides the most protection a kit can afford, providing you with the sword, shield, and armor necessary to play the prototypical knight.

##### Equipment

You wear heavy armor and wield a shield and a medium weapon.

```ds-feature
distance: '[Melee](../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
      tier1: 5 + M or A damage
      tier2: 8 + M or A damage
      tier3: 11 + M or A damage
    - effect: The target is [taunted](../condition/taunted.md) until the end of their next [turn](../rule/combat/turn.md).
      name: Effect
feature_type: ability
flavor: The strength of your assault makes it impossible for your foe to ignore you.
keywords:
    - '[Melee](../rule/combat/melee.md)'
    - '[Strike](../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](../rule/combat/melee.md) 1'
    effects:
        - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
          tier1: 5 + M or A damage
          tier2: 8 + M or A damage
          tier3: 11 + M or A damage
        - effect: The target is [taunted](../condition/taunted.md) until the end of their next [turn](../rule/combat/turn.md).
          name: Effect
    flavor: The strength of your assault makes it impossible for your foe to ignore you.
    keywords:
        - '[Melee](../rule/combat/melee.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Protective Attack
    power_roll_characteristic: '[Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)'
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
