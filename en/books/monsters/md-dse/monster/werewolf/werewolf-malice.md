---
features:
    - body: The werewolf gains 10 temporary [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and a +3 bonus to speed until the end of their turn. The werewolf can't use this feature if they took any holy damage since ending their last turn.
      cost: 3 Malice
      icon: ⭐️
      name: Blood In Their Eyes
    - body: The werewolf takes an additional main action on their turn. They can use this feature even if they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - body: Until the end of the encounter, the encounter map turns to night and the moon appears impossibly huge in the sky. The werewolf can take an additional move action or maneuver on each of their turns while they have line of effect to the moon. Any creature who ends their turn with line of effect to the moon with 1 or more rage gains 2 rag.
      cost: 10 Malice
      icon: "\U0001F300"
      name: Moonfall
file_basename: werewolf-malice
file_dpath: monster/werewolf
flavor: At the start of a werewolf's turn, you can spend Malice to activate one of the following features.
item_id: werewolf-malice
item_name: Werewolf Malice
kind: malice
name: Werewolf Malice
scc: mcdm.monsters.v1/monster.werewolf/werewolf-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: The werewolf gains 10 temporary [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and a +3 bonus to speed until the end of their turn. The werewolf can't use this feature if they took any holy damage since ending their last turn.
      cost: 3 Malice
      icon: ⭐️
      name: Blood In Their Eyes
    - body: The werewolf takes an additional main action on their turn. They can use this feature even if they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - body: Until the end of the encounter, the encounter map turns to night and the moon appears impossibly huge in the sky. The werewolf can take an additional move action or maneuver on each of their turns while they have line of effect to the moon. Any creature who ends their turn with line of effect to the moon with 1 or more rage gains 2 rag.
      cost: 10 Malice
      icon: "\U0001F300"
      name: Moonfall
flavor: At the start of a werewolf's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.werewolf/werewolf-malice
    source: mcdm.monsters.v1
name: Werewolf Malice
type: featureblock
```
