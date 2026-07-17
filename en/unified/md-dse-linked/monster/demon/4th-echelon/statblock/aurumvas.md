---
agility: 2
ev: "48"
file_basename: aurumvas
file_dpath: monster/demon/4th-echelon/statblock
free_strike: 10
intuition: 3
item_id: aurumvas
item_name: Aurumvas
keywords:
    - Abyssal
    - Demon
level: 10
might: 5
movement: Fly
name: Aurumvas
organization: Leader
presence: 5
reason: 5
scc: mcdm.monsters.v1/monster.demon.4th-echelon.statblock/aurumvas
size: "3"
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: "260"
type: statblock
weaknesses:
    - Holy 5
---

```ds-sb
agility: 2
ev: "48"
features:
    - effects:
        - effect: Whenever any demon is reduced to 0 [Stamina](../../../../rule/health/stamina.md) within 10 squares of Aurumvas, the Director gains 1 [Malice](../../../../rule/monster/malice.md). Aurumvas loses this trait while he is [dazed](../../../../condition/dazed.md).
      feature_type: trait
      icon: ⭐️
      name: Absorb Soul
      type: feature
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 5
          tier1: 15 corruption damage; R < 4 [weakened](../../../../condition/weakened.md) (save ends)
          tier2: 20 corruption damage; R < 5 [weakened](../../../../condition/weakened.md) (save ends)
          tier3: 24 corruption damage; R < 6 [weakened](../../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Magic
        - Melee
        - Strike
      name: Greedy Hands
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Ranged 20
      effects:
        - roll: Power Roll + 5
          tier1: 15 psychic damage; P < 4 [dazed](../../../../condition/dazed.md) (save ends)
          tier2: 20 psychic damage; P < 5 [dazed](../../../../condition/dazed.md) (save ends)
          tier3: 24 psychic damage; P < 6 [dazed](../../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Covetous Bolts
      target: Two creatures
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Ranged 10
      effects:
        - effect: '**Effect:** Aurumvas chooses a supernatural treasure or an item made of gold and [teleports](../../../../movement/teleport.md) to an unoccupied space [adjacent](../../../../rule/combat/adjacent.md) to that object, then ends one effect on him that can be ended by a [saving throw](../../../../rule/general/saving-throw.md).'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: Greed Is Good
      target: Special
      type: feature
      usage: Maneuver
    - effects:
        - effect: While Aurumvas is [winded](../../../../rule/health/winded.md), he has a double [edge](../../../../rule/dice/edge.md) on strikes.
      feature_type: trait
      icon: ⭐️
      name: More... More...
      type: feature
    - effects:
        - effect: Any creature within 5 squares of Aurumvas can't be hidden from him.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
    - cost: Villain Action 1
      distance: 20 burst
      effects:
        - effect: '**Effect:** Aurumvas warps time with his abyssal avarice. Each target can [teleport](../../../../movement/teleport.md) up to their speed and make a [free strike](../../../../feature/common/main-actions/free-strike.md).'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Time Is Money
      target: Self and each ally in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: Ranged 10
      effects:
        - effect: '**Effect:** Aurumvas chooses up to three treasures within distance that he has [line of effect](../../../../rule/combat/line-of-effect.md) to and that aren''t artifacts. Until the end of the encounter, ethereal golden snakes swirl around the target treasures. While an affected treasure is worn or held by a hero, each time that hero gains any amount of their [Heroic Resource](../../../../rule/resource/heroic-resource.md), the Director gains 1 [Malice](../../../../rule/monster/malice.md).'
      feature_type: ability
      icon: ☠️
      keywords:
        - Ranged
      name: Hostile Acquisition
      target: Special
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: Four 3 cubes within 10
      effects:
        - roll: Power Roll + 5
          tier1: 10 fire damage; push 1
          tier2: 15 fire damage; push 2
          tier3: 19 fire damage; push 3
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
        - Ranged
      name: No Matter the Cost
      target: Each creature in the area
      type: feature
      usage: '-'
free_strike: 10
intuition: 3
keywords:
    - Abyssal
    - Demon
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.demon.4th-echelon.statblock/aurumvas
    source: mcdm.monsters.v1
might: 5
movement: Fly
name: Aurumvas
organization: Leader
presence: 5
reason: 5
role: ""
size: "3"
speed: 8
stability: 2
stamina: "260"
type: statblock
weaknesses:
    - Holy 5
```
