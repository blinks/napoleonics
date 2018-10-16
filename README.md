# Untitled Napoleonic Wars Game
Napoleonic Wars x Up Front.

## Objective
As Napoleon, bring Europe under your thumb. As the Coalition, keep Napoleon in check without going broke.

## Components
- A 20-area map of Europe and the surrounding area.
- Tokens (or cylinders) for National Will / Resources of each participant.
- A single ten-sided die, from 0 to 9.
- A pile of cubes for strength points.
- Two decks of cards (one for Napoleon, one for the Coalition).
  - 2 sets of Move cards from 1 to 10
  - 2 sets of Battle / Regroup cards from 1 to 10
  - Map cards: rivers, villages, cities. Each has a fixed mark for the defender's position (so the defender's standee can remain on the strategic map), while attackers (and reinforcements) are placed on the card in their tactical position.
  - Leader cards?

## Setup
Scenario-driven. For the first prototype, we'll work on the 1805 Ulm campaign leading up to Austerlitz in the [War of the Third Coalition](https://en.wikipedia.org/wiki/War_of_the_Third_Coalition).

- Fr. General Napoleon and 200k in Northern France.
- Au. General Mack and 200k in the Black Forest.
- Ru. General Kutusov and 100k in Russia.

(How many cubes should this be? Perhaps 20k per cube?)

Each player draws to their hand size, probably seven for the prototype. Players are also divided amongst the possible army groups, such that each player is on at most one side (France or the Coalition).

## Play
On your turn, play cards from your hand to your various army groups to take actions. Each army leader has a card limit that applies per-turn: you may not play more than that many cards in a single turn to that army.

### Operations
The numbers on cards are the _operations points_ (ops) that card provides. The more ops, the more of your army can act.

- Movement: Every full multiple of your army size allows your army to (1) move to an adjacent region, (2) engage with an army in your current region, or (3) disengage. (Multiple movement cards can be combined.)
   - Engage: Make a morale test. If the defender already has a tactical map, place your standee on it. Otherwise, they may play a tactical map card. If they don't, you can. If you don't, use any card as a "field". Place your standee on that card based on your position.
   - Disengage: Make a morale test. If you fail, your opponent may play a move (out of turn) to cancel your disengage. You still take losses.
   - Reorganize: Make a morale test, then you can move a subset of the cubes in your army, forming a new army group. It enters play with just the Move cards used for this action.
- Battle: If engaged with an enemy army, play on their morale stack to force a morale test with a negative modifier equal to the least of the battle ops and your army size. (Each battle card must be used alone.)
- Regroup: If not engaged with an enemy army, play on your own morale stack to make a morale test with no negative modifiers. Discard the result from your morale stack, oldest-card first.

### Morale Tests
Roll a d10 and add your army size. If the result is less than the number of cards in your morale stack, you take losses equal to half your result, rounded up. If you roll a natural zero, there's a random event instead.
