---
action_type: Main action
class: troubadour
cost: 9 Drama
cost_amount: "9"
cost_resource: Drama
distance: Three 3 [cubes](../../../../rule/combat/cube.md) within 1
effect: A [prone target](../../../../condition/prone.md) ignores this ability.
feature_type: ability
file_basename: feedback
file_dpath: feature/ability/troubadour/level-6
flavor: Your music pounds the crowd to the beat until their hearts can't stand it anymore.
item_id: feedback
item_name: Feedback
keywords:
    - Area
    - Magic
level: "6"
name: Feedback
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-6/feedback
source: mcdm.heroes.v1
subclass: virtuoso
target: Each enemy in the area
tier1: 7 sonic damage; P < WEAK[, prone](../../../../condition/prone.md)
tier2: 10 sonic damage; P < AVERAGE[, prone](../../../../condition/prone.md)
tier3: 13 sonic damage; P < STRONG[, prone](../../../../condition/prone.md)
type: ability
---

```ds-feature
cost: 9 Drama
distance: Three 3 [cubes](../../../../rule/combat/cube.md) within 1
effects:
    - effect: A [prone target](../../../../condition/prone.md) ignores this ability.
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 7 sonic damage; P < WEAK[, prone](../../../../condition/prone.md)
      tier2: 10 sonic damage; P < AVERAGE[, prone](../../../../condition/prone.md)
      tier3: 13 sonic damage; P < STRONG[, prone](../../../../condition/prone.md)
feature_type: ability
flavor: Your music pounds the crowd to the beat until their hearts can't stand it anymore.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: troubadour
    cost: 9 Drama
    distance: Three 3 [cubes](../../../../rule/combat/cube.md) within 1
    effect: A [prone target](../../../../condition/prone.md) ignores this ability.
    flavor: Your music pounds the crowd to the beat until their hearts can't stand it anymore.
    keywords:
        - Area
        - Magic
    level: "6"
    name: Feedback
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-6/feedback
    subclass: virtuoso
    target: Each enemy in the area
    tier1: 7 sonic damage; P < WEAK[, prone](../../../../condition/prone.md)
    tier2: 10 sonic damage; P < AVERAGE[, prone](../../../../condition/prone.md)
    tier3: 13 sonic damage; P < STRONG[, prone](../../../../condition/prone.md)
    type: ability
name: Feedback
target: Each enemy in the area
type: feature
usage: Main action
```
