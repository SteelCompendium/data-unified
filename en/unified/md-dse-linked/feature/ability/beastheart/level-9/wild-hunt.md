---
action_type: Main action
class: beastheart
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: 5 cube within 20
effects:
    - effect: Your companion summons a ghostly pack of creatures that resemble them to fill the area. The pack can appear in and move through creatures, objects, and terrain. Once summoned, the pack moves in a straight line toward your companion until it's centered on your companion's space, then continues moving in a straight line until it is up to 20 squares away.
      name: Effect
    - roll: Power Roll + Might
      tier1: 9 damage
      tier2: 13 damage
      tier3: 18 damage
feature_type: ability
file_basename: wild-hunt
file_dpath: feature/ability/beastheart/level-9
flavor: Your companion summons a ravening pack of spectral ancestors to devour your foes.
item_id: wild-hunt
item_name: Wild Hunt
keywords:
    - Area
    - Companion
    - Magic
level: "9"
name: Wild Hunt
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-9/wild-hunt
source: mcdm.beastheart.v1
subclass: spark
target: Each enemy in the area
tier1: 9 damage
tier2: 13 damage
tier3: 18 damage
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: 5 cube within 20
effects:
    - effect: Your companion summons a ghostly pack of creatures that resemble them to fill the area. The pack can appear in and move through creatures, objects, and terrain. Once summoned, the pack moves in a straight line toward your companion until it's centered on your companion's space, then continues moving in a straight line until it is up to 20 squares away.
      name: Effect
    - roll: Power Roll + Might
      tier1: 9 damage
      tier2: 13 damage
      tier3: 18 damage
feature_type: ability
flavor: Your companion summons a ravening pack of spectral ancestors to devour your foes.
keywords:
    - Area
    - Companion
    - Magic
metadata:
    action_type: Main action
    class: beastheart
    cost: 11 Ferocity
    distance: 5 cube within 20
    effects:
        - effect: Your companion summons a ghostly pack of creatures that resemble them to fill the area. The pack can appear in and move through creatures, objects, and terrain. Once summoned, the pack moves in a straight line toward your companion until it's centered on your companion's space, then continues moving in a straight line until it is up to 20 squares away.
          name: Effect
        - roll: Power Roll + Might
          tier1: 9 damage
          tier2: 13 damage
          tier3: 18 damage
    flavor: Your companion summons a ravening pack of spectral ancestors to devour your foes.
    keywords:
        - Area
        - Companion
        - Magic
    level: "9"
    name: Wild Hunt
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-9/wild-hunt
    subclass: spark
    target: Each enemy in the area
    tier1: 9 damage
    tier2: 13 damage
    tier3: 18 damage
    type: ability
name: Wild Hunt
target: Each enemy in the area
type: feature
usage: Main action
```
