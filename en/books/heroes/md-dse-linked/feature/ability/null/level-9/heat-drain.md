---
action_type: '[Maneuver](../../../../rule/combat/turn.md)'
class: "null"
cost: 11 Discipline
cost_amount: "11"
cost_resource: Discipline
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 8 + I cold damage; M < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
      tier2: 11 + I cold damage; M < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
      tier3: 15 + I cold damage; M < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
    - effect: While [restrained](../../../../condition/restrained.md) this way, the target takes cold damage equal to your [Intuition](../../../../rule/character/intuition.md) score at the start of each of your [turns](../../../../rule/combat/turn.md). Additionally, whenever the target damages another creature while [restrained](../../../../condition/restrained.md) this way, any [potency](../../../../rule/character/potency.md) associated with the damage is reduced by 2.
      name: Effect
feature_type: ability
file_basename: heat-drain
file_dpath: feature/ability/null/level-9
flavor: You drain all the heat from the target.
item_id: heat-drain
item_name: Heat Drain
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../../../../rule/combat/strike.md)'
level: "9"
name: Heat Drain
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
scc: mcdm.heroes.v1/feature.ability.null.level-9/heat-drain
source: mcdm.heroes.v1
subclass: cryokinetic
target: One creature
tier1: 8 + I cold damage; M < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
tier2: 11 + I cold damage; M < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
tier3: 15 + I cold damage; M < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
type: ability
---

```ds-feature
cost: 11 Discipline
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 8 + I cold damage; M < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
      tier2: 11 + I cold damage; M < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
      tier3: 15 + I cold damage; M < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
    - effect: While [restrained](../../../../condition/restrained.md) this way, the target takes cold damage equal to your [Intuition](../../../../rule/character/intuition.md) score at the start of each of your [turns](../../../../rule/combat/turn.md). Additionally, whenever the target damages another creature while [restrained](../../../../condition/restrained.md) this way, any [potency](../../../../rule/character/potency.md) associated with the damage is reduced by 2.
      name: Effect
feature_type: ability
flavor: You drain all the heat from the target.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: '[Maneuver](../../../../rule/combat/turn.md)'
    class: "null"
    cost: 11 Discipline
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effects:
        - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
          tier1: 8 + I cold damage; M < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
          tier2: 11 + I cold damage; M < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
          tier3: 15 + I cold damage; M < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
        - effect: While [restrained](../../../../condition/restrained.md) this way, the target takes cold damage equal to your [Intuition](../../../../rule/character/intuition.md) score at the start of each of your [turns](../../../../rule/combat/turn.md). Additionally, whenever the target damages another creature while [restrained](../../../../condition/restrained.md) this way, any [potency](../../../../rule/character/potency.md) associated with the damage is reduced by 2.
          name: Effect
    flavor: You drain all the heat from the target.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - Psionic
        - '[Strike](../../../../rule/combat/strike.md)'
    level: "9"
    name: Heat Drain
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.null.level-9/heat-drain
    subclass: cryokinetic
    target: One creature
    tier1: 8 + I cold damage; M < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
    tier2: 11 + I cold damage; M < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
    tier3: 15 + I cold damage; M < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
    type: ability
name: Heat Drain
target: One creature
type: feature
usage: '[Maneuver](../../../../rule/combat/turn.md)'
```
