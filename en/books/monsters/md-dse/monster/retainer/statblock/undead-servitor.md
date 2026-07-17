---
agility: -1
ev: '-'
file_basename: undead-servitor
file_dpath: monster/retainer/statblock
free_strike: 3
intuition: -1
item_id: undead-servitor
item_name: Undead Servitor
keywords:
    - Undead
    - Soulless
level: 1
might: 2
name: Undead Servitor
organization: Retainer
presence: 0
reason: -3
role: Brute
scc: mcdm.monsters.v1/monster.retainer.statblock/undead-servitor
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "21"
type: statblock
---

```ds-sb
agility: -1
ev: '-'
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 4 damage
          tier2: 7 damage
          tier3: 10 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Lurching Swipe
      target: One creature or object
      type: feature
      usage: Main action
    - effects:
        - effect: The first time in an encounter that the servitor is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) by damage that isn't fire damage or holy damage and their body isn't destroyed, they regain half their [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) maximum and fall [prone](scc.v1:mcdm.heroes.v1/condition/prone).
      feature_type: trait
      icon: ⭐️
      name: Arise
      type: feature
free_strike: 3
intuition: -1
keywords:
    - Undead
    - Soulless
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.retainer.statblock/undead-servitor
    source: mcdm.monsters.v1
might: 2
name: Undead Servitor
organization: Retainer
presence: 0
reason: -3
role: Brute
size: 1M
speed: 5
stability: 0
stamina: "21"
type: statblock
```
