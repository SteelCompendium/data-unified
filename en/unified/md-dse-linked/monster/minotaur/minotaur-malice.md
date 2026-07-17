---
features:
    - body: For each 3 [Malice](../../rule/monster/malice.md) spent, one minotaur acting this turn gains a +4 bonus to speed and ignores [difficult terrain](../../movement/difficult-terrain.md) until the start of their next turn.
      cost: 3 Malice
      icon: "\U0001F464"
      name: Bull Rush
    - body: One minotaur acting this turn halves any damage they take, and can use the Knockback maneuver as a free triggered action whenever an enemy comes [adjacent](../../rule/combat/adjacent.md) to them, all until the start of their next turn.
      cost: 5 Malice
      icon: "\U0001F464"
      name: Cut the... Nonsense!
    - cost: 7 Malice
      icon: ❇️
      intro: All minotaurs in the encounter fill the area around them with psychic impressions of feeling lost and isolated. Each enemy within 5 squares of a minotaur is [teleported](../../movement/teleport.md) up to 5 squares and makes an **Intuition test**.
      name: Bullseye
      power_roll:
        tiers:
            high: No effect.
            low: The target has line of effect only within 3 squares and is [frightened](../../condition/frightened.md) of all minotaurs (save ends).
            mid: The target has line of effect only within 3 squares (EoT).
file_basename: minotaur-malice
file_dpath: monster/minotaur
flavor: At the start of any minotaur's turn, you can spend Malice to activate one of the following features.
item_id: minotaur-malice
item_name: Minotaur Malice
kind: malice
name: Minotaur Malice
scc: mcdm.monsters.v1/monster.minotaur/minotaur-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: For each 3 [Malice](../../rule/monster/malice.md) spent, one minotaur acting this turn gains a +4 bonus to speed and ignores [difficult terrain](../../movement/difficult-terrain.md) until the start of their next turn.
      cost: 3 Malice
      icon: "\U0001F464"
      name: Bull Rush
    - body: One minotaur acting this turn halves any damage they take, and can use the Knockback maneuver as a free triggered action whenever an enemy comes [adjacent](../../rule/combat/adjacent.md) to them, all until the start of their next turn.
      cost: 5 Malice
      icon: "\U0001F464"
      name: Cut the... Nonsense!
    - cost: 7 Malice
      icon: ❇️
      intro: All minotaurs in the encounter fill the area around them with psychic impressions of feeling lost and isolated. Each enemy within 5 squares of a minotaur is [teleported](../../movement/teleport.md) up to 5 squares and makes an **Intuition test**.
      name: Bullseye
      power_roll:
        tiers:
            high: No effect.
            low: The target has line of effect only within 3 squares and is [frightened](../../condition/frightened.md) of all minotaurs (save ends).
            mid: The target has line of effect only within 3 squares (EoT).
flavor: At the start of any minotaur's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.minotaur/minotaur-malice
    source: mcdm.monsters.v1
name: Minotaur Malice
type: featureblock
```
