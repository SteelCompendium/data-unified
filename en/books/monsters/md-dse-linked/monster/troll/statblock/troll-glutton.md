---
agility: 1
ev: "28"
file_basename: troll-glutton
file_dpath: monster/troll/statblock
free_strike: 7
intuition: 0
item_id: troll-glutton
item_name: Troll Glutton
keywords:
    - Giant
    - Troll
level: 5
might: 3
name: Troll Glutton
organization: Elite
presence: 1
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.troll.statblock/troll-glutton
size: "2"
source: mcdm.monsters.v1
speed: 6
stability: 4
stamina: "160"
type: statblock
weaknesses:
    - Acid 5
    - fire
---

```ds-sb
agility: 1
ev: "28"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 10 damage
          tier2: 15 damage; M < 2 [slowed](../../../condition/slowed.md) (save ends)
          tier3: 18 damage; M < 3 [slowed](../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Voracious Mastication
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Self
      effects:
        - effect: '**Effect:** The glutton [shifts](../../../movement/shifting.md) up to their speed in a straight line, ignoring [difficult terrain](../../../movement/difficult-terrain.md). The first time during this movement that the glutton moves through the space of a creature or object their size or smaller, that creature or object takes 10 damage, or a creature can choose to fall [prone](../../../condition/prone.md) instead. If the glutton moves into a creature or object larger than them and doesn''t knock the creature [prone](../../../condition/prone.md) or destroy the object, the glutton''s movement ends and they are [dazed](../../../condition/dazed.md) until the end of their next turn.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Crash Through
      target: Self
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** Until the start of their next turn, the glutton has a double edge on strikes, and strikes made against them gain an edge.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Food Frenzy
      target: Self
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** The glutton is reduced to 0 [Stamina](../../../rule/health/stamina.md) but doesn't die.
            **Effect:** The glutton uses Voracious Mastication against an [adjacent](../../../rule/combat/adjacent.md) creature.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Spiteful Retort
      target: The triggering creature
      type: feature
      usage: Free triggered action
    - effects:
        - effect: Once per turn, the glutton can use the Charge main action as a free maneuver if they target a [winded](../../../rule/health/winded.md) creature.
      feature_type: trait
      icon: ⭐️
      name: Insatiable Appetite
      type: feature
    - effects:
        - effect: The glutton dies only if they are reduced to 0 [Stamina](../../../rule/health/stamina.md) by acid or fire damage, if they end their turn with 0 [Stamina](../../../rule/health/stamina.md), or if they take acid or fire damage while at 0 [Stamina](../../../rule/health/stamina.md).
      feature_type: trait
      icon: ⭐️
      name: Relentless Hunger
      type: feature
free_strike: 7
intuition: 0
keywords:
    - Giant
    - Troll
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.troll.statblock/troll-glutton
    source: mcdm.monsters.v1
might: 3
name: Troll Glutton
organization: Elite
presence: 1
reason: -1
role: Brute
size: "2"
speed: 6
stability: 4
stamina: "160"
type: statblock
weaknesses:
    - Acid 5
    - fire
```
