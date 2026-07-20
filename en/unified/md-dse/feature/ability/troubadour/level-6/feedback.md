---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
cost: 9 Drama
cost_amount: "9"
cost_resource: Drama
distance: Three 3 [cubes](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 1
effect: A [prone target](scc.v1:mcdm.heroes.v1/condition/prone) ignores this ability.
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
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-6/feedback
source: mcdm.heroes.v1
subclass: virtuoso
target: Each enemy in the area
tier1: 7 sonic damage; P < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier2: 10 sonic damage; P < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier3: 13 sonic damage; P < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
type: ability
---

```ds-feature
cost: 9 Drama
distance: Three 3 [cubes](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 1
effects:
    - effect: A [prone target](scc.v1:mcdm.heroes.v1/condition/prone) ignores this ability.
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 7 sonic damage; P < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier2: 10 sonic damage; P < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier3: 13 sonic damage; P < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
feature_type: ability
flavor: Your music pounds the crowd to the beat until their hearts can't stand it anymore.
keywords:
    - Area
    - Magic
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: troubadour
    cost: 9 Drama
    distance: Three 3 [cubes](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 1
    effect: A [prone target](scc.v1:mcdm.heroes.v1/condition/prone) ignores this ability.
    flavor: Your music pounds the crowd to the beat until their hearts can't stand it anymore.
    keywords:
        - Area
        - Magic
    level: "6"
    name: Feedback
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-6/feedback
    subclass: virtuoso
    target: Each enemy in the area
    tier1: 7 sonic damage; P < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    tier2: 10 sonic damage; P < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    tier3: 13 sonic damage; P < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    type: ability
name: Feedback
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
