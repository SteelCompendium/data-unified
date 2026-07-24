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

The [Arcane Archer](arcane-archer.md) kit allows you to combine magic and [ranged](../rule/combat/ranged.md) weapon [strikes](../rule/combat/strike.md). Your lack of armor keeps you mobile, and your magic makes your arrows explode to devastate your foes.

##### Equipment

You wear no armor and wield a bow.

```ds-feature
distance: '[Ranged](../rule/combat/ranged.md) 15'
effects:
    - roll: Power Roll + [Agility](../rule/character/agility.md), [Reason](../rule/character/reason.md), [Intuition](../rule/character/intuition.md), or [Presence](../rule/character/presence.md)
      tier1: 5 + A, R, I, or P fire damage
      tier2: 7 + A, R, I, or P fire damage
      tier3: 10 + A, R, I, or P fire damage
    - effect: One creature or object of your choice within 2 squares of the target takes fire damage equal to the [characteristic](../rule/character/characteristic.md) score used for this ability's [power roll](../rule/dice/power-roll.md).
      name: Effect
feature_type: ability
flavor: Your ammunition explodes with magical energy.
keywords:
    - Magic
    - '[Ranged](../rule/combat/ranged.md)'
    - '[Strike](../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Ranged](../rule/combat/ranged.md) 15'
    effects:
        - roll: Power Roll + [Agility](../rule/character/agility.md), [Reason](../rule/character/reason.md), [Intuition](../rule/character/intuition.md), or [Presence](../rule/character/presence.md)
          tier1: 5 + A, R, I, or P fire damage
          tier2: 7 + A, R, I, or P fire damage
          tier3: 10 + A, R, I, or P fire damage
        - effect: One creature or object of your choice within 2 squares of the target takes fire damage equal to the [characteristic](../rule/character/characteristic.md) score used for this ability's [power roll](../rule/dice/power-roll.md).
          name: Effect
    flavor: Your ammunition explodes with magical energy.
    keywords:
        - Magic
        - '[Ranged](../rule/combat/ranged.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Exploding Arrow
    power_roll_characteristic: '[Agility](../rule/character/agility.md), [Reason](../rule/character/reason.md), [Intuition](../rule/character/intuition.md), or [Presence](../rule/character/presence.md)'
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
