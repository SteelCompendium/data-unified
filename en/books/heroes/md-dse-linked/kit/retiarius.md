---
disengage_bonus: "+1"
equipment_text: You wear light armor and wield several ensnaring weapons and a polearm.
file_basename: retiarius
file_dpath: kit
flavor: The retiarius is often depicted as a lightly armored warrior with a net in one hand and a trident in the other, and this kit gives you the equipment and fighting technique to make that happen. Tie up your foe with a net and then poke them to death!
item_id: retiarius
item_name: Retiarius
kit_type: Martial
melee_damage_bonus: +2/+2/+2
melee_distance_bonus: "+1"
name: Retiarius
scc: mcdm.heroes.v1/kit/retiarius
source: mcdm.heroes.v1
speed_bonus: "+1"
stamina_bonus: +3 per [echelon](../rule/general/echelon.md)
type: kit
---

The [retiarius](retiarius.md) is often depicted as a lightly armored warrior with a net in one hand and a trident in the other, and this kit gives you the equipment and fighting technique to make that happen. Tie up your foe with a net and then poke them to death!

##### Equipment

You wear light armor and wield several ensnaring weapons and a polearm.

```ds-feature
distance: '[Melee](../rule/combat/melee.md) 2'
effects:
    - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
      tier1: 4 + M or A damage; A < WEAK, [slowed](../condition/slowed.md) ([EoT](../rule/combat/end-of-turn.md))
      tier2: 6 + M or A damage; A < AVERAGE, [slowed](../condition/slowed.md) ([EoT](../rule/combat/end-of-turn.md))
      tier3: 8 + M or A damage; A < STRONG, [restrained](../condition/restrained.md) ([EoT](../rule/combat/end-of-turn.md))
feature_type: ability
flavor: The well-thrown net that follows your main attack leaves your foes right where you want them.
keywords:
    - '[Melee](../rule/combat/melee.md)'
    - '[Strike](../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](../rule/combat/melee.md) 2'
    effects:
        - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
          tier1: 4 + M or A damage; A < WEAK, [slowed](../condition/slowed.md) ([EoT](../rule/combat/end-of-turn.md))
          tier2: 6 + M or A damage; A < AVERAGE, [slowed](../condition/slowed.md) ([EoT](../rule/combat/end-of-turn.md))
          tier3: 8 + M or A damage; A < STRONG, [restrained](../condition/restrained.md) ([EoT](../rule/combat/end-of-turn.md))
    flavor: The well-thrown net that follows your main attack leaves your foes right where you want them.
    keywords:
        - '[Melee](../rule/combat/melee.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Net and Stab
    power_roll_characteristic: '[Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)'
    subtype: signature
    target: One creature
    tier1: 4 + M or A damage; A < WEAK, [slowed](../condition/slowed.md) ([EoT](../rule/combat/end-of-turn.md))
    tier2: 6 + M or A damage; A < AVERAGE, [slowed](../condition/slowed.md) ([EoT](../rule/combat/end-of-turn.md))
    tier3: 8 + M or A damage; A < STRONG, [restrained](../condition/restrained.md) ([EoT](../rule/combat/end-of-turn.md))
    type: ability
name: Net and Stab
target: One creature
type: feature
usage: Main action
```
