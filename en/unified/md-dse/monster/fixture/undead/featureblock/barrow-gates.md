---
features:
    - body: Each enemy that starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) within 3 squares of the gates is I < AVERAGE [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (EoT) by the gates. The [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) increases by 1 for [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) enemies.
      icon: ⭐️
      name: The Bell Tolls
    - body: Each of your undead [minions](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/minions) has [damage immunity](scc.v1:mcdm.heroes.v1/rule.damage/damage-immunity) 2 while occupying a space within 3 squares of the gates.
      icon: ⭐️
      name: Undead Dominion
file_basename: barrow-gates
file_dpath: monster/fixture/undead/featureblock
item_id: barrow-gates
item_name: Barrow Gates
name: Barrow Gates
role: Defender
scc: mcdm.summoner.v1/monster.fixture.undead.featureblock/barrow-gates
source: mcdm.summoner.v1
stats:
    - name: Stamina
      value: 20 + your level
    - name: Size
      value: "2"
terrain_type: Fortification
type: featureblock
---

*Fortification Defender*

| **Stamina:** 20 + your level | **Size:** 2 |
|------------------------------|------------:|

> ⭐️ **The Bell Tolls**
>
> Each enemy that starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) within 3 squares of the gates is I < AVERAGE [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (EoT) by the gates. The [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) increases by 1 for [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) enemies.

> ⭐️ **Undead Dominion**
>
> Each of your undead [minions](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/minions) has [damage immunity](scc.v1:mcdm.heroes.v1/rule.damage/damage-immunity) 2 while occupying a space within 3 squares of the gates.
