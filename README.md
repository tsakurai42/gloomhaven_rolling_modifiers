# Testing rolling modifier effect on attacks with advantage, using Scoundrel as a test

Advantage negates the chance of missing with an attack, since when you compare two cards, miss can never be the better card.

However, with Gloomhaven's rules, advantage with rolling modifiers applies thusly:

* If one card is rolling, add its effect to the other card drawn

* If both are rolling, continue drawing until a non-rolling is drawn and combine

Thus it is possible to miss with rolling, so how much average damage do you gain for the possibility of MISSING completely?

The default deck is: x0, x2, +0, +0, +0, +0, +0, +0, +1, +1, +1, +1, +1, -1, -1, -1, -1, -1, +2, -2

The no-rolling deck adds the following perks:
* Remove 2 -1 cards
* Remove 2 -1 cards
* Remove 4 +0 cards
* Replace one -2 card with one +0 card
* Replace one -1 card with one +1 card
* Replace one +0 card with one +2 card
* Replace one +0 card with one +2 card

The rolling deck adds the following perks to the above:
* Add two rolling +1 cards
* Add two rolling +1 cards

Thus:
* Non-rolling: x0, x2, +0, +1, +1, +1, +1, +1, +1, +2, +2, +2
* Rolling: x0, x2, +0, +1, +1, +1, +1, +1, +1, +2, +2, +2, +1 Rolling, +1 Rolling, +1 Rolling, +1 Rolling

# The Results!

# So is it worth it to take those perks?

Over 500000 rounds, the mean damage for the non-rolling deck was 4.8 damage per "roll"/round while the rolling deck is 4.91 damage per "roll"/round. There are even certain rounds where the damage for the rolling deck hit 14 ((3+1+1+1+1)x2). The 4 +1 rolling attack modifiers add about 0.1 damage per round.

## HOWEVER...

The increased damage comes at a cost. The rolling modifiers increase the chance of a complete miss (zero damage) from 0 to almost 5%. In a game where expected damage is king, knowing that you will at least get 3 damage, and most likely get 4 or 5 damage is much more valuable than a chance of getting a very high damage number.
