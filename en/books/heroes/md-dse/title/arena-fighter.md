---
echelon: "2"
effect: 'Choose one of the following benefits:'
file_basename: arena-fighter
file_dpath: title
flavor: You've never seen the showstopper? The move so brutal it was banned in the arena? Come closer and I'll show it to you.
item_id: arena-fighter
item_name: Arena Fighter
name: Arena Fighter
prerequisite: You are victorious in battle in an arena or some other public contest of combat.
scc: mcdm.heroes.v1/title/arena-fighter
source: mcdm.heroes.v1
type: title
---

*You've never seen the showstopper? The move so brutal it was banned in the arena? Come closer and I'll show it to you.*

**Prerequisite:** You are victorious in battle in an arena or some other public contest of combat.

**Effect:** Choose one of the following benefits:

- *Dirty Fighting:* While you are standing, your [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [strikes](scc.v1:mcdm.heroes.v1/rule.combat/strike) gain a +3 damage [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) against [prone creature](scc.v1:mcdm.heroes.v1/condition/prone)s. Additionally, being prone doesn't impose a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on your [strikes](scc.v1:mcdm.heroes.v1/rule.combat/strike).
- *Foes as Weapons:* Whenever you have a creature of your [size](scc.v1:mcdm.heroes.v1/rule.character/size) or smaller [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed), you can use them as a weapon when you make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) weapon free strike. Both the target and the [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) enemy take the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'s damage.
- *Instant Celebrity:* You earn 1 [Renown](scc.v1:mcdm.heroes.v1/rule.resource/renown).
- *Showstopper:* You have the following ability, which can be paid for using the [Heroic Resource](scc.v1:mcdm.heroes.v1/rule.resource/heroic-resource) of your class.

> ###### Showstopper (5 Heroic Resource)
>
> | **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |---------------------------|--------------------:|
> | **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature** |
>
> **[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**
>
> - **≤11:** 6 damage; I < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **12-16:** 10 damage; I < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **17+:** 14 damage; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
>
> **Effect:** If you kill a non-minion opponent using this ability, each enemy within 3 squares of you is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends).
