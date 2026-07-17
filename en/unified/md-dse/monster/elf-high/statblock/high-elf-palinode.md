---
agility: 0
ev: "6"
file_basename: high-elf-palinode
file_dpath: monster/elf-high/statblock
free_strike: 3
immunities:
    - Psychic 5
intuition: 2
item_id: high-elf-palinode
item_name: High Elf Palinode
keywords:
    - Fey
    - High Elf
    - Humanoid
level: 1
might: 0
name: High Elf Palinode
organization: Platoon
presence: 1
reason: 0
role: Support
scc: mcdm.monsters.v1/monster.elf-high.statblock/high-elf-palinode
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "30"
type: statblock
---

```ds-sb
agility: 0
ev: "6"
features:
    - ability_type: Signature Ability
      distance: Ranged 8
      effects:
        - roll: Power Roll + 2
          tier1: 5 psychic damage
          tier2: 7 psychic damage; I < 1 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
          tier3: 9 psychic damage; I < 2 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Instill Regret
      target: One creature
      type: feature
      usage: Main action
    - distance: Ranged 5
      effects:
        - effect: '**Effect:** Each target can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to an unoccupied space [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the palinode. The palinode and each target then gain 5 temporary Stamina.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Recall
      target: Two allies
      type: feature
      usage: Maneuver
    - effects:
        - effect: At the start of each of their turns, the palinode can choose one effect on them that can be ended by a saving throw. That effect instead ends at the end of their turn.
      feature_type: trait
      icon: ⭐️
      name: Otherworldly Grace
      type: feature
free_strike: 3
immunities:
    - Psychic 5
intuition: 2
keywords:
    - Fey
    - High Elf
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.elf-high.statblock/high-elf-palinode
    source: mcdm.monsters.v1
might: 0
name: High Elf Palinode
organization: Platoon
presence: 1
reason: 0
role: Support
size: 1M
speed: 5
stability: 0
stamina: "30"
type: statblock
```
