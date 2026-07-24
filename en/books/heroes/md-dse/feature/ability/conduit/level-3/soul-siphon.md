---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 7 Piety
cost_amount: "7"
cost_resource: Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 7 + I corruption damage
      tier2: 10 + I corruption damage
      tier3: 15 + I corruption damage
    - effect: One ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) can spend any number of [Recoveries](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
      name: Effect
feature_type: ability
file_basename: soul-siphon
file_dpath: feature/ability/conduit/level-3
flavor: A beam of energy connects a foe to a friend, draining life from one to heal the other.
item_id: soul-siphon
item_name: Soul Siphon
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "3"
name: Soul Siphon
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
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
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 7 + I corruption damage
      tier2: 10 + I corruption damage
      tier3: 15 + I corruption damage
    - effect: One ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) can spend any number of [Recoveries](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
      name: Effect
feature_type: ability
flavor: A beam of energy connects a foe to a friend, draining life from one to heal the other.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    cost: 7 Piety
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
          tier1: 7 + I corruption damage
          tier2: 10 + I corruption damage
          tier3: 15 + I corruption damage
        - effect: One ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) can spend any number of [Recoveries](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
          name: Effect
    flavor: A beam of energy connects a foe to a friend, draining life from one to heal the other.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "3"
    name: Soul Siphon
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-3/soul-siphon
    target: One enemy
    tier1: 7 + I corruption damage
    tier2: 10 + I corruption damage
    tier3: 15 + I corruption damage
    type: ability
name: Soul Siphon
target: One enemy
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
