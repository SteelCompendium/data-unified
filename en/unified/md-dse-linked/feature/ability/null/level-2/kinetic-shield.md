---
action_type: Maneuver
class: "null"
cost: 5 Discipline
cost_amount: "5"
cost_resource: Discipline
distance: Self
effect: While you have [temporary Stamina](../../../../rule/health/temporary-stamina.md) from this ability, you can't be made [bleeding](../../../../condition/bleeding.md) even while [dying](../../../../rule/health/dying.md).
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
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
scc: mcdm.heroes.v1/feature.ability.null.level-2/kinetic-shield
source: mcdm.heroes.v1
target: Self
tier1: You gain 10 [temporary Stamina](../../../../rule/health/temporary-stamina.md).
tier2: You gain 15 [temporary Stamina](../../../../rule/health/temporary-stamina.md).
tier3: You gain 20 [temporary Stamina](../../../../rule/health/temporary-stamina.md).
type: ability
---

```ds-feature
cost: 5 Discipline
distance: Self
effects:
    - effect: While you have [temporary Stamina](../../../../rule/health/temporary-stamina.md) from this ability, you can't be made [bleeding](../../../../condition/bleeding.md) even while [dying](../../../../rule/health/dying.md).
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: You gain 10 [temporary Stamina](../../../../rule/health/temporary-stamina.md).
      tier2: You gain 15 [temporary Stamina](../../../../rule/health/temporary-stamina.md).
      tier3: You gain 20 [temporary Stamina](../../../../rule/health/temporary-stamina.md).
feature_type: ability
flavor: You manifest a force barrier that absorbs incoming kinetic energy.
keywords:
    - Psionic
metadata:
    action_type: Maneuver
    class: "null"
    cost: 5 Discipline
    distance: Self
    effect: While you have [temporary Stamina](../../../../rule/health/temporary-stamina.md) from this ability, you can't be made [bleeding](../../../../condition/bleeding.md) even while [dying](../../../../rule/health/dying.md).
    flavor: You manifest a force barrier that absorbs incoming kinetic energy.
    keywords:
        - Psionic
    level: "2"
    name: Kinetic Shield
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.null.level-2/kinetic-shield
    target: Self
    tier1: You gain 10 [temporary Stamina](../../../../rule/health/temporary-stamina.md).
    tier2: You gain 15 [temporary Stamina](../../../../rule/health/temporary-stamina.md).
    tier3: You gain 20 [temporary Stamina](../../../../rule/health/temporary-stamina.md).
    type: ability
name: Kinetic Shield
target: Self
type: feature
usage: Maneuver
```
