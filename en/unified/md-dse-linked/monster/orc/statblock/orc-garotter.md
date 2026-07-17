---
agility: 2
ev: "6"
file_basename: orc-garotter
file_dpath: monster/orc/statblock
free_strike: 4
intuition: 1
item_id: orc-garotter
item_name: Orc Garotter
keywords:
    - Humanoid
    - Orc
level: 1
might: 1
name: Orc Garotter
organization: Platoon
presence: -1
reason: 0
role: Ambusher
scc: mcdm.monsters.v1/monster.orc.statblock/orc-garotter
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "30"
type: statblock
---

```ds-sb
agility: 2
ev: "6"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 6 damage; the garroter can [shift](../../../movement/shifting.md) 1 square
          tier2: 9 damage; the garroter [shifts](../../../movement/shifting.md) up to 2 squares
          tier3: 12 damage; the garroter [shifts](../../../movement/shifting.md) up to 3 squares
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Dagger Feint
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 6 damage
          tier2: 9 damage; I < 1 [dazed](../../../condition/dazed.md) (save ends)
          tier3: 12 damage; [grabbed](../../../condition/grabbed.md); I < 2 [dazed](../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Strangle
      target: One creature
      type: feature
      usage: Main action
    - cost: 1 Malice
      distance: '-'
      effects:
        - effect: The garroter turns invisible until the end of their turn. This invisibility ends early if they take damage or use an ability.
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Chroma Cloak
      target: '-'
      type: feature
      usage: Maneuver
    - effects:
        - effect: If the garroter is reduced to 0 [Stamina](../../../rule/health/stamina.md), they can make a [free strike](../../../feature/common/main-actions/free-strike.md) before dying. If the target of the free strike is reduced to 0 [Stamina](../../../rule/health/stamina.md), the garroter is reduced to 1 [Stamina](../../../rule/health/stamina.md) instead.
      feature_type: trait
      icon: ⭐️
      name: Relentless
      type: feature
free_strike: 4
intuition: 1
keywords:
    - Humanoid
    - Orc
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.orc.statblock/orc-garotter
    source: mcdm.monsters.v1
might: 1
name: Orc Garotter
organization: Platoon
presence: -1
reason: 0
role: Ambusher
size: 1L
speed: 5
stability: 0
stamina: "30"
type: statblock
```
