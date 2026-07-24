---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
cost: 7 Drama
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 5 fire damage; A < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier2: 7 fire damage; A < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier3: 10 fire damage; A < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    - effect: Each ally in the area can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares.
      name: Effect
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
---


*A spicy performance lights a fire under your allies' feet.*

| **Area, Magic, [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), Weapon** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|--------------------------------|------------------------------:|
| **📏 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)**                 | **🎯 Each enemy in the area** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence):**

- **≤11:** 5 fire damage; A < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
- **12-16:** 7 fire damage; A < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
- **17+:** 10 fire damage; A < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)

**Effect:** Each ally in the area can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares.
