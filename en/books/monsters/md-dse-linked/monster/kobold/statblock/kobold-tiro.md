---
agility: 2
ev: 3 for four minions
file_basename: kobold-tiro
file_dpath: monster/kobold/statblock
free_strike: 1
intuition: 0
item_id: kobold-tiro
item_name: Kobold Tiro
keywords:
    - Humanoid
    - Kobold
level: 1
might: 0
name: Kobold Tiro
organization: Minion
presence: 0
reason: 0
role: Defender
scc: mcdm.monsters.v1/monster.kobold.statblock/kobold-tiro
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "5"
type: statblock
with_captain: +1 bonus to speed
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
          tier2: 2 damage; the tiro can [shift](../../../movement/shifting.md) 1 square
          tier3: 3 damage; the tiro [shifts](../../../movement/shifting.md) up to 2 squares
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Pugio
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: While [adjacent](../../../rule/combat/adjacent.md) to an ally who also has this trait, the tiro has stability 1, has cover, and grants cover to allies.
      feature_type: trait
      icon: ⭐️
      name: Shield? Shield!
      type: feature
free_strike: 1
intuition: 0
keywords:
    - Humanoid
    - Kobold
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.kobold.statblock/kobold-tiro
    source: mcdm.monsters.v1
might: 0
name: Kobold Tiro
organization: Minion
presence: 0
reason: 0
role: Defender
size: 1S
speed: 5
stability: 0
stamina: "5"
type: statblock
with_captain: +1 bonus to speed
```
