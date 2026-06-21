---
features:
    - body: The shambling mound seeps noxious residue from their vines. The next time they use their Vine Lash ability before the end of their next turn, they deal an extra 12 poison damage to each target.
      cost: 3 Malice
      icon: "\U0001F464"
      name: Poisoned Vines
    - cost: 5 Malice
      icon: ❇️
      intro: The shambling mound lashes out at each enemy within 10 squares of them, driving them back or into the air. Each target makes an **Agility test**.
      name: Frenzy Lash
      power_roll:
        tiers:
            high: 3 damage
            low: 7 damage; [push](../../movement/forced-movement.md) 7 or vertical push 3; [restrained](../../condition/restrained.md) (save ends)
            mid: 6 damage; [push](../../movement/forced-movement.md) 5 or vertical push 2
    - body: The shambling mound takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - body: Until the end of the shambling mound's next turn, the area within 10 squares of them is [difficult terrain](../../movement/difficult-terrain.md) for enemies, and any enemy in the area takes a bane on power rolls. Any enemy who starts their turn in the area takes 4 acid damage, and the shambling mound regains an equal amount of [Stamina](../../rule/health/stamina.md).
      cost: 7 Malice
      icon: ❇️
      name: Leeching Wilds
flavor: At the start of a shambling mound's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Shambling Mound Malice
scc: mcdm.monsters.v1/monster.shambling-mound/shambling-mound-malice
type: featureblock
---

At the start of a shambling mound's turn, you can spend [Malice](../../rule/monster/malice.md) to activate one of the following features.

> 👤 **Poisoned Vines (3 [Malice](../../rule/monster/malice.md))**
>
> The shambling mound seeps noxious residue from their vines. The next time they use their Vine Lash ability before the end of their next turn, they deal an extra 12 poison damage to each target.

> ❇️ **Frenzy Lash (5 [Malice](../../rule/monster/malice.md))**
>
> The shambling mound lashes out at each enemy within 10 squares of them, driving them back or into the air. Each target makes an **Agility test**.
>
> - **≤11:** 7 damage; [push](../../movement/forced-movement.md) 7 or vertical push 3; [restrained](../../condition/restrained.md) (save ends)
> - **12-16:** 6 damage; [push](../../movement/forced-movement.md) 5 or vertical push 2
> - **17+:** 3 damage

> ☠️ **Solo Action (5 [Malice](../../rule/monster/malice.md))**
>
> The shambling mound takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).

> ❇️ **Leeching Wilds (7 [Malice](../../rule/monster/malice.md))**
>
> Until the end of the shambling mound's next turn, the area within 10 squares of them is [difficult terrain](../../movement/difficult-terrain.md) for enemies, and any enemy in the area takes a bane on power rolls. Any enemy who starts their turn in the area takes 4 acid damage, and the shambling mound regains an equal amount of [Stamina](../../rule/health/stamina.md).
