---
disengage_bonus: "+1"
equipment_text: You wear medium armor and wield a shield and a medium weapon.
file_basename: sword-and-board
file_dpath: kit
flavor: The Sword and Board kit doesn't just give you a shield—it makes the shield part of your offensive arsenal. With a medium weapon in one hand and a block of steel or solid oak in the other, you protect yourself while you control the battlefield.
item_id: sword-and-board
item_name: Sword and Board
kit_type: Martial
melee_damage_bonus: +2/+2/+2
name: Sword and Board
scc: mcdm.heroes.v1/kit/sword-and-board
source: mcdm.heroes.v1
stability_bonus: "+1"
stamina_bonus: +9 per [echelon](../rule/general/echelon.md)
type: kit
---

The [Sword and Board](sword-and-board.md) kit doesn't just give you a shield—it makes the shield part of your offensive arsenal. With a medium weapon in one hand and a block of steel or solid oak in the other, you protect yourself while you control the battlefield.

##### Equipment

You wear medium armor and wield a shield and a medium weapon.

```ds-feature
distance: '[Melee](../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
      tier1: 4 + M or A damage; [push](../movement/forced-movement.md) 1
      tier2: 7 + M or A damage; [push](../movement/forced-movement.md) 2
      tier3: 9 + M or A damage; [push](../movement/forced-movement.md) 3; M < STRONG[, prone](../condition/prone.md)
feature_type: ability
flavor: In your hands, a shield isn't just for protection.
keywords:
    - '[Melee](../rule/combat/melee.md)'
    - '[Strike](../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](../rule/combat/melee.md) 1'
    effects:
        - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
          tier1: 4 + M or A damage; [push](../movement/forced-movement.md) 1
          tier2: 7 + M or A damage; [push](../movement/forced-movement.md) 2
          tier3: 9 + M or A damage; [push](../movement/forced-movement.md) 3; M < STRONG[, prone](../condition/prone.md)
    flavor: In your hands, a shield isn't just for protection.
    keywords:
        - '[Melee](../rule/combat/melee.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Shield Bash
    power_roll_characteristic: '[Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)'
    subtype: signature
    target: One creature
    tier1: 4 + M or A damage; [push](../movement/forced-movement.md) 1
    tier2: 7 + M or A damage; [push](../movement/forced-movement.md) 2
    tier3: 9 + M or A damage; [push](../movement/forced-movement.md) 3; M < STRONG[, prone](../condition/prone.md)
    type: ability
name: Shield Bash
target: One creature
type: feature
usage: Main action
```
