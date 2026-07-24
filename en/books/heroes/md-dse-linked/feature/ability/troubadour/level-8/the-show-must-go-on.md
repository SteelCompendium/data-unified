---
action_type: '[Maneuver](../../../../rule/combat/turn.md)'
class: troubadour
cost: 11 Drama
cost_amount: "11"
cost_resource: Drama
distance: 5 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 6 damage; P < WEAK, the target can't willingly leave the area ([EoT](../../../../rule/combat/end-of-turn.md))
      tier2: 8 damage; P < AVERAGE, the target can't willingly leave the area (save ends)
      tier3: 12 damage; the target can't willingly leave the area ([EoT](../../../../rule/combat/end-of-turn.md)); if P < STRONG, they can't willingly leave the area (save ends)
    - effect: Each ally within [distance](../../../../rule/combat/distance.md) can't obtain lower than a tier 2 outcome on the next [test](../../../../rule/test/test.md) they make before the start of your next [turn](../../../../rule/combat/turn.md).
      name: Effect
feature_type: ability
file_basename: the-show-must-go-on
file_dpath: feature/ability/troubadour/level-8
flavor: You shine a bright light on the players on the stage and compel them to finish the performance.
item_id: the-show-must-go-on
item_name: The Show Must Go On
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "8"
name: The Show Must Go On
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-8/the-show-must-go-on
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 6 damage; P < WEAK, the target can't willingly leave the area ([EoT](../../../../rule/combat/end-of-turn.md))
tier2: 8 damage; P < AVERAGE, the target can't willingly leave the area (save ends)
tier3: 12 damage; the target can't willingly leave the area ([EoT](../../../../rule/combat/end-of-turn.md)); if P < STRONG, they can't willingly leave the area (save ends)
type: ability
---

```ds-feature
cost: 11 Drama
distance: 5 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 6 damage; P < WEAK, the target can't willingly leave the area ([EoT](../../../../rule/combat/end-of-turn.md))
      tier2: 8 damage; P < AVERAGE, the target can't willingly leave the area (save ends)
      tier3: 12 damage; the target can't willingly leave the area ([EoT](../../../../rule/combat/end-of-turn.md)); if P < STRONG, they can't willingly leave the area (save ends)
    - effect: Each ally within [distance](../../../../rule/combat/distance.md) can't obtain lower than a tier 2 outcome on the next [test](../../../../rule/test/test.md) they make before the start of your next [turn](../../../../rule/combat/turn.md).
      name: Effect
feature_type: ability
flavor: You shine a bright light on the players on the stage and compel them to finish the performance.
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Maneuver](../../../../rule/combat/turn.md)'
    class: troubadour
    cost: 11 Drama
    distance: 5 [cube](../../../../rule/combat/cube.md) within 10
    effects:
        - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
          tier1: 6 damage; P < WEAK, the target can't willingly leave the area ([EoT](../../../../rule/combat/end-of-turn.md))
          tier2: 8 damage; P < AVERAGE, the target can't willingly leave the area (save ends)
          tier3: 12 damage; the target can't willingly leave the area ([EoT](../../../../rule/combat/end-of-turn.md)); if P < STRONG, they can't willingly leave the area (save ends)
        - effect: Each ally within [distance](../../../../rule/combat/distance.md) can't obtain lower than a tier 2 outcome on the next [test](../../../../rule/test/test.md) they make before the start of your next [turn](../../../../rule/combat/turn.md).
          name: Effect
    flavor: You shine a bright light on the players on the stage and compel them to finish the performance.
    keywords:
        - Area
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "8"
    name: The Show Must Go On
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-8/the-show-must-go-on
    target: Each enemy in the area
    tier1: 6 damage; P < WEAK, the target can't willingly leave the area ([EoT](../../../../rule/combat/end-of-turn.md))
    tier2: 8 damage; P < AVERAGE, the target can't willingly leave the area (save ends)
    tier3: 12 damage; the target can't willingly leave the area ([EoT](../../../../rule/combat/end-of-turn.md)); if P < STRONG, they can't willingly leave the area (save ends)
    type: ability
name: The Show Must Go On
target: Each enemy in the area
type: feature
usage: '[Maneuver](../../../../rule/combat/turn.md)'
```
