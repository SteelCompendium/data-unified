---
features:
    - body: The dragon thickens the fog of their Gloaming Wyrmscale Aura [trait](../../rule/monster/monster-trait.md) and the horrors within it. Each creature in the area takes a [bane](../../rule/dice/bane.md) on strikes made against the dragon until the start of the dragon's next turn.
      cost: 3 Malice
      icon: ⭐️
      name: Dread and Terror
    - cost: 5 Malice
      icon: "\U0001F533"
      intro: The dragon manifests four 2 cubes of nightmarish apparitions anywhere on the encounter map. Each creature in the area when it appears makes an **Intuition test**.
      name: Doleful Visions
      power_roll:
        tiers:
            high: 6 damage
            low: 14 damage; [dazed](../../condition/dazed.md) (save ends)
            mid: 11 damage; [dazed](../../condition/dazed.md) (EoT)
    - body: The dragon takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - body: The dragon summons macabre, disquieting phantasms in a 10 cube within 1 square that lasts until the end of the encounter. Any enemy who enters the area for the first time in a round or starts their turn there takes 6 psychic damage, or 8 psychic damage if they are dragonsealed by the gloom dragon. Additionally, the enemy's Intuition score is treated as 1 lower for the purpose of resisting [potencies](../../rule/character/potency.md) until the end of the encounter.
      cost: 7 Malice
      icon: "\U0001F533"
      name: Phantasmagoria!
file_basename: gloom-dragon-malice
file_dpath: monster/dragon
flavor: At the start of a gloom dragon's turn, you can spend Malice to activate one of the following features.
item_id: gloom-dragon-malice
item_name: Gloom Dragon Malice
kind: malice
name: Gloom Dragon Malice
scc: mcdm.monsters.v1/monster.dragon/gloom-dragon-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: The dragon thickens the fog of their Gloaming Wyrmscale Aura [trait](../../rule/monster/monster-trait.md) and the horrors within it. Each creature in the area takes a [bane](../../rule/dice/bane.md) on strikes made against the dragon until the start of the dragon's next turn.
      cost: 3 Malice
      icon: ⭐️
      name: Dread and Terror
    - cost: 5 Malice
      icon: "\U0001F533"
      intro: The dragon manifests four 2 cubes of nightmarish apparitions anywhere on the encounter map. Each creature in the area when it appears makes an **Intuition test**.
      name: Doleful Visions
      power_roll:
        tiers:
            high: 6 damage
            low: 14 damage; [dazed](../../condition/dazed.md) (save ends)
            mid: 11 damage; [dazed](../../condition/dazed.md) (EoT)
    - body: The dragon takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - body: The dragon summons macabre, disquieting phantasms in a 10 cube within 1 square that lasts until the end of the encounter. Any enemy who enters the area for the first time in a round or starts their turn there takes 6 psychic damage, or 8 psychic damage if they are dragonsealed by the gloom dragon. Additionally, the enemy's Intuition score is treated as 1 lower for the purpose of resisting [potencies](../../rule/character/potency.md) until the end of the encounter.
      cost: 7 Malice
      icon: "\U0001F533"
      name: Phantasmagoria!
flavor: At the start of a gloom dragon's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.dragon/gloom-dragon-malice
    source: mcdm.monsters.v1
name: Gloom Dragon Malice
type: featureblock
```
