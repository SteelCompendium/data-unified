---
action_type: Maneuver
class: conduit
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: The target can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
file_basename: healing-grace
file_dpath: feature/ability/conduit/level-1
flavor: Your divine energy restores the righteous.
item_id: healing-grace
item_name: Healing Grace
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Healing Grace
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/healing-grace
source: mcdm.heroes.v1
spend: '1+ Piety: For each piety spent, choose one of the following [enhancements](scc.v1:mcdm.heroes.v1/rule.treasure/enhancement):'
target: Self or one ally
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    - effect: '1+ Piety: For each piety spent, choose one of the following [enhancements](scc.v1:mcdm.heroes.v1/rule.treasure/enhancement):'
      name: Spend
feature_type: ability
flavor: Your divine energy restores the righteous.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Maneuver
    class: conduit
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: The target can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    flavor: Your divine energy restores the righteous.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Healing Grace
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/healing-grace
    spend: '1+ Piety: For each piety spent, choose one of the following [enhancements](scc.v1:mcdm.heroes.v1/rule.treasure/enhancement):'
    target: Self or one ally
    type: ability
name: Healing Grace
target: Self or one ally
type: feature
usage: Maneuver
```
