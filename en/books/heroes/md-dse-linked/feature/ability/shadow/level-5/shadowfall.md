---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: shadow
cost: 9 Insight
cost_amount: "9"
cost_resource: Insight
distance: 10 x 1 line within 1
effects:
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 10 damage
      tier2: 14 damage
      tier3: 20 damage
    - effect: You disappear before making the [power roll](../../../../rule/dice/power-roll.md). After the [power roll](../../../../rule/dice/power-roll.md) is resolved, you appear in the first unoccupied space at the far end of the line.
      name: Effect
feature_type: ability
file_basename: shadowfall
file_dpath: feature/ability/shadow/level-5
flavor: You vanish. They fall. You reappear.
item_id: shadowfall
item_name: Shadowfall
keywords:
    - Area
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
level: "5"
name: Shadowfall
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-5/shadowfall
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 10 damage
tier2: 14 damage
tier3: 20 damage
type: ability
---

```ds-feature
cost: 9 Insight
distance: 10 x 1 line within 1
effects:
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 10 damage
      tier2: 14 damage
      tier3: 20 damage
    - effect: You disappear before making the [power roll](../../../../rule/dice/power-roll.md). After the [power roll](../../../../rule/dice/power-roll.md) is resolved, you appear in the first unoccupied space at the far end of the line.
      name: Effect
feature_type: ability
flavor: You vanish. They fall. You reappear.
keywords:
    - Area
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: shadow
    cost: 9 Insight
    distance: 10 x 1 line within 1
    effects:
        - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
          tier1: 10 damage
          tier2: 14 damage
          tier3: 20 damage
        - effect: You disappear before making the [power roll](../../../../rule/dice/power-roll.md). After the [power roll](../../../../rule/dice/power-roll.md) is resolved, you appear in the first unoccupied space at the far end of the line.
          name: Effect
    flavor: You vanish. They fall. You reappear.
    keywords:
        - Area
        - '[Melee](../../../../rule/combat/melee.md)'
        - Weapon
    level: "5"
    name: Shadowfall
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-5/shadowfall
    target: Each enemy in the area
    tier1: 10 damage
    tier2: 14 damage
    tier3: 20 damage
    type: ability
name: Shadowfall
target: Each enemy in the area
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
