---
agility: 0
ev: '-'
file_basename: hobgoblin-flameslinger
file_dpath: monster/retainer/statblock
free_strike: 5
immunities:
    - Fire 4
intuition: 1
item_id: hobgoblin-flameslinger
item_name: Hobgoblin Flameslinger
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 4
might: 1
name: Hobgoblin Flameslinger
organization: Retainer
presence: 3
reason: 2
role: Controller
scc: mcdm.monsters.v1/monster.retainer.statblock/hobgoblin-flameslinger
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "48"
type: statblock
---

```ds-sb
agility: 0
ev: '-'
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 5 fire damage
          tier2: 9 fire damage
          tier3: 12 fire damage; A < STRONG the target is burning (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Fire Curse
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - effect: '**Effect:** Until the end of the flameslinger''s next turn, the target has fire weakness equal to the flameslinger''s level. If the target is the flameslinger''s mentor, they instead have fire immunity equal to the flameslinger''s level.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Fuel for the Fire
      target: One creature
      type: feature
      usage: Main action
    - effects:
        - effect: When the flameslinger is reduced to 0 [Stamina](../../../rule/health/stamina.md), they spray buring blood. Each creature [adjacent](../../../rule/combat/adjacent.md) to the flameslinger takes 3 fire damage.
      feature_type: trait
      icon: ⭐️
      name: Infernal Ichor
      type: feature
free_strike: 5
immunities:
    - Fire 4
intuition: 1
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.retainer.statblock/hobgoblin-flameslinger
    source: mcdm.monsters.v1
might: 1
name: Hobgoblin Flameslinger
organization: Retainer
presence: 3
reason: 2
role: Controller
size: 1M
speed: 5
stability: 0
stamina: "48"
type: statblock
```
