---
agility: 1
ev: '-'
file_basename: kobold-shieldbearer
file_dpath: monster/retainer/statblock
free_strike: 6
intuition: 0
item_id: kobold-shieldbearer
item_name: Kobold Shieldbearer
keywords:
    - Humanoid
    - Kobold
level: 1
might: 2
name: Kobold Shieldbearer
organization: Retainer
presence: 0
reason: 0
role: Defender
scc: mcdm.monsters.v1/monster.retainer.statblock/kobold-shieldbearer
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 4
stamina: "21"
type: statblock
---

```ds-sb
agility: 1
ev: '-'
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 3 damage
          tier2: 5 damage
          tier3: 7 damage; [taunted](../../../condition/taunted.md) (EoT)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Gladius
      target: One creature or object
      type: feature
      usage: Main action
    - effects:
        - effect: While the shieldbearer is [adjacent](../../../rule/combat/adjacent.md) to their mentor, both have a +1 bonus to [stability](../../../rule/character/stability.md), have [cover](../../../rule/combat/cover.md), and grant [cover](../../../rule/combat/cover.md) to allies.
      feature_type: trait
      icon: ⭐️
      name: Shield, Boss?
      type: feature
free_strike: 6
intuition: 0
keywords:
    - Humanoid
    - Kobold
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.retainer.statblock/kobold-shieldbearer
    source: mcdm.monsters.v1
might: 2
name: Kobold Shieldbearer
organization: Retainer
presence: 0
reason: 0
role: Defender
size: "2"
speed: 5
stability: 4
stamina: "21"
type: statblock
```
