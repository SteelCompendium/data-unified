---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: elementalist
cost: 5 Essence
cost_amount: "5"
cost_resource: Essence
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target is [teleport](scc.v1:mcdm.heroes.v1/movement/teleport)ed to another space within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). Make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that affects each enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target's new space.
      name: Effect
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 3 fire damage
      tier2: 5 fire damage
      tier3: 8 fire damage
feature_type: ability
file_basename: translated-through-flame
file_dpath: feature/ability/elementalist/level-2
flavor: Your ally disappears, then reappears in a burst of fire.
item_id: translated-through-flame
item_name: Translated Through Flame
keywords:
    - Fire
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Void
level: "2"
name: Translated Through Flame
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-2/translated-through-flame
source: mcdm.heroes.v1
target: Self or one ally
tier1: 3 fire damage
tier2: 5 fire damage
tier3: 8 fire damage
type: ability
---

```ds-feature
cost: 5 Essence
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target is [teleport](scc.v1:mcdm.heroes.v1/movement/teleport)ed to another space within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). Make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that affects each enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target's new space.
      name: Effect
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 3 fire damage
      tier2: 5 fire damage
      tier3: 8 fire damage
feature_type: ability
flavor: Your ally disappears, then reappears in a burst of fire.
keywords:
    - Fire
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Void
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: elementalist
    cost: 5 Essence
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - effect: The target is [teleport](scc.v1:mcdm.heroes.v1/movement/teleport)ed to another space within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). Make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that affects each enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target's new space.
          name: Effect
        - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
          tier1: 3 fire damage
          tier2: 5 fire damage
          tier3: 8 fire damage
    flavor: Your ally disappears, then reappears in a burst of fire.
    keywords:
        - Fire
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - Void
    level: "2"
    name: Translated Through Flame
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-2/translated-through-flame
    target: Self or one ally
    tier1: 3 fire damage
    tier2: 5 fire damage
    tier3: 8 fire damage
    type: ability
name: Translated Through Flame
target: Self or one ally
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
