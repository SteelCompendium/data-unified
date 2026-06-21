---
action_type: Maneuver
class: troubadour
cost: 11 Drama
cost_amount: "11"
cost_resource: Drama
distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effect: Each ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) can't obtain lower than a tier 2 outcome on the next [test](scc.v1:mcdm.heroes.v1/rule.test/test) they make before the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
feature_type: ability
file_basename: the-show-must-go-on
file_dpath: feature/ability/troubadour/level-8
flavor: You shine a bright light on the players on the stage and compel them to finish the performance.
item_id: the-show-must-go-on
item_name: The Show Must Go On
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "8"
name: The Show Must Go On
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-8/the-show-must-go-on
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 6 damage; P < WEAK, the target can't willingly leave the area ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
tier2: 8 damage; P < AVERAGE, the target can't willingly leave the area (save ends)
tier3: 12 damage; the target can't willingly leave the area ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)); if P < STRONG, they can't willingly leave the area (save ends)
type: ability
---

```ds-feature
cost: 11 Drama
distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - effect: Each ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) can't obtain lower than a tier 2 outcome on the next [test](scc.v1:mcdm.heroes.v1/rule.test/test) they make before the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 6 damage; P < WEAK, the target can't willingly leave the area ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
      tier2: 8 damage; P < AVERAGE, the target can't willingly leave the area (save ends)
      tier3: 12 damage; the target can't willingly leave the area ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)); if P < STRONG, they can't willingly leave the area (save ends)
feature_type: ability
flavor: You shine a bright light on the players on the stage and compel them to finish the performance.
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Maneuver
    class: troubadour
    cost: 11 Drama
    distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    effect: Each ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) can't obtain lower than a tier 2 outcome on the next [test](scc.v1:mcdm.heroes.v1/rule.test/test) they make before the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    flavor: You shine a bright light on the players on the stage and compel them to finish the performance.
    keywords:
        - Area
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "8"
    name: The Show Must Go On
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-8/the-show-must-go-on
    target: Each enemy in the area
    tier1: 6 damage; P < WEAK, the target can't willingly leave the area ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
    tier2: 8 damage; P < AVERAGE, the target can't willingly leave the area (save ends)
    tier3: 12 damage; the target can't willingly leave the area ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)); if P < STRONG, they can't willingly leave the area (save ends)
    type: ability
name: The Show Must Go On
target: Each enemy in the area
type: feature
usage: Maneuver
```
