---
disengage_bonus: "+1"
equipment_text: You wear medium armor and wield a light weapon and a medium weapon.
file_basename: dual-wielder
file_dpath: kit
flavor: The Dual Wielder kit is for folks who want to excel at using two weapons at the same time. Your fighting style maximizes the power of each weapon you have in hand, making you a whirling dealer of death.
item_id: dual-wielder
item_name: Dual Wielder
kit_type: Martial
melee_damage_bonus: +2/+2/+2
name: Dual Wielder
scc: mcdm.heroes.v1/kit/dual-wielder
source: mcdm.heroes.v1
speed_bonus: "+2"
stamina_bonus: +6 per [echelon](../rule/general/echelon.md)
type: kit
---

The [Dual Wielder](dual-wielder.md) kit is for folks who want to excel at using two weapons at the same time. Your fighting style maximizes the power of each weapon you have in hand, making you a whirling dealer of death.

##### Equipment

You wear medium armor and wield a light weapon and a medium weapon.

```ds-feature
distance: '[Melee](../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
      tier1: 4 damage
      tier2: 6 damage
      tier3: 8 damage
    - effect: If you use this ability on your [turn](../rule/combat/turn.md), you can use it against one target, then use your maneuver and your move action for that [turn](../rule/combat/turn.md) before using the ability against a second target. You still use the same [power roll](../rule/dice/power-roll.md) for both targets.
      name: Effect
feature_type: ability
flavor: Why strike once when you could do it twice?
keywords:
    - '[Melee](../rule/combat/melee.md)'
    - '[Strike](../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](../rule/combat/melee.md) 1'
    effects:
        - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
          tier1: 4 damage
          tier2: 6 damage
          tier3: 8 damage
        - effect: If you use this ability on your [turn](../rule/combat/turn.md), you can use it against one target, then use your maneuver and your move action for that [turn](../rule/combat/turn.md) before using the ability against a second target. You still use the same [power roll](../rule/dice/power-roll.md) for both targets.
          name: Effect
    flavor: Why strike once when you could do it twice?
    keywords:
        - '[Melee](../rule/combat/melee.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Double Strike
    power_roll_characteristic: '[Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)'
    subtype: signature
    target: Two creatures or objects
    tier1: 4 damage
    tier2: 6 damage
    tier3: 8 damage
    type: ability
name: Double Strike
target: Two creatures or objects
type: feature
usage: Main action
```
