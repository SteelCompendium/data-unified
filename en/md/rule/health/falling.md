---
name: Falling
scc: mcdm.heroes.v1/rule.health/falling
type: rule
---

When a creature falls 2 or more squares and lands on the ground, they take 2 damage for each square they fall (to a maximum of 50 damage) and l[and prone](scc:mcdm.heroes.v1/condition/prone). A creature who falls can reduce the effective height of the fall by a number of squares equal to their [Agility](scc:mcdm.heroes.v1/rule.character/agility) score (to a minimum of 0). Falling into liquid that is 1 square or more deep reduces the effective height of a fall by 4 squares (to a minimum of 0).

Falling is not [forced movement](scc:mcdm.heroes.v1/movement/forced-movement), but being force moved downward is considered falling. Movement from falling doesn't provoke opportunity attacks (see Opportunity Attacks below).

##### Falling Onto Another Creature

A creature who falls and lands on another creature causes that creature to take the same damage from the fall. The falling creature then lands prone in the nearest unoccupied space of their choice. If the falling creature's [size](scc:mcdm.heroes.v1/rule.character/size) is greater than the [Might](scc:mcdm.heroes.v1/rule.character/might) score of the creature they land on, that creature is [knocked prone](scc:mcdm.heroes.v1/condition/prone).

##### Falling Far

When a creature first falls from a great height, they fall 100 squares in the first round. At the end of each subsequent round that they remain falling, they fall another 100 squares.
