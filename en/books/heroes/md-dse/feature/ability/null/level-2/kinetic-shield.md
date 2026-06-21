---
action_type: Maneuver
class: "null"
cost: 5 Discipline
cost_amount: "5"
cost_resource: Discipline
distance: Self
effect: While you have [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) from this ability, you can't be made [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) even while [dying](scc.v1:mcdm.heroes.v1/rule.health/dying).
feature_type: ability
file_basename: kinetic-shield
file_dpath: feature/ability/null/level-2
flavor: You manifest a force barrier that absorbs incoming kinetic energy.
item_id: kinetic-shield
item_name: Kinetic Shield
keywords:
    - Psionic
level: "2"
name: Kinetic Shield
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.null.level-2/kinetic-shield
source: mcdm.heroes.v1
target: Self
tier1: You gain 10 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina).
tier2: You gain 15 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina).
tier3: You gain 20 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina).
type: ability
---

```ds-feature
cost: 5 Discipline
distance: Self
effects:
    - effect: While you have [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) from this ability, you can't be made [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) even while [dying](scc.v1:mcdm.heroes.v1/rule.health/dying).
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: You gain 10 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina).
      tier2: You gain 15 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina).
      tier3: You gain 20 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina).
feature_type: ability
flavor: You manifest a force barrier that absorbs incoming kinetic energy.
keywords:
    - Psionic
metadata:
    action_type: Maneuver
    class: "null"
    cost: 5 Discipline
    distance: Self
    effect: While you have [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) from this ability, you can't be made [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) even while [dying](scc.v1:mcdm.heroes.v1/rule.health/dying).
    flavor: You manifest a force barrier that absorbs incoming kinetic energy.
    keywords:
        - Psionic
    level: "2"
    name: Kinetic Shield
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.null.level-2/kinetic-shield
    target: Self
    tier1: You gain 10 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina).
    tier2: You gain 15 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina).
    tier3: You gain 20 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina).
    type: ability
name: Kinetic Shield
target: Self
type: feature
usage: Maneuver
```
