---
agility: 0
ev: '-'
file_basename: human-warrior
file_dpath: monster/retainer/statblock
free_strike: 2
intuition: 0
item_id: human-warrior
item_name: Human Warrior
keywords:
    - Human
    - Humanoid
level: 1
might: 2
name: Human Warrior
organization: Retainer
presence: 1
reason: 0
role: Defender
scc: mcdm.monsters.v1/monster.retainer.statblock/human-warrior
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "21"
type: statblock
---

```ds-sb
agility: 0
ev: '-'
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 3 damage
          tier2: 5 damage
          tier3: 7 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Chop
      target: One creature or object
      type: feature
      usage: Main action
    - effects:
        - effect: The warrior ignores concealment if it's granted by a supernatural effect.
      feature_type: trait
      icon: ⭐️
      name: Supernatural Insight
      type: feature
free_strike: 2
intuition: 0
keywords:
    - Human
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.retainer.statblock/human-warrior
    source: mcdm.monsters.v1
might: 2
name: Human Warrior
organization: Retainer
presence: 1
reason: 0
role: Defender
size: 1M
speed: 5
stability: 0
stamina: "21"
type: statblock
```
