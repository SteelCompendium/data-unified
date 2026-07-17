---
agility: 3
ev: "32"
file_basename: war-dog-tetrarch
file_dpath: monster/war-dog/2nd-echelon/statblock
free_strike: 7
intuition: 3
item_id: war-dog-tetrarch
item_name: War Dog Tetrarch
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 6
might: 4
name: War Dog Tetrarch
organization: Leader
presence: 4
reason: 2
scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon.statblock/war-dog-tetrarch
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 2
stamina: "180"
type: statblock
---

```ds-sb
agility: 3
ev: "32"
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 3
      effects:
        - roll: Power Roll + 4
          tier1: 11 damage
          tier2: 16 damage; taunted (EoT)
          tier3: 19 damage; taunted (EoT)
      feature_type: ability
      icon: ⚔️
      keywords:
        - Charge
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Houndblade
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 1 Malice per target
      distance: Ranged 10
      effects:
        - effect: '**Effect:** Each target [shifts](../../../../movement/shifting.md) up to their speed and can make a [free strike](../../../../feature/common/main-actions/free-strike.md). If the [free strike](../../../../feature/common/main-actions/free-strike.md) targets an enemy taunted by the tetrarch, it deals an extra 4 damage.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: Get Them, You Dolts!
      target: Three creatures
      type: feature
      usage: Maneuver
    - distance: Ranged 10
      effects:
        - effect: |-
            **Trigger:** A creature within distance who is not taunted by the tetrarch targets the tetrarch with a power roll.
            **Effect:** The power roll has a double bane. If the target obtains a tier 1 outcome, the tetrarch ignores any of the power roll's effects other than damage and the target is [frightened](../../../../condition/frightened.md) of the tetrarch (save ends).
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Sneering Disregard
      target: The triggering creature
      type: feature
      usage: Triggered action
    - effects:
        - effect: At the end of each of their turns, the tetrarch can take 10 damage to end one effect on them that can be ended by a [saving throw](../../../../rule/general/saving-throw.md). This damage can't be reduced in any way.
      feature_type: trait
      icon: ⭐️
      name: End Effect
      type: feature
    - cost: Villain Action 1
      distance: 2 burst
      effects:
        - roll: Power Roll + 4
          tier1: '[Push](../../../../movement/forced-movement.md) 2; I < 2 [frightened](../../../../condition/frightened.md) (save ends)'
          tier2: '[Push](../../../../movement/forced-movement.md) 4; I < 3 [frightened](../../../../condition/frightened.md) (save ends)'
          tier3: '[Push](../../../../movement/forced-movement.md) 5; I < 4 [frightened](../../../../condition/frightened.md) (save ends)'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: Enter the Fray
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: Five 2 cubes within 20
      effects:
        - roll: Power Roll + 4
          tier1: 7 fire damage; A < 2 [slowed](../../../../condition/slowed.md) (EoT)
          tier2: 13 fire damage; A < 3 [slowed](../../../../condition/slowed.md) (save ends)
          tier3: 16 fire damage; A < 4 [slowed](../../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Ranged
        - Weapon
      name: Lay Waste
      target: Each creature and object in the area
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: Self
      effects:
        - effect: '**Effect:** Until the end of the encounter, the tetrarch has damage immunity 2, and their Houndblade ability targets three creatures or objects.'
      feature_type: ability
      icon: ☠️
      keywords: []
      name: You Would Dare?!
      target: Self
      type: feature
      usage: '-'
free_strike: 7
intuition: 3
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 6
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon.statblock/war-dog-tetrarch
    source: mcdm.monsters.v1
might: 4
name: War Dog Tetrarch
organization: Leader
presence: 4
reason: 2
role: ""
size: 1M
speed: 7
stability: 2
stamina: "180"
type: statblock
```
