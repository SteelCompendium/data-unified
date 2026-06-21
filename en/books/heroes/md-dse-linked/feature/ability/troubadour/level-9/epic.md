---
action_type: Maneuver
class: troubadour
cost: 11 Drama
cost_amount: "11"
cost_resource: Drama
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 10'
effect: Choose one ally within [distance](../../../../rule/combat/distance.md). While the target is affected by this ability, each time they use an ability, that ally can make a [free strike](../../../common/main-actions/free-strike.md) against them after the ability is resolved.
feature_type: ability
file_basename: epic
file_dpath: feature/ability/troubadour/level-9
flavor: Your story tells a tale of the villain's waning power and how the heroes rose to the occasion to stop them.
item_id: epic
item_name: Epic
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "9"
name: Epic
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/epic
source: mcdm.heroes.v1
target: One creature
tier1: The target takes a [bane](../../../../rule/dice/bane.md) on [ability rolls](../../../../rule/dice/ability-roll.md) (save ends).
tier2: The target has a double [bane](../../../../rule/dice/bane.md) on [ability rolls](../../../../rule/dice/ability-roll.md) (save ends).
tier3: The target has a double [bane](../../../../rule/dice/bane.md) on [power rolls](../../../../rule/dice/power-roll.md) (save ends).
type: ability
---

```ds-feature
cost: 11 Drama
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: Choose one ally within [distance](../../../../rule/combat/distance.md). While the target is affected by this ability, each time they use an ability, that ally can make a [free strike](../../../common/main-actions/free-strike.md) against them after the ability is resolved.
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: The target takes a [bane](../../../../rule/dice/bane.md) on [ability rolls](../../../../rule/dice/ability-roll.md) (save ends).
      tier2: The target has a double [bane](../../../../rule/dice/bane.md) on [ability rolls](../../../../rule/dice/ability-roll.md) (save ends).
      tier3: The target has a double [bane](../../../../rule/dice/bane.md) on [power rolls](../../../../rule/dice/power-roll.md) (save ends).
feature_type: ability
flavor: Your story tells a tale of the villain's waning power and how the heroes rose to the occasion to stop them.
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: Maneuver
    class: troubadour
    cost: 11 Drama
    distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 10'
    effect: Choose one ally within [distance](../../../../rule/combat/distance.md). While the target is affected by this ability, each time they use an ability, that ally can make a [free strike](../../../common/main-actions/free-strike.md) against them after the ability is resolved.
    flavor: Your story tells a tale of the villain's waning power and how the heroes rose to the occasion to stop them.
    keywords:
        - Magic
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "9"
    name: Epic
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/epic
    target: One creature
    tier1: The target takes a [bane](../../../../rule/dice/bane.md) on [ability rolls](../../../../rule/dice/ability-roll.md) (save ends).
    tier2: The target has a double [bane](../../../../rule/dice/bane.md) on [ability rolls](../../../../rule/dice/ability-roll.md) (save ends).
    tier3: The target has a double [bane](../../../../rule/dice/bane.md) on [power rolls](../../../../rule/dice/power-roll.md) (save ends).
    type: ability
name: Epic
target: One creature
type: feature
usage: Maneuver
```
