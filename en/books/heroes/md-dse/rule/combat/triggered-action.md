---
file_basename: triggered-action
file_dpath: rule/combat
item_id: triggered-action
item_name: Triggered Actions and Free Triggered Actions
name: Triggered Actions and Free Triggered Actions
scc: mcdm.heroes.v1/rule.combat/triggered-action
source: mcdm.heroes.v1
type: rule
---

Your hero might have one or more unique triggered actions, each of which has a specified trigger that allows the action to be used. You can use one triggered action per round, either on your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) or another creature's [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), but only when the action's trigger occurs. For instance, a [fury](scc.v1:mcdm.heroes.v1/class/fury) hero can use the [Lines of Force](scc.v1:mcdm.heroes.v1/feature.ability.fury.level-1/lines-of-force) triggered action to [force move](scc.v1:mcdm.heroes.v1/movement/forced-movement) a target, but only after an enemy has first tried to [force move](scc.v1:mcdm.heroes.v1/movement/forced-movement) the [fury](scc.v1:mcdm.heroes.v1/class/fury) or another nearby creature.

A free triggered action follows the same rules as a triggered action, but it doesn't count against your limit of one triggered action per round. For instance, a [shadow](scc.v1:mcdm.heroes.v1/class/shadow) hero can use their [Hesitation Is Weakness](scc.v1:mcdm.heroes.v1/feature.ability.shadow.level-1/hesitation-is-weakness) ability to take their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) in response to the trigger of another hero ending their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). But because that ability is a free triggered action, the [shadow](scc.v1:mcdm.heroes.v1/class/shadow) can still use their In All This Confusion triggered action later in the round.

If multiple triggered actions occur in response to the same trigger, any heroes and other player-controlled creatures taking a triggered action or a free triggered action decide among themselves which of those triggered actions are resolved first. Then the Director decides the same for creatures they control.

Any effect that prevents you from using triggered actions also prevents you from using free triggered actions.
