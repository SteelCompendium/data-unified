---
agility: 2
ev: "28"
file_basename: hobgoblin-war-mage
file_dpath: monster/hobgoblin/statblock
free_strike: 6
immunities:
    - Fire 5
intuition: 2
item_id: hobgoblin-war-mage
item_name: Hobgoblin War Mage
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 5
might: 0
movement: Hover, teleport
name: Hobgoblin War Mage
organization: Elite
presence: 2
reason: 3
role: Controller
scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-war-mage
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "120"
type: statblock
---

```ds-sb
agility: 2
ev: "28"
features:
    - ability_type: Signature Ability
      distance: 3 cube within 10
      effects:
        - roll: Power Roll + 3
          tier1: 5 fire damage; M < 1 [weakened](../../../condition/weakened.md) (save ends)
          tier2: 9 fire damage; M < 2 [weakened](../../../condition/weakened.md) (save ends)
          tier3: 11 fire damage; M < 3 [weakened](../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Hellfire
      target: Each enemy in the area
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - effect: '**Effect:** Each target gains 10 temporary [Stamina](../../../rule/health/stamina.md) and has a double edge on their next power roll. The war mage can spend any amount of their current [Stamina](../../../rule/health/stamina.md) to increase the temporary [Stamina](../../../rule/health/stamina.md) each target gains by an equivalent amount.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Enchantments of War
      target: Two allies
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 5 cube within 10
      effects:
        - effect: '**Effect:** The war mage consecrates the area and causes it to smolder until the end of the encounter. The area is [difficult terrain](../../../movement/difficult-terrain.md) and an enemy in the area has fire weakness 10.'
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Unhallowed Ground
      target: Special
      type: feature
      usage: Maneuver
    - distance: Ranged 10
      effects:
        - effect: |-
            **Trigger:** A creature within distance uses a magic ability.
            **Effect:** Any damage dealt or [Stamina](../../../rule/health/stamina.md) regained from the creature's ability is halved. The war mage regains [Stamina](../../../rule/health/stamina.md) equal to the remaining damage dealt or [Stamina](../../../rule/health/stamina.md) regained.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Ranged
      name: Magic Siphon
      target: The triggering creature
      type: feature
      usage: Triggered action
    - effects:
        - effect: When the war mage is reduced to 0 [Stamina](../../../rule/health/stamina.md), they spray burning blood. Each creature [adjacent](../../../rule/combat/adjacent.md) to the war mage takes 3 fire damage.
      feature_type: trait
      icon: ⭐️
      name: Infernal Ichor
      type: feature
    - effects:
        - effect: Any enemy within 2 squares of the war mage has a −2 penalty to saving throws.
      feature_type: trait
      icon: ⭐️
      name: Despair, You Who Face Death
      type: feature
free_strike: 6
immunities:
    - Fire 5
intuition: 2
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-war-mage
    source: mcdm.monsters.v1
might: 0
movement: Hover, teleport
name: Hobgoblin War Mage
organization: Elite
presence: 2
reason: 3
role: Controller
size: 1M
speed: 5
stability: 0
stamina: "120"
type: statblock
```
