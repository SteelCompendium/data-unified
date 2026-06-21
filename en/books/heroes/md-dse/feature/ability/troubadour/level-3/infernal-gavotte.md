---
action_type: Main action
class: troubadour
cost: 7 Drama
cost_amount: "7"
cost_resource: Drama
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effect: Each ally in the area can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares.
feature_type: ability
file_basename: infernal-gavotte
file_dpath: feature/ability/troubadour/level-3
flavor: A spicy performance lights a fire under your allies' feet.
item_id: infernal-gavotte
item_name: Infernal Gavotte
keywords:
    - Area
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
level: "3"
name: Infernal Gavotte
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-3/infernal-gavotte
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 5 fire damage; A < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier2: 7 fire damage; A < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier3: 10 fire damage; A < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
type: ability
---

```ds-feature
cost: 7 Drama
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: Each ally in the area can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares.
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 5 fire damage; A < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier2: 7 fire damage; A < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier3: 10 fire damage; A < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
feature_type: ability
flavor: A spicy performance lights a fire under your allies' feet.
keywords:
    - Area
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
metadata:
    action_type: Main action
    class: troubadour
    cost: 7 Drama
    distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effect: Each ally in the area can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares.
    flavor: A spicy performance lights a fire under your allies' feet.
    keywords:
        - Area
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Weapon
    level: "3"
    name: Infernal Gavotte
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-3/infernal-gavotte
    target: Each enemy in the area
    tier1: 5 fire damage; A < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier2: 7 fire damage; A < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier3: 10 fire damage; A < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    type: ability
name: Infernal Gavotte
target: Each enemy in the area
type: feature
usage: Main action
```
