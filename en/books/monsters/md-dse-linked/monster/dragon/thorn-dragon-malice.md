---
features:
    - body: A cage of thorns grows around one dragonsealed enemy on the encounter map, making that enemy [restrained](../../condition/restrained.md) until the end of their next turn.
      cost: 3 Malice
      icon: ⭐️
      name: Cage of Thorns
    - body: The dragon grows a 10 wall of briars in unoccupied spaces on the encounter map. The wall blocks [line of effect](../../rule/combat/line-of-effect.md) for all creatures except the dragon. Each square of the wall has 5 [Stamina](../../rule/health/stamina.md) and fire weakness 5. The area can be moved through but is [difficult terrain](../../movement/difficult-terrain.md). Any creature who is [force moved](../../movement/forced-movement.md) into or within the area takes 1 damage for each square of the area entered and is [bleeding](../../condition/bleeding.md) until the end of their next turn.
      cost: 5 Malice
      icon: "\U0001F533"
      name: Bramble Barricade
    - body: The dragon takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - cost: 7 Malice
      icon: "\U0001F300"
      intro: The dragon summons poisonous, biting thorns around their foes. Each enemy on the encounter map makes an **Agility test**.
      name: Afflictive Overgrowth
      power_roll:
        tiers:
            high: 5 poison damage; [bleeding](../../condition/bleeding.md) (EoT)
            low: 12 poison damage; [restrained](../../condition/restrained.md) (save ends)
            mid: 9 poison damage; [bleeding](../../condition/bleeding.md) (save ends)
file_basename: thorn-dragon-malice
file_dpath: monster/dragon
flavor: At the start of a thorn dragon's turn, you can spend Malice to activate one of the following features.
item_id: thorn-dragon-malice
item_name: Thorn Dragon Malice
kind: malice
name: Thorn Dragon Malice
scc: mcdm.monsters.v1/monster.dragon/thorn-dragon-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: A cage of thorns grows around one dragonsealed enemy on the encounter map, making that enemy [restrained](../../condition/restrained.md) until the end of their next turn.
      cost: 3 Malice
      icon: ⭐️
      name: Cage of Thorns
    - body: The dragon grows a 10 wall of briars in unoccupied spaces on the encounter map. The wall blocks [line of effect](../../rule/combat/line-of-effect.md) for all creatures except the dragon. Each square of the wall has 5 [Stamina](../../rule/health/stamina.md) and fire weakness 5. The area can be moved through but is [difficult terrain](../../movement/difficult-terrain.md). Any creature who is [force moved](../../movement/forced-movement.md) into or within the area takes 1 damage for each square of the area entered and is [bleeding](../../condition/bleeding.md) until the end of their next turn.
      cost: 5 Malice
      icon: "\U0001F533"
      name: Bramble Barricade
    - body: The dragon takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - cost: 7 Malice
      icon: "\U0001F300"
      intro: The dragon summons poisonous, biting thorns around their foes. Each enemy on the encounter map makes an **Agility test**.
      name: Afflictive Overgrowth
      power_roll:
        tiers:
            high: 5 poison damage; [bleeding](../../condition/bleeding.md) (EoT)
            low: 12 poison damage; [restrained](../../condition/restrained.md) (save ends)
            mid: 9 poison damage; [bleeding](../../condition/bleeding.md) (save ends)
flavor: At the start of a thorn dragon's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.dragon/thorn-dragon-malice
    source: mcdm.monsters.v1
name: Thorn Dragon Malice
type: featureblock
```
