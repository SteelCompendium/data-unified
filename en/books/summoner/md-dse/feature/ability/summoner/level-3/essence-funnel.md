---
action_type: Main action
class: summoner
distance: 10 × 1 line within 1
feature_source: summoner
feature_type: ability
file_basename: essence-funnel
file_dpath: feature/ability/summoner/level-3
flavor: You rapidly summon and sacrifice minions in order to power a devastating blast of magic.
item_id: essence-funnel
item_name: Essence Funnel
keywords:
    - Area
    - Magic
level: "3"
name: Essence Funnel
power_roll_characteristic: Reason
scc: mcdm.summoner.v1/feature.ability.summoner.level-3/essence-funnel
source: mcdm.summoner.v1
target: Each enemy and object in the area
tier1: 5 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
tier2: 9 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
tier3: 12 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
type: ability
---

```ds-feature
distance: 10 × 1 line within 1
effects:
    - roll: Power Roll + Reason
      tier1: 5 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier2: 9 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
      tier3: 12 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
feature_type: ability
flavor: You rapidly summon and sacrifice minions in order to power a devastating blast of magic.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: summoner
    distance: 10 × 1 line within 1
    feature_source: summoner
    flavor: You rapidly summon and sacrifice minions in order to power a devastating blast of magic.
    keywords:
        - Area
        - Magic
    level: "3"
    name: Essence Funnel
    power_roll_characteristic: Reason
    scc: mcdm.summoner.v1/feature.ability.summoner.level-3/essence-funnel
    target: Each enemy and object in the area
    tier1: 5 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    tier2: 9 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
    tier3: 12 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
    type: ability
name: Essence Funnel
target: Each enemy and object in the area
type: feature
usage: Main action
```
