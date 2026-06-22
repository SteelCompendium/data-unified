---
action_type: Main action
class: troubadour
cost: 9 Drama
cost_amount: "9"
cost_resource: Drama
distance: '[Melee](../../../../rule/combat/melee.md) 1'
feature_type: ability
file_basename: blood-on-the-stage
file_dpath: feature/ability/troubadour/level-6
flavor: It's love and blood or drama and blood. Either way, there's always blood.
item_id: blood-on-the-stage
item_name: Blood on the Stage
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "6"
name: Blood on the Stage
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-6/blood-on-the-stage
source: mcdm.heroes.v1
subclass: duelist
target: One creature or object
tier1: 12 + A damage; M < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
tier2: 18 + A damage; M < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
tier3: 24 + A damage; [bleeding](../../../../condition/bleeding.md) ([EoT](../../../../rule/combat/end-of-turn.md)), or if M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
type: ability
---

```ds-feature
cost: 9 Drama
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 12 + A damage; M < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
      tier2: 18 + A damage; M < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
      tier3: 24 + A damage; [bleeding](../../../../condition/bleeding.md) ([EoT](../../../../rule/combat/end-of-turn.md)), or if M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
feature_type: ability
flavor: It's love and blood or drama and blood. Either way, there's always blood.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: troubadour
    cost: 9 Drama
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    flavor: It's love and blood or drama and blood. Either way, there's always blood.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "6"
    name: Blood on the Stage
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-6/blood-on-the-stage
    subclass: duelist
    target: One creature or object
    tier1: 12 + A damage; M < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
    tier2: 18 + A damage; M < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
    tier3: 24 + A damage; [bleeding](../../../../condition/bleeding.md) ([EoT](../../../../rule/combat/end-of-turn.md)), or if M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
    type: ability
name: Blood on the Stage
target: One creature or object
type: feature
usage: Main action
```
