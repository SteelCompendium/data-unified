---
action_type: Main action
class: talent
cost: 11 Clarity
cost_amount: "11"
cost_resource: Clarity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
effect: The target can't communicate with anyone until the end of the encounter.
feature_type: ability
file_basename: mindwipe
file_dpath: feature/ability/talent/level-8
flavor: You attempt to make them forget all their training.
item_id: mindwipe
item_name: Mindwipe
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Telepathy
level: "8"
name: Mindwipe
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-8/mindwipe
source: mcdm.heroes.v1
target: One creature
tier1: 12 + R damage; R < WEAK, the target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on their next [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll)
tier2: 17 + R damage; R < AVERAGE, the target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on [power rolls](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) (save ends)
tier3: 23 + R damage; R < STRONG, the target has a double [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on [power rolls](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) (save ends)
type: ability
---

```ds-feature
cost: 11 Clarity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
effects:
    - effect: The target can't communicate with anyone until the end of the encounter.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 12 + R damage; R < WEAK, the target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on their next [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll)
      tier2: 17 + R damage; R < AVERAGE, the target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on [power rolls](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) (save ends)
      tier3: 23 + R damage; R < STRONG, the target has a double [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on [power rolls](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) (save ends)
feature_type: ability
flavor: You attempt to make them forget all their training.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Telepathy
metadata:
    action_type: Main action
    class: talent
    cost: 11 Clarity
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
    effect: The target can't communicate with anyone until the end of the encounter.
    flavor: You attempt to make them forget all their training.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Telepathy
    level: "8"
    name: Mindwipe
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-8/mindwipe
    target: One creature
    tier1: 12 + R damage; R < WEAK, the target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on their next [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll)
    tier2: 17 + R damage; R < AVERAGE, the target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on [power rolls](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) (save ends)
    tier3: 23 + R damage; R < STRONG, the target has a double [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on [power rolls](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) (save ends)
    type: ability
name: Mindwipe
target: One creature
type: feature
usage: Main action
```
