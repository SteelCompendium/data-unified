---
disengage_bonus: "+1"
equipment_text: You wear light armor and wield a shield and a light weapon.
file_basename: raider
file_dpath: kit
flavor: The Raider kit keeps you protected while granting you full mobility, providing a boost to speed and distance that lets you run around the battlefield like a Viking warrior.
item_id: raider
item_name: Raider
melee_damage_bonus: +1/+1/+1
name: Raider
ranged_damage_bonus: +1/+1/+1
ranged_distance_bonus: "+5"
scc: mcdm.heroes.v1/kit/raider
source: mcdm.heroes.v1
speed_bonus: "+1"
stamina_bonus: +6 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)
type: kit
---

The [Raider](scc.v1:mcdm.heroes.v1/kit/raider) kit keeps you protected while granting you full mobility, providing a boost to [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) that lets you run around the battlefield like a Viking warrior.

##### Equipment

You wear light armor and wield a shield and a light weapon.

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 + M or A damage
      tier2: 6 + M or A damage
      tier3: 8 + M or A damage
    - effect: The target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on their next [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) made before the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Effect
feature_type: ability
flavor: You execute a brutal strike that leaves your foe reeling. (Previously known as "[Shock and Awe](scc.v1:mcdm.heroes.v1/feature.tactician.level-7/shock-and-awe)")
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 3 + M or A damage
          tier2: 6 + M or A damage
          tier3: 8 + M or A damage
        - effect: The target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on their next [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) made before the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
          name: Effect
    flavor: You execute a brutal strike that leaves your foe reeling. (Previously known as "[Shock and Awe](scc.v1:mcdm.heroes.v1/feature.tactician.level-7/shock-and-awe)")
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Raider's Awe
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    subtype: signature
    target: One creature
    tier1: 3 + M or A damage
    tier2: 6 + M or A damage
    tier3: 8 + M or A damage
    type: ability
name: Raider's Awe
target: One creature
type: feature
usage: Main action
```
