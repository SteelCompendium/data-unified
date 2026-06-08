---
name: Power Rolls
scc: mcdm.heroes.v1/rule.dice/power-roll
type: rule
---

Whenever a hero or other creature in the game attempts a task with an uncertain outcome, such as attacking a foe, sneaking by a guard patrol without being seen, or persuading a queen to provide military aid, the creature makes a power roll to determine the outcome of their actions.

#### Types of Power Rolls

The game uses two types of power rolls. An **[ability roll](scc:mcdm.heroes.v1/rule.dice/ability-roll)** is used when you use certain abilities to determine their impact. For instance, if a [fury](scc:mcdm.heroes.v1/class/fury) uses their [Brutal Slam](scc:mcdm.heroes.v1/feature.ability.fury.level-1/brutal-slam) ability to strike an enemy, their [ability roll](scc:mcdm.heroes.v1/rule.dice/ability-roll) determines how much [damage](scc:mcdm.heroes.v1/rule.damage/damage) the enemy takes and how far back the enemy is pushed. See Abilities for more information.

A **[test](scc:mcdm.heroes.v1/rule.test/test)** is a power roll you make outside of using your abilities to affect or interact with the world around you. A [tactician](scc:mcdm.heroes.v1/class/tactician) might not have an ability that lets them climb up the face of a cliff, so climbing is an activity they can attempt with a [test](scc:mcdm.heroes.v1/rule.test/test). An [elementalist](scc:mcdm.heroes.v1/class/elementalist) doesn't have an ability that lets them automatically intimidate a cultist into backing down from a fight, but they can make a [test](scc:mcdm.heroes.v1/rule.test/test) if they want to try. See [Tests](scc:mcdm.heroes.v1/chapter/tests) for more information.

> **Sapient Creatures**
>
> All creatures in the game are sentient, capable of sensing and reacting to the world around them. But only some creatures are sapient, possessed of advanced intellect and consciousness. Being sapient has nothing to do with a creature's [Reason](scc:mcdm.heroes.v1/rule.character/reason) score, but is determined solely by whether a creature is capable of human-like levels of thought and emotion. The Director decides whether creatures are sapient for the purpose of being affected by abilities and features that affect only sapient or nonsapient creatures.

#### Making a Power Roll

When you make a power roll, you roll two ten-sided dice (usually noted as 2d10 in the rules) and add one of your [characteristics](scc:mcdm.heroes.v1/rule.character/characteristic). The [characteristic](scc:mcdm.heroes.v1/rule.character/characteristic) you add depends on the kind of roll you're making, as outlined in Abilities and [Tests](scc:mcdm.heroes.v1/rule.test/test).

##### Downgrade a Power Roll

Whenever you make a power roll, you can downgrade it to select the outcome of a lower tier. For instance, if an ability has a tier 3 outcome that lets you impose the [restrained](scc:mcdm.heroes.v1/condition/restrained) [condition](scc:mcdm.heroes.v1/rule.combat/condition) on a creature, but the tier 2 outcome for that ability lets you impose the [slowed](scc:mcdm.heroes.v1/condition/slowed) [condition](scc:mcdm.heroes.v1/rule.combat/condition), you can use the tier 2 outcome if you would rather have the creature [slowed](scc:mcdm.heroes.v1/condition/slowed) than [restrained](scc:mcdm.heroes.v1/condition/restrained).

If you downgrade a [critical hit](scc:mcdm.heroes.v1/rule.combat/critical-hit), you still get the extra action benefit of the [critical hit](scc:mcdm.heroes.v1/rule.combat/critical-hit) (see [Critical Hit](scc:mcdm.heroes.v1/rule.combat/critical-hit) in [Classes](scc:mcdm.heroes.v1/chapter/classes)).

#### Edges and Banes

An archer standing on a castle wall fires down into a throng of enemies, hitting the mark each time thanks to their [high ground](scc:mcdm.heroes.v1/movement/high-ground). A drunken bandit struggles to land blows on sober opponents as alcohol clouds their senses. Under certain circumstances, you need more than just a [characteristic](scc:mcdm.heroes.v1/rule.character/characteristic) to represent the advantages and disadvantages that heroes, their enemies, and their allies might have.

##### Rolling With Edges and Banes

Under certain circumstances, you might have one or more [edges](scc:mcdm.heroes.v1/rule.dice/edge) and [banes](scc:mcdm.heroes.v1/rule.dice/bane) on the same roll. For instance, you might take a [bane](scc:mcdm.heroes.v1/rule.dice/bane) when [weakened](scc:mcdm.heroes.v1/condition/weakened) by poison, even as you gain an [edge](scc:mcdm.heroes.v1/rule.dice/edge) for striking a [prone](scc:mcdm.heroes.v1/condition/prone) creature. In general, [edges](scc:mcdm.heroes.v1/rule.dice/edge) and [banes](scc:mcdm.heroes.v1/rule.dice/bane) cancel each other out, resolving as follows:

- If you have an [edge](scc:mcdm.heroes.v1/rule.dice/edge) and a [bane](scc:mcdm.heroes.v1/rule.dice/bane), or if you have a double [edge](scc:mcdm.heroes.v1/rule.dice/edge) and a double [bane](scc:mcdm.heroes.v1/rule.dice/bane), the roll is made as usual without any [edges](scc:mcdm.heroes.v1/rule.dice/edge) or [banes](scc:mcdm.heroes.v1/rule.dice/bane).
- If you have a double [edge](scc:mcdm.heroes.v1/rule.dice/edge) and just one [bane](scc:mcdm.heroes.v1/rule.dice/bane), the roll is made with one [edge](scc:mcdm.heroes.v1/rule.dice/edge), regardless of how many individual [edges](scc:mcdm.heroes.v1/rule.dice/edge) contribute to the double [edge](scc:mcdm.heroes.v1/rule.dice/edge).
- If you have a double [bane](scc:mcdm.heroes.v1/rule.dice/bane) and just one [edge](scc:mcdm.heroes.v1/rule.dice/edge), the roll is made with one [bane](scc:mcdm.heroes.v1/rule.dice/bane), regardless of how many individual [banes](scc:mcdm.heroes.v1/rule.dice/bane) contribute to the double [bane](scc:mcdm.heroes.v1/rule.dice/bane).

##### When to Use Edges and Banes

The rules tell you when to modify a roll with an [edge](scc:mcdm.heroes.v1/rule.dice/edge) or a [bane](scc:mcdm.heroes.v1/rule.dice/bane). The Director can also modify rolls with [edges](scc:mcdm.heroes.v1/rule.dice/edge) and [banes](scc:mcdm.heroes.v1/rule.dice/bane) as a response to narrative or environmental circumstances. For instance, no rule specifically says that rain imposes a [bane](scc:mcdm.heroes.v1/rule.dice/bane) on power rolls made to climb a stone wall. But it makes sense that rainy [conditions](scc:mcdm.heroes.v1/rule.combat/condition) should make climbing that wall harder, so a Director should absolutely do so!

> **Why Cap?**
>
> We capped [edges](scc:mcdm.heroes.v1/rule.dice/edge) and [banes](scc:mcdm.heroes.v1/rule.dice/bane) at a maximum of two each for several reasons, including thinking about the narrative of those [penalties](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties). Every little advantage or disadvantage in a heroic story has diminishing returns, acknowledging that a creature can benefit or be hindered by short-term circumstances only so much. For example, a character who is [prone](scc:mcdm.heroes.v1/condition/prone) and [weakened](scc:mcdm.heroes.v1/condition/weakened) by poison already finds it difficult to attack—so that becoming [restrained](scc:mcdm.heroes.v1/condition/restrained) by a net can't really make it harder.

We also liked capping [edges](scc:mcdm.heroes.v1/rule.dice/edge) and [banes](scc:mcdm.heroes.v1/rule.dice/bane) at two because it keeps play quick. It's nice to not need to count beyond two positive or negative circumstances in a battle with a lot of effects flying around.

#### Automatic Tier Outcomes

Effects in the game sometimes allow a creature to obtain an automatic tier 1, 2, or 3 outcome on a power roll. Such effects supersede any [edges](scc:mcdm.heroes.v1/rule.dice/edge), [banes](scc:mcdm.heroes.v1/rule.dice/bane), [bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties)es, or [penalties](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) that might affect the roll. If you obtain an automatic [tier outcome](scc:mcdm.heroes.v1/rule.dice/tier-outcome) and the power roll would have an additional effect if you get a specific roll, such as scoring a [critical hit](scc:mcdm.heroes.v1/rule.combat/critical-hit) in combat, you can still make the roll to determine if you obtain the additional effect in addition to the automatic outcome.

If you are under multiple effects that each grant you a different automatic outcome, those effects cancel each other out and all automatic outcomes are ignored. If multiple effects grant you the same automatic outcome, you obtain that outcome.
