---
action_type: Main action
class: conduit
cost: 3 Piety
cost_amount: "3"
cost_resource: Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: judgments-hammer
file_dpath: feature/ability/conduit/level-1
flavor: Your divine [fury](scc.v1:mcdm.heroes.v1/class/fury) is a hammer that crashes down upon the unrighteous.
item_id: judgments-hammer
item_name: Judgment's Hammer
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Judgment's Hammer
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/judgments-hammer
source: mcdm.heroes.v1
target: One creature or object
tier1: 3 + I holy damage; A < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier2: 6 + I holy damage; A < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier3: 9 + I holy damage; A < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
type: ability
---

```ds-feature
cost: 3 Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 3 + I holy damage; A < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier2: 6 + I holy damage; A < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier3: 9 + I holy damage; A < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
feature_type: ability
flavor: Your divine [fury](scc.v1:mcdm.heroes.v1/class/fury) is a hammer that crashes down upon the unrighteous.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: conduit
    cost: 3 Piety
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: Your divine [fury](scc.v1:mcdm.heroes.v1/class/fury) is a hammer that crashes down upon the unrighteous.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Judgment's Hammer
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/judgments-hammer
    target: One creature or object
    tier1: 3 + I holy damage; A < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    tier2: 6 + I holy damage; A < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    tier3: 9 + I holy damage; A < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
    type: ability
name: Judgment's Hammer
target: One creature or object
type: feature
usage: Main action
```
