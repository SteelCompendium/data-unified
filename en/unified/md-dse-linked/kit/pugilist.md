---
equipment_text: You wear no armor and wield only your unarmed [strikes](../rule/combat/strike.md).
file_basename: pugilist
file_dpath: kit
flavor: Meant for brawlers and boxers, the Pugilist kit gives you access to a melee fighting style that grants a boost to Stamina and damage while allowing you to float like a butterfly. If you want to be a tough, strong hero who doles out punishment with your fists, then this kit is for you.
item_id: pugilist
item_name: Pugilist
melee_damage_bonus: +1/+1/+1
name: Pugilist
scc: mcdm.heroes.v1/kit/pugilist
source: mcdm.heroes.v1
speed_bonus: "+2"
stability_bonus: "+1"
stamina_bonus: +6 per [echelon](../rule/general/echelon.md)
type: kit
---

Meant for brawlers and boxers, the [Pugilist](pugilist.md) kit gives you access to a [melee](../rule/combat/melee.md) fighting style that grants a boost to [Stamina](../rule/health/stamina.md) and damage while allowing you to float like a butterfly. If you want to be a tough, strong hero who doles out punishment with your fists, then this kit is for you.

##### Equipment

You wear no armor and wield only your unarmed [strikes](../rule/combat/strike.md).

```ds-feature
distance: '[Melee](../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
      tier1: 3 + M or A damage
      tier2: 6 + M or A damage; [slide](../movement/forced-movement.md) 1
      tier3: 8 + M or A damage; [slide](../movement/forced-movement.md) 2
    - effect: You can [shift](../movement/shifting.md) into any square the target leaves after you [slide](../movement/forced-movement.md) them.
      name: Effect
feature_type: ability
flavor: Keeping your enemies stumbling around the battlefield is second nature to you.
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
          tier2: 6 + M or A damage; [slide](../movement/forced-movement.md) 1
          tier3: 8 + M or A damage; [slide](../movement/forced-movement.md) 2
        - effect: You can [shift](../movement/shifting.md) into any square the target leaves after you [slide](../movement/forced-movement.md) them.
          name: Effect
    flavor: Keeping your enemies stumbling around the battlefield is second nature to you.
    keywords:
        - '[Melee](../rule/combat/melee.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Let's Dance
    power_roll_characteristic: '[Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)'
    subtype: signature
    target: One creature
    tier1: 3 + M or A damage
    tier2: 6 + M or A damage; [slide](../movement/forced-movement.md) 1
    tier3: 8 + M or A damage; [slide](../movement/forced-movement.md) 2
    type: ability
name: Let's Dance
target: One creature
type: feature
usage: Main action
```
