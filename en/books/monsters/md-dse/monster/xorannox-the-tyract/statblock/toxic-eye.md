---
agility: 1
ev: '-'
file_basename: toxic-eye
file_dpath: monster/xorannox-the-tyract/statblock
free_strike: 3
intuition: 1
item_id: toxic-eye
item_name: Toxic Eye
keywords:
    - Eyestalk
    - Horror
    - Overmind
level: 6
might: -1
movement: Fly, hover
name: Toxic Eye
presence: -1
reason: 4
role: Hexer
scc: mcdm.monsters.v1/monster.xorannox-the-tyract.statblock/toxic-eye
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
          tier1: 6 poison damage
          tier2: 10 poison damage; M < 3 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
          tier3: 13 poison damage; M < 4 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Psionic
        - Ranged
      name: Toxic Vapors
      target: Each enemy in the area
      type: feature
      usage: Main action
    - effects:
        - effect: The toxic eye has damage immunity 15. When they use a main action, they lose this immunity until the end of the round.
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
    scc: mcdm.monsters.v1/monster.xorannox-the-tyract.statblock/toxic-eye
    source: mcdm.monsters.v1
might: -1
movement: Fly, hover
name: Toxic Eye
organization: ""
presence: -1
reason: 4
role: Hexer
size: 1M
speed: 5
stability: 0
stamina: "30"
type: statblock
```
