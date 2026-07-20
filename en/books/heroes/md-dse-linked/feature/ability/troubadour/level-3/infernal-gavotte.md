---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: troubadour
cost: 7 Drama
cost_amount: "7"
cost_resource: Drama
distance: 3 [burst](../../../../rule/combat/burst.md)
effect: Each ally in the area can [shift](../../../../movement/shifting.md) up to 2 squares.
feature_type: ability
file_basename: infernal-gavotte
file_dpath: feature/ability/troubadour/level-3
flavor: A spicy performance lights a fire under your allies' feet.
item_id: infernal-gavotte
item_name: Infernal Gavotte
keywords:
    - Area
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
level: "3"
name: Infernal Gavotte
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-3/infernal-gavotte
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 5 fire damage; A < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
tier2: 7 fire damage; A < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
tier3: 10 fire damage; A < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
type: ability
---

```ds-feature
cost: 7 Drama
distance: 3 [burst](../../../../rule/combat/burst.md)
effects:
    - effect: Each ally in the area can [shift](../../../../movement/shifting.md) up to 2 squares.
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 5 fire damage; A < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
      tier2: 7 fire damage; A < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
      tier3: 10 fire damage; A < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
feature_type: ability
flavor: A spicy performance lights a fire under your allies' feet.
keywords:
    - Area
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: troubadour
    cost: 7 Drama
    distance: 3 [burst](../../../../rule/combat/burst.md)
    effect: Each ally in the area can [shift](../../../../movement/shifting.md) up to 2 squares.
    flavor: A spicy performance lights a fire under your allies' feet.
    keywords:
        - Area
        - Magic
        - '[Melee](../../../../rule/combat/melee.md)'
        - Weapon
    level: "3"
    name: Infernal Gavotte
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-3/infernal-gavotte
    target: Each enemy in the area
    tier1: 5 fire damage; A < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
    tier2: 7 fire damage; A < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
    tier3: 10 fire damage; A < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
    type: ability
name: Infernal Gavotte
target: Each enemy in the area
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
