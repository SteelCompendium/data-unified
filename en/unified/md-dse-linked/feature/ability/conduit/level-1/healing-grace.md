---
action_type: '[Maneuver](../../../../rule/combat/turn.md)'
class: conduit
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: The target can spend a [Recovery](../../../../rule/health/recoveries.md).
      name: Effect
    - cost: Spend 1+ Piety
      effect: 'For each piety spent, choose one of the following [enhancements](../../../../rule/treasure/enhancement.md):'
    - effect: '- You can target one additional ally within [distance](../../../../rule/combat/distance.md). - You can end one effect on a target that is ended by a [saving throw](../../../../rule/general/saving-throw.md) or that ends at the end of their [turn](../../../../rule/combat/turn.md). - A [prone target](../../../../condition/prone.md) can stand up. - A target can spend 1 additional [Recovery](../../../../rule/health/recoveries.md).'
feature_type: ability
file_basename: healing-grace
file_dpath: feature/ability/conduit/level-1
flavor: Your divine energy restores the righteous.
item_id: healing-grace
item_name: Healing Grace
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "1"
name: Healing Grace
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/healing-grace
source: mcdm.heroes.v1
target: Self or one ally
type: ability
---

```ds-feature
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: The target can spend a [Recovery](../../../../rule/health/recoveries.md).
      name: Effect
    - cost: Spend 1+ Piety
      effect: 'For each piety spent, choose one of the following [enhancements](../../../../rule/treasure/enhancement.md):'
    - effect: '- You can target one additional ally within [distance](../../../../rule/combat/distance.md). - You can end one effect on a target that is ended by a [saving throw](../../../../rule/general/saving-throw.md) or that ends at the end of their [turn](../../../../rule/combat/turn.md). - A [prone target](../../../../condition/prone.md) can stand up. - A target can spend 1 additional [Recovery](../../../../rule/health/recoveries.md).'
feature_type: ability
flavor: Your divine energy restores the righteous.
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Maneuver](../../../../rule/combat/turn.md)'
    class: conduit
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effects:
        - effect: The target can spend a [Recovery](../../../../rule/health/recoveries.md).
          name: Effect
        - cost: Spend 1+ Piety
          effect: 'For each piety spent, choose one of the following [enhancements](../../../../rule/treasure/enhancement.md):'
        - effect: '- You can target one additional ally within [distance](../../../../rule/combat/distance.md). - You can end one effect on a target that is ended by a [saving throw](../../../../rule/general/saving-throw.md) or that ends at the end of their [turn](../../../../rule/combat/turn.md). - A [prone target](../../../../condition/prone.md) can stand up. - A target can spend 1 additional [Recovery](../../../../rule/health/recoveries.md).'
    flavor: Your divine energy restores the righteous.
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "1"
    name: Healing Grace
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/healing-grace
    target: Self or one ally
    type: ability
name: Healing Grace
target: Self or one ally
type: feature
usage: '[Maneuver](../../../../rule/combat/turn.md)'
```
