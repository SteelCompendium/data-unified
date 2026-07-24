---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 9 Wrath
cost_amount: "9"
cost_resource: Wrath
distance: 3 [aura](scc.v1:mcdm.heroes.v1/rule.combat/aura)
effects:
    - effect: Until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), whenever any target takes a [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) or a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), that action is negated and the target takes holy damage equal to your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score.
      name: Effect
feature_type: ability
file_basename: edict-of-peace
file_dpath: feature/ability/censor/level-6
flavor: You anticipate your foes' moves and deny them.
item_id: edict-of-peace
item_name: Edict of Peace
keywords:
    - Area
    - Magic
level: "6"
name: Edict of Peace
scc: mcdm.heroes.v1/feature.ability.censor.level-6/edict-of-peace
source: mcdm.heroes.v1
subclass: oracle
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 9 Wrath
distance: 3 [aura](scc.v1:mcdm.heroes.v1/rule.combat/aura)
effects:
    - effect: Until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), whenever any target takes a [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) or a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), that action is negated and the target takes holy damage equal to your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score.
      name: Effect
feature_type: ability
flavor: You anticipate your foes' moves and deny them.
keywords:
    - Area
    - Magic
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: censor
    cost: 9 Wrath
    distance: 3 [aura](scc.v1:mcdm.heroes.v1/rule.combat/aura)
    effects:
        - effect: Until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), whenever any target takes a [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) or a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), that action is negated and the target takes holy damage equal to your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score.
          name: Effect
    flavor: You anticipate your foes' moves and deny them.
    keywords:
        - Area
        - Magic
    level: "6"
    name: Edict of Peace
    scc: mcdm.heroes.v1/feature.ability.censor.level-6/edict-of-peace
    subclass: oracle
    target: Each enemy in the area
    type: ability
name: Edict of Peace
target: Each enemy in the area
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
