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
stamina_bonus: +6 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)
type: kit
---

The [Dual Wielder](scc.v1:mcdm.heroes.v1/kit/dual-wielder) kit is for folks who want to excel at using two weapons at the same time. Your fighting style maximizes the power of each weapon you have in hand, making you a whirling dealer of death.

##### Equipment

You wear medium armor and wield a light weapon and a medium weapon.

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 damage
      tier2: 6 damage
      tier3: 8 damage
    - effect: If you use this ability on your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), you can use it against one target, then use your maneuver and your move action for that [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) before using the ability against a second target. You still use the same [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) for both targets.
      name: Effect
feature_type: ability
flavor: Why strike once when you could do it twice?
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 4 damage
          tier2: 6 damage
          tier3: 8 damage
        - effect: If you use this ability on your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), you can use it against one target, then use your maneuver and your move action for that [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) before using the ability against a second target. You still use the same [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) for both targets.
          name: Effect
    flavor: Why strike once when you could do it twice?
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Double Strike
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
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
