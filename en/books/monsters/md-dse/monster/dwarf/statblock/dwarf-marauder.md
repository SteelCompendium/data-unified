---
agility: 0
ev: "20"
file_basename: dwarf-marauder
file_dpath: monster/dwarf/statblock
free_strike: 5
intuition: 1
item_id: dwarf-marauder
item_name: Dwarf Marauder
keywords:
    - Dwarf
    - Humanoid
level: 3
might: 3
name: Dwarf Marauder
organization: Leader
presence: 0
reason: 2
scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-marauder
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 4
stamina: "132"
type: statblock
---

```ds-sb
agility: 0
ev: "20"
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 10
      effects:
        - roll: Power Roll + 3
          tier1: 8 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier2: 12 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
          tier3: 15 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
      feature_type: ability
      icon: ⚔️
      keywords:
        - Melee
        - Psionic
        - Ranged
        - Strike
        - Weapon
      name: Levitating Axes
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - effect: |-
            **Effect:** The target vertical [slides](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to 5 squares. A target [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) by a dwarf can be force moved by this ability. This forced movement doesn't end the [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) condition unless the Director determines otherwise.
            **5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** This ability takes the Area keyword and loses the Ranged keyword, its distance becomes a 10 burst, and it targets each [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) creature in the area.
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Psionic
        - Ranged
      name: Magnetomancy
      target: One creature or object
      type: feature
      usage: Maneuver
    - distance: Ranged 10
      effects:
        - effect: |-
            **Trigger:** A creature makes a melee strike against the target.
            **Effect:** The target halves any damage from the strike and the triggering creature takes 4 damage.
      feature_type: ability
      icon: ❗️
      keywords:
        - Psionic
        - Ranged
      name: Your Weapon Is Useless
      target: Self or one ally
      type: feature
      usage: Triggered action
    - effects:
        - effect: At the end of each of their turns, the marauder lord can take 5 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
      feature_type: trait
      icon: ⭐️
      name: End Effect
      type: feature
    - cost: Villain Action 1
      distance: 5 cube within 10
      effects:
        - effect: '**Effect:** The marauder lord uses Levitating Axes against each target, making one power roll against all targets.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Psionic
        - Ranged
        - Weapon
      name: Ajax Will Pay Well for These Specimens
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: 5 burst
      effects:
        - effect: '**Effect:** Each target shifts up to their speed. The marauder lord then uses Levitating Axes.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: Don't Let Them Escape!
      target: Each ally in the area
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: Ranged 10
      effects:
        - effect: '**Effect:** The marauder lord creates three size 2 metal objects in unoccupied spaces within distance. Whenever the marauder lord uses Magnetomancy, they can additionally target one of these objects.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Psionic
        - Ranged
      name: Test Your Metal!
      target: Special
      type: feature
      usage: '-'
free_strike: 5
intuition: 1
keywords:
    - Dwarf
    - Humanoid
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-marauder
    source: mcdm.monsters.v1
might: 3
name: Dwarf Marauder
organization: Leader
presence: 0
reason: 2
role: ""
size: 1M
speed: 5
stability: 4
stamina: "132"
type: statblock
```
