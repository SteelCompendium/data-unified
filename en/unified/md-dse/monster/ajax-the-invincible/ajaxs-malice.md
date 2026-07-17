---
features:
    - body: Ajax attempts to instill doubt into a creature within line of effect through logic and reason. The creature and Ajax make an opposed [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) test. If Ajax wins, he chooses to either deal 11 extra damage to one target on his next strike or to gain an additional [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) during the current round. Ajax can't use this feature against the same creature during the same encounter.
      cost: 2 Malice
      icon: "\U0001F464"
      name: Reason
    - body: Until the end of the round, Ajax chooses one of the following environments he has previously visited and overlays that environment on top of the encounter map, temporarily merging multiple realities.
      cost: 5 Malice
      icon: "\U0001F300"
      name: Nexus Jewel
      sections:
        - label: Incredibly High Above the Ground
          text: The winds whip and bluster. Any creature who can't [fly](scc.v1:mcdm.heroes.v1/movement/fly) takes a −3 penalty to stability, and [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) effects gain a +3 bonus to their distance against such creatures.
        - label: Swamp
          text: The ground is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies. Any creature who starts and ends their turn in the same space is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends).
        - label: Volcanic Canyon
          text: The air is stiflingly hot. Each enemy takes 5 fire damage for each square they enter.
    - body: Ajax takes an additional main action on his turn. He can use this feature even if he is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - cost: 10 Malice
      distance: Four 3 cubes within 10
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
        - Weapon
      name: Draw Steel
      power_roll:
        tiers:
            high: 16 damage
            low: 26 damage; [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
            mid: 22 damage; [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      sections:
        - label: Effect
          text: Each target makes a test using their highest characteristic.
      target: Each enemy and object in the area
      trailing: Ajax then raises his Blade of the Gol King above his head as four giant blades emerge from the ground to fill the area. Each target is [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) into an unoccupied space adjacent to the area after the power roll is resolved. Each blade blocks line of effect and can be dismissed by Ajax at will (no action required).
      usage: Main Action
file_basename: ajaxs-malice
file_dpath: monster/ajax-the-invincible
flavor: At the start of Ajax's turn, you can spend Malice to activate one of the following features.
item_id: ajaxs-malice
item_name: Ajax's Malice
kind: malice
name: Ajax's Malice
scc: mcdm.monsters.v1/monster.ajax-the-invincible/ajaxs-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: Ajax attempts to instill doubt into a creature within line of effect through logic and reason. The creature and Ajax make an opposed [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) test. If Ajax wins, he chooses to either deal 11 extra damage to one target on his next strike or to gain an additional [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) during the current round. Ajax can't use this feature against the same creature during the same encounter.
      cost: 2 Malice
      icon: "\U0001F464"
      name: Reason
    - body: Until the end of the round, Ajax chooses one of the following environments he has previously visited and overlays that environment on top of the encounter map, temporarily merging multiple realities.
      cost: 5 Malice
      icon: "\U0001F300"
      name: Nexus Jewel
      sections:
        - label: Incredibly High Above the Ground
          text: The winds whip and bluster. Any creature who can't [fly](scc.v1:mcdm.heroes.v1/movement/fly) takes a −3 penalty to stability, and [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) effects gain a +3 bonus to their distance against such creatures.
        - label: Swamp
          text: The ground is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies. Any creature who starts and ends their turn in the same space is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends).
        - label: Volcanic Canyon
          text: The air is stiflingly hot. Each enemy takes 5 fire damage for each square they enter.
    - body: Ajax takes an additional main action on his turn. He can use this feature even if he is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - cost: 10 Malice
      distance: Four 3 cubes within 10
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
        - Weapon
      name: Draw Steel
      power_roll:
        tiers:
            high: 16 damage
            low: 26 damage; [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
            mid: 22 damage; [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      sections:
        - label: Effect
          text: Each target makes a test using their highest characteristic.
      target: Each enemy and object in the area
      trailing: Ajax then raises his Blade of the Gol King above his head as four giant blades emerge from the ground to fill the area. Each target is [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) into an unoccupied space adjacent to the area after the power roll is resolved. Each blade blocks line of effect and can be dismissed by Ajax at will (no action required).
      usage: Main Action
flavor: At the start of Ajax's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.ajax-the-invincible/ajaxs-malice
    source: mcdm.monsters.v1
name: Ajax's Malice
type: featureblock
```
