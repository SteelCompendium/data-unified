---
action_type: Free triggered
class: "null"
cost: 11 Discipline
cost_amount: "11"
cost_resource: Discipline
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: If the target loses their [turn](../../../../rule/combat/turn.md), the round continues as if they had acted. A target who doesn't lose their [turn](../../../../rule/combat/turn.md) takes psychic damage equal to twice your [Intuition](../../../../rule/character/intuition.md) score for each main action they take until the end of their next [turn](../../../../rule/combat/turn.md).
feature_type: ability
file_basename: arrestor-cycle
file_dpath: feature/ability/null/level-9
flavor: You trap your foe in a looping cycle of time, where they relive the last few seconds over and over again.
item_id: arrestor-cycle
item_name: Arrestor Cycle
keywords:
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "9"
name: Arrestor Cycle
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
scc: mcdm.heroes.v1/feature.ability.null.level-9/arrestor-cycle
source: mcdm.heroes.v1
subclass: chronokinetic
subtype: triggered
target: One creature
tier1: I < WEAK, the target loses their [turn](../../../../rule/combat/turn.md)
tier2: I < AVERAGE, the target loses their [turn](../../../../rule/combat/turn.md)
tier3: I < STRONG, the target loses their [turn](../../../../rule/combat/turn.md)
trigger: The triggering creature starts their [turn](../../../../rule/combat/turn.md).
type: ability
---

```ds-feature
cost: 11 Discipline
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: If the target loses their [turn](../../../../rule/combat/turn.md), the round continues as if they had acted. A target who doesn't lose their [turn](../../../../rule/combat/turn.md) takes psychic damage equal to twice your [Intuition](../../../../rule/character/intuition.md) score for each main action they take until the end of their next [turn](../../../../rule/combat/turn.md).
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: I < WEAK, the target loses their [turn](../../../../rule/combat/turn.md)
      tier2: I < AVERAGE, the target loses their [turn](../../../../rule/combat/turn.md)
      tier3: I < STRONG, the target loses their [turn](../../../../rule/combat/turn.md)
feature_type: ability
flavor: You trap your foe in a looping cycle of time, where they relive the last few seconds over and over again.
keywords:
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: Free triggered
    class: "null"
    cost: 11 Discipline
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: If the target loses their [turn](../../../../rule/combat/turn.md), the round continues as if they had acted. A target who doesn't lose their [turn](../../../../rule/combat/turn.md) takes psychic damage equal to twice your [Intuition](../../../../rule/character/intuition.md) score for each main action they take until the end of their next [turn](../../../../rule/combat/turn.md).
    flavor: You trap your foe in a looping cycle of time, where they relive the last few seconds over and over again.
    keywords:
        - Psionic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "9"
    name: Arrestor Cycle
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.null.level-9/arrestor-cycle
    subclass: chronokinetic
    subtype: triggered
    target: One creature
    tier1: I < WEAK, the target loses their [turn](../../../../rule/combat/turn.md)
    tier2: I < AVERAGE, the target loses their [turn](../../../../rule/combat/turn.md)
    tier3: I < STRONG, the target loses their [turn](../../../../rule/combat/turn.md)
    trigger: The triggering creature starts their [turn](../../../../rule/combat/turn.md).
    type: ability
name: Arrestor Cycle
target: One creature
trigger: The triggering creature starts their [turn](../../../../rule/combat/turn.md).
type: feature
usage: Free triggered
```
