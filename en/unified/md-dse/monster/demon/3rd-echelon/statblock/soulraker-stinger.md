---
agility: -1
ev: 9 for four minions
file_basename: soulraker-stinger
file_dpath: monster/demon/3rd-echelon/statblock
free_strike: 4
intuition: 4
item_id: soulraker-stinger
item_name: Soulraker Stinger
keywords:
    - Abyssal
    - Demon
    - Soulraker
level: 7
might: 0
movement: Climb
name: Soulraker Stinger
organization: Minion
presence: 0
reason: 4
role: Artillery
scc: mcdm.monsters.v1/monster.demon.3rd-echelon.statblock/soulraker-stinger
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "10"
type: statblock
weaknesses:
    - Holy 5
with_captain: Gain an edge on strikes
---

```ds-sb
agility: -1
ev: 9 for four minions
features:
    - ability_type: Signature Ability
      distance: Ranged 20
      effects:
        - roll: Power Roll + 4
          tier1: 4 poison damage
          tier2: 7 poison damage
          tier3: 8 poison damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
        - Weapon
      name: Barb Launch
      target: One creature per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Any enemy who starts their turn with two or more soulraker [minions](scc.v1:mcdm.monsters.v1/rule.organization/minion) [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them takes 3 sonic damage.
      feature_type: trait
      icon: ⭐️
      name: Abyssal Buzzing
      type: feature
free_strike: 4
intuition: 4
keywords:
    - Abyssal
    - Demon
    - Soulraker
level: 7
metadata:
    scc: mcdm.monsters.v1/monster.demon.3rd-echelon.statblock/soulraker-stinger
    source: mcdm.monsters.v1
might: 0
movement: Climb
name: Soulraker Stinger
organization: Minion
presence: 0
reason: 4
role: Artillery
size: 1M
speed: 6
stability: 0
stamina: "10"
type: statblock
weaknesses:
    - Holy 5
with_captain: Gain an edge on strikes
```
