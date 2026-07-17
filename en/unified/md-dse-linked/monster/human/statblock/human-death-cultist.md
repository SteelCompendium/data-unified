---
agility: 1
ev: "8"
file_basename: human-death-cultist
file_dpath: monster/human/statblock
free_strike: 4
immunities:
    - Corruption 2
    - psychic 2
intuition: 0
item_id: human-death-cultist
item_name: Human Death Cultist
keywords:
    - Human
    - Humanoid
level: 2
might: 0
name: Human Death Cultist
organization: Platoon
presence: 2
reason: 0
role: Support
scc: mcdm.monsters.v1/monster.human.statblock/human-death-cultist
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "40"
type: statblock
---

```ds-sb
agility: 1
ev: "8"
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 6 corruption damage
          tier2: 9 corruption damage
          tier3: 12 corruption damage; I < 2 [weakened](../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: ⚔️
      keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Death Scythe
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 1 Malice per minion
      distance: 5 burst
      effects:
        - effect: '**Effect:** Each target who died during this encounter revives with full [Stamina](../../../rule/health/stamina.md). They immediately die at the end of the encounter or if the death cultist is killed. A target can be revived multiple times by this ability.'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Rise, My Minions
      target: Each dead minion in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: The death cultist ignores concealment if it's granted by a supernatural effect.
      feature_type: trait
      icon: ⭐️
      name: Supernatural Insight
      type: feature
free_strike: 4
immunities:
    - Corruption 2
    - psychic 2
intuition: 0
keywords:
    - Human
    - Humanoid
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.human.statblock/human-death-cultist
    source: mcdm.monsters.v1
might: 0
name: Human Death Cultist
organization: Platoon
presence: 2
reason: 0
role: Support
size: 1M
speed: 5
stability: 0
stamina: "40"
type: statblock
```
