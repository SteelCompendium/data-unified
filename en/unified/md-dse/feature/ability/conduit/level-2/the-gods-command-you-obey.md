---
action_type: Main action
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: the-gods-command-you-obey
file_dpath: feature/ability/conduit/level-2
flavor: You speak with the voice of your [saint](scc.v1:mcdm.heroes.v1/rule.world/saint), commanding your enemies.
item_id: the-gods-command-you-obey
item_name: The Gods Command You Obey
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "2"
name: The Gods Command You Obey
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-2/the-gods-command-you-obey
source: mcdm.heroes.v1
subclass: knowledge
target: One creature
tier1: 4 + I holy damage; P < WEAK, before taking damage, the target makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a target you choose
tier2: 7 + I holy damage; P < AVERAGE, before taking damage, the target uses an ability of your choice and you choose any targets for that ability
tier3: 11 + I holy damage; P < STRONG, before taking damage, the target shifts up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) to a location you choose, uses an ability of your choice, and you choose any targets for that ability
type: ability
---

```ds-feature
cost: 5 Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 4 + I holy damage; P < WEAK, before taking damage, the target makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a target you choose
      tier2: 7 + I holy damage; P < AVERAGE, before taking damage, the target uses an ability of your choice and you choose any targets for that ability
      tier3: 11 + I holy damage; P < STRONG, before taking damage, the target shifts up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) to a location you choose, uses an ability of your choice, and you choose any targets for that ability
feature_type: ability
flavor: You speak with the voice of your [saint](scc.v1:mcdm.heroes.v1/rule.world/saint), commanding your enemies.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: conduit
    cost: 5 Piety
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: You speak with the voice of your [saint](scc.v1:mcdm.heroes.v1/rule.world/saint), commanding your enemies.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "2"
    name: The Gods Command You Obey
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-2/the-gods-command-you-obey
    subclass: knowledge
    target: One creature
    tier1: 4 + I holy damage; P < WEAK, before taking damage, the target makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a target you choose
    tier2: 7 + I holy damage; P < AVERAGE, before taking damage, the target uses an ability of your choice and you choose any targets for that ability
    tier3: 11 + I holy damage; P < STRONG, before taking damage, the target shifts up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) to a location you choose, uses an ability of your choice, and you choose any targets for that ability
    type: ability
name: The Gods Command You Obey
target: One creature
type: feature
usage: Main action
```
