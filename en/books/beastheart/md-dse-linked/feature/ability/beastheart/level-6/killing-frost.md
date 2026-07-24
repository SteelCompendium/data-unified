---
action_type: Main action
class: beastheart
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: 5 cube within 1
effects:
    - roll: Power Roll + Might
      tier1: 5 cold damage; I < WEAK [restrained](../../../../condition/restrained.md) (save ends)
      tier2: 7 cold damage; I < AVERAGE [restrained](../../../../condition/restrained.md) (save ends)
      tier3: 12 cold damage; I < STRONG [restrained](../../../../condition/restrained.md) (save ends)
    - effect: While [restrained](../../../../condition/restrained.md) this way, a creature takes 5 cold damage at the start of each of your turns. A creature killed by this ability becomes an ice statue and their space is difficult terrain.
      name: Effect
feature_type: ability
file_basename: killing-frost
file_dpath: feature/ability/beastheart/level-6
flavor: Black frost freezes boots to the floor and creeps up trapped victims until they're completely encased in ice.
item_id: killing-frost
item_name: Killing Frost
keywords:
    - Area
    - Companion
    - Magic
level: "6"
name: Killing Frost
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-6/killing-frost
source: mcdm.beastheart.v1
subclass: spark
target: Each enemy in the area
tier1: 5 cold damage; I < WEAK [restrained](../../../../condition/restrained.md) (save ends)
tier2: 7 cold damage; I < AVERAGE [restrained](../../../../condition/restrained.md) (save ends)
tier3: 12 cold damage; I < STRONG [restrained](../../../../condition/restrained.md) (save ends)
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: 5 cube within 1
effects:
    - roll: Power Roll + Might
      tier1: 5 cold damage; I < WEAK [restrained](../../../../condition/restrained.md) (save ends)
      tier2: 7 cold damage; I < AVERAGE [restrained](../../../../condition/restrained.md) (save ends)
      tier3: 12 cold damage; I < STRONG [restrained](../../../../condition/restrained.md) (save ends)
    - effect: While [restrained](../../../../condition/restrained.md) this way, a creature takes 5 cold damage at the start of each of your turns. A creature killed by this ability becomes an ice statue and their space is difficult terrain.
      name: Effect
feature_type: ability
flavor: Black frost freezes boots to the floor and creeps up trapped victims until they're completely encased in ice.
keywords:
    - Area
    - Companion
    - Magic
metadata:
    action_type: Main action
    class: beastheart
    cost: 9 Ferocity
    distance: 5 cube within 1
    effects:
        - roll: Power Roll + Might
          tier1: 5 cold damage; I < WEAK [restrained](../../../../condition/restrained.md) (save ends)
          tier2: 7 cold damage; I < AVERAGE [restrained](../../../../condition/restrained.md) (save ends)
          tier3: 12 cold damage; I < STRONG [restrained](../../../../condition/restrained.md) (save ends)
        - effect: While [restrained](../../../../condition/restrained.md) this way, a creature takes 5 cold damage at the start of each of your turns. A creature killed by this ability becomes an ice statue and their space is difficult terrain.
          name: Effect
    flavor: Black frost freezes boots to the floor and creeps up trapped victims until they're completely encased in ice.
    keywords:
        - Area
        - Companion
        - Magic
    level: "6"
    name: Killing Frost
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-6/killing-frost
    subclass: spark
    target: Each enemy in the area
    tier1: 5 cold damage; I < WEAK [restrained](../../../../condition/restrained.md) (save ends)
    tier2: 7 cold damage; I < AVERAGE [restrained](../../../../condition/restrained.md) (save ends)
    tier3: 12 cold damage; I < STRONG [restrained](../../../../condition/restrained.md) (save ends)
    type: ability
name: Killing Frost
target: Each enemy in the area
type: feature
usage: Main action
```
