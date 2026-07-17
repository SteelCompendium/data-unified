---
agility: 1
ev: "6"
file_basename: wode-elf-green-seer
file_dpath: monster/elf-wode/statblock
free_strike: 3
intuition: 2
item_id: wode-elf-green-seer
item_name: Wode Elf Green Seer
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 1
might: 0
name: Wode Elf Green Seer
organization: Platoon
presence: 1
reason: 0
role: Hexer
scc: mcdm.monsters.v1/monster.elf-wode.statblock/wode-elf-green-seer
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "20"
type: statblock
---

```ds-sb
agility: 1
ev: "6"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 5 damage
          tier2: 7 damage; I < 1 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
          tier3: 9 damage; I < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: The Forest's Embrace
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 2 damage
          tier2: 4 damage; P < 1 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
          tier3: 6 damage; P < 1 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends); the target has a double bane on strikes (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: The Natural Cycle
      target: Two creatures
      type: feature
      usage: Maneuver
    - distance: Ranged 5
      effects:
        - effect: |-
            **Trigger:** A creature uses a triggered action targeting the green seer or an ally within distance.
            **Effect:** The green seer makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target after the target's triggered action is resolved.
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Foreseen Punishment
      target: The triggering creature
      type: feature
      usage: Free triggered action
    - effects:
        - effect: Abilities targeting the green seer that would take a bane from cover or concealment have a double bane instead.
      feature_type: trait
      icon: ⭐️
      name: Masking Glamor
      type: feature
free_strike: 3
intuition: 2
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.elf-wode.statblock/wode-elf-green-seer
    source: mcdm.monsters.v1
might: 0
name: Wode Elf Green Seer
organization: Platoon
presence: 1
reason: 0
role: Hexer
size: 1M
speed: 7
stability: 0
stamina: "20"
type: statblock
```
