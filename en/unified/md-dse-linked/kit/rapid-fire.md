---
disengage_bonus: "+1"
equipment_text: You wear light armor and wield a bow.
file_basename: rapid-fire
file_dpath: kit
flavor: The Rapid-Fire kit is for archers who want to deal maximum damage by shooting as many arrows as possible into nearby enemies. With this kit, your fighting technique focuses on peppering foes before they can get close enough to counterattack.
item_id: rapid-fire
item_name: Rapid-Fire
kit_type: Martial
name: Rapid-Fire
ranged_damage_bonus: +2/+2/+2
ranged_distance_bonus: "+7"
scc: mcdm.heroes.v1/kit/rapid-fire
source: mcdm.heroes.v1
speed_bonus: "+1"
stamina_bonus: +3 per [echelon](../rule/general/echelon.md)
type: kit
---

The Rapid-Fire kit is for archers who want to deal maximum damage by shooting as many arrows as possible into nearby enemies. With this kit, your fighting technique focuses on peppering foes before they can get close enough to counterattack.

##### Equipment

You wear light armor and wield a bow.

```ds-feature
distance: '[Ranged](../rule/combat/ranged.md) 12'
effects:
    - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
      tier1: 4 damage
      tier2: 6 damage
      tier3: 8 damage
feature_type: ability
flavor: When you fire two arrows back-to-back, both hit their mark.
keywords:
    - '[Ranged](../rule/combat/ranged.md)'
    - '[Strike](../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Ranged](../rule/combat/ranged.md) 12'
    effects:
        - roll: Power Roll + [Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)
          tier1: 4 damage
          tier2: 6 damage
          tier3: 8 damage
    flavor: When you fire two arrows back-to-back, both hit their mark.
    keywords:
        - '[Ranged](../rule/combat/ranged.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Two Shot
    power_roll_characteristic: '[Might](../rule/character/might.md) or [Agility](../rule/character/agility.md)'
    subtype: signature
    target: Two creatures or objects
    tier1: 4 damage
    tier2: 6 damage
    tier3: 8 damage
    type: ability
name: Two Shot
target: Two creatures or objects
type: feature
usage: Main action
```
