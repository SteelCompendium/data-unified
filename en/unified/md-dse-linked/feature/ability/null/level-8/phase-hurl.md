---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: "null"
cost: 11 Discipline
cost_amount: "11"
cost_resource: Discipline
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: The target and each creature or object they collide with from this [forced movement](../../../../movement/forced-movement.md) takes psychic damage equal to the total number of squares the target was force moved. While the target is [dazed](../../../../condition/dazed.md) this way, they see glimpses of creatures from other parts of the timescape.
feature_type: ability
file_basename: phase-hurl
file_dpath: feature/ability/null/level-8
flavor: You throw your foe out of phase with this manifold, causing them to harm other enemies as they return.
item_id: phase-hurl
item_name: Phase Hurl
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "8"
name: Phase Hurl
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.null.level-8/phase-hurl
source: mcdm.heroes.v1
target: One creature
tier1: 9 + A damage; [push](../../../../movement/forced-movement.md) 5; I < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
tier2: 13 + A damage; [push](../../../../movement/forced-movement.md) 7; I < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
tier3: 18 + A damage; [push](../../../../movement/forced-movement.md) 10; I < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
type: ability
---

```ds-feature
cost: 11 Discipline
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: The target and each creature or object they collide with from this [forced movement](../../../../movement/forced-movement.md) takes psychic damage equal to the total number of squares the target was force moved. While the target is [dazed](../../../../condition/dazed.md) this way, they see glimpses of creatures from other parts of the timescape.
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 9 + A damage; [push](../../../../movement/forced-movement.md) 5; I < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
      tier2: 13 + A damage; [push](../../../../movement/forced-movement.md) 7; I < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
      tier3: 18 + A damage; [push](../../../../movement/forced-movement.md) 10; I < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
feature_type: ability
flavor: You throw your foe out of phase with this manifold, causing them to harm other enemies as they return.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: "null"
    cost: 11 Discipline
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: The target and each creature or object they collide with from this [forced movement](../../../../movement/forced-movement.md) takes psychic damage equal to the total number of squares the target was force moved. While the target is [dazed](../../../../condition/dazed.md) this way, they see glimpses of creatures from other parts of the timescape.
    flavor: You throw your foe out of phase with this manifold, causing them to harm other enemies as they return.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - Psionic
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "8"
    name: Phase Hurl
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.null.level-8/phase-hurl
    target: One creature
    tier1: 9 + A damage; [push](../../../../movement/forced-movement.md) 5; I < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
    tier2: 13 + A damage; [push](../../../../movement/forced-movement.md) 7; I < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
    tier3: 18 + A damage; [push](../../../../movement/forced-movement.md) 10; I < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
    type: ability
name: Phase Hurl
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
