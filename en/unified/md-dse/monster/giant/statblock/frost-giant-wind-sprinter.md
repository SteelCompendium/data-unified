---
agility: 4
ev: "40"
file_basename: frost-giant-wind-sprinter
file_dpath: monster/giant/statblock
free_strike: 8
immunities:
    - Cold 8
intuition: 0
item_id: frost-giant-wind-sprinter
item_name: Frost Giant Wind Sprinter
keywords:
    - Frost Giant
    - Giant
level: 8
might: 4
name: Frost Giant Wind Sprinter
organization: Elite
presence: 0
reason: -1
role: Harrier
scc: mcdm.monsters.v1/monster.giant.statblock/frost-giant-wind-sprinter
size: "4"
source: mcdm.monsters.v1
speed: 10
stability: 5
stamina: "200"
type: statblock
---

```ds-sb
agility: 4
ev: "40"
features:
    - ability_type: Signature Ability
      distance: Melee 3
      effects:
        - roll: Power Roll + 4
          tier1: 12 damage
          tier2: 17 damage; A < 3 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
          tier3: 21 damage; A < 4 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Cold Axe
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: Self
      effects:
        - effect: '**Effect:** The wind sprinter [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed and uses Cold Axe against each enemy who comes within 2 squares of them during the move. The wind sprinter makes one power roll against all targets.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Blizzard Surge
      target: Self
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - effect: '**Effect:** The wind sprinter and the target each [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 6 squares while staying [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to each other. The target can then jump up to 5 squares and make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).'
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
      name: Ice Dance
      target: One giant ally
      type: feature
      usage: Maneuver
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** The wind sprinter takes damage.
            **Effect:** The wind sprinter moves up to their speed and uses Cold Axe against one target.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Begone, Smallfolk!
      target: Self
      type: feature
      usage: Triggered action
    - effects:
        - effect: The wind sprinter can move through enemies' spaces at their usual speed. The first time on a turn that a wind sprinter enters a creature's space, that creature can choose to fall [prone](scc.v1:mcdm.heroes.v1/condition/prone) or to take 8 damage.
      feature_type: trait
      icon: ⭐️
      name: Crush Underfoot
      type: feature
    - effects:
        - effect: The wind sprinter is surrounded by a snowstorm. Any enemy who starts their turn within 2 squares of the wind sprinter can't [shift](scc.v1:mcdm.heroes.v1/movement/shifting).
      feature_type: trait
      icon: ⭐️
      name: Kingdom of Isolation
      type: feature
free_strike: 8
immunities:
    - Cold 8
intuition: 0
keywords:
    - Frost Giant
    - Giant
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.giant.statblock/frost-giant-wind-sprinter
    source: mcdm.monsters.v1
might: 4
name: Frost Giant Wind Sprinter
organization: Elite
presence: 0
reason: -1
role: Harrier
size: "4"
speed: 10
stability: 5
stamina: "200"
type: statblock
```
