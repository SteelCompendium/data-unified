---
agility: 2
ev: "32"
file_basename: aeolyxria-the-uncanny
file_dpath: monster/draconian/statblock
free_strike: 7
immunities:
    - Poison 6
intuition: 3
item_id: aeolyxria-the-uncanny
item_name: Aeolyxria the Uncanny
keywords:
    - Draconian
    - Dragon
    - Humanoid
level: 6
might: -1
movement: Fly
name: Aeolyxria the Uncanny
organization: Elite
presence: 1
reason: 2
role: Controller
scc: mcdm.monsters.v1/monster.draconian.statblock/aeolyxria-the-uncanny
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "140"
type: statblock
---

```ds-sb
agility: 2
ev: "32"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 3
          tier1: 10 poison damage; M < 1 [slowed](../../../condition/slowed.md) (save ends)
          tier2: 15 poison damage; M < 2 [slowed](../../../condition/slowed.md) (save ends)
          tier3: 18 poison damage; M < 3 [slowed](../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Spittlesplash
      target: Two enemies
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - roll: Power Roll + 3
          tier1: The targets regains 10 [Stamina](../../../rule/health/stamina.md).
          tier2: 12 corruption damage; A < 2 [weakened](../../../condition/weakened.md) (save ends)
          tier3: 12 lightning damage; A < 2 [bleeding](../../../condition/bleeding.md) (save ends)
        - effect: The first time in an encounter that Aeolyxria makes a power roll for this ability, she can subsequently use the outcome of that roll instead of rolling whenever she uses this ability until the end of the encounter.
          name: Effect
        - cost: 2+ Malice
          effect: The ability targets one additional target for each 2 [Malice](../../../rule/monster/malice.md) spent.
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Experimental Treasure
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: 1 cube within 5
      effects:
        - effect: The ground in the area rises 5 squares, creating a pillar of dirt. Any creature in the area moves with the ground to its new elevation.
          name: Effect
        - cost: 1+ Malice
          effect: Aeolyxria creates an additional pillar for each [Malice](../../../rule/monster/malice.md) spent.
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
      name: Elevate
      target: Special
      type: feature
      usage: Maneuver
    - distance: Ranged 5
      effects:
        - roll: Power Roll + 3
          tier1: 7 poison damage; A < 2 [bleeding](../../../condition/bleeding.md) (save ends)
          tier2: 12 poison damage; A < 3 [bleeding](../../../condition/bleeding.md) (save ends)
          tier3: 15 poison damage; [bleeding](../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
        - Weapon
      name: Blood For Blood
      target: One creature
      trigger: An ally is made [bleeding](../../../condition/bleeding.md) by the target.
      type: feature
      usage: Triggered action
    - effects:
        - effect: The Director gains 1 [Malice](../../../rule/monster/malice.md) whenever Aeolyxria imposes a condition on an enemy.
      feature_type: trait
      icon: ⭐️
      name: That's Our Opening!
      type: feature
free_strike: 7
immunities:
    - Poison 6
intuition: 3
keywords:
    - Draconian
    - Dragon
    - Humanoid
level: 6
metadata:
    scc: mcdm.monsters.v1/monster.draconian.statblock/aeolyxria-the-uncanny
    source: mcdm.monsters.v1
might: -1
movement: Fly
name: Aeolyxria the Uncanny
organization: Elite
presence: 1
reason: 2
role: Controller
size: 1M
speed: 5
stability: 2
stamina: "140"
type: statblock
```
