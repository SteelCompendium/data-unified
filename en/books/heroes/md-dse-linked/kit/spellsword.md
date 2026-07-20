---
equipment_text: You wear light armor and wield a shield and a medium weapon.
file_basename: spellsword
file_dpath: kit
flavor: The Spellsword kit combines melee strikes and a little bit of magic, letting you create a warrior who doesn't have to choose between the incantation and the blade.
item_id: spellsword
item_name: Spellsword
melee_damage_bonus: +2/+2/+2
name: Spellsword
scc: mcdm.heroes.v1/kit/spellsword
source: mcdm.heroes.v1
speed_bonus: "+1"
stability_bonus: "+1"
stamina_bonus: +6 per [echelon](../rule/general/echelon.md)
type: kit
---

The [Spellsword](spellsword.md) kit combines [melee](../rule/combat/melee.md) [strikes](../rule/combat/strike.md) and a little bit of magic, letting you create a warrior who doesn't have to choose between the incantation and the blade.

##### Equipment

You wear light armor and wield a shield and a medium weapon.

```ds-feature
distance: '[Melee](../rule/combat/melee.md) 1'
effects:
    - effect: A creature or object of your choice within 2 squares of the target takes lightning damage equal to the [characteristic](../rule/character/characteristic.md) score used for this ability's [power roll](../rule/dice/power-roll.md).
    - roll: Power Roll + [Might](../rule/character/might.md), [Reason](../rule/character/reason.md), [Intuition](../rule/character/intuition.md), or [Presence](../rule/character/presence.md)
      tier1: 5 + M, R, I, or P lightning damage
      tier2: 8 + M, R, I, or P lightning damage
      tier3: 11 + M, R, I, or P lightning damage
feature_type: ability
flavor: Lightning jumps from your weapon as you strike to harm a nearby foe.
keywords:
    - Magic
    - '[Melee](../rule/combat/melee.md)'
    - '[Strike](../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](../rule/combat/melee.md) 1'
    effect: A creature or object of your choice within 2 squares of the target takes lightning damage equal to the [characteristic](../rule/character/characteristic.md) score used for this ability's [power roll](../rule/dice/power-roll.md).
    flavor: Lightning jumps from your weapon as you strike to harm a nearby foe.
    keywords:
        - Magic
        - '[Melee](../rule/combat/melee.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Leaping Lightning
    power_roll_characteristic: '[Might](../rule/character/might.md), [Reason](../rule/character/reason.md), [Intuition](../rule/character/intuition.md), or [Presence](../rule/character/presence.md)'
    subtype: signature
    target: One creature or object
    tier1: 5 + M, R, I, or P lightning damage
    tier2: 8 + M, R, I, or P lightning damage
    tier3: 11 + M, R, I, or P lightning damage
    type: ability
name: Leaping Lightning
target: One creature or object
type: feature
usage: Main action
```
