---
features:
    - body: For each 3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice) spent, one minotaur acting this turn gains a +4 bonus to speed and ignores [difficult terrain](scc:mcdm.heroes.v1/movement/difficult-terrain) until the start of their next turn.
      cost: 3 Malice
      icon: "\U0001F464"
      name: Bull Rush
    - body: One minotaur acting this turn halves any damage they take, and can use the Knockback maneuver as a free triggered action whenever an enemy comes [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to them, all until the start of their next turn.
      cost: 5 Malice
      icon: "\U0001F464"
      name: Cut the... Nonsense!
    - cost: 7 Malice
      icon: ❇️
      intro: All minotaurs in the encounter fill the area around them with psychic impressions of feeling lost and isolated. Each enemy within 5 squares of a minotaur is [teleported](scc:mcdm.heroes.v1/movement/teleport) up to 5 squares and makes an **Intuition test**.
      name: Bullseye
      power_roll:
        tiers:
            high: No effect.
            low: The target has line of effect only within 3 squares and is [frightened](scc:mcdm.heroes.v1/condition/frightened) of all minotaurs (save ends).
            mid: The target has line of effect only within 3 squares (EoT).
flavor: At the start of any minotaur's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Minotaur Malice
scc: mcdm.monsters.v1/monster.minotaur/minotaur-malice
type: featureblock
---

At the start of any minotaur's turn, you can spend Malice to activate one of the following features.

> 👤 **Bull Rush (3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> For each 3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice) spent, one minotaur acting this turn gains a +4 bonus to speed and ignores [difficult terrain](scc:mcdm.heroes.v1/movement/difficult-terrain) until the start of their next turn.

> 👤 **Cut the... Nonsense! (5 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> One minotaur acting this turn halves any damage they take, and can use the Knockback maneuver as a free triggered action whenever an enemy comes [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to them, all until the start of their next turn.

> ❇️ **Bullseye (7 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> All minotaurs in the encounter fill the area around them with psychic impressions of feeling lost and isolated. Each enemy within 5 squares of a minotaur is [teleported](scc:mcdm.heroes.v1/movement/teleport) up to 5 squares and makes an **Intuition test**.
>
> - **≤11:** The target has line of effect only within 3 squares and is [frightened](scc:mcdm.heroes.v1/condition/frightened) of all minotaurs (save ends).
> - **12-16:** The target has line of effect only within 3 squares (EoT).
> - **17+:** No effect.
