---
action_type: Main action
class: troubadour
cost: 5 Drama
cost_amount: "5"
cost_resource: Drama
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
feature_type: ability
file_basename: dramatic-reversal
file_dpath: feature/ability/troubadour/level-1
flavor: Give the audience a surprise.
item_id: dramatic-reversal
item_name: Dramatic Reversal
keywords:
    - Area
    - Magic
level: "1"
name: Dramatic Reversal
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/dramatic-reversal
source: mcdm.heroes.v1
target: Self and each ally in the area
tier1: The target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square and make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
tier2: The target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares and make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge).
tier3: The target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares and make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge), then can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
type: ability
---

```ds-feature
cost: 5 Drama
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: The target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square and make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
      tier2: The target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares and make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge).
      tier3: The target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares and make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge), then can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
flavor: Give the audience a surprise.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: troubadour
    cost: 5 Drama
    distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    flavor: Give the audience a surprise.
    keywords:
        - Area
        - Magic
    level: "1"
    name: Dramatic Reversal
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/dramatic-reversal
    target: Self and each ally in the area
    tier1: The target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square and make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
    tier2: The target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares and make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge).
    tier3: The target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares and make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge), then can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    type: ability
name: Dramatic Reversal
target: Self and each ally in the area
type: feature
usage: Main action
```
