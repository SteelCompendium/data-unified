---
agility: 1
ev: "32"
file_basename: dorzinuuth-the-base
file_dpath: monster/draconian/statblock
free_strike: 7
immunities:
    - Lightning 6
intuition: 2
item_id: dorzinuuth-the-base
item_name: Dorzinuuth the Base
keywords:
    - Draconian
    - Dragon
    - Humanoid
level: 6
might: 4
movement: Fly, hover
name: Dorzinuuth the Base
organization: Leader
presence: 3
reason: 1
scc: mcdm.monsters.v1/monster.draconian.statblock/dorzinuuth-the-base
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 3
stamina: "180"
type: statblock
---

```ds-sb
agility: 1
ev: "32"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 4
          tier1: 11 damage; M < 2 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
          tier2: 16 damage; M < 3 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
          tier3: 19 damage; M < 4 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Punishing Flail
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: 5 x 2 line within 1
      effects:
        - roll: Power Roll + 4
          tier1: 7 damage
          tier2: 13 damage; M < 3 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
          tier3: 15 damage; M < 4 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Weapon
      name: I'll Cut A Path
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** An ally within distance takes damage while Dorzinuuth isn't [flying](scc.v1:mcdm.heroes.v1/movement/fly).
            **Effect:** Dorzinuuth shields the triggering ally with his wings, halving the damage.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Watch Your Six!
      target: One ally
      type: feature
      usage: Triggered action
    - effects:
        - effect: At the end of each of his turns, Dorzinuuth can take 10 damage to end one effect on him that can be ended by a saving throw. This damage can't be reduced in any way.
      feature_type: trait
      icon: ⭐️
      name: End Effect
      type: feature
    - effects:
        - effect: If Dorzinuuth hears a creature recite the Dragon Phalanx oath, he takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on strikes made against that character until the end of the encounter.
      feature_type: trait
      icon: ⭐️
      name: Remember Your Oath
      type: feature
    - effects:
        - effect: While Dorzinuuth isn't [flying](scc.v1:mcdm.heroes.v1/movement/fly), strikes made against him take a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane).
      feature_type: trait
      icon: ⭐️
      name: Sheltering Wings
      type: feature
    - cost: Villain Action 1
      distance: 5 burst
      effects:
        - roll: ""
          tier1: '[Frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)'
          tier2: '[Frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (EoT)'
          tier3: No effect.
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: Roaring Gambit
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: 10 burst
      effects:
        - effect: '**Effect:** Each target [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) or [flies](scc.v1:mcdm.heroes.v1/movement/fly) up to their speed and regains 10 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: Wings of Second Wind
      target: Self and each ally in the area
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 5 burst
      effects:
        - effect: '**Effect:** Dorzinuuth covers the targets in an electrifying mesh. Whenever a target takes damage from a melee ability, the attacker takes 6 lightning damage.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Snap, Crackle, Pop
      target: Each ally in the area
      type: feature
      usage: '-'
free_strike: 7
immunities:
    - Lightning 6
intuition: 2
keywords:
    - Draconian
    - Dragon
    - Humanoid
level: 6
metadata:
    scc: mcdm.monsters.v1/monster.draconian.statblock/dorzinuuth-the-base
    source: mcdm.monsters.v1
might: 4
movement: Fly, hover
name: Dorzinuuth the Base
organization: Leader
presence: 3
reason: 1
role: ""
size: "2"
speed: 5
stability: 3
stamina: "180"
type: statblock
```
