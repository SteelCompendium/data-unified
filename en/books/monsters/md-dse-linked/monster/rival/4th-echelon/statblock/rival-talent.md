---
agility: 0
ev: "48"
file_basename: rival-talent
file_dpath: monster/rival/4th-echelon/statblock
free_strike: 10
intuition: 0
item_id: rival-talent
item_name: Rival Talent
keywords:
    - Humanoid
    - Rival
level: 10
might: 0
name: Rival Talent
organization: Elite
presence: 1
reason: 5
role: Hexer
scc: mcdm.monsters.v1/monster.rival.4th-echelon.statblock/rival-talent
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "220"
type: statblock
---

```ds-sb
agility: 0
ev: "48"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 5
          tier1: 15 psychic damage
          tier2: 20 psychic damage
          tier3: 24 psychic damage
        - cost: 4 Malice
          effect: Each target moves up to their speed and can make a [free strike](../../../../feature/common/main-actions/free-strike.md) against one enemy of the talent's choice. The target's movement can provoke opportunity attacks, but they can't otherwise be moved in a way that would harm them.
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Psionic
        - Ranged
        - Strike
        - Telekinesis
      name: Override
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Ranged 10
      effects:
        - roll: Power Roll + 5
          tier1: R < 3 [slowed](../../../../condition/slowed.md) (save ends)
          tier2: R < 4 [restrained](../../../../condition/restrained.md) (save ends)
          tier3: R < 5 [restrained](../../../../condition/restrained.md) (save ends)
        - effect: One ally within distance can use an additional main action on their next turn.
          name: Effect
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Chronopathy
        - Psionic
        - Ranged
      name: Steal Time
      target: One creature or object
      type: feature
      usage: Maneuver
    - cost: 2 Malice
      distance: Self; see below
      effects:
        - effect: The talent halves the damage and [shifts](../../../../movement/shifting.md) up to 2 squares. The triggering creature takes psychic damage equal to half the damage dealt and is [pushed](../../../../movement/forced-movement.md) up to 5 squares.
          name: Effect
      feature_type: ability
      icon: ❗️
      keywords:
        - Psionic
      name: Psionic Retribution
      target: Self
      trigger: A creature deals damage to the talent.
      type: feature
      usage: Triggered action
    - effects:
        - effect: At the start of an encounter, the talent chooses one creature within their [line of effect](../../../../rule/combat/line-of-effect.md). Both the talent and the creature can add a d3 roll to power rolls they make against each other.
      feature_type: trait
      icon: ⭐️
      name: Rivalry
      type: feature
free_strike: 10
intuition: 0
keywords:
    - Humanoid
    - Rival
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.rival.4th-echelon.statblock/rival-talent
    source: mcdm.monsters.v1
might: 0
name: Rival Talent
organization: Elite
presence: 1
reason: 5
role: Hexer
size: 1M
speed: 5
stability: 2
stamina: "220"
type: statblock
```
