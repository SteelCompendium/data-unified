---
agility: 1
ev: "16"
file_basename: ogre-juggernaut
file_dpath: monster/ogre/statblock
free_strike: 5
intuition: 0
item_id: ogre-juggernaut
item_name: Ogre Juggernaut
keywords:
    - Giant
    - Ogre
level: 2
might: 2
name: Ogre Juggernaut
organization: Elite
presence: -1
reason: -1
role: Harrier
scc: mcdm.monsters.v1/monster.ogre.statblock/ogre-juggernaut
size: "2"
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "80"
type: statblock
---

```ds-sb
agility: 1
ev: "16"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage
          tier2: 10 damage; A < 1 vertical [push](../../../movement/forced-movement.md) 2
          tier3: 13 damage; A < 2 vertical [slide](../../../movement/forced-movement.md) 3
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Pitchfork Catapult
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: 3 burst
      effects:
        - roll: Power Roll + 2
          tier1: 4 damage
          tier2: 6 damage; [push](../../../movement/forced-movement.md) 2; M < 1 [prone](../../../condition/prone.md)
          tier3: 9 damage; [push](../../../movement/forced-movement.md) 4; M < 2 [prone](../../../condition/prone.md)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Weapon
      name: Earth-Breaking Jump
      target: Each creature in the area
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: 3 burst
      effects:
        - roll: Power Roll + 2
          tier1: I < 0 [frightened](../../../condition/frightened.md) (save ends)
          tier2: I < 1 [frightened](../../../condition/frightened.md) (save ends)
          tier3: I < 2 [frightened](../../../condition/frightened.md) (save ends)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Horrible Bellow
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: Self
      effects:
        - effect: |-
            **Trigger:** The juggernaut takes damage.
            **Effect:** The juggernaut moves up to their speed and can make a [free strike](../../../feature/common/main-actions/free-strike.md).
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Hrraaaaaagh!
      target: Self
      type: feature
      usage: Free triggered action
    - effects:
        - effect: The juggernaut automatically destroys any mundane size 1 objects in their path when they move or are [force moved](../../../movement/forced-movement.md). They can break through any mundane wall made of wood, stone, or a similarly sturdy material this way as long as the wall is 2 squares thick or less.
      feature_type: trait
      icon: ⭐️
      name: Destructive Path
      type: feature
    - effects:
        - effect: While [winded](../../../rule/health/winded.md), the juggernaut has damage immunity 2.
      feature_type: trait
      icon: ⭐️
      name: Defiant Anger
      type: feature
free_strike: 5
intuition: 0
keywords:
    - Giant
    - Ogre
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.ogre.statblock/ogre-juggernaut
    source: mcdm.monsters.v1
might: 2
name: Ogre Juggernaut
organization: Elite
presence: -1
reason: -1
role: Harrier
size: "2"
speed: 6
stability: 2
stamina: "80"
type: statblock
```
