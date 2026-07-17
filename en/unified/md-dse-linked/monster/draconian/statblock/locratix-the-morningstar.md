---
agility: 3
ev: "32"
file_basename: locratix-the-morningstar
file_dpath: monster/draconian/statblock
free_strike: 7
immunities:
    - Acid 6
intuition: 2
item_id: locratix-the-morningstar
item_name: Locratix the Morningstar
keywords:
    - Draconian
    - Dragon
    - Humanoid
level: 6
might: 1
movement: Fly
name: Locratix the Morningstar
organization: Elite
presence: 2
reason: 1
role: Harrier
scc: mcdm.monsters.v1/monster.draconian.statblock/locratix-the-morningstar
size: 1M
source: mcdm.monsters.v1
speed: 8
stability: 2
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
          tier2: 15 damage; M < 1 [slowed](../../../condition/slowed.md) (save ends)
          tier3: 18 damage; M < 2 [slowed](../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Skewer
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: 3 x 1 line within 1
      effects:
        - roll: Power Roll + 3
          tier1: 7 acid damage; M < 1 [dazed](../../../condition/dazed.md) (save ends)
          tier2: 12 acid damage; M < 2 [dazed](../../../condition/dazed.md) (save ends)
          tier3: 15 acid damage; M < 3 [dazed](../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      name: Acidic Stun
      target: Each enemy in the area
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** Locratix [flies](../../../movement/fly.md) up to her speed. Any creature [adjacent](../../../rule/combat/adjacent.md) to the space on the ground she took off from who has A < 2 is knocked [prone](../../../condition/prone.md).'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Takeoff
      target: Self
      type: feature
      usage: Maneuver
    - distance: Melee 2
      effects:
        - roll: Power Roll + 3
          tier1: 7 acid damage; A < 1 the target's speed is 0 (EoT)
          tier2: 12 acid damage; A < 2 the target's speed is 0 (EoT)
          tier3: 15 acid damage; A < 3 the target's speed is 0 (EoT)
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Stay Back!
      target: The triggering creature
      type: feature
      usage: Triggered action
    - effects:
        - effect: When Locratix deals rolled damage to an enemy, that enemy can't use Locratix as the trigger for any of their [triggered actions](../../../rule/combat/triggered-action.md) until the start of Locratix's next turn.
      feature_type: trait
      icon: ⭐️
      name: Flighty
      type: feature
    - effects:
        - effect: When Locratix takes damage of any type for which she has damage immunity, she has damage immunity 6 against the next strike made against her.
      feature_type: trait
      icon: ⭐️
      name: Absorbing Scales
      type: feature
free_strike: 7
immunities:
    - Acid 6
intuition: 2
keywords:
    - Draconian
    - Dragon
    - Humanoid
level: 6
metadata:
    scc: mcdm.monsters.v1/monster.draconian.statblock/locratix-the-morningstar
    source: mcdm.monsters.v1
might: 1
movement: Fly
name: Locratix the Morningstar
organization: Elite
presence: 2
reason: 1
role: Harrier
size: 1M
speed: 8
stability: 2
stamina: "160"
type: statblock
```
