---
agility: 2
ev: "10"
file_basename: orc-juggernaut
file_dpath: monster/orc/statblock
free_strike: 5
intuition: -1
item_id: orc-juggernaut
item_name: Orc Juggernaut
keywords:
    - Humanoid
    - Orc
level: 3
might: 2
name: Orc Juggernaut
organization: Platoon
presence: 2
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.orc.statblock/orc-juggernaut
size: 1L
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "60"
type: statblock
---

```ds-sb
agility: 2
ev: "10"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage
          tier2: 11 damage; [prone](../../../condition/prone.md)
          tier3: 14 damage; [prone](../../../condition/prone.md); M < 2 [bleeding](../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Haymaker Greataxe
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 1 Malice
      distance: Self
      effects:
        - effect: |-
            **Trigger:** The juggernaut takes damage.
            **Effect:** The juggernaut moves up to their speed and can make a [free strike](../../../feature/common/main-actions/free-strike.md).
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Hrraaaaaagh!
      target: Self
      type: feature
      usage: Free triggered action
    - effects:
        - effect: Whenever the juggernaut willingly moves, they can move 3 additional squares if they end their movement closer to a [prone](../../../condition/prone.md) creature.
      feature_type: trait
      icon: ⭐️
      name: Blood in the Water
      type: feature
    - effects:
        - effect: If the juggernaut is reduced to 0 [Stamina](../../../rule/health/stamina.md), they can make a [free strike](../../../feature/common/main-actions/free-strike.md) before dying. If the target of the free strike is reduced to 0 [Stamina](../../../rule/health/stamina.md), the juggernaut is reduced to 1 [Stamina](../../../rule/health/stamina.md) instead.
      feature_type: trait
      icon: ⭐️
      name: Relentless
      type: feature
free_strike: 5
intuition: -1
keywords:
    - Humanoid
    - Orc
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.orc.statblock/orc-juggernaut
    source: mcdm.monsters.v1
might: 2
name: Orc Juggernaut
organization: Platoon
presence: 2
reason: -1
role: Brute
size: 1L
speed: 6
stability: 0
stamina: "60"
type: statblock
```
