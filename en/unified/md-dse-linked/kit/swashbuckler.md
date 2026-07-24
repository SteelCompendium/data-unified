---
disengage_bonus: "+1"
equipment_text: You wear light armor and wield a medium weapon.
file_basename: swashbuckler
file_dpath: kit
flavor: If you want to be mobile and deal a lot of damage with melee strikes, then you should reach for the Swashbuckler kit. This is a great kit for heroes who want to be master duelists.
item_id: swashbuckler
item_name: Swashbuckler
melee_damage_bonus: +2/+2/+2
name: Swashbuckler
scc: mcdm.heroes.v1/kit/swashbuckler
source: mcdm.heroes.v1
speed_bonus: "+3"
stamina_bonus: +3 per [echelon](../rule/general/echelon.md)
type: kit
---

If you want to be mobile and deal a lot of damage with [melee](../rule/combat/melee.md) [strikes](../rule/combat/strike.md), then you should reach for the [Swashbuckler](swashbuckler.md) kit. This is a great kit for heroes who want to be master duelists.

##### Equipment

You wear light armor and wield a medium weapon.

```ds-feature
distance: '[Melee](../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
      tier1: 5 + M or A damage
      tier2: 7 + M or A damage; [push](../movement/forced-movement.md) 1
      tier3: 10 + M or A damage; [push](../movement/forced-movement.md) 2
    - effect: You can [shift](../movement/shifting.md) into any square the target leaves after you [push](../movement/forced-movement.md) them.
      name: Effect
feature_type: ability
flavor: All combat is a dance—and you'll be the one leading.
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
          tier2: 7 + M or A damage; [push](../movement/forced-movement.md) 1
          tier3: 10 + M or A damage; [push](../movement/forced-movement.md) 2
        - effect: You can [shift](../movement/shifting.md) into any square the target leaves after you [push](../movement/forced-movement.md) them.
          name: Effect
    flavor: All combat is a dance—and you'll be the one leading.
    keywords:
        - '[Melee](../rule/combat/melee.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Fancy Footwork
    power_roll_characteristic: '[Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)'
    subtype: signature
    target: One creature
    tier1: 5 + M or A damage
    tier2: 7 + M or A damage; [push](../movement/forced-movement.md) 1
    tier3: 10 + M or A damage; [push](../movement/forced-movement.md) 2
    type: ability
name: Fancy Footwork
target: One creature
type: feature
usage: Main action
```
