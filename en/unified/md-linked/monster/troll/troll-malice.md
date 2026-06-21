---
features:
    - cost: 3 Malice
      icon: "\U0001F533"
      intro: One troll acting this turn spews out a half-digested meal in a 5 x 1 line within 1 square of them. Each troll in the area regains 3 [Stamina](../../rule/health/stamina.md). Each enemy in the area makes a **Might test**.
      name: Foul Spew
      power_roll:
        tiers:
            high: 6 acid damage
            low: 12 acid damage; [dazed](../../condition/dazed.md) (EoT)
            mid: 10 acid damage; [weakened](../../condition/weakened.md) (EoT)
    - body: Each troll in the encounter can make a [free strike](../../feature/common/main-actions/free-strike.md) against a creature [adjacent](../../rule/combat/adjacent.md) to them, and regains [Stamina](../../rule/health/stamina.md) equal to the damage dealt.
      cost: 5 Malice
      icon: "\U0001F5E1"
      name: Emergency Meal
    - body: Each [winded](../../rule/health/winded.md) troll in the encounter disgorges the contents of their stomach onto the ground around them, creating a 1 burst of foul vomitus that lasts until the end of the encounter. Each non-troll who enters this area for the first time in a round or starts their turn there takes 5 acid damage. Each troll in the area has a double edge on power rolls.
      cost: 7 Malice
      icon: ❇️
      name: Bloody Banquet
flavor: At the start of any troll's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Troll Malice
scc: mcdm.monsters.v1/monster.troll/troll-malice
type: featureblock
---

At the start of any troll's turn, you can spend [Malice](../../rule/monster/malice.md) to activate one of the following features.

> 🔳 **Foul Spew (3 [Malice](../../rule/monster/malice.md))**
>
> One troll acting this turn spews out a half-digested meal in a 5 x 1 line within 1 square of them. Each troll in the area regains 3 [Stamina](../../rule/health/stamina.md). Each enemy in the area makes a **Might test**.
>
> - **≤11:** 12 acid damage; [dazed](../../condition/dazed.md) (EoT)
> - **12-16:** 10 acid damage; [weakened](../../condition/weakened.md) (EoT)
> - **17+:** 6 acid damage

> 🗡 **Emergency Meal (5 [Malice](../../rule/monster/malice.md))**
>
> Each troll in the encounter can make a [free strike](../../feature/common/main-actions/free-strike.md) against a creature [adjacent](../../rule/combat/adjacent.md) to them, and regains [Stamina](../../rule/health/stamina.md) equal to the damage dealt.

> ❇️ **Bloody Banquet (7 [Malice](../../rule/monster/malice.md))**
>
> Each [winded](../../rule/health/winded.md) troll in the encounter disgorges the contents of their stomach onto the ground around them, creating a 1 burst of foul vomitus that lasts until the end of the encounter. Each non-troll who enters this area for the first time in a round or starts their turn there takes 5 acid damage. Each troll in the area has a double edge on power rolls.
