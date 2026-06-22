---
action_type: Triggered
class: troubadour
cost: 3 Drama
cost_amount: "3"
cost_resource: Drama
distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
effect: The target can choose one additional target for the triggering ability. Any damage dealt to the additional target is sonic damage.
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
spend: '1+ Drama: You can trigger this ability when a target uses an ability that has a [Heroic Resource](../../../../rule/resource/heroic-resource.md) cost of 3 + each additional drama spent.'
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
    - effect: '1+ Drama: You can trigger this ability when a target uses an ability that has a [Heroic Resource](../../../../rule/resource/heroic-resource.md) cost of 3 + each additional drama spent.'
      name: Spend
feature_type: ability
flavor: Give the chorus a little punch.
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: Triggered
    class: troubadour
    cost: 3 Drama
    distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
    effect: The target can choose one additional target for the triggering ability. Any damage dealt to the additional target is sonic damage.
    flavor: Give the chorus a little punch.
    keywords:
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "1"
    name: Harmonize
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/harmonize
    spend: '1+ Drama: You can trigger this ability when a target uses an ability that has a [Heroic Resource](../../../../rule/resource/heroic-resource.md) cost of 3 + each additional drama spent.'
    subclass: virtuoso
    subtype: triggered
    target: One ally
    trigger: The target uses an ability that targets only one enemy and costs 3 or fewer of their [Heroic Resource](../../../../rule/resource/heroic-resource.md).
    type: ability
name: Harmonize
target: One ally
trigger: The target uses an ability that targets only one enemy and costs 3 or fewer of their [Heroic Resource](../../../../rule/resource/heroic-resource.md).
type: feature
usage: Triggered
```
