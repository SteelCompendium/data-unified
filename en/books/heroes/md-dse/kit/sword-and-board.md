---
disengage_bonus: "+1"
equipment_text: You wear medium armor and wield a shield and a medium weapon.
file_basename: sword-and-board
file_dpath: kit
flavor: The Sword and Board kit doesn't just give you a shield—it makes the shield part of your offensive arsenal. With a medium weapon in one hand and a block of steel or solid oak in the other, you protect yourself while you control the battlefield.
item_id: sword-and-board
item_name: Sword and Board
melee_damage_bonus: +2/+2/+2
name: Sword and Board
scc: mcdm.heroes.v1/kit/sword-and-board
source: mcdm.heroes.v1
stability_bonus: "+1"
stamina_bonus: +9 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)
type: kit
---

The [Sword and Board](scc.v1:mcdm.heroes.v1/kit/sword-and-board) kit doesn't just give you a shield—it makes the shield part of your offensive arsenal. With a medium weapon in one hand and a block of steel or solid oak in the other, you protect yourself while you control the battlefield.

##### Equipment

You wear medium armor and wield a shield and a medium weapon.

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier2: 7 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier3: 9 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
feature_type: ability
flavor: In your hands, a shield isn't just for protection.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    flavor: In your hands, a shield isn't just for protection.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Shield Bash
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    subtype: signature
    target: One creature
    tier1: 4 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier2: 7 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    tier3: 9 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    type: ability
name: Shield Bash
target: One creature
type: feature
usage: Main action
```
