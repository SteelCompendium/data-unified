---
action_type: Maneuver
class: beastheart
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: 3 burst
effects:
    - effect: You can spend a Recovery and gain 3 temporary Stamina for each target. Each target is [taunted](../../../../condition/taunted.md) by you until the end of their next turn.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: This ability also affects a 3 burst originating from your companion. Targets in this second area are [taunted](../../../../condition/taunted.md) by your companion. An enemy in both areas is [taunted](../../../../condition/taunted.md) only by you.
feature_type: ability
file_basename: all-of-you-versus-all-of-me
file_dpath: feature/ability/beastheart/level-1
flavor: Let all of them come forward and shatter themselves against your might!
item_id: all-of-you-versus-all-of-me
item_name: All of You Versus All of Me
keywords:
    - Area
    - Beastheart
level: "1"
name: All of You Versus All of Me
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/all-of-you-versus-all-of-me
source: mcdm.beastheart.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: 3 burst
effects:
    - effect: You can spend a Recovery and gain 3 temporary Stamina for each target. Each target is [taunted](../../../../condition/taunted.md) by you until the end of their next turn.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: This ability also affects a 3 burst originating from your companion. Targets in this second area are [taunted](../../../../condition/taunted.md) by your companion. An enemy in both areas is [taunted](../../../../condition/taunted.md) only by you.
feature_type: ability
flavor: Let all of them come forward and shatter themselves against your might!
keywords:
    - Area
    - Beastheart
metadata:
    action_type: Maneuver
    class: beastheart
    cost: 5 Ferocity
    distance: 3 burst
    effects:
        - effect: You can spend a Recovery and gain 3 temporary Stamina for each target. Each target is [taunted](../../../../condition/taunted.md) by you until the end of their next turn.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: This ability also affects a 3 burst originating from your companion. Targets in this second area are [taunted](../../../../condition/taunted.md) by your companion. An enemy in both areas is [taunted](../../../../condition/taunted.md) only by you.
    flavor: Let all of them come forward and shatter themselves against your might!
    keywords:
        - Area
        - Beastheart
    level: "1"
    name: All of You Versus All of Me
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/all-of-you-versus-all-of-me
    target: Each enemy in the area
    type: ability
name: All of You Versus All of Me
target: Each enemy in the area
type: feature
usage: Maneuver
```
