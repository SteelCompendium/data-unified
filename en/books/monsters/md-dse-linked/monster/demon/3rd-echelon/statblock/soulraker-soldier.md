---
agility: 2
ev: 9 for four minions
file_basename: soulraker-soldier
file_dpath: monster/demon/3rd-echelon/statblock
free_strike: 4
intuition: -1
item_id: soulraker-soldier
item_name: Soulraker Soldier
keywords:
    - Abyssal
    - Demon
    - Soulraker
level: 7
might: 4
name: Soulraker Soldier
organization: Minion
presence: -1
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.demon.3rd-echelon.statblock/soulraker-soldier
size: "2"
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "13"
type: statblock
weaknesses:
    - Holy 5
with_captain: Gain an edge on strikes
---

```ds-sb
agility: 2
ev: 9 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 4
          tier1: 4 damage; push 2
          tier2: 7 damage; push 2
          tier3: 8 damage; push 4
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Chitin Bash
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Any enemy who starts their turn with two or more soulraker [minions](../../../../rule/organization/minion.md) [adjacent](../../../../rule/combat/adjacent.md) to them takes 3 sonic damage.
      feature_type: trait
      icon: ⭐️
      name: Abyssal Buzzing
      type: feature
free_strike: 4
intuition: -1
keywords:
    - Abyssal
    - Demon
    - Soulraker
level: 7
metadata:
    scc: mcdm.monsters.v1/monster.demon.3rd-echelon.statblock/soulraker-soldier
    source: mcdm.monsters.v1
might: 4
name: Soulraker Soldier
organization: Minion
presence: -1
reason: -1
role: Brute
size: "2"
speed: 6
stability: 2
stamina: "13"
type: statblock
weaknesses:
    - Holy 5
with_captain: Gain an edge on strikes
```
