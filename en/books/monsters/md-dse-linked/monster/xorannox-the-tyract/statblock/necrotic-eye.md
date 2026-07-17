---
agility: 1
ev: '-'
file_basename: necrotic-eye
file_dpath: monster/xorannox-the-tyract/statblock
free_strike: 3
intuition: 1
item_id: necrotic-eye
item_name: Necrotic Eye
keywords:
    - Eyestalk
    - Horror
    - Overmind
level: 6
might: -1
movement: Fly, hover
name: Necrotic Eye
presence: -1
reason: 4
role: Hexer
scc: mcdm.monsters.v1/monster.xorannox-the-tyract.statblock/necrotic-eye
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
      distance: Ranged 10
      effects:
        - roll: Power Roll + 4
          tier1: 11 corruption damage
          tier2: 17 corruption damage; M < 3 [bleeding](../../../condition/bleeding.md) (save ends)
          tier3: 20 corruption damage; M < 4 [bleeding](../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Psionic
        - Ranged
        - Strike
      name: Necro Beam
      target: One creature or object
      type: feature
      usage: Main action
    - effects:
        - effect: The necrotic eye has damage immunity 15. When they use a main action, they lose this immunity until the end of the round.
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
    scc: mcdm.monsters.v1/monster.xorannox-the-tyract.statblock/necrotic-eye
    source: mcdm.monsters.v1
might: -1
movement: Fly, hover
name: Necrotic Eye
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
