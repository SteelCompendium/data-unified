---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 5 Ferocity
distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 2 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1; M < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier2: 5 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier3: 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    - effect: This ability deals your primordial [damage type](scc.v1:mcdm.heroes.v1/rule.damage/damage-type) (see [Stormwight Kits](scc.v1:mcdm.heroes.v1/feature.fury.stormwight-kits/kit-features)).
      name: Effect
flavor: The sound of the storm within you staggers your opponents.
keywords:
    - Area
    - Magic
level: "2"
name: Visceral Roar
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-2/visceral-roar
target: Each enemy in the area
tier1: 2 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1; M < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier2: 5 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier3: 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
type: ability
---


*The sound of the storm within you staggers your opponents.*

| **Area, Magic** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|-----------------|------------------------------:|
| **📏 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)**  | **🎯 Each enemy in the area** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 2 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1; M < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
- **12-16:** 5 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
- **17+:** 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)

**Effect:** This ability deals your primordial [damage type](scc.v1:mcdm.heroes.v1/rule.damage/damage-type) (see [Stormwight Kits](scc.v1:mcdm.heroes.v1/feature.fury.stormwight-kits/kit-features)).
