---
action_type: Maneuver
class: beastheart
companion: sporeling
distance: Melee 1
effects:
    - effect: The target takes poison damage equal to 3 + the sporeling's Might score, and the sporeling is invisible to the target until the end of the sporeling's next turn or they deal damage to the target.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: If the target has M < STRONG, they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) until the end of their next turn.
feature_type: ability
file_basename: spore-puff
file_dpath: feature/ability/companion/beastheart/sporeling/level-1
flavor: The sporeling breathes a cloud of disorienting fumes.
item_id: spore-puff
item_name: Spore Puff
keywords:
    - Companion
    - Melee
level: "1"
name: Spore Puff
scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.sporeling.level-1/spore-puff
source: mcdm.beastheart.v1
subtype: signature
target: One enemy
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: The target takes poison damage equal to 3 + the sporeling's Might score, and the sporeling is invisible to the target until the end of the sporeling's next turn or they deal damage to the target.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: If the target has M < STRONG, they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) until the end of their next turn.
feature_type: ability
flavor: The sporeling breathes a cloud of disorienting fumes.
keywords:
    - Companion
    - Melee
metadata:
    action_type: Maneuver
    class: beastheart
    companion: sporeling
    distance: Melee 1
    effects:
        - effect: The target takes poison damage equal to 3 + the sporeling's Might score, and the sporeling is invisible to the target until the end of the sporeling's next turn or they deal damage to the target.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: If the target has M < STRONG, they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) until the end of their next turn.
    flavor: The sporeling breathes a cloud of disorienting fumes.
    keywords:
        - Companion
        - Melee
    level: "1"
    name: Spore Puff
    scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.sporeling.level-1/spore-puff
    subtype: signature
    target: One enemy
    type: ability
name: Spore Puff
target: One enemy
type: feature
usage: Maneuver
```
