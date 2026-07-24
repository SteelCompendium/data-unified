---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: censor
cost: 5 Wrath
cost_amount: "5"
cost_resource: Wrath
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 5 + M holy damage; M < WEAK, the target has fire weakness 3 (save ends)
      tier2: 9 + M holy damage; M < AVERAGE, the target has fire weakness 5 (save ends)
      tier3: 12 + M holy damage; M < STRONG, the target has fire weakness 7 (save ends)
    - effect: While the target has fire weakness from this ability, you can choose to have your abilities deal fire damage to the target instead of holy damage.
      name: Effect
feature_type: ability
file_basename: purifying-fire
file_dpath: feature/ability/censor/level-1
flavor: The gods judge, fire cleanses.
item_id: purifying-fire
item_name: Purifying Fire
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Purifying Fire
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.censor.level-1/purifying-fire
source: mcdm.heroes.v1
target: One creature
tier1: 5 + M holy damage; M < WEAK, the target has fire weakness 3 (save ends)
tier2: 9 + M holy damage; M < AVERAGE, the target has fire weakness 5 (save ends)
tier3: 12 + M holy damage; M < STRONG, the target has fire weakness 7 (save ends)
type: ability
---

```ds-feature
cost: 5 Wrath
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 5 + M holy damage; M < WEAK, the target has fire weakness 3 (save ends)
      tier2: 9 + M holy damage; M < AVERAGE, the target has fire weakness 5 (save ends)
      tier3: 12 + M holy damage; M < STRONG, the target has fire weakness 7 (save ends)
    - effect: While the target has fire weakness from this ability, you can choose to have your abilities deal fire damage to the target instead of holy damage.
      name: Effect
feature_type: ability
flavor: The gods judge, fire cleanses.
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: censor
    cost: 5 Wrath
    distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
    effects:
        - roll: Power Roll + [Might](../../../../rule/character/might.md)
          tier1: 5 + M holy damage; M < WEAK, the target has fire weakness 3 (save ends)
          tier2: 9 + M holy damage; M < AVERAGE, the target has fire weakness 5 (save ends)
          tier3: 12 + M holy damage; M < STRONG, the target has fire weakness 7 (save ends)
        - effect: While the target has fire weakness from this ability, you can choose to have your abilities deal fire damage to the target instead of holy damage.
          name: Effect
    flavor: The gods judge, fire cleanses.
    keywords:
        - Magic
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Purifying Fire
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/purifying-fire
    target: One creature
    tier1: 5 + M holy damage; M < WEAK, the target has fire weakness 3 (save ends)
    tier2: 9 + M holy damage; M < AVERAGE, the target has fire weakness 5 (save ends)
    tier3: 12 + M holy damage; M < STRONG, the target has fire weakness 7 (save ends)
    type: ability
name: Purifying Fire
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
