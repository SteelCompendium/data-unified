---
features:
    - body: Each wode elf who ends this turn hidden can [shift](../../movement/shifting.md) up to their speed while remaining hidden.
      cost: 3 Malice
      icon: ⭐️
      name: Forest Network
    - body: Until the end of the round, each wode elf gains an edge on abilities, and their strikes can [slide](../../movement/forced-movement.md) a target up to 2 squares in addition to their usual effects. If a strike already imposes forced movement, this slide happens after that forced movement. A creature force moved by a wode elf's strike who ends this forced movement in [difficult terrain](../../movement/difficult-terrain.md) is [restrained](../../condition/restrained.md) until the end of their next turn.
      cost: 5 Malice
      icon: ⭐️
      name: Punishing Regrowth
    - cost: 7 Malice
      icon: "\U0001F300"
      intro: Vines rapidly grow across the entire encounter map. Each enemy in the encounter makes an **Agility test**.
      name: Vines Everywhere
      power_roll:
        tiers:
            high: No effect.
            low: 8 damage; [restrained](../../condition/restrained.md) (save ends)
            mid: '[Restrained](../../condition/restrained.md) (EoT)'
file_basename: wode-elf-malice
file_dpath: monster/elf-wode
flavor: At the start of any wode elf's turn, you can spend Malice to activate one of the following features.
item_id: wode-elf-malice
item_name: Wode Elf Malice
kind: malice
name: Wode Elf Malice
scc: mcdm.monsters.v1/monster.elf-wode/wode-elf-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: Each wode elf who ends this turn hidden can [shift](../../movement/shifting.md) up to their speed while remaining hidden.
      cost: 3 Malice
      icon: ⭐️
      name: Forest Network
    - body: Until the end of the round, each wode elf gains an edge on abilities, and their strikes can [slide](../../movement/forced-movement.md) a target up to 2 squares in addition to their usual effects. If a strike already imposes forced movement, this slide happens after that forced movement. A creature force moved by a wode elf's strike who ends this forced movement in [difficult terrain](../../movement/difficult-terrain.md) is [restrained](../../condition/restrained.md) until the end of their next turn.
      cost: 5 Malice
      icon: ⭐️
      name: Punishing Regrowth
    - cost: 7 Malice
      icon: "\U0001F300"
      intro: Vines rapidly grow across the entire encounter map. Each enemy in the encounter makes an **Agility test**.
      name: Vines Everywhere
      power_roll:
        tiers:
            high: No effect.
            low: 8 damage; [restrained](../../condition/restrained.md) (save ends)
            mid: '[Restrained](../../condition/restrained.md) (EoT)'
flavor: At the start of any wode elf's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.elf-wode/wode-elf-malice
    source: mcdm.monsters.v1
name: Wode Elf Malice
type: featureblock
```
