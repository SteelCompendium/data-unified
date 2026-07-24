---
disengage_bonus: "+1"
equipment_text: You wear no armor and wield a whip.
file_basename: whirlwind
file_dpath: kit
flavor: The Whirlwind kit makes effective use of whips, granting you mobility, damage, and reach. If you want to be a fast-moving warrior who lashes foes with a chain or whip, then this is the kit for you.
item_id: whirlwind
item_name: Whirlwind
melee_damage_bonus: +1/+1/+1
melee_distance_bonus: "+1"
name: Whirlwind
scc: mcdm.heroes.v1/kit/whirlwind
source: mcdm.heroes.v1
speed_bonus: "+3"
type: kit
---

The [Whirlwind](whirlwind.md) kit makes effective use of whips, granting you mobility, damage, and reach. If you want to be a fast-moving warrior who lashes foes with a chain or whip, then this is the kit for you.

##### Equipment

You wear no armor and wield a whip.

```ds-feature
distance: '[Melee](../rule/combat/melee.md) 3'
effects:
    - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
      tier1: 4 + M or A damage; vertical [pull](../movement/forced-movement.md) 1
      tier2: 7 + M or A damage; vertical [pull](../movement/forced-movement.md) 2
      tier3: 10 + M or A damage; vertical [pull](../movement/forced-movement.md) 3
feature_type: ability
flavor: When you draw your whip back after an attack, your enemy is drawn ever closer.
keywords:
    - '[Melee](../rule/combat/melee.md)'
    - '[Strike](../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](../rule/combat/melee.md) 3'
    effects:
        - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
          tier1: 4 + M or A damage; vertical [pull](../movement/forced-movement.md) 1
          tier2: 7 + M or A damage; vertical [pull](../movement/forced-movement.md) 2
          tier3: 10 + M or A damage; vertical [pull](../movement/forced-movement.md) 3
    flavor: When you draw your whip back after an attack, your enemy is drawn ever closer.
    keywords:
        - '[Melee](../rule/combat/melee.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Extension of My Arm
    power_roll_characteristic: '[Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)'
    subtype: signature
    target: One creature
    tier1: 4 + M or A damage; vertical [pull](../movement/forced-movement.md) 1
    tier2: 7 + M or A damage; vertical [pull](../movement/forced-movement.md) 2
    tier3: 10 + M or A damage; vertical [pull](../movement/forced-movement.md) 3
    type: ability
name: Extension of My Arm
target: One creature
type: feature
usage: Main action
```
