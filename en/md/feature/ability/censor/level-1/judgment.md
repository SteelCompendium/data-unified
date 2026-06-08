---
action_type: Maneuver
class: censor
distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: The target is judged by you until the end of the encounter, you use this ability again, you willingly end this effect (no action required), or another [censor](scc:mcdm.heroes.v1/class/censor) judges the target.
flavor: You utter a prayer that outlines your foe in holy energy.
keywords:
    - Magic
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Judgment
scc: mcdm.heroes.v1/feature.ability.censor.level-1/judgment
target: One enemy
type: ability
---


*You utter a prayer that outlines your foe in holy energy.*

| **Magic, [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)** |     **Maneuver** |
|-------------------|-----------------:|
| **📏 [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10**  | **🎯 One enemy** |

**Effect:** The target is judged by you until the end of the encounter, you use this ability again, you willingly end this effect (no action required), or another [censor](scc:mcdm.heroes.v1/class/censor) judges the target.

Whenever a creature judged by you uses a main action and is within your [line of effect](scc:mcdm.heroes.v1/rule.combat/line-of-effect), you can use a free [triggered action](scc:mcdm.heroes.v1/rule.combat/triggered-action) to deal holy damage equal to twice your [Presence](scc:mcdm.heroes.v1/rule.character/presence) score to them.

When a creature judged by you is reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina), you can use a free [triggered action](scc:mcdm.heroes.v1/rule.combat/triggered-action) to use this ability against a new target.

Additionally, you can spend 1 wrath to take one of the following free [triggered actions](scc:mcdm.heroes.v1/rule.combat/triggered-action):

- When an [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) creature judged by you starts to [shift](scc:mcdm.heroes.v1/movement/shifting), you make a [melee](scc:mcdm.heroes.v1/rule.combat/melee) [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them and their [speed](scc:mcdm.heroes.v1/rule.character/speed) becomes 0 until the end of the current [turn](scc:mcdm.heroes.v1/rule.combat/turn), preventing them from [shifting](scc:mcdm.heroes.v1/movement/shifting).
- When a creature judged by you within 10 squares makes a [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll), you cause them to take a [bane](scc:mcdm.heroes.v1/rule.dice/bane) on the roll.
- When a creature judged by you within 10 squares uses an ability with a [potency](scc:mcdm.heroes.v1/rule.character/potency) that targets only one creature, the [potency](scc:mcdm.heroes.v1/rule.character/potency) is reduced by 1 for that creature.
- If you damage a creature judged by you with a [melee](scc:mcdm.heroes.v1/rule.combat/melee) ability, the creature is [taunted](scc:mcdm.heroes.v1/condition/taunted) by you until the end of their next [turn](scc:mcdm.heroes.v1/rule.combat/turn).
  
You can choose only one free [triggered action](scc:mcdm.heroes.v1/rule.combat/triggered-action) option at a time, even if multiple options are triggered by the same effect.
