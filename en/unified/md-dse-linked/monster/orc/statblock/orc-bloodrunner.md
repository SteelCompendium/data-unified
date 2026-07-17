---
agility: 2
ev: "10"
file_basename: orc-bloodrunner
file_dpath: monster/orc/statblock
free_strike: 5
intuition: 1
item_id: orc-bloodrunner
item_name: Orc Bloodrunner
keywords:
    - Humanoid
    - Orc
level: 3
might: 2
name: Orc Bloodrunner
organization: Platoon
presence: 1
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.orc.statblock/orc-bloodrunner
size: 1M
source: mcdm.monsters.v1
speed: 8
stability: 0
stamina: "50"
type: statblock
---

```ds-sb
agility: 2
ev: "10"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage; [push](../../../movement/forced-movement.md) special
          tier2: 10 damage; [push](../../../movement/forced-movement.md) special
          tier3: 13 damage; [push](../../../movement/forced-movement.md) special or [prone](../../../condition/prone.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Shield Bash
      target: One creature or object
      type: feature
      usage: Main action
    - effects:
        - effect: The bloodrunner can end their movement in a [prone](../../../condition/prone.md) creature's space. The first time on a turn that a bloodrunner enters any creature's space, that creature takes 3 damage.
      feature_type: trait
      icon: ⭐️
      name: Unimpeded
      type: feature
    - effects:
        - effect: If the bloodrunner is reduced to 0 [Stamina](../../../rule/health/stamina.md), they can make a [free strike](../../../feature/common/main-actions/free-strike.md) before dying. If the target of the free strike is reduced to 0 [Stamina](../../../rule/health/stamina.md), the bloodrunner is reduced to 1 [Stamina](../../../rule/health/stamina.md) instead.
      feature_type: trait
      icon: ⭐️
      name: Relentless
      type: feature
free_strike: 5
intuition: 1
keywords:
    - Humanoid
    - Orc
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.orc.statblock/orc-bloodrunner
    source: mcdm.monsters.v1
might: 2
name: Orc Bloodrunner
organization: Platoon
presence: 1
reason: 0
role: Harrier
size: 1M
speed: 8
stability: 0
stamina: "50"
type: statblock
```
