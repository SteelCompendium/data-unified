---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: You conjure a [size](scc.v1:mcdm.heroes.v1/rule.character/size) 2 rolling machine that appears in an unoccupied space within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). The machine has 50 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and immunity all to poison and psychic damage. It disappears at the end of the encounter, if its [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) drops to 0, or if you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying). When the machine first appears, make the following [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) once, targeting each enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to it.
      name: Effect
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 3 damage
      tier2: 5 damage
      tier3: 8 damage
feature_type: ability
file_basename: gods-machine
file_dpath: feature/ability/conduit/level-6
flavor: You conjure a whirring tank made of blades and metal.
item_id: gods-machine
item_name: Gods' Machine
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "6"
name: Gods' Machine
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-6/gods-machine
source: mcdm.heroes.v1
subclass: creation
target: Special
tier1: 3 damage
tier2: 5 damage
tier3: 8 damage
type: ability
---

```ds-feature
cost: 9 Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: You conjure a [size](scc.v1:mcdm.heroes.v1/rule.character/size) 2 rolling machine that appears in an unoccupied space within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). The machine has 50 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and immunity all to poison and psychic damage. It disappears at the end of the encounter, if its [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) drops to 0, or if you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying). When the machine first appears, make the following [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) once, targeting each enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to it.
      name: Effect
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 3 damage
      tier2: 5 damage
      tier3: 8 damage
feature_type: ability
flavor: You conjure a whirring tank made of blades and metal.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    cost: 9 Piety
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - effect: You conjure a [size](scc.v1:mcdm.heroes.v1/rule.character/size) 2 rolling machine that appears in an unoccupied space within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). The machine has 50 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and immunity all to poison and psychic damage. It disappears at the end of the encounter, if its [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) drops to 0, or if you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying). When the machine first appears, make the following [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) once, targeting each enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to it.
          name: Effect
        - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
          tier1: 3 damage
          tier2: 5 damage
          tier3: 8 damage
    flavor: You conjure a whirring tank made of blades and metal.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "6"
    name: Gods' Machine
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-6/gods-machine
    subclass: creation
    target: Special
    tier1: 3 damage
    tier2: 5 damage
    tier3: 8 damage
    type: ability
name: Gods' Machine
target: Special
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
