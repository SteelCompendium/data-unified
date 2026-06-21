---
action_type: Free triggered
class: "null"
cost: 11 Discipline
cost_amount: "11"
cost_resource: Discipline
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: If the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), the round continues as if they had acted. A target who doesn't lose their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) takes psychic damage equal to twice your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score for each main action they take until the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
feature_type: ability
file_basename: arrestor-cycle
file_dpath: feature/ability/null/level-9
flavor: You trap your foe in a looping cycle of time, where they relive the last few seconds over and over again.
item_id: arrestor-cycle
item_name: Arrestor Cycle
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "9"
name: Arrestor Cycle
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.null.level-9/arrestor-cycle
source: mcdm.heroes.v1
subtype: triggered
target: One creature
tier1: I < WEAK, the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)
tier2: I < AVERAGE, the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)
tier3: I < STRONG, the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)
trigger: The triggering creature starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
type: ability
---

```ds-feature
cost: 11 Discipline
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: If the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), the round continues as if they had acted. A target who doesn't lose their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) takes psychic damage equal to twice your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score for each main action they take until the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: I < WEAK, the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)
      tier2: I < AVERAGE, the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)
      tier3: I < STRONG, the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)
feature_type: ability
flavor: You trap your foe in a looping cycle of time, where they relive the last few seconds over and over again.
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Free triggered
    class: "null"
    cost: 11 Discipline
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: If the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), the round continues as if they had acted. A target who doesn't lose their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) takes psychic damage equal to twice your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score for each main action they take until the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    flavor: You trap your foe in a looping cycle of time, where they relive the last few seconds over and over again.
    keywords:
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "9"
    name: Arrestor Cycle
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.null.level-9/arrestor-cycle
    subtype: triggered
    target: One creature
    tier1: I < WEAK, the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)
    tier2: I < AVERAGE, the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)
    tier3: I < STRONG, the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)
    trigger: The triggering creature starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    type: ability
name: Arrestor Cycle
target: One creature
trigger: The triggering creature starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
type: feature
usage: Free triggered
```
