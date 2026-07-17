---
agility: 1
ev: 4 for four minions
file_basename: human-apprentice-mage
file_dpath: monster/human/statblock
free_strike: 2
immunities:
    - Corruption 2
    - psychic 2
intuition: 0
item_id: human-apprentice-mage
item_name: Human Apprentice Mage
keywords:
    - Human
    - Humanoid
level: 2
might: 0
name: Human Apprentice Mage
organization: Minion
presence: 2
reason: 0
role: Controller
scc: mcdm.monsters.v1/monster.human.statblock/human-apprentice-mage
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "4"
type: statblock
with_captain: +5 bonus to ranged distance
---

```ds-sb
agility: 1
ev: 4 for four minions
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 2 lightning damage
          tier2: 3 lightning damage
          tier3: 5 lightning damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Lightning Strike
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The apprentice mage ignores concealment if it's granted by a supernatural effect.
      feature_type: trait
      icon: ⭐️
      name: Supernatural Insight
      type: feature
free_strike: 2
immunities:
    - Corruption 2
    - psychic 2
intuition: 0
keywords:
    - Human
    - Humanoid
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.human.statblock/human-apprentice-mage
    source: mcdm.monsters.v1
might: 0
name: Human Apprentice Mage
organization: Minion
presence: 2
reason: 0
role: Controller
size: 1M
speed: 5
stability: 0
stamina: "4"
type: statblock
with_captain: +5 bonus to ranged distance
```
