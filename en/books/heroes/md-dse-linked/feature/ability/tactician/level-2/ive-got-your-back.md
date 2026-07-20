---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: tactician
cost: 5 Focus
cost_amount: "5"
cost_resource: Focus
distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
effect: One ally [adjacent](../../../../rule/combat/adjacent.md) to the target can spend a [Recovery](../../../../rule/health/recoveries.md).
feature_type: ability
file_basename: ive-got-your-back
file_dpath: feature/ability/tactician/level-2
flavor: Your enemy will think twice about attacking your friend.
item_id: ive-got-your-back
item_name: I've Got Your Back
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "2"
name: I've Got Your Back
power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-2/ive-got-your-back
source: mcdm.heroes.v1
subclass: mastermind
target: One creature
tier1: 5 + R damage; [taunted](../../../../condition/taunted.md) ([EoT](../../../../rule/combat/end-of-turn.md))
tier2: 9 + R damage; [taunted](../../../../condition/taunted.md) ([EoT](../../../../rule/combat/end-of-turn.md))
tier3: 12 + R damage; [taunted](../../../../condition/taunted.md) ([EoT](../../../../rule/combat/end-of-turn.md))
type: ability
---

```ds-feature
cost: 5 Focus
distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - effect: One ally [adjacent](../../../../rule/combat/adjacent.md) to the target can spend a [Recovery](../../../../rule/health/recoveries.md).
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: 5 + R damage; [taunted](../../../../condition/taunted.md) ([EoT](../../../../rule/combat/end-of-turn.md))
      tier2: 9 + R damage; [taunted](../../../../condition/taunted.md) ([EoT](../../../../rule/combat/end-of-turn.md))
      tier3: 12 + R damage; [taunted](../../../../condition/taunted.md) ([EoT](../../../../rule/combat/end-of-turn.md))
feature_type: ability
flavor: Your enemy will think twice about attacking your friend.
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: tactician
    cost: 5 Focus
    distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
    effect: One ally [adjacent](../../../../rule/combat/adjacent.md) to the target can spend a [Recovery](../../../../rule/health/recoveries.md).
    flavor: Your enemy will think twice about attacking your friend.
    keywords:
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "2"
    name: I've Got Your Back
    power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-2/ive-got-your-back
    subclass: mastermind
    target: One creature
    tier1: 5 + R damage; [taunted](../../../../condition/taunted.md) ([EoT](../../../../rule/combat/end-of-turn.md))
    tier2: 9 + R damage; [taunted](../../../../condition/taunted.md) ([EoT](../../../../rule/combat/end-of-turn.md))
    tier3: 12 + R damage; [taunted](../../../../condition/taunted.md) ([EoT](../../../../rule/combat/end-of-turn.md))
    type: ability
name: I've Got Your Back
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
