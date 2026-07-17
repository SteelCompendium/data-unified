---
agility: 2
ev: "3"
file_basename: ghoul
file_dpath: monster/undead/1st-echelon/statblock
free_strike: 1
immunities:
    - Corruption 1
    - poison 1
intuition: 0
item_id: ghoul
item_name: Ghoul
keywords:
    - Undead
level: 1
might: 0
name: Ghoul
organization: Horde
presence: -1
reason: -2
role: Harrier
scc: mcdm.monsters.v1/monster.undead.1st-echelon.statblock/ghoul
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "15"
type: statblock
---

```ds-sb
agility: 2
ev: "3"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 3 damage
          tier2: 4 damage
          tier3: 5 damage; M < 2 [bleeding](../../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Razor Claws
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** The ghoul jumps up to 3 squares. If they land on a size 1 enemy, that enemy is knocked [prone](../../../../condition/prone.md) and the ghoul can make a [free strike](../../../../feature/common/main-actions/free-strike.md) against them.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Leap
      target: Self
      type: feature
      usage: Maneuver
    - effects:
        - effect: The first time the ghoul is reduced to 0 [Stamina](../../../../rule/health/stamina.md) by damage that isn't fire damage or holy damage and their body isn't destroyed, they instead have 1 [Stamina](../../../../rule/health/stamina.md) and fall [prone](../../../../condition/prone.md).
      feature_type: trait
      icon: ⭐️
      name: Arise
      type: feature
    - effects:
        - effect: When the ghoul uses the Charge main action, they gain a +2 bonus to speed until the end of their turn.
      feature_type: trait
      icon: ⭐️
      name: Hunger
      type: feature
free_strike: 1
immunities:
    - Corruption 1
    - poison 1
intuition: 0
keywords:
    - Undead
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.undead.1st-echelon.statblock/ghoul
    source: mcdm.monsters.v1
might: 0
name: Ghoul
organization: Horde
presence: -1
reason: -2
role: Harrier
size: 1M
speed: 7
stability: 0
stamina: "15"
type: statblock
```
