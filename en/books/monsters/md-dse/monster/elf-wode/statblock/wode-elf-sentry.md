---
agility: 2
ev: "6"
file_basename: wode-elf-sentry
file_dpath: monster/elf-wode/statblock
free_strike: 3
intuition: 0
item_id: wode-elf-sentry
item_name: Wode Elf Sentry
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 1
might: 0
name: Wode Elf Sentry
organization: Platoon
presence: 1
reason: 0
role: Support
scc: mcdm.monsters.v1/monster.elf-wode.statblock/wode-elf-sentry
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "30"
type: statblock
---

```ds-sb
agility: 2
ev: "6"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 5 damage
          tier2: 7 damage
          tier3: 9 damage; the target is marked (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Tracer Longbow
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: 5 burst
      effects:
        - effect: '**Effect:** Each target takes 3 damage.'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Weapon
      name: Death Blossom
      target: Each marked enemy
      type: feature
      usage: Maneuver
    - effects:
        - effect: Abilities targeting the sentry that would take a bane from cover or concealment have a double bane instead.
      feature_type: trait
      icon: ⭐️
      name: Masking Glamor
      type: feature
free_strike: 3
intuition: 0
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.elf-wode.statblock/wode-elf-sentry
    source: mcdm.monsters.v1
might: 0
name: Wode Elf Sentry
organization: Platoon
presence: 1
reason: 0
role: Support
size: 1M
speed: 7
stability: 0
stamina: "30"
type: statblock
```
