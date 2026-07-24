---
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
---


*Organizing your forces like feckless creatures of Law. Pitiful.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), Weapon**      | **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|------------------------|----------------:|
| **📏 Self; see below** |     **🎯 Self** |

**Effect:** You [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets up to three enemies you move [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during this [shift](scc.v1:mcdm.heroes.v1/movement/shifting).

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 2 damage; A < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
- **12-16:** 4 damage; A < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
- **17+:** 6 damage; A < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
