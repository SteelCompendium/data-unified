---
equipment_text: You wear light armor and wield a medium weapon.
file_basename: battlemind
file_dpath: kit
flavor: Who says lightly armored heroes can't also be hard to move? You just need to employ some psionics! The Battlemind kit harnesses the power of your mind to make you harder to move—and to make your foes easier to push around.
item_id: battlemind
item_name: Battlemind
name: Battlemind
scc: mcdm.heroes.v1/kit/battlemind
source: mcdm.heroes.v1
type: kit
---

Who says lightly armored heroes can't also be hard to move? You just need to employ some psionics! The [Battlemind](scc.v1:mcdm.heroes.v1/kit/battlemind) kit harnesses the power of your mind to make you harder to move—and to make your foes easier to push around.

##### Equipment

You wear light armor and wield a medium weapon.

##### Kit Bonuses

**[Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +3 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)

**[Speed](scc.v1:mcdm.heroes.v1/rule.character/speed) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +2

**[Stability](scc.v1:mcdm.heroes.v1/rule.character/stability) [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

**[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) Damage [Bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +2/+2/+2

##### Signature Ability

###### Unmooring

*Your weapon unleashes psionic energy that reduces your target's weight.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), Psionic, [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|------------------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**                     | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence):**

- **≤11:** 5 + M, R, I, or P damage
- **12-16:** 8 + M, R, I, or P damage
- **17+:** 11 + M, R, I, or P damage

**Effect:** Until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), any [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) that affects the target has its [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) increased by 2.

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: Until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), any [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) that affects the target has its [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) increased by 2.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 5 + M, R, I, or P damage
      tier2: 8 + M, R, I, or P damage
      tier3: 11 + M, R, I, or P damage
feature_type: ability
flavor: Your weapon unleashes psionic energy that reduces your target's weight.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: Until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), any [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) that affects the target has its [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) increased by 2.
    flavor: Your weapon unleashes psionic energy that reduces your target's weight.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Unmooring
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    subtype: signature
    target: One creature
    tier1: 5 + M, R, I, or P damage
    tier2: 8 + M, R, I, or P damage
    tier3: 11 + M, R, I, or P damage
    type: ability
name: Unmooring
target: One creature
type: feature
usage: Main action
```
