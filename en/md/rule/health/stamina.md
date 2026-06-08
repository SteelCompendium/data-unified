---
name: Stamina
scc: mcdm.heroes.v1/rule.health/stamina
type: rule
---

Your hero's survivability is represented by your Stamina. Think of Stamina as a combination of a creature's physical vitality and their overall energy for dodging and resisting incoming blows, spells, and other violence. It's not that every instance of [damage](scc:mcdm.heroes.v1/rule.damage/damage) deals a [bleeding](scc:mcdm.heroes.v1/condition/bleeding) wound to you, but that each one chips away at your ability to fight effectively. One attack might make you sweat as you leap back to avoid an arrow, while another might graze your elbow with a dagger nick, leaving a dull, distracting pain. Eventually, this draining of energy leaves you open for bigger blows that can truly harm your body—or possibly kill you.

After any [damage](scc:mcdm.heroes.v1/rule.damage/damage) you take is reduced by [damage immunity](scc:mcdm.heroes.v1/rule.damage/damage-immunity) or other effects, your Stamina is reduced by an amount equal to the remaining [damage](scc:mcdm.heroes.v1/rule.damage/damage). Some effects can also reduce your Stamina maximum, limiting the amount of Stamina you can regain.

#### Director-Controlled Creatures

In most circumstances, Director-controlled creatures die or are destroyed when their [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) drops to 0.

##### No Recoveries

Director-controlled creatures don't have [Recoveries](scc:mcdm.heroes.v1/rule.health/recoveries) or a [recovery value](scc:mcdm.heroes.v1/rule.health/recoveries). Any such creatures who regain [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) during a battle do so by way of a special item or an ability in their stat block. However, there are times when a hero might wish to use an ability that allows another creature to spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries) or to regain [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) equal to their [recovery value](scc:mcdm.heroes.v1/rule.health/recoveries) on an injured [NPC](scc:mcdm.heroes.v1/rule.general/npc). In such cases, a Director-controlled creature regains [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) equal to one-third of their [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) maximum.

#### Knocking Creatures Out

If you damage a creature with an ability that would kill them, you can choose to instead knock them unconscious. If a creature takes damage while unconscious in this way, they die.

Director-controlled creatures remain unconscious for 1 hour if no one does anything to wake them. They then gain 1 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) and are no longer unconscious.

Heroes remain unconscious for 1 hour if no one does anything to wake them. After 1 hour, they can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries) and are no longer unconscious. If the hero has no [Recoveries](scc:mcdm.heroes.v1/rule.health/recoveries) left, they can't wake up until they finish a [respite](scc:mcdm.heroes.v1/rule.resource/respite).

##### Unconscious

While you are unconscious, you can't take main actions, maneuvers, [triggered actions](scc:mcdm.heroes.v1/rule.combat/triggered-action), free [triggered actions](scc:mcdm.heroes.v1/rule.combat/triggered-action), or [free maneuvers](scc:mcdm.heroes.v1/rule.combat/free-maneuver); your [speed](scc:mcdm.heroes.v1/rule.character/speed) is 0; you are unaware of your surroundings; and you [are prone](scc:mcdm.heroes.v1/condition/prone). [Ability rolls](scc:mcdm.heroes.v1/rule.dice/ability-roll) against you have a double [edge](scc:mcdm.heroes.v1/rule.dice/edge). If you wake up from being unconscious, you can stand up from prone as a [free maneuver](scc:mcdm.heroes.v1/rule.combat/free-maneuver).
