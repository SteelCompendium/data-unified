---
agility: 1
ev: '-'
file_basename: demolition
file_dpath: monster/xorannox-the-tyract/statblock
free_strike: 3
intuition: 1
item_id: demolition
item_name: Demolition
keywords:
    - Eyestalk
    - Horror
    - Overmind
level: 6
might: -1
movement: Fly, hover
name: Demolition
presence: -1
reason: 4
role: Artillery
scc: mcdm.monsters.v1/monster.xorannox-the-tyract.statblock/demolition
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
      distance: 4 cube within 10
      effects:
        - roll: Power Roll + 4
          tier1: 6 fire damage
          tier2: 10 fire damage; M < 3 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
          tier3: 13 fire damage; M < 4 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Psionic
        - Ranged
        - Strike
      name: Explosion
      target: Each enemy in the area
      type: feature
      usage: Main action
    - effects:
        - effect: The demolition eye has damage immunity 15. When they use a main action, they lose this immunity until the end of the round.
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
    scc: mcdm.monsters.v1/monster.xorannox-the-tyract.statblock/demolition
    source: mcdm.monsters.v1
might: -1
movement: Fly, hover
name: Demolition
organization: ""
presence: -1
reason: 4
role: Artillery
size: 1M
speed: 5
stability: 0
stamina: "30"
type: statblock
```
