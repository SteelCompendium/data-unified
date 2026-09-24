---
file_basename: stacking-effects
file_dpath: rule/combat
item_id: stacking-effects
item_name: Stacking Unique Effects
name: Stacking Unique Effects
scc: mcdm.heroes.v1/rule.combat/stacking-effects
source: mcdm.heroes.v1
type: rule
---

The unique effects of different abilities are combined—effectively stacking on top of each other—if their durations and targets overlap. However, the effects of the same ability used multiple times don't stack. Instead, the most impactful effect—such as the highest [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties)—from each use of the ability applies. The most recently used ability applies for determining duration.

For example, the [null's](scc.v1:mcdm.heroes.v1/class/null) [Null Field](scc.v1:mcdm.heroes.v1/feature.null.level-1/null-field) ability reduces the [potencies](scc.v1:mcdm.heroes.v1/rule.character/potency) of enemies within the field by 1. If two allied [nulls](scc.v1:mcdm.heroes.v1/class/null) each have their [Null Field](scc.v1:mcdm.heroes.v1/feature.null.level-1/null-field) ability active and an enemy cultist is targeted by both abilities, that cultist's [potencies](scc.v1:mcdm.heroes.v1/rule.character/potency) are reduced by 1, not by 2.

Different effects that impose the same [condition](scc.v1:mcdm.heroes.v1/rule.combat/condition) (see [Conditions](scc.v1:mcdm.heroes.v1/rule.combat/condition) below) don't stack to impose the [condition](scc.v1:mcdm.heroes.v1/rule.combat/condition) twice. For instance, if a hero is targeted by numerous creatures whose abilities cause a target to become [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (imposing a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on the target's [power rolls](scc.v1:mcdm.heroes.v1/rule.dice/power-roll)), the target isn't [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) twice to impose a double [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on those rolls. A character who is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by an enemy can't be [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) again by another enemy. The same holds true for game effects that aren't [conditions](scc.v1:mcdm.heroes.v1/rule.combat/condition). For example, if a hero is targeted by multiple abilities or effects that can halve their [recovery value](scc.v1:mcdm.heroes.v1/rule.health/recoveries), the hero's [recovery value](scc.v1:mcdm.heroes.v1/rule.health/recoveries) is halved only once.
