---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 3 Piety
cost_amount: "3"
cost_resource: Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 3 + I lightning damage
      tier2: 6 + I lightning damage
      tier3: 9 + I lightning damage
    - effect: The first time on a [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) that the target deals damage to another creature, the target of this ability takes 1d10 lightning damage (save ends).
      name: Effect
feature_type: ability
file_basename: violence-will-not-aid-thee
file_dpath: feature/ability/conduit/level-1
flavor: After some holy lightning, your enemy will think twice about their next attack.
item_id: violence-will-not-aid-thee
item_name: Violence Will Not Aid Thee
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Violence Will Not Aid Thee
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/violence-will-not-aid-thee
source: mcdm.heroes.v1
target: One creature
tier1: 3 + I lightning damage
tier2: 6 + I lightning damage
tier3: 9 + I lightning damage
type: ability
---

```ds-feature
cost: 3 Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 3 + I lightning damage
      tier2: 6 + I lightning damage
      tier3: 9 + I lightning damage
    - effect: The first time on a [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) that the target deals damage to another creature, the target of this ability takes 1d10 lightning damage (save ends).
      name: Effect
feature_type: ability
flavor: After some holy lightning, your enemy will think twice about their next attack.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    cost: 3 Piety
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
          tier1: 3 + I lightning damage
          tier2: 6 + I lightning damage
          tier3: 9 + I lightning damage
        - effect: The first time on a [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) that the target deals damage to another creature, the target of this ability takes 1d10 lightning damage (save ends).
          name: Effect
    flavor: After some holy lightning, your enemy will think twice about their next attack.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Violence Will Not Aid Thee
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/violence-will-not-aid-thee
    target: One creature
    tier1: 3 + I lightning damage
    tier2: 6 + I lightning damage
    tier3: 9 + I lightning damage
    type: ability
name: Violence Will Not Aid Thee
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
