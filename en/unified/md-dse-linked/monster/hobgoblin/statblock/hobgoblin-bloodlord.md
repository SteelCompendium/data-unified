---
agility: 2
ev: "32"
file_basename: hobgoblin-bloodlord
file_dpath: monster/hobgoblin/statblock
free_strike: 7
immunities:
    - Fire 6
intuition: 3
item_id: hobgoblin-bloodlord
item_name: Hobgoblin Bloodlord
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 6
might: 4
movement: Teleport
name: Hobgoblin Bloodlord
organization: Leader
presence: 3
reason: 2
scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-bloodlord
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "180"
type: statblock
---

```ds-sb
agility: 2
ev: "32"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 4
          tier1: 11 corruption damage; P < 2 [bleeding](../../../condition/bleeding.md) (save ends)
          tier2: 16 corruption damage; P < 3 [bleeding](../../../condition/bleeding.md) (save ends)
          tier3: 19 corruption damage; P < 4 [bleeding](../../../condition/bleeding.md) (save ends)
        - cost: 2 Malice
          effect: Each target is marked until the end of the encounter or until they die. The bloodlord's allies gain an edge on strikes against any target marked this way. The bloodlord can have up to three targets marked this way. If they mark a new target who would exceed the limit, the oldest mark ends.
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Magic
        - Melee
        - Strike
        - Weapon
      name: Soul Sword
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - effect: The target moves up to their speed and can use a signature ability.
          name: Effect
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: Take Point!
      target: One ally
      type: feature
      usage: Maneuver
    - cost: 3 Malice
      distance: Ranged 10
      effects:
        - effect: Three hobgoblin recruits manifest from the target's blood into unoccupied spaces [adjacent](../../../rule/combat/adjacent.md) to the target.
          name: Effect
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: An Army From Blood
      target: The triggering creature
      trigger: A non-[minion](../../../rule/organization/minion.md) hobgoblin within distance takes damage.
      type: feature
      usage: Triggered action
    - effects:
        - effect: When the bloodlord is reduced to 0 [Stamina](../../../rule/health/stamina.md), they spray burning blood. Each creature [adjacent](../../../rule/combat/adjacent.md) to the bloodlord takes 3 fire damage.
      feature_type: trait
      icon: ⭐️
      name: Infernal Ichor
      type: feature
    - effects:
        - effect: At the end of each of their turns, the bloodlord can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
      feature_type: trait
      icon: ⭐️
      name: End Effect
      type: feature
    - cost: Villain Action 1
      distance: 10 burst
      effects:
        - effect: Each target gains 10 temporary [Stamina](../../../rule/health/stamina.md) and can move up to their speed. Then each non-[minion](../../../rule/organization/minion.md) target can make a [free strike](../../../feature/common/main-actions/free-strike.md).
          name: Effect
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: Advance!
      target: Self and each ally in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: 3 aura
      effects:
        - effect: Until the end of the encounter, the bloodlord surrounds themself with a storm of flying skulls. Any enemy who enters the area for the first time in a round or starts their turn there takes 8 corruption damage and takes a bane on their next power roll until the start of their next turn.
          name: Effect
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Skulls Abound
      target: Self
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 5 burst
      effects:
        - roll: Power Roll + 4
          tier1: 5 fire damage; P < 2 2 fire damage, [push](../../../movement/forced-movement.md) 2, [prone](../../../condition/prone.md)
          tier2: 5 fire damage; P < 3 7 fire damage, [push](../../../movement/forced-movement.md) 3, [prone](../../../condition/prone.md)
          tier3: 5 fire damage; P < 4 10 fire damage, [push](../../../movement/forced-movement.md) 5, [prone](../../../condition/prone.md)
        - effect: Until the end of the encounter, the bloodlord is wreathed in black flames. Whenever any [adjacent](../../../rule/combat/adjacent.md) enemy [grabs](../../../condition/grabbed.md) the bloodlord or uses a melee ability against them, that enemy takes 5 corruption damage.
          name: Effect
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: I Am Fire! I Am Death!
      target: Each enemy in the area
      type: feature
      usage: '-'
free_strike: 7
immunities:
    - Fire 6
intuition: 3
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 6
metadata:
    scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-bloodlord
    source: mcdm.monsters.v1
might: 4
movement: Teleport
name: Hobgoblin Bloodlord
organization: Leader
presence: 3
reason: 2
role: ""
size: 1M
speed: 6
stability: 2
stamina: "180"
type: statblock
```
