---
features:
    - cost: 3 Malice
      effects:
        - effect: Each orc [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed, moving through enemy spaces if they can. Each enemy passed through during this movement makes a **Might test**.
          tier1: 6 damage; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
          tier2: 4 damage; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
          tier3: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2'
      icon: ⭐️
      intro: Each orc [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed, moving through enemy spaces if they can. Each enemy passed through during this movement makes a **Might test**.
      name: Overwhelming March
      power_roll:
        tiers:
            high: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2'
            low: 6 damage; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
            mid: 4 damage; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    - body: An orc acting this turn summons 2 **mohlers** out of the ground, who dig a trench that is a 10 x 1 line within 10 squares when they appear. The trench is 2 squares deep and is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain). The trench can't be created directly underneath creatures.
      cost: 5 Malice
      effects:
        - effect: An orc acting this turn summons 2 **mohlers** out of the ground, who dig a trench that is a 10 x 1 line within 10 squares when they appear. The trench is 2 squares deep and is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain). The trench can't be created directly underneath creatures.
      icon: "\U0001F533"
      name: Mohler Trench
    - cost: 7 Malice
      effects:
        - effect: The ground shakes as a group of mohlers dig a 5 cube pit beneath an area where at least one creature is on the ground. The area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain). Each orc in the area can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into the nearest unoccupied space outside the pit before it is completed. Each nonorc in the area makes an **Agility test**.
          tier1: 4 damage; the target falls; [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand (EoT)
          tier2: 4 damage; the target falls
          tier3: The target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into the nearest unoccupied space outside the pit.
      icon: "\U0001F533"
      intro: The ground shakes as a group of mohlers dig a 5 cube pit beneath an area where at least one creature is on the ground. The area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain). Each orc in the area can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into the nearest unoccupied space outside the pit before it is completed. Each nonorc in the area makes an **Agility test**.
      name: Mohler Cavity
      power_roll:
        tiers:
            high: The target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into the nearest unoccupied space outside the pit.
            low: 4 damage; the target falls; [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand (EoT)
            mid: 4 damage; the target falls
file_basename: orc-malice
file_dpath: monster/orc
flavor: At the start of any orc's turn, you can spend Malice to activate one of the following features.
item_id: orc-malice
item_name: Orc Malice
kind: malice
name: Orc Malice
scc: mcdm.monsters.v1/monster.orc/orc-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - cost: 3 Malice
      effects:
        - effect: Each orc [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed, moving through enemy spaces if they can. Each enemy passed through during this movement makes a **Might test**.
          tier1: 6 damage; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
          tier2: 4 damage; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
          tier3: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2'
      icon: ⭐️
      intro: Each orc [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed, moving through enemy spaces if they can. Each enemy passed through during this movement makes a **Might test**.
      name: Overwhelming March
      power_roll:
        tiers:
            high: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2'
            low: 6 damage; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
            mid: 4 damage; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    - body: An orc acting this turn summons 2 **mohlers** out of the ground, who dig a trench that is a 10 x 1 line within 10 squares when they appear. The trench is 2 squares deep and is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain). The trench can't be created directly underneath creatures.
      cost: 5 Malice
      effects:
        - effect: An orc acting this turn summons 2 **mohlers** out of the ground, who dig a trench that is a 10 x 1 line within 10 squares when they appear. The trench is 2 squares deep and is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain). The trench can't be created directly underneath creatures.
      icon: "\U0001F533"
      name: Mohler Trench
    - cost: 7 Malice
      effects:
        - effect: The ground shakes as a group of mohlers dig a 5 cube pit beneath an area where at least one creature is on the ground. The area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain). Each orc in the area can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into the nearest unoccupied space outside the pit before it is completed. Each nonorc in the area makes an **Agility test**.
          tier1: 4 damage; the target falls; [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand (EoT)
          tier2: 4 damage; the target falls
          tier3: The target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into the nearest unoccupied space outside the pit.
      icon: "\U0001F533"
      intro: The ground shakes as a group of mohlers dig a 5 cube pit beneath an area where at least one creature is on the ground. The area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain). Each orc in the area can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into the nearest unoccupied space outside the pit before it is completed. Each nonorc in the area makes an **Agility test**.
      name: Mohler Cavity
      power_roll:
        tiers:
            high: The target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into the nearest unoccupied space outside the pit.
            low: 4 damage; the target falls; [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand (EoT)
            mid: 4 damage; the target falls
flavor: At the start of any orc's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.orc/orc-malice
    source: mcdm.monsters.v1
name: Orc Malice
type: featureblock
```
