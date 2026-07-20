---
disengage_bonus: "+1"
equipment_text: You wear light armor and wield a polearm.
file_basename: stick-and-robe
file_dpath: kit
flavor: Armed with a simple reach weapon, often a quarterstaff, a character using the Stick and Robe kit is highly mobile thanks to their light armor. This allows your hero to make maximum use of their weapon's length.
item_id: stick-and-robe
item_name: Stick and Robe
melee_damage_bonus: +1/+1/+1
melee_distance_bonus: "+1"
name: Stick and Robe
scc: mcdm.heroes.v1/kit/stick-and-robe
source: mcdm.heroes.v1
speed_bonus: "+2"
stamina_bonus: +3 per [echelon](../rule/general/echelon.md)
type: kit
---

Armed with a simple reach weapon, often a quarterstaff, a character using the [Stick and Robe](stick-and-robe.md) kit is highly mobile thanks to their light armor. This allows your hero to make maximum use of their weapon's length.

##### Equipment

You wear light armor and wield a polearm.

```ds-feature
distance: '[Melee](../rule/combat/melee.md) 2'
effects:
    - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
      tier1: 4 + M or A damage
      tier2: 7 + M or A damage; [slide](../movement/forced-movement.md) 1
      tier3: 10 + M or A damage; [slide](../movement/forced-movement.md) 3
feature_type: ability
flavor: When your stick speaks, your enemy moves.
keywords:
    - '[Melee](../rule/combat/melee.md)'
    - '[Strike](../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](../rule/combat/melee.md) 2'
    flavor: When your stick speaks, your enemy moves.
    keywords:
        - '[Melee](../rule/combat/melee.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Where I Want You
    power_roll_characteristic: '[Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)'
    subtype: signature
    target: One creature
    tier1: 4 + M or A damage
    tier2: 7 + M or A damage; [slide](../movement/forced-movement.md) 1
    tier3: 10 + M or A damage; [slide](../movement/forced-movement.md) 3
    type: ability
name: Where I Want You
target: One creature
type: feature
usage: Main action
```
