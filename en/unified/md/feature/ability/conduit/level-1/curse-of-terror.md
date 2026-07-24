---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 5 Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 6 + I holy damage; I < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier2: 9 + I holy damage; I < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier3: 13 + I holy damage; I < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
flavor: Fear of divine judgment overwhelms your foe.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Curse of Terror
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/curse-of-terror
target: One creature
tier1: 6 + I holy damage; I < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier2: 9 + I holy damage; I < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier3: 13 + I holy damage; I < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
type: ability
---


*Fear of divine judgment overwhelms your foe.*

| **Magic, [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)**  |                      **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|----------------------------|-------------------------------------:|
| **📏 [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10**           |                  **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition):**

- **≤11:** 6 + I holy damage; I < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
- **12-16:** 9 + I holy damage; I < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
- **17+:** 13 + I holy damage; I < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
