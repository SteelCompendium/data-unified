---
agility: 1
ev: "20"
file_basename: lightbender
file_dpath: monster/lightbender/statblock
free_strike: 6
intuition: 1
item_id: lightbender
item_name: Lightbender
keywords:
    - Beast
    - Lightbender
level: 3
might: 2
name: Lightbender
organization: Elite
presence: -1
reason: -3
role: Ambusher
scc: mcdm.monsters.v1/monster.lightbender.statblock/lightbender
size: "2"
source: mcdm.monsters.v1
speed: 10
stability: 1
stamina: "100"
type: statblock
---

```ds-sb
agility: 1
ev: "20"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 9 damage
          tier2: 14 damage
          tier3: 18 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Flash Swipe
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 8 damage
          tier2: 12 damage; M < 1 [bleeding](../../../condition/bleeding.md) (save ends)
          tier3: 15 damage; M < 2 [bleeding](../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Piercing Tails
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: 3 burst
      effects:
        - roll: Power Roll + 2
          tier1: I < 0 [dazed](../../../condition/dazed.md) (save ends)
          tier2: I < 1 [dazed](../../../condition/dazed.md) (save ends)
          tier3: I < 2 [dazed](../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Hypnotic Mane
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** The lightbender takes damage from a strike.
            **Effect:** The lightbender halves the damage, ignores any nondamaging effects associated with it, and can [teleport](../../../movement/teleport.md) up to 5 squares. If they [teleport](../../../movement/teleport.md) into concealment or cover, the lightbender can immediately attempt to hide as a free maneuver.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
      name: Stalker's Afterimage
      target: Self
      type: feature
      usage: Triggered action
    - effects:
        - effect: Any effect on the lightbender that would be ended by a [saving throw](../../../rule/general/saving-throw.md) instead ends automatically at the end of their next turn.
      feature_type: trait
      icon: ⭐️
      name: Avoidance
      type: feature
free_strike: 6
intuition: 1
keywords:
    - Beast
    - Lightbender
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.lightbender.statblock/lightbender
    source: mcdm.monsters.v1
might: 2
name: Lightbender
organization: Elite
presence: -1
reason: -3
role: Ambusher
size: "2"
speed: 10
stability: 1
stamina: "100"
type: statblock
```
