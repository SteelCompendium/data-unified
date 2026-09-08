---
agility: 0
ev: "16"
file_basename: ogre-goon
file_dpath: monster/ogre/statblock
free_strike: 5
intuition: 0
item_id: ogre-goon
item_name: Ogre Goon
keywords:
    - Giant
    - Ogre
level: 2
might: 2
name: Ogre Goon
organization: Elite
presence: -1
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.ogre.statblock/ogre-goon
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 4
stamina: "100"
type: statblock
---

```ds-sb
agility: 0
ev: "16"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage; [push](../../../movement/forced-movement.md) 2
          tier2: 11 damage; [push](../../../movement/forced-movement.md) 4
          tier3: 14 damage; [push](../../../movement/forced-movement.md) 6, [prone](../../../condition/prone.md)
        - effect: Any target who takes damage from this [forced movement](../../../movement/forced-movement.md) takes an extra 4 damage.
          name: Effect
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Club Swing
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 1 Malice
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage
          tier2: 11 damage; [grabbed](../../../condition/grabbed.md)
          tier3: 14 damage; [grabbed](../../../condition/grabbed.md)
        - effect: A target [grabbed](../../../condition/grabbed.md) this way takes a bane on the Escape Grab maneuver.
          name: Effect
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Grabby Hand
      target: One creature or object
      type: feature
      usage: Maneuver
    - cost: 3 Malice
      distance: 6 x 1 line within 1
      effects:
        - effect: The goon must have a size 1 creature or object [grabbed](../../../condition/grabbed.md), which they hurl across the area, ending the grab. The hurled creature or object is targeted by the ability, and lands in the last square of the line or the nearest unoccupied square of the goon's choice.
          name: Effect
          roll: Power Roll + 2
          tier1: 5 damage
          tier2: 9 damage
          tier3: 12 damage; [prone](../../../condition/prone.md)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Weapon
      name: People Bowling
      target: Each creature and object in the area
      type: feature
      usage: Maneuver
    - distance: Melee 1
      effects:
        - effect: The goon [slides](../../../movement/forced-movement.md) the target up to 5 squares.
          name: Effect
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Swat the Fly
      target: The triggering creature or object
      trigger: A creature or object within distance moves or [shifts](../../../movement/shifting.md) away from the goon.
      type: feature
      usage: Triggered action
    - effects:
        - effect: While [winded](../../../rule/health/winded.md), the goon has damage immunity 2.
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
    scc: mcdm.monsters.v1/monster.ogre.statblock/ogre-goon
    source: mcdm.monsters.v1
might: 2
name: Ogre Goon
organization: Elite
presence: -1
reason: -1
role: Brute
size: "2"
speed: 5
stability: 4
stamina: "100"
type: statblock
```
