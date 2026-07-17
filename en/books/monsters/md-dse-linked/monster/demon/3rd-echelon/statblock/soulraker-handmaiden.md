---
agility: 0
ev: "10"
file_basename: soulraker-handmaiden
file_dpath: monster/demon/3rd-echelon/statblock
free_strike: 4
intuition: 2
item_id: soulraker-handmaiden
item_name: Soulraker Handmaiden
keywords:
    - Abyssal
    - Demon
    - Soulraker
level: 8
might: 3
name: Soulraker Handmaiden
organization: Horde
presence: 4
reason: 2
role: Ambusher
scc: mcdm.monsters.v1/monster.demon.3rd-echelon.statblock/soulraker-handmaiden
size: 1M
source: mcdm.monsters.v1
speed: 0
stability: 0
stamina: "50"
type: statblock
weaknesses:
    - Holy 5
---

```ds-sb
agility: 0
ev: "10"
features:
    - effects:
        - effect: |-
            A host creature implanted by a soulraker hivequeen's Stinging Ovipositor has no physical or mental signs of the handmaiden gestating inside the host's body.
            After 1d3 + 1 weeks of gestation, the handmaiden fully forms inside the host. The handmaiden always moves with and occupies the same space as the host and can't be separated from them. While totally within the creature, the handmaiden doesn't have [line of effect](../../../../rule/combat/line-of-effect.md) to the host or targets outside the host and vice versa. As a maneuver, the handmaiden can emerge from the host as a horrifying tower of flesh and bone that remains attached to the host's insides. While emerged, the handmaiden can use a move action to make the host move up to their speed and has access to the host's [signature abilities](../../../../rule/combat/signature-ability.md), using the host's modifiers for any power rolls. The handmaiden has the same [Stability](../../../../rule/character/stability.md) as the host. If the handmaiden or host is [force moved](../../../../movement/forced-movement.md), the other moves with them. While emerged, the handmaiden can be targeted independently of the host. The handmaiden can retreat totally within the host's body as a maneuver. If the handmaiden dies, their remains separate from the host.
            The [Find a Cure](../../../../project/find-a-cure.md) downtime project in Draw Steel: Heroes can be used to find a cure that removes a handmaiden from a host. The cure kills the handmaiden when consumed.
      feature_type: trait
      icon: ⭐️
      name: Implanted Parasite
      type: feature
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 4
          tier1: 8 corruption damage
          tier2: 11 corruption damage
          tier3: 13 corruption damage; M < 4 [frightened](../../../../condition/frightened.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Emergent Horrors
      target: One creature or object
      type: feature
      usage: Main action
    - effects:
        - effect: While the handmaiden is [winded](../../../../rule/health/winded.md), they gain an [edge](../../../../rule/dice/edge.md) on strikes, and any strike made against them gains an edge.
      feature_type: trait
      icon: ⭐️
      name: Lethe
      type: feature
free_strike: 4
intuition: 2
keywords:
    - Abyssal
    - Demon
    - Soulraker
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.demon.3rd-echelon.statblock/soulraker-handmaiden
    source: mcdm.monsters.v1
might: 3
name: Soulraker Handmaiden
organization: Horde
presence: 4
reason: 2
role: Ambusher
size: 1M
speed: 0
stability: 0
stamina: "50"
type: statblock
weaknesses:
    - Holy 5
```
