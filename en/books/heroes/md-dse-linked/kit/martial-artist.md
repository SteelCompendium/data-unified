---
disengage_bonus: "+1"
equipment_text: You wear no armor and wield only your unarmed [strikes](../rule/combat/strike.md).
file_basename: martial-artist
file_dpath: kit
flavor: If you want to be fast in a fight, then Martial Artist is the kit for you. Unencumbered by weapons or armor, this fighting style rewards quick, focused unarmed strikes against opponents, and allows you to be the ultimate skirmisher.
item_id: martial-artist
item_name: Martial Artist
kit_type: Martial
melee_damage_bonus: +2/+2/+2
name: Martial Artist
scc: mcdm.heroes.v1/kit/martial-artist
source: mcdm.heroes.v1
speed_bonus: "+3"
stamina_bonus: +3 per [echelon](../rule/general/echelon.md)
type: kit
---

If you want to be fast in a fight, then [Martial Artist](martial-artist.md) is the kit for you. Unencumbered by weapons or armor, this fighting style rewards quick, focused unarmed [strikes](../rule/combat/strike.md) against opponents, and allows you to be the ultimate skirmisher.

##### Equipment

You wear no armor and wield only your unarmed [strikes](../rule/combat/strike.md).

```ds-feature
distance: '[Melee](../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
      tier1: 5 + M or A damage
      tier2: 8 + M or A damage; you can swap places with the target
      tier3: 11 + M or A damage; you can swap places with the target
    - effect: If you obtain a tier 2 or tier 3 outcome and can't swap places with the target because one or both of you is too big to fit into the swapped space, you both remain in your original spaces and the target takes 1 extra damage.
      name: Effect
feature_type: ability
flavor: You feint to move your enemies into perfect position.
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
          tier2: 8 + M or A damage; you can swap places with the target
          tier3: 11 + M or A damage; you can swap places with the target
        - effect: If you obtain a tier 2 or tier 3 outcome and can't swap places with the target because one or both of you is too big to fit into the swapped space, you both remain in your original spaces and the target takes 1 extra damage.
          name: Effect
    flavor: You feint to move your enemies into perfect position.
    keywords:
        - '[Melee](../rule/combat/melee.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Battle Grace
    power_roll_characteristic: '[Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)'
    subtype: signature
    target: One creature
    tier1: 5 + M or A damage
    tier2: 8 + M or A damage; you can swap places with the target
    tier3: 11 + M or A damage; you can swap places with the target
    type: ability
name: Battle Grace
target: One creature
type: feature
usage: Main action
```
