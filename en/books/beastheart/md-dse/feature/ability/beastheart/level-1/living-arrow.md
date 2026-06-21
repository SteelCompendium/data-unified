---
action_type: Maneuver
class: beastheart
distance: Ranged 10
effect: If your companion is within range and can fit into the target space, they [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to the space. They can then make a melee free strike.
feature_type: ability
file_basename: living-arrow
file_dpath: feature/ability/beastheart/level-1
flavor: You point, and your companion appears.
item_id: living-arrow
item_name: Living Arrow
keywords:
    - Beastheart
    - Magic
    - Ranged
level: "1"
name: Living Arrow
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/living-arrow
source: mcdm.beastheart.v1
spend: '1 Ferocity: The distance increases to ranged 15.'
subclass: guardian
target: One unoccupied space
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: If your companion is within range and can fit into the target space, they [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to the space. They can then make a melee free strike.
    - effect: '1 Ferocity: The distance increases to ranged 15.'
      name: Spend
feature_type: ability
flavor: You point, and your companion appears.
keywords:
    - Beastheart
    - Magic
    - Ranged
metadata:
    action_type: Maneuver
    class: beastheart
    distance: Ranged 10
    effect: If your companion is within range and can fit into the target space, they [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to the space. They can then make a melee free strike.
    flavor: You point, and your companion appears.
    keywords:
        - Beastheart
        - Magic
        - Ranged
    level: "1"
    name: Living Arrow
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/living-arrow
    spend: '1 Ferocity: The distance increases to ranged 15.'
    subclass: guardian
    target: One unoccupied space
    type: ability
name: Living Arrow
target: One unoccupied space
type: feature
usage: Maneuver
```
