---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
      name: Effect
    - cost: Spend 1+ Piety
      effect: 'For each piety spent, choose one of the following [enhancements](scc.v1:mcdm.heroes.v1/rule.treasure/enhancement):'
    - effect: '- You can target one additional ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). - You can end one effect on a target that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). - A [prone target](scc.v1:mcdm.heroes.v1/condition/prone) can stand up. - A target can spend 1 additional [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).'
feature_type: ability
file_basename: healing-grace
file_dpath: feature/ability/conduit/level-1
flavor: Your divine energy restores the righteous.
item_id: healing-grace
item_name: Healing Grace
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Healing Grace
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/healing-grace
source: mcdm.heroes.v1
target: Self or one ally
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
      name: Effect
    - cost: Spend 1+ Piety
      effect: 'For each piety spent, choose one of the following [enhancements](scc.v1:mcdm.heroes.v1/rule.treasure/enhancement):'
    - effect: '- You can target one additional ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). - You can end one effect on a target that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). - A [prone target](scc.v1:mcdm.heroes.v1/condition/prone) can stand up. - A target can spend 1 additional [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).'
feature_type: ability
flavor: Your divine energy restores the righteous.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - effect: The target can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
          name: Effect
        - cost: Spend 1+ Piety
          effect: 'For each piety spent, choose one of the following [enhancements](scc.v1:mcdm.heroes.v1/rule.treasure/enhancement):'
        - effect: '- You can target one additional ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). - You can end one effect on a target that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). - A [prone target](scc.v1:mcdm.heroes.v1/condition/prone) can stand up. - A target can spend 1 additional [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).'
    flavor: Your divine energy restores the righteous.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Healing Grace
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/healing-grace
    target: Self or one ally
    type: ability
name: Healing Grace
target: Self or one ally
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
