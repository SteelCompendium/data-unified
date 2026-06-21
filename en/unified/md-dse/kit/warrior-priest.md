---
equipment_text: You wear heavy armor and wield a light weapon.
file_basename: warrior-priest
file_dpath: kit
flavor: The Warrior Priest kit imbues the power of the gods into your weapon, making it a smiting instrument. You wade into the fray without fear, thanks to the power of the divine... and the heavy armor you wear.
item_id: warrior-priest
item_name: Warrior Priest
name: Warrior Priest
scc: mcdm.heroes.v1/kit/warrior-priest
source: mcdm.heroes.v1
type: kit
---

The [Warrior Priest](scc.v1:mcdm.heroes.v1/kit/warrior-priest) kit imbues the power of the gods into your weapon, making it a smiting instrument. You wade into the fray without fear, thanks to the power of the divine... and the heavy armor you wear.

##### Equipment

You wear heavy armor and wield a light weapon.

##### Kit Bonuses

**[Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +9 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)

**[Speed](scc.v1:mcdm.heroes.v1/rule.character/speed) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

**[Stability](scc.v1:mcdm.heroes.v1/rule.character/stability) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

**[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) Damage [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1/+1/+1

##### Signature Ability

###### Weakening Brand

*The impact of your weapon brands your target for destruction.*

| **Magic, [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |
|----------------------------------|------------------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**                   | **🎯 One creature or object** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence):**

- **≤11:** 3 + M, R, I, or P holy damage
- **12-16:** 5 + M, R, I, or P holy damage
- **17+:** 8 + M, R, I, or P holy damage

**Effect:** Until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), they have [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) equal to the [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) score used for this ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: Until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), they have [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) equal to the [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) score used for this ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 3 + M, R, I, or P holy damage
      tier2: 5 + M, R, I, or P holy damage
      tier3: 8 + M, R, I, or P holy damage
feature_type: ability
flavor: The impact of your weapon brands your target for destruction.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: Until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), they have [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) equal to the [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) score used for this ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    flavor: The impact of your weapon brands your target for destruction.
    keywords:
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Weakening Brand
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    subtype: signature
    target: One creature or object
    tier1: 3 + M, R, I, or P holy damage
    tier2: 5 + M, R, I, or P holy damage
    tier3: 8 + M, R, I, or P holy damage
    type: ability
name: Weakening Brand
target: One creature or object
type: feature
usage: Main action
```
