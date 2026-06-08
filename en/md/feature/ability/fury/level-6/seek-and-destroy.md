---
action_type: Main action
class: fury
cost: 9 Ferocity
distance: Melee 1
effect: You [shift](scc:mcdm.heroes.v1/movement/shifting) up to your [speed](scc:mcdm.heroes.v1/rule.character/speed).
flavor: You break through the enemy lines to make an example.
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "6"
name: Seek and Destroy
scc: mcdm.heroes.v1/feature.ability.fury.level-6/seek-and-destroy
target: One creature
type: ability
---


*You break through the enemy lines to make an example.*

| **Melee, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|---------------------------|--------------------:|
| **📏 Melee 1**            | **🎯 One creature** |

**Effect:** You [shift](scc:mcdm.heroes.v1/movement/shifting) up to your [speed](scc:mcdm.heroes.v1/rule.character/speed).

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 4 + M damage; P < WEAK, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
- **12-16:** 6 + M damage; P < AVERAGE, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
- **17+:** 10 + M damage; P < STRONG, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)

**Effect:** If a target who is not a leader or solo creature is [winded](scc:mcdm.heroes.v1/rule.health/winded) by this [strike](scc:mcdm.heroes.v1/rule.combat/strike), they are reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) and you choose an enemy within 5 squares of you. If that enemy has P < AVERAGE, they are [frightened](scc:mcdm.heroes.v1/condition/frightened) of you (save ends).
