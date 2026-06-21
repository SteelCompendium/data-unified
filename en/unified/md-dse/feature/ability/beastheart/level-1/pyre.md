---
action_type: Triggered Action
class: beastheart
distance: Self
effect: You take half the damage and [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 5 squares.
feature_type: ability
file_basename: pyre
file_dpath: feature/ability/beastheart/level-1
flavor: You burn to ash before your foes' eyes.
item_id: pyre
item_name: Pyre
keywords:
    - Magic
level: "1"
name: Pyre
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/pyre
source: mcdm.beastheart.v1
spend: '1 Ferocity: When you [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) this way, each enemy adjacent to your original space takes lightning or fire damage (your choice) equal to your Intuition score.'
subclass: spark
target: Self
trigger: You take damage.
type: ability
---

```ds-feature
distance: Self
effects:
    - effect: You take half the damage and [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 5 squares.
    - effect: '1 Ferocity: When you [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) this way, each enemy adjacent to your original space takes lightning or fire damage (your choice) equal to your Intuition score.'
      name: Spend
feature_type: ability
flavor: You burn to ash before your foes' eyes.
keywords:
    - Magic
metadata:
    action_type: Triggered Action
    class: beastheart
    distance: Self
    effect: You take half the damage and [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 5 squares.
    flavor: You burn to ash before your foes' eyes.
    keywords:
        - Magic
    level: "1"
    name: Pyre
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/pyre
    spend: '1 Ferocity: When you [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) this way, each enemy adjacent to your original space takes lightning or fire damage (your choice) equal to your Intuition score.'
    subclass: spark
    target: Self
    trigger: You take damage.
    type: ability
name: Pyre
target: Self
trigger: You take damage.
type: feature
usage: Triggered Action
```
