---
disengage_bonus: "+1"
equipment_text: You wear medium armor and wield a bow and a medium weapon.
file_basename: ranger
file_dpath: kit
flavor: The Ranger kit outfits you with medium armor and weapons for every challenge, letting you easily switch between melee and ranged combat. This kit provides a good balance of bonuses to defense and offense to create a hero who is a jack-of-all-trades.
item_id: ranger
item_name: Ranger
melee_damage_bonus: +1/+1/+1
name: Ranger
ranged_damage_bonus: +1/+1/+1
ranged_distance_bonus: "+5"
scc: mcdm.heroes.v1/kit/ranger
source: mcdm.heroes.v1
speed_bonus: "+1"
stamina_bonus: +6 per [echelon](../rule/general/echelon.md)
type: kit
---

The [Ranger](ranger.md) kit outfits you with medium armor and weapons for every challenge, letting you easily switch between [melee](../rule/combat/melee.md) and [ranged](../rule/combat/ranged.md) combat. This kit provides a good balance of [bonus](../rule/dice/bonuses-and-penalties.md)es to defense and offense to create a hero who is a jack-of-all-trades.

##### Equipment

You wear medium armor and wield a bow and a medium weapon.

```ds-feature
distance: '[Ranged](../rule/combat/ranged.md) 10'
effects:
    - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
      tier1: 3 + M or A damage; A < WEAK, [slowed](../condition/slowed.md) (save ends)
      tier2: 5 + M or A damage; A < AVERAGE, [slowed](../condition/slowed.md) (save ends)
      tier3: 7 + M or A damage; A < STRONG, [slowed](../condition/slowed.md) (save ends)
feature_type: ability
flavor: A well-placed shot leaves your enemy struggling to move.
keywords:
    - '[Ranged](../rule/combat/ranged.md)'
    - '[Strike](../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Ranged](../rule/combat/ranged.md) 10'
    effects:
        - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
          tier1: 3 + M or A damage; A < WEAK, [slowed](../condition/slowed.md) (save ends)
          tier2: 5 + M or A damage; A < AVERAGE, [slowed](../condition/slowed.md) (save ends)
          tier3: 7 + M or A damage; A < STRONG, [slowed](../condition/slowed.md) (save ends)
    flavor: A well-placed shot leaves your enemy struggling to move.
    keywords:
        - '[Ranged](../rule/combat/ranged.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Hamstring Shot
    power_roll_characteristic: '[Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)'
    subtype: signature
    target: One creature
    tier1: 3 + M or A damage; A < WEAK, [slowed](../condition/slowed.md) (save ends)
    tier2: 5 + M or A damage; A < AVERAGE, [slowed](../condition/slowed.md) (save ends)
    tier3: 7 + M or A damage; A < STRONG, [slowed](../condition/slowed.md) (save ends)
    type: ability
name: Hamstring Shot
target: One creature
type: feature
usage: Main action
```
