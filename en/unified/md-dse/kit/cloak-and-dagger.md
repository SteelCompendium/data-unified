---
disengage_bonus: "+1"
equipment_text: You wear light armor and wield one or two light weapons.
file_basename: cloak-and-dagger
file_dpath: kit
flavor: Providing throwable light weapons and light armor easily concealed by a cloak to confuse your enemies, the Cloak and Dagger kit makes you more mobile while increasing the effectiveness of your short-range strikes.
item_id: cloak-and-dagger
item_name: Cloak and Dagger
melee_damage_bonus: +1/+1/+1
name: Cloak and Dagger
ranged_damage_bonus: +1/+1/+1
ranged_distance_bonus: "+5"
scc: mcdm.heroes.v1/kit/cloak-and-dagger
source: mcdm.heroes.v1
speed_bonus: "+2"
stamina_bonus: +3 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)
type: kit
---

Providing throwable light weapons and light armor easily concealed by a cloak to confuse your enemies, the [Cloak and Dagger](scc.v1:mcdm.heroes.v1/kit/cloak-and-dagger) kit makes you more mobile while increasing the effectiveness of your short-range strikes.

##### Equipment

You wear light armor and wield one or two light weapons.

##### Kit Bonuses

**[Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +3 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)

**[Speed](scc.v1:mcdm.heroes.v1/rule.character/speed) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +2

**[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) Damage [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1/+1/+1

**[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) Damage [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1/+1/+1

**[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) [Distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +5

**Disengage [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

##### Signature Ability

###### Fade

*A stab, and a few quick, careful steps back.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|-----------------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10**       | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 3 + M or A damage; you can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square
- **12-16:** 6 + M or A damage; you can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares
- **17+:** 8 + M or A damage; you can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 + M or A damage; you can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square
      tier2: 6 + M or A damage; you can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares
      tier3: 8 + M or A damage; you can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares
feature_type: ability
flavor: A stab, and a few quick, careful steps back.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: A stab, and a few quick, careful steps back.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Fade
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    subtype: signature
    target: One creature
    tier1: 3 + M or A damage; you can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square
    tier2: 6 + M or A damage; you can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares
    tier3: 8 + M or A damage; you can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares
    type: ability
name: Fade
target: One creature
type: feature
usage: Main action
```
