# The Tactical Combat Sequence

`Round` - In a tactical situation, action is tracked in **rounds of 10 seconds**.

`Initiative` - determines the order in which combatants declare and resolve their actions.

`Action` - Actions include any activity the character performs including moving, attacking, reloading, applying first aid, retrieving items from a backpack, etc.

## Round
During a round, combatants take turns to perform actions, in order from __highest to lowest__ `initiative`.

Initiative is determined each round as changing conditions can alter the order in which the characters resolve their actions.

After all actions have been resolved the GM and players resolves any ongoing effects, like bleeding and stun.

A round consists of 3 steps:

- Step 1: __Roll Initiative__
- Step 2: __Resolve Actions__
- Step 3: __Upkeep__

### Initiative Step
Each combatants roll __2d10 + Quickness Bonus + Modifiers__ to determine their `initiative`.

| Condition | Modification |
| --- | --- |
| Weapon ready (first round of combat only) | +4 |
| Surprised | -4 |
| Encumbered | -4 |
| Wounded (taken more than 50% of hits) | -4 |

### Resolve Actions step
Combatants take turns and resolve `actions`, in order from __highest to lowest__ `initiative`. 

Each action takes a percentage of the character’s activity to accomplish, representing the ‘dedication’ required.

Combatants may normally use up to a total of 100% activity in a single round.

| Activity | percentages |
| --- | --- |
Movement / Moving Maneuver | Minimum 10%
Melee Attack/Parry | 60%-100%
Ranged Attack | 30%-60%
Dodge | 50%-100%
Ammo reload | 60%
Draw weapon/ammo/item | 20%
Changing weapons | 50%
Perception Roll | 10%-30%
Static Maneuver | Minimum 100%
Simple Actions (GM's Discretion) | 10%-30%
Complex Actions (GM's Discretion) | 20%-100

Actions with a % range (e.g. 50%-100%) can be performed at a penalty of __-1__ for each % less than the normal maximum.
Combatants may only declare 1 melee attack action per round.

### Upkeep step
End of turn each combatant:
- subtracts hits due to bleeding.
- reduces stun effects 1 round, starting with the most severe effect (Stunned/Unable to Parry, then Stunned, then Dazed).
- removes any staggered effect.

### Conditional Action
A conditional action is a held `action` that can be triggered when certain conditions are met later in the round. The action is resolved if and when the trigger condition occurs (interrupting the triggering action).
Conditional actions can be held for as long as the character can maintain unbroken concentration, until end of round. If the conditional action is never triggered, the action is lost.

### Instantaneous actions
Some `actions` occur so quickly they are treated as instantaneous (0 AP); the first such action costs 0 AP and is thus a "free" action taking no time during the `round`, however any further instantaneous actions performed that `round` take 1 AP each. This represents the fact that no action is strictly instantaneous.

### Round to Round Actions
Some `actions` may require more than 100% such as donning or removing armor, or picking a complicated lock. These actions take multiple `rounds` to complete and must usually be performed uninterrupted by other `actions` (although they may be combined with movement).
