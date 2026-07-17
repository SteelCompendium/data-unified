---
agility: 0
ev: "10"
file_basename: dwarf-shieldwall
file_dpath: monster/dwarf/statblock
free_strike: 5
intuition: 0
item_id: dwarf-shieldwall
item_name: Dwarf Shieldwall
keywords:
    - Dwarf
    - Humanoid
level: 3
might: 2
name: Dwarf Shieldwall
organization: Platoon
presence: 1
reason: 0
role: Defender
scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-shieldwall
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 4
stamina: "72"
type: statblock
---

```ds-sb
agility: 0
ev: "10"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage; [slide](../../../movement/forced-movement.md) 1
          tier2: 10 damage; [slide](../../../movement/forced-movement.md) 1
          tier3: 13 damage; [slide](../../../movement/forced-movement.md) 1
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Wide Axe
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 1 Malice
      distance: Self
      effects:
        - effect: |-
            **Trigger:** A creature makes a strike against an ally [adjacent](../../../rule/combat/adjacent.md) to the shieldwall.
            **Effect:** The shieldwall becomes the target of the triggering strike and halves the damage.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Intercepting Shield
      target: Self
      type: feature
      usage: Triggered action
    - effects:
        - effect: Whenever a creature deals damage to or takes damage from the shieldwall, the shieldwall can make that creature [taunted](../../../condition/taunted.md) until the end of the creature's next turn.
      feature_type: trait
      icon: ⭐️
      name: Call to the Wall
      type: feature
free_strike: 5
intuition: 0
keywords:
    - Dwarf
    - Humanoid
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-shieldwall
    source: mcdm.monsters.v1
might: 2
name: Dwarf Shieldwall
organization: Platoon
presence: 1
reason: 0
role: Defender
size: 1M
speed: 5
stability: 4
stamina: "72"
type: statblock
```
