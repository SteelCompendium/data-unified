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
stamina_bonus: +3 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)
type: kit
---

If you want to be mobile and deal a lot of damage with [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [strikes](scc.v1:mcdm.heroes.v1/rule.combat/strike), then you should reach for the [Swashbuckler](scc.v1:mcdm.heroes.v1/kit/swashbuckler) kit. This is a great kit for heroes who want to be master duelists.

##### Equipment

You wear light armor and wield a medium weapon.

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 5 + M or A damage
      tier2: 7 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier3: 10 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into any square the target leaves after you [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.
      name: Effect
feature_type: ability
flavor: All combat is a dance—and you'll be the one leading.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 5 + M or A damage
          tier2: 7 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier3: 10 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
        - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into any square the target leaves after you [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.
          name: Effect
    flavor: All combat is a dance—and you'll be the one leading.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Fancy Footwork
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    subtype: signature
    target: One creature
    tier1: 5 + M or A damage
    tier2: 7 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier3: 10 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    type: ability
name: Fancy Footwork
target: One creature
type: feature
usage: Main action
```
