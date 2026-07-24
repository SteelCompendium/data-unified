---
action_type: Maneuver
class: summoner
distance: 4 burst
effects:
    - effect: You can use this ability as if in the space of one of your minions within your Summoner's Range.
      name: Effect
feature_source: summoner
flavor: Your champion fills the area with a thick haze hiding friend from foe.
keywords:
    - Area
    - Champion
    - Magic
level: "6"
name: Their Pall Shrouds All
scc: mcdm.summoner.v1/feature.ability.summoner.level-6/their-pall-shrouds-all
target: Each enemy in the area
type: ability
---

*Your champion fills the area with a thick haze hiding friend from foe.*

| **Area, Champion, Magic** | **Maneuver** |
|---------------------------|-------------:|
| **📏 4 burst** | **🎯 Each enemy in the area** |

**Effect:** You can use this ability as if in the space of one of your minions within your Summoner's Range.

Each target is R < AVERAGE [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw)).

Until the end of the encounter, whenever a target gets a [tier](scc.v1:mcdm.heroes.v1/rule.dice/tier-outcome) 1 result on a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), they deal half [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage). If a target was striking a creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to one of their allies, they target their ally instead.
