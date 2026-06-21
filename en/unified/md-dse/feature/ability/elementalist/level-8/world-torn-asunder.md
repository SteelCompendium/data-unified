---
action_type: Main action
class: elementalist
cost: 11 Essence
cost_amount: "11"
cost_resource: Essence
distance: 5 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effect: You create a fissure in the ground [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you that is a 10 x 2 line and 6 squares deep. Each creature in the area who [is prone](scc.v1:mcdm.heroes.v1/condition/prone) and [size](scc.v1:mcdm.heroes.v1/rule.character/size) 2 or smaller falls in. Other creatures can enter the fissure or can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) to the nearest unoccupied space of their choice outside it.
feature_type: ability
file_basename: world-torn-asunder
file_dpath: feature/ability/elementalist/level-8
flavor: You stomp your foot and quake the whole world over.
item_id: world-torn-asunder
item_name: World Torn Asunder
keywords:
    - Area
    - Earth
    - Magic
level: "8"
name: World Torn Asunder
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-8/world-torn-asunder
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: M < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier2: M < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier3: M < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
type: ability
---

```ds-feature
cost: 11 Essence
distance: 5 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: You create a fissure in the ground [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you that is a 10 x 2 line and 6 squares deep. Each creature in the area who [is prone](scc.v1:mcdm.heroes.v1/condition/prone) and [size](scc.v1:mcdm.heroes.v1/rule.character/size) 2 or smaller falls in. Other creatures can enter the fissure or can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) to the nearest unoccupied space of their choice outside it.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: M < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier2: M < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier3: M < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
feature_type: ability
flavor: You stomp your foot and quake the whole world over.
keywords:
    - Area
    - Earth
    - Magic
metadata:
    action_type: Main action
    class: elementalist
    cost: 11 Essence
    distance: 5 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effect: You create a fissure in the ground [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you that is a 10 x 2 line and 6 squares deep. Each creature in the area who [is prone](scc.v1:mcdm.heroes.v1/condition/prone) and [size](scc.v1:mcdm.heroes.v1/rule.character/size) 2 or smaller falls in. Other creatures can enter the fissure or can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) to the nearest unoccupied space of their choice outside it.
    flavor: You stomp your foot and quake the whole world over.
    keywords:
        - Area
        - Earth
        - Magic
    level: "8"
    name: World Torn Asunder
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-8/world-torn-asunder
    target: Each enemy in the area
    tier1: M < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    tier2: M < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    tier3: M < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    type: ability
name: World Torn Asunder
target: Each enemy in the area
type: feature
usage: Main action
```
