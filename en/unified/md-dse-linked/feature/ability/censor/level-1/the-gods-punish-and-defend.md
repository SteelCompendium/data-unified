---
action_type: Main action
class: censor
cost: 3 Wrath
cost_amount: "3"
cost_resource: Wrath
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: You can spend a [Recovery](../../../../rule/health/recoveries.md) to allow yourself or one ally within 10 squares to regain [Stamina](../../../../rule/health/stamina.md) equal to your [recovery value](../../../../rule/health/recoveries.md).
feature_type: ability
file_basename: the-gods-punish-and-defend
file_dpath: feature/ability/censor/level-1
flavor: You channel holy energy to smite a foe and heal an ally.
item_id: the-gods-punish-and-defend
item_name: The Gods Punish and Defend
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: The Gods Punish and Defend
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.censor.level-1/the-gods-punish-and-defend
source: mcdm.heroes.v1
target: One creature or object
tier1: 5 + M holy damage
tier2: 8 + M holy damage
tier3: 11 + M holy damage
type: ability
---

```ds-feature
cost: 3 Wrath
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: You can spend a [Recovery](../../../../rule/health/recoveries.md) to allow yourself or one ally within 10 squares to regain [Stamina](../../../../rule/health/stamina.md) equal to your [recovery value](../../../../rule/health/recoveries.md).
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 5 + M holy damage
      tier2: 8 + M holy damage
      tier3: 11 + M holy damage
feature_type: ability
flavor: You channel holy energy to smite a foe and heal an ally.
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: censor
    cost: 3 Wrath
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: You can spend a [Recovery](../../../../rule/health/recoveries.md) to allow yourself or one ally within 10 squares to regain [Stamina](../../../../rule/health/stamina.md) equal to your [recovery value](../../../../rule/health/recoveries.md).
    flavor: You channel holy energy to smite a foe and heal an ally.
    keywords:
        - Magic
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: The Gods Punish and Defend
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/the-gods-punish-and-defend
    target: One creature or object
    tier1: 5 + M holy damage
    tier2: 8 + M holy damage
    tier3: 11 + M holy damage
    type: ability
name: The Gods Punish and Defend
target: One creature or object
type: feature
usage: Main action
```
