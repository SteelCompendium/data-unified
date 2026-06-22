---
action_type: Main action
class: shadow
cost: 5 Insight
cost_amount: "5"
cost_resource: Insight
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: You attach a small bomb to a creature. If you are hidden from the creature, they don't notice the bomb and you remain hidden. The creature otherwise notices the bomb and can disarm and remove it as a main action. If they don't, at the end of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), the bomb detonates. When the bomb detonates, you make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) targeting each enemy within 2 squares of it.
feature_type: ability
file_basename: sticky-bomb
file_dpath: feature/ability/shadow/level-2
flavor: Explosives are best when they're attached to an enemy.
item_id: sticky-bomb
item_name: Sticky Bomb
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "2"
name: Sticky Bomb
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-2/sticky-bomb
source: mcdm.heroes.v1
subclass: caustic-alchemy
target: One creature
tier1: 4 + A fire damage
tier2: 7 + A fire damage
tier3: 11 + A fire damage
type: ability
---

```ds-feature
cost: 5 Insight
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: You attach a small bomb to a creature. If you are hidden from the creature, they don't notice the bomb and you remain hidden. The creature otherwise notices the bomb and can disarm and remove it as a main action. If they don't, at the end of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), the bomb detonates. When the bomb detonates, you make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) targeting each enemy within 2 squares of it.
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + A fire damage
      tier2: 7 + A fire damage
      tier3: 11 + A fire damage
feature_type: ability
flavor: Explosives are best when they're attached to an enemy.
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Main action
    class: shadow
    cost: 5 Insight
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: You attach a small bomb to a creature. If you are hidden from the creature, they don't notice the bomb and you remain hidden. The creature otherwise notices the bomb and can disarm and remove it as a main action. If they don't, at the end of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), the bomb detonates. When the bomb detonates, you make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) targeting each enemy within 2 squares of it.
    flavor: Explosives are best when they're attached to an enemy.
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "2"
    name: Sticky Bomb
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-2/sticky-bomb
    subclass: caustic-alchemy
    target: One creature
    tier1: 4 + A fire damage
    tier2: 7 + A fire damage
    tier3: 11 + A fire damage
    type: ability
name: Sticky Bomb
target: One creature
type: feature
usage: Main action
```
