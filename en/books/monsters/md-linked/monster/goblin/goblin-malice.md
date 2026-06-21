---
features:
    - body: Each goblin in the encounter gains a +2 bonus to speed until the end of the round.
      cost: 3 Malice
      icon: ⭐️
      name: Goblin Mode
    - body: Each enemy in the encounter takes 1 damage for each goblin [adjacent](../../rule/combat/adjacent.md) to them.
      cost: 5 Malice
      icon: ❇️
      name: Tiny Stabs
    - cost: 7 Malice
      icon: "\U0001F300"
      intro: The encounter map is covered in a green mist that lasts until the end of the round, and which can't be dispersed by wind. All areas of the map are [difficult terrain](../../movement/difficult-terrain.md) for non-goblins, and each non-goblin on the map makes a **Might test**.
      name: Swamp Stink
      power_roll:
        tiers:
            high: No effect.
            low: 5 poison damage; the creature is [weakened](../../condition/weakened.md) until the mist disappears.
            mid: The creature is [weakened](../../condition/weakened.md) until the mist disappears.
flavor: At the start of any goblin's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Goblin Malice
scc: mcdm.monsters.v1/monster.goblin/goblin-malice
type: featureblock
---

At the start of any goblin's turn, you can spend [Malice](../../rule/monster/malice.md) to activate one of the following features.

> ⭐️ **Goblin Mode (3 [Malice](../../rule/monster/malice.md))**
>
> Each goblin in the encounter gains a +2 bonus to speed until the end of the round.

> ❇️ **Tiny Stabs (5 [Malice](../../rule/monster/malice.md))**
>
> Each enemy in the encounter takes 1 damage for each goblin [adjacent](../../rule/combat/adjacent.md) to them.

> 🌀 **Swamp Stink (7 [Malice](../../rule/monster/malice.md))**
>
> The encounter map is covered in a green mist that lasts until the end of the round, and which can't be dispersed by wind. All areas of the map are [difficult terrain](../../movement/difficult-terrain.md) for non-goblins, and each non-goblin on the map makes a **Might test**.
>
> - **≤11:** 5 poison damage; the creature is [weakened](../../condition/weakened.md) until the mist disappears.
> - **12-16:** The creature is [weakened](../../condition/weakened.md) until the mist disappears.
> - **17+:** No effect.
