---
features:
    - body: The manticore uses their mimicry in an attempt to unnerve one creature within their line of effect. If the target has R < 4, they take a bane on power rolls against the manticore (save ends). Each time this feature is used against the same target during the encounter, its [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) decreases by 2.
      cost: 3 Malice
      icon: "\U0001F300"
      name: Uncanny Mimicry
    - body: The manticore takes an additional main action on their turn. They can use this feature even if they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - cost: 5 Malice
      icon: "\U0001F300"
      intro: The manticore lets out an unnerving cry. Each enemy within the manticore's line of effect makes an **Intuition test**.
      name: Desperate Howl
      power_roll:
        tiers:
            high: No effect.
            low: '[Frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)'
            mid: '[Frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (EoT)'
    - body: The manticore sprays tail spikes across the ground within 5 squares of them. Each enemy in that area who has A < 3 is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends). Additionally, the area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain), and any enemy takes 3 poison damage for each square of the area they enter. An enemy who takes 9 poison damage this way on one turn is [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) until the end of the encounter.
      cost: 7 Malice
      icon: ❇️
      name: Barrage of Barbs
file_basename: manticore-malice
file_dpath: monster/manticore
flavor: At the start of any manticore's turn, you can spend Malice to activate one of the following features.
item_id: manticore-malice
item_name: Manticore Malice
kind: malice
name: Manticore Malice
scc: mcdm.monsters.v1/monster.manticore/manticore-malice
source: mcdm.monsters.v1
type: featureblock
---

At the start of any manticore's turn, you can spend Malice to activate one of the following features.

> 🌀 **Uncanny Mimicry (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The manticore uses their mimicry in an attempt to unnerve one creature within their line of effect. If the target has R < 4, they take a bane on power rolls against the manticore (save ends). Each time this feature is used against the same target during the encounter, its [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) decreases by 2.

> ☠️ **Solo Action (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The manticore takes an additional main action on their turn. They can use this feature even if they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).

> 🌀 **Desperate Howl (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The manticore lets out an unnerving cry. Each enemy within the manticore's line of effect makes an **Intuition test**.
>
> - **≤11:** [Frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **12-16:** [Frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (EoT)
> - **17+:** No effect.

> ❇️ **Barrage of Barbs (7 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The manticore sprays tail spikes across the ground within 5 squares of them. Each enemy in that area who has A < 3 is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends). Additionally, the area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain), and any enemy takes 3 poison damage for each square of the area they enter. An enemy who takes 9 poison damage this way on one turn is [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) until the end of the encounter.
