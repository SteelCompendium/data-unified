---
disengage_bonus: "+1"
equipment_text: You wear light armor and wield a shield and a light weapon.
file_basename: raider
file_dpath: kit
flavor: The Raider kit keeps you protected while granting you full mobility, providing a boost to speed and distance that lets you run around the battlefield like a Viking warrior.
item_id: raider
item_name: Raider
melee_damage_bonus: +1/+1/+1
name: Raider
ranged_damage_bonus: +1/+1/+1
ranged_distance_bonus: "+5"
scc: mcdm.heroes.v1/kit/raider
source: mcdm.heroes.v1
speed_bonus: "+1"
stamina_bonus: +6 per [echelon](../rule/general/echelon.md)
type: kit
---

The [Raider](raider.md) kit keeps you protected while granting you full mobility, providing a boost to [speed](../rule/character/speed.md) and [distance](../rule/combat/distance.md) that lets you run around the battlefield like a Viking warrior.

##### Equipment

You wear light armor and wield a shield and a light weapon.

```ds-feature
distance: '[Melee](../rule/combat/melee.md) 1 or [ranged](../rule/combat/ranged.md) 10'
effects:
    - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
      tier1: 3 + M or A damage
      tier2: 6 + M or A damage
      tier3: 8 + M or A damage
    - effect: The target takes a [bane](../rule/dice/bane.md) on their next [power roll](../rule/dice/power-roll.md) made before the end of their next [turn](../rule/combat/turn.md).
      name: Effect
feature_type: ability
flavor: You execute a brutal strike that leaves your foe reeling. (Previously known as "[Shock and Awe](../feature/tactician/level-7/shock-and-awe.md)")
keywords:
    - '[Melee](../rule/combat/melee.md)'
    - '[Ranged](../rule/combat/ranged.md)'
    - '[Strike](../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](../rule/combat/melee.md) 1 or [ranged](../rule/combat/ranged.md) 10'
    effects:
        - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
          tier1: 3 + M or A damage
          tier2: 6 + M or A damage
          tier3: 8 + M or A damage
        - effect: The target takes a [bane](../rule/dice/bane.md) on their next [power roll](../rule/dice/power-roll.md) made before the end of their next [turn](../rule/combat/turn.md).
          name: Effect
    flavor: You execute a brutal strike that leaves your foe reeling. (Previously known as "[Shock and Awe](../feature/tactician/level-7/shock-and-awe.md)")
    keywords:
        - '[Melee](../rule/combat/melee.md)'
        - '[Ranged](../rule/combat/ranged.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Raider's Awe
    power_roll_characteristic: '[Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)'
    subtype: signature
    target: One creature
    tier1: 3 + M or A damage
    tier2: 6 + M or A damage
    tier3: 8 + M or A damage
    type: ability
name: Raider's Awe
target: One creature
type: feature
usage: Main action
```
