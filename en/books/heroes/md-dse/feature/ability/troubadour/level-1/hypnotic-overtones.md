---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
cost: 3 Drama
cost_amount: "3"
cost_resource: Drama
distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
feature_type: ability
file_basename: hypnotic-overtones
file_dpath: feature/ability/troubadour/level-1
flavor: You produce an entrancing note that twists the senses in a spectacular fashion.
item_id: hypnotic-overtones
item_name: Hypnotic Overtones
keywords:
    - Area
    - Magic
level: "1"
name: Hypnotic Overtones
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/hypnotic-overtones
source: mcdm.heroes.v1
spend: '2+ Drama: The size of the [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst) increases by 1 for every 2 drama spent.'
target: Each enemy in the area
tier1: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1; I < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)'
tier2: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1; I < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)'
tier3: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)'
type: ability
---

```ds-feature
cost: 3 Drama
distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1; I < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)'
      tier2: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1; I < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)'
      tier3: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)'
    - effect: '2+ Drama: The size of the [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst) increases by 1 for every 2 drama spent.'
      name: Spend
feature_type: ability
flavor: You produce an entrancing note that twists the senses in a spectacular fashion.
keywords:
    - Area
    - Magic
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: troubadour
    cost: 3 Drama
    distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    flavor: You produce an entrancing note that twists the senses in a spectacular fashion.
    keywords:
        - Area
        - Magic
    level: "1"
    name: Hypnotic Overtones
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/hypnotic-overtones
    spend: '2+ Drama: The size of the [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst) increases by 1 for every 2 drama spent.'
    target: Each enemy in the area
    tier1: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1; I < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)'
    tier2: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1; I < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)'
    tier3: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)'
    type: ability
name: Hypnotic Overtones
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
