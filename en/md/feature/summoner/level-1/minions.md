---
class: summoner
level: "1"
name: Minions
scc: mcdm.summoner.v1/feature.summoner.level-1/minions
type: feature
---

The creatures you control are called minions. You can summon and maintain up to a maximum of 8 minions. Your minions are considered allies at your level.

You can manage up to two squads of minions. Newly summoned minions can either be organized into a new squad or be distributed into other squads under your control. A squad can't contain more than eight minions, and all minions in the squad must have the same name.

The maximum [distance](scc:mcdm.heroes.v1/rule.combat/distance) that you can summon minions and use specific conjuring abilities is called your Summoner's Range. Your Summoner's Range is equal to 5 + your [Reason](scc:mcdm.heroes.v1/rule.character/reason) score. You must have [line of effect](scc:mcdm.heroes.v1/rule.combat/line-of-effect) to summon and give commands to minions within your Summoner's Range. Commanding a minion to take a [main action](scc:mcdm.heroes.v1/rule.combat/turn) or a [maneuver](scc:mcdm.heroes.v1/rule.combat/turn) while hidden reveals you.

You also have special minions at your disposal called signature minions, low-cost creatures that you've become accustomed to summoning often. See [Portfolio](scc:mcdm.summoner.v1/feature.summoner.level-1/portfolio) for more details about the types of minions you can summon.

#### Minions in Combat

**Start of Combat:** At the start of a combat encounter or some other stressful situation tracked in [combat rounds](scc:mcdm.heroes.v1/rule.combat/combat-round) (as determined by the Director), you can summon up to two of your signature minions at no cost into unoccupied spaces within your Summoner's Range (no action required).

**Start of [Turn](scc:mcdm.heroes.v1/rule.combat/turn):** At the start of each of your turns during combat, you can summon up to three of your signature minions at no cost into unoccupied spaces within your Summoner's Range (no action required).

**Summoning:** Each minion is summoned on the ground unless they can [fly](scc:mcdm.heroes.v1/movement/fly) or [hover](scc:mcdm.heroes.v1/movement/hover). Unless an ability specifies, you can't summon any new minions beyond your minion maximum until the same number of existing minions are dismissed or destroyed.

**[Stamina](scc:mcdm.heroes.v1/rule.health/stamina):** Minions in a squad pool their [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) together. Whenever a minion in a squad takes [damage](scc:mcdm.heroes.v1/rule.damage/damage), the squad's [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) pool is reduced by a number equal to the damage taken. Each time the pool is reduced by an amount equal to a single squad member's [Stamina](scc:mcdm.heroes.v1/rule.health/stamina), one minion dies (starting with the minion that took damage, followed by the next nearest minion). If there is any excess damage after all minions in the squad are dead, you take damage equal to 2 + your level. Minions can't be [winded](scc:mcdm.heroes.v1/rule.health/winded), can't regain [Stamina](scc:mcdm.heroes.v1/rule.health/stamina), and can't gain [temporary Stamina](scc:mcdm.heroes.v1/rule.health/temporary-stamina).

**Area Effects:** The [damage](scc:mcdm.heroes.v1/rule.damage/damage) from an area effect dealt to a squad's [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) pool can only kill up to the minions in its area. Any excess damage is ignored.

**Strikes with Multiple Targets:** A squad's [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) pool only takes the largest single instance of [damage](scc:mcdm.heroes.v1/rule.damage/damage) from a [strike](scc:mcdm.heroes.v1/rule.combat/strike) that targets two or more minions in that squad. Any additional effects still affect the minions targeted by the strike.

**[Conditions](scc:mcdm.heroes.v1/rule.combat/condition):** You resolve any [saving throws](scc:mcdm.heroes.v1/rule.general/saving-throw) on [conditions](scc:mcdm.heroes.v1/rule.combat/condition) affecting one or more of your minions. Treat [saving throws](scc:mcdm.heroes.v1/rule.general/saving-throw) as if you had one instance of each condition.

**[Damage Immunity](scc:mcdm.heroes.v1/rule.damage/damage-immunity) and [Weakness](scc:mcdm.heroes.v1/rule.damage/damage-weakness):** If any minion in a squad has [damage immunity](scc:mcdm.heroes.v1/rule.damage/damage-immunity) or [weakness](scc:mcdm.heroes.v1/rule.damage/damage-weakness) to a particular [damage type](scc:mcdm.heroes.v1/rule.damage/damage-type), apply that effect to the entire squad only once, regardless of how many minions share the same trait.

**Actions:** Minions in a squad act together on your [turn](scc:mcdm.heroes.v1/rule.combat/turn) in any order, before, in-between, and/or after any of your actions. They can either take a move action and a [main action](scc:mcdm.heroes.v1/rule.combat/turn) (excluding [Heal](scc:mcdm.heroes.v1/feature.common.main-actions/heal) and [Defend](scc:mcdm.heroes.v1/feature.common.main-actions/defend)), a move action and a [maneuver](scc:mcdm.heroes.v1/rule.combat/turn), or two move actions. Individual minions can also make [opportunity attacks](scc:mcdm.heroes.v1/rule.combat/opportunity-attack).

**[Free Strikes](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike):** Unless otherwise specified, a minion's [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) has a distance of Melee 1 or Ranged 5 and deals the damage value listed on the stat block. The minion can choose to deal untyped damage or the [damage type](scc:mcdm.heroes.v1/rule.damage/damage-type) next to the damage value.

**[Damage](scc:mcdm.heroes.v1/rule.damage/damage):** Whenever multiple minions [strike](scc:mcdm.heroes.v1/rule.combat/strike) the same target simultaneously, the damage is added together and treated as a single strike. Minions in a squad targeting the same target with a [signature ability](scc:mcdm.heroes.v1/rule.combat/signature-ability) only apply one instance of the signature ability while each additional minion increases the damage by a number equal to their [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) value.

**[Surges](scc:mcdm.heroes.v1/rule.resource/surge):** Your minions share your pool of [surges](scc:mcdm.heroes.v1/rule.resource/surge) and can apply them to their strikes. Whenever one or more of your minions would gain a [surge](scc:mcdm.heroes.v1/rule.resource/surge) during a [turn](scc:mcdm.heroes.v1/rule.combat/turn), you gain that surge instead.

**Maneuvers:** Unless otherwise specified on the minions' stat block, a squad uses their maneuver together as a unit. If a maneuver targets a single creature, all minions in the squad target the same creature. If a maneuver requires a [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll), the result is equal to 8 + the minions' characteristic + the number of squad members within distance of the maneuver.

**Individual Maneuvers:** An individual minion can use a maneuver to alleviate their own circumstances, such as getting up from [prone](scc:mcdm.heroes.v1/condition/prone) or escaping a [grab](scc:mcdm.heroes.v1/condition/grabbed). If they do, they can't take part in their squad's main action or maneuver.

**[Characteristics](scc:mcdm.heroes.v1/rule.character/characteristic):** Your minions have their own [characteristics](scc:mcdm.heroes.v1/rule.character/characteristic) for the purposes of resisting [potencies](scc:mcdm.heroes.v1/rule.character/potency), maneuvers, and making tests. You use your own [characteristics](scc:mcdm.heroes.v1/rule.character/characteristic) where a minion's stat block refers to an R or uses a [potency](scc:mcdm.heroes.v1/rule.character/potency) (such as M < WEAK).

**Unconscious:** If you are unconscious or unable to act on your [turn](scc:mcdm.heroes.v1/rule.combat/turn), you can't summon new minions. Additionally, your remaining minions can't deal damage; they can only act to bring you to safety.

**End of Combat:** At the end of combat, your minions finish their tasks (such as carrying someone to safety) and are then dismissed.

#### Minions Outside of Combat

While outside of combat, you can have up to 4 minions summoned without spending [essence](scc:mcdm.summoner.v1/feature.summoner.level-1/essence). You can freely summon your signature minions this way. For other minions, while you have a number of [Victories](scc:mcdm.heroes.v1/rule.resource/victories) equal to the minion's essence cost or more, you can summon up to the set number of minions listed on their stat block.

Each of your minions can be given a simple task and a destination you've previously visited and they'll fulfill it to the best of their ability. Example tasks include sending messages, scouting, and carrying supplies. Your minions aren't [followers](scc:mcdm.heroes.v1/rule.general/follower) and can't make [project rolls](scc:mcdm.heroes.v1/rule.downtime/project-roll) until you can summon specialists (see [Minion Machinations](scc:mcdm.summoner.v1/feature.summoner.level-6/minion-machinations)).

When combat begins, any of your minions who were summoned outside of combat finish their tasks and are then dismissed.

> **Soul-y Moley!**
>
> Your minions are manifestations of the magic you weave and don't harbor any souls of their own. They are expressions of your own soul and are more akin to dreams than sapient creatures.
>
> Treat your minions as if they had your soul whenever they are targeted by abilities that affect souls. Ignore any effects that trigger when a creature with a soul dies unless you're the one being targeted.
