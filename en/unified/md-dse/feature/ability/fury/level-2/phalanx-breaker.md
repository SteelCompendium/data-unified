---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: Self; see below
effects:
    - effect: You [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets up to three enemies you move [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during this [shift](scc.v1:mcdm.heroes.v1/movement/shifting).
      name: Effect
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 2 damage; A < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier2: 4 damage; A < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier3: 6 damage; A < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
feature_type: ability
file_basename: phalanx-breaker
file_dpath: feature/ability/fury/level-2
flavor: Organizing your forces like feckless creatures of Law. Pitiful.
item_id: phalanx-breaker
item_name: Phalanx-Breaker
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
level: "2"
name: Phalanx-Breaker
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-2/phalanx-breaker
source: mcdm.heroes.v1
target: Self
tier1: 2 damage; A < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier2: 4 damage; A < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier3: 6 damage; A < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: Self; see below
effects:
    - effect: You [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets up to three enemies you move [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during this [shift](scc.v1:mcdm.heroes.v1/movement/shifting).
      name: Effect
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 2 damage; A < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier2: 4 damage; A < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier3: 6 damage; A < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
feature_type: ability
flavor: Organizing your forces like feckless creatures of Law. Pitiful.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: fury
    cost: 5 Ferocity
    distance: Self; see below
    effects:
        - effect: You [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets up to three enemies you move [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during this [shift](scc.v1:mcdm.heroes.v1/movement/shifting).
          name: Effect
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: 2 damage; A < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
          tier2: 4 damage; A < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
          tier3: 6 damage; A < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    flavor: Organizing your forces like feckless creatures of Law. Pitiful.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Weapon
    level: "2"
    name: Phalanx-Breaker
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-2/phalanx-breaker
    target: Self
    tier1: 2 damage; A < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    tier2: 4 damage; A < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    tier3: 6 damage; A < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    type: ability
name: Phalanx-Breaker
target: Self
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
