---
features:
    - body: The ashen hoarder moves up to their speed and can make a [free strike](../../feature/common/main-actions/free-strike.md) against two targets.
      cost: 3 Malice
      icon: "\U0001F464"
      name: Relentless Strikes
    - body: The ashen hoarder summons a 10 [wall](../../rule/combat/wall.md) of bones and blades into unoccupied squares within 5 squares of them. Each square of the wall has 5 [Stamina](../../rule/health/stamina.md). An enemy who comes adjacent to the wall for the first time in a round or starts their turn there takes 3 damage.
      cost: 5 Malice
      icon: "\U0001F533"
      name: Blade Wall
    - body: The ashen hoarder takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - cost: 7 Malice
      icon: "\U0001F533"
      intro: The ashen hoarder launches bone lances into the air, raining them down on enemies and impaling those unlucky enough to be on the receiving end. Each enemy within 20 squares of the ashen hoarder makes an **[Agility](../../rule/character/agility.md) test**.
      name: Bone Storm
      power_roll:
        tiers:
            high: 6 damage
            low: 14 damage; [restrained](../../condition/restrained.md) and [bleeding](../../condition/bleeding.md) (save ends)
            mid: 11 damage; [bleeding](../../condition/bleeding.md) ([EoT](../../rule/combat/end-of-turn.md))
file_basename: ashen-hoarder-malice
file_dpath: monster/ashen-hoarder
flavor: At the start of an ashen hoarder's turn, you can spend Malice to activate one of the following features.
item_id: ashen-hoarder-malice
item_name: Ashen Hoarder Malice
kind: malice
name: Ashen Hoarder Malice
scc: mcdm.monsters.v1/monster.ashen-hoarder/ashen-hoarder-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: The ashen hoarder moves up to their speed and can make a [free strike](../../feature/common/main-actions/free-strike.md) against two targets.
      cost: 3 Malice
      icon: "\U0001F464"
      name: Relentless Strikes
    - body: The ashen hoarder summons a 10 [wall](../../rule/combat/wall.md) of bones and blades into unoccupied squares within 5 squares of them. Each square of the wall has 5 [Stamina](../../rule/health/stamina.md). An enemy who comes adjacent to the wall for the first time in a round or starts their turn there takes 3 damage.
      cost: 5 Malice
      icon: "\U0001F533"
      name: Blade Wall
    - body: The ashen hoarder takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - cost: 7 Malice
      icon: "\U0001F533"
      intro: The ashen hoarder launches bone lances into the air, raining them down on enemies and impaling those unlucky enough to be on the receiving end. Each enemy within 20 squares of the ashen hoarder makes an **[Agility](../../rule/character/agility.md) test**.
      name: Bone Storm
      power_roll:
        tiers:
            high: 6 damage
            low: 14 damage; [restrained](../../condition/restrained.md) and [bleeding](../../condition/bleeding.md) (save ends)
            mid: 11 damage; [bleeding](../../condition/bleeding.md) ([EoT](../../rule/combat/end-of-turn.md))
flavor: At the start of an ashen hoarder's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.ashen-hoarder/ashen-hoarder-malice
    source: mcdm.monsters.v1
name: Ashen Hoarder Malice
type: featureblock
```
