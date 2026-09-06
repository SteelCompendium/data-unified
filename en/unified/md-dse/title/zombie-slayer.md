---
echelon: "1"
effect: 'Choose one of the following benefits:'
file_basename: zombie-slayer
file_dpath: title
flavor: Why won't you die?! You've already done it once, you should be good at it by now!
item_id: zombie-slayer
item_name: Zombie Slayer
name: Zombie Slayer
prerequisite: You defeat a leader or solo creature with the Undead keyword, such as a ghost.
scc: mcdm.heroes.v1/title/zombie-slayer
source: mcdm.heroes.v1
type: title
---

*Why won't you die?! You've already done it once, you should be good at it by now!*

**Prerequisite:** You defeat a leader or solo creature with the Undead keyword, such as a ghost.

**Effect:** Choose one of the following benefits:

- *Blessed Weapons:* Whenever you use a damage-dealing weapon ability, that ability can deal holy damage instead of its usual [damage type](scc.v1:mcdm.heroes.v1/rule.damage/damage-type).
- *Divine Health:* You gain corruption immunity equal to your highest [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) score. Additionally, you can't be turned into an undead creature.
- *Holy Terror:* You have the following ability, which can be paid for using the [Heroic Resource](scc.v1:mcdm.heroes.v1/rule.resource/heroic-resource) of your class.

> ###### Holy Terror (3 Heroic Resource)
>
> *Return to your grave!*
>
> | **Area, Magic** |                         **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-----------------|-------------------------------------:|
> | **📏 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)**  | **🎯 Each undead enemy in the area** |
>
> **Effect:** Each target takes holy damage equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score (your choice). Additionally, each target who has P < STRONG is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends).
