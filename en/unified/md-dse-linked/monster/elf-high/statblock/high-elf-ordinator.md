---
agility: 2
ev: "20"
file_basename: high-elf-ordinator
file_dpath: monster/elf-high/statblock
free_strike: 5
intuition: 2
item_id: high-elf-ordinator
item_name: High Elf Ordinator
keywords:
    - Fey
    - High Elf
    - Humanoid
level: 3
might: 0
movement: Fly
name: High Elf Ordinator
organization: Leader
presence: 3
reason: 3
scc: mcdm.monsters.v1/monster.elf-high.statblock/high-elf-ordinator
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "120"
type: statblock
---

```ds-sb
agility: 2
ev: "20"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 3
          tier1: 9 lightning damage; R < 1 [dazed](../../../condition/dazed.md) (save ends)
          tier2: 14 lightning damage; R < 2 [dazed](../../../condition/dazed.md) (save ends)
          tier3: 17 lightning damage; R < 3 [dazed](../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Lightning Rod
      target: One creature or object
      type: feature
      usage: Main action
    - distance: 10 burst
      effects:
        - effect: '**Effect:** Each target can move up to their speed or make a [free strike](../../../feature/common/main-actions/free-strike.md). Elemental mote targets can, instead, use their Spark of Life trait.'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Elemental Uproar
      target: Each elemental ally in the area
      type: feature
      usage: Maneuver
    - cost: 2 Malice
      distance: Ranged 10
      effects:
        - effect: |-
            **Effect:** The ordinator summons four elemental motes or four soot crows into unoccupied space within distance.
            **3 [Malice](../../../rule/monster/malice.md):** The ordinator instead summons one ceramic horse or one winded brambleguard into an unoccupied space within distance.
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: Summon Elemental
      target: Special
      type: feature
      usage: Maneuver
    - distance: Ranged 10
      effects:
        - effect: |-
            **Trigger:** An enemy within distance uses an ability against the ordinator or any ally within distance.
            **Effect:** The ordinator uses Lightning Rod against the target after the ability is resolved.
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Enough!
      target: The triggering enemy
      type: feature
      usage: Triggered action
    - effects:
        - effect: At the start of each of their turns, the ordinator can choose one or more effects on them that can be ended by a saving throw. The effects instead end at the end of the ordinator's turn.
      feature_type: trait
      icon: ⭐️
      name: Otherworldly Blessing
      type: feature
    - cost: Villain Action 1
      distance: 10 burst
      effects:
        - effect: '**Effect:** Each target glows briefly, and can end one effect on themself then move up to their speed.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Fountains Roar, Now Free From the Earth
      target: Each ally in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: 5 cube within 10
      effects:
        - roll: ""
          tier1: 12 corruption damage; pull 5 toward the center of the cube
          tier2: 9 corruption damage; pull 3 toward the center of the cube
          tier3: Pull 1 toward the center of the cube
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
        - Ranged
      name: And the Sun Forsook Her Children
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 10 burst
      effects:
        - effect: '**Effect:** Each target''s free strike now has the Magic keyword and can target two creatures or objects. Additionally, each target glows with magic.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: But We Will Change Her Mind
      target: Self and each ally in the area
      type: feature
      usage: '-'
free_strike: 5
intuition: 2
keywords:
    - Fey
    - High Elf
    - Humanoid
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.elf-high.statblock/high-elf-ordinator
    source: mcdm.monsters.v1
might: 0
movement: Fly
name: High Elf Ordinator
organization: Leader
presence: 3
reason: 3
role: ""
size: 1M
speed: 5
stability: 0
stamina: "120"
type: statblock
```
