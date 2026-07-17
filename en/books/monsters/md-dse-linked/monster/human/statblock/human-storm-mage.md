---
agility: 0
ev: "10"
file_basename: human-storm-mage
file_dpath: monster/human/statblock
free_strike: 5
immunities:
    - Corruption 3
    - psychic 3
intuition: 0
item_id: human-storm-mage
item_name: Human Storm Mage
keywords:
    - Human
    - Humanoid
level: 3
might: 0
name: Human Storm Mage
organization: Platoon
presence: 1
reason: 2
role: Controller
scc: mcdm.monsters.v1/monster.human.statblock/human-storm-mage
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "40"
type: statblock
---

```ds-sb
agility: 0
ev: "10"
features:
    - ability_type: Signature Ability
      distance: Ranged 15
      effects:
        - roll: Power Roll + 2
          tier1: 7 lightning damage
          tier2: 10 lightning damage
          tier3: 13 lightning damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Lightning Bolt
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 5 cube within 1
      effects:
        - roll: Power Roll + 2
          tier1: '[Slide](../../../movement/forced-movement.md) 2; M < 0 [slowed](../../../condition/slowed.md) (save ends)'
          tier2: '[Slide](../../../movement/forced-movement.md) 4; M < 1 [slowed](../../../condition/slowed.md) (save ends)'
          tier3: '[Slide](../../../movement/forced-movement.md) 6; M < 2 [slowed](../../../condition/slowed.md) (save ends)'
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      name: Gust of Wind
      target: Each enemy and object in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: |-
            Any melee ability targeting the storm mage takes a bane.
            Additionally, whenever the mage takes damage from an [adjacent](../../../rule/combat/adjacent.md) enemy, the enemy takes 2 lightning damage, and if they have R < 1 they are [pushed](../../../movement/forced-movement.md) up to 2 squares.
      feature_type: trait
      icon: ⭐️
      name: Arcane Shield
      type: feature
    - effects:
        - effect: The storm mage ignores concealment if it's granted by a supernatural effect.
      feature_type: trait
      icon: ⭐️
      name: Supernatural Insight
      type: feature
free_strike: 5
immunities:
    - Corruption 3
    - psychic 3
intuition: 0
keywords:
    - Human
    - Humanoid
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.human.statblock/human-storm-mage
    source: mcdm.monsters.v1
might: 0
name: Human Storm Mage
organization: Platoon
presence: 1
reason: 2
role: Controller
size: 1M
speed: 5
stability: 0
stamina: "40"
type: statblock
```
