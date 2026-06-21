---
action_type: Main action
class: elementalist
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: You [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) one creature within 10 squares of the target up to 2 squares.
feature_type: ability
file_basename: the-green-within-the-green-without
file_dpath: feature/ability/elementalist/level-1
flavor: Whipping vines erupt from a foe's body to grasp at another close by.
item_id: the-green-within-the-green-without
item_name: The Green Within, the Green Without
keywords:
    - Green
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: The Green Within, the Green Without
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/the-green-within-the-green-without
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 2 + R damage
tier2: 5 + R damage
tier3: 7 + R damage
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: You [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) one creature within 10 squares of the target up to 2 squares.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 + R damage
      tier2: 5 + R damage
      tier3: 7 + R damage
feature_type: ability
flavor: Whipping vines erupt from a foe's body to grasp at another close by.
keywords:
    - Green
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: elementalist
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: You [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) one creature within 10 squares of the target up to 2 squares.
    flavor: Whipping vines erupt from a foe's body to grasp at another close by.
    keywords:
        - Green
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: The Green Within, the Green Without
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/the-green-within-the-green-without
    subtype: signature
    target: One creature
    tier1: 2 + R damage
    tier2: 5 + R damage
    tier3: 7 + R damage
    type: ability
name: The Green Within, the Green Without
target: One creature
type: feature
usage: Main action
```
