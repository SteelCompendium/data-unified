---
file_basename: power-roll
file_dpath: rule/dice
item_id: power-roll
item_name: Power Rolls
name: Power Rolls
scc: mcdm.heroes.v1/rule.dice/power-roll
source: mcdm.heroes.v1
type: rule
---

Whenever a hero or other creature in the game attempts a task with an uncertain outcome, such as attacking a foe, sneaking by a guard patrol without being seen, or persuading a queen to provide military aid, the creature makes a power roll to determine the outcome of their actions.

#### Types of Power Rolls

The game uses two types of power rolls. An **[ability roll](ability-roll.md)** is used when you use certain abilities to determine their impact. For instance, if a [fury](../../class/fury.md) uses their [Brutal Slam](../../feature/ability/fury/level-1/brutal-slam.md) ability to strike an enemy, their [ability roll](ability-roll.md) determines how much [damage](../damage/damage.md) the enemy takes and how far back the enemy is [pushed](../../movement/forced-movement.md). See Abilities for more information.

A **[test](../test/test.md)** is a power roll you make outside of using your abilities to affect or interact with the world around you. A [tactician](../../class/tactician.md) might not have an ability that lets them climb up the face of a cliff, so climbing is an activity they can attempt with a [test](../test/test.md). An [elementalist](../../class/elementalist.md) doesn't have an ability that lets them automatically intimidate a cultist into backing down from a fight, but they can make a [test](../test/test.md) if they want to try. See [Tests](../../chapter/tests.md) for more information.

> **Sapient Creatures**
>
> All creatures in the game are sentient, capable of sensing and reacting to the world around them. But only some creatures are sapient, possessed of advanced intellect and consciousness. Being sapient has nothing to do with a creature's [Reason](../character/reason.md) score, but is determined solely by whether a creature is capable of human-like levels of thought and emotion. The Director decides whether creatures are sapient for the purpose of being affected by abilities and features that affect only sapient or nonsapient creatures.

#### Making a Power Roll

When you make a power roll, you roll two ten-sided dice (usually noted as 2d10 in the rules) and add one of your [characteristics](../character/characteristic.md). The [characteristic](../character/characteristic.md) you add depends on the kind of roll you're making, as outlined in Abilities and [Tests](../test/test.md).

##### Downgrade a Power Roll

Whenever you make a power roll, you can downgrade it to select the outcome of a lower tier. For instance, if an ability has a tier 3 outcome that lets you impose the [restrained](../../condition/restrained.md) [condition](../combat/condition.md) on a creature, but the tier 2 outcome for that ability lets you impose the [slowed](../../condition/slowed.md) [condition](../combat/condition.md), you can use the tier 2 outcome if you would rather have the creature [slowed](../../condition/slowed.md) than [restrained](../../condition/restrained.md).

If you downgrade a [critical hit](../combat/critical-hit.md), you still get the extra action benefit of the [critical hit](../combat/critical-hit.md) (see [Critical Hit](../combat/critical-hit.md) in [Classes](../../chapter/classes.md)).

#### Edges and Banes

An archer standing on a castle wall fires down into a throng of enemies, hitting the mark each time thanks to their [high ground](../../movement/high-ground.md). A drunken bandit struggles to land blows on sober opponents as alcohol clouds their senses. Under certain circumstances, you need more than just a [characteristic](../character/characteristic.md) to represent the advantages and disadvantages that heroes, their enemies, and their allies might have.

##### Rolling With Edges and Banes

Under certain circumstances, you might have one or more [edges](edge.md) and [banes](bane.md) on the same roll. For instance, you might take a [bane](bane.md) when [weakened](../../condition/weakened.md) by poison, even as you gain an [edge](edge.md) for striking a [prone](../../condition/prone.md) creature. In general, [edges](edge.md) and [banes](bane.md) cancel each other out, resolving as follows:

- If you have an [edge](edge.md) and a [bane](bane.md), or if you have a double [edge](edge.md) and a double [bane](bane.md), the roll is made as usual without any [edges](edge.md) or [banes](bane.md).
- If you have a double [edge](edge.md) and just one [bane](bane.md), the roll is made with one [edge](edge.md), regardless of how many individual [edges](edge.md) contribute to the double [edge](edge.md).
- If you have a double [bane](bane.md) and just one [edge](edge.md), the roll is made with one [bane](bane.md), regardless of how many individual [banes](bane.md) contribute to the double [bane](bane.md).

##### When to Use Edges and Banes

The rules tell you when to modify a roll with an [edge](edge.md) or a [bane](bane.md). The Director can also modify rolls with [edges](edge.md) and [banes](bane.md) as a response to narrative or environmental circumstances. For instance, no rule specifically says that rain imposes a [bane](bane.md) on power rolls made to climb a stone wall. But it makes sense that rainy [conditions](../combat/condition.md) should make climbing that wall harder, so a Director should absolutely do so!

> **Why Cap?**
>
> We capped [edges](edge.md) and [banes](bane.md) at a maximum of two each for several reasons, including thinking about the narrative of those [penalties](bonuses-and-penalties.md). Every little advantage or disadvantage in a heroic story has diminishing returns, acknowledging that a creature can benefit or be hindered by short-term circumstances only so much. For example, a character who is [prone](../../condition/prone.md) and [weakened](../../condition/weakened.md) by poison already finds it difficult to attack—so that becoming [restrained](../../condition/restrained.md) by a net can't really make it harder.

We also liked capping [edges](edge.md) and [banes](bane.md) at two because it keeps play quick. It's nice to not need to count beyond two positive or negative circumstances in a battle with a lot of effects flying around.

#### Automatic Tier Outcomes

Effects in the game sometimes allow a creature to obtain an automatic tier 1, 2, or 3 outcome on a power roll. Such effects supersede any [edges](edge.md), [banes](bane.md), [bonus](bonuses-and-penalties.md)es, or [penalties](bonuses-and-penalties.md) that might affect the roll. If you obtain an automatic [tier outcome](tier-outcome.md) and the power roll would have an additional effect if you get a specific roll, such as scoring a [critical hit](../combat/critical-hit.md) in combat, you can still make the roll to determine if you obtain the additional effect in addition to the automatic outcome.

If you are under multiple effects that each grant you a different automatic outcome, those effects cancel each other out and all automatic outcomes are ignored. If multiple effects grant you the same automatic outcome, you obtain that outcome.
