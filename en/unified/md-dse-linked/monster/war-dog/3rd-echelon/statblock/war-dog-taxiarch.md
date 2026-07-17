---
agility: 3
ev: "44"
file_basename: war-dog-taxiarch
file_dpath: monster/war-dog/3rd-echelon/statblock
free_strike: 9
intuition: 4
item_id: war-dog-taxiarch
item_name: War Dog Taxiarch
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 9
might: 1
movement: Teleport
name: War Dog Taxiarch
organization: Leader
presence: 3
reason: 5
scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-taxiarch
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 1
stamina: "240"
type: statblock
---

```ds-sb
agility: 3
ev: "44"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 5
          tier1: 14 lightning damage; the lightning spreads 1 square; I < 3 [dazed](../../../../condition/dazed.md) (save ends)
          tier2: 19 lightning damage; the lightning spreads 2 squares; I < 4 [dazed](../../../../condition/dazed.md) (save ends)
          tier3: 23 lightning damage; the lightning spreads 3 squares; I < 5 [dazed](../../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Stunning Surge
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: 4 cube within 10
      effects:
        - effect: '**Effect:** Each target [shifts](../../../../movement/shifting.md) up to their speed and can make a [free strike](../../../../feature/common/main-actions/free-strike.md) that deals an extra 5 lightning damage.'
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Overcharge
      target: Each war dog in the area
      type: feature
      usage: Maneuver
    - distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** An enemy within distance deals damage to the taxiarch.
            **Effect:** After the ability is resolved, the target is [teleported](../../../../movement/teleport.md) up to 5 squares and is thunderstruck (save ends). A thunderstruck creature has lightning weakness 5, and the taxiarch gains an edge on power rolls against them.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Melee
      name: Thunderstruck
      target: The triggering enemy
      type: feature
      usage: Triggered action
    - effects:
        - effect: At the end of each of their turns, the taxiarch can take 15 damage to end one effect on them that can be ended by a [saving throw](../../../../rule/general/saving-throw.md). This damage can't be reduced in any way.
      feature_type: trait
      icon: ⭐️
      name: End Effect
      type: feature
    - cost: Villain Action 1
      distance: 10 burst
      effects:
        - effect: '**Effect:** [Slide](../../../../movement/forced-movement.md) 5, and if the the target has M < 4, they fall [prone](../../../../condition/prone.md).'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Magnetic Trickery
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: 5 burst
      effects:
        - effect: '**Effect:** Each target [shifts](../../../../movement/shifting.md) up to their speed, then can make a [free strike](../../../../feature/common/main-actions/free-strike.md) or use a maneuver.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Conductor of Combat
      target: Each war dog in the area
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 3 burst
      effects:
        - roll: ""
          tier1: 18 lightning damage; the target is thunderstruck (save ends)
          tier2: 14 lightning damage; the target is thunderstruck (EoT)
          tier3: 9 lightning damage
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Unlimited Power!
      target: Each creature in the area
      type: feature
      usage: '-'
free_strike: 9
intuition: 4
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 9
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-taxiarch
    source: mcdm.monsters.v1
might: 1
movement: Teleport
name: War Dog Taxiarch
organization: Leader
presence: 3
reason: 5
role: ""
size: 1M
speed: 7
stability: 1
stamina: "240"
type: statblock
```
