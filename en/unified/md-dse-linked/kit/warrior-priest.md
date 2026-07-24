---
equipment_text: You wear heavy armor and wield a light weapon.
file_basename: warrior-priest
file_dpath: kit
flavor: The Warrior Priest kit imbues the power of the gods into your weapon, making it a smiting instrument. You wade into the fray without fear, thanks to the power of the divine... and the heavy armor you wear.
item_id: warrior-priest
item_name: Warrior Priest
melee_damage_bonus: +1/+1/+1
name: Warrior Priest
scc: mcdm.heroes.v1/kit/warrior-priest
source: mcdm.heroes.v1
speed_bonus: "+1"
stability_bonus: "+1"
stamina_bonus: +9 per [echelon](../rule/general/echelon.md)
type: kit
---

The [Warrior Priest](warrior-priest.md) kit imbues the power of the gods into your weapon, making it a smiting instrument. You wade into the fray without fear, thanks to the power of the divine... and the heavy armor you wear.

##### Equipment

You wear heavy armor and wield a light weapon.

```ds-feature
distance: '[Melee](../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../rule/character/might.md), [Reason](../rule/character/reason.md), [Intuition](../rule/character/intuition.md), or [Presence](../rule/character/presence.md)
      tier1: 3 + M, R, I, or P holy damage
      tier2: 5 + M, R, I, or P holy damage
      tier3: 8 + M, R, I, or P holy damage
    - effect: Until the end of the target's next [turn](../rule/combat/turn.md), they have [damage weakness](../rule/damage/damage-weakness.md) equal to the [characteristic](../rule/character/characteristic.md) score used for this ability's [power roll](../rule/dice/power-roll.md).
      name: Effect
feature_type: ability
flavor: The impact of your weapon brands your target for destruction.
keywords:
    - Magic
    - '[Melee](../rule/combat/melee.md)'
    - '[Strike](../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](../rule/combat/melee.md) 1'
    effects:
        - roll: Power Roll + [Might](../rule/character/might.md), [Reason](../rule/character/reason.md), [Intuition](../rule/character/intuition.md), or [Presence](../rule/character/presence.md)
          tier1: 3 + M, R, I, or P holy damage
          tier2: 5 + M, R, I, or P holy damage
          tier3: 8 + M, R, I, or P holy damage
        - effect: Until the end of the target's next [turn](../rule/combat/turn.md), they have [damage weakness](../rule/damage/damage-weakness.md) equal to the [characteristic](../rule/character/characteristic.md) score used for this ability's [power roll](../rule/dice/power-roll.md).
          name: Effect
    flavor: The impact of your weapon brands your target for destruction.
    keywords:
        - Magic
        - '[Melee](../rule/combat/melee.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Weakening Brand
    power_roll_characteristic: '[Might](../rule/character/might.md), [Reason](../rule/character/reason.md), [Intuition](../rule/character/intuition.md), or [Presence](../rule/character/presence.md)'
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
