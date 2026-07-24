---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: tactician
cost: 5 Focus
cost_amount: "5"
cost_resource: Focus
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 5 + R damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
      tier2: 9 + R damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
      tier3: 12 + R damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
    - effect: One ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
      name: Effect
feature_type: ability
file_basename: ive-got-your-back
file_dpath: feature/ability/tactician/level-2
flavor: Your enemy will think twice about attacking your friend.
item_id: ive-got-your-back
item_name: I've Got Your Back
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "2"
name: I've Got Your Back
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-2/ive-got-your-back
source: mcdm.heroes.v1
subclass: mastermind
target: One creature
tier1: 5 + R damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
tier2: 9 + R damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
tier3: 12 + R damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
type: ability
---

```ds-feature
cost: 5 Focus
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 5 + R damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
      tier2: 9 + R damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
      tier3: 12 + R damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
    - effect: One ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
      name: Effect
feature_type: ability
flavor: Your enemy will think twice about attacking your friend.
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: tactician
    cost: 5 Focus
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
    effects:
        - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
          tier1: 5 + R damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
          tier2: 9 + R damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
          tier3: 12 + R damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
        - effect: One ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
          name: Effect
    flavor: Your enemy will think twice about attacking your friend.
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "2"
    name: I've Got Your Back
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-2/ive-got-your-back
    subclass: mastermind
    target: One creature
    tier1: 5 + R damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
    tier2: 9 + R damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
    tier3: 12 + R damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
    type: ability
name: I've Got Your Back
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
