---
action_type: Main action
class: troubadour
cost: 11 Drama
cost_amount: "11"
cost_resource: Drama
distance: 5 [burst](../../../../rule/combat/burst.md)
effect: Each creature within [distance](../../../../rule/combat/distance.md) gains a +5 [bonus](../../../../rule/dice/bonuses-and-penalties.md) to [speed](../../../../rule/character/speed.md) until the end of their next [turn](../../../../rule/combat/turn.md). While under this effect, each target must use their full movement during their [turn](../../../../rule/combat/turn.md).
feature_type: ability
file_basename: jam-session
file_dpath: feature/ability/troubadour/level-9
flavor: Your [jam session](jam-session.md) creates new genres that compel everyone to get up and move.
item_id: jam-session
item_name: Jam Session
keywords:
    - Area
    - Magic
level: "9"
name: Jam Session
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/jam-session
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 8 sonic damage
tier2: 11 sonic damage
tier3: 15 sonic damage
type: ability
---

```ds-feature
cost: 11 Drama
distance: 5 [burst](../../../../rule/combat/burst.md)
effects:
    - effect: Each creature within [distance](../../../../rule/combat/distance.md) gains a +5 [bonus](../../../../rule/dice/bonuses-and-penalties.md) to [speed](../../../../rule/character/speed.md) until the end of their next [turn](../../../../rule/combat/turn.md). While under this effect, each target must use their full movement during their [turn](../../../../rule/combat/turn.md).
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 8 sonic damage
      tier2: 11 sonic damage
      tier3: 15 sonic damage
feature_type: ability
flavor: Your [jam session](jam-session.md) creates new genres that compel everyone to get up and move.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: troubadour
    cost: 11 Drama
    distance: 5 [burst](../../../../rule/combat/burst.md)
    effect: Each creature within [distance](../../../../rule/combat/distance.md) gains a +5 [bonus](../../../../rule/dice/bonuses-and-penalties.md) to [speed](../../../../rule/character/speed.md) until the end of their next [turn](../../../../rule/combat/turn.md). While under this effect, each target must use their full movement during their [turn](../../../../rule/combat/turn.md).
    flavor: Your [jam session](jam-session.md) creates new genres that compel everyone to get up and move.
    keywords:
        - Area
        - Magic
    level: "9"
    name: Jam Session
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/jam-session
    target: Each enemy in the area
    tier1: 8 sonic damage
    tier2: 11 sonic damage
    tier3: 15 sonic damage
    type: ability
name: Jam Session
target: Each enemy in the area
type: feature
usage: Main action
```
