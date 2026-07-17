---
agility: 4
ev: "72"
file_basename: gloom-dragon
file_dpath: monster/dragon/statblock
free_strike: 6
immunities:
    - Psychic 5
intuition: 3
item_id: gloom-dragon
item_name: Gloom Dragon
keywords:
    - Dragon
    - Elemental
level: 4
might: 2
movement: Fly, hover
name: Gloom Dragon
organization: Solo
presence: 4
reason: 1
scc: mcdm.monsters.v1/monster.dragon.statblock/gloom-dragon
size: "4"
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: "350"
type: statblock
---

```ds-sb
agility: 4
ev: "72"
features:
    - effects:
        - effect: |-
            **[End Effect](../../../rule/monster/end-effect.md):** At the end of each of their turns, the dragon can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
            **Solo Turns:** The dragon can take two turns each round. They can't take turns consecutively.
      feature_type: trait
      icon: ☠️
      name: Solo Monster
      type: feature
    - effects:
        - effect: The dragon's scales create a 3 aura of dark supernatural fog around them that feeds on their victims' fears and provides concealment to the dragon only. Each enemy who starts their turn in the area takes 2 psychic damage. Additionally, whenever one or more enemies is in the area, the dragon's abilities deal an extra 3 psychic damage.
      feature_type: trait
      icon: ❇️
      name: Gloaming Wyrmscale Aura
      type: feature
    - ability_type: Signature Ability
      distance: 4 cube within 10
      effects:
        - roll: ""
          tier1: 14 cold damage; the target is dragonsealed (save ends)
          tier2: 11 cold damage; the target is dragonsealed (save ends)
          tier3: 6 cold damage
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Breath of Brume
      target: Each enemy and object in the area
      type: feature
      usage: Main action
    - distance: Melee 3
      effects:
        - roll: Power Roll + 4
          tier1: 10 psychic damage; pull 2
          tier2: 15 psychic damage; pull 4
          tier3: 18 psychic damage; pull 6
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Magic
        - Melee
        - Strike
      name: Phantom Tail Swing
      target: Two creatures or objects
      type: feature
      usage: Main action
    - effects:
        - effect: Once per turn, the dragon can [shift](../../../movement/shifting.md) up to their speed, leaving behind a 4 cube area of magical darkness in their starting space that lasts until the end of the encounter. The dragon ignores concealment created by this darkness. Any enemy who ends their turn in the area and has I < 3 is [frightened](../../../condition/frightened.md) of the dragon until the end of their next turn.
      feature_type: trait
      icon: ⭐️
      name: Shadow Skulk
      type: feature
    - cost: 5 Malice
      distance: 10 burst
      effects:
        - effect: '**Effect:** Each target must be dragonsealed. Each target takes 3 psychic damage, and if they have I < 3 they immediately make a [free strike](../../../feature/common/main-actions/free-strike.md) against one ally of the dragon''s choice.'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Visions in the Dark
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: Self
      effects:
        - effect: |-
            **Trigger:** A creature within 10 squares moves.
            **Effect:** The dragon moves two existing cubes of magical darkness they created up to 10 squares each.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Encroaching Darkness
      target: Self
      type: feature
      usage: Free triggered action
    - cost: Villain Action 1
      distance: 5 burst
      effects:
        - roll: Power Roll + 4
          tier1: Pull 2; I < 2 [frightened](../../../condition/frightened.md) (EoT)
          tier2: Pull 4; I < 3 [frightened](../../../condition/frightened.md) (save ends)
          tier3: Pull 6; I < 4 [frightened](../../../condition/frightened.md) (save ends)
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Enveloping Umbrage
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: 10 burst
      effects:
        - roll: Power Roll + 4
          tier1: 6 psychic damage
          tier2: 11 psychic damage
          tier3: 14 psychic damage
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Pall of Nightmares
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: Special
      effects:
        - effect: '**Effect:** The dragon disappears from the encounter map. The dragon and three hallucinatory illusions of themself then immediately reappear in unoccupied spaces on the encounter map, and the dragon and each illusion uses Breath of Brume. Each illusion is indistinguishable from the dragon except by supernatural means, has 1 [Stamina](../../../rule/health/stamina.md), and has the dragon''s speed. An illusion acts on the dragon''s turns but can take only move actions. Once per round before or after using an ability, the dragon can trade places with any duplicate.'
      feature_type: ability
      icon: ☠️
      keywords: []
      name: Absence of All Light
      target: Special
      type: feature
      usage: '-'
free_strike: 6
immunities:
    - Psychic 5
intuition: 3
keywords:
    - Dragon
    - Elemental
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.dragon.statblock/gloom-dragon
    source: mcdm.monsters.v1
might: 2
movement: Fly, hover
name: Gloom Dragon
organization: Solo
presence: 4
reason: 1
role: ""
size: "4"
speed: 8
stability: 2
stamina: "350"
type: statblock
```
