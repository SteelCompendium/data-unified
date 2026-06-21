---
action_type: Main action
class: troubadour
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effect: One ally within 10 squares of you can end one effect on them that is ended by a [saving throw](../../../../rule/general/saving-throw.md) or that ends at the end of their [turn](../../../../rule/combat/turn.md).
feature_type: ability
file_basename: witty-banter
file_dpath: feature/ability/troubadour/level-1
flavor: A lyrical (and physical) jab insults an enemy and inspires an ally.
item_id: witty-banter
item_name: Witty Banter
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
level: "1"
name: Witty Banter
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/witty-banter
source: mcdm.heroes.v1
spend: '1 Drama: The chosen ally can spend a [Recovery](../../../../rule/health/recoveries.md).'
subtype: signature
target: One creature
tier1: 4 + P psychic damage
tier2: 5 + P psychic damage
tier3: 7 + P psychic damage
type: ability
---

```ds-feature
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - effect: One ally within 10 squares of you can end one effect on them that is ended by a [saving throw](../../../../rule/general/saving-throw.md) or that ends at the end of their [turn](../../../../rule/combat/turn.md).
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 4 + P psychic damage
      tier2: 5 + P psychic damage
      tier3: 7 + P psychic damage
    - effect: '1 Drama: The chosen ally can spend a [Recovery](../../../../rule/health/recoveries.md).'
      name: Spend
feature_type: ability
flavor: A lyrical (and physical) jab insults an enemy and inspires an ally.
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: Main action
    class: troubadour
    distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
    effect: One ally within 10 squares of you can end one effect on them that is ended by a [saving throw](../../../../rule/general/saving-throw.md) or that ends at the end of their [turn](../../../../rule/combat/turn.md).
    flavor: A lyrical (and physical) jab insults an enemy and inspires an ally.
    keywords:
        - Magic
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
    level: "1"
    name: Witty Banter
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/witty-banter
    spend: '1 Drama: The chosen ally can spend a [Recovery](../../../../rule/health/recoveries.md).'
    subtype: signature
    target: One creature
    tier1: 4 + P psychic damage
    tier2: 5 + P psychic damage
    tier3: 7 + P psychic damage
    type: ability
name: Witty Banter
target: One creature
type: feature
usage: Main action
```
