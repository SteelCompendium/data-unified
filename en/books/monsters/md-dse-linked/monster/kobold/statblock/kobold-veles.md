---
agility: 2
ev: 3 for four minions
file_basename: kobold-veles
file_dpath: monster/kobold/statblock
free_strike: 1
intuition: 0
item_id: kobold-veles
item_name: Kobold Veles
keywords:
    - Humanoid
    - Kobold
level: 1
might: 0
name: Kobold Veles
organization: Minion
presence: 0
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.kobold.statblock/kobold-veles
size: 1S
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "4"
type: statblock
with_captain: +1 bonus to speed
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
      name: Pilium
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: While [adjacent](../../../rule/combat/adjacent.md) to an ally who also has this trait, the veles has stability 1, has cover, and grants cover to allies.
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
    scc: mcdm.monsters.v1/monster.kobold.statblock/kobold-veles
    source: mcdm.monsters.v1
might: 0
name: Kobold Veles
organization: Minion
presence: 0
reason: 0
role: Harrier
size: 1S
speed: 6
stability: 0
stamina: "4"
type: statblock
with_captain: +1 bonus to speed
```
