---
agility: 2
ev: "4"
file_basename: gnoll-abyssal-archer
file_dpath: monster/gnoll/statblock
free_strike: 3
intuition: 0
item_id: gnoll-abyssal-archer
item_name: Gnoll Abyssal Archer
keywords:
    - Abyssal
    - Gnoll
level: 2
might: 0
name: Gnoll Abyssal Archer
organization: Horde
presence: -1
reason: 1
role: Artillery
scc: mcdm.monsters.v1/monster.gnoll.statblock/gnoll-abyssal-archer
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "15"
type: statblock
---

```ds-sb
agility: 2
ev: "4"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 5 corruption damage
          tier2: 6 corruption damage
          tier3: 8 corruption damage; M < 2 [slowed](../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Dark Longbow
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: 2 burst
      effects:
        - effect: '**Effect:** Until the end of their next turn, each target gains an edge on their next strike. If any target hasn''t used their own Cackletongue maneuver on this turn, they can use it immediately at no cost.'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Archer's Cackletongue
      target: Self and each ally in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: Whenever a non-[minion](../../../rule/organization/minion.md) ally within 5 squares of the abyssal archer is reduced to 0 [Stamina](../../../rule/health/stamina.md), the abyssal archer can make a ranged [free strike](../../../feature/common/main-actions/free-strike.md).
      feature_type: trait
      icon: ⭐️
      name: Distant Death Frenzy
      type: feature
    - effects:
        - effect: The abyssal archer doesn't need line of effect to use their abilities against any creature who isn't at full [Stamina](../../../rule/health/stamina.md), as long as a size 1 opening exists between the archer and the target.
      feature_type: trait
      icon: ⭐️
      name: Bloodscent
      type: feature
free_strike: 3
intuition: 0
keywords:
    - Abyssal
    - Gnoll
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.gnoll.statblock/gnoll-abyssal-archer
    source: mcdm.monsters.v1
might: 0
name: Gnoll Abyssal Archer
organization: Horde
presence: -1
reason: 1
role: Artillery
size: 1M
speed: 5
stability: 1
stamina: "15"
type: statblock
```
