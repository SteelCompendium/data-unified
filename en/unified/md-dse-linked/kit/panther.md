---
equipment_text: You wear no armor and wield a heavy weapon.
file_basename: panther
file_dpath: kit
flavor: If you want a good balance of protection, speed, and damage, the Panther kit is for you. This kit increases your Stamina not by wearing armor, but through the focused battle preparation of body and mind, letting you be fast and mobile while swinging a heavy weapon at your foes.
item_id: panther
item_name: Panther
kit_type: Martial
melee_damage_bonus: +0/+0/+4
name: Panther
scc: mcdm.heroes.v1/kit/panther
source: mcdm.heroes.v1
speed_bonus: "+1"
stability_bonus: "+1"
stamina_bonus: +6 per [echelon](../rule/general/echelon.md)
type: kit
---

If you want a good balance of protection, [speed](../rule/character/speed.md), and damage, the [Panther](panther.md) kit is for you. This kit increases your [Stamina](../rule/health/stamina.md) not by wearing armor, but through the focused battle preparation of body and mind, letting you be fast and mobile while swinging a heavy weapon at your foes.

##### Equipment

You wear no armor and wield a heavy weapon.

```ds-feature
distance: '[Melee](../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
      tier1: 3 + M or A damage
      tier2: 6 + M or A damage
      tier3: 13 + M or A damage
    - effect: You can move up to 3 squares straight toward the target before this [strike](../rule/combat/strike.md), which deals extra damage equal to the number of squares you move this way.
      name: Effect
feature_type: ability
flavor: The faster you move, the harder you hit.
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
          tier2: 6 + M or A damage
          tier3: 13 + M or A damage
        - effect: You can move up to 3 squares straight toward the target before this [strike](../rule/combat/strike.md), which deals extra damage equal to the number of squares you move this way.
          name: Effect
    flavor: The faster you move, the harder you hit.
    keywords:
        - '[Melee](../rule/combat/melee.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Devastating Rush
    power_roll_characteristic: '[Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)'
    subtype: signature
    target: One creature or object
    tier1: 3 + M or A damage
    tier2: 6 + M or A damage
    tier3: 13 + M or A damage
    type: ability
name: Devastating Rush
target: One creature or object
type: feature
usage: Main action
```
