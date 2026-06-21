---
equipment_text: You wear light armor and wield a medium weapon.
file_basename: swashbuckler
file_dpath: kit
flavor: If you want to be mobile and deal a lot of damage with melee strikes, then you should reach for the Swashbuckler kit. This is a great kit for heroes who want to be master duelists.
item_id: swashbuckler
item_name: Swashbuckler
name: Swashbuckler
scc: mcdm.heroes.v1/kit/swashbuckler
source: mcdm.heroes.v1
type: kit
---

If you want to be mobile and deal a lot of damage with [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [strikes](scc.v1:mcdm.heroes.v1/rule.combat/strike), then you should reach for the [Swashbuckler](scc.v1:mcdm.heroes.v1/kit/swashbuckler) kit. This is a great kit for heroes who want to be master duelists.

##### Equipment

You wear light armor and wield a medium weapon.

##### Kit Bonuses

**[Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +3 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)

**[Speed](scc.v1:mcdm.heroes.v1/rule.character/speed) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +3

**[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) Damage [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +2/+2/+2

**Disengage [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

##### Signature Ability

###### Fancy Footwork

*All combat is a dance—and you'll be the one leading.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|---------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 5 + M or A damage
- **12-16:** 7 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
- **17+:** 10 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2

**Effect:** You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into any square the target leaves after you [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into any square the target leaves after you [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 5 + M or A damage
      tier2: 7 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier3: 10 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
feature_type: ability
flavor: All combat is a dance—and you'll be the one leading.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into any square the target leaves after you [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.
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
