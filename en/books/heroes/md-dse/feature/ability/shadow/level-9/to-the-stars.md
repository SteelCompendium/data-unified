---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: shadow
cost: 11 Insight
cost_amount: "11"
cost_resource: Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + A fire damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 8
      tier2: 7 + A fire damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10
      tier3: 11 + A fire damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 15
    - effect: The ground beneath a 3-[cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) area around the target's starting position is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).
      name: Effect
feature_type: ability
file_basename: to-the-stars
file_dpath: feature/ability/shadow/level-9
flavor: You attach your most potent explosive to your foe. Under less pressing circumstances, you're sure you could launch them into orbit.
item_id: to-the-stars
item_name: To the Stars
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "9"
name: To the Stars
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-9/to-the-stars
source: mcdm.heroes.v1
subclass: caustic-alchemy
target: One creature or object
tier1: 4 + A fire damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 8
tier2: 7 + A fire damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10
tier3: 11 + A fire damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 15
type: ability
---

```ds-feature
cost: 11 Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + A fire damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 8
      tier2: 7 + A fire damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10
      tier3: 11 + A fire damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 15
    - effect: The ground beneath a 3-[cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) area around the target's starting position is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).
      name: Effect
feature_type: ability
flavor: You attach your most potent explosive to your foe. Under less pressing circumstances, you're sure you could launch them into orbit.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: shadow
    cost: 11 Insight
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 4 + A fire damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 8
          tier2: 7 + A fire damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10
          tier3: 11 + A fire damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 15
        - effect: The ground beneath a 3-[cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) area around the target's starting position is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).
          name: Effect
    flavor: You attach your most potent explosive to your foe. Under less pressing circumstances, you're sure you could launch them into orbit.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "9"
    name: To the Stars
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-9/to-the-stars
    subclass: caustic-alchemy
    target: One creature or object
    tier1: 4 + A fire damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 8
    tier2: 7 + A fire damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10
    tier3: 11 + A fire damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 15
    type: ability
name: To the Stars
target: One creature or object
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
