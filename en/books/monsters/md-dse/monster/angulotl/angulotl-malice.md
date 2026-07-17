---
features:
    - body: Until the end of the round, when an angulotl moves through an inactive angulotl's space, the inactive angulotl can use a free triggered action to jump 3 squares.
      cost: 3 Malice
      icon: ⭐️
      name: Leapfrog
    - cost: 5 Malice
      icon: ❇️
      intro: Each angulotl in the encounter puffs out their throat and starts loudly droning. Any non-angulotl adjacent to an angulotl makes an **[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) test.**
      name: Resonating Croak
      power_roll:
        tiers:
            high: No effect.
            low: 5 sonic damage; [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
            mid: 4 sonic damage
    - body: An angulotl calls clouds to cover the encounter map and unleash rain until the end of the round. Any creature or object that is exposed to the sky is wet until the end of the encounter.
      cost: 7 Malice
      icon: "\U0001F300"
      name: Rainfall
file_basename: angulotl-malice
file_dpath: monster/angulotl
flavor: At the start of any angulotl's turn, you can spend Malice to activate one of the following features.
item_id: angulotl-malice
item_name: Angulotl Malice
kind: malice
name: Angulotl Malice
scc: mcdm.monsters.v1/monster.angulotl/angulotl-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: Until the end of the round, when an angulotl moves through an inactive angulotl's space, the inactive angulotl can use a free triggered action to jump 3 squares.
      cost: 3 Malice
      icon: ⭐️
      name: Leapfrog
    - cost: 5 Malice
      icon: ❇️
      intro: Each angulotl in the encounter puffs out their throat and starts loudly droning. Any non-angulotl adjacent to an angulotl makes an **[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) test.**
      name: Resonating Croak
      power_roll:
        tiers:
            high: No effect.
            low: 5 sonic damage; [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
            mid: 4 sonic damage
    - body: An angulotl calls clouds to cover the encounter map and unleash rain until the end of the round. Any creature or object that is exposed to the sky is wet until the end of the encounter.
      cost: 7 Malice
      icon: "\U0001F300"
      name: Rainfall
flavor: At the start of any angulotl's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.angulotl/angulotl-malice
    source: mcdm.monsters.v1
name: Angulotl Malice
type: featureblock
```
