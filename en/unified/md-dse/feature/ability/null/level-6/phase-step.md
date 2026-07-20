---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: "null"
cost: 9 Discipline
cost_amount: "9"
cost_resource: Discipline
distance: Self; see below
effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed), and squares occupied by enemies or objects are not [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for this [shift](scc.v1:mcdm.heroes.v1/movement/shifting). You make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each enemy you moved through during this [shift](scc.v1:mcdm.heroes.v1/movement/shifting).
feature_type: ability
file_basename: phase-step
file_dpath: feature/ability/null/level-6
flavor: You weaken your connection to this manifold, allowing you to move through and damage enemies.
item_id: phase-step
item_name: Phase Step
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - Weapon
level: "6"
name: Phase Step
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.null.level-6/phase-step
source: mcdm.heroes.v1
subclass: chronokinetic
target: Self
tier1: 6 damage; M < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed)
tier2: 8 damage; M < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed)
tier3: 12 damage; M < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed)
type: ability
---

```ds-feature
cost: 9 Discipline
distance: Self; see below
effects:
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed), and squares occupied by enemies or objects are not [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for this [shift](scc.v1:mcdm.heroes.v1/movement/shifting). You make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each enemy you moved through during this [shift](scc.v1:mcdm.heroes.v1/movement/shifting).
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 6 damage; M < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed)
      tier2: 8 damage; M < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed)
      tier3: 12 damage; M < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed)
feature_type: ability
flavor: You weaken your connection to this manifold, allowing you to move through and damage enemies.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: "null"
    cost: 9 Discipline
    distance: Self; see below
    effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed), and squares occupied by enemies or objects are not [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for this [shift](scc.v1:mcdm.heroes.v1/movement/shifting). You make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each enemy you moved through during this [shift](scc.v1:mcdm.heroes.v1/movement/shifting).
    flavor: You weaken your connection to this manifold, allowing you to move through and damage enemies.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - Weapon
    level: "6"
    name: Phase Step
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.null.level-6/phase-step
    subclass: chronokinetic
    target: Self
    tier1: 6 damage; M < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed)
    tier2: 8 damage; M < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed)
    tier3: 12 damage; M < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed)
    type: ability
name: Phase Step
target: Self
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
