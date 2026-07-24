---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: tactician
cost: 11 Focus
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: Each target uses a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against one or more targets of your choosing, with each ability automatically obtaining a tier 3 outcome on the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll). After resolving the targets' abilities, you make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) against each original target.
      name: Effect
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: R < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier2: R < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier3: R < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
flavor: You trick your enemies into attacking each other and leave them confused by the aftermath.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Weapon
level: "9"
name: Their Lack of Focus Is Their Undoing
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-9/their-lack-of-focus-is-their-undoing
subclass: insurgent
target: Three enemies
tier1: R < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier2: R < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier3: R < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
type: ability
---


*You trick your enemies into attacking each other and leave them confused by the aftermath.*

| **Magic, [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged), Weapon** |      **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|---------------------------|---------------------:|
| **📏 [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10**          | **🎯 Three enemies** |

**Effect:** Each target uses a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against one or more targets of your choosing, with each ability automatically obtaining a tier 3 outcome on the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll). After resolving the targets' abilities, you make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) against each original target.

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** R < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
- **12-16:** R < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
- **17+:** R < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
