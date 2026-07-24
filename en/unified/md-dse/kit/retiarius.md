---
disengage_bonus: "+1"
equipment_text: You wear light armor and wield several ensnaring weapons and a polearm.
file_basename: retiarius
file_dpath: kit
flavor: The retiarius is often depicted as a lightly armored warrior with a net in one hand and a trident in the other, and this kit gives you the equipment and fighting technique to make that happen. Tie up your foe with a net and then poke them to death!
item_id: retiarius
item_name: Retiarius
melee_damage_bonus: +2/+2/+2
melee_distance_bonus: "+1"
name: Retiarius
scc: mcdm.heroes.v1/kit/retiarius
source: mcdm.heroes.v1
speed_bonus: "+1"
stamina_bonus: +3 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)
type: kit
---

The [retiarius](scc.v1:mcdm.heroes.v1/kit/retiarius) is often depicted as a lightly armored warrior with a net in one hand and a trident in the other, and this kit gives you the equipment and fighting technique to make that happen. Tie up your foe with a net and then poke them to death!

##### Equipment

You wear light armor and wield several ensnaring weapons and a polearm.

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + M or A damage; A < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
      tier2: 6 + M or A damage; A < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
      tier3: 8 + M or A damage; A < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
feature_type: ability
flavor: The well-thrown net that follows your main attack leaves your foes right where you want them.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 4 + M or A damage; A < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
          tier2: 6 + M or A damage; A < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
          tier3: 8 + M or A damage; A < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
    flavor: The well-thrown net that follows your main attack leaves your foes right where you want them.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Net and Stab
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    subtype: signature
    target: One creature
    tier1: 4 + M or A damage; A < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
    tier2: 6 + M or A damage; A < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
    tier3: 8 + M or A damage; A < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
    type: ability
name: Net and Stab
target: One creature
type: feature
usage: Main action
```
