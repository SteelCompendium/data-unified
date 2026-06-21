---
file_basename: stamina
file_dpath: rule/health
item_id: stamina
item_name: Stamina
name: Stamina
scc: mcdm.heroes.v1/rule.health/stamina
source: mcdm.heroes.v1
type: rule
---

Your hero's survivability is represented by your Stamina. Think of Stamina as a combination of a creature's physical vitality and their overall energy for dodging and resisting incoming blows, spells, and other violence. It's not that every instance of [damage](../damage/damage.md) deals a [bleeding](../../condition/bleeding.md) wound to you, but that each one chips away at your ability to fight effectively. One attack might make you sweat as you leap back to avoid an arrow, while another might graze your elbow with a dagger nick, leaving a dull, distracting pain. Eventually, this draining of energy leaves you open for bigger blows that can truly harm your body—or possibly kill you.

After any [damage](../damage/damage.md) you take is reduced by [damage immunity](../damage/damage-immunity.md) or other effects, your Stamina is reduced by an amount equal to the remaining [damage](../damage/damage.md). Some effects can also reduce your Stamina maximum, limiting the amount of Stamina you can regain.

#### Director-Controlled Creatures

In most circumstances, Director-controlled creatures die or are destroyed when their [Stamina](stamina.md) drops to 0.

##### No Recoveries

Director-controlled creatures don't have [Recoveries](recoveries.md) or a [recovery value](recoveries.md). Any such creatures who regain [Stamina](stamina.md) during a battle do so by way of a special item or an ability in their stat block. However, there are times when a hero might wish to use an ability that allows another creature to spend a [Recovery](recoveries.md) or to regain [Stamina](stamina.md) equal to their [recovery value](recoveries.md) on an injured [NPC](../general/npc.md). In such cases, a Director-controlled creature regains [Stamina](stamina.md) equal to one-third of their [Stamina](stamina.md) maximum.

#### Knocking Creatures Out

If you damage a creature with an ability that would kill them, you can choose to instead knock them unconscious. If a creature takes damage while unconscious in this way, they die.

Director-controlled creatures remain unconscious for 1 hour if no one does anything to wake them. They then gain 1 [Stamina](stamina.md) and are no longer unconscious.

Heroes remain unconscious for 1 hour if no one does anything to wake them. After 1 hour, they can spend a [Recovery](recoveries.md) and are no longer unconscious. If the hero has no [Recoveries](recoveries.md) left, they can't wake up until they finish a [respite](../resource/respite.md).

##### Unconscious

While you are unconscious, you can't take main actions, maneuvers, [triggered actions](../combat/triggered-action.md), free [triggered actions](../combat/triggered-action.md), or [free maneuvers](../combat/free-maneuver.md); your [speed](../character/speed.md) is 0; you are unaware of your surroundings; and you [are prone](../../condition/prone.md). [Ability rolls](../dice/ability-roll.md) against you have a double [edge](../dice/edge.md). If you wake up from being unconscious, you can stand up from prone as a [free maneuver](../combat/free-maneuver.md).
