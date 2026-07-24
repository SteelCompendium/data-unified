---
action_type: '[Maneuver](../../../../rule/combat/turn.md)'
class: tactician
cost: 5 Focus
cost_amount: "5"
cost_resource: Focus
distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - effect: Each target is marked by you, and you gain two [surges](../../../../rule/resource/surge.md).
      name: Effect
    - effect: Until the end of the encounter, whenever you or any ally makes a [strike](../../../../rule/combat/strike.md) against a creature marked by you, you can spend 2 focus to add one additional target to the [strike](../../../../rule/combat/strike.md).
      name: Mark Benefit
feature_type: ability
file_basename: targets-of-opportunity
file_dpath: feature/ability/tactician/level-2
flavor: You point out easy targets to your friends, allowing them to include more enemies in their attacks.
item_id: targets-of-opportunity
item_name: Targets of Opportunity
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "2"
name: Targets of Opportunity
scc: mcdm.heroes.v1/feature.ability.tactician.level-2/targets-of-opportunity
source: mcdm.heroes.v1
subclass: mastermind
target: Two creatures
type: ability
---

```ds-feature
cost: 5 Focus
distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - effect: Each target is marked by you, and you gain two [surges](../../../../rule/resource/surge.md).
      name: Effect
    - effect: Until the end of the encounter, whenever you or any ally makes a [strike](../../../../rule/combat/strike.md) against a creature marked by you, you can spend 2 focus to add one additional target to the [strike](../../../../rule/combat/strike.md).
      name: Mark Benefit
feature_type: ability
flavor: You point out easy targets to your friends, allowing them to include more enemies in their attacks.
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Maneuver](../../../../rule/combat/turn.md)'
    class: tactician
    cost: 5 Focus
    distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
    effects:
        - effect: Each target is marked by you, and you gain two [surges](../../../../rule/resource/surge.md).
          name: Effect
        - effect: Until the end of the encounter, whenever you or any ally makes a [strike](../../../../rule/combat/strike.md) against a creature marked by you, you can spend 2 focus to add one additional target to the [strike](../../../../rule/combat/strike.md).
          name: Mark Benefit
    flavor: You point out easy targets to your friends, allowing them to include more enemies in their attacks.
    keywords:
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "2"
    name: Targets of Opportunity
    scc: mcdm.heroes.v1/feature.ability.tactician.level-2/targets-of-opportunity
    subclass: mastermind
    target: Two creatures
    type: ability
name: Targets of Opportunity
target: Two creatures
type: feature
usage: '[Maneuver](../../../../rule/combat/turn.md)'
```
