---
action_type: Main action
class: conduit
cost: 11 Piety
cost_amount: "11"
cost_resource: Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: Each ally the target comes [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
file_basename: drag-the-unworthy
file_dpath: feature/ability/conduit/level-8
flavor: You conjure an angel who moves a foe and heals your allies.
item_id: drag-the-unworthy
item_name: Drag the Unworthy
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "8"
name: Drag the Unworthy
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-8/drag-the-unworthy
source: mcdm.heroes.v1
target: One creature or object
tier1: 9 + I holy damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier2: 13 + I holy damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
tier3: 18 + I holy damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
type: ability
---

```ds-feature
cost: 11 Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: Each ally the target comes [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 9 + I holy damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier2: 13 + I holy damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
      tier3: 18 + I holy damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
feature_type: ability
flavor: You conjure an angel who moves a foe and heals your allies.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: conduit
    cost: 11 Piety
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: Each ally the target comes [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    flavor: You conjure an angel who moves a foe and heals your allies.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "8"
    name: Drag the Unworthy
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-8/drag-the-unworthy
    target: One creature or object
    tier1: 9 + I holy damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    tier2: 13 + I holy damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
    tier3: 18 + I holy damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
    type: ability
name: Drag the Unworthy
target: One creature or object
type: feature
usage: Main action
```
