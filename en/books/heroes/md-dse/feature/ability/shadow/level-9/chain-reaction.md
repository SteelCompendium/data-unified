---
action_type: Main action
class: shadow
cost: 11 Insight
cost_amount: "11"
cost_resource: Insight
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: Each enemy within 3 squares of the target who is not currently targeted by this ability also becomes targeted by this ability. This effect continues until there are no more available targets. The ability deals acid, fire, or poison damage (your choice).
feature_type: ability
file_basename: chain-reaction
file_dpath: feature/ability/shadow/level-9
flavor: One explosion, an offense. Three explosions, an assault. Nine explosions, a celebration.
item_id: chain-reaction
item_name: Chain Reaction
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "9"
name: Chain Reaction
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-9/chain-reaction
source: mcdm.heroes.v1
subclass: caustic-alchemy
target: One creature or object
tier1: 7 damage
tier2: 10 damage
tier3: 15 damage
type: ability
---

```ds-feature
cost: 11 Insight
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: Each enemy within 3 squares of the target who is not currently targeted by this ability also becomes targeted by this ability. This effect continues until there are no more available targets. The ability deals acid, fire, or poison damage (your choice).
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 7 damage
      tier2: 10 damage
      tier3: 15 damage
feature_type: ability
flavor: One explosion, an offense. Three explosions, an assault. Nine explosions, a celebration.
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Main action
    class: shadow
    cost: 11 Insight
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: Each enemy within 3 squares of the target who is not currently targeted by this ability also becomes targeted by this ability. This effect continues until there are no more available targets. The ability deals acid, fire, or poison damage (your choice).
    flavor: One explosion, an offense. Three explosions, an assault. Nine explosions, a celebration.
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "9"
    name: Chain Reaction
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-9/chain-reaction
    subclass: caustic-alchemy
    target: One creature or object
    tier1: 7 damage
    tier2: 10 damage
    tier3: 15 damage
    type: ability
name: Chain Reaction
target: One creature or object
type: feature
usage: Main action
```
