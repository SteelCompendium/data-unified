---
features:
    - body: At the end of this round, each hero not already [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to one or more undead is beset by two **rotting zombies** who burst up from the ground to appear in adjacent unoccupied spaces. Each zombie is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded). This feature can't be used two rounds in a row.
      cost: 2 Malice
      icon: "\U0001F300"
      name: Ravenous Horde
    - body: Up to three unattended objects on the encounter map rise to float 1 square off the ground. Each object is then [pulled](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5 squares toward the nearest enemy within 3 squares of the object.
      cost: 3 Malice
      icon: "\U0001F300"
      name: Paranormal Fling
    - cost: 5 Malice
      icon: "\U0001F533"
      intro: Ravenous and rotting undead arms burst forth from 9 connected squares of a vertical or horizontal surface. Any creature who ends their turn [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to an affected square makes an **Agility test**.
      name: The Grasping, the Hungry
      power_roll:
        tiers:
            high: 5 damage
            low: 5 damage; [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
            mid: 5 damage; [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (EoT)
      sections:
        - label: Effect
          text: While [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way, a creature takes 1d6 damage at the start of each of their turns.
    - body: Up to four undead in the encounter move up to their speed and can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike). The number of undead affected increases by 1 for each additional [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) spent on this feature. If an undead is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) during this dread march, they don't die until the march is resolved.
      cost: 7+ Malice
      icon: ⭐️
      name: Dread March
file_basename: undead-malice-level-1-malice-features
file_dpath: monster/undead/1st-echelon
flavor: At the start of any undead's turn, you can spend Malice to activate one of the following features.
item_id: undead-malice-level-1-malice-features
item_name: Undead Malice (Level 1+ Malice Features)
kind: malice
level: 1
name: Undead Malice (Level 1+ Malice Features)
scc: mcdm.monsters.v1/monster.undead.1st-echelon/undead-malice-level-1-malice-features
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: At the end of this round, each hero not already [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to one or more undead is beset by two **rotting zombies** who burst up from the ground to appear in adjacent unoccupied spaces. Each zombie is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded). This feature can't be used two rounds in a row.
      cost: 2 Malice
      icon: "\U0001F300"
      name: Ravenous Horde
    - body: Up to three unattended objects on the encounter map rise to float 1 square off the ground. Each object is then [pulled](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5 squares toward the nearest enemy within 3 squares of the object.
      cost: 3 Malice
      icon: "\U0001F300"
      name: Paranormal Fling
    - cost: 5 Malice
      icon: "\U0001F533"
      intro: Ravenous and rotting undead arms burst forth from 9 connected squares of a vertical or horizontal surface. Any creature who ends their turn [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to an affected square makes an **Agility test**.
      name: The Grasping, the Hungry
      power_roll:
        tiers:
            high: 5 damage
            low: 5 damage; [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
            mid: 5 damage; [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (EoT)
      sections:
        - label: Effect
          text: While [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way, a creature takes 1d6 damage at the start of each of their turns.
    - body: Up to four undead in the encounter move up to their speed and can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike). The number of undead affected increases by 1 for each additional [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) spent on this feature. If an undead is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) during this dread march, they don't die until the march is resolved.
      cost: 7+ Malice
      icon: ⭐️
      name: Dread March
flavor: At the start of any undead's turn, you can spend Malice to activate one of the following features.
kind: malice
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.undead.1st-echelon/undead-malice-level-1-malice-features
    source: mcdm.monsters.v1
name: Undead Malice (Level 1+ Malice Features)
type: featureblock
```
