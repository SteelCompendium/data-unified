---
agility: 2
ev: "44"
file_basename: fire-giant-lightbearer
file_dpath: monster/giant/statblock
free_strike: 9
immunities:
    - Fire 9
intuition: 4
item_id: fire-giant-lightbearer
item_name: Fire Giant Lightbearer
keywords:
    - Fire Giant
    - Giant
level: 9
might: 4
name: Fire Giant Lightbearer
organization: Elite
presence: 1
reason: 0
role: Support
scc: mcdm.monsters.v1/monster.giant.statblock/fire-giant-lightbearer
size: "4"
source: mcdm.monsters.v1
speed: 8
stability: 5
stamina: "200"
type: statblock
---

```ds-sb
agility: 2
ev: "44"
features:
    - ability_type: Signature Ability
      distance: Melee 6
      effects:
        - roll: Power Roll + 4
          tier1: 13 fire damage; slide 2
          tier2: 17 fire damage; slide 4
          tier3: 22 fire damage; slide 6
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Magic
        - Melee
        - Strike
      name: Flamelash
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Ranged 6
      effects:
        - roll: Power Roll + 4
          tier1: 15 fire damage
          tier2: 21 fire damage
          tier3: 26 fire damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Living Blaze
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Ranged 5
      effects:
        - effect: '**Effect:** The lightbearer can target themself with this ability. Each target takes 1d6 fire damage and [teleports](../../../movement/teleport.md) in a plume of smoke to swap places with the other target.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Travel By Fire
      target: Two creatures or objects
      type: feature
      usage: Maneuver
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** The lightbearer takes damage.
            **Effect:** The lightbearer emits a beacon of light until the start of their next turn. Each fire giant who has line of effect to the lightbearer has a double edge on abilities.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Emergency Beacon
      target: Self
      type: feature
      usage: Triggered action
    - effects:
        - effect: Any fire giant targeted by the lightbearer's damage-dealing abilities ignores the damage and instead regains [Stamina](../../../rule/health/stamina.md) equal to the damage that would have been dealt. If the lightbearer moves a fire giant using an ability, they can choose to ignore [stability](../../../rule/character/stability.md).
      feature_type: trait
      icon: ⭐️
      name: Healing Heat
      type: feature
    - effects:
        - effect: Whenever an [adjacent](../../../rule/combat/adjacent.md) enemy [grabs](../../../condition/grabbed.md) the lightbearer or uses a melee ability against them, that enemy takes 5 fire damage.
      feature_type: trait
      icon: ⭐️
      name: Searing Skin
      type: feature
free_strike: 9
immunities:
    - Fire 9
intuition: 4
keywords:
    - Fire Giant
    - Giant
level: 9
metadata:
    scc: mcdm.monsters.v1/monster.giant.statblock/fire-giant-lightbearer
    source: mcdm.monsters.v1
might: 4
name: Fire Giant Lightbearer
organization: Elite
presence: 1
reason: 0
role: Support
size: "4"
speed: 8
stability: 5
stamina: "200"
type: statblock
```
