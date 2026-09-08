---
agility: 2
ev: "40"
file_basename: basalt-stone-giant
file_dpath: monster/giant/statblock
free_strike: 8
intuition: 2
item_id: basalt-stone-giant
item_name: Basalt Stone Giant
keywords:
    - Giant
    - Stone Giant
level: 8
might: 4
movement: Burrow
name: Basalt Stone Giant
organization: Elite
presence: 1
reason: 1
role: Controller
scc: mcdm.monsters.v1/monster.giant.statblock/basalt-stone-giant
size: "4"
source: mcdm.monsters.v1
speed: 7
stability: 10
stamina: "207"
type: statblock
---

```ds-sb
agility: 2
ev: "40"
features:
    - ability_type: Signature Ability
      distance: Melee 3
      effects:
        - roll: Power Roll + 4
          tier1: 12 damage; M < 2 [slowed](../../../condition/slowed.md) (save ends)
          tier2: 17 damage; M < 3 [slowed](../../../condition/slowed.md) (save ends)
          tier3: 21 damage; M < 4 [slowed](../../../condition/slowed.md) (save ends)
        - effect: If a target was already [slowed](../../../condition/slowed.md), that condition continues but their speed is 0 until the end of their next turn.
          name: Effect
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Magic
        - Melee
        - Strike
        - Weapon
      name: Rune-Signed Blade
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Melee 3 or ranged 12
      effects:
        - roll: Power Roll + 4
          tier1: 10 damage; A < 2 [restrained](../../../condition/restrained.md) (save ends)
          tier2: 16 damage; A < 3 [restrained](../../../condition/restrained.md) (save ends)
          tier3: 20 damage; [prone](../../../condition/prone.md); A < 4 [restrained](../../../condition/restrained.md) (save ends)
        - effect: The knife lands in the target's square, and has 30 [Stamina](../../../rule/health/stamina.md) and damage immunity 5. Whenever the knife takes damage, it deals 4 sonic damage to each enemy within 3 squares. The knife lasts until the end of the encounter, and can't be picked up or manipulated.
          name: Effect
      feature_type: ability
      icon: ⚔️
      keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Forked Knife
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: The basalt stone giant moves up to their speed. Each square that they leave during this move is [difficult terrain](../../../movement/difficult-terrain.md) for enemies. Giants ignore this [difficult terrain](../../../movement/difficult-terrain.md).
          name: Effect
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Cobblestone Shape
      target: Self
      type: feature
      usage: Maneuver
    - distance: 2 burst
      effects:
        - effect: The target is [pushed](../../../movement/forced-movement.md) up to 3 squares, or if they have A < 3, they are [pushed](../../../movement/forced-movement.md) up to 6 squares and knocked [prone](../../../condition/prone.md).
          name: Effect
      feature_type: ability
      icon: ❗️
      keywords:
        - Area
        - Magic
      name: Resonate Rune
      target: Each enemy in the area
      trigger: The basalt stone giant takes damage.
      type: feature
      usage: Triggered action
    - effects:
        - effect: Whenever an enemy obtains a tier 1 outcome on a melee ability used against the basalt stone giant, they take a bane on that ability until the end of the encounter.
      feature_type: trait
      icon: ⭐️
      name: Stonebreaker Flesh
      type: feature
    - effects:
        - effect: The basalt stone giant ignores [difficult terrain](../../../movement/difficult-terrain.md).
      feature_type: trait
      icon: ⭐️
      name: Stone Steps
      type: feature
    - effects:
        - effect: The basalt stone giant can [burrow](../../../movement/burrow.md) through stone, but can't drag other creatures underground when they do so.
      feature_type: trait
      icon: ⭐️
      name: Stone Swim
      type: feature
free_strike: 8
intuition: 2
keywords:
    - Giant
    - Stone Giant
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.giant.statblock/basalt-stone-giant
    source: mcdm.monsters.v1
might: 4
movement: Burrow
name: Basalt Stone Giant
organization: Elite
presence: 1
reason: 1
role: Controller
size: "4"
speed: 7
stability: 10
stamina: "207"
type: statblock
```
