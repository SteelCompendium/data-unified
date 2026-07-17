---
agility: 1
ev: '-'
file_basename: troll-mercenary
file_dpath: monster/retainer/statblock
free_strike: 6
intuition: 0
item_id: troll-mercenary
item_name: Troll Mercenary
keywords:
    - Giant
    - Troll
level: 5
might: 3
name: Troll Mercenary
organization: Retainer
presence: 1
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.retainer.statblock/troll-mercenary
size: "2"
source: mcdm.monsters.v1
speed: 6
stability: 4
stamina: "57"
type: statblock
weaknesses:
    - Acid 5
    - fire
---

```ds-sb
agility: 1
ev: '-'
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 6 damage
          tier2: 11 damage
          tier3: 14 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Big Bite
      target: One creature or object
      type: feature
      usage: Main action
    - cost: Encounter
      distance: 3 burst
      effects:
        - roll: Power Roll + highest characteristic
          tier1: P < WEAK [frightened](../../../condition/frightened.md) ([save](../../../rule/general/saving-throw.md) ends)
          tier2: P < AVERAGE [frightened](../../../condition/frightened.md) ([save](../../../rule/general/saving-throw.md) ends)
          tier3: P < STRONG [frightened](../../../condition/frightened.md) ([save](../../../rule/general/saving-throw.md) ends), push 3, [prone](../../../condition/prone.md)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Troll Roar
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: The mercenary dies only if they are reduced to 0 [Stamina](../../../rule/health/stamina.md) by acid or fire damage, if they end their turn with 0 [Stamina](../../../rule/health/stamina.md), or if they take acid or fire damage while at 0 [Stamina](../../../rule/health/stamina.md).
      feature_type: trait
      icon: ⭐️
      name: Relentless Hunger
      type: feature
free_strike: 6
intuition: 0
keywords:
    - Giant
    - Troll
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.retainer.statblock/troll-mercenary
    source: mcdm.monsters.v1
might: 3
name: Troll Mercenary
organization: Retainer
presence: 1
reason: -1
role: Brute
size: "2"
speed: 6
stability: 4
stamina: "57"
type: statblock
weaknesses:
    - Acid 5
    - fire
```
