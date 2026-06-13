---
features:
    - body: While the dragon is [flying](scc:mcdm.heroes.v1/movement/fly), they shape themself into a blade and fall. Each creature and object in the dragon's space when they hit the ground and in a 6 x 4 line within 1 square of the dragon takes 7 damage. A creature who takes this damage and has A < 4 takes 4 extra damage per square the dragon fell and is [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends). A creature not [restrained](scc:mcdm.heroes.v1/condition/restrained) this way can move into the nearest unoccupied space.
      cost: 3 Malice
      icon: "\U0001F533"
      name: Swordfall
    - body: The dragon shakes loose a cloud of shattered weapons in a 6 x 4 line within 1 square of them. Each creature and object in the area makes an **Agility test**.
      cost: 5 Malice
      icon: "\U0001F533"
      name: Shower of Blades
      power_roll:
        tiers:
            high: 7 damage
            low: 16 damage; [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)
            mid: 13 damage; [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (EoT)
    - body: The dragon takes an additional main action on their turn. They can use this feature even if they are [dazed](scc:mcdm.heroes.v1/condition/dazed).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - body: The dragon superheats the ground across the encounter map until the end of the round. Any enemy who starts their turn on the ground is slagged as if affected by the dragon's Slag Spew ability.
      cost: 7 Malice
      icon: "\U0001F300"
      name: Meltdown
flavor: At the start of a crucible dragon's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Crucible Dragon Malice
scc: mcdm.monsters.v1/monster.dragons/crucible-dragon-malice
type: featureblock
---

At the start of a crucible dragon's turn, you can spend [Malice](scc:mcdm.monsters.v1/rule.monster/malice) to activate one of the following features.

> 🔳 **Swordfall (3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> While the dragon is [flying](scc:mcdm.heroes.v1/movement/fly), they shape themself into a blade and fall. Each creature and object in the dragon's space when they hit the ground and in a 6 x 4 line within 1 square of the dragon takes 7 damage. A creature who takes this damage and has A < 4 takes 4 extra damage per square the dragon fell and is [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends). A creature not [restrained](scc:mcdm.heroes.v1/condition/restrained) this way can move into the nearest unoccupied space.

> 🔳 **Shower of Blades (5 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> The dragon shakes loose a cloud of shattered weapons in a 6 x 4 line within 1 square of them. Each creature and object in the area makes an **Agility test**.
>
> - **≤11:** 16 damage; [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **12-16:** 13 damage; [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (EoT)
> - **17+:** 7 damage

> ☠️ **Solo Action (5 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> The dragon takes an additional main action on their turn. They can use this feature even if they are [dazed](scc:mcdm.heroes.v1/condition/dazed).

> 🌀 **Meltdown (7 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> The dragon superheats the ground across the encounter map until the end of the round. Any enemy who starts their turn on the ground is slagged as if affected by the dragon's Slag Spew ability.
