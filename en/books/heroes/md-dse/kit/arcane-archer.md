---
disengage_bonus: "+1"
equipment_text: You wear no armor and wield a bow.
file_basename: arcane-archer
file_dpath: kit
flavor: The Arcane Archer kit allows you to combine magic and ranged weapon strikes. Your lack of armor keeps you mobile, and your magic makes your arrows explode to devastate your foes.
item_id: arcane-archer
item_name: Arcane Archer
name: Arcane Archer
ranged_damage_bonus: +2/+2/+2
ranged_distance_bonus: "+10"
scc: mcdm.heroes.v1/kit/arcane-archer
source: mcdm.heroes.v1
speed_bonus: "+1"
type: kit
---

The [Arcane Archer](scc.v1:mcdm.heroes.v1/kit/arcane-archer) kit allows you to combine magic and [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) weapon [strikes](scc.v1:mcdm.heroes.v1/rule.combat/strike). Your lack of armor keeps you mobile, and your magic makes your arrows explode to devastate your foes.

##### Equipment

You wear no armor and wield a bow.

##### Kit Bonuses

**[Speed](scc.v1:mcdm.heroes.v1/rule.character/speed) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

**[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) Damage [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +2/+2/+2

**[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) [Distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +10

**Disengage [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

##### Signature Ability

###### Exploding Arrow

*Your ammunition explodes with magical energy.*

| **Magic, [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |
|-----------------------------------|------------------------------:|
| **📏 [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 15**                  | **🎯 One creature or object** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence):**

- **≤11:** 5 + A, R, I, or P fire damage
- **12-16:** 7 + A, R, I, or P fire damage
- **17+:** 10 + A, R, I, or P fire damage

**Effect:** One creature or object of your choice within 2 squares of the target takes fire damage equal to the [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) score used for this ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 15'
effects:
    - effect: One creature or object of your choice within 2 squares of the target takes fire damage equal to the [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) score used for this ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 5 + A, R, I, or P fire damage
      tier2: 7 + A, R, I, or P fire damage
      tier3: 10 + A, R, I, or P fire damage
feature_type: ability
flavor: Your ammunition explodes with magical energy.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 15'
    effect: One creature or object of your choice within 2 squares of the target takes fire damage equal to the [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) score used for this ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    flavor: Your ammunition explodes with magical energy.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Exploding Arrow
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    subtype: signature
    target: One creature or object
    tier1: 5 + A, R, I, or P fire damage
    tier2: 7 + A, R, I, or P fire damage
    tier3: 10 + A, R, I, or P fire damage
    type: ability
name: Exploding Arrow
target: One creature or object
type: feature
usage: Main action
```
