---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: "null"
cost: 9 Discipline
cost_amount: "9"
cost_resource: Discipline
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 10 + A damage; A < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier2: 14 + A damage; A < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier3: 18 + A damage; A < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    - effect: While [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way, the target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on the [Escape Grab](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/escape-grab) maneuver. Each time they use that maneuver, they take damage equal to twice your [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score.
      name: Effect
feature_type: ability
file_basename: iron-grip
file_dpath: feature/ability/null/level-5
flavor: You grab the target with [supernatural](scc.v1:mcdm.heroes.v1/rule.general/supernatural) force.
item_id: iron-grip
item_name: Iron Grip
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "5"
name: Iron Grip
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.null.level-5/iron-grip
source: mcdm.heroes.v1
target: One creature
tier1: 10 + A damage; A < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
tier2: 14 + A damage; A < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
tier3: 18 + A damage; A < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
type: ability
---

```ds-feature
cost: 9 Discipline
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 10 + A damage; A < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier2: 14 + A damage; A < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier3: 18 + A damage; A < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    - effect: While [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way, the target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on the [Escape Grab](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/escape-grab) maneuver. Each time they use that maneuver, they take damage equal to twice your [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score.
      name: Effect
feature_type: ability
flavor: You grab the target with [supernatural](scc.v1:mcdm.heroes.v1/rule.general/supernatural) force.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: "null"
    cost: 9 Discipline
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 10 + A damage; A < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
          tier2: 14 + A damage; A < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
          tier3: 18 + A damage; A < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
        - effect: While [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way, the target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on the [Escape Grab](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/escape-grab) maneuver. Each time they use that maneuver, they take damage equal to twice your [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score.
          name: Effect
    flavor: You grab the target with [supernatural](scc.v1:mcdm.heroes.v1/rule.general/supernatural) force.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "5"
    name: Iron Grip
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.null.level-5/iron-grip
    target: One creature
    tier1: 10 + A damage; A < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    tier2: 14 + A damage; A < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    tier3: 18 + A damage; A < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    type: ability
name: Iron Grip
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
