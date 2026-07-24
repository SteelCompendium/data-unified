---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 3 + I holy damage
      tier2: 6 + I holy damage
      tier3: 9 + I holy damage
    - effect: You or one ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) equal to your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score.
      name: Effect
feature_type: ability
file_basename: warriors-prayer
file_dpath: feature/ability/conduit/level-1
flavor: Your quickly uttered prayer lends aggressive divine energy to a friend engaged in [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee).
item_id: warriors-prayer
item_name: Warrior's Prayer
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Warrior's Prayer
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/warriors-prayer
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 3 + I holy damage
tier2: 6 + I holy damage
tier3: 9 + I holy damage
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 3 + I holy damage
      tier2: 6 + I holy damage
      tier3: 9 + I holy damage
    - effect: You or one ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) equal to your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score.
      name: Effect
feature_type: ability
flavor: Your quickly uttered prayer lends aggressive divine energy to a friend engaged in [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee).
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
          tier1: 3 + I holy damage
          tier2: 6 + I holy damage
          tier3: 9 + I holy damage
        - effect: You or one ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) equal to your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score.
          name: Effect
    flavor: Your quickly uttered prayer lends aggressive divine energy to a friend engaged in [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee).
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Warrior's Prayer
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/warriors-prayer
    subtype: signature
    target: One creature
    tier1: 3 + I holy damage
    tier2: 6 + I holy damage
    tier3: 9 + I holy damage
    type: ability
name: Warrior's Prayer
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
