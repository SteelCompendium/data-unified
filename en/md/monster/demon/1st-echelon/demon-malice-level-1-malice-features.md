---
features:
    - body: Each demon acting this turn has a double [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on abilities.
      cost: 3 Malice
      icon: ⭐️
      name: Soulburn
    - body: A demon [minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) of your choice transforms into a non-minion [horde](scc.v1:mcdm.monsters.v1/rule.organization/horde) demon of the same level.
      cost: 7 Malice
      icon: "\U0001F300"
      name: Abyssal Evolution
    - cost: 7 Malice
      icon: "\U0001F533"
      intro: Two size 2 rifts to the Abyssal Wasteland appear at locations of your choice. Any demon can use an abyssal rift as a portal to another abyssal rift in the encounter, moving into any space in one rift and appearing immediately in any unoccupied space in the other rift. A non-demon who enters a rift for the first time in a round or starts their turn there takes corruption damage equal to the level of the highest-level demon on the encounter map. An abyssal rift is an immovable object that has 25 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), [damage immunity](scc.v1:mcdm.heroes.v1/rule.damage/damage-immunity) 2, and holy [weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 5. The rift closes when there are no demons remaining on the encounter map. Additionally, a creature who has the Magic or Psionics skill can make a Reason test or Intuition test as a maneuver while [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to a rift to destabilize and close it.
      name: Abyssal Rift
      power_roll:
        tiers:
            high: The rift closes.
            low: The rift remains open and regains 5 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
            mid: The rift remains open.
flavor: At the start of any demon's turn, you can spend Malice to activate one of the following features.
kind: malice
level: 1
name: Demon Malice (Level 1+ Malice Features)
scc: mcdm.monsters.v1/monster.demon.1st-echelon/demon-malice-level-1-malice-features
type: featureblock
---

At the start of any demon's turn, you can spend [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) to activate one of the following features.

> ⭐️ **Soulburn (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> Each demon acting this turn has a double [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on abilities.

> 🌀 **Abyssal Evolution (7 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> A demon [minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) of your choice transforms into a non-minion [horde](scc.v1:mcdm.monsters.v1/rule.organization/horde) demon of the same level.

> 🔳 **Abyssal Rift (7 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> Two size 2 rifts to the Abyssal Wasteland appear at locations of your choice. Any demon can use an abyssal rift as a portal to another abyssal rift in the encounter, moving into any space in one rift and appearing immediately in any unoccupied space in the other rift. A non-demon who enters a rift for the first time in a round or starts their turn there takes corruption damage equal to the level of the highest-level demon on the encounter map. An abyssal rift is an immovable object that has 25 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), [damage immunity](scc.v1:mcdm.heroes.v1/rule.damage/damage-immunity) 2, and holy [weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 5. The rift closes when there are no demons remaining on the encounter map. Additionally, a creature who has the Magic or Psionics skill can make a Reason test or Intuition test as a maneuver while [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to a rift to destabilize and close it.
>
> - **≤11:** The rift remains open and regains 5 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
> - **12-16:** The rift remains open.
> - **17+:** The rift closes.
