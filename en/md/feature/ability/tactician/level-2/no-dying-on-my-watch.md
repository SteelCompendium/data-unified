---
action_type: Triggered
class: tactician
cost: 5 Focus
distance: Ranged 5
effect: You move up to your [speed](scc:mcdm.heroes.v1/rule.character/speed) toward the triggering ally, ending this movement adjacent to them or in the nearest square if you can't reach an adjacent square. The triggering ally can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries) and gains 5 [temporary Stamina](scc:mcdm.heroes.v1/rule.health/temporary-stamina) for each enemy you came adjacent to during the move. You then make a [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll) against the target.
flavor: You prioritize saving an ally over your own safety.
keywords:
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "2"
name: No Dying on My Watch
scc: mcdm.heroes.v1/feature.ability.tactician.level-2/no-dying-on-my-watch
subtype: triggered
target: One enemy
trigger: The target deals damage to an ally.
type: ability
---


*You prioritize saving an ally over your own safety.*

| **Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |    **Triggered** |
|----------------------------|-----------------:|
| **📏 Ranged 5**            | **🎯 One enemy** |

**Trigger:** The target deals damage to an ally.

**Effect:** You move up to your [speed](scc:mcdm.heroes.v1/rule.character/speed) toward the triggering ally, ending this movement adjacent to them or in the nearest square if you can't reach an adjacent square. The triggering ally can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries) and gains 5 [temporary Stamina](scc:mcdm.heroes.v1/rule.health/temporary-stamina) for each enemy you came adjacent to during the move. You then make a [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll) against the target.

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might):**

- **≤11:** R < WEAK, the target is [frightened](scc:mcdm.heroes.v1/condition/frightened) of the triggering ally (save ends)
- **12-16:** R < AVERAGE, the target is [frightened](scc:mcdm.heroes.v1/condition/frightened) of the triggering ally (save ends)
- **17+:** R < STRONG, the target is [frightened](scc:mcdm.heroes.v1/condition/frightened) of the triggering ally (save ends)
