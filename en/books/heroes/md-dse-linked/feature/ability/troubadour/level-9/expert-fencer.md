---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: troubadour
cost: 11 Drama
cost_amount: "11"
cost_resource: Drama
distance: '[Melee](../../../../rule/combat/melee.md) 3'
effects:
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 15 + A damage
      tier2: 21 + A damage
      tier3: 28 + A damage; M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
    - effect: This ability can't obtain better than a tier 2 outcome unless the target is at maximum [distance](../../../../rule/combat/distance.md). If you obtain a tier 3 outcome with a natural 17 or higher, you gain 3 [surges](../../../../rule/resource/surge.md) that you can use immediately.
      name: Effect
feature_type: ability
file_basename: expert-fencer
file_dpath: feature/ability/troubadour/level-9
flavor: If you can land the [strike](../../../../rule/combat/strike.md), the crowd goes wild.
item_id: expert-fencer
item_name: Expert Fencer
keywords:
    - Charge
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "9"
name: Expert Fencer
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/expert-fencer
source: mcdm.heroes.v1
subclass: duelist
target: One creature or object
tier1: 15 + A damage
tier2: 21 + A damage
tier3: 28 + A damage; M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
type: ability
---

```ds-feature
cost: 11 Drama
distance: '[Melee](../../../../rule/combat/melee.md) 3'
effects:
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 15 + A damage
      tier2: 21 + A damage
      tier3: 28 + A damage; M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
    - effect: This ability can't obtain better than a tier 2 outcome unless the target is at maximum [distance](../../../../rule/combat/distance.md). If you obtain a tier 3 outcome with a natural 17 or higher, you gain 3 [surges](../../../../rule/resource/surge.md) that you can use immediately.
      name: Effect
feature_type: ability
flavor: If you can land the [strike](../../../../rule/combat/strike.md), the crowd goes wild.
keywords:
    - Charge
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: troubadour
    cost: 11 Drama
    distance: '[Melee](../../../../rule/combat/melee.md) 3'
    effects:
        - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
          tier1: 15 + A damage
          tier2: 21 + A damage
          tier3: 28 + A damage; M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
        - effect: This ability can't obtain better than a tier 2 outcome unless the target is at maximum [distance](../../../../rule/combat/distance.md). If you obtain a tier 3 outcome with a natural 17 or higher, you gain 3 [surges](../../../../rule/resource/surge.md) that you can use immediately.
          name: Effect
    flavor: If you can land the [strike](../../../../rule/combat/strike.md), the crowd goes wild.
    keywords:
        - Charge
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "9"
    name: Expert Fencer
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/expert-fencer
    subclass: duelist
    target: One creature or object
    tier1: 15 + A damage
    tier2: 21 + A damage
    tier3: 28 + A damage; M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
    type: ability
name: Expert Fencer
target: One creature or object
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
