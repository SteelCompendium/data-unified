---
action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
class: troubadour
cost: 3 Drama
cost_amount: "3"
cost_resource: Drama
distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - effect: The target can choose one additional target for the triggering ability. Any damage dealt to the additional target is sonic damage.
      name: Effect
    - cost: Spend 1+ Drama
      effect: You can trigger this ability when a target uses an ability that has a [Heroic Resource](../../../../rule/resource/heroic-resource.md) cost of 3 + each additional drama spent.
feature_type: ability
file_basename: harmonize
file_dpath: feature/ability/troubadour/level-1
flavor: Give the chorus a little punch.
item_id: harmonize
item_name: Harmonize
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "1"
name: Harmonize
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/harmonize
source: mcdm.heroes.v1
subclass: virtuoso
subtype: triggered
target: One ally
trigger: The target uses an ability that targets only one enemy and costs 3 or fewer of their [Heroic Resource](../../../../rule/resource/heroic-resource.md).
type: ability
---

```ds-feature
cost: 3 Drama
distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - effect: The target can choose one additional target for the triggering ability. Any damage dealt to the additional target is sonic damage.
      name: Effect
    - cost: Spend 1+ Drama
      effect: You can trigger this ability when a target uses an ability that has a [Heroic Resource](../../../../rule/resource/heroic-resource.md) cost of 3 + each additional drama spent.
feature_type: ability
flavor: Give the chorus a little punch.
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
    class: troubadour
    cost: 3 Drama
    distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
    effects:
        - effect: The target can choose one additional target for the triggering ability. Any damage dealt to the additional target is sonic damage.
          name: Effect
        - cost: Spend 1+ Drama
          effect: You can trigger this ability when a target uses an ability that has a [Heroic Resource](../../../../rule/resource/heroic-resource.md) cost of 3 + each additional drama spent.
    flavor: Give the chorus a little punch.
    keywords:
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "1"
    name: Harmonize
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/harmonize
    subclass: virtuoso
    subtype: triggered
    target: One ally
    trigger: The target uses an ability that targets only one enemy and costs 3 or fewer of their [Heroic Resource](../../../../rule/resource/heroic-resource.md).
    type: ability
name: Harmonize
target: One ally
trigger: The target uses an ability that targets only one enemy and costs 3 or fewer of their [Heroic Resource](../../../../rule/resource/heroic-resource.md).
type: feature
usage: '[Triggered](../../../../rule/combat/triggered-action.md)'
```
