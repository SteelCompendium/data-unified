---
action_type: Main action
class: talent
cost: 9 Clarity
cost_amount: "9"
cost_resource: Clarity
distance: 5 x 2 line within 1
effect: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to a square on the opposite side of the area before making the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
feature_type: ability
file_basename: hypersonic
file_dpath: feature/ability/talent/level-5
flavor: You move fast enough to [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) around and watch your foes feel the aftermath.
item_id: hypersonic
item_name: Hypersonic
keywords:
    - Area
    - Charge
    - Psionic
    - Telekinesis
level: "5"
name: Hypersonic
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-5/hypersonic
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 12 sonic damage
tier2: 18 sonic damage
tier3: 24 sonic damage
type: ability
---

```ds-feature
cost: 9 Clarity
distance: 5 x 2 line within 1
effects:
    - effect: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to a square on the opposite side of the area before making the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 12 sonic damage
      tier2: 18 sonic damage
      tier3: 24 sonic damage
feature_type: ability
flavor: You move fast enough to [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) around and watch your foes feel the aftermath.
keywords:
    - Area
    - Charge
    - Psionic
    - Telekinesis
metadata:
    action_type: Main action
    class: talent
    cost: 9 Clarity
    distance: 5 x 2 line within 1
    effect: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to a square on the opposite side of the area before making the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    flavor: You move fast enough to [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) around and watch your foes feel the aftermath.
    keywords:
        - Area
        - Charge
        - Psionic
        - Telekinesis
    level: "5"
    name: Hypersonic
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-5/hypersonic
    target: Each enemy in the area
    tier1: 12 sonic damage
    tier2: 18 sonic damage
    tier3: 24 sonic damage
    type: ability
name: Hypersonic
target: Each enemy in the area
type: feature
usage: Main action
```
