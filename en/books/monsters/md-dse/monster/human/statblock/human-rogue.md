---
agility: 2
ev: 3 for four minions
file_basename: human-rogue
file_dpath: monster/human/statblock
free_strike: 2
immunities:
    - Corruption 1
    - psychic 1
intuition: 0
item_id: human-rogue
item_name: Human Rogue
keywords:
    - Human
    - Humanoid
level: 1
might: 0
name: Human Rogue
organization: Minion
presence: 1
reason: 0
role: Ambusher
scc: mcdm.monsters.v1/monster.human.statblock/human-rogue
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "4"
type: statblock
with_captain: Gain an edge on strikes
---

```ds-sb
agility: 2
ev: 3 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1 or Ranged 5
      effects:
        - roll: Power Roll + 2
          tier1: 1 damage
          tier2: 2 damage
          tier3: 3 damage
      feature_type: ability
      icon: ⚔️
      keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Concealed Dagger
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The rogue ignores concealment if it's granted by a supernatural effect.
      feature_type: trait
      icon: ⭐️
      name: Supernatural Insight
      type: feature
free_strike: 2
immunities:
    - Corruption 1
    - psychic 1
intuition: 0
keywords:
    - Human
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.human.statblock/human-rogue
    source: mcdm.monsters.v1
might: 0
name: Human Rogue
organization: Minion
presence: 1
reason: 0
role: Ambusher
size: 1M
speed: 7
stability: 0
stamina: "4"
type: statblock
with_captain: Gain an edge on strikes
```
