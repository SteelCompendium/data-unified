---
features:
    - body: The dragon expands their wings to create a shroud of shadow. Until the start of the dragon's next turn, any strike made against them takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane).
      cost: 3 Malice
      icon: ⭐️
      name: Black Skies
    - cost: 5 Malice
      icon: ❇️
      intro: The dragon [flies](scc.v1:mcdm.heroes.v1/movement/fly) up to 10 squares and carries fated souls with them. Each creature in the area of the dragon's Stagnant Wyrmscale Aura [trait](scc.v1:mcdm.monsters.v1/rule.monster/monster-trait) makes a **Presence test**.
      name: Rise and Fall
      power_roll:
        tiers:
            high: Vertical pull 4
            low: Vertical pull 10
            mid: Vertical pull 6
    - body: The dragon takes an additional main action on their turn. They can use this feature even if they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - body: Each edge of the encounter map burns with intangible purple flames until the end of the encounter. The flames expand by 1 square at the end of every turn. Any enemy takes 5 corruption damage for each square of flames they enter.
      cost: 10 Malice
      icon: "\U0001F300"
      name: Burn It Right Down
file_basename: omen-dragon-malice
file_dpath: monster/dragon
flavor: At the start of an omen dragon's turn, you can spend Malice to activate one of the following features.
item_id: omen-dragon-malice
item_name: Omen Dragon Malice
kind: malice
name: Omen Dragon Malice
scc: mcdm.monsters.v1/monster.dragon/omen-dragon-malice
source: mcdm.monsters.v1
type: featureblock
---

At the start of an omen dragon's turn, you can spend [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) to activate one of the following features.

> ⭐️ **Black Skies (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The dragon expands their wings to create a shroud of shadow. Until the start of the dragon's next turn, any strike made against them takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane).

> ❇️ **Rise and Fall (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The dragon [flies](scc.v1:mcdm.heroes.v1/movement/fly) up to 10 squares and carries fated souls with them. Each creature in the area of the dragon's Stagnant Wyrmscale Aura [trait](scc.v1:mcdm.monsters.v1/rule.monster/monster-trait) makes a **Presence test**.
>
> - **≤11:** Vertical pull 10
> - **12-16:** Vertical pull 6
> - **17+:** Vertical pull 4

> ☠️ **Solo Action (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The dragon takes an additional main action on their turn. They can use this feature even if they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).

> 🌀 **Burn It Right Down (10 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> Each edge of the encounter map burns with intangible purple flames until the end of the encounter. The flames expand by 1 square at the end of every turn. Any enemy takes 5 corruption damage for each square of flames they enter.
