---
agility: 3
ev: "32"
file_basename: devil-magistrate
file_dpath: monster/devil/statblock
free_strike: 7
immunities:
    - Fire 5
intuition: 1
item_id: devil-magistrate
item_name: Devil Magistrate
keywords:
    - Devil
    - Infernal
level: 6
might: 1
name: Devil Magistrate
organization: Elite
presence: 2
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.devil.statblock/devil-magistrate
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "160"
type: statblock
---

```ds-sb
agility: 3
ev: "32"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 10 damage
          tier2: 15 damage
          tier3: 18 fire damage; R < 3 [dazed](../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Edge of the Law
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 11 damage
          tier2: 17 damage
          tier3: 21 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Verdict
      target: One creature
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** The magistrate turns invisible until the start of their next turn, and can attempt to hide as a [free maneuver](../../../rule/combat/free-maneuver.md) before the end of the current turn.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Justice Turns Its Gaze
      target: Self
      type: feature
      usage: Maneuver
    - cost: 2 Malice
      distance: Ranged 5
      effects:
        - roll: ""
          tier1: The magistrate chooses a new target for the strike.
          tier2: The magistrate halves the triggering damage.
          tier3: The target takes a [bane](../../../rule/dice/bane.md) on the strike.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Ranged
      name: Devilish Charm
      target: The triggering creature
      type: feature
      usage: Triggered action
    - effects:
        - effect: Whenever the magistrate moves away from an enemy who is [adjacent](../../../rule/combat/adjacent.md) to one of the magistrate's allies, they can [shift](../../../movement/shifting.md) instead.
      feature_type: trait
      icon: ⭐️
      name: Leading
      type: feature
    - effects:
        - effect: If a creature within 10 squares speaks the magistrate's true name, the magistrate loses their damage immunities, any nondamaging effects of their [signature ability](../../../rule/combat/signature-ability.md), and their Devilish Charm ability until the end of the encounter.
      feature_type: trait
      icon: ⭐️
      name: True Name
      type: feature
free_strike: 7
immunities:
    - Fire 5
intuition: 1
keywords:
    - Devil
    - Infernal
level: 6
metadata:
    scc: mcdm.monsters.v1/monster.devil.statblock/devil-magistrate
    source: mcdm.monsters.v1
might: 1
name: Devil Magistrate
organization: Elite
presence: 2
reason: 0
role: Harrier
size: 1M
speed: 7
stability: 0
stamina: "160"
type: statblock
```
