---
action_type: Maneuver
class: beastheart
distance: Melee 1
effects:
    - effect: The target takes damage equal to 3 + your Might score. Before you use this ability, you can [jump](../../../../movement/jump.md) up to a number of squares equal to your Intuition score in a straight line. During this jump, enemies' spaces don't count as [difficult terrain](../../../../movement/difficult-terrain.md) for you. The target takes extra lightning damage equal to the number of squares you jumped this way.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: Your jump doesn't provoke opportunity attacks.
feature_type: ability
file_basename: lightning-leap
file_dpath: feature/ability/beastheart/level-1
flavor: You summon a lightning bolt and ride it into battle.
item_id: lightning-leap
item_name: Lightning Leap
keywords:
    - Beastheart
    - Melee
    - Weapon
level: "1"
name: Lightning Leap
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/lightning-leap
source: mcdm.beastheart.v1
subclass: prowler
target: One creature
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: The target takes damage equal to 3 + your Might score. Before you use this ability, you can [jump](../../../../movement/jump.md) up to a number of squares equal to your Intuition score in a straight line. During this jump, enemies' spaces don't count as [difficult terrain](../../../../movement/difficult-terrain.md) for you. The target takes extra lightning damage equal to the number of squares you jumped this way.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: Your jump doesn't provoke opportunity attacks.
feature_type: ability
flavor: You summon a lightning bolt and ride it into battle.
keywords:
    - Beastheart
    - Melee
    - Weapon
metadata:
    action_type: Maneuver
    class: beastheart
    distance: Melee 1
    effects:
        - effect: The target takes damage equal to 3 + your Might score. Before you use this ability, you can [jump](../../../../movement/jump.md) up to a number of squares equal to your Intuition score in a straight line. During this jump, enemies' spaces don't count as [difficult terrain](../../../../movement/difficult-terrain.md) for you. The target takes extra lightning damage equal to the number of squares you jumped this way.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: Your jump doesn't provoke opportunity attacks.
    flavor: You summon a lightning bolt and ride it into battle.
    keywords:
        - Beastheart
        - Melee
        - Weapon
    level: "1"
    name: Lightning Leap
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/lightning-leap
    subclass: prowler
    target: One creature
    type: ability
name: Lightning Leap
target: One creature
type: feature
usage: Maneuver
```
