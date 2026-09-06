---
equipment_text: You wear heavy armor and wield a heavy weapon.
file_basename: mountain
file_dpath: kit
flavor: The Mountain kit does exactly what it says on the tin. You don heavy armor and raise a heavy weapon to stand strong against your foes, quickly demolishing them when it's your turn to strike.
item_id: mountain
item_name: Mountain
kit_type: Martial
melee_damage_bonus: +0/+0/+4
name: Mountain
scc: mcdm.heroes.v1/kit/mountain
source: mcdm.heroes.v1
stability_bonus: "+2"
stamina_bonus: +9 per [echelon](../rule/general/echelon.md)
type: kit
---

The [Mountain](mountain.md) kit does exactly what it says on the tin. You don heavy armor and raise a heavy weapon to stand strong against your foes, quickly demolishing them when it's your turn to strike.

##### Equipment

You wear heavy armor and wield a heavy weapon.

```ds-feature
distance: '[Melee](../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
      tier1: 3 + M or A damage
      tier2: 5 + M or A damage
      tier3: 13 + M or A damage
    - effect: If the target dealt damage to you since the end of your last [turn](../rule/combat/turn.md), this [strike](../rule/combat/strike.md) deals additional damage equal to your [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md) score (your choice).
      name: Effect
feature_type: ability
flavor: An enemy who tagged you will pay for that.
keywords:
    - '[Melee](../rule/combat/melee.md)'
    - '[Strike](../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](../rule/combat/melee.md) 1'
    effects:
        - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
          tier1: 3 + M or A damage
          tier2: 5 + M or A damage
          tier3: 13 + M or A damage
        - effect: If the target dealt damage to you since the end of your last [turn](../rule/combat/turn.md), this [strike](../rule/combat/strike.md) deals additional damage equal to your [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md) score (your choice).
          name: Effect
    flavor: An enemy who tagged you will pay for that.
    keywords:
        - '[Melee](../rule/combat/melee.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Pain for Pain
    power_roll_characteristic: '[Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)'
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
