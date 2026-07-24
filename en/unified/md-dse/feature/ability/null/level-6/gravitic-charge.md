---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: "null"
cost: 9 Discipline
cost_amount: "9"
cost_resource: Discipline
distance: Self
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: Vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
      tier2: Vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
      tier3: Vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 9
    - effect: This movement ignores [stability](scc.v1:mcdm.heroes.v1/rule.character/stability). If you [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) into another creature, you resolve damage to both of you as if your [force move](scc.v1:mcdm.heroes.v1/movement/forced-movement)ment had ended, but you keep moving through that creature's space.
      name: Effect
feature_type: ability
file_basename: gravitic-charge
file_dpath: feature/ability/null/level-6
flavor: You channel your discipline into momentum that defies gravity.
item_id: gravitic-charge
item_name: Gravitic Charge
keywords:
    - Psionic
level: "6"
name: Gravitic Charge
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.null.level-6/gravitic-charge
source: mcdm.heroes.v1
subclass: metakinetic
target: Self
tier1: Vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
tier2: Vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
tier3: Vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 9
type: ability
---

```ds-feature
cost: 9 Discipline
distance: Self
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: Vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
      tier2: Vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
      tier3: Vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 9
    - effect: This movement ignores [stability](scc.v1:mcdm.heroes.v1/rule.character/stability). If you [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) into another creature, you resolve damage to both of you as if your [force move](scc.v1:mcdm.heroes.v1/movement/forced-movement)ment had ended, but you keep moving through that creature's space.
      name: Effect
feature_type: ability
flavor: You channel your discipline into momentum that defies gravity.
keywords:
    - Psionic
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: "null"
    cost: 9 Discipline
    distance: Self
    effects:
        - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
          tier1: Vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
          tier2: Vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
          tier3: Vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 9
        - effect: This movement ignores [stability](scc.v1:mcdm.heroes.v1/rule.character/stability). If you [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) into another creature, you resolve damage to both of you as if your [force move](scc.v1:mcdm.heroes.v1/movement/forced-movement)ment had ended, but you keep moving through that creature's space.
          name: Effect
    flavor: You channel your discipline into momentum that defies gravity.
    keywords:
        - Psionic
    level: "6"
    name: Gravitic Charge
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.null.level-6/gravitic-charge
    subclass: metakinetic
    target: Self
    tier1: Vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
    tier2: Vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
    tier3: Vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 9
    type: ability
name: Gravitic Charge
target: Self
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
