---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: "null"
cost: 9 Discipline
cost_amount: "9"
cost_resource: Discipline
distance: Self; see below
effects:
    - effect: You can [shift](../../../../movement/shifting.md) up to your [speed](../../../../rule/character/speed.md), and squares occupied by enemies or objects are not [difficult terrain](../../../../movement/difficult-terrain.md) for this [shift](../../../../movement/shifting.md). You make one [power roll](../../../../rule/dice/power-roll.md) that targets each enemy you moved through during this [shift](../../../../movement/shifting.md).
      name: Effect
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 6 damage; M < WEAK, [dazed](../../../../condition/dazed.md)
      tier2: 8 damage; M < AVERAGE, [dazed](../../../../condition/dazed.md)
      tier3: 12 damage; M < STRONG, [dazed](../../../../condition/dazed.md)
feature_type: ability
file_basename: phase-step
file_dpath: feature/ability/null/level-6
flavor: You weaken your connection to this manifold, allowing you to move through and damage enemies.
item_id: phase-step
item_name: Phase Step
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - Weapon
level: "6"
name: Phase Step
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.null.level-6/phase-step
source: mcdm.heroes.v1
subclass: chronokinetic
target: Self
tier1: 6 damage; M < WEAK, [dazed](../../../../condition/dazed.md)
tier2: 8 damage; M < AVERAGE, [dazed](../../../../condition/dazed.md)
tier3: 12 damage; M < STRONG, [dazed](../../../../condition/dazed.md)
type: ability
---

```ds-feature
cost: 9 Discipline
distance: Self; see below
effects:
    - effect: You can [shift](../../../../movement/shifting.md) up to your [speed](../../../../rule/character/speed.md), and squares occupied by enemies or objects are not [difficult terrain](../../../../movement/difficult-terrain.md) for this [shift](../../../../movement/shifting.md). You make one [power roll](../../../../rule/dice/power-roll.md) that targets each enemy you moved through during this [shift](../../../../movement/shifting.md).
      name: Effect
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 6 damage; M < WEAK, [dazed](../../../../condition/dazed.md)
      tier2: 8 damage; M < AVERAGE, [dazed](../../../../condition/dazed.md)
      tier3: 12 damage; M < STRONG, [dazed](../../../../condition/dazed.md)
feature_type: ability
flavor: You weaken your connection to this manifold, allowing you to move through and damage enemies.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: "null"
    cost: 9 Discipline
    distance: Self; see below
    effects:
        - effect: You can [shift](../../../../movement/shifting.md) up to your [speed](../../../../rule/character/speed.md), and squares occupied by enemies or objects are not [difficult terrain](../../../../movement/difficult-terrain.md) for this [shift](../../../../movement/shifting.md). You make one [power roll](../../../../rule/dice/power-roll.md) that targets each enemy you moved through during this [shift](../../../../movement/shifting.md).
          name: Effect
        - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
          tier1: 6 damage; M < WEAK, [dazed](../../../../condition/dazed.md)
          tier2: 8 damage; M < AVERAGE, [dazed](../../../../condition/dazed.md)
          tier3: 12 damage; M < STRONG, [dazed](../../../../condition/dazed.md)
    flavor: You weaken your connection to this manifold, allowing you to move through and damage enemies.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - Psionic
        - Weapon
    level: "6"
    name: Phase Step
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.null.level-6/phase-step
    subclass: chronokinetic
    target: Self
    tier1: 6 damage; M < WEAK, [dazed](../../../../condition/dazed.md)
    tier2: 8 damage; M < AVERAGE, [dazed](../../../../condition/dazed.md)
    tier3: 12 damage; M < STRONG, [dazed](../../../../condition/dazed.md)
    type: ability
name: Phase Step
target: Self
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
