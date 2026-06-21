---
equipment_text: You wear no armor and wield only your unarmed [strikes](scc.v1:mcdm.heroes.v1/rule.combat/strike).
file_basename: pugilist
file_dpath: kit
flavor: Meant for brawlers and boxers, the Pugilist kit gives you access to a melee fighting style that grants a boost to Stamina and damage while allowing you to float like a butterfly. If you want to be a tough, strong hero who doles out punishment with your fists, then this kit is for you.
item_id: pugilist
item_name: Pugilist
name: Pugilist
scc: mcdm.heroes.v1/kit/pugilist
source: mcdm.heroes.v1
type: kit
---

Meant for brawlers and boxers, the [Pugilist](scc.v1:mcdm.heroes.v1/kit/pugilist) kit gives you access to a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) fighting style that grants a boost to [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and damage while allowing you to float like a butterfly. If you want to be a tough, strong hero who doles out punishment with your fists, then this kit is for you.

##### Equipment

You wear no armor and wield only your unarmed [strikes](scc.v1:mcdm.heroes.v1/rule.combat/strike).

##### Kit Bonuses

**[Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +6 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)

**[Speed](scc.v1:mcdm.heroes.v1/rule.character/speed) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +2

**[Stability](scc.v1:mcdm.heroes.v1/rule.character/stability) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

**[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) Damage [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1/+1/+1

##### Signature Ability

###### Let's Dance

*Keeping your enemies stumbling around the battlefield is second nature to you.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|---------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 3 + M or A damage
- **12-16:** 6 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
- **17+:** 8 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2

**Effect:** You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into any square the target leaves after you [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into any square the target leaves after you [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 + M or A damage
      tier2: 6 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier3: 8 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
feature_type: ability
flavor: Keeping your enemies stumbling around the battlefield is second nature to you.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into any square the target leaves after you [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.
    flavor: Keeping your enemies stumbling around the battlefield is second nature to you.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Let's Dance
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    subtype: signature
    target: One creature
    tier1: 3 + M or A damage
    tier2: 6 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier3: 8 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    type: ability
name: Let's Dance
target: One creature
type: feature
usage: Main action
```
