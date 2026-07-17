---
agility: 2
ev: 3 for four minions
file_basename: crawling-claw
file_dpath: monster/undead/1st-echelon/statblock
free_strike: 1
immunities:
    - Corruption 1
    - poison 1
intuition: -1
item_id: crawling-claw
item_name: Crawling Claw
keywords:
    - Undead
    - Soulless
level: 1
might: 0
movement: Climb
name: Crawling Claw
organization: Minion
presence: -1
reason: -5
role: Harrier
scc: mcdm.monsters.v1/monster.undead.1st-echelon.statblock/crawling-claw
size: 1T
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "4"
type: statblock
with_captain: +2 bonus to speed
---

```ds-sb
agility: 2
ev: 3 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 1 damage
          tier2: 2 damage
          tier3: 3 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Fingernails
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Allies can't [flank](scc.v1:mcdm.heroes.v1/rule.combat/flanking) with the crawling claw.
      feature_type: trait
      icon: ⭐️
      name: Disorganized
      type: feature
free_strike: 1
immunities:
    - Corruption 1
    - poison 1
intuition: -1
keywords:
    - Undead
    - Soulless
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.undead.1st-echelon.statblock/crawling-claw
    source: mcdm.monsters.v1
might: 0
movement: Climb
name: Crawling Claw
organization: Minion
presence: -1
reason: -5
role: Harrier
size: 1T
speed: 6
stability: 0
stamina: "4"
type: statblock
with_captain: +2 bonus to speed
```
