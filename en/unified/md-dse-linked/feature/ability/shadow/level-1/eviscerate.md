---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: shadow
cost: 3 Insight
cost_amount: "3"
cost_resource: Insight
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 4 + A damage; A < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
      tier2: 6 + A damage; A < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
      tier3: 10 + A damage; A < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
feature_type: ability
file_basename: eviscerate
file_dpath: feature/ability/shadow/level-1
flavor: You leave your foe bleeding out after a devastating attack.
item_id: eviscerate
item_name: Eviscerate
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Eviscerate
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/eviscerate
source: mcdm.heroes.v1
target: One creature
tier1: 4 + A damage; A < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
tier2: 6 + A damage; A < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
tier3: 10 + A damage; A < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
type: ability
---

```ds-feature
cost: 3 Insight
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 4 + A damage; A < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
      tier2: 6 + A damage; A < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
      tier3: 10 + A damage; A < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
feature_type: ability
flavor: You leave your foe bleeding out after a devastating attack.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: shadow
    cost: 3 Insight
    distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
    effects:
        - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
          tier1: 4 + A damage; A < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
          tier2: 6 + A damage; A < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
          tier3: 10 + A damage; A < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
    flavor: You leave your foe bleeding out after a devastating attack.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Eviscerate
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/eviscerate
    target: One creature
    tier1: 4 + A damage; A < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
    tier2: 6 + A damage; A < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
    tier3: 10 + A damage; A < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
    type: ability
name: Eviscerate
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
