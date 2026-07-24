---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 5 Wrath
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 8 + M holy damage; P < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier2: 12 + M holy damage; P < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier3: 15 + M holy damage; P < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    - effect: If the target is already [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you or another creature and this ability would frighten them again, they instead take psychic damage equal to twice your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score.
      name: Effect
flavor: I am but a vessel. Your own deeds weigh upon you.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "2"
name: It Is Justice You Fear
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.censor.level-2/it-is-justice-you-fear
subclass: exorcist
target: One creature
tier1: 8 + M holy damage; P < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier2: 12 + M holy damage; P < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier3: 15 + M holy damage; P < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
type: ability
---


*I am but a vessel. Your own deeds weigh upon you.*

| **Magic, [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|---------------------------|--------------------:|
| **📏 [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10**          | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 8 + M holy damage; P < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
- **12-16:** 12 + M holy damage; P < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
- **17+:** 15 + M holy damage; P < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)

**Effect:** If the target is already [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you or another creature and this ability would frighten them again, they instead take psychic damage equal to twice your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score.
