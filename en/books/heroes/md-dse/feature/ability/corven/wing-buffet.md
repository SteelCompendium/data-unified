---
action_type: Main action
distance: 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 damage
      tier2: 6 damage
      tier3: 8 damage
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares before or after making the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
      name: Effect
feature_type: ability
file_basename: wing-buffet
file_dpath: feature/ability/corven
flavor: Foes who try to close in around you do so at their peril.
item_id: wing-buffet
item_name: Wing Buffet
keywords:
    - Area
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
kit: corven
name: Wing Buffet
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.corven/wing-buffet
source: mcdm.heroes.v1
subtype: signature
target: Each enemy in the area
tier1: 3 damage
tier2: 6 damage
tier3: 8 damage
type: ability
---

```ds-feature
distance: 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 damage
      tier2: 6 damage
      tier3: 8 damage
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares before or after making the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
      name: Effect
feature_type: ability
flavor: Foes who try to close in around you do so at their peril.
keywords:
    - Area
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
metadata:
    action_type: Main action
    distance: 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effects:
        - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 3 damage
          tier2: 6 damage
          tier3: 8 damage
        - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares before or after making the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
          name: Effect
    flavor: Foes who try to close in around you do so at their peril.
    keywords:
        - Area
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Weapon
    kit: corven
    name: Wing Buffet
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.corven/wing-buffet
    subtype: signature
    target: Each enemy in the area
    tier1: 3 damage
    tier2: 6 damage
    tier3: 8 damage
    type: ability
name: Wing Buffet
target: Each enemy in the area
type: feature
usage: Main action
```
