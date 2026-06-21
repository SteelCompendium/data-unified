---
action_type: Maneuver
class: beastheart
distance: 2 cube within 5
effect: Each target takes cold, fire, lightning, or sonic damage (your choice) equal to your Might score.
feature_type: ability
file_basename: jaws-of-the-storm
file_dpath: feature/ability/beastheart/level-1
flavor: Your foes are torn by a tempest of primordial teeth and claws.
item_id: jaws-of-the-storm
item_name: Jaws of the Storm
keywords:
    - Area
    - Beastheart
    - Magic
level: "1"
name: Jaws of the Storm
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/jaws-of-the-storm
source: mcdm.beastheart.v1
spend: '1 Ferocity: The size of the cube increases by 1.'
subclass: spark
target: Each enemy in the area
type: ability
---

```ds-feature
distance: 2 cube within 5
effects:
    - effect: Each target takes cold, fire, lightning, or sonic damage (your choice) equal to your Might score.
    - effect: '1 Ferocity: The size of the cube increases by 1.'
      name: Spend
feature_type: ability
flavor: Your foes are torn by a tempest of primordial teeth and claws.
keywords:
    - Area
    - Beastheart
    - Magic
metadata:
    action_type: Maneuver
    class: beastheart
    distance: 2 cube within 5
    effect: Each target takes cold, fire, lightning, or sonic damage (your choice) equal to your Might score.
    flavor: Your foes are torn by a tempest of primordial teeth and claws.
    keywords:
        - Area
        - Beastheart
        - Magic
    level: "1"
    name: Jaws of the Storm
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/jaws-of-the-storm
    spend: '1 Ferocity: The size of the cube increases by 1.'
    subclass: spark
    target: Each enemy in the area
    type: ability
name: Jaws of the Storm
target: Each enemy in the area
type: feature
usage: Maneuver
```
