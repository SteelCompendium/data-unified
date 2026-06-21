---
action_type: Main action
class: elementalist
cost: 5 Essence
cost_amount: "5"
cost_resource: Essence
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effect: You can end one effect on yourself that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Each ally in the area also gains this benefit.
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
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Test of Rain
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
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
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - effect: You can end one effect on yourself that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Each ally in the area also gains this benefit.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 4 acid damage
      tier2: 6 acid damage
      tier3: 10 acid damage
feature_type: ability
flavor: You call down a rain that burns your enemies and restores your allies.
keywords:
    - Area
    - Green
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Main action
    class: elementalist
    cost: 5 Essence
    distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    effect: You can end one effect on yourself that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Each ally in the area also gains this benefit.
    flavor: You call down a rain that burns your enemies and restores your allies.
    keywords:
        - Area
        - Green
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Test of Rain
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/test-of-rain
    target: Each enemy in the area
    tier1: 4 acid damage
    tier2: 6 acid damage
    tier3: 10 acid damage
    type: ability
name: Test of Rain
target: Each enemy in the area
type: feature
usage: Main action
```
