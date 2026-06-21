---
action_type: Main action
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: Until the end of the encounter, whenever you or any ally damages the target using an ability, that creature can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries). If the target is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) before the end of the encounter, you can use a free [triggered action](scc.v1:mcdm.heroes.v1/feature.conduit.level-1/triggered-action) to move this effect to another creature within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance).
feature_type: ability
file_basename: beacon-of-grace
file_dpath: feature/ability/conduit/level-5
flavor: You ignite a foe with holy radiance, rewarding allies who attack them.
item_id: beacon-of-grace
item_name: Beacon of Grace
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "5"
name: Beacon of Grace
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-5/beacon-of-grace
source: mcdm.heroes.v1
target: One creature
tier1: 8 + I holy damage
tier2: 13 + I holy damage
tier3: 17 + I holy damage
type: ability
---

```ds-feature
cost: 9 Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: Until the end of the encounter, whenever you or any ally damages the target using an ability, that creature can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries). If the target is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) before the end of the encounter, you can use a free [triggered action](scc.v1:mcdm.heroes.v1/feature.conduit.level-1/triggered-action) to move this effect to another creature within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance).
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 8 + I holy damage
      tier2: 13 + I holy damage
      tier3: 17 + I holy damage
feature_type: ability
flavor: You ignite a foe with holy radiance, rewarding allies who attack them.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: conduit
    cost: 9 Piety
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: Until the end of the encounter, whenever you or any ally damages the target using an ability, that creature can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries). If the target is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) before the end of the encounter, you can use a free [triggered action](scc.v1:mcdm.heroes.v1/feature.conduit.level-1/triggered-action) to move this effect to another creature within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance).
    flavor: You ignite a foe with holy radiance, rewarding allies who attack them.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "5"
    name: Beacon of Grace
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-5/beacon-of-grace
    target: One creature
    tier1: 8 + I holy damage
    tier2: 13 + I holy damage
    tier3: 17 + I holy damage
    type: ability
name: Beacon of Grace
target: One creature
type: feature
usage: Main action
```
