---
disengage_bonus: "+1"
equipment_text: You wear light armor and wield a polearm.
file_basename: stick-and-robe
file_dpath: kit
flavor: Armed with a simple reach weapon, often a quarterstaff, a character using the Stick and Robe kit is highly mobile thanks to their light armor. This allows your hero to make maximum use of their weapon's length.
item_id: stick-and-robe
item_name: Stick and Robe
melee_damage_bonus: +1/+1/+1
melee_distance_bonus: "+1"
name: Stick and Robe
scc: mcdm.heroes.v1/kit/stick-and-robe
source: mcdm.heroes.v1
speed_bonus: "+2"
stamina_bonus: +3 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)
type: kit
---

Armed with a simple reach weapon, often a quarterstaff, a character using the [Stick and Robe](scc.v1:mcdm.heroes.v1/kit/stick-and-robe) kit is highly mobile thanks to their light armor. This allows your hero to make maximum use of their weapon's length.

##### Equipment

You wear light armor and wield a polearm.

##### Kit Bonuses

**[Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +3 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)

**[Speed](scc.v1:mcdm.heroes.v1/rule.character/speed) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +2

**[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) Damage [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1/+1/+1

**[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [Distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

**Disengage [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

##### Signature Ability

###### Where I Want You

*When your stick speaks, your enemy moves.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|---------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2**            | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 4 + M or A damage
- **12-16:** 7 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
- **17+:** 10 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + M or A damage
      tier2: 7 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier3: 10 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
feature_type: ability
flavor: When your stick speaks, your enemy moves.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
    flavor: When your stick speaks, your enemy moves.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Where I Want You
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    subtype: signature
    target: One creature
    tier1: 4 + M or A damage
    tier2: 7 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier3: 10 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    type: ability
name: Where I Want You
target: One creature
type: feature
usage: Main action
```
