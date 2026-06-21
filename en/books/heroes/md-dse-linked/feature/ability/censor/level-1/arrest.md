---
action_type: Main action
class: censor
cost: 5 Wrath
cost_amount: "5"
cost_resource: Wrath
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: If the target makes a [strike](../../../../rule/combat/strike.md) against a creature while [grabbed](../../../../condition/grabbed.md) this way, you can spend 3 wrath to deal holy damage to them equal to your [Presence](../../../../rule/character/presence.md) score, then change the target of the [strike](../../../../rule/combat/strike.md) to another target within the [strike](../../../../rule/combat/strike.md)'s [distance](../../../../rule/combat/distance.md).
feature_type: ability
file_basename: arrest
file_dpath: feature/ability/censor/level-1
flavor: '"I got you, you son of a bitch."'
item_id: arrest
item_name: Arrest
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Arrest
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.censor.level-1/arrest
source: mcdm.heroes.v1
target: One creature
tier1: 6 + M holy damage; [grabbed](../../../../condition/grabbed.md)
tier2: 9 + M holy damage; [grabbed](../../../../condition/grabbed.md)
tier3: 13 + M holy damage; [grabbed](../../../../condition/grabbed.md)
type: ability
---

```ds-feature
cost: 5 Wrath
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: If the target makes a [strike](../../../../rule/combat/strike.md) against a creature while [grabbed](../../../../condition/grabbed.md) this way, you can spend 3 wrath to deal holy damage to them equal to your [Presence](../../../../rule/character/presence.md) score, then change the target of the [strike](../../../../rule/combat/strike.md) to another target within the [strike](../../../../rule/combat/strike.md)'s [distance](../../../../rule/combat/distance.md).
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 6 + M holy damage; [grabbed](../../../../condition/grabbed.md)
      tier2: 9 + M holy damage; [grabbed](../../../../condition/grabbed.md)
      tier3: 13 + M holy damage; [grabbed](../../../../condition/grabbed.md)
feature_type: ability
flavor: '"I got you, you son of a bitch."'
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: censor
    cost: 5 Wrath
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: If the target makes a [strike](../../../../rule/combat/strike.md) against a creature while [grabbed](../../../../condition/grabbed.md) this way, you can spend 3 wrath to deal holy damage to them equal to your [Presence](../../../../rule/character/presence.md) score, then change the target of the [strike](../../../../rule/combat/strike.md) to another target within the [strike](../../../../rule/combat/strike.md)'s [distance](../../../../rule/combat/distance.md).
    flavor: '"I got you, you son of a bitch."'
    keywords:
        - Magic
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Arrest
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/arrest
    target: One creature
    tier1: 6 + M holy damage; [grabbed](../../../../condition/grabbed.md)
    tier2: 9 + M holy damage; [grabbed](../../../../condition/grabbed.md)
    tier3: 13 + M holy damage; [grabbed](../../../../condition/grabbed.md)
    type: ability
name: Arrest
target: One creature
type: feature
usage: Main action
```
