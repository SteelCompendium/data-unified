---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: elementalist
distance: 2 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 damage
      tier2: 5 damage
      tier3: 7 damage
    - effect: The ground beneath the area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies.
      name: Effect
flavor: A sudden storm of detritus assaults your foes and leaves them struggling to move.
keywords:
    - Area
    - Earth
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Unquiet Ground
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/unquiet-ground
subtype: signature
target: Each enemy in the area
tier1: 2 damage
tier2: 5 damage
tier3: 7 damage
type: ability
---


*A sudden storm of detritus assaults your foes and leaves them struggling to move.*

| **Area, Earth, Magic, [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|--------------------------------|------------------------------:|
| **📏 2 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10**        | **🎯 Each enemy in the area** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason):**

- **≤11:** 2 damage
- **12-16:** 5 damage
- **17+:** 7 damage

**Effect:** The ground beneath the area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies.
