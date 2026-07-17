---
agility: 2
ev: "20"
file_basename: chorogaunt
file_dpath: monster/demon/1st-echelon/statblock
free_strike: 5
intuition: 2
item_id: chorogaunt
item_name: Chorogaunt
keywords:
    - Abyssal
    - Demon
level: 3
might: 2
name: Chorogaunt
organization: Leader
presence: 3
reason: 2
scc: mcdm.monsters.v1/monster.demon.1st-echelon.statblock/chorogaunt
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "120"
type: statblock
weaknesses:
    - Holy 5
---

```ds-sb
agility: 2
ev: "20"
features:
    - ability_type: Signature Ability
      distance: 5 burst
      effects:
        - roll: Power Roll + 3
          tier1: 4 psychic damage; I < 1 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
          tier2: 7 psychic damage; I < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
          tier3: 10 psychic damage; I < 3 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Weapon
      name: Agonizing Harmony
      target: Each enemy in the area
      type: feature
      usage: Main action
    - distance: 10 burst
      effects:
        - effect: '**Effect:** The chorogaunt slides each target up to 3 squares, ignoring [stability](scc.v1:mcdm.heroes.v1/rule.character/stability).'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Chaotic Entrancing Harmony
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - cost: 3 Malice
      distance: Self
      effects:
        - effect: |-
            **Trigger:** The chorogaunt is targeted by a strike.
            **Effect:** Any damage from the strike is halved, and the chorogaunt's abilities deal an extra 3 damage until the end of their next turn.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
      name: I Thrive on Pain
      target: Self
      type: feature
      usage: Triggered action
    - effects:
        - effect: At the end of each of their turns, the chorogaunt can take 5 damage to end one effect on them that can be ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw). This damage can't be reduced in any way.
      feature_type: trait
      icon: ⭐️
      name: End Effect
      type: feature
    - effects:
        - effect: While the chorogaunt is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), they gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on strikes, and any strike made against them gains an edge.
      feature_type: trait
      icon: ⭐️
      name: Lethe
      type: feature
    - effects:
        - effect: Any creature within 2 squares of the chorogaunt can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
    - cost: Villain Action 1
      distance: Ranged 10
      effects:
        - effect: '**Effect:** Each target must choose between taking 5 psychic damage, or being [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends).'
      feature_type: ability
      icon: ☠️
      keywords:
        - Ranged
      name: Frightening Tones
      target: Three enemies
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: Ranged 10
      effects:
        - effect: '**Effect:** The chorogaunt kills the target, and each other ally in the encounter deals an extra 3 damage with strikes until the end of the round. The Director gains [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) equal to the number of heroes in the encounter.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Magic
        - Ranged
      name: Bully the Weak
      target: One ally
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: Self
      effects:
        - effect: '**Effect:** The chorogaunt [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed, uses Agonizing Harmony, [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed, and then uses Agonizing Harmony again.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Magic
      name: Running Cacophony
      target: Self
      type: feature
      usage: '-'
free_strike: 5
intuition: 2
keywords:
    - Abyssal
    - Demon
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.demon.1st-echelon.statblock/chorogaunt
    source: mcdm.monsters.v1
might: 2
name: Chorogaunt
organization: Leader
presence: 3
reason: 2
role: ""
size: 1L
speed: 5
stability: 2
stamina: "120"
type: statblock
weaknesses:
    - Holy 5
```
