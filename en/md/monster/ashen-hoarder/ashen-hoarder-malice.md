---
features:
    - body: The ashen hoarder moves up to their speed and can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against two targets.
      cost: 3 Malice
      icon: "\U0001F464"
      name: Relentless Strikes
    - body: The ashen hoarder summons a 10 [wall](scc:mcdm.heroes.v1/rule.combat/wall) of bones and blades into unoccupied squares within 5 squares of them. Each square of the wall has 5 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina). An enemy who comes adjacent to the wall for the first time in a round or starts their turn there takes 3 damage.
      cost: 5 Malice
      icon: "\U0001F533"
      name: Blade Wall
    - body: The ashen hoarder takes an additional main action on their turn. They can use this feature even if they are [dazed](scc:mcdm.heroes.v1/condition/dazed).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - cost: 7 Malice
      icon: "\U0001F533"
      intro: The ashen hoarder launches bone lances into the air, raining them down on enemies and impaling those unlucky enough to be on the receiving end. Each enemy within 20 squares of the ashen hoarder makes an **[Agility](scc:mcdm.heroes.v1/rule.character/agility) test**.
      name: Bone Storm
      power_roll:
        tiers:
            high: 6 damage
            low: 14 damage; [restrained](scc:mcdm.heroes.v1/condition/restrained) and [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)
            mid: 11 damage; [bleeding](scc:mcdm.heroes.v1/condition/bleeding) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
flavor: At the start of an ashen hoarder's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Ashen Hoarder Malice
scc: mcdm.monsters.v1/monster.ashen-hoarder/ashen-hoarder-malice
type: featureblock
---

At the start of an ashen hoarder's turn, you can spend Malice to activate one of the following features.

> 👤 **Relentless Strikes (3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> The ashen hoarder moves up to their speed and can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against two targets.

> 🔳 **Blade Wall (5 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> The ashen hoarder summons a 10 [wall](scc:mcdm.heroes.v1/rule.combat/wall) of bones and blades into unoccupied squares within 5 squares of them. Each square of the wall has 5 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina). An enemy who comes adjacent to the wall for the first time in a round or starts their turn there takes 3 damage.

> ☠️ **Solo Action (5 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> The ashen hoarder takes an additional main action on their turn. They can use this feature even if they are [dazed](scc:mcdm.heroes.v1/condition/dazed).

> 🔳 **Bone Storm (7 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> The ashen hoarder launches bone lances into the air, raining them down on enemies and impaling those unlucky enough to be on the receiving end. Each enemy within 20 squares of the ashen hoarder makes an **[Agility](scc:mcdm.heroes.v1/rule.character/agility) test**.
>
> - **≤11:** 14 damage; [restrained](scc:mcdm.heroes.v1/condition/restrained) and [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **12-16:** 11 damage; [bleeding](scc:mcdm.heroes.v1/condition/bleeding) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
> - **17+:** 6 damage
