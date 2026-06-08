---
action_type: Maneuver
class: tactician
distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: The target is marked by you until the end of the encounter, until you are [dying](scc:mcdm.heroes.v1/rule.health/dying), or until you use this ability again. You can willingly end your mark on a creature (no action required), and if another [tactician](scc:mcdm.heroes.v1/class/tactician) marks a creature, your mark on that creature ends. When a creature marked by you is reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina), you can use a free [triggered action](scc:mcdm.heroes.v1/rule.combat/triggered-action) to mark a new target within [distance](scc:mcdm.heroes.v1/rule.combat/distance).
flavor: You draw your allies' attention to a specific foe—with devastating effect.
keywords:
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Mark
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/mark
target: One creature
type: ability
---


*You draw your allies' attention to a specific foe—with devastating effect.*

| **[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)**       |        **Maneuver** |
|------------------|--------------------:|
| **📏 [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10** | **🎯 One creature** |

**Effect:** The target is marked by you until the end of the encounter, until you are [dying](scc:mcdm.heroes.v1/rule.health/dying), or until you use this ability again. You can willingly end your mark on a creature (no action required), and if another [tactician](scc:mcdm.heroes.v1/class/tactician) marks a creature, your mark on that creature ends. When a creature marked by you is reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina), you can use a free [triggered action](scc:mcdm.heroes.v1/rule.combat/triggered-action) to mark a new target within [distance](scc:mcdm.heroes.v1/rule.combat/distance).

You can initially mark only one creature using this ability, though other [tactician](scc:mcdm.heroes.v1/class/tactician) abilities allow you to mark additional creatures at the same time. The mastermind [tactical doctrine](scc:mcdm.heroes.v1/feature.tactician.level-1/tactical-doctrine)'s [Anticipation](scc:mcdm.heroes.v1/feature.tactician.level-5/anticipation) feature allows you to target additional creatures with this ability starting at 5th level.

While a creature marked by you is within your [line of effect](scc:mcdm.heroes.v1/rule.combat/line-of-effect), you and allies within your [line of effect](scc:mcdm.heroes.v1/rule.combat/line-of-effect) gain an [edge](scc:mcdm.heroes.v1/rule.dice/edge) on [power rolls](scc:mcdm.heroes.v1/rule.dice/power-roll) made against that creature. Additionally, whenever you or any ally uses an ability to deal [rolled damage](scc:mcdm.heroes.v1/rule.damage/rolled-damage) to a creature marked by you, you can spend 1 focus to gain one of the following benefits as a free [triggered action](scc:mcdm.heroes.v1/rule.combat/triggered-action):

- The ability deals extra damage equal to twice your [Reason](scc:mcdm.heroes.v1/rule.character/reason) score.
- The creature dealing the damage can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries).
- The creature dealing the damage can [shift](scc:mcdm.heroes.v1/movement/shifting) up to a number of squares equal to your [Reason](scc:mcdm.heroes.v1/rule.character/reason) score.
- If you damage a creature marked by you with a [melee](scc:mcdm.heroes.v1/rule.combat/melee) ability, the creature is [taunted](scc:mcdm.heroes.v1/condition/taunted) by you until the end of their next [turn](scc:mcdm.heroes.v1/rule.combat/turn).

You can't gain more than one benefit from the same trigger.
