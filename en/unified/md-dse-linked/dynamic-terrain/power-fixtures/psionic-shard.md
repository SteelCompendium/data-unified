---
features:
    - body: The psionic shard must be completely destroyed.
      icon: "\U0001F300"
      name: Deactivate
    - body: A psionic shard is attuned to one side in an encounter. While a psionic shard is intact, any damage dealt to each ally of the shard in the encounter is halved.
      icon: ⭐️
      name: Psionic Barrier
    - distance: Special
      icon: ❗️
      name: Psionic Pulse
      sections:
        - label: Trigger
          text: The shard is destroyed.
        - label: Effect
          text: The shard releases a shockwave channeled through each creature affected by Psionic Barrier. Each ally in the encounter is [dazed](../../condition/dazed.md) until the end of their next turn.
      target: Special
      usage: Free triggered action
file_basename: psionic-shard
file_dpath: dynamic-terrain/power-fixtures
flavor: A massive humming crystal makes the air around it feel thick.
item_id: psionic-shard
item_name: Psionic Shard
level: 5
name: Psionic Shard
role: Defender
scc: mcdm.monsters.v1/dynamic-terrain.power-fixtures/psionic-shard
source: mcdm.monsters.v1
stats:
    - name: EV
      value: "7"
    - name: Stamina
      value: "40"
    - name: Size
      value: "2"
terrain_type: Fortification
type: dynamic-terrain
---

```ds-fb
features:
    - body: The psionic shard must be completely destroyed.
      icon: "\U0001F300"
      name: Deactivate
    - body: A psionic shard is attuned to one side in an encounter. While a psionic shard is intact, any damage dealt to each ally of the shard in the encounter is halved.
      icon: ⭐️
      name: Psionic Barrier
    - distance: Special
      icon: ❗️
      name: Psionic Pulse
      sections:
        - label: Trigger
          text: The shard is destroyed.
        - label: Effect
          text: The shard releases a shockwave channeled through each creature affected by Psionic Barrier. Each ally in the encounter is [dazed](../../condition/dazed.md) until the end of their next turn.
      target: Special
      usage: Free triggered action
flavor: A massive humming crystal makes the air around it feel thick.
level: 5
metadata:
    scc: mcdm.monsters.v1/dynamic-terrain.power-fixtures/psionic-shard
    source: mcdm.monsters.v1
name: Psionic Shard
role: Defender
stats:
    - name: EV
      value: "7"
    - name: Stamina
      value: "40"
    - name: Size
      value: "2"
terrain_type: Fortification
type: dynamic-terrain
```
