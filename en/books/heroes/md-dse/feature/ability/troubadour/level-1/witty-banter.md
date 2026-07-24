---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 4 + P psychic damage
      tier2: 5 + P psychic damage
      tier3: 7 + P psychic damage
    - effect: One ally within 10 squares of you can end one effect on them that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Effect
    - cost: Spend 1 Drama
      effect: The chosen ally can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
file_basename: witty-banter
file_dpath: feature/ability/troubadour/level-1
flavor: A lyrical (and physical) jab insults an enemy and inspires an ally.
item_id: witty-banter
item_name: Witty Banter
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Witty Banter
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/witty-banter
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 4 + P psychic damage
tier2: 5 + P psychic damage
tier3: 7 + P psychic damage
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 4 + P psychic damage
      tier2: 5 + P psychic damage
      tier3: 7 + P psychic damage
    - effect: One ally within 10 squares of you can end one effect on them that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Effect
    - cost: Spend 1 Drama
      effect: The chosen ally can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
flavor: A lyrical (and physical) jab insults an enemy and inspires an ally.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: troubadour
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
    effects:
        - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
          tier1: 4 + P psychic damage
          tier2: 5 + P psychic damage
          tier3: 7 + P psychic damage
        - effect: One ally within 10 squares of you can end one effect on them that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
          name: Effect
        - cost: Spend 1 Drama
          effect: The chosen ally can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    flavor: A lyrical (and physical) jab insults an enemy and inspires an ally.
    keywords:
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Witty Banter
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/witty-banter
    subtype: signature
    target: One creature
    tier1: 4 + P psychic damage
    tier2: 5 + P psychic damage
    tier3: 7 + P psychic damage
    type: ability
name: Witty Banter
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
