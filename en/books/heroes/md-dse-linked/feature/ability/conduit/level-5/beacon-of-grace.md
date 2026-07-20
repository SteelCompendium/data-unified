---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: Until the end of the encounter, whenever you or any ally damages the target using an ability, that creature can spend a [Recovery](../../../../rule/health/recoveries.md). If the target is reduced to 0 [Stamina](../../../../rule/health/stamina.md) before the end of the encounter, you can use a free [triggered action](../../../conduit/level-1/triggered-action.md) to move this effect to another creature within [distance](../../../../rule/combat/distance.md).
feature_type: ability
file_basename: beacon-of-grace
file_dpath: feature/ability/conduit/level-5
flavor: You ignite a foe with holy radiance, rewarding allies who attack them.
item_id: beacon-of-grace
item_name: Beacon of Grace
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
level: "5"
name: Beacon of Grace
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
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
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: Until the end of the encounter, whenever you or any ally damages the target using an ability, that creature can spend a [Recovery](../../../../rule/health/recoveries.md). If the target is reduced to 0 [Stamina](../../../../rule/health/stamina.md) before the end of the encounter, you can use a free [triggered action](../../../conduit/level-1/triggered-action.md) to move this effect to another creature within [distance](../../../../rule/combat/distance.md).
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 8 + I holy damage
      tier2: 13 + I holy damage
      tier3: 17 + I holy damage
feature_type: ability
flavor: You ignite a foe with holy radiance, rewarding allies who attack them.
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: conduit
    cost: 9 Piety
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: Until the end of the encounter, whenever you or any ally damages the target using an ability, that creature can spend a [Recovery](../../../../rule/health/recoveries.md). If the target is reduced to 0 [Stamina](../../../../rule/health/stamina.md) before the end of the encounter, you can use a free [triggered action](../../../conduit/level-1/triggered-action.md) to move this effect to another creature within [distance](../../../../rule/combat/distance.md).
    flavor: You ignite a foe with holy radiance, rewarding allies who attack them.
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
    level: "5"
    name: Beacon of Grace
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-5/beacon-of-grace
    target: One creature
    tier1: 8 + I holy damage
    tier2: 13 + I holy damage
    tier3: 17 + I holy damage
    type: ability
name: Beacon of Grace
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
