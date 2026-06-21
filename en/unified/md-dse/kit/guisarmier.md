---
equipment_text: You wear medium armor and wield a polearm.
file_basename: guisarmier
file_dpath: kit
flavor: The Guisarmier kit is for those who want to use a polearm for extended reach while remaining protected by sturdy armor. This is the kit that allows you to become the ultimate halberd, longspear, or glaive fighter.
item_id: guisarmier
item_name: Guisarmier
melee_damage_bonus: +2/+2/+2
melee_distance_bonus: "+1"
name: Guisarmier
scc: mcdm.heroes.v1/kit/guisarmier
source: mcdm.heroes.v1
stability_bonus: "+1"
stamina_bonus: +6 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)
type: kit
---

The [Guisarmier](scc.v1:mcdm.heroes.v1/kit/guisarmier) kit is for those who want to use a polearm for extended reach while remaining protected by sturdy armor. This is the kit that allows you to become the ultimate halberd, longspear, or glaive fighter.

##### Equipment

You wear medium armor and wield a polearm.

##### Kit Bonuses

**[Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +6 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)

**[Stability](scc.v1:mcdm.heroes.v1/rule.character/stability) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

**[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) Damage [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +2/+2/+2

**[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [Distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

##### Signature Ability

###### Forward Thrust, Backward Smash

*In your hands, the haft is as good as the head.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |                 **Main action** |
|---------------------------|--------------------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2**            | **🎯 Two creatures or objects** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 4 damage
- **12-16:** 7 damage
- **17+:** 9 damage

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 damage
      tier2: 7 damage
      tier3: 9 damage
feature_type: ability
flavor: In your hands, the haft is as good as the head.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
    flavor: In your hands, the haft is as good as the head.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Forward Thrust, Backward Smash
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    subtype: signature
    target: Two creatures or objects
    tier1: 4 damage
    tier2: 7 damage
    tier3: 9 damage
    type: ability
name: Forward Thrust, Backward Smash
target: Two creatures or objects
type: feature
usage: Main action
```
