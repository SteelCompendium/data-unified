---
agility: 2
ev: "10"
file_basename: wode-elf-guerrilla
file_dpath: monster/elf-wode/statblock
free_strike: 5
intuition: 0
item_id: wode-elf-guerrilla
item_name: Wode Elf Guerrilla
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 3
might: 0
movement: Teleport
name: Wode Elf Guerrilla
organization: Platoon
presence: 1
reason: 0
role: Ambusher
scc: mcdm.monsters.v1/monster.elf-wode.statblock/wode-elf-guerrilla
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "50"
type: statblock
---

```ds-sb
agility: 2
ev: "10"
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 5
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage
          tier2: 11 damage
          tier3: 14 damage; M < 2 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      feature_type: ability
      icon: ⚔️
      keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Splinter Dagger
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Ranged 20
      effects:
        - effect: |-
            **Special:** The guerrilla must be acting as a captain.
            **Trigger:** An ally ends their turn while the guerrilla hasn't acted this round.
            **Effect:** The targets take their turn immediately. Each target gains an edge on abilities until the end of their turn.
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Do Not Hesitate in the Wode
      target: Self and each ally
      type: feature
      usage: Free triggered action
    - effects:
        - effect: The guerrilla can attempt to hide at the end of each of their turns.
      feature_type: trait
      icon: ⭐️
      name: Into the Green
      type: feature
    - effects:
        - effect: Abilities targeting the guerrilla that would take a bane from cover or concealment have a double bane instead.
      feature_type: trait
      icon: ⭐️
      name: Masking Glamor
      type: feature
free_strike: 5
intuition: 0
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.elf-wode.statblock/wode-elf-guerrilla
    source: mcdm.monsters.v1
might: 0
movement: Teleport
name: Wode Elf Guerrilla
organization: Platoon
presence: 1
reason: 0
role: Ambusher
size: 1M
speed: 7
stability: 0
stamina: "50"
type: statblock
```
