---
agility: 3
ev: "48"
file_basename: soulbinder-psyche
file_dpath: monster/war-dog/4th-echelon/statblock
free_strike: 10
intuition: 4
item_id: soulbinder-psyche
item_name: Soulbinder Psyche
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 10
might: 1
movement: Fly, hover
name: Soulbinder Psyche
organization: Elite
presence: 5
reason: 3
role: Hexer
scc: mcdm.monsters.v1/monster.war-dog.4th-echelon.statblock/soulbinder-psyche
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "220"
type: statblock
---

```ds-sb
agility: 3
ev: "48"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 5
          tier1: 15 holy damage; R < 3 the target is soulbound (save ends)
          tier2: 20 holy damage; R < 4 the target is soulbound (save ends)
          tier3: 24 holy damage; R < 5 the target is soulbound (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Soulbind
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: 3 cube within 10
      effects:
        - roll: Power Roll + 5
          tier1: 8 corruption damage; P < 3 [weakened](../../../../condition/weakened.md) (EoT)
          tier2: 12 corruption damage; P < 4 [weakened](../../../../condition/weakened.md) (EoT)
          tier3: 15 corruption damage; P < 5 [weakened](../../../../condition/weakened.md) (EoT)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Soulstorm
      target: Each enemy in the area
      type: feature
      usage: Main action
    - distance: 5 burst
      effects:
        - effect: '**Effect:** Each target takes 5 damage from a self-inflicted wound, and if they have M < 4 Psyche [slides](../../../../movement/forced-movement.md) them up to 5 squares.'
      feature_type: ability
      icon: ❇️
      keywords:
        - Magic
        - Ranged
      name: Command the Awakened
      target: Each soulbound enemy in the area
      type: feature
      usage: Maneuver
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** An enemy moves within 2 squares of Psyche.
            **Effect:** Psyche moves up to 5 squares, and has damage immunity 5 and ignores [difficult terrain](../../../../movement/difficult-terrain.md) during this movement. The first time she moves through any creature during this movement, that creature takes 5 corruption damage.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Spirit Form
      target: Self
      type: feature
      usage: Triggered action
    - distance: Ranged 10
      effects:
        - effect: |-
            **Trigger:** A war dog within distance is made [winded](../../../../rule/health/winded.md) or reduced to 0 [Stamina](../../../../rule/health/stamina.md).
            **Effect:** The target loses all their [surges](../../../../rule/resource/surge.md) and takes 5 corruption damage.
            **1 [Malice](../../../../rule/monster/malice.md):** The target also takes a bane on their next strike.
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Vengeance for the Slain
      target: One enemy
      type: feature
      usage: Free triggered action
    - effects:
        - effect: When Psyche is reduced to 0 [Stamina](../../../../rule/health/stamina.md), her spirit surrounds the nearest war dog, who has damage immunity 2, deals an extra 5 damage on strikes, and can use the following Immortal Flare maneuver until the end of the encounter. That war dog also gains the Immortal Soul trait, and transfers this effect to the nearest war dog when they die.
      feature_type: trait
      icon: ⭐️
      name: Immortal Soul
      type: feature
    - distance: Ranged 10
      effects:
        - effect: '**Effect:** The target takes 10 psychic damage.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Immortal Flare
      target: One creature or object
      type: feature
      usage: Maneuver
free_strike: 10
intuition: 4
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.4th-echelon.statblock/soulbinder-psyche
    source: mcdm.monsters.v1
might: 1
movement: Fly, hover
name: Soulbinder Psyche
organization: Elite
presence: 5
reason: 3
role: Hexer
size: 1M
speed: 5
stability: 1
stamina: "220"
type: statblock
```
