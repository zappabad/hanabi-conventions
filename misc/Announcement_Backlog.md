## Introduction

As noted in the [convention changes document](Convention_Changes.md), sometimes a change to the conventions is made but is not yet announced due to there being a backlog of things to announce. This document contains the backlog.

<br />

## The Backlog (General Conventions)

n/a

<br />

## The Backlog (Variant-Specific Conventions)

@everyone Clarified conventions:

**Precedence of Variant-Specific Conventions**

```
- We have many variant-specific strategies and conventions. Sometimes, it can be confusing as to how they interact with "normal" conventions (e.g. non-variant-specific conventions).
- In general, non-variant-specific conventions take precedence over variant-specific conventions, unless explicitly mentioned otherwise.
```

@everyone Deleted variant-specific conventions:

**Positional Finesses**

```
* *Positional Finesses* are deleted.
* This convention makes it hard to get null cards in certain situations. It is also a common point of failure.
```

@everyone Changed variant-specific conventions:

**Bluff Seat with Positional Clues**

```
* This convention only applies to variants with a null suit.
* Previously, you could give a *Positional Clue* to anyone on the team.
* Now, you can only give a *Positional Clue* if you are in *Bluff Seat*.
```

**Good Touch Principle with Positional Clues**

```
* This convention only applies to variants with a null suit.
* Previously, *Good Touch Principle* did not apply to cards touched as part of a *Positional Clue*.
* Now, *Good Touch Principle* does apply. If a trash card is touched as part of a *Positional Clue*, then it must be given a *Fix Clue*.
```

@everyone New variant-specific conventions:

**Gray Loaded Play Clues**

```
- This convention only applies to variants with a gray suit.
- Gray 3 must be saved with a number 3 clue and gray 4 must be saved with a number 4 suit.
- However, these cards cannot be saved "early" - any early save to these cards would instead be treated as a *Loaded Play Clue*.
```

**The Slot Finesse** (by Jeff)

```
- Normally, if a *Positional Clue* is used to get a non-null card, then the blind-playing player would continue blind-playing cards as a *Positional Layered Finesse*. For that reason, it is normally impossible to *just* get a non-null card with a *Positional Clue*.
- As a rare exception, players can perform a *Finesse* using a *Positional Clue* that has the blind-play "match" the card that was clued. If they match, then **no null cards are promised**.
- This is called a *Slot Finesse* to distinguish it from a *Positional Finesse*. In other words, *Positional Finesses* use *Positional Clues* to get null cards to blind-play into other null cards. And *Slot Finesses* use *Positional Clues* to get non-null cards to play into other non-null cards.
- For example, in a 3-player game of the "Null (6 Suits)" variant:
  - It is the first turn of the game and nothing is played on the stacks.
  - Alice clues number 2 to Cathy, touching a red 2 as a *Play Clue*.
  - Bob sees that Cathy has no other red cards in her hand, so Alice had a *Free Choice* between cluing red and cluing number 2. If Bob really had a red 1 on his *Finesse Position*, then Alice would clue red. Thus, this must be a *Rank Choice Positional Clue*.
  - Bob blind-plays his slot 2 card as a null 1. Instead, it is the red 1 and it successfully plays. Bob now knows that this must be a *Positional Layered Finesse*, so Bob marks his slot 3 card as the null 1.
  - Cathy knows that since Bob played slot 2 instead of slot 1, this must be a *Positional Clue*. However, Cathy also knows that you are only supposed to use *Positional Clues* to get null cards. So this must be a *Positional Layered Finesse* on Bob.
  - However, from Cathy's perspective, Bob has no null cards, so Alice must have been intending something else. If Cathy does nothing, then Bob will go on to misplay his slot 3 card as a null 1. Cathy knows that since a red 1 matches a number 2 clue, then this must be a *Slot Finesse*.
  - Cathy plays her 2 as a red 2 and it successfully plays.
  - Bob knows that cards clued as part of *Positional Clues* are not promised to be playable, so it was very strange that Cathy played her 2. This must mean that he does not have the null 1 after all and that Alice's clue was simply a *Slot Finesse*.
```

**The Slot Double Bluff** (by Jeff)

```
- Normally, if a *Positional Clue* is used to get a non-null card, then the blind-playing player would continue blind-playing cards as a *Positional Layered Finesse*. For that reason, it is normally impossible to *just* get a non-null card with a *Positional Clue*.
- One way to get the blind-playing player to stop searching for a null card is to perform a *Slot Finesse* (see above).
- One other way to get the blind-playing player to stop searching for a null card is to force the next player after that to blind-play their *Finesse Position* card (in the exact same way as a *Pestilent Double Bluff*). After seeing the second blind-play, the first player will know that it is impossible for them to have a layered null card.
- For example, in a 4-player game of the "Null (6 Suits)" variant:
  - All the 1's are played on the stacks.
  - Alice clues number 4 to Donald, touching a red 4 as a *Play Clue*.
  - Bob does not see anyone else have any red cards. And Bob knows that *Double Self-Finesses* are turned off in null variants, so this must be a *Positional Clue*.
  - Slot 4 is Bob's chop, so normally Bob would treat this as a *Positional Save Clue* on a null 5. However, Bob currently has a globally-known playable blue 2 in his hand on slot 1 (e.g. he is *Loaded*). That means that this is a *Loaded Play Clue* and that he has a playable null 2 on his slot 4.
  - Bob blind-plays slot 4 as null 2. It is instead a green 2 and it successfully plays. Bob now knows that this must be a *Positional Inverted Layered Finesse*, so Bob marks his slot 3 card as the null 2.
  - Cathy sees that since Bob did not play a null card, Bob will assume an *Positional Inverted Layered Finesse* and will go on to play his slot 3 on his next turn. However, Bob does not have any null cards in his hand. Alice must have intended for something else to happen.
  - Cathy knows that this must be a *Slot Double Bluff*, so she blind-plays her *Finesse Position* as any playable card. It is yellow 2 and it successfully plays.
  - Donald knows that from the sequence of events that Alice performed a *Slot Double Bluff*, so the 4 clue is to be treated as a *Positional Clue* (e.g. the 4 in his hand might be trash).
  - Bob sees that since Cathy blind-played her *Finesse Position* card for "no reason", he must not actually have the null 2 in his hand after all. Bob can reason that Alice performed a *Slot Double Bluff*.
```

**The Turnabout Ejection (For 1's and 5's)** (by pianoblook)

```
- If a player uses *Pink Promise* to falsely indicate a pink 1 as a pink 5 **or** a pink 5 as a pink 1, this is a dangerous lie that must be immediately resolved.
- In this situation, the next player must immediately play their *Second Finesse Position* to prove what happened. This is called a *Turnabout Ejection*.
- After the *Ejection*, the player who received the clue will know that the focused card's identity has been "reversed".
- For example, in a 3-player game:
  - It is the first turn and nothing is played on the stacks.
  - Alice clues number 5 to Cathy, which touches a pink 1 on Cathy's chop.
  - Bob knows that Alice is violating *Pink Promise*. This must be a *Turnabout Ejection*.
  - Bob blind-plays his *Second Finesse Position* (slot 2). It is a blue 1 and it successfully plays on the stacks.
  - At first, Cathy thought that the number 5 clue from Alice was a *5 Save*.
  - After Bob blind-plays, Cathy knows that Alice did not perform a *5 Save* and instead did something else.
  - Cathy knows that Alice did not perform a *Bubblegum Bluff*, because Bob would have played his slot 5 card instead of his slot 2 card.
  - Thus, Cathy knows that this must be a *Turnabout Ejection*. She marks her slot 5 card as a pink 1.
- If a *Turnabout Ejection* occurs from a number 1 clue that also touches other 1s, the non-focused cards should still be assumed to be 1s (using the *1's Assumption* convention).
```

**Dark Omni & Gray Pink Saves**

```
- This convention only applies in variants with a dark omni or gray pink suit.
- The rules for saving dark omni and gray pink suits have been slightly refined so that players can perform more 2-for-1 clues.
- See the doc for more details: https://github.com/Zamiell/hanabi-conventions/blob/master/variant-specific/Dark_Omni_&_Gray_Pink.md
```

**The Pink Fake Prompt & The Pink Fake Finesse** (by Jeff)

```
* This convention only applies to variants with a pink suit.
* First, read the section on the *[Pink Play Clue Lie](#the-pink-play-clue-lie-with-a-mismatched-play-clue-that-touches-other-cards)*.
* In the *Pink Play Clue Lie*, *Pink Promise* is violated when giving a *Play Clue* to a playable pink card. However, no special actions need to be taken from anyone else on the team, because the lie will automatically resolve when the card is played.
* In some special situations, it is possible to give a *Pink Play Clue Lie* that will **not** resolve automatically. In this situation, the next player must play a card to "fix" the lie.
* For example, in a 3-player game:
  * It is the first turn of the game and nothing is played on the stacks.
  * Alice gives a number 2 clue to Cathy, touching a pink 1 on slot 2. (Cathy does not have a playable card on slot 1.)
  * Bob looks into the future and knows that if he does nothing, Cathy will interpret this as a *Self-Finesse*, and play her *Finesse Position*, which will misplay.
  * Thus, Bob plays his *Finesse Position* as a *Pink Fake Finesse*. It is a blue 1 and it successfully plays.
  * From Cathy's perspective, Alice performed a *Finesse* on the blue 1 into the blue 2. Cathy plays the blue 2, but it is actually the pink 1. Now, Cathy knows that Alice performed a *Pink Fake Finesse*.
```
