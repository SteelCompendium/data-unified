---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 9 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed).
      name: Effect
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 4 + M damage; P < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier2: 6 + M damage; P < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier3: 10 + M damage; P < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    - effect: If a target who is not a leader or solo creature is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) by this [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and you choose an enemy within 5 squares of you. If that enemy has P < AVERAGE, they are [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you (save ends).
      name: Effect
flavor: You break through the enemy lines to make an example.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "6"
name: Seek and Destroy
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-6/seek-and-destroy
subclass: reaver
target: One creature
tier1: 4 + M damage; P < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier2: 6 + M damage; P < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier3: 10 + M damage; P < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
type: ability
---


*You break through the enemy lines to make an example.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|---------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature** |

**Effect:** You [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed).

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 4 + M damage; P < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
- **12-16:** 6 + M damage; P < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
- **17+:** 10 + M damage; P < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)

**Effect:** If a target who is not a leader or solo creature is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) by this [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and you choose an enemy within 5 squares of you. If that enemy has P < AVERAGE, they are [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you (save ends).
