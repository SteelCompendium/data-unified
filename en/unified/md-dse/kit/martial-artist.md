---
disengage_bonus: "+1"
equipment_text: You wear no armor and wield only your unarmed [strikes](scc.v1:mcdm.heroes.v1/rule.combat/strike).
file_basename: martial-artist
file_dpath: kit
flavor: If you want to be fast in a fight, then Martial Artist is the kit for you. Unencumbered by weapons or armor, this fighting style rewards quick, focused unarmed strikes against opponents, and allows you to be the ultimate skirmisher.
item_id: martial-artist
item_name: Martial Artist
melee_damage_bonus: +2/+2/+2
name: Martial Artist
scc: mcdm.heroes.v1/kit/martial-artist
source: mcdm.heroes.v1
speed_bonus: "+3"
stamina_bonus: +3 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)
type: kit
---

If you want to be fast in a fight, then [Martial Artist](scc.v1:mcdm.heroes.v1/kit/martial-artist) is the kit for you. Unencumbered by weapons or armor, this fighting style rewards quick, focused unarmed [strikes](scc.v1:mcdm.heroes.v1/rule.combat/strike) against opponents, and allows you to be the ultimate skirmisher.

##### Equipment

You wear no armor and wield only your unarmed [strikes](scc.v1:mcdm.heroes.v1/rule.combat/strike).

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: If you obtain a tier 2 or tier 3 outcome and can't swap places with the target because one or both of you is too big to fit into the swapped space, you both remain in your original spaces and the target takes 1 extra damage.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 5 + M or A damage
      tier2: 8 + M or A damage; you can swap places with the target
      tier3: 11 + M or A damage; you can swap places with the target
feature_type: ability
flavor: You feint to move your enemies into perfect position.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: If you obtain a tier 2 or tier 3 outcome and can't swap places with the target because one or both of you is too big to fit into the swapped space, you both remain in your original spaces and the target takes 1 extra damage.
    flavor: You feint to move your enemies into perfect position.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Battle Grace
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
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
