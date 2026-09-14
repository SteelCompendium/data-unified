---
action_type: Maneuver
class: summoner
distance: 4 burst
effects:
    - effect: You can use this ability as if in the space of one of your minions within your Summoner's Range.
      name: Effect
    - effect: Each target is R < AVERAGE [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw)).
    - effect: Until the end of the encounter, whenever a target gets a [tier](scc.v1:mcdm.heroes.v1/rule.dice/tier-outcome) 1 result on a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), they deal half [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage). If a target was striking a creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to one of their allies, they target their ally instead.
feature_source: summoner
feature_type: ability
file_basename: their-pall-shrouds-all
file_dpath: feature/ability/summoner/level-6
flavor: Your champion fills the area with a thick haze hiding friend from foe.
item_id: their-pall-shrouds-all
item_name: Their Pall Shrouds All
keywords:
    - Area
    - Champion
    - Magic
level: "6"
name: Their Pall Shrouds All
scc: mcdm.summoner.v1/feature.ability.summoner.level-6/their-pall-shrouds-all
source: mcdm.summoner.v1
target: Each enemy in the area
type: ability
---

```ds-feature
distance: 4 burst
effects:
    - effect: You can use this ability as if in the space of one of your minions within your Summoner's Range.
      name: Effect
    - effect: Each target is R < AVERAGE [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw)).
    - effect: Until the end of the encounter, whenever a target gets a [tier](scc.v1:mcdm.heroes.v1/rule.dice/tier-outcome) 1 result on a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), they deal half [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage). If a target was striking a creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to one of their allies, they target their ally instead.
feature_type: ability
flavor: Your champion fills the area with a thick haze hiding friend from foe.
keywords:
    - Area
    - Champion
    - Magic
metadata:
    action_type: Maneuver
    class: summoner
    distance: 4 burst
    effects:
        - effect: You can use this ability as if in the space of one of your minions within your Summoner's Range.
          name: Effect
        - effect: Each target is R < AVERAGE [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw)).
        - effect: Until the end of the encounter, whenever a target gets a [tier](scc.v1:mcdm.heroes.v1/rule.dice/tier-outcome) 1 result on a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), they deal half [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage). If a target was striking a creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to one of their allies, they target their ally instead.
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
name: Their Pall Shrouds All
target: Each enemy in the area
type: feature
usage: Maneuver
```
