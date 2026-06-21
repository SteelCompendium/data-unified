---
file_basename: interest
file_dpath: rule/negotiation
item_id: interest
item_name: Interest
name: Interest
scc: mcdm.heroes.v1/rule.negotiation/interest
source: mcdm.heroes.v1
type: rule
---

An [NPC](../general/npc.md)'s interest represents how eager they are to make a deal with the heroes. Interest is graded on a scale of 0 (no interest) to 5 (the most possible interest). When a negotiation begins, an [NPC](../general/npc.md)'s interest is between 1 and 4. If the [NPC](../general/npc.md)'s interest goes to 5, they make a final offer and the negotiation ends (see Keep Going or Stop, below). If the [NPC](../general/npc.md)'s interest drops to 0, they end a negotiation without offering the heroes any deal.

Interest increases and decreases during the negotiation based on the arguments the heroes make.
