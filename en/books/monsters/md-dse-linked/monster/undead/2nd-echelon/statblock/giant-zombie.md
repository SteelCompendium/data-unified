---
agility: -1
ev: "24"
file_basename: giant-zombie
file_dpath: monster/undead/2nd-echelon/statblock
free_strike: 6
immunities:
    - Corruption 4
    - poison 4
intuition: 1
item_id: giant-zombie
item_name: Giant Zombie
keywords:
    - Undead
    - Soulless
level: 4
might: 3
name: Giant Zombie
organization: Elite
presence: 2
reason: -2
role: Brute
scc: mcdm.monsters.v1/monster.undead.2nd-echelon.statblock/giant-zombie
size: "3"
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "140"
type: statblock
---

```ds-sb
agility: -1
ev: "24"
features:
    - ability_type: Signature Ability
      distance: Melee 3
      effects:
        - roll: Power Roll + 3
          tier1: 9 damage
          tier2: 14 damage; A < 2 [grabbed](../../../../condition/grabbed.md)
          tier3: 17 damage; A < 3 [grabbed](../../../../condition/grabbed.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Rotten Smash
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 1 Malice
      distance: Self
      effects:
        - effect: |-
            **Trigger:** The giant zombie [grabs](../../../../condition/grabbed.md) two creatures or objects, or starts their turn with two creatures or objects [grabbed](../../../../condition/grabbed.md).
            **Effect:** The creatures or objects are smashed together using Rotten Smash, which has a double edge.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Knocking Heads
      target: Self; see below
      type: feature
      usage: Triggered action
    - effects:
        - effect: The first time the giant zombie is reduced to 0 [Stamina](../../../../rule/health/stamina.md) by damage that isn't fire damage or holy damage and their body isn't destroyed, they instead have 50 [Stamina](../../../../rule/health/stamina.md) and fall [prone](../../../../condition/prone.md).
      feature_type: trait
      icon: ⭐️
      name: Endless Knight
      type: feature
    - effects:
        - effect: When the giant zombie is targeted by an ability that deals rolled damage, they halve the damage from a tier 1 outcome.
      feature_type: trait
      icon: ⭐️
      name: Negative Nerves
      type: feature
free_strike: 6
immunities:
    - Corruption 4
    - poison 4
intuition: 1
keywords:
    - Undead
    - Soulless
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.undead.2nd-echelon.statblock/giant-zombie
    source: mcdm.monsters.v1
might: 3
name: Giant Zombie
organization: Elite
presence: 2
reason: -2
role: Brute
size: "3"
speed: 6
stability: 2
stamina: "140"
type: statblock
```
