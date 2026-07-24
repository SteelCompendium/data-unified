---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: talent
cost: 9 Clarity
cost_amount: "9"
cost_resource: Clarity
distance: 5 x 2 line within 1
effects:
    - effect: You [teleport](../../../../movement/teleport.md) to a square on the opposite side of the area before making the [power roll](../../../../rule/dice/power-roll.md).
      name: Effect
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: 12 sonic damage
      tier2: 18 sonic damage
      tier3: 24 sonic damage
    - effect: If you obtain a tier 2 outcome or better, you are [slowed](../../../../condition/slowed.md) until the end of your [turn](../../../../rule/combat/turn.md) and each target is [slowed](../../../../condition/slowed.md) until the end of their [turn](../../../../rule/combat/turn.md).
      name: Strained
feature_type: ability
file_basename: hypersonic
file_dpath: feature/ability/talent/level-5
flavor: You move fast enough to [turn](../../../../rule/combat/turn.md) around and watch your foes feel the aftermath.
item_id: hypersonic
item_name: Hypersonic
keywords:
    - Area
    - Charge
    - Psionic
    - Telekinesis
level: "5"
name: Hypersonic
power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
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
    - effect: You [teleport](../../../../movement/teleport.md) to a square on the opposite side of the area before making the [power roll](../../../../rule/dice/power-roll.md).
      name: Effect
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: 12 sonic damage
      tier2: 18 sonic damage
      tier3: 24 sonic damage
    - effect: If you obtain a tier 2 outcome or better, you are [slowed](../../../../condition/slowed.md) until the end of your [turn](../../../../rule/combat/turn.md) and each target is [slowed](../../../../condition/slowed.md) until the end of their [turn](../../../../rule/combat/turn.md).
      name: Strained
feature_type: ability
flavor: You move fast enough to [turn](../../../../rule/combat/turn.md) around and watch your foes feel the aftermath.
keywords:
    - Area
    - Charge
    - Psionic
    - Telekinesis
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: talent
    cost: 9 Clarity
    distance: 5 x 2 line within 1
    effects:
        - effect: You [teleport](../../../../movement/teleport.md) to a square on the opposite side of the area before making the [power roll](../../../../rule/dice/power-roll.md).
          name: Effect
        - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
          tier1: 12 sonic damage
          tier2: 18 sonic damage
          tier3: 24 sonic damage
        - effect: If you obtain a tier 2 outcome or better, you are [slowed](../../../../condition/slowed.md) until the end of your [turn](../../../../rule/combat/turn.md) and each target is [slowed](../../../../condition/slowed.md) until the end of their [turn](../../../../rule/combat/turn.md).
          name: Strained
    flavor: You move fast enough to [turn](../../../../rule/combat/turn.md) around and watch your foes feel the aftermath.
    keywords:
        - Area
        - Charge
        - Psionic
        - Telekinesis
    level: "5"
    name: Hypersonic
    power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-5/hypersonic
    target: Each enemy in the area
    tier1: 12 sonic damage
    tier2: 18 sonic damage
    tier3: 24 sonic damage
    type: ability
name: Hypersonic
target: Each enemy in the area
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
