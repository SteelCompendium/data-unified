---
agility: 3
ev: "32"
file_basename: lydixavus-the-deadeye
file_dpath: monster/draconian/statblock
free_strike: 7
immunities:
    - Cold 6
intuition: 3
item_id: lydixavus-the-deadeye
item_name: Lydixavus the Deadeye
keywords:
    - Draconian
    - Dragon
    - Humanoid
level: 6
might: -1
movement: Fly
name: Lydixavus the Deadeye
organization: Elite
presence: 1
reason: 3
role: Artillery
scc: mcdm.monsters.v1/monster.draconian.statblock/lydixavus-the-deadeye
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "140"
type: statblock
---

```ds-sb
agility: 3
ev: "32"
features:
    - ability_type: Signature Ability
      distance: Ranged 15
      effects:
        - roll: Power Roll + 3
          tier1: 10 cold damage
          tier2: 16 cold damage; the target takes a [bane](../../../rule/dice/bane.md) on their next strike
          tier3: 19 cold damage; the target has a double [bane](../../../rule/dice/bane.md) on their next strike
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Breathsnipe
      target: One enemy
      type: feature
      usage: Main action
    - distance: 2 cube within 10
      effects:
        - roll: Power Roll + 3
          tier1: 7 cold damage; M < 1 [dazed](../../../condition/dazed.md) (save ends)
          tier2: 12 cold damage; M < 2 [dazed](../../../condition/dazed.md) (save ends)
          tier3: 15 cold damage; M < 3 [dazed](../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Ice Lob
      target: Each enemy and object in the area
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** Lydixavus [flies](../../../movement/fly.md) up to their speed, leaving a size 1S ice mine in the space they took off from. The ice mine explodes when an enemy enters its space, using the power roll for the Ice Lob ability, and targeting the triggering creature and each creature and object [adjacent](../../../rule/combat/adjacent.md) to the ice mine.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Parting Gift
      target: Self
      type: feature
      usage: Maneuver
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** Lydixavus obtains a tier 1 outcome on their [signature ability](../../../rule/combat/signature-ability.md).
            **Effect:** Lydixavus uses their [signature ability](../../../rule/combat/signature-ability.md) again, targeting a creature within 5 squares of the original target.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Wasn't Aiming For You
      target: Self
      type: feature
      usage: Triggered action
    - effects:
        - effect: Lydixavus knows the location of every creature who has ever dealt damage to them. If any of those creatures are within 20 squares of Lydixavus, Lydixavus always has [line of effect](../../../rule/combat/line-of-effect.md) to them as long as a size 1 opening exists between Lydixavus and the target.
      feature_type: trait
      icon: ⭐️
      name: Scorekeeping Scales
      type: feature
free_strike: 7
immunities:
    - Cold 6
intuition: 3
keywords:
    - Draconian
    - Dragon
    - Humanoid
level: 6
metadata:
    scc: mcdm.monsters.v1/monster.draconian.statblock/lydixavus-the-deadeye
    source: mcdm.monsters.v1
might: -1
movement: Fly
name: Lydixavus the Deadeye
organization: Elite
presence: 1
reason: 3
role: Artillery
size: 1M
speed: 5
stability: 2
stamina: "140"
type: statblock
```
