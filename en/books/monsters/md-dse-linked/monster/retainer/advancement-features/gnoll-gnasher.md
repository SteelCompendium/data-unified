---
features:
    - cost: Encounter
      distance: Self
      icon: ❗️
      level: 4
      name: Frenzied Bite
      sections:
        - label: Trigger
          text: An enemy within 5 squares is reduced to 0 [Stamina](../../../rule/health/stamina.md).
        - label: Effect
          text: The gnasher moves up to their speed and can use their [signature ability](../../../rule/combat/signature-ability.md).
      target: Self
      usage: Triggered action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: Flurry of Fangs
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage
            low: 7 damage
            mid: 11 damage
      target: Three creatures or objects
      usage: Main action
    - cost: Encounter
      distance: Self
      icon: "\U0001F464"
      level: 10
      name: Horrific Feas
      sections:
        - label: Trigger
          text: The gnasher reduces a creature to 0 [Stamina](../../../rule/health/stamina.md).
        - label: Effect
          text: The gnasher consumes part of the target's body. The gnasher can spend a [Recovery](../../../rule/health/recoveries.md), and each enemy within 5 squares of the gnasher who has I < AVERAGE is [frightened](../../../condition/frightened.md) ([save](../../../rule/general/saving-throw.md) ends).
      target: Self
      usage: Main action
file_basename: gnoll-gnasher
file_dpath: monster/retainer/advancement-features
item_id: gnoll-gnasher
item_name: Gnoll Gnasher Advancement Features
name: Gnoll Gnasher Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/gnoll-gnasher
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - cost: Encounter
      distance: Self
      icon: ❗️
      level: 4
      name: Frenzied Bite
      sections:
        - label: Trigger
          text: An enemy within 5 squares is reduced to 0 [Stamina](../../../rule/health/stamina.md).
        - label: Effect
          text: The gnasher moves up to their speed and can use their [signature ability](../../../rule/combat/signature-ability.md).
      target: Self
      usage: Triggered action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: Flurry of Fangs
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage
            low: 7 damage
            mid: 11 damage
      target: Three creatures or objects
      usage: Main action
    - cost: Encounter
      distance: Self
      icon: "\U0001F464"
      level: 10
      name: Horrific Feas
      sections:
        - label: Trigger
          text: The gnasher reduces a creature to 0 [Stamina](../../../rule/health/stamina.md).
        - label: Effect
          text: The gnasher consumes part of the target's body. The gnasher can spend a [Recovery](../../../rule/health/recoveries.md), and each enemy within 5 squares of the gnasher who has I < AVERAGE is [frightened](../../../condition/frightened.md) ([save](../../../rule/general/saving-throw.md) ends).
      target: Self
      usage: Main action
metadata:
    scc: mcdm.monsters.v1/monster.retainer.advancement-features/gnoll-gnasher
    source: mcdm.monsters.v1
name: Gnoll Gnasher Advancement Features
type: featureblock
```
