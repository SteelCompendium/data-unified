---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: conduit
cost: 7 Piety
cost_amount: "7"
cost_resource: Piety
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 7 + I corruption damage
      tier2: 10 + I corruption damage
      tier3: 15 + I corruption damage
    - effect: One ally within [distance](../../../../rule/combat/distance.md) can spend any number of [Recoveries](../../../../rule/health/recoveries.md).
      name: Effect
feature_type: ability
file_basename: soul-siphon
file_dpath: feature/ability/conduit/level-3
flavor: A beam of energy connects a foe to a friend, draining life from one to heal the other.
item_id: soul-siphon
item_name: Soul Siphon
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
level: "3"
name: Soul Siphon
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-3/soul-siphon
source: mcdm.heroes.v1
target: One enemy
tier1: 7 + I corruption damage
tier2: 10 + I corruption damage
tier3: 15 + I corruption damage
type: ability
---

```ds-feature
cost: 7 Piety
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 7 + I corruption damage
      tier2: 10 + I corruption damage
      tier3: 15 + I corruption damage
    - effect: One ally within [distance](../../../../rule/combat/distance.md) can spend any number of [Recoveries](../../../../rule/health/recoveries.md).
      name: Effect
feature_type: ability
flavor: A beam of energy connects a foe to a friend, draining life from one to heal the other.
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: conduit
    cost: 7 Piety
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effects:
        - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
          tier1: 7 + I corruption damage
          tier2: 10 + I corruption damage
          tier3: 15 + I corruption damage
        - effect: One ally within [distance](../../../../rule/combat/distance.md) can spend any number of [Recoveries](../../../../rule/health/recoveries.md).
          name: Effect
    flavor: A beam of energy connects a foe to a friend, draining life from one to heal the other.
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
    level: "3"
    name: Soul Siphon
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-3/soul-siphon
    target: One enemy
    tier1: 7 + I corruption damage
    tier2: 10 + I corruption damage
    tier3: 15 + I corruption damage
    type: ability
name: Soul Siphon
target: One enemy
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
