---
agility: 2
ev: 6 for four minions
file_basename: ghoul-craver
file_dpath: monster/undead/2nd-echelon/statblock
free_strike: 2
immunities:
    - Corruption 4
    - poison 4
intuition: 0
item_id: ghoul-craver
item_name: Ghoul Craver
keywords:
    - Undead
level: 4
might: 3
movement: Climb
name: Ghoul Craver
organization: Minion
presence: 0
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.undead.2nd-echelon.statblock/ghoul-craver
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "8"
type: statblock
with_captain: +2 damage bonus to strikes
---

```ds-sb
agility: 2
ev: 6 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 2 damage
          tier2: 4 damage
          tier3: 6 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Taste
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Any enemy [adjacent](../../../../rule/combat/adjacent.md) to three or more ghoul cravers can't [shift](../../../../movement/shifting.md).
      feature_type: trait
      icon: ⭐️
      name: Ever So Hungry
      type: feature
    - effects:
        - effect: When the ghoul craver uses the Charge main action, they gain a +2 bonus to speed until the end of their turn.
      feature_type: trait
      icon: ⭐️
      name: Hunger
      type: feature
free_strike: 2
immunities:
    - Corruption 4
    - poison 4
intuition: 0
keywords:
    - Undead
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.undead.2nd-echelon.statblock/ghoul-craver
    source: mcdm.monsters.v1
might: 3
movement: Climb
name: Ghoul Craver
organization: Minion
presence: 0
reason: 0
role: Harrier
size: 1M
speed: 7
stability: 0
stamina: "8"
type: statblock
with_captain: +2 damage bonus to strikes
```
