---
agility: 1
ev: 3 for four minions
file_basename: human-death-acolyte
file_dpath: monster/human/statblock
free_strike: 1
immunities:
    - Corruption 1
    - psychic 1
intuition: 0
item_id: human-death-acolyte
item_name: Human Death Acolyte
keywords:
    - Human
    - Humanoid
level: 1
might: 0
name: Human Death Acolyte
organization: Minion
presence: 2
reason: 0
role: Hexer
scc: mcdm.monsters.v1/monster.human.statblock/human-death-acolyte
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "3"
type: statblock
with_captain: +5 bonus to ranged distance
---

```ds-sb
agility: 1
ev: 3 for four minions
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 1 corruption damage
          tier2: 2 corruption damage
          tier3: 3 corruption damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Necrotic Bolt
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The death acolyte ignores concealment if it's granted by a supernatural effect.
      feature_type: trait
      icon: ⭐️
      name: Supernatural Insight
      type: feature
free_strike: 1
immunities:
    - Corruption 1
    - psychic 1
intuition: 0
keywords:
    - Human
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.human.statblock/human-death-acolyte
    source: mcdm.monsters.v1
might: 0
name: Human Death Acolyte
organization: Minion
presence: 2
reason: 0
role: Hexer
size: 1M
speed: 5
stability: 0
stamina: "3"
type: statblock
with_captain: +5 bonus to ranged distance
```
