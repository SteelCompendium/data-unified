---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: fury
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
feature_type: ability
file_basename: to-the-uttermost-end
file_dpath: feature/ability/fury/level-1
flavor: You gut your life force to ensure a foe's demise.
item_id: to-the-uttermost-end
item_name: To the Uttermost End
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: To the Uttermost End
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.fury.level-1/to-the-uttermost-end
source: mcdm.heroes.v1
spend: '1+ Ferocity: While you are [winded](../../../../rule/health/winded.md), this ability deals an extra 1d6 damage for each ferocity spent. While you are [dying](../../../../rule/health/dying.md), it deals an extra 1d10 damage for each ferocity spent. In either case, you lose 1d6 [Stamina](../../../../rule/health/stamina.md) after making this [strike](../../../../rule/combat/strike.md).'
target: One creature
tier1: 7 + M damage
tier2: 11 + M damage
tier3: 16 + M damage
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 7 + M damage
      tier2: 11 + M damage
      tier3: 16 + M damage
    - effect: '1+ Ferocity: While you are [winded](../../../../rule/health/winded.md), this ability deals an extra 1d6 damage for each ferocity spent. While you are [dying](../../../../rule/health/dying.md), it deals an extra 1d10 damage for each ferocity spent. In either case, you lose 1d6 [Stamina](../../../../rule/health/stamina.md) after making this [strike](../../../../rule/combat/strike.md).'
      name: Spend
feature_type: ability
flavor: You gut your life force to ensure a foe's demise.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: fury
    cost: 5 Ferocity
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    flavor: You gut your life force to ensure a foe's demise.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: To the Uttermost End
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/to-the-uttermost-end
    spend: '1+ Ferocity: While you are [winded](../../../../rule/health/winded.md), this ability deals an extra 1d6 damage for each ferocity spent. While you are [dying](../../../../rule/health/dying.md), it deals an extra 1d10 damage for each ferocity spent. In either case, you lose 1d6 [Stamina](../../../../rule/health/stamina.md) after making this [strike](../../../../rule/combat/strike.md).'
    target: One creature
    tier1: 7 + M damage
    tier2: 11 + M damage
    tier3: 16 + M damage
    type: ability
name: To the Uttermost End
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
