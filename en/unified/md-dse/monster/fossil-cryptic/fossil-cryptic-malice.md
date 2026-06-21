---
features:
    - body: The fossil cryptic [slides](scc.v1:mcdm.heroes.v1/movement/forced-movement) one creature on the ground up to 5 squares. If the creature is [prone](scc.v1:mcdm.heroes.v1/condition/prone), this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores [stability](scc.v1:mcdm.heroes.v1/rule.character/stability).
      cost: 3 Malice
      icon: "\U0001F3F9"
      name: Floor Mosaic
    - body: The fossil cryptic takes an additional main action on their turn. They can use this feature even if they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - body: Two pillars of stone 1 square wide either thrust up out of the ground or jut down from the ceiling anywhere on the encounter map, to a height of up to 5 squares. A creature in the area of a pillar before it appears is knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone) on its surface. If the creature comes into contact with the ceiling above or the floor beneath the pillar and has M < 2 they are [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends).
      cost: 5 Malice
      icon: "\U0001F533"
      name: Stone Pillars
    - cost: 10 Malice
      icon: "\U0001F300"
      intro: The air across the encounter map is thick with dust until the end of the encounter. Each enemy in the dust is suffocating. Additionally, at the end of each round, each enemy in the dust makes a **Might test**.
      name: Choking Dust
      power_roll:
        tiers:
            high: No effect.
            low: Until the end of the enemy's next turn, their [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) is reduced to 0, and any [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) effects targeting them gain a +2 bonus to the distance moved.
            mid: The enemy's [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) is halved (EoT).
file_basename: fossil-cryptic-malice
file_dpath: monster/fossil-cryptic
flavor: At the start of a fossil cryptic's turn, you can spend Malice to activate one of the following features.
item_id: fossil-cryptic-malice
item_name: Fossil Cryptic Malice
kind: malice
name: Fossil Cryptic Malice
scc: mcdm.monsters.v1/monster.fossil-cryptic/fossil-cryptic-malice
source: mcdm.monsters.v1
type: featureblock
---

At the start of a fossil cryptic's turn, you can spend [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) to activate one of the following features.

> 🏹 **Floor Mosaic (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The fossil cryptic [slides](scc.v1:mcdm.heroes.v1/movement/forced-movement) one creature on the ground up to 5 squares. If the creature is [prone](scc.v1:mcdm.heroes.v1/condition/prone), this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores [stability](scc.v1:mcdm.heroes.v1/rule.character/stability).

> ☠️ **Solo Action (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The fossil cryptic takes an additional main action on their turn. They can use this feature even if they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).

> 🔳 **Stone Pillars (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> Two pillars of stone 1 square wide either thrust up out of the ground or jut down from the ceiling anywhere on the encounter map, to a height of up to 5 squares. A creature in the area of a pillar before it appears is knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone) on its surface. If the creature comes into contact with the ceiling above or the floor beneath the pillar and has M < 2 they are [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends).

> 🌀 **Choking Dust (10 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The air across the encounter map is thick with dust until the end of the encounter. Each enemy in the dust is suffocating. Additionally, at the end of each round, each enemy in the dust makes a **Might test**.
>
> - **≤11:** Until the end of the enemy's next turn, their [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) is reduced to 0, and any [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) effects targeting them gain a +2 bonus to the distance moved.
> - **12-16:** The enemy's [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) is halved (EoT).
> - **17+:** No effect.
