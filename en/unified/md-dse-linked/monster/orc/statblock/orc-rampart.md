---
agility: 2
ev: "8"
file_basename: orc-rampart
file_dpath: monster/orc/statblock
free_strike: 4
intuition: 2
item_id: orc-rampart
item_name: Orc Rampart
keywords:
    - Humanoid
    - Orc
level: 2
might: 2
name: Orc Rampart
organization: Platoon
presence: 2
reason: 2
role: Defender
scc: mcdm.monsters.v1/monster.orc.statblock/orc-rampart
size: 1L
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "59"
type: statblock
---

```ds-sb
agility: 2
ev: "8"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 6 damage
          tier2: 9 damage; [taunted](../../../condition/taunted.md) (EoT)
          tier3: 12 damage; [taunted](../../../condition/taunted.md) (EoT)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: My Spear, My Foe
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Self; see below
      effects:
        - effect: '**Effect:** The rampart moves or [shifts](../../../movement/shifting.md) up to their speed [adjacent](../../../rule/combat/adjacent.md) to the target, then can swap places with the target.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Castling
      target: One ally
      type: feature
      usage: Maneuver
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** A creature targets an ally [adjacent](../../../rule/combat/adjacent.md) to the rampart with an ability that doesn't also target the rampart.
            **Effect:** The rampart becomes the target of the triggering ability instead.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: No.
      target: Self
      type: feature
      usage: Triggered action
    - effects:
        - effect: If the rampart is reduced to 0 [Stamina](../../../rule/health/stamina.md), they can make a [free strike](../../../feature/common/main-actions/free-strike.md) before dying. If the target of the free strike is reduced to 0 [Stamina](../../../rule/health/stamina.md), the rampart is reduced to 1 [Stamina](../../../rule/health/stamina.md) instead.
      feature_type: trait
      icon: ⭐️
      name: Relentless
      type: feature
free_strike: 4
intuition: 2
keywords:
    - Humanoid
    - Orc
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.orc.statblock/orc-rampart
    source: mcdm.monsters.v1
might: 2
name: Orc Rampart
organization: Platoon
presence: 2
reason: 2
role: Defender
size: 1L
speed: 6
stability: 2
stamina: "59"
type: statblock
```
