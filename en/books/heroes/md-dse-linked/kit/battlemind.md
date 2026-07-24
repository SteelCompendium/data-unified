---
equipment_text: You wear light armor and wield a medium weapon.
file_basename: battlemind
file_dpath: kit
flavor: Who says lightly armored heroes can't also be hard to move? You just need to employ some psionics! The Battlemind kit harnesses the power of your mind to make you harder to move—and to make your foes easier to push around.
item_id: battlemind
item_name: Battlemind
melee_damage_bonus: +2/+2/+2
name: Battlemind
scc: mcdm.heroes.v1/kit/battlemind
source: mcdm.heroes.v1
speed_bonus: "+2"
stability_bonus: "+1"
stamina_bonus: +3 per [echelon](../rule/general/echelon.md)
type: kit
---

Who says lightly armored heroes can't also be hard to move? You just need to employ some psionics! The [Battlemind](battlemind.md) kit harnesses the power of your mind to make you harder to move—and to make your foes easier to push around.

##### Equipment

You wear light armor and wield a medium weapon.

```ds-feature
distance: '[Melee](../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../rule/character/might.md), [Reason](../rule/character/reason.md), [Intuition](../rule/character/intuition.md), or [Presence](../rule/character/presence.md)
      tier1: 5 + M, R, I, or P damage
      tier2: 8 + M, R, I, or P damage
      tier3: 11 + M, R, I, or P damage
    - effect: Until the end of the target's next [turn](../rule/combat/turn.md), any [forced movement](../movement/forced-movement.md) that affects the target has its [distance](../rule/combat/distance.md) increased by 2.
      name: Effect
feature_type: ability
flavor: Your weapon unleashes psionic energy that reduces your target's weight.
keywords:
    - '[Melee](../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](../rule/combat/melee.md) 1'
    effects:
        - roll: Power Roll + [Might](../rule/character/might.md), [Reason](../rule/character/reason.md), [Intuition](../rule/character/intuition.md), or [Presence](../rule/character/presence.md)
          tier1: 5 + M, R, I, or P damage
          tier2: 8 + M, R, I, or P damage
          tier3: 11 + M, R, I, or P damage
        - effect: Until the end of the target's next [turn](../rule/combat/turn.md), any [forced movement](../movement/forced-movement.md) that affects the target has its [distance](../rule/combat/distance.md) increased by 2.
          name: Effect
    flavor: Your weapon unleashes psionic energy that reduces your target's weight.
    keywords:
        - '[Melee](../rule/combat/melee.md)'
        - Psionic
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Unmooring
    power_roll_characteristic: '[Might](../rule/character/might.md), [Reason](../rule/character/reason.md), [Intuition](../rule/character/intuition.md), or [Presence](../rule/character/presence.md)'
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
