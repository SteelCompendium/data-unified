---
agility: 0
file_basename: devil-detective
file_dpath: monster/retainer/statblock
free_strike: 2
immunities:
    - Fire 2
intuition: 2
item_id: devil-detective
item_name: Devil Detective
keywords:
    - Devil
    - Infernal
level: 1
might: -1
movement: —
name: Devil Detective
organization: Retainer
presence: 0
reason: 2
role: Controller
scc: mcdm.summoner.v1/monster.retainer.statblock/devil-detective
size: 1M
source: mcdm.summoner.v1
speed: 5
stability: 0
stamina: "21"
type: statblock
weaknesses: []
---

```ds-sb
agility: 0
ev: ""
features:
    - effects:
        - effect: |-
            The detective can command up to two squads of minions with a maximum of 4 minions per squad. They can only have one squad of [signature minions](../../../feature/summoner/level-1/minions.md) active at any time.
            At the start of each of the detective's turns, up to three **razors** appear in unoccupied spaces within 5 squares of the detective. On each of the detective's turns, they direct the squad of razors to move and use a main action.
      feature_type: trait
      icon: ⭐️
      name: Demon Summoner
      type: feature
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: 2d10 + highest characteristic
          tier1: 1 damage
          tier2: 3 damage
          tier3: 5 damage; R < STRONG [slowed](../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Diabolic Probe
      target: One creature or object
      type: feature
      usage: Main action
    - effects:
        - effect: If a creature within 10 squares speaks the detective's true name, the detective loses their [damage immunities](../../../rule/damage/damage-immunity.md) and can't summon any **razors** until the end of the encounter.
      feature_type: trait
      icon: ⭐️
      name: True Name
      type: feature
free_strike: 2
immunities:
    - Fire 2
intuition: 2
keywords:
    - Devil
    - Infernal
level: 1
metadata:
    scc: mcdm.summoner.v1/monster.retainer.statblock/devil-detective
    source: mcdm.summoner.v1
might: -1
movement: —
name: Devil Detective
organization: Retainer
presence: 0
reason: 2
role: Controller
size: 1M
speed: 5
stability: 0
stamina: "21"
type: statblock
weaknesses: []
```
