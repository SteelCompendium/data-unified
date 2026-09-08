---
agility: 2
ev: "12"
file_basename: basilisk-tonguesnapper
file_dpath: monster/basilisk/statblock
free_strike: 4
immunities:
    - Acid 2
    - Poison 2
intuition: -1
item_id: basilisk-tonguesnapper
item_name: Basilisk Tonguesnapper
keywords:
    - Basilisk
    - Beast
level: 1
might: 1
name: Basilisk Tonguesnapper
organization: Elite
presence: -1
reason: -3
role: Hexer
scc: mcdm.monsters.v1/monster.basilisk.statblock/basilisk-tonguesnapper
size: "2"
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: "40"
type: statblock
---

```ds-sb
agility: 2
ev: "12"
features:
    - ability_type: Signature Ability
      distance: Melee 3
      effects:
        - roll: Power Roll + 2
          tier1: 8 acid damage; pull 1
          tier2: 10 acid damage; pull 2
          tier3: 14 acid damage; pull 3
        - effect: This ability can pull targets [restrained](../../../condition/restrained.md) by Petrifying Eye Beams, and ignores stability if it does so.
          name: Effect
        - cost: 3 Malice
          effect: The tonguesnapper targets two additional creatures or objects.
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Prehensile Tongue
      target: One creature or object
      type: feature
      usage: Main action
    - distance: 5 x 2 line within 1
      effects:
        - effect: The area extends from both the tonguesnapper’s eyes, and this ability targets the first creature without cover on either side of the area.
          name: Special
          roll: Power Roll + 2
          tier1: A < 0 [restrained](../../../condition/restrained.md) (save ends)
          tier2: A < 1 [restrained](../../../condition/restrained.md) (save ends)
          tier3: '[Slowed](../../../condition/slowed.md) (save ends); or if A < 2 [restrained](../../../condition/restrained.md) (save ends)'
        - effect: If a target is already [slowed](../../../condition/slowed.md), the potency increases by 1 for that target. A target [restrained](../../../condition/restrained.md) this way magically begins to turn to stone, and a target who ends two consecutive turns [restrained](../../../condition/restrained.md) this way is petrified. A target [restrained](../../../condition/restrained.md) this way or a creature adjacent to them can use a main action to cut encroaching stone from the target’s body, dealing 8 damage to the target that can’t be reduced in any way and ending this effect.
          name: Effect
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      name: Petrifying Eye Beams
      target: Special
      type: feature
      usage: Maneuver
    - cost: 2 Malice
      distance: Melee 1 or ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 8 corruption damage; R < 0 [dazed](../../../condition/dazed.md) (save ends)
          tier2: 10 corruption damage; R < 1 [dazed](../../../condition/dazed.md) (save ends)
          tier3: 14 corruption damage; R < 2 [dazed](../../../condition/dazed.md) and [slowed](../../../condition/slowed.md) (save ends)
        - effect: A creature [dazed](../../../condition/dazed.md) this way can’t benefit from [edges](../../../rule/dice/edge.md) or double [edges](../../../rule/dice/edge.md) and can’t gain or use [surges](../../../rule/resource/surge.md).
          name: Effect
      feature_type: ability
      icon: ⚔️
      keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
      name: Wink
      target: One creature
      type: feature
      usage: Main action
    - distance: 2 burst
      effects:
        - effect: Each target takes 4 acid damage. Any target who has M < 2 is also [slowed](../../../condition/slowed.md) (save ends).
          name: Effect
      feature_type: ability
      icon: ❗️
      keywords:
        - Area
      name: Neurotoxin Splash
      target: Each enemy in the area
      trigger: The tonguesnapper takes damage from a melee ability.
      type: feature
      usage: Triggered action
    - effects:
        - effect: Any creature who starts their turn adjacent to the tonguesnapper and has M < 1 is [slowed](../../../condition/slowed.md) (save ends).
      feature_type: trait
      icon: ⭐️
      name: Petrifying Fumes
      type: feature
free_strike: 4
immunities:
    - Acid 2
    - Poison 2
intuition: -1
keywords:
    - Basilisk
    - Beast
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.basilisk.statblock/basilisk-tonguesnapper
    source: mcdm.monsters.v1
might: 1
name: Basilisk Tonguesnapper
organization: Elite
presence: -1
reason: -3
role: Hexer
size: "2"
speed: 8
stability: 2
stamina: "40"
type: statblock
```
