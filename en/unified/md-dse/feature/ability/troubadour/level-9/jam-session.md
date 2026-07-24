---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
cost: 11 Drama
cost_amount: "11"
cost_resource: Drama
distance: 5 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 8 sonic damage
      tier2: 11 sonic damage
      tier3: 15 sonic damage
    - effect: Each creature within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a +5 [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) to [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) until the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). While under this effect, each target must use their full movement during their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Effect
feature_type: ability
file_basename: jam-session
file_dpath: feature/ability/troubadour/level-9
flavor: Your [jam session](scc.v1:mcdm.heroes.v1/feature.ability.troubadour.level-9/jam-session) creates new genres that compel everyone to get up and move.
item_id: jam-session
item_name: Jam Session
keywords:
    - Area
    - Magic
level: "9"
name: Jam Session
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/jam-session
source: mcdm.heroes.v1
subclass: virtuoso
target: Each enemy in the area
tier1: 8 sonic damage
tier2: 11 sonic damage
tier3: 15 sonic damage
type: ability
---

```ds-feature
cost: 11 Drama
distance: 5 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 8 sonic damage
      tier2: 11 sonic damage
      tier3: 15 sonic damage
    - effect: Each creature within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a +5 [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) to [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) until the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). While under this effect, each target must use their full movement during their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Effect
feature_type: ability
flavor: Your [jam session](scc.v1:mcdm.heroes.v1/feature.ability.troubadour.level-9/jam-session) creates new genres that compel everyone to get up and move.
keywords:
    - Area
    - Magic
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: troubadour
    cost: 11 Drama
    distance: 5 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effects:
        - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
          tier1: 8 sonic damage
          tier2: 11 sonic damage
          tier3: 15 sonic damage
        - effect: Each creature within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a +5 [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) to [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) until the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). While under this effect, each target must use their full movement during their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
          name: Effect
    flavor: Your [jam session](scc.v1:mcdm.heroes.v1/feature.ability.troubadour.level-9/jam-session) creates new genres that compel everyone to get up and move.
    keywords:
        - Area
        - Magic
    level: "9"
    name: Jam Session
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/jam-session
    subclass: virtuoso
    target: Each enemy in the area
    tier1: 8 sonic damage
    tier2: 11 sonic damage
    tier3: 15 sonic damage
    type: ability
name: Jam Session
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
