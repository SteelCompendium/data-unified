---
name: Potencies
scc: mcdm.heroes.v1/rule.character/potency
type: rule
---

Many abilities and other effects impose [conditions](scc:mcdm.heroes.v1/rule.combat/condition) and unique statuses on targets. But creatures sometimes get a chance to resist such effects. After all, a monster with a high [Might](scc:mcdm.heroes.v1/rule.character/might) should be harder to knock [prone](scc:mcdm.heroes.v1/condition/prone) most of the time than a creature lacking in that [characteristic](scc:mcdm.heroes.v1/rule.character/characteristic).

Ability effects that have a **potency** are applied to a target only if the effect's potency value is higher than the target's indicated [characteristic](scc:mcdm.heroes.v1/rule.character/characteristic) score. The [characteristic](scc:mcdm.heroes.v1/rule.character/characteristic) a target uses to resist a potency is based on the ability used, while the value of the potency for your hero's abilities is based on one of your [characteristics](scc:mcdm.heroes.v1/rule.character/characteristic) and determined by your class.

Your character has a **weak**, an **average**, and a **strong** potency value, as follows:

- Your weak potency value is equal to your highest [characteristic](scc:mcdm.heroes.v1/rule.character/characteristic) score − 2.
- Your average potency value is equal to your highest [characteristic](scc:mcdm.heroes.v1/rule.character/characteristic) score − 1.
- Your strong potency value is equal to your highest [characteristic](scc:mcdm.heroes.v1/rule.character/characteristic) score.

In abilities and other effects, a potency always appears as the single-letter abbreviation for the target's [characteristic](scc:mcdm.heroes.v1/rule.character/characteristic): M for [Might](scc:mcdm.heroes.v1/rule.character/might), A for [Agility](scc:mcdm.heroes.v1/rule.character/agility), R for [Reason](scc:mcdm.heroes.v1/rule.character/reason), I for [Intuition](scc:mcdm.heroes.v1/rule.character/intuition), or P for [Presence](scc:mcdm.heroes.v1/rule.character/presence). That [characteristic](scc:mcdm.heroes.v1/rule.character/characteristic) is followed by a "less than" sign (<) and your potency value—for example, M < WEAK or R < AVERAGE -with the value indicating the minimum score in that [characteristic](scc:mcdm.heroes.v1/rule.character/characteristic) that the target needs to beat the effect.

As an example, consider the [conduit's](scc:mcdm.heroes.v1/class/conduit) Judgment's Hammer ability, which has the following [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll):

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Intuition](scc:mcdm.heroes.v1/rule.character/intuition):**

- **≤11:** 3 + I holy damage; A < WEAK, [prone](scc:mcdm.heroes.v1/condition/prone)
- **12-16:** 6 + I holy damage; A < AVERAGE, [prone](scc:mcdm.heroes.v1/condition/prone)
- **17+:** 9 + I holy damage; A < STRONG, [prone](scc:mcdm.heroes.v1/condition/prone) and can't stand (save ends)

At 1st level, a [conduit](scc:mcdm.heroes.v1/class/conduit) uses their [Intuition](scc:mcdm.heroes.v1/rule.character/intuition) score to determine their potency values, and that score is 2. That gives the [conduit](scc:mcdm.heroes.v1/class/conduit) the following potencies:

- Weak: 0
- Average: 1
- Strong: 2

When writing Judgment's Hammer on their character sheet, the [conduit's](scc:mcdm.heroes.v1/class/conduit) player updates the damage and converts the weak, average, and strong potencies into their numerical values, knowing that those values won't change until the character hits 2nd [echelon](scc:mcdm.heroes.v1/rule.general/echelon) and their [Intuition](scc:mcdm.heroes.v1/rule.character/intuition) score becomes 3. That produces the following:

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Intuition](scc:mcdm.heroes.v1/rule.character/intuition):**

- **≤11:** 5 holy damage; A < 0, [prone](scc:mcdm.heroes.v1/condition/prone)
- **12-16:** 8 holy damage; A < 1, [prone](scc:mcdm.heroes.v1/condition/prone)
- **17+:** 11 holy damage; A < 2, [prone](scc:mcdm.heroes.v1/condition/prone) and can't stand (save ends)

During a game session, the [conduit](scc:mcdm.heroes.v1/class/conduit) uses Judgment's Hammer to target a bandit with an [Agility](scc:mcdm.heroes.v1/rule.character/agility) score of 0. The ability thus has the following outcomes at each tier:

- With a tier 1 outcome (11 or lower), the ability deals 5 holy damage to the bandit. But the bandit resists the additional effect because they have [Agility](scc:mcdm.heroes.v1/rule.character/agility) 0 (and therefore don't have an [Agility](scc:mcdm.heroes.v1/rule.character/agility) of less than 0).
- With a tier 2 outcome (12-16), the ability deals 8 holy damage. But the bandit is also knocked [prone](scc:mcdm.heroes.v1/condition/prone), unable to resist the additional effect because they would need an [Agility](scc:mcdm.heroes.v1/rule.character/agility) of 1 or higher to do so. If the bandit had [Agility](scc:mcdm.heroes.v1/rule.character/agility) 1 or higher, they would have taken 8 holy damage but stayed standing.
- With a tier 3 outcome (17 or higher), the bandit takes 11 holy damage and is knocked flat and left struggling to stand, unable to resist the strong potency of the additional effect with a mere [Agility](scc:mcdm.heroes.v1/rule.character/agility) 0.

##### Potency Presentation

[Potencies](scc:mcdm.heroes.v1/rule.character/potency) are presented in an abbreviated style in abilities so they don't take up too much space, and so you can read them by saying: "If the target's [characteristic] is less than [potency value], they [suffer effect]." If our 1st-level [conduit](scc:mcdm.heroes.v1/class/conduit) obtained a tier 2 outcome when using Judgment's Hammer, the player would say, "I deal 8 holy damage, and if the bandit's [Agility](scc:mcdm.heroes.v1/rule.character/agility) is less than 1, they fall [prone](scc:mcdm.heroes.v1/condition/prone)."

Reading the ability this way prevents a lot of back and forth. You don't need to ask, "What's the target's [Agility](scc:mcdm.heroes.v1/rule.character/agility) score?", wait for a response, and then give the outcome. You can simply say, "If they don't have an [Agility](scc:mcdm.heroes.v1/rule.character/agility) of 1 or higher, they [fall prone](scc:mcdm.heroes.v1/condition/prone)." Players can let the Director figure out whether the target [is prone](scc:mcdm.heroes.v1/condition/prone) and keep the game moving, with the Director doing the same in reverse when monsters and other foes use abilities with [potencies](scc:mcdm.heroes.v1/rule.character/potency) against the heroes.

##### Adjusting Potencies

[Potencies](scc:mcdm.heroes.v1/rule.character/potency) are made for quick resolution at the table, but a number of [triggered actions](scc:mcdm.heroes.v1/rule.combat/triggered-action) and other abilities—for example, the [censor's](scc:mcdm.heroes.v1/class/censor) Judgment ability and the [null's](scc:mcdm.heroes.v1/class/null) [Null Field](scc:mcdm.heroes.v1/feature.null.level-1/null-field) ability—allow you to manipulate the value of [potencies](scc:mcdm.heroes.v1/rule.character/potency). If you build a hero who can adjust [potencies](scc:mcdm.heroes.v1/rule.character/potency), pay attention during combat! You might be able to help out a friend who needs a little boost to make their ability take full effect, or hinder an enemy about to lock down one of your allies.

##### Spending Resources on Potencies

If an ability or feature allows you to spend your [Heroic Resource](scc:mcdm.heroes.v1/rule.resource/heroic-resource) on an effect that is entirely dependent on a [potency](scc:mcdm.heroes.v1/rule.character/potency) and the target is unaffected because their [characteristic](scc:mcdm.heroes.v1/rule.character/characteristic) is high enough to resist the [potency](scc:mcdm.heroes.v1/rule.character/potency), then you don't spend the [Heroic Resource](scc:mcdm.heroes.v1/rule.resource/heroic-resource).

For example, the [tactician's](scc:mcdm.heroes.v1/class/tactician) Overwatch ability allows the [tactician](scc:mcdm.heroes.v1/class/tactician) to spend 1 focus to impose the [slowed](scc:mcdm.heroes.v1/condition/slowed) [condition](scc:mcdm.heroes.v1/rule.combat/condition) on a target who has R < AVERAGE. Since spending focus this way has no other effect, if the [tactician](scc:mcdm.heroes.v1/class/tactician) targets a creature whose high [Reason](scc:mcdm.heroes.v1/rule.character/reason) leaves them unaffected, the [tactician](scc:mcdm.heroes.v1/class/tactician) doesn't waste any focus. However, if spending this focus had another automatic effect such as dealing extra damage to the target, the 1 focus would be spent even though the [potency](scc:mcdm.heroes.v1/rule.character/potency) was resisted.

This rule also applies to Director-controlled creatures who spend Malice on abilities and features that affect a target using a [potency](scc:mcdm.heroes.v1/rule.character/potency) and have no other automatic effects.
