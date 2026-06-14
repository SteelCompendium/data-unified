---
features:
    - body: Each enemy that starts their [turn](scc:mcdm.heroes.v1/rule.combat/turn) within 3 squares of the boil is I < AVERAGE [taunted](scc:mcdm.heroes.v1/condition/taunted) (EoT) by the boil, or I < WEAK [taunted](scc:mcdm.heroes.v1/condition/taunted) (EoT) by the boil and can't move further from it.
      icon: ⭐️
      name: Hunger Thrush
    - body: When the boil is destroyed, each enemy within 3 squares of the boil takes acid [damage](scc:mcdm.heroes.v1/rule.damage/damage) equal to your level and is A < STRONG [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends).
      icon: ⭐️
      name: Oh, It Pops
name: The Boil
role: Support
scc: mcdm.summoner.v1/monster.fixture.demon.featureblock/the-boil
stats:
    - name: Stamina
      value: 20 + your level
    - name: Size
      value: "2"
terrain_type: Hazard
type: featureblock
---

*Hazard Support*

| **Stamina:** 20 + your level | **Size:** 2 |
|------------------------------|------------:|

> ⭐️ **Hunger Thrush**
>
> Each enemy that starts their [turn](scc:mcdm.heroes.v1/rule.combat/turn) within 3 squares of the boil is I < AVERAGE [taunted](scc:mcdm.heroes.v1/condition/taunted) (EoT) by the boil, or I < WEAK [taunted](scc:mcdm.heroes.v1/condition/taunted) (EoT) by the boil and can't move further from it.

> ⭐️ **Oh, It Pops**
>
> When the boil is destroyed, each enemy within 3 squares of the boil takes acid [damage](scc:mcdm.heroes.v1/rule.damage/damage) equal to your level and is A < STRONG [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends).
