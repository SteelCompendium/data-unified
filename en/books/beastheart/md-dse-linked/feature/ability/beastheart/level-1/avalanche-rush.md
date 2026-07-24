---
action_type: Maneuver
class: beastheart
distance: Melee 1
effects:
    - effect: The target takes damage equal to 3 + your Might score, and if they have M < AVERAGE, they are knocked [prone](../../../../condition/prone.md).
      name: Effect
    - cost: Spend 1 Ferocity
      effect: If the target has M < STRONG, they are knocked [prone](../../../../condition/prone.md).
feature_type: ability
file_basename: avalanche-rush
file_dpath: feature/ability/beastheart/level-1
flavor: You ride a cascade of ice over your foes.
item_id: avalanche-rush
item_name: Avalanche Rush
keywords:
    - Beastheart
    - Melee
    - Weapon
level: "1"
name: Avalanche Rush
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/avalanche-rush
source: mcdm.beastheart.v1
subclass: punisher
target: One creature
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: The target takes damage equal to 3 + your Might score, and if they have M < AVERAGE, they are knocked [prone](../../../../condition/prone.md).
      name: Effect
    - cost: Spend 1 Ferocity
      effect: If the target has M < STRONG, they are knocked [prone](../../../../condition/prone.md).
feature_type: ability
flavor: You ride a cascade of ice over your foes.
keywords:
    - Beastheart
    - Melee
    - Weapon
metadata:
    action_type: Maneuver
    class: beastheart
    distance: Melee 1
    effects:
        - effect: The target takes damage equal to 3 + your Might score, and if they have M < AVERAGE, they are knocked [prone](../../../../condition/prone.md).
          name: Effect
        - cost: Spend 1 Ferocity
          effect: If the target has M < STRONG, they are knocked [prone](../../../../condition/prone.md).
    flavor: You ride a cascade of ice over your foes.
    keywords:
        - Beastheart
        - Melee
        - Weapon
    level: "1"
    name: Avalanche Rush
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/avalanche-rush
    subclass: punisher
    target: One creature
    type: ability
name: Avalanche Rush
target: One creature
type: feature
usage: Maneuver
```
