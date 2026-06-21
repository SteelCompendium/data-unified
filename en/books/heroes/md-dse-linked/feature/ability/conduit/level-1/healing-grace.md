---
action_type: Maneuver
class: conduit
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: The target can spend a [Recovery](../../../../rule/health/recoveries.md).
feature_type: ability
file_basename: healing-grace
file_dpath: feature/ability/conduit/level-1
flavor: Your divine energy restores the righteous.
item_id: healing-grace
item_name: Healing Grace
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "1"
name: Healing Grace
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/healing-grace
source: mcdm.heroes.v1
spend: '1+ Piety: For each piety spent, choose one of the following [enhancements](../../../../rule/treasure/enhancement.md):'
target: Self or one ally
type: ability
---

```ds-feature
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: The target can spend a [Recovery](../../../../rule/health/recoveries.md).
    - effect: '1+ Piety: For each piety spent, choose one of the following [enhancements](../../../../rule/treasure/enhancement.md):'
      name: Spend
feature_type: ability
flavor: Your divine energy restores the righteous.
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: Maneuver
    class: conduit
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: The target can spend a [Recovery](../../../../rule/health/recoveries.md).
    flavor: Your divine energy restores the righteous.
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "1"
    name: Healing Grace
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/healing-grace
    spend: '1+ Piety: For each piety spent, choose one of the following [enhancements](../../../../rule/treasure/enhancement.md):'
    target: Self or one ally
    type: ability
name: Healing Grace
target: Self or one ally
type: feature
usage: Maneuver
```
