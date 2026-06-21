---
action_type: Maneuver
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: Until the end of the encounter, whenever one target takes damage, the other target can use a free [triggered action](scc.v1:mcdm.heroes.v1/feature.conduit.level-1/triggered-action) to take the damage instead. The original target suffers any effects associated with the damage. Additionally, whenever one target spends a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries), the other target can use a free [triggered action](scc.v1:mcdm.heroes.v1/feature.conduit.level-1/triggered-action) to spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
file_basename: sacred-bond
file_dpath: feature/ability/conduit/level-2
flavor: You forge a divine connection between two creatures.
item_id: sacred-bond
item_name: Sacred Bond
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "2"
name: Sacred Bond
scc: mcdm.heroes.v1/feature.ability.conduit.level-2/sacred-bond
source: mcdm.heroes.v1
target: Self and one ally
type: ability
---

```ds-feature
cost: 5 Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: Until the end of the encounter, whenever one target takes damage, the other target can use a free [triggered action](scc.v1:mcdm.heroes.v1/feature.conduit.level-1/triggered-action) to take the damage instead. The original target suffers any effects associated with the damage. Additionally, whenever one target spends a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries), the other target can use a free [triggered action](scc.v1:mcdm.heroes.v1/feature.conduit.level-1/triggered-action) to spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
flavor: You forge a divine connection between two creatures.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Maneuver
    class: conduit
    cost: 5 Piety
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: Until the end of the encounter, whenever one target takes damage, the other target can use a free [triggered action](scc.v1:mcdm.heroes.v1/feature.conduit.level-1/triggered-action) to take the damage instead. The original target suffers any effects associated with the damage. Additionally, whenever one target spends a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries), the other target can use a free [triggered action](scc.v1:mcdm.heroes.v1/feature.conduit.level-1/triggered-action) to spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    flavor: You forge a divine connection between two creatures.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "2"
    name: Sacred Bond
    scc: mcdm.heroes.v1/feature.ability.conduit.level-2/sacred-bond
    target: Self and one ally
    type: ability
name: Sacred Bond
target: Self and one ally
type: feature
usage: Maneuver
```
