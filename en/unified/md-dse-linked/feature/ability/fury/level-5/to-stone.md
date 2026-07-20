---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: While the target is [slowed](../../../../condition/slowed.md) this way, any other effect that would make the target [slowed](../../../../condition/slowed.md) instead makes them [restrained](../../../../condition/restrained.md) by this ability. Additionally, a creature who fails the [saving throw](../../../../rule/general/saving-throw.md) while [restrained](../../../../condition/restrained.md) this way is petrified until they are given a [supernatural](../../../../rule/general/supernatural.md) cure or you choose to reverse the effect (no action required).
feature_type: ability
file_basename: to-stone
file_dpath: feature/ability/fury/level-5
flavor: You channel the Primordial Chaos into blows that petrify your foe... literally.
item_id: to-stone
item_name: To Stone!
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "5"
name: To Stone!
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.fury.level-5/to-stone
source: mcdm.heroes.v1
target: One creature
tier1: 9 + M damage; M < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
tier2: 13 + M damage; M < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
tier3: 18 + M damage; M < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: While the target is [slowed](../../../../condition/slowed.md) this way, any other effect that would make the target [slowed](../../../../condition/slowed.md) instead makes them [restrained](../../../../condition/restrained.md) by this ability. Additionally, a creature who fails the [saving throw](../../../../rule/general/saving-throw.md) while [restrained](../../../../condition/restrained.md) this way is petrified until they are given a [supernatural](../../../../rule/general/supernatural.md) cure or you choose to reverse the effect (no action required).
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 9 + M damage; M < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
      tier2: 13 + M damage; M < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
      tier3: 18 + M damage; M < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
feature_type: ability
flavor: You channel the Primordial Chaos into blows that petrify your foe... literally.
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: fury
    cost: 9 Ferocity
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: While the target is [slowed](../../../../condition/slowed.md) this way, any other effect that would make the target [slowed](../../../../condition/slowed.md) instead makes them [restrained](../../../../condition/restrained.md) by this ability. Additionally, a creature who fails the [saving throw](../../../../rule/general/saving-throw.md) while [restrained](../../../../condition/restrained.md) this way is petrified until they are given a [supernatural](../../../../rule/general/supernatural.md) cure or you choose to reverse the effect (no action required).
    flavor: You channel the Primordial Chaos into blows that petrify your foe... literally.
    keywords:
        - Magic
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "5"
    name: To Stone!
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-5/to-stone
    target: One creature
    tier1: 9 + M damage; M < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
    tier2: 13 + M damage; M < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
    tier3: 18 + M damage; M < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
    type: ability
name: To Stone!
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
