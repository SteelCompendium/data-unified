---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: elementalist
cost: 5 Essence
cost_amount: "5"
cost_resource: Essence
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: 4 acid damage
      tier2: 6 acid damage
      tier3: 10 acid damage
    - effect: You can end one effect on yourself that is ended by a [saving throw](../../../../rule/general/saving-throw.md) or that ends at the end of your [turn](../../../../rule/combat/turn.md). Each ally in the area also gains this benefit.
      name: Effect
feature_type: ability
file_basename: test-of-rain
file_dpath: feature/ability/elementalist/level-1
flavor: You call down a rain that burns your enemies and restores your allies.
item_id: test-of-rain
item_name: Test of Rain
keywords:
    - Area
    - Green
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "1"
name: Test of Rain
power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/test-of-rain
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 4 acid damage
tier2: 6 acid damage
tier3: 10 acid damage
type: ability
---

```ds-feature
cost: 5 Essence
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: 4 acid damage
      tier2: 6 acid damage
      tier3: 10 acid damage
    - effect: You can end one effect on yourself that is ended by a [saving throw](../../../../rule/general/saving-throw.md) or that ends at the end of your [turn](../../../../rule/combat/turn.md). Each ally in the area also gains this benefit.
      name: Effect
feature_type: ability
flavor: You call down a rain that burns your enemies and restores your allies.
keywords:
    - Area
    - Green
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: elementalist
    cost: 5 Essence
    distance: 3 [cube](../../../../rule/combat/cube.md) within 10
    effects:
        - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
          tier1: 4 acid damage
          tier2: 6 acid damage
          tier3: 10 acid damage
        - effect: You can end one effect on yourself that is ended by a [saving throw](../../../../rule/general/saving-throw.md) or that ends at the end of your [turn](../../../../rule/combat/turn.md). Each ally in the area also gains this benefit.
          name: Effect
    flavor: You call down a rain that burns your enemies and restores your allies.
    keywords:
        - Area
        - Green
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "1"
    name: Test of Rain
    power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/test-of-rain
    target: Each enemy in the area
    tier1: 4 acid damage
    tier2: 6 acid damage
    tier3: 10 acid damage
    type: ability
name: Test of Rain
target: Each enemy in the area
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
