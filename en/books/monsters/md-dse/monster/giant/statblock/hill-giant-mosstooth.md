---
agility: -1
ev: 9 for four minions
file_basename: hill-giant-mosstooth
file_dpath: monster/giant/statblock
free_strike: 4
immunities:
    - Damage 3
intuition: -1
item_id: hill-giant-mosstooth
item_name: Hill Giant Mosstooth
keywords:
    - Giant
    - Hill Giant
level: 7
might: 4
movement: Climb
name: Hill Giant Mosstooth
organization: Minion
presence: -1
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.giant.statblock/hill-giant-mosstooth
size: "4"
source: mcdm.monsters.v1
speed: 6
stability: 5
stamina: "13"
type: statblock
with_captain: +3 damage bonus to strikes
---

```ds-sb
agility: -1
ev: 9 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 3
      effects:
        - roll: Power Roll + 4
          tier1: 4 damage
          tier2: 7 damage
          tier3: 8 damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Swing
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Whenever the mosstooth targets a creature or object with an ability, any enemy within distance of the ability can use a free triggered action to distract the mosstooth. The mosstooth targets that enemy instead.
      feature_type: trait
      icon: ⭐️
      name: Distracted
      type: feature
free_strike: 4
immunities:
    - Damage 3
intuition: -1
keywords:
    - Giant
    - Hill Giant
level: 7
metadata:
    scc: mcdm.monsters.v1/monster.giant.statblock/hill-giant-mosstooth
    source: mcdm.monsters.v1
might: 4
movement: Climb
name: Hill Giant Mosstooth
organization: Minion
presence: -1
reason: -1
role: Brute
size: "4"
speed: 6
stability: 5
stamina: "13"
type: statblock
with_captain: +3 damage bonus to strikes
```
