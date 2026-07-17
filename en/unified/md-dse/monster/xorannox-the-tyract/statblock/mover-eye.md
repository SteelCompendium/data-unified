---
agility: 1
ev: '-'
file_basename: mover-eye
file_dpath: monster/xorannox-the-tyract/statblock
free_strike: 3
intuition: 1
item_id: mover-eye
item_name: Mover Eye
keywords:
    - Eyestalk
    - Horror
    - Overmind
level: 6
might: -1
movement: Fly, hover
name: Mover Eye
presence: -1
reason: 4
role: Controller
scc: mcdm.monsters.v1/monster.xorannox-the-tyract.statblock/mover-eye
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "30"
type: statblock
---

```ds-sb
agility: 1
ev: '-'
features:
    - ability_type: Signature Ability
      distance: Ranged 6
      effects:
        - roll: Power Roll + 4
          tier1: 11 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
          tier2: 17 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
          tier3: 20 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Psionic
        - Ranged
        - Strike
      name: Telekinetic Beam
      target: Two creatures or objects
      type: feature
      usage: Main action
    - effects:
        - effect: The mover eye has damage immunity 15. When they use a main action, they lose this immunity until the end of the round.
      feature_type: trait
      icon: ⭐️
      name: Psionic Barrier
      type: feature
free_strike: 3
intuition: 1
keywords:
    - Eyestalk
    - Horror
    - Overmind
level: 6
metadata:
    scc: mcdm.monsters.v1/monster.xorannox-the-tyract.statblock/mover-eye
    source: mcdm.monsters.v1
might: -1
movement: Fly, hover
name: Mover Eye
organization: ""
presence: -1
reason: 4
role: Controller
size: 1M
speed: 5
stability: 0
stamina: "30"
type: statblock
```
