---
features:
    - cost: 3 Malice
      icon: ❇️
      intro: One ogre acting this turn jumps and lands on their rear, causing a 3 burst shockwave. Each size 1 creature in the area makes a **Might test** or **Agility test**.
      name: Shockwave
      power_roll:
        tiers:
            high: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1'
            low: 5 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
            mid: 4 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    - body: Each ogre in the encounter [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed and can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike). If they can, they gang up on the same target rather than picking different targets.
      cost: 5 Malice
      icon: "\U0001F300"
      name: Bully
    - body: Until the end of the round, each ogre has damage immunity 5 and deals an extra 5 damage with abilities, and heroic abilities that target any ogre have their Heroic Resource cost reduced by 1 (to a minimum of 1).
      cost: 7 Malice
      icon: ⭐️
      name: Rampage
file_basename: ogre-malice
file_dpath: monster/ogre
flavor: At the start of any ogre's turn, you can spend Malice to activate one of the following features.
item_id: ogre-malice
item_name: Ogre Malice
kind: malice
name: Ogre Malice
scc: mcdm.monsters.v1/monster.ogre/ogre-malice
source: mcdm.monsters.v1
type: featureblock
---

At the start of any ogre's turn, you can spend Malice to activate one of the following features.

> ❇️ **Shockwave (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> One ogre acting this turn jumps and lands on their rear, causing a 3 burst shockwave. Each size 1 creature in the area makes a **Might test** or **Agility test**.
>
> - **≤11:** 5 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
> - **12-16:** 4 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
> - **17+:** [Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1

> 🌀 **Bully (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> Each ogre in the encounter [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed and can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike). If they can, they gang up on the same target rather than picking different targets.

> ⭐️ **Rampage (7 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> Until the end of the round, each ogre has damage immunity 5 and deals an extra 5 damage with abilities, and heroic abilities that target any ogre have their Heroic Resource cost reduced by 1 (to a minimum of 1).
