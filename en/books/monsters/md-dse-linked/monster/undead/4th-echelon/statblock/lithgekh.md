---
agility: 1
ev: "12"
file_basename: lithgekh
file_dpath: monster/undead/4th-echelon/statblock
free_strike: 5
immunities:
    - Corruption 10
    - poison 10
intuition: 3
item_id: lithgekh
item_name: Lithgekh
keywords:
    - Undead
    - Soulless
level: 10
might: 0
movement: Fly, hover
name: Lithgekh
organization: Horde
presence: -1
reason: 5
role: Hexer
scc: mcdm.monsters.v1/monster.undead.4th-echelon.statblock/lithgekh
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 1
stamina: "55"
type: statblock
---

```ds-sb
agility: 1
ev: "12"
features:
    - ability_type: Signature Ability
      distance: Ranged 15
      effects:
        - roll: Power Roll + 5
          tier1: 9 corruption damage; I < 3 [frightened](../../../../condition/frightened.md) (save ends)
          tier2: 12 corruption damage; I < 4 [frightened](../../../../condition/frightened.md) (save ends)
          tier3: 14 corruption damage; I < 5 [frightened](../../../../condition/frightened.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Heartstopper
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 1 Malice
      distance: Ranged 20
      effects:
        - effect: |-
            **Trigger:** A creature within distance uses a magic ability.
            **Effect:** Any damage dealt by or [Stamina](../../../../rule/health/stamina.md) regained from the ability is halved. The lithgekh regains [Stamina](../../../../rule/health/stamina.md) equal to the remaining damage dealt or [Stamina](../../../../rule/health/stamina.md) gained.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Ranged
      name: Mystic Battery
      target: The triggering creature
      type: feature
      usage: Free triggered action
    - effects:
        - effect: Each ally within 10 squares of the lithgekh gains an [edge](../../../../rule/dice/edge.md) on magic abilities.
      feature_type: trait
      icon: ⭐️
      name: Devour Magic
      type: feature
free_strike: 5
immunities:
    - Corruption 10
    - poison 10
intuition: 3
keywords:
    - Undead
    - Soulless
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.undead.4th-echelon.statblock/lithgekh
    source: mcdm.monsters.v1
might: 0
movement: Fly, hover
name: Lithgekh
organization: Horde
presence: -1
reason: 5
role: Hexer
size: 1M
speed: 6
stability: 1
stamina: "55"
type: statblock
```
