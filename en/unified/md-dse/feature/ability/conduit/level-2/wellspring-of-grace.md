---
action_type: Main action
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: 3 [aura](scc.v1:mcdm.heroes.v1/rule.combat/aura)
effect: Until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), whenever a target starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) in the area, they can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
file_basename: wellspring-of-grace
file_dpath: feature/ability/conduit/level-2
flavor: A holy light is emitted from your body, healing your allies.
item_id: wellspring-of-grace
item_name: Wellspring of Grace
keywords:
    - Area
    - Magic
level: "2"
name: Wellspring of Grace
scc: mcdm.heroes.v1/feature.ability.conduit.level-2/wellspring-of-grace
source: mcdm.heroes.v1
target: Each ally in the area
type: ability
---

```ds-feature
cost: 5 Piety
distance: 3 [aura](scc.v1:mcdm.heroes.v1/rule.combat/aura)
effects:
    - effect: Until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), whenever a target starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) in the area, they can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
flavor: A holy light is emitted from your body, healing your allies.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: conduit
    cost: 5 Piety
    distance: 3 [aura](scc.v1:mcdm.heroes.v1/rule.combat/aura)
    effect: Until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), whenever a target starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) in the area, they can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    flavor: A holy light is emitted from your body, healing your allies.
    keywords:
        - Area
        - Magic
    level: "2"
    name: Wellspring of Grace
    scc: mcdm.heroes.v1/feature.ability.conduit.level-2/wellspring-of-grace
    target: Each ally in the area
    type: ability
name: Wellspring of Grace
target: Each ally in the area
type: feature
usage: Main action
```
