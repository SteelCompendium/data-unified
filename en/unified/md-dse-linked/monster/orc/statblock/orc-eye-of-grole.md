---
agility: 1
ev: "6"
file_basename: orc-eye-of-grole
file_dpath: monster/orc/statblock
free_strike: 4
immunities:
    - Cold
    - fire
    - or lightning
intuition: 0
item_id: orc-eye-of-grole
item_name: Orc Eye of Grole
keywords:
    - Humanoid
    - Orc
level: 1
might: 1
name: Orc Eye of Grole
organization: Platoon
presence: 2
reason: 0
role: Artillery
scc: mcdm.monsters.v1/monster.orc.statblock/orc-eye-of-grole
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "20"
type: statblock
---

```ds-sb
agility: 1
ev: "6"
features:
    - effects:
        - effect: The eye has an affinity for one of the following damage types cold, fire, or lightning. The chosen type determines the eye's [damage immunity](../../../rule/damage/damage-immunity.md) and the damage dealt by their abilities.
      feature_type: trait
      icon: ⭐️
      name: Elemental Affinity
      type: feature
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 6 damage; [push](../../../movement/forced-movement.md) 2, or the eye [shifts](../../../movement/shifting.md) up to 2 squares away from the target
          tier2: 9 damage; [slide](../../../movement/forced-movement.md) 4, or the eye [shifts](../../../movement/shifting.md) up to 4 squares away from the target
          tier3: 12 damage; [slide](../../../movement/forced-movement.md) 6, or the eye [shifts](../../../movement/shifting.md) up to 6 squares away from the target
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Elemental Discharge
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 5 x 2 line within 1
      effects:
        - roll: Power Roll + 2
          tier1: 3 damage; [push](../../../movement/forced-movement.md) 2
          tier2: 5 damage; [push](../../../movement/forced-movement.md) 3
          tier3: 8 damage; [push](../../../movement/forced-movement.md) 4, [prone](../../../condition/prone.md)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      name: Power Burst
      target: Each enemy in the area
      type: feature
      usage: Main action
    - effects:
        - effect: If the eye is reduced to 0 [Stamina](../../../rule/health/stamina.md), they can make a [free strike](../../../feature/common/main-actions/free-strike.md) before dying. If the target of the free strike is reduced to 0 [Stamina](../../../rule/health/stamina.md), the eye is reduced to 1 [Stamina](../../../rule/health/stamina.md) instead.
      feature_type: trait
      icon: ⭐️
      name: Relentless
      type: feature
free_strike: 4
immunities:
    - Cold
    - fire
    - or lightning
intuition: 0
keywords:
    - Humanoid
    - Orc
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.orc.statblock/orc-eye-of-grole
    source: mcdm.monsters.v1
might: 1
name: Orc Eye of Grole
organization: Platoon
presence: 2
reason: 0
role: Artillery
size: 1M
speed: 6
stability: 0
stamina: "20"
type: statblock
```
