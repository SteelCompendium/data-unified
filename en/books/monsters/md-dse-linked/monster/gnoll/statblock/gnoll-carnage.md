---
agility: 3
ev: "16"
file_basename: gnoll-carnage
file_dpath: monster/gnoll/statblock
free_strike: 5
intuition: 0
item_id: gnoll-carnage
item_name: Gnoll Carnage
keywords:
    - Abyssal
    - Gnoll
level: 2
might: 3
name: Gnoll Carnage
organization: Leader
presence: 3
reason: 0
scc: mcdm.monsters.v1/monster.gnoll.statblock/gnoll-carnage
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "100"
type: statblock
---

```ds-sb
agility: 3
ev: "16"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 3
          tier1: 8 damage; A < 1 [bleeding](../../../condition/bleeding.md) (save ends)
          tier2: 11 damage; A < 2 [bleeding](../../../condition/bleeding.md) (save ends)
          tier3: 14 damage; A < 3 [bleeding](../../../condition/bleeding.md) and [dazed](../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Shrapnel Whip
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 4 Malice
      distance: 5 burst
      effects:
        - effect: '**Effect:** Each target deals an extra 3 damage with their next strike until the start of the carnage''s next turn. If any target hasn''t used their own Cackletongue maneuver on this turn, they can use it immediately at no cost.'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Carnage's Cackletongue
      target: Self and each ally in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: Whenever a non-[minion](../../../rule/organization/minion.md) ally within 5 squares of the carnage is reduced to 0 [Stamina](../../../rule/health/stamina.md), the carnage can move up to their speed, then can either make a melee [free strike](../../../feature/common/main-actions/free-strike.md) against two creatures or use Shrapnel Whip against one creature.
      feature_type: trait
      icon: ⭐️
      name: Death Rampage
      type: feature
    - effects:
        - effect: At the end of each of their turns, the carnage can take 5 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
      feature_type: trait
      icon: ⭐️
      name: End Effect
      type: feature
    - effects:
        - effect: If the carnage is reduced to 0 [Stamina](../../../rule/health/stamina.md) while there are still gnolls on the encounter map, one gnoll on the map is transformed into a gnoll carnage, keeping their current [Stamina](../../../rule/health/stamina.md).
      feature_type: trait
      icon: ⭐️
      name: Endless Hunger
      type: feature
    - cost: Villain Action 1
      distance: Ranged 10
      effects:
        - effect: '**Effect:** The carnage summons four abyssal hyenas into unoccupied spaces within distance.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Magic
        - Ranged
      name: Call Up From the Abyss
      target: Special
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: 10 burst
      effects:
        - effect: '**Effect:** Each target moves up to their speed and can make a [free strike](../../../feature/common/main-actions/free-strike.md). Any creature damaged by one of these [free strikes](../../../feature/common/main-actions/free-strike.md) who has M < 2 is knocked [prone](../../../condition/prone.md).'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: Edacity
      target: Self and three allies
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 5 burst
      effects:
        - roll: ""
          tier1: The target can't regain [Stamina](../../../rule/health/stamina.md) until the end of the encounter.
          tier2: The target can't regain [Stamina](../../../rule/health/stamina.md) (save ends).
          tier3: No effect
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Deepest Wounds
      target: Each winded enemy in the area
      type: feature
      usage: '-'
free_strike: 5
intuition: 0
keywords:
    - Abyssal
    - Gnoll
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.gnoll.statblock/gnoll-carnage
    source: mcdm.monsters.v1
might: 3
name: Gnoll Carnage
organization: Leader
presence: 3
reason: 0
role: ""
size: 1M
speed: 5
stability: 1
stamina: "100"
type: statblock
```
