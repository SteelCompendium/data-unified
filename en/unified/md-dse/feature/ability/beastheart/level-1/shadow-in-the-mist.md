---
action_type: Triggered Action
class: beastheart
distance: Self
effect: You become invisible until the end of your next turn or you deal damage. You can then use the [Hide](scc.v1:mcdm.heroes.v1/skill.intrigue/hide) maneuver even if you are observed and can move up to a number of squares equal to your Intuition score before or after using that maneuver.
feature_type: ability
file_basename: shadow-in-the-mist
file_dpath: feature/ability/beastheart/level-1
flavor: While everyone's eyes are drawn to your foe, you wreathe yourself in obscuring mist.
item_id: shadow-in-the-mist
item_name: Shadow in the Mist
keywords:
    - Magic
level: "1"
name: Shadow in the Mist
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/shadow-in-the-mist
source: mcdm.beastheart.v1
spend: '1 Ferocity: You can move up to a number of squares equal to twice your Intuition score and ignore [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) during this movement.'
subclass: prowler
target: Self
trigger: An enemy within 10 squares deals damage to a creature other than you.
type: ability
---

```ds-feature
distance: Self
effects:
    - effect: You become invisible until the end of your next turn or you deal damage. You can then use the [Hide](scc.v1:mcdm.heroes.v1/skill.intrigue/hide) maneuver even if you are observed and can move up to a number of squares equal to your Intuition score before or after using that maneuver.
    - effect: '1 Ferocity: You can move up to a number of squares equal to twice your Intuition score and ignore [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) during this movement.'
      name: Spend
feature_type: ability
flavor: While everyone's eyes are drawn to your foe, you wreathe yourself in obscuring mist.
keywords:
    - Magic
metadata:
    action_type: Triggered Action
    class: beastheart
    distance: Self
    effect: You become invisible until the end of your next turn or you deal damage. You can then use the [Hide](scc.v1:mcdm.heroes.v1/skill.intrigue/hide) maneuver even if you are observed and can move up to a number of squares equal to your Intuition score before or after using that maneuver.
    flavor: While everyone's eyes are drawn to your foe, you wreathe yourself in obscuring mist.
    keywords:
        - Magic
    level: "1"
    name: Shadow in the Mist
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/shadow-in-the-mist
    spend: '1 Ferocity: You can move up to a number of squares equal to twice your Intuition score and ignore [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) during this movement.'
    subclass: prowler
    target: Self
    trigger: An enemy within 10 squares deals damage to a creature other than you.
    type: ability
name: Shadow in the Mist
target: Self
trigger: An enemy within 10 squares deals damage to a creature other than you.
type: feature
usage: Triggered Action
```
