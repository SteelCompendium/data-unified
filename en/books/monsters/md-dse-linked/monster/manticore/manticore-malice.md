---
features:
    - body: The manticore uses their mimicry in an attempt to unnerve one creature within their line of effect. If the target has R < 4, they take a bane on power rolls against the manticore (save ends). Each time this feature is used against the same target during the encounter, its [potency](../../rule/character/potency.md) decreases by 2.
      cost: 3 Malice
      icon: "\U0001F300"
      name: Uncanny Mimicry
    - body: The manticore takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).
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
            low: '[Frightened](../../condition/frightened.md) (save ends)'
            mid: '[Frightened](../../condition/frightened.md) (EoT)'
    - body: The manticore sprays tail spikes across the ground within 5 squares of them. Each enemy in that area who has A < 3 is [bleeding](../../condition/bleeding.md) (save ends). Additionally, the area is [difficult terrain](../../movement/difficult-terrain.md), and any enemy takes 3 poison damage for each square of the area they enter. An enemy who takes 9 poison damage this way on one turn is [weakened](../../condition/weakened.md) until the end of the encounter.
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

```ds-fb
features:
    - body: The manticore uses their mimicry in an attempt to unnerve one creature within their line of effect. If the target has R < 4, they take a bane on power rolls against the manticore (save ends). Each time this feature is used against the same target during the encounter, its [potency](../../rule/character/potency.md) decreases by 2.
      cost: 3 Malice
      icon: "\U0001F300"
      name: Uncanny Mimicry
    - body: The manticore takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).
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
            low: '[Frightened](../../condition/frightened.md) (save ends)'
            mid: '[Frightened](../../condition/frightened.md) (EoT)'
    - body: The manticore sprays tail spikes across the ground within 5 squares of them. Each enemy in that area who has A < 3 is [bleeding](../../condition/bleeding.md) (save ends). Additionally, the area is [difficult terrain](../../movement/difficult-terrain.md), and any enemy takes 3 poison damage for each square of the area they enter. An enemy who takes 9 poison damage this way on one turn is [weakened](../../condition/weakened.md) until the end of the encounter.
      cost: 7 Malice
      icon: ❇️
      name: Barrage of Barbs
flavor: At the start of any manticore's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.manticore/manticore-malice
    source: mcdm.monsters.v1
name: Manticore Malice
type: featureblock
```
