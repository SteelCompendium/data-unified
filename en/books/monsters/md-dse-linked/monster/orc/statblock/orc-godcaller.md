---
agility: 0
ev: "6"
file_basename: orc-godcaller
file_dpath: monster/orc/statblock
free_strike: 3
intuition: 1
item_id: orc-godcaller
item_name: Orc Godcaller
keywords:
    - Humanoid
    - Orc
level: 1
might: 1
name: Orc Godcaller
organization: Platoon
presence: 2
reason: 0
role: Support
scc: mcdm.monsters.v1/monster.orc.statblock/orc-godcaller
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "30"
type: statblock
---

```ds-sb
agility: 0
ev: "6"
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 5 sonic damage
          tier2: 7 sonic damage
          tier3: 9 sonic damage; P < 2 [weakened](../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: ⚔️
      keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
      name: Power Chord
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - effect: |-
            **Effect:** The target moves up to their speed and can use a main action.
            **3 [Malice](../../../rule/monster/malice.md):** The godcaller targets a second ally.
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Cadenza
      target: One ally
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Ranged 10
      effects:
        - effect: '**Effect:** Each target regains 15 [Stamina](../../../rule/health/stamina.md) and ignores [difficult terrain](../../../movement/difficult-terrain.md) until the end of the encounter.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Rallying Ostinato
      target: Self and three allies
      type: feature
      usage: Maneuver
    - effects:
        - effect: If the godcaller is reduced to 0 [Stamina](../../../rule/health/stamina.md), they can make a [free strike](../../../feature/common/main-actions/free-strike.md) before dying. If the target of the free strike is reduced to 0 [Stamina](../../../rule/health/stamina.md), the godcaller is reduced to 1 [Stamina](../../../rule/health/stamina.md) instead.
      feature_type: trait
      icon: ⭐️
      name: Relentless
      type: feature
free_strike: 3
intuition: 1
keywords:
    - Humanoid
    - Orc
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.orc.statblock/orc-godcaller
    source: mcdm.monsters.v1
might: 1
name: Orc Godcaller
organization: Platoon
presence: 2
reason: 0
role: Support
size: 1M
speed: 6
stability: 0
stamina: "30"
type: statblock
```
