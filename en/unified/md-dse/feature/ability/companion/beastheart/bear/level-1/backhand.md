---
action_type: Maneuver
class: beastheart
companion: bear
distance: Melee 1
effect: The target takes damage equal to 4 + the bear's Might score and is pushed up to 2 squares.
feature_type: ability
file_basename: backhand
file_dpath: feature/ability/companion/beastheart/bear/level-1
flavor: The bear casually swats the pesky foe into next week.
item_id: backhand
item_name: Backhand
keywords:
    - Companion
    - Melee
    - Weapon
level: "1"
name: Backhand
scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.bear.level-1/backhand
source: mcdm.beastheart.v1
spend: '1 Ferocity: The target is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to a number of additional squares equal to the bear''s Might score.'
subtype: signature
target: One creature or object
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: The target takes damage equal to 4 + the bear's Might score and is pushed up to 2 squares.
    - effect: '1 Ferocity: The target is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to a number of additional squares equal to the bear''s Might score.'
      name: Spend
feature_type: ability
flavor: The bear casually swats the pesky foe into next week.
keywords:
    - Companion
    - Melee
    - Weapon
metadata:
    action_type: Maneuver
    class: beastheart
    companion: bear
    distance: Melee 1
    effect: The target takes damage equal to 4 + the bear's Might score and is pushed up to 2 squares.
    flavor: The bear casually swats the pesky foe into next week.
    keywords:
        - Companion
        - Melee
        - Weapon
    level: "1"
    name: Backhand
    scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.bear.level-1/backhand
    spend: '1 Ferocity: The target is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to a number of additional squares equal to the bear''s Might score.'
    subtype: signature
    target: One creature or object
    type: ability
name: Backhand
target: One creature or object
type: feature
usage: Maneuver
```
