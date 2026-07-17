---
agility: -1
ev: "44"
file_basename: soulraker-hivequeen
file_dpath: monster/demon/3rd-echelon/statblock
free_strike: 9
intuition: 3
item_id: soulraker-hivequeen
item_name: Soulraker Hivequeen
keywords:
    - Abyssal
    - Demon
    - Soulraker
level: 9
might: 5
movement: Fly
name: Soulraker Hivequeen
organization: Leader
presence: 2
reason: 3
scc: mcdm.monsters.v1/monster.demon.3rd-echelon.statblock/soulraker-hivequeen
size: "5"
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "240"
type: statblock
weaknesses:
    - Holy 5
---

```ds-sb
agility: -1
ev: "44"
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 10
      effects:
        - roll: Power Roll + 5
          tier1: 14 poison damage; M < 3 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
          tier2: 19 poison damage; M < 4 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
          tier3: 23 poison damage; M < 5 the target is implanted
      feature_type: ability
      icon: ⚔️
      keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
      name: Stinging Ovipositor
      target: Two creatures
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 10 burst
      effects:
        - effect: '**Effect:** The hivequeen lets loose a subsonic call to each target, forcing them to immediately emerge from their host''s body as a mature soulraker handmaiden and make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Forced Gestation
      target: Each implanted handmaiden parasite in the area
      type: feature
      usage: Maneuver
    - cost: 2 Malice
      distance: 5 burst
      effects:
        - effect: |-
            **Trigger:** The hivequeen is targeted by a strike for the second time on an attacker's turn, whether by the attacker or another creature acting on the attacker's turn.
            **Effect:** Two soulraker [minions](scc.v1:mcdm.monsters.v1/rule.organization/minion) appear within distance.
            **2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** A soulraker praetorian also appears within distance.
      feature_type: ability
      icon: ❗️
      keywords:
        - Area
      name: For the Queen!
      target: Special
      type: feature
      usage: Triggered action
    - effects:
        - effect: At the end of their turn, the hivequeen can consume an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) soulraker demon to end one effect on them that can be ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) (no action required).
      feature_type: trait
      icon: ⭐️
      name: Cannibal Queen
      type: feature
    - effects:
        - effect: Any creature within 2 squares of a soulraker demon within 100 miles of the hivequeen can't be hidden from the hivequeen. The hivequeen has [line of effect](scc.v1:mcdm.heroes.v1/rule.combat/line-of-effect) to such creatures.
      feature_type: trait
      icon: ⭐️
      name: Hive Soulsight
      type: feature
    - cost: Villain Action 1
      distance: 10 burst
      effects:
        - effect: '**Effect:** Each target can move their speed and make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike). If no [minions](scc.v1:mcdm.monsters.v1/rule.organization/minion) are present, four soulraker [minions](scc.v1:mcdm.monsters.v1/rule.organization/minion) are summoned into unoccupied spaces within distance before the hivequeen uses this [villain action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action).'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: Kicking the Nest
      target: Each soulraker minion in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: 5 burst
      effects:
        - roll: Power Roll + 5
          tier1: Push 3; I < 3 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
          tier2: Push 3; I < 4 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
          tier3: 11 sonic damage; push 3; I < 5 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: Buzz Off!
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: Four 2 cubes within 10
      effects:
        - roll: Power Roll + 4
          tier1: 7 poison damage; M < 3 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
          tier2: 11 poison damage; M < 4 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
          tier3: 14 poison damage; M < 5 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
        - Ranged
      name: Bomber Wasp Warfare
      target: Each enemy in the area
      type: feature
      usage: '-'
free_strike: 9
intuition: 3
keywords:
    - Abyssal
    - Demon
    - Soulraker
level: 9
metadata:
    scc: mcdm.monsters.v1/monster.demon.3rd-echelon.statblock/soulraker-hivequeen
    source: mcdm.monsters.v1
might: 5
movement: Fly
name: Soulraker Hivequeen
organization: Leader
presence: 2
reason: 3
role: ""
size: "5"
speed: 6
stability: 2
stamina: "240"
type: statblock
weaknesses:
    - Holy 5
```
