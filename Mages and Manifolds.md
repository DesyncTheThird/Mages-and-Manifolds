# Components

Combat:
- Rune Board
- Rune Tile Deck (x40)
- Player Spell Pointers (x4)
- Enemy Spell Pointer
- Hazard Tokens (x40)
- Mana Card Deck (x45)
- Status Effect Deck (x25)
- Skill Card Deck (x78)
- Rare Skill Card Deck (x33)
- Curse Deck (x28)
- Resistance/Vulnerability Tokens

Dungeon setup:
- Event Deck (x39)
- Monster Encounter Cards (x15)
- Elite Encounter Cards (x9)
- Boss Encounter Cards (x6)

Reward/Merchant:
- Misc Item Tokens (x25)
- Relic Deck (x59)
- Boss Relic Deck (x10)

Misc:
- Player Sheet (x6)
- Boss Health Tracker
- Dice (**D4**, **D6**, **D10**, **D12** **D20**)



# Setup

## Characters


### Basic Stats (All Characters)


Maximum Health:
- 60

Cast Speed:
- 2

Draw:
- 3

Hand Size:
- 7

Maximum Potions:
- 3

Starting Combat Deck:
- 2 Flame
- 2 Spark
- 4 Defend
- 2 Mend
- 2 Prepare
- 1 Focus
- 1 Delta
- 1 Epsilon




### The Mage

Description:
- The vanilla *Mages & Manifolds* experience.

Passive abilities:
- Reveal an additional card when drafting.

Special ability:
- You may reroll each Reward once.



### The Apprentice

Description:
- More forgiving casting, and no special twists.

Passive abilities:
- Transitions that leave the Rune board map to the opposite side of the board.
- Roll for 2 additional accepting tiles at the beginning of each dungeon.

Special ability:
- Once per combat, activate an Epsilon transition. This ability can only be activated at the beginning of your turn.



### The Rogue

Description:
- Specialises in stealth and adaptability.

Passive abilities:
- Gain an instant Epsilon transition the first time you would collide with the enemy Spell Pointer each combat.
- Disarm the first Hazard tile encountered each combat.
- Lose an additional Health every time you take damage.
- Whenever you would lose less than 4 Health, lose 4 Health instead.

Special ability:
- Once per combat, reroll all enemy Intentions.



### The Alchemist

Description:
- Tranform and manipulate Mana.

Passive abilities:
- Draw an extra mana card each turn.
- Gain 1 Cast Speed.
- Can only have two kinds of Mana in the Casting Queue at once. (Mana that has been Consumed or Accumulated does not count towards this restriction.)

Special ability:
- Once per turn, you may discard two Mana card of the same type from your hand to convert all of one type of Mana in your Casting Queue to the discarded type.



### The Spellsword

Description:
- Specialises in Skill combat; Spells cannot directly damage enemies.

Passive abilities:
- Spells deal no damage to enemies.
- Draw two additional cards each turn.
- Reveal an additional card when drafting.
- At the end of combat, draft an additional card.

Special ability:
- Once per turn, you may convert one Mana in your Casting Queue to a different type.



### The Outsider

Description:
- Weak to elemental damage, but can channel Void mana at will.

Passive abilities:
- Vulnerable to all elemental damage.
- Gain 1 Phantasmal at the beginning of combat.
- Void mana does not block Mana Consumption.

Special Ability:
- Once per turn, you may channel a Void mana. This ability can only be activated at the beginning of your turn.


### The Thaumaturge

Description:
- Powerful but complex Spells. For experienced players.

Passive abilities:
- Draw an extra mana card each turn.
- Gain 1 Cast Speed.
- Spells shorter than 5 symbols long Misfire.
- Take full damage from Misfires.

Special ability:
- Once per turn, you may rotate two additional unoccupied Rune tiles of your choice. This ability can only be activated at the beginning of your turn.



### The Ascetic



### The Elementalist

Description:
- Master the elements.

Passive abilities:
- Scorch, Flood, Shock, and Shatter two tiles at the beginning of each combat.
- Resist damage from Scorch and Shock.
- Gain Block instead of Ward.

Special ability:
- Once per turn, expend the top Mana from the Casting Queue and:
   - Scorch, Flood, Shock, or Shatter a tile under or adjacent to the Spell Pointer (matching the expended Mana);

  *or*

   - Remove a single elemental Hazard on a tile adjacent to the Spell Pointer (matching the expended Mana).

  This ability may only be activated at the beginning of your turn.



### The Archivist


Description:
- The Archivist excels in managing and reusing limited resources.

Passive abilities:
- Whenever you play a Skill, shuffle a card from your discard pile back into your Combat deck and draw one Mana.
- Whenever you channel 3 Mana in one turn, draw three Skills.
- Draw one extra card each turn.


Special ability:
- Once per turn, you may change your Casting Queue into a Stack, or vice versa. This ability can only be activated at the beginning of your turn and has a cooldown of 2 turns.







# Beginning a Dungeon

Add the following to your inventory:
- Six [Rations](#ration-pack);
- Three [Laudanum](#laudanum);
- Two [Healing Salves](#healing-salve);
- One [Bandage](#bandages);
- One [Blessed Water](#blessed-water).

Draw 19 tiles from the Rune Deck and arrange them on the Rune board as labeled, in order. You may choose the rotation of each tile at will, apart from the *initial tiles* 11 and 17 (or if playing with 2 players, tiles 10, 12, and 17), whose transitions must not point off the board. If no rotation will facilitate this, redraw these tiles until this is possible.
```
         16   17   18
      15    6    7   19
    14    5    1    2    8
      13    4    3    9
         12   11   10
```
Roll a **D20** three times, and add the *Target* marker to the indicated tile. If the dice rolls 20, reroll two additional times.



# Combat

## Setup

1. Draw 7 *Mana cards* from the *Mana deck*. If you draw 4 or more of the same kind of Mana, you may choose to discard and redraw your Mana hand.
2. You must immediately channel at least 3 Mana from your hand into your *Casting Queue* at the start of each combat.
3. Draw 3 *Skill cards* from your *Combat deck*.
4. Place your *Spell Pointer* on tile 11, and the *Enemy Spell Pointer* on tile 17. If playing with 2 players, place Player 1's Spell Pointers on tile 12, and Player 2's Spell Pointers on tile 10.
4. Reveal the enemy card and commence combat.


## Turn Phases
After initial setup, the phases in a normal turn are as follows:
- [Reset](#reset-phase)
- [Draw](#draw-phase)
- [Channelling](#channelling-phase)
- [Casting](#casting-phase)
- [Enemy actions](#enemy-actions)
- ([Decay](#decay))

### Reset Phase

- Remove leftover block from the previous turn.
- For each enemy, roll a **D6** to determine [enemy Intentions](#enemy-intentions) (if applicable).


### Draw Phase

Draw *five* cards total from your Mana and Combat decks (you may divide your draws however you like). Non-specific modifiers to draw affect this number (some modifiers will specify Mana or Skill draw).

If your Combat Deck is emptied, shuffle the Discard pile back into the Combat Deck.

### Channelling Phase
If playing with 2 players, take your turns simultaneously.

- If your initial tile is unoccupied, you may add a new Spell Pointer there. There may be up to 2 concurrent spells cast by the Player(s) at once.

- Then, you may channel up to 3 Mana from your hand into any existing Casting Queue. The 3 Mana may be distributed between Queues at will.



### Casting Phase

The following may be performed in any order.

- Select two unoccupied Rune tiles and change their rotations.



- You may play any Skill cards from your Hand. The Mana cost of a Skill must be *Consumed* from a single Casting Queue, and furthermore, the first available Mana from the top of the Casting Queue must be Consumed. For instance, if your Queue is:

       (Head) `[Fire - Ice - Lightning - Fire - Earth - Ice]` (Tail)
    and you play a Skill that requires 1 Fire and 1 Ice Mana, then you must take the newest Mana possible:

       (Head) `[Fire - Ice - Lightning - Earth]` (Tail)
    Consumed Mana is discarded and not Accumulated.
    
    Resolve [enemy defensive actions](#enemy-actions) before applying damage from Skills.



- For each Cast Speed, collect one Mana from the head of the Casting Queue into an *Accumulation Stack* and move the associated Spell Pointer along transitions accordingly. Perform these actions separately for each Spell Pointer.

  Spell Pointers cannot be partially resolved. That is, if your Cast Speed is 2, then you cannot move a Pointer one tile, play a Skill, then finish moving the Pointer after.

  If a Casting Queue is empty and the associated Spell Pointer is on an Accepting tile, the Spell is successfully [*Resolved*](#resolution).
  
  Otherwise, the Spell [*Misfires*](#Misfires). If two Spell Pointers collides, both Spells Misfire.

Whenever your last Spell Resolves or Misfires, instantly start a new Spell and channel the top 3 Mana from your Mana deck.



#### Spell Phase

Some special effects may also instantly Resolve Spells outside of the normal Accepting Tile process. Whenever this happens, all Queued Mana counts as Accumulated.

When a Spell successfully resolves, it deals damage to **one** enemy as follows:

1. Count the Accumulated Mana and convert to damage as follows:

   |                  |        |
   | ---------------- | ------ |
   | Mana Accumulated | Damage |
   | 1                | 1      |
   | 2                | 2      |
   | 3                | 3      |
   | 4                | 5      |
   | 5                | 7      |
   | 6                | 10     |
   | 7                | 12     |
   | 8+               | 16     |

2. Deal this much damage as the type of the final Mana Accumulated to **one enemy**;

Resolve [enemy defensive actions](#enemy-actions) before applying damage.



#### Misfires

A **Player** Spell will *Misfire* if it:
- Resolves on a tile that is not Accepting;
- collides with any other Spell;
- takes a transition that leaves the board;
- takes a transition to an invalid state.

An **Enemy** Spell will Misfire if it:
- Resolves on a tile that is Accepting;
- collides with any other Spell.

(If an enemy Spell leaves the board or takes a transition to an invalid state, it successfully Resolves instead.)

Upon a Misfire, the caster takes half the damage of the Misfired Spell (rounded up) and gain one *Stress*.

## Damage Resistance and Vulnerability
Enemies and players take **half** damage (rounded up) from Resisted damage types, and **double** damage (rounded down) from Vulnerabilities.

[Resistance](#resistance) and [Vulnerability tokens](#vulnerable) apply the associated effect for **all** damage types (apart from [Void damage](#void-mana), which ignores all Resistances and Vulnerabilities).

If you are Vulnerable and Resistant to the same damage type, they cancel out and no damage multipliers are applied. Having multiple sources of Vulnerability and Resistance do not have additional effect, e.g. if you are on a [Shattered](#shattered-earth) tile and have any positive number of Resistance tokens, the two effects simply cancel out.



### Enemy Actions

After all Spells Resolve and Skills have been played, enemies finally perform the listed *Intention* action(s) on their card. (Defensive actions may be triggered earlier.)

The leftmost enemy acts first, before proceeding rightwards.

- If an action does not have a listed number, it is activated every turn.
- If several unnumbered actions are listed, cycle through them each turn.
- Otherwise, the enemy takes the action corresponding to the number that the [dice rolled at the start of the turn](#setup-2).

[Status cards](#status-effects) activate at the very end of the turn.



### Decay

Each combat has a *Decay Counter*, and some additionally have a *Decay effect*.

If the turn counter is equal to the Decay Counter, activate the Decay effect at this point.

While Decay is active, gain 1 Stress every turn.





# Combat Mechanics

## Void Mana
Void Mana is a potent but dangerous type of Mana:
- Void Mana can take any transition.
- Mana further in the Casting Queue than a Void Mana cannot be consumed for Skills.
- Misfires with cause an additional Stress per Void Mana channelled/accumulated.
- Void damage bypasses Block and Ward.
- Void damage ignores Resistances and Vulnerabilities.


## Accumulation
The process of collecting Mana from a Casting Queue into a Spell.

Distinct from *Consuming* Mana for Skills.

## Epsilon/Delta Transitions
An Epsilon transition allows a Spell Pointer to move to any tile without accumulating Mana.

A Delta transition allows a Spell Pointer to move to an adjacent tile without accumulating Mana.

## Health
Whenever your Health total reaches zero or less each combat, gain **Death's Door** and increase your Stress to **18+X**, where **X** is the number of times your character has been on Death's Door this combat.

Taking any damage while on Death's Door will kill your character and end the expedition.

If your Health is healed back to a positive value, remove **Death's Door**.


## Block
- Temporary hitpoints that are removed at the end of each turn.
- Take damage from Block before Health.
- Void damage bypasses Block.

## Ward
- Temporary hitpoints that are removed at the end of combat.
- Take damage from Ward before Health.
- Void damage bypasses Ward.


## Stress

Upon accumulating 10 total Stress, your hero will be *tested* and gain a random *Stress effect*:
1.  Heal 4 Stress.
2.  Heal 2 Health, gain 1 Phantasmal.
3.  Gain 1 Vulnerable.
4.  Channel three Mana from hand. If Mana is not available, remove two Health for each  Mana deficit.
5.  Scorch three random Rune tiles and double Cast Speed for next turn.
6.  Flood two random Rune tiles and channel all Lightning Mana from hand.
7.  Shock two random Rune tiles and channel all Ice Mana from hand..
8.  Warp two random Rune tiles.
9.  Exhaust your next Skill card.
10. Gain one Curse.

If playing with 2 players, roll a **D12** instead, and add the following possible effects:
11. Your next Spell will target a random ally instead. If the Spell Misfires, then hit all allies.
12. Your next damaging Skill will target a random ally instead. If the Skill targets all or multiple enemies, target all allies instead.

If a Stress effect that is already active is rolled, take the next higher available effect. Note that effect 10 (Gain one Curse) will always count as available.

Stress effects that affect the Rune board will re-trigger every combat until Stress is reduced to 2 or lower.

Stress can continue to accumulate, and you will gain another random Stress effect for every 2 points of Stress past 10. Healing then regaining Stress does not give additional Stress effects until Stress has been completely cleared, e.g. if you have 2 Stress effects from having 12 Stress, then heal 4 Stress down to 8, you do not gain additional Stress effects from later reaching 10 or 12 Stress, as these are already considered active.

Reaching 20 points of Stress mid-combat will instantly kill your character.




## Hazards

Rune tiles may be afflicted with various Hazards that affect the caster when entered; mark hazards on the rune board with the relevant tokens.

Enemies do not take damage from Hazards, but Resistance and Vulnerability modifiers still apply (to every enemy in an encounter).

Hazards are removed at the end of combat.

#### Scorched (Fire):
Upon *entering* a Scorched tile, take **8-X** Fire damage, where **X** is the number of Accumulated Ice Mana.

While on a Scorched tile, the caster becomes
- Vulnerable to Lightning damage.
- Resistant to Ice damage.

If an Ice transition is used to *leave* a Scorched tile, the Hazard is removed.
If a Fire transition is used to *leave*, the Hazard spreads to the next tile the Spell Pointer moves to.


#### Flooded (Ice):
Upon *entering* a Flooded tile, take **X** Lightning damage, where **X** is the number of Accumulated Lightning Mana.

While on a Flooded tile, the caster becomes:
- Vulnerable to Earth damage.
- Resistant to Fire damage.

If a Fire transition is used to *leave* a Flooded tile, the Hazard is removed.
If a Lightning transition is used to *leave*, the Spell instantly Misfires.
If an Ice transition is used to *leave*, the Hazard spreads to the next tile the Spell Pointer moves to.


#### Shocked (Lightning):
Upon *entering* a Shocked tile, take **2\*X** Lightning damage, where **X** is the number of Accumulated Ice Mana.

While on a Shocked tile, the caster becomes:
- Vulnerable to Ice damage.
- Resistant to Earth damage.

If an Earth transition is used to *leave* a Shocked tile, the Hazard is removed.


#### Shattered (Earth):
If a Fire transition is used to *enter or exit* a Shattered tile, the caster takes **X** Earth damage, where **X** is the total number of channelled Fire and Earth Mana.

While on a Shattered tile, the caster becomes:
- Vulnerable to all damage types.

If a Lightning transition is used to *leave* a Shattered tile, the Hazard is removed.


#### Warped (Void):
Upon *entering* a Warped tile, take **X** Void damage, where **X** is the number of channelled Mana.

While on a Warped tile, Damage Resistances and Vulnerability are inverted, and outbound Fire/Ice and Lightning/Earth transitions are swapped.


#### Infested:
Upon *entering* an Infested tile, shuffle 2 Poison into Combat deck.

While on an Infested tile, Skills cost an additional generic Mana.

When leaving an Infested tile, the Hazard moves to the tile in the opposite direction; if the infestation leaves the rune board, gain a Curse.

If a Fire transition is used to *leave* an Infested tile, the Hazard is removed instead.

(Infestation has no effect on enemies.)











# Non-combat Mechanics

## Rewards

### Small Reward

Gain **D4** Gold.
Roll a **D10** and gain one of the following:
1.  2 Rations
2.  3 Rations
3.  1 Key
4.  1 Healing Salve
5.  2 Healing Salve
6.  1 Bandages
7.  1 Laudanum
8.  2 Laudanum
9.  1 Blessed Water
10. Random [Potion](#Potion)

### Large Reward

Gain **2\*D4** Gold.
Roll a **D10** and gain one of the following:
1.  3 Rations
2.  4 Rations
3.  2 Keys
4.  2 Healing Salve
5.  2 Bandages
6.  2 Laudanum
7.  2 Blessed Water
8.  Random [Relic](#Relic)
9.  Random [Potion](#Potion)
10. Random [Potion](#Potion)



### Draft
If instructed to, for example, "draft **two** of **five** cards", reveal the top **five** cards of the Reward Deck and select ***up to* two** to add to your Combat Deck.

Whenever you reveal a Golden Card, replace it with the top card of the Rare Reward Deck.

Shuffle the other unselected cards back into their respective Reward Decks.

You may choose to skip adding any cards.

### Rare Draft
Reveal the top **three** cards of the Rare Reward Deck and select **one** to add to your Combat Deck.

You may choose to skip adding a card.


### Potion
Draw a card from the Potion Deck.

You may choose to skip adding a Potion.

### Relic
Draw a card from the Relic Deck.

You may choose to skip adding a Relic.

### Boss Relic
After defeating a boss, reveal the top **three** cards of the Boss Relic Deck, and select **one** to keep.

You may choose to skip adding a Relic.





## Camping

## Merchants

Draw 3 Relics, 3 Potions, and 3 Skill cards and place them on the indicated spaces on the Merchant Board.

Roll a **D6**. If the dice rolls a 6, the leftmost Relic, Potion, and Skill card are 2 Gold Cheaper.

Prices:
- Cards:
  - Common: 5 Gold
  - Uncommon: 7 Gold
  - Rare: 15 Gold
  - Remove a card: 5 Gold (Once per merchant.)
- Potions: 5 Gold
- Relics: 10 Gold


# Keywords

## Weight
Maximum hand size is 7 by default.

- A card with Weight **X** counts as **X** many cards.
- Unless specified otherwise, Skill cards have Weight 1.

## Exhaust
- Discard to a separate Exhaust pile.
- Does not get reshuffled back into draw deck until end of combat.

## Ephemeral
- Discard at the end of your turn.

## Phantasmal
- The next instance of damage taken is reduced to 1.
- Removed after the next instance of damage.

## Vulnerable
Place a Vulnerability Counter on the affected target.
- Causes Vulnerability to all damage types.
- Removed after the next instance of damage.

## Resistant
Place a Resistance Counter on the affected target.
- Grants Resistance to all damage types.
- Removed after the next instance of damage.




# Ascension
After your previous successful raids, the twisted dungeon grows stronger. Activate the following Ascension levels for an increased challenge.

Each time you beat a dungeon at Ascension level **X**, unlock Ascension level **X+1**.

Ascension effects are cumulative.

1.  Scorch and Shatter one Rune at the beginning of each dungeon.
2.  Decay activates 2 turns earlier.
3.  Misfires deal full damage to casters and deal one additional Stress.
4.  Start each dungeon with 75% Health (rounded down).
5.  Start each dungeon with a random Curse.
6.  Only heal 50% hp after Boss battles.
7.  Add one Looming Fate card into your Combat deck. This card cannot be removed.
8.  At the beginning of each dungeon, roll a **D20** and remove that Rune from the Rune board. If the dice rolls 20, reroll once.
9.  Infest one Rune at the beginning of each dungeon. This tile cannot be cleansed.
10. Enemy Spells now deal one additional Stress.
11. When drafting, reveal one fewer card.
12. Draw one fewer card at the start of each combat.






# Skills

## Status Effects


### Bleeding
- While this card is in hand, lose 1 Health each turn.
- Exhaust.

Cost:
- 1 Fire Mana

### Poisoned
- Automatically played when drawn.
- Lose 2 Health.
- Gain 1 Stress.
- Exhaust.

### Burn
- Take 2 Fire damage at the end of your turn.
- Exhaust at end of your turn.

### Sapped
- Discard two Mana from hand.
- Exhaust.

Cost:
- 1 Earth Mana

### Hex
- Weight 2
- Exhaust.

Cost:
- 2 Generic Mana









## Curses

### Looming Fate
"A shadow of inevitable doom weighs down your every move..."
- Automatically played when drawn.
- Gain 1 Stress.
- Cannot be removed.

### Greed
"Your desires will mislead you."
- Discard one card.
- Gain 1 Stress.
- Weight 2

Cost:
- 3 Generic Mana

### Apathy
"The weight of disinterest drains your will to act."
- While this card is in your hand, you can only play 1 Skill per turn.
- Weight 3
- Cannot be played.

### Wrath
"Rage consumes you."
- Automatically played along with your next Skill.
- Your next Skill costs no mana and is exhausted.
- Take **X** Void damage, where **X** is the number of Skill cards in hand.
- Cannot be played.

This card is shuffled into your draw pile rather than discard pile.

### Impermanence
"Nothing will remain."
- Discard 3 other cards when drawn.
- Weight 4
- Cannot be played.
- [Ephemeral](#Ephemeral).

### Pride
"Only the weak will yield."
- While this card is in your hand, you cannot take Epsilon or Delta transitions.
- Cannot be played.
- Weight 2

### Impatience
"Impatience breeds imprecision."
- While this card is in your hand, if a Casting Queue ever has more than 4 Mana channelled, the Spell instantly Misfires.
- Mana accumulation is capped to 4.
- While this card is in your hand, gain one Cast Speed.
- Cannot be played.

### Shame
"Every mistake weighs heavier and heavier still..."
- Weight **X**, where **X** is the number of turns this card has been in your hand.

Cost:
- **X** generic Mana.

### Hubris
"You invoke power beyond your means..."
- While this card is in your hand, if your channelled Spell has more than 3 Mana of the same type, take 4 Void damage.
- Cannot be played.

### Blighted
"The infestation spreads..."
- Automatically played when drawn.
- Heal 4 Health.
- Gain 2 Stress.

This card is shuffled into your draw pile rather than discard pile.

### Overload
"The spell’s unbalanced energy cascades beyond your control."
- While this card is in hand, if a Casting Queue ever has three consective mana of the same type, the Spell instantly Misfires.
- While this card is in your hand, gain one Cast Speed.
- Cannot be played.

### Dissonance
"The air becomes as thick as tar..."
- While this card is in your hand, healing instead causes damage.

Cost:
- 3 Ice Mana

### Fractured Thoughts
"Your mind tears and splinters..."
- While this card is in your hand, become Vulnerable to all damage types.
- While this card is in your hand, your Spells hit all enemies.
- Gain 2 Stress every turn.

Cost:
- 3 Generic Mana

### Visions
"You see yourself fall, impaled by countless daggers."
- While this card is in hand, lose 1 Health every time Mana is channelled.
- While this card is in hand, gain 1 Stress every time a Skill is played.
- Weight 2

Cost:
- 3 Generic Mana

### Remorse
"The fires of guilt consumes you."
- While this card is in hand, lose 2 Health every time Fire Mana is channelled.
- Gain 2 Stress and discard this card when Ice Mana is Accumulated.
- Cannot be played.

This card is shuffled into your draw pile rather than discard pile.

### Nightmares
"Reality twists and tears at the edges of your vision."
- Automatically played when drawn.
- Gain 2 Stress.

### Festering Wound
"Torn stitches and seeping pus..."
- Automatically played when drawn.
- Gain 1 Stress.
- Lose 2 Health.

### Insatiable Hunger
"A gnawing emptiness consumes you."
- Automatically played when drawn.
- Consume 3 channelled Mana from the head of a Casting Queue. If this empties the Queue, the Spell Misfires.

### Collapsing Will
"Your resolve crumbles..."
- While this card is in hand, Skills cost an additional generic Mana.
- Cannot be played.

### Parasitic Influence
"The host grows weaker..."
- Automatically played when drawn.
- Lose 1 Maximum Health.

### Tearing Wounds
"Weaker and weaker still..."
- While this card is in hand, lose 2 Health every time Ice Mana is channelled.
- Gain 2 Stress and discard this card when Fire Mana is Accumulated.
- Cannot be played.

### Haemophilia
"A single cut can become a river when left untended."
- While this card is in hand, lose 1 Health each turn.
- Exhaust.

Cost:
- 2 Fire Mana

### Doubt
"A frost creeps not on the surface, but within the soul, paralyzing resolve."
- Whenever you gain Block, lose an equal amount of Ward.
- Cannot be played.

### Brittle Resolve
"The cold is not merely an absence of warmth but a relentless presence that demands stillness."
- While this card is in hand, take 2 Ice damage every time a Skill is played.

Cost:
- 2 Ice Mana

### Crackling Static
"The air hums with tension, each step drawing closer to a sudden, shattering burst."
- Automatically played when drawn.
- Channel 1 Lightning Mana.
- Gain 1 Stress for each type of Mana in your Casting Queue(s).

### Static Discharge
"Nervous shivers and twitching hands..."
- Automatically played when drawn.
- Take **X** Lightning damage, where **X** is the number of Skill cards in hand.

### Virulent Toxins
"It spreads like whispers in the dark..."
- Automatically played when drawn.
- Discard one card.
- Gain 2 Stress.

### Fungal Spores
"It drifts in the air, the rot spreading deeper with every breath."
- Automatically played when drawn.
- Gain 1 Stress.







## Rare (x33)

<!-- Fire -->

### Pillar of Light
"You will stand out amongst the rest, a shining beacon of hope."
- Deal 7 Fire damage to all enemies.
- Channel 2 Fire Mana.
- Set all enemy Intentions to 6.
- Gain 3 Stress.

Cost:
- 4 Fire Mana

### Fallen Star
"A fragment of the heavens descends, heralded by a piercing song of brilliance and ruin."
- Deal 12 Fire damage to one enemy.
- Scorch and Shatter the tile under the enemy Spell Pointer.
- Lose all Ward.
- Lose 8 Health.

Cost:
- 4 Fire Mana

### Eclipse
"The hungering darkness consumes all."
- Apply 1 Vulnerable to all enemies.
- Warp every Flooded tile.
- Channel 1 Fire Mana.
- Exhaust.

Cost:
- 3 Fire Mana
- 1 Generic Mana

### Daybreak
"The sun always rises."
- At the end of your next turn, deal 8 Fire damage to all enemies.
- You cannot gain Block until the end of your next turn.

Cost:
- 4 Fire Mana

### Holy Light
"A fleeting respite before the next storm."
- Heal 10 Health.
- Gain 4 Ward.
- Draw 2 Mana cards.
- Exhaust.

Cost:
- 2 Fire Mana
- 1 Ice Mana
- 1 Generic Mana

### Inferno
"Spare nothing in your fury."
- Deal 2 Fire damage to all enemies.
- Activate this card 3 times.

Cost:
- 4 Fire Mana
- 1 Generic Mana

<!-- Ice -->

### Impervious
"Your body freezes into unyielding armour, each shard of ice a testament to your defiance."
- Gain 1 Phantasmal.
- Gain 4 Ward.
- If you have been on Death's Door this combat, gain 2 additional Phantasmal.
- Exhaust

Cost:
- 4 Ice Mana

### Sanctuary
"Solace within the ice's embrace, free from chaos."
- Gain 16 Block.
- Remove all Hazards on the current tile.
- Exhaust.

Cost:
- 4 Ice Mana

### Healing Coil
"Spiralling pillars of frost surround your twisted form, mending torn flesh and shattered bones with each numbing caress."
- Heal 3 Health.
- Gain 2 Ward.
- Gain 8 Block.
- Remove an elemental Hazard from the current tile.

Cost:
- 2 Ice Mana
- 2 Generic Mana


### Leviathan
"The roar echoes first, heralding the coming storm."
- Shock and Flood every Scorched tile.
- Remove all Scorch Hazards.
- Deal 8 Ice damage to one enemy.

Cost:
- 3 Ice Mana
- 2 Lightning Mana

### Downfall
"The weight of the frost crushes all beneath it, merciless and unrelenting."
- Destroy the current tile for the rest of combat, and move Spell Pointer to any adjacent tile without Accumulating Mana.
- Enemy Spells now Misfire from misnavigation for the rest of combat.
- Take full damage from Misfires for the rest of combat.
- Exhaust.

Cost:
- 3 Ice Mana
- 2 Generic Mana

### Abyss
"It calls to you with promises of power."
- Warp every Scorched tile.
- Draw and immediately Channel 1 Mana.
- Gain 1 Stress.

Cost:
- 2 Ice Mana


<!-- Lightning -->

### Dragon Arc
"The storm dances between its prey, leaping from one to the next, never stopping, never tiring."
- Deal 3 Lightning damage to one enemy.
- Activate this card 3 times.

Cost:
- 4 Lightning Mana
- 1 Generic Mana

### Burst Salvo
"Each strike is precise, a calculated barrage that leaves no room for error."
- Apply 2 Vulnerable to one enemy.
- Shock the tile under the enemy Spell Pointer.
- Exhaust

Cost:
- 1 Lightning Mana
- 1 Ice Mana

### Zephyr
"Lightning courses through the air, swift and unpredictable as you channel its speed into your actions."
- Draw 3 Mana cards.
- Accumulate 3 Mana.

Cost:
- 2 Lightning Mana

### Voltaxic Burst
"The skies tear open, a gaping maw spewing out tongues of wicked lightning, hungrily preparing its next meal."
- Apply 1 Vulnerable to all enemies.
- Gain 1 Vulnerable.
- Channel 3 Lightning Mana.
- Gain 4 Stress.

Cost:
- 4 Lightning Mana
- 1 Generic Mana

### Transience
"You are but a conduit for the storm. Let it flow freely through your veins."
- Accumulate 2 Mana.
- Discard 2 Cards.
- Draw 4 Cards.

Cost:
- 3 Lightning Mana

### Inversion
"The blinding light splits like a forked tongue, flickering out with a vicious roar."
- If your next Skill is single-target, target all enemies instead.
- If your next Skill is multi-target, activate it 3 times on one enemy instead.
- Exhaust.

Cost:
- 3 Lightning Mana
- 1 Generic Mana

<!-- Earth -->

### Overpower
"Strength beyond measure crushes all who dare stand in its way."
- Channel 2 Earth Mana
- Ignore transition requirements this turn.
- Gain 2 Stress.

Cost:
- 3 Earth Mana
- 1 Generic Mana

### Pulverise
"Earth and stone shatter under your might, leaving your enemies broken and defenseless."
- Deal 6 Earth damage to one enemy.
- Apply 3 Vulnerable.
- Exhaust.

Cost:
- 4 Earth Mana

### Entrench
"The earth rises in your defense, a wall against the tides of chaos. It will hold, as long as you do."
- Gain 30 Block.
- Enemies take their Intention actions twice.
- Exhaust.

Cost:
- 3 Earth Mana

### Citadel
"A fortress rises beneath your feet, unyielding and eternal, protecting what must never fall."
- Gain 10 Block.
- Heal 4 Stress.
- Gain 1 Resistance.
- Exhaust.

Cost:
- 3 Earth Mana

### Obliterate
"With a single motion, you channel the power of the earth to annihilate all in its path."
- Shatter all tiles in a ray pointing the same direction as your last transition taken.
- Enemies caught in this line gain 1 Vulnerable.
- Exhaust.

Cost:
- 4 Earth Mana

### Sentinel
"An unshakable guardian stands beside you, shielding you from harm with unwavering vigilance."
- Lose all Ward.
- Gain 1 Phantasmal. Remove at the end of turn.
- Exhaust.

Cost:
- 2 Earth Mana
- 1 Generic Mana



<!-- Other -->

### Eternity
"Time halts at your command, freezing the battlefield in an eternal moment of stillness."
- View the top 5 Cards of your Combat deck.
- Enemies do not perform Intention actions this turn.
- Exhaust.

Cost:
- 3 Ice Mana
- 1 Generic Mana

### Terminus Est
"All paths converge."
- Deal 8 Void damage to the enemy with the lowest Health.
- Can only be used when multiple enemies are alive.

Cost:
- 4 Generic Mana

### Last Breath
"A fleeting moment of defiance before the end."
- Accumulate 4 Mana.
- Lose all Block.
- Lose all Ward.
- Exhaust.

Cost:
- None.

### Devour
"You take what the land offers, consuming it wholly."
- Destroy the current tile for the rest of combat, and move Spell Pointer to any adjacent tile without Accumulating Mana.
- Take full damage from Misfires for the rest of combat.
- Heal 12 Health.
- Exhaust.

Cost:
- 5 Generic Mana

### Clockwork
"Each gear turns in perfect harmony, a machine of endless precision and relentless purpose."
- Gain 1 Cast Speed for the rest of combat.
- Gain 1 Draw per turn for the rest of combat.
- Misfires cause 4 additional stress for the rest of combat.
- Exhaust.

Cost:
- 4 Generic Mana

### Apotheosis
"You ascend beyond mortal limits, the cost of power etched deeply into your very being."
- Gain 2 Draw per turn for the rest of combat.
- Gain 6 Stress.
- Exhaust.

Cost:
- 2 Generic Mana

### Fractal Strike
"Echoes of infinity."
- Draw 1 Skill card.
- Deal 1 Void damage to one enemy.

This card is shuffled into your draw pile rather than discard pile.

Cost:
- None

### Relentless
"No retreat."
- Accumulate 5 Mana.
- Gain 3 Vulnerable.
- Set all enemy Intentions to 6.
- Exhaust.

Cost:
- None

### Trifurcation
"In aeons past, three names bestowed, but only one deferred,
Abandoned, lost, deceived; at last, I am the fractured Third."
- Your next Spell targets all enemies.
- If there is only one enemy, activate your next Spell thrice.
- Exhaust.

Cost:
- 4 Generic Mana








## Uncommon (x33)

<!-- Fire -->
### Cleanse
"Burn away the impurities and rise anew."
- Remove an elemental Hazard from the current tile.
- Gain 4 Ward.
- Channel 2 Fire Mana.
- Discard 2 Cards.

Cost:
- 3 Fire Mana
- 1 Generic Mana

### Firestorm
"Only ashes will remain."
- Deal 4 Fire damage to all enemies.
- Channel 2 Fire Mana.

Cost:
- 4 Fire Mana

### Blaze
"The brightest flames cast the deepest shadows."
- Warp your current tile.
- Scorch a tile of your choice.

Cost:
- 3 Fire Mana

### Divine Ire
"Wrath tempered with righteousness is no less fierce."
- Deal 6 Fire damage to one enemy.
- If this Skill does not kill an enemy, lose 4 Health.

Cost:
- 3 Fire Mana

### Incinerate
"All it takes is the right moment."
- Scorch the current tile.
- Shuffle a Burn into Combat Deck.

Cost:
- 3 Fire Mana.

### Flame Nova
"In its wake, only embers remain."
- Scorch every tile adjacent to the current tile.
- Become immune to Scorch until the end of the turn.

Cost:
- 2 Fire Mana


<!-- Ice -->
### Consecrate
"Shadows flee from your presence."
- Heal 3 Health.
- Heal 2 Stress.
- Exhaust.

Cost:
- 3 Ice Mana

### Heal
"The body will endure if the spirit is unbroken."
- Heal 5 Health.
- Gain 2 Ward.
- Exhaust.

Cost:
- 2 Ice Mana
- 1 Generic Mana

### Unholy Mending
"Renewal is always within reach, if one is willing to bend a few rules."
- Heal 2 Health.
- Gain 10 Ward.
- Gain 4 Stress.

Cost:
- 2 Ice Mana
- 1 Generic Mana

### Desecrate
"Defile the sacred and unleash the unspeakable."
- Deal 4 Void damage.
- Reduce one enemy Intention to 1.
- Gain 2 Stress.

Cost:
- 3 Ice Mana

### Rejuvenate
"The cold winds carry more than icy ruin."
- Remove an elemental Hazard from the current tile.
- Heal 2 Stress.
- Discard 2 Cards.

Cost:
- 2 Ice Mana
- 1 Generic Mana

### Frost Nova
"A sudden pulse of biting cold washes forth, stopping even the most ferocious advances."
- Deal 6 Ice damage to all enemies.
- Reduce enemy Cast Speed to 0 this turn.

Cost:
- 3 Ice Mana


<!-- Lightning -->
### Discharge
"The energy of a thousand storms, released in a single blinding instant."
- Deal **D10** Lightning damage to one enemy.
- If this Skill deals 8 or more damage, draw 2 Mana Cards.

Cost:
- 3 Lightning Mana

### Finesse
"With a delicate touch and a sharp mind, even chaos can be guided into order."
- Accumulate 2 Mana.
- Draw 2 Cards.
- Discard 2 Cards.

Cost:
- 1 Generic Mana

### Conduit
"Breathe deeply, concentrate. A moment of calm before the storm."
- The next Skill costs **X+1** less Mana.

Cost:
- **X** Lightning Mana

### Volt Driver
"Harness the storm, drive it forward."
- Scorch one tile adjacent to the current tile.
- Deal 6 Lightning damage to one enemy.

Cost:
- 2 Lightning Mana
- 2 Generic Mana

### Tempest Ward
"A wall of light and thunder."
- Gain 10 Block.
- If attacked this turn, deal 4 Lightning damage to all enemies.

Cost:
- 2 Lightning Mana
- 1 Generic Mana

### Storm Call
"The storm answers, relentless and unyielding."
- Deal **D6** Lightning damage to all enemies.

Cost:
- 2 Lightning Mana
- 1 Generic Mana

<!-- Earth -->
### Aegis
"The earth shields all who stand firm upon it."
- Gain 2 Ward.
- Heal 2 Stress.
- Gain 12 Block.

Cost:
- 2 Earth Mana
- 1 Generic Mana


### Shockwave
"A tremor that rattles the heart and crushes the spirit."
- Deal 5 Earth damage to all enemies.
- Decrease one enemy Intention by up to 2.

Cost:
- 2 Earth Mana
- 1 Generic Mana

### Eviscerate
"Great spines of stone tear into your foes."
- Deal 8 Earth damage to one enemy.
- Channel 2 Earth Mana.

Cost:
- 3 Earth Mana
- 1 Generic Mana

### Unstoppable
"No force can halt a mountain in motion."
- Gain 2 Ward.
- Accumulate 1 Mana.
- Discard 1 Card.

Cost:
- 2 Earth Mana


### Aftershock
"Every blow leaves ripples in its wake."
- Shatter the tile under the enemy Spell Pointer.
- Deal **X** Earth damage to one enemy.

Cost:
- 1 Generic Mana
- **X** Earth Mana

### Earthquake
"The earth crumbles beneath you."
- Shock the current tile.
- Flood the current tile.



<!-- Colourless -->
### Riposte
"Timing is everything."
- Gain 1 Phantasmal. Remove at the end of turn.

Cost:
- 4 Generic Mana

### Parry
"A hair's breadth can mean the difference between triumph and defeat."
- Gain 10 Block.
- Discard 1 Card.
- If you do not lose any Health this turn, heal 4 Stress.

Cost:
- 2 Generic Mana

### Sidestep
"Wait, then strike."
- Increase or decrease one enemy Intention by up to 2.

Cost:
- 1 Generic Mana

### Misdirection
"A well-placed stumble can be just as effective as a blade."
- Swap two enemy Intentions.

Cost:
- 1 Generic Mana

### Astral Rift
"Space bends to your will."
- Gain an Epsilon transition.
- Draw 2 Cards.

Cost:
- 2 Generic Mana

### Bifurcating Strike
"Divide and conquer."
- Your next single-target Skill targets two enemies.

Cost:
- 2 Generic Mana

### Arcane Battery
"Overflowing with latent energy."
- Draw 3 Mana cards.

Cost:
- 2 Lightning Mana

### Surge
"The tides of power rise swiftly and without warning."
- Accumulate 2 Mana.
- Draw 2 Mana cards.

Cost:
- 2 Generic Mana

### Berserk
"Abandon restraint and unleash chaos."
- Accumulate 2 Mana.
- Lose 2 Health.
- Gain 2 Stress.

Cost:
- None







## Common (x30)

<!-- Fire -->
### Magic Missile
"The first spell a young mage learns."
- Deal 3 Fire damage to one enemy.
- If cast using only Fire mana, deal 3 Fire damage to all enemies.

Cost:
- 2 Generic Mana

### Combust
"Nothing sparks fear like fire."
- Deal 3 Fire damage to one enemy.
- Scorch your current tile.

Cost:
- 1 Fire Mana

### Ignite
"A wildfire is started by a single spark."
- Scorch the tile under the enemy Spell Pointer.
- Discard 1 card.

Cost:
- 1 Fire Mana

### Fireball
"An iconic show of explosive force."
- Deal 4 Fire damage to one enemy.
- If your Spell Pointer is adjacent to the enemy Spell Pointer, deal 4 Fire damage to all enemies.

Cost:
- 3 Fire Mana

### Eruption
"Molten energy bursts forth."
- Shatter the tile under the enemy Spell Pointer.

Cost:
- 1 Earth Mana
- 1 Fire Mana
- 1 Generic Mana

### Flare
"A blinding light in the darkness."
- Draw 1 Mana card.
- Draw 1 Skill card.
- Channel 1 Lightning Mana.

Cost:
- 1 Fire Mana
- 1 Lightning Mana
- 1 Generic Mana



<!-- Ice  -->
### Restore
"Cool, soothing energy flows through you."
- Heal 3 Health.
- Discard 1 Card.

Cost:
- 2 Ice Mana

### Blessing
"Divine strength flows through your veins."
- Heal 2 Health.
- Heal 3 Stress.

Cost:
- 1 Ice Mana

### Repair
"The body will endure."
- Heal 2 Health.
- Heal 2 Stress.
- Remove an elemental Hazard from the current tile.

Cost:
- 1 Earth Mana
- 1 Ice Mana

### Icicle Burst
"A vicious volley, sharp and precise."
- Deal 2 Ice damage to all enemies.

Cost:
- 1 Ice Mana

### Aqua Bolt
"Rippling power surges forth."
- Deal 2 Ice damage to one enemy.
- Decrease one enemy Intention by up to 2.
- Heal 2 Stress.

Cost:
- 1 Ice Mana

### Circle of Power
"Power sealed in ice, waiting to be released."
- Draw 2 Mana cards.
- Discard 1 Card.
- Flood your current tile.

Cost:
- 2 Ice Mana


<!-- Lightning  -->
### Blink
"Gone in an instant, leaving nothing but a faint crackle of electricity in your wake."
- Gain an Epsilon transition.
- Channel 1 Lightning Mana.

Cost:
- 2 Lightning Mana
- 1 Generic Mana

### Arc
"A shocking chain of electricity."
- Deal 3 Lightning damage to one enemy.
- For each Lightning Mana used to activate this Skill, hit one additional enemy.
- If only Lightning Mana is used, Shock the tile under the enemy Spell Pointer.

Cost:
- 3 Generic Mana

### Ion Bolt
"An energized projectile crackles with lethal intent."
- Deal 2 Fire damage to one enemy.
- Deal 2 Lightning damage to all enemies.

Cost:
- 1 Lightning Mana
- 1 Fire Mana
- 1 Generic Mana

### Attune
"Harmony with the storm."
- Draw 2 Mana cards.

Cost:
- None

### Ball Lightning
"A sphere of raw electricity dances in the air, a transient containment of power."
- Shock a tile of your choice.
- Channel 1 Lightning mana.

Cost:
- 2 Lightning Mana

### Unleash
"Power without restraint."
- Deal **3\*X** Lightning damage to one enemy.
- If the enemy is on a Flooded tile, ignore Resistances.

Cost:
- 1 Generic Mana
- **X** Lightning Mana

<!-- Earth -->
### Tenacity
"Perseverance will see you through."
- Gain 6 Block.

Cost:
- 1 Earth Mana

### Bulwark
"An impenetrable defense."
- Gain 5 Ward.
- Heal 2 Stress.
- Channel 1 Earth Mana.

Cost:
- 3 Earth Mana

### Deflect
"Redirect the force."
- Decrease one enemy Intention by up to 2.
- Gain 12 Block.
- Deal 2 Earth damage to all enemies.

Cost:
- 2 Earth Mana
- 1 Generic Mana

### Fracture
"Crack the foundation."
- Shatter a tile adjacent to your Spell Pointer.

Cost:
- 2 Earth Mana
- 1 Generic Mana

### Concentration
"The key to success lies in focus."
- Deal 6 Earth damage to one enemy.
- Accumulate 1 Mana.

Cost:
- 1 Earth Mana

### Constriction
"Strength suffocates as it protects."
- All enemies gain 1 Resistance.
- Reduce enemy Cast Speed to 0 this turn.

Cost:
- 2 Earth Mana



<!-- Other -->
### Prescience
"A fleeting glimpse into the future."
- View the top 2 cards of your Combat deck.

- 1 Generic Mana

### Redirection
"Momentum is its own kind of magic."
- Reroll one enemy Intention.
- Heal 2 Stress.

Cost:
- 1 Generic Mana

### Inertia
"There is no force without motion."
- The Spell Pointer continues in the same direction for one more tile, regardless of available transitions.

Cost:
- None.

### Rift
"Tear through reality itself."
- Channel 1 Void Mana.

Cost:
- 2 Generic Mana

### Anticipate
"Know your enemy, and you've already won half the battle."
- Increase or decrease one enemy Intention by up to 2.
- Heal 2 Stress.

Cost:
- 1 Generic Mana

### Enrage
"Fury fuels your actions."
- Accumulate 2 Mana.

Cost:
- 1 Generic Mana






## Starting Cards (x15)

### Flame (x1)
- Deal 4 Fire damage to one enemy.

Cost:
- 1 Fire Mana.
- 1 Generic Mana.

### Spark (x1)
- Deal 4 Lightning damage to one enemy.

Cost:
- 1 Lightning Mana.
- 1 Generic Mana.

### Defend (x4)
- Gain 5 Block.

Cost:
- 1 Earth Mana.

### Mend (x2)
- Heal 2 Health.
- Heal 1 Stress.

Cost:
- 1 Ice Mana

### Prepare (x2)
- Draw 2 cards.
- Discard 1 Card.

Cost:
- 1 Generic Mana

### Focus (x2)
- Accumulate 1 Mana.
- Heal 2 Stress.

Cost:
- 1 Generic Mana

### Delta (x2)
- Move Spell Pointer to an adjacent tile without Accumulating Mana.

Cost:
- None

### Epsilon (x1)
- Move Spell Pointer to any tile without Accumulating Mana.
- Exhaust.

Cost:
- 2 Generic Mana





# Consumables

## Ration Pack
Restore 2 Health.
Cannot be used during combat.

## Key
Unlocks various treasures in the dungeons.

## Bandages
Restore 8 Health.

## Healing Salve
Exhaust all Bleed, Burn, and Sapped status cards from hand.

## Blessed Water
Exhaust all Hex status cards from hand.

## Laudanum
Heal 2 Stress.
Lose 4 Health.














# Events

## Common (23)

### Abandoned Library
Dusty tomes and scattered scrolls line the decrepit shelves. What secrets might they hold?

1. Read a tome.
   - Gain 1 Stress.
   - Draft one of three cards.
   - Purge one Skill card.
2. Peruse the shelves. (Consumes Laudanum)
   - Draft two of five cards.
   - Purge two Skill cards.
3. Leave the ancient books undisturbed.
   - Nothing happens.


### Hunger (x4)
You grow hungry from your efforts. Perhaps you have time for a break?

1. We must save our supplies.
   - Gain 2 Stress.
   - Lose 4 Health.
2. Only eat what is necessary. (Consumes 1 Ration Pack)
   - Nothing happens.
3. We have plenty. (Consumes 2 Rations)
   - Heal 2 Stress.
   - Heal 10% Health.
4. We are desperate. 
   - Discard one Relic.
   - Heal 50% Health.
   - Gain 4 Stress.


### Locked Chest
"An intricately locked chest rests before you.

1. Smash the chest open.
   - Gain Small Reward.
2. Smash the lock.
   - Lose 6 Health.
   - Gain a Potion.
   - Gain Large Reward
3. Use a key. (Consumes Key)
   - Obtain a Relic.
   - Draft one of three cards.


### Infested Supplies
Our rations are crawling with parasites, but there’s still some use in them.

1. Save what we can. (Requires less than 8 Stress.)
   - Lose 6 Health.
   - Shuffle back into Event deck.
2. Purge the infection. (Requires less than 4 Stress)
   - Lose 2 Rations.
3. Consume the infested goods.
   - Heal 10 Health.
   - Lose 4 Maximum Health.
   - Gain 2 Stress.


### Blighted Supplies
Our rations are green with rot, releasing clouds of toxic spores with every movement.

1. Save what we can. (Requires less than 8 Stress.)
   - Lose 6 Health.
   - Shuffle back into Event deck.
2. Purge the Blight. (Requires less than 4 Stress)
   - Lose 2 Rations.
3. Consume the blighted goods.
   - Heal 8 Health.
   - Lose 4 Maximum Health.
   - Gain two Curses.


### Rotting Corpses
A grim sight of decay lies before you, their belongings still intact.

1. Burn the bodies.
   - Take 2 Damage.
   - Heal 2 Stress.
2. Pilfer the corpses.
   - Gain Small Reward.
   - Gain two Curses.
3. Ignore the scene.
   - Gain 1 Stress.


### Uncovered Grave
A shallow grave reveals buried treasures... or perhaps curses.

1. Disturb the grave.
   - 50% chance to obtain a Relic. Otherwise, gain a Curse.
2. Purify the grave. (Consumes Blessed Water)
   - Obtain a Relic.
   - Gain Large Reward.
3. Cover the grave.
   - Heal 2 Stress.
   - Remove one Curse.


### Unmarked Grave
A forgotten grave lies exposed by the elements.

1. Dig up the grave:
   - Obtain a Relic.
   - Gain a Curse.
2. Purify the grave. (Consumes Blessed Water)
   - Obtain a Relic.
   - Heal 4 Stress.
3. Cover the grave.
   - Heal 2 Stress.
   - Remove one Curse.


### Blighted Ruins
The air here is thick with rot and decay, thick clouds of spores bursting from the ground with every step.

1. Explore the ruins.
   - Lose 5 Health.
   - 50% chance to obtain a relic.
   - Draft one of three cards.
2. Cleanse the blight. (Consumes Laudanum)
   - Lose 2 Health.
   - Heal 4 Stress.
3. Leave immediately.
   - Nothing happens.


### Mana Storm
The air crackles with unstable energy, charging your very being.

1. Lay low and find shelter.
   - Lose 2 Health.
   - Choose a mana type to be disabled for the next combat.
3. Absorb the energy.
   - Lose D10 Health.
   - Remove a Curse.


### Tainted Well
A cracked stone well trickles with foul, dark water.

1. Drink anyway.
   - Heal 10 Health.
   - Gain two Curses.
2. Purify the well. (Consumes Blessed Water)
   - Heal 10 Health.
   - Heal 4 Stress.
   - Remove one Curse.
3. Draw a vial.
   - Obtain a Potion.
   - Heal 1 Stress.


### Infested Supplies
A stash of supplies teems with small, skittering creatures.

1. Scavenge what you can.
   - Gain 2 Rations.
   - Gain 4 Stress.
   - Gain 1 Curse.
2. Partake in the rotting goods.
   - Heal 4 Health
3. Burn the infested goods. (Consumes)
   - Nothing happens.


### Branching Pathways
The road ahead splits into two equally uncertain directions.

1. Take the path less-travelled.
   - Gain Small Reward.
2. Follow the light.
   - Heal 2 Stress.


### The Corruption
A ominous red mist surrounds you, smothering the light.

1. Stay close to the light.
   - Gain Small Reward.
2. Cautiously venture into the unknown.
   - Gain 2 Stress.
   - Gain Large Reward.
3. Embrace the darkness.
   - Gain 6 Stress.
   - Obtain a Relic.


### Hidden Trapdoor
A faint draft emanates from a concealed opening in the ground.

1. Descend into the trapdoor.
   - Obtain a Relic.
   - Gain 2 Stress.
   - 50% chance of gaining a Curse.
2. Leave it untouched.
   - Gain Small Reward.


### Secret Cache
A hidden stash glints in the shadows.

Roll a **D4** and gain:
1. Gain Small Reward.
2. Gain Large Reward.
3. Draft one of three cards.
4. Obtain a Relic.


### The Bone Garden
A macabre yet strangely serene field of bones stretches out before you. The remains seem to grow like plants, each piece perfectly interwoven with another, as though cultivated by unseen hands.

1. Harvest the bones.
   - Gain 2 Stress.
   - Gain Large Reward.
2. Admire the garden.
   - Purge one Skill card.
   - Draft one of three cards.
3. Leave the garden undisturbed.
   - Heal 1 Stress.


### The Ossuary
The walls are lined with rows of meticulously arranged skulls, hollow eyes watching your every move. A faint whisper emanates from the depths of the chamber.

1. Search for valuables.
   - Lose 2 Health.
   - Gain Small Reward.
2. Study the carvings in the walls.
   - Gain 2 Stress.
   - Purge two Skill cards.
3. Turn back.
   - Nothing happens.


### Forgotten Graveyard
Tombstones dot the landscape, some crumbling and forgotten, others freshly disturbed. A sense of unease permeates the air.
1. Dig up the grave with the largest headstone.
   - 50% chance of gaining a Large Reward. Otherwise gain Small Reward.
   - Gain a Curse.
2. Read the epitaphs.
   - Gain 1 Stress.
   - Draft one of three cards.
3. Pay your respects. (Consumes 3 Gold)
   - Heal 2 Stress.


### Mass Grave
A pit filled with sickly blighted remains, hastily covered with a thin layer of soil, decidedly insufficient to contain the smell. Merely standing here fills you with unease, and the stench of decay lingers in the air.

1. Scavenge through the remains.
   - Lose 8 Health.
   - Obtain a Relic.
   - Gain two Curses.
2. Offer a token of respect. (Consumes Blessed Water)
   - Purge one Skill card.
3. Leave quickly.
   - Nothing happens.


### Abandoned Shop
Shelves hang askew, and the counters are littered with broken trinkets. Faint echoes of footsteps suggest you’re not alone.

1. Search for usable goods.
   - Gain 2 Stress.
   - Gain Small Reward.
2. Prioritise more valuable wares.
   - Gain 4 Stress.
   - Draft one of three cards.
3. Leave quickly.
   - Nothing happens.


### Blighted Farmstead
The fields are barren, the soil choked with rot. The farmhouse door hangs open, swaying in the breeze.

1. Search the farmhouse.
   - Gain 1 Stress.
   - Gain Small Reward.
2. Harvest what little remains.
   - Gain 3 Stress.
   - Gain 2 Rations.
   - Gain a Potion.
3. Burn the fields.
   - Lose 4 Health.
   - Remove one Curse.


### Towering Gates
An immense iron gate bars your path, its rusted surface adorned with ominous carvings.

1. Unlock the gate. (Consumes Key)
   - Heal 2 Stress.
2. Break through.
   - Lose 4 Health.
   - Purge one Skill card.
3. Turn back.
   - Gain 2 Stress.





## Uncommon (16)

### Ancient Vault
An ancient mechanism guards a long-forgotten treasure.

1. Force it open.
   - Lose 10 Health.
   - Obtain a Relic.
2. Open your mind and decipher the arcane mechanism. (Consumes Laudanum)
   - Gain 2 Stress.
   - Obtain a relic.
3. Leave empty-handed.
   - Nothing happens.


### Arcane Surge
A massive wave of elemental mana surges through the dungeon, crushing all in its path.

1. Succumb to the arcane energies.
   - Lose 2 Health.
   - Choose a mana type to be disabled for the next combat.
2. Stand firm against the rising tide.
   - 50% chance of losing 4 Health.
   - Gain a Potion.
3. Absorb the energy.
   - 75% chance of losing 6 Health.
   - Draft one of five cards.


### Fallen Hero
A silent grave lies before you.

1. Offer a prayer.
   - Draft one of three cards.
2. Disturb the grave.
   - Draft two of five cards.
   - Activate an Elite enemy encounter.


### Torn Contract
An ancient parchment, faded and torn, lies before you. It radiates dark power but speaks of broken oaths.

1. Sign the remnants.
   - Obtain a Relic.
   - Heal 4 Stress.
   - Gain a Curse.
2. Burn the contract. (Requires less than 10 Stress)
   - Heal 2 Stress.
   - Remove a Curse.
3. Ignore it.
   - Heal 2 Stress.


### Sacrificial Harvest
A glowing, rune-inscribed circle sits in the middle of the room, surrounded by withered vegetation.

1. Offer your blood.
   - Lose 4 Health.
   - Draft two of five cards.
2. Offer your mana.
   - Draw two fewer Mana cards at the beginning of the next combat.
   - Gain Large Reward.
3. Ignore the ritual.
   - Gain 2 Stress.


### Twisted Arena
A cursed battleground manifests, and the spirits of long-dead warriors demand entertainment.

1. Face the Spirits.
   - Draft one of three cards.
   - Obtain two Relics.
   - Gain Large Reward.
   - Fight two Elites at once.
2. Defy the challenge.
   - Gain 6 Stress.
   - Gain Large Reward.
3. Escape the arena. (Consumes Laudanum)
   - Gain 1 Stress.
   - Gain Small Reward.


### Ritual
Dark figures chant in an arcane circle, their spell nearing completion.

1. Interrupt the ritual.
   - Gain Large Reward.
   - Fight an Elite.
2. Silently observe.
   - Gain 2 Stress.
   - Draft one of three cards.


### Crimson Rot
The walls bleed with an unnatural red ichor. Bloody insects flitter about, filling the narrow corridor with the stench of iron.

1. Taste the ichor.
   - Lose 8 Health.
   - Draft three of five cards.
2. Avoid the insects.
   - Gain 2 Stress


### Ancient Ruins
The crumbling remnants of an ancient civilization tower before you. Though its inhabitants are long gone, you can feel the faintest whisper of magic still flow through the ruins.

1. Search the ruins.
   - Gain 1 Stress.
   - Gain Small Reward.
2. Explore cautiously. (Requires less than 6 Stress)
   - Obtain a Potion.
   - Gain Large Reward.
3. Leave immediately.
   - Nothing happens.


### Promises of Treasure
A glittering pile of treasure lies ahead, guarded by sinister traps.

1. Risk it all.
   - 50% chance of losing 12 Health.
   - Gain 2 Large Rewards.
2. Proceed carefully.
   - Lose 4 Health.
   - Gain 1 Large Reward.
3. Study the traps.
   - Purge two Skill cards.
   - Draft one of three cards.


### Lost Soul
A lost spirit drifts aimlessly, pleading for guidance.

1. Offer comfort.
   - Remove one Curse.
3. Offer knowledge.
   - Lose 4 Health.
   - Purge two Skill cards.
3. Offer blood.
   - Lose 12 Health
   - Gain two Curses.
   - Obtain two Relics.


### Rogue Scholar
The wandering spirit of an mage mutters incoherently, tiny ripples of magic wrapping around you with every word.

1. Decipher their spell.
   - Gain 2 Stress.
   - Draft two of five cards.
2. Memorise their words.
   - Lose 2 Health.
   - Purge a Skill card.
3. Ignore the voice.
   - Nothing happens.


### Runic Vault
An imposing stone vault sealed with glowing runes stands before you.

1. Break the seal.
   - 50% chance of obtaining a Relic. Otherwise fight an Elite.
2. Study the runes.
   - Gain 1 Stress.
   - Draft one of three cards.
3. Leave the vault.
   - Nothing happens.


### Entropic Brew
A cauldron of swirling, chaotic energy bubbles ominously.

1. Drink deeply.
   - Gain 6 Stress.
   - Draft three of five cards.
2. Distill a vial.
   - Gain a Potion.
3. Pour it out. (Requires less than 8 Stress)
   - Heal 10 Health.


### Supply Cache
A forgotten stash of supplies lies hidden behind rubble.

1. Loot it quickly.
   - Lose 2 Health
   - Gain 1 Stress.
   - Gain Large Reward.
2. Inspect the cache carefully.
   - Gain Small Reward.
3. Ignore the cache.
   - Nothing happens.


### Shattered Relic
A pile of broken treasures lies before you, their magic faint but undeniable. Fragments of runes flicker, whispering to be repaired or reclaimed.

1. Piece them back together.
   - Gain 8 Stress damage.
   - Lose 8 Health.
   - Obtain two Relics.
2. Extract their essence.
   - Gain 4 Stress.
   - Gain a Potion.
   - Draft one of three cards.
1. Don't risk it.
   - Nothing happens.













## Rare (15)

### Infested Altar
A writhing mass of parasitic growths surrounds an ominous stone pillar, bound in place by ancient magic. Whispers tear at the edges of your mind, insistently demanding that you approach. Before you can resist, you inexplicably find yourself standing by the pillar, a bloated bloody parasite wriggling in your hand.

1. Consume the parasite.
   - Heal 10 Health.
   - Lose 5 Maximum Health.
   - Gain 4 Stress.
   - Gain two Curses.
2. Resist. (Requires less than 4 Stress)
   - Gain 2 Stress.
3. Burn the mass. (Requires 0 Stress)
   - Remove one Curse.


### Cursed Shrine
A decaying corpse lies at the foot of the shrine, its ribs torn asunder. The ancient tome upon the altar beckons you forth, promising both power and peril.

1. Forbidden knowledge.
   - Gain a Curse.
   - Draft two of five cards.
2. Spill your blood upon the tome.
   - Lose 10 Health.
   - Draft three of five cards.
   - Purge two Skill cards.
3. Resist temptation. (Consumes Laudanum)
   - Gain 6 Stress.


### Profane Altar
A sinister aura surrounds a shrine of rotting flesh and bones, a rusty dagger protruding from the bloody stone. Severed hands wriggle their fingers upon the altar, pointing at you accusingly.

1. Offer your blood.
   - Lose 2 Health.
   - Gain 4 Maximum Health.
   - Gain 2 Stress.
   - Gain a Curse.
2. Impale the hands with the dagger. (Requires less than 10 Stress)
   - Obtain a Relic.
   - Gain a Curse.
3. Resist its pull. (Requires less than 4 Stress)
   - Gain 2 Stress.


### Maw of the Abyss
Disfigured corpses are piled around a stone altar, each body torn apart, their bones arranged in unidentifiable yet deliberate patterns. In the centre lies an unidentifiable bloody mass of writhing flesh. An insatiable hunger suddenly gnaws at your insides, compelling you to approach.

1. Partake.
   - Heal 12 Health.
   - Lose 6 Maximum Health.
   - Gain 2 Stress.
   - Gain two Curses.
2. Resist temptation. (Requires less than 8 Stress)
   - Gain 1 Stress.
3. Distract yourself with other sustenance. (Consumes 2 Rations)
   - Heal 4 Health.


### The Weeping Idol
A grotesque idol carved from obsidian weeps a thick, red fluid that smells faintly of iron. Its presence is oppressive, its sorrow infesting the atmosphere.

1. Drink the tears.
   - Heal 15 Health.
   - Gain 4 Maximum Health.
   - Gain a Curse.
2. Shatter the idol.
   - Lose 10 Health.
   - Gain Small Reward.
3. Pray to the idol. (Requires less than 4 Stress)
   - Gain Large Reward.


### Whispers beneath the Floor
The ground beneath your feet shudders. Faint whispers urge you to listen, to kneel, to dig. The earth feels alive, and something ancient stirs below.

1. Dig deeper.
   - Obtain a Relic.
   - Gain a Curse.
2. Ignore the voices.
   - Gain 1 Stress.
3. Bury it further. (Requires less than 8 Stress)
   - Lose 2 Health.
   - Remove a Curse.


### The Hungry Wound
A small scratch from the previous battle throbs unnaturally, growing and writhing as though alive. The flesh around it splits, revealing a glimmer of something otherworldly.

1. Feed the wound.
   - Heal 10 Health.
   - Lose 4 Maximum Health.
   - Gain 4 Stress.
2. Burn it closed.
   - Lose 10 Health.
   - Remove 2 Curses.
   - Purge a Skill card.


### The Burrowing Hunger
A black, serpentine shape writhes under your skin, gnawing hungrily at your insides. Its voice whispers promises of strength if you let it take root.

1. Embrace the hunger.
   - Lose 5 Maximum health.
   - Obtain a Relic.
2. Resist the urge. (Requires less than 8 Stress)
   - Heal 10 Health.
   - Take 2
3. Tear out the creature. (Requires less than 4 Stress or Laudanum)
   - Lose 10 Health.
   - Remove two Curses.


### Puppet Strings
Thin, silken threads erupt from your fingertips, attaching themselves to everything around you. The strings tug and jerk, pulling you forward.

1. Allow yourself to be controlled.
   - Lose 5 Health.
   - Obtain a Relic.
   - Gain a Curse.
3. Resist the pull.
   - Gain 4 Stress.
   - Heal 5 Health.
2. Cut the strings. (Consumes Laudanum)
   - Heal 2 Stress.
   - Remove one Curse.


### Untainted Fountain
In a desolate chamber, a crystalline fountain glimmers with pristine water. Its purity seems untouched by the corruption surrounding it, and its allure is irresistible. Yet something is amiss.

3. Cleanse yourself.
   - Heal 25 Health.
   - Gain one Curse.
1. Drink deeply.
   - Heal 8 Stress.
2. Throw a coin in the water.
   - Remove a Curse.


### Enshrined Tome
An ancient book lies atop a pedestal, its pages glowing faintly with forbidden runes. As you approach, the air grows heavy, and a voice murmurs incomprehensible secrets.
1. Open the tome.
   - Gain one Curse.
   - Gain 4 Stress.
   - Draft one of three **Rare** cards.
2. Seal the tome. (Requires less than 8 Stress)
   - Purge one Skill card.
   - Heal 10 Health.
   - Heal 2 Stress.
3. Leave it untouched.
   - Nothing happens.


### Whispers from Beyond
A faint, chilling voice beckons from the shadows. The whispers twist and pull at your thoughts, offering insights no mortal should possess.
1. Listen closely.
   - Lose 4 Maximum Health.
   - Gain 4 Stress.
   - Gain one Curse.
   - Draft one of three **Rare** cards.
2. Resist the whispers.
   - Gain 2 Stress.
   - Draft one of three cards.
3. Run away.
   - Take 2 Stress damage.


### An Eldritch Offer
A shadowy figure approaches, offering wares both wondrous and cursed.

1. Blood for Power.
   - Lose 20 Health.
   - Draft one of five cards.
   - Draft one of three **Rare** cards.
3. Blood for Wealth.
   - Lose **X** Health.
   - Gain **X/5** Large Reward.
2. Charity.
   - Heal 8 Health.
   - Gain 4 Stress.


### Temporal Nexus
A swirling vortex of light and shadow crackles in the air, tugging at the fabric of time itself. Standing before it, you feel the flow of mana accelerate unnaturally.

1. Step into the nexus.
   - Draw two additional cards at the beginning of the next combat.
   - Gain Large Reward.
   - Lose 10 Maximum Health.
2. Attempt to stabilize it.
   - Gain 4 Stress.
   - Draft two of five cards.
3. Turn back.
   - Nothing happens.


### Divine Blessing
A glowing statue of an ancient deity radiates warmth and light. Its gaze fills you with both hope and dread.

1. Bow in reverence.
   - Heal 20 Health.
   - Purge one Skill card.
2. Blasphemy.
   - Take 6 Stress damage.
   - Draft one of three **Rare** cards.
3. Avert your gaze.
   - Heal 1 Stress.






# Encounters



## Common Encounters


### Skeleton Trio

Channels 6 Mana.

#### Skeleton Mage (Fire)
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 10     |             | Ice             |

Actions:
- 1-2: Deal 2 Fire damage.
- 3-5: Gain 4 Block.
- 6: Scorch one tile.

#### Skeleton Mage (Lightning)
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 10     |             | Earth           |

Actions:
- 1-2: Deal 2 Lightning damage.
- 3-5: Gain 4 Block.
- 6: Shock one tile.

#### Skeleton Mage (Ice)
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 10     |             | Fire            |

Actions:
- 1-2: Deal 2 Ice damage.
- 3-5: Gain 4 Block.
- 6: Flood one tile.

#### Encounter Modifiers

Whenever the enemy successfully resolves a Spell, apply a Hazard matching the Damage type of the spell to a random tile.

Decay:
- 8 turns

Decay Effect:
- None






### Skeleton Army

Channels 4 Mana.

#### Skeleton Guard
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 15     |             | Lightning       |

Actions:
- 1-2: Deal 2 Earth damage.
- 3-4: Gain 6 Block.
- 5-6: All enemies gain 4 Block.

#### Skeleton Knight
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 15     |             | Lightning       |

Actions:
- 1-2: Deal 4 Fire damage.
- 4-6: Gain 4 Block.

#### Skeleton Archer
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 12     |             | Earth           |

Actions:
- 1-4: Deal 2 Lightning damage.
- 5-6: Gain 6 Block.

#### Encounter Modifiers

Decay:
- 8 turns

Decay Effect:
- None








### Pack of Slimes

Channels 4 Mana.

#### Slime
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 10     |             | Fire            |

Actions:
- 1-4: Deal 1 Ice damage.
- 5-6: Gain 4 Block.

#### Slime
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 10     |             | Fire            |

Actions:
- 1-5: Deal 1 Ice damage.
- 5-6: Gain 4 Block.

#### Large Slime
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 15     |             | Fire            |

Actions:
- 1-4: Deal 2 Ice damage.
- 5-6: Shuffle 1 Poison into Combat deck.

#### Encounter Modifiers

Whenever the enemy successfully resolves a Spell, Flood a random tile.

When killing any slime, heal all remaining slimes 5 Health.









### Forest Clearing

Channels 4 Mana.

#### Slime
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 10     |             | Fire            |

Actions:
- 1-4: Deal 1 Ice damage.
- 5-6: Gain 4 Block.

#### Slime
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 10     |             | Fire            |

Actions:
- 1-5: Deal 1 Ice damage.
- 5-6: Gain 4 Block.

#### Dryad
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 20     | Ice         | Fire            |

Loses Ice Resistance if your Spell contains two consective Fire Mana.

Actions:
- 1-2: Deal 3 Earth damage.
- 3-5: Gain 6 Block.
- 6: Apply 1 Vulnerable.

#### Encounter Modifiers

Whenever the enemy successfully resolves a Spell, Flood a random tile.

When killing any slime, heal all remaining slimes 5 Health.


Decay:
- 8 turns

Decay Effect:
- None








### Ominous Shrine

Channels 6 Mana.

#### Hooded Figure
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 20     |             | All             |

Actions:
- 1-4: Gain 4 Block.
- 5-6: All enemies gain 4 Block.

#### Dark Cultist
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 20     |             | All             |

Actions:
- 1-4: Deal 1 Void damage.
- 5-6: Gain 6 Block.

#### Corrupted Seer
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 30     |             | All             |

- 1-2: Deal 1 Void damage.
- 3-4: Gain 6 Block.
- 5-6: Shuffle 1 Hex into Combat deck.

#### Encounter Modifiers

Warp one Rune tile at beginning of combat.

Upon casting a spell of Damage Type **X**, all enemies Resist **X** until next Spell is resolved.

Decay:
- 10 turns

Decay Effect:
- None





### Overgrown Graveyard

Channels 6 Mana.

#### Wraith
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 4      | All         |                 |

Permanent Phantasmal.

Actions:
- Deal 1 Ice damage.

#### Plague Ghoul
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 20     |             | Fire            |

Actions:
- 1-4: Deal 1 Ice damage.
- 5-6: Shuffle 1 Poison into Combat deck.

#### Dire Wolf
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 10     |             | Lightning       |

Actions:
- 1-4: Deal 1 Void damage.
- 5-6: Gain 6 Block.


#### Encounter Modifiers

Warp one Rune tile at beginning of combat.

Decay:
- 10 turns

Decay Effect:
- None








### Bandit Raid

Channels 5 Mana.

#### Bandit Marauder
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 20     | Earth       | Lightning       |

Actions:
- 1-5: Deal 2 Earth damage.
- 6: Shuffle 1 Bleed into Combat deck.


#### Bandit Mage
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 12     |             | Ice             |

Actions (Cycling):
- All enemies heal 4 Health.
- All enemies gain 8 Block.

#### Encounter Modifiers

None.

Decay:
- 10 turns

Decay Effect:
- None






### Necromantic Cult

Channels 5 Mana.

#### Skeleton Gladiator
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 12     |             | Earth           |

Actions:
- 1-5: Deal 2 Earth damage.
- 6: Shuffle 1 Bleed into Combat deck.


#### Skeleton Duelist
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 12     |             | Earth           |

Actions:
- 1-5: Deal 2 Earth damage.
- 6: Shuffle 1 Poison into Combat deck.


#### Necromancer
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 20     |             | Ice             |

Actions:
- 1-4: All enemies gain 4 Block.
- 5: All enemies heal 4 Health.
- 6: Shuffle 1 Sapped into Combat deck.

#### Encounter Modifiers

Skeletons gain 1 Vulnerable when necromancer dies.

Decay:
- 8 turns

Decay Effect:
- None






### Ancient Arena

Channels 5 Mana.

#### Skeleton Knight
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 15     | Earth       | Lightning       |

Actions:
- 1-2: Deal 4 Fire damage.
- 4-6: Gain 4 Block.

#### Shadow Duelist
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 10     |             | Ice             |

Actions:
- 1-2: Deal 2 Earth damage.
- 4-6: Gain 4 Block.

#### Lich
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 10     |             | Fire            |

Actions:
- 1-4: Gain 4 Block.
- 5: Shuffle 1 Burn into Combat deck.
- 6: Shuffle 1 Sapped into Combat deck.

#### Encounter Modifiers

None.

Decay:
- 8 turns

Decay Effect:
- None
















## Elite Enemies




### Infested Altar

Channels 5 Mana.

#### Infested Wolf
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 12     |             | Fire            |

Actions:
- 1-2: Deal 4 Earth damage.
- 3-5: Gain 4 Block.
- 6: Shuffle 1 Poison into Combat deck.

#### Infested Bandit
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 18     |             | Lightning       |

Actions:
- 1-3: Deal 4 Earth damage.
- 4-6: Gain 4 Block.

#### Fungal Symbiote
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 40     |             | Fire            |

Actions:
- 1-4: Shuffle 1 Poison into Combat deck.
- 5: Shuffle 1 Sapped into Combat deck.
- 6: Gain 1 Resistance.


#### Encounter Modifiers

[Infest](#infested) two tiles at the beginning of combat.
Lose 2 Health whenever the enemy Spell Pointer lands on an Infested tile.
Gain 1 Vulnerable whenever an enemy Spell successfully resolves.

Decay:
- 12 turns

Decay Effect:
- None.









### Echoing Catacombs

Channels 5 Mana.

#### Shattered Bone Construct
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 30     |             | Lightning       |

Actions:
- 1-3: Deal 4 Earth damage.
- 4-6: Gain 6 Block.

#### Amalgamated Ruins
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 60     |             | Lightning       |

Actions:
- Deal 2 Earth damage.

#### Stasis Automaton
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 10     |             | All             |

Cannot be damaged until Amalgamated Ruins is destroyed.

Actions:
- 1-3: None.
- 4: Shuffle 1 Sapped into Combat deck.
- 5: Flood a random tile.
- 6: Shatter a random tile.

#### Encounter Modifiers

Whenever your Spell Pointer enters a Hazard tile, the Amalgamated Ruin gains 1 Resistance and all enemies Heal 5 Health.

Decay:
- 16 turns

Decay Effect:
- Flood a random tile each turn.
- Enemies become immune to Shatter.









### Runic Nexus

Channels 5 Mana.

#### Rune Golem
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 24     | Earth       | Lightning       |

Actions:
- 1-4: None.
- 5-6: Shuffle 1 Sapped into Combat deck.

#### Voidbringer
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 10     |             | Earth           |

Actions:
- 1-4: None.
- 5: Shuffle a Burn into Combat deck.
- 6: Shuffle a Poison into Combat deck.

#### Beacon of Madness
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 40     |             | Ice             |
|        |             | Fire            |

Actions:
- 1-3: None.
- 4: Shuffle 1 Sapped into Combat deck.
- 5: Shock a random tile.
- 6: Flood a random tile.


#### Encounter Modifiers

Enemy spells count as having Accumulated one additional Mana when resolving successfully.

Decay:
- 16 turns

Decay Effect:
- None.








### Eldritch Convocation

Channels 4 Mana.

#### Eldritch Remnant
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 16     | Lightning   | Fire            |

Actions:
- 1-2: Nothing.
- 3-4: Increase The Harbinger's Intention by 1.
- 5-6: Increase The Harbinger's Intention by 2.

#### Eldritch Echo
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 16     | Ice         | Earth           |

Actions:
- Performs the same action as The Harbinger.

#### The Harbinger
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 40     |             |                 |

Actions:
- 1-2: None.
- 3-4: Deal 3 Void Damage.
- 5-6: Deal 6 Void Damage.


#### Encounter Modifiers

Shuffle a Bleeding into Combat deck whenever you take damage from The Harbinger.

Decay:
- 16 turns

Decay Effect:
- None.









### The Twins

Channels 6 Mana.

#### Aspect of Decay
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 40     | Lightning   | Ice             |
|        | Earth       | Fire            |

Actions:
- 1-2: All enemies heal 4 Health.
- 3-4: All enemies gain 8 Block.
- 5-6: Deal 4 Ice damage.


#### Aspect of Apathy
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 40     | Ice         | Earth           |
|        | Fire        | Lightning       |

Actions:
- 1-2: Deal 4 Fire damage.
- 3-4: Deal 7 Fire damage.
- 5-6: Apply 1 Vulnerable.

#### Encounter Modifiers

Once one Aspect is defeated, the remaining Aspect gains 2 Phantasmal.

Whenever the enemy successfully resolves a Spell, Shatter one tile.


Decay:
- 16 turns

Decay Effect:
- Shock one tile every turn.










### The Repository Archives

Channels 6 Mana.

#### Elder Guardian
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 20     | Fire        | Ice            |

Actions:
- 1-4: Shuffle a Burn into Combat deck.
- 5-6: Force player to draw two Skill Cards.

#### Elder Guardian
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 20     | Earth       | Lightning       |

Actions:
- 1-4: Shuffle a Bleeding into Combat deck.
- 5-6: Force player to draw two Skill Cards.

#### The Collector
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 40     |             | Earth           |

- 1-3: Force player to draw two Skill Cards.
- 4-6: Deal **X\*2** Ice damage, where **X** is the number of cards in the player's hand.

#### Encounter Modifiers

Choose one relic to disable for this combat.

Decay:
- 16 turns

Decay Effect:
- Disable an additional relic.










### The Sovereign Slime

Channels 5 Mana.

#### Large Slime
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 15     | Ice         | Fire            |

Actions:
- 1-4: Deal 2 Ice damage.
- 5-6: Shuffle 1 Poison into Combat deck.

#### Blast Slime
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 10     | Fire        | Ice             |

Actions (Cycling):
- Gain 4 Block.
- Gain 2 Block.
- Nothing.
- Lose 8 Health and deal 20 Fire damage.

### Royal Slime
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 50     | Ice         | Fire            |

Actions:
- 1-2: Heal Blast Slime 4 Health.
- 3-4: Deal 6 Ice damage.
- 5-6: Heal 6 Health and gain 4 Block.



#### Encounter Modifiers

Decay:
- 16 turns

Decay Effect:
- Heal all enemies 4 Health.












### The Champion Apparent

Channels 5 Mana.

#### The Ascendant
| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 75     |             |                 |

Action 1 (Cycling):
- Gain 8 Block.
- Gain 8 Block.
- Nothing.
- Deal **4\*X** Fire damage, where **X** is the number of Mana Accumulated by the Ascendant.

Action 2:
- 1-2: Deal 4 Fire damage.
- 3-4: Gain 4 Block.
- 5-6: Accumulate an additional Mana.

#### Encounter Modifiers

The Ascendant gains 4 Block for each Mana they Accumulate each turn.
Gain 2 Stress every time the Ascendant successfully Resolves a spell.

Decay:
- 18 turns

Decay Effect:
- Gain 1 Stress.












## Bosses




### The Pale King

Channels 6 Mana.

| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 150    | Lightning   | Earth           |
|        |             | Ice             |

Action 1 (Cycling):
- Deal 2 Lightning damage.
- Deal 4 Fire damage.
- Deal 8 Lighting damage.
- Gain 16 Block.
- Take **X\*10** Lightning damage, where **X** is the number of Skill cards in hand.
  Take 8 Stress damage if no Skill cards are in hand.

Action 2:
- 1-2: Shuffle 1 Sapped into Combat deck.
- 3-4: Gain 4 Block.
- 5-6: Deal 6 Lightning damage.


#### Encounter Modifiers

Damaging Skills are placed into Casting Queue instead of activating instantly when played.
Skills that reach the end of the Casting Queue are activated twice.
Whenever the Pale King loses 20 or more Health in one turn, reset the cycling action to the first state.

Decay:
- 20 turns

Decay Effect:
- Can no longer remove stress.
- The Pale King now performs the last cycling action every turn.







### The Consuming Dark

Channels 6 Mana.

| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 120    | Ice         | Fire            |
|        |             | Lightning       |

Action 1 (Cycling):
- Gain 10 Block.
- Gain 10 Block.
- Heal **X/2** Health, where **X** is the Player's Stress.
- Deal **X+10** Ice damage, where **X** is the Player's Stress.

Action 2:
- 1-2: Gain 2 Stress.
- 3-4: Gain 10 Block.
- 5-6: Deal 8 Ice damage.

#### Encounter Modifiers

Gain 1 Stress every turn.
Heal 1 Stress for each Ice Mana you Consume when activating a Skill.
Upon casting a spell of Damage Type Fire or Lightning, heal 5 Stress.

Decay:
- 20 turns

Decay Effect:
- Can no longer remove stress.






### The Endless Tide

Channels 6 Mana.

| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 120    | Fire        | Earth           |
|        |             | Lightning       |

Action 1 (Cycling):
- Gain 6 Block.
- Gain 6 Block.
- Gain 6 Block.
- Deal **X\*8** Ice damage where **X** is the total number of Status and Curse cards in hand.
  Gain 8 Stress if no such cards are in hand.

Action 2:
- 1-2: Shuffle 1 Bleeding into Combat deck.
- 3-4: Shuffle 1 Burn into Combat deck.
- 5-6: Shuffle 1 Hex into Combat deck.

#### Encounter Modifiers

Draw an additional card each turn.
Shuffle a Bleeding into Combat deck whenever you take damage from The Endless Tide.
Whenever you exhaust a Status card, draw a card.
Whenever you exhaust 5 Status cards, gain 1 Phantasmal.
Phantasmal is not removed from damage applied by Status cards.

Decay:
- 20 turns

Decay Effect:
- Can no longer remove stress.
- Can no longer gain Phantasmal.





### Omniphobia

Channels 5 Mana.

| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 135    | Earth       | Lightning       |
|        |             | Ice             |

Action 1 (Cycling):
- Take 4 Stress damage if...
- Take 16 **X** damage if...

...you do not Channel or Consume a **X** Mana this turn, where:
- 1: **X** is Lightning.
- 2: **X** is Ice.
- 3-4: **X** is Fire.
- 5-6: **X** is Earth.

Action 2:
- 1-3: Deal 4 Fire Damage and gain 8 Block.
- 4-5: Deal 8 Earth Damage.
- 6: Gain 1 Phantasmal.

#### Encounter Modifiers

Warp two tiles at the beginning of combat.

Decay:
- 20 turns

Decay Effect:
- Can no longer remove stress.



### The Zenith

Channels 12 Mana. Cast Speed 2.

| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 120    |             | Fire            |
|        |             | Earth           |


Action 1 (Cycling):
- Gain 6 Block.
- Gain 6 Block.
- Gain 6 Block.
- Accumulate an additional Mana this turn.

Action 2:
- 1-2: Deal 6 Ice Damage.
- 3-4: Deal 6 Lightning Damage.
- 5-6: Shuffle 1 Hex into Combat deck.

#### Encounter Modifiers

Shuffle any Mana Accumulated by the Zenith back into Mana deck.
Enemy spells have no effect.
If the Zenith Misfires, you lose 40 Health.
If the Zenith Resolves a Spell, you lose 40 Health and gain 8 Stress.
Every time the Zenith loses 15 Health in a single turn, channel the top two Mana from the Mana deck into the Zenith's Spell Queue.

Decay:
- 20 turns

Decay Effect:
- The Zenith gains 1 Cast Speed.






### The Annihilating Light

Channels 6 Mana.

| Health | Resistances | Vulnerabilities |
| ------ | ----------- | --------------- |
| 100    | All         |                 |


Action 1 (Cycling):
- Gain 8 Block.
- Gain 8 Block.
- Deal 4 Stress damage.
- Deal **(X+5)\*2** Fire damage, where **X** is the Player's Stress.

Action 2:
- 1-2: Shuffle 1 Burn into Combat deck.
- 3-4: Shuffle 1 Sapped into Combat deck.
- 5-6: Deal 2 Stress damage.

#### Encounter Modifiers

Every time you play a Skill, heal 2 Stress.
Every time you draw a Status or Curse card, gain 2 Stress.

Whenever the Annihilating Light loses 20 or more Health in one turn, reset their cycling action to the first state.

While your Stress is 8 or lower:
- Heal 10 Health every turn.
- The Annihilating Light gains permanent Phantasmal.

While your Stress is 12 or higher:
- Take double damage.
- Deal double damage.

Decay:
- 24 turns

Decay Effect:
- Can no longer remove stress.
- The Annihilating Light now performs the last cycling action every turn.











# Relics

## Common Relics (x20)

### Bag of Redraw
"A pouch full of second chances."
- Once per combat, you may discard your either of your hands and redraw up to that many cards.

### Wall Chicken
"An inexplicable meal hidden in the unlikeliest of places. You probably shouldn't eat this."
- Campfire actions that restore Health restore 2 more.

### Iron Marble
"Small but unyielding."
- Draw two additional Mana cards at the beginning of combat.

### Mysterious Disk
"Its purpose is unknown, but it hums with potential."
- You can channel one additional Mana at the start of combat.

### Lantern
"A guiding light through the darkness."
- Draw two additional cards at the start of combat.

### Fractured Stone
"The humble beginnings of a mighty fortress."
- Gain 3 Ward at the start of combat.

### Broken Compass
"It spins wildly, pointing nowhere."
- Once per combat, roll a D20 and randomise the position of your Spell Pointer. If the dice rolls 20, the Spell instantly Resolves.

### Ironwood Totem
"Its roots are ancient, its strength unmatched."
- Immune to damage on first turn.

### Hand-carved Toy Soldier
"It stands at the ready."
- Draw one additional card each turn.

### Slightly-Worn Towel
"Far from pristine, but still comforting."
- If you took no damage during combat, heal 8 Health and 4 Stress.

### Strange Brew
"A bubbling concoction of questionable origin."
- Once per turn, you may convert 1 Mana in your Casting Queue into a Void Mana.
- Gain 2 Stress whenever you activate this relic.

### Ominous Vial
"The label warns of sealed evil within."
- Once per combat, you may choose to gain Stress instead of losing Health, at a rate of 1 Stress per 2 Health.

### Bag of Nails
"Let the blood flow."
- Every time you play three Skills in one turn, deal 5 damage to all enemies.

### Lucky Penny
"Luck is a fickle thing, but it favors the prepared."
- Gain 1 Gold whenever you channel exactly 3 Mana in one turn.

### Bezoar
"A Relic of resilience."
- Ignore the first Blighted tile encountered each combat.
- Ignore the first Poison applied each combat.

### Mechanical Counterweight
"Intricate yet oddly practical."
- Gain 1 Ward whenever you channel two Mana in one turn.

### Bone Effigy
"Whispers of the departed echo within."
- Whenever you take damage from an environmental Hazard, channel one Void Mana.

### Second-place Trophy
"Proof of a valiant effort."
- Draw two cards when a Spell Misfires.

### Glass Bead
"Delicate yet strangely captivating."
- Once per combat, you may freeze one enemy intent, fixing it for the next turn.

### Battered Horseshoe
"It feels lucky."
- Once per combat, you may reroll one enemy intent.





## Uncommon Relics (x25)

### Bloody Satchel
"The leather weeps for its lost owner."
- Gain 10 Gold, 1 Laudenum, and 1 Blessed Water.
- Reveal an additional card when drafting.

### Midas Coin
"It sparkles faintly, even in the dark."
- Whenever you decline to draft a card, gain one Gold.

### Sunstone
"This unremarkable-looking rock feels pleasantly warm to the touch."
- Heal 2 Health at the start of every combat. If your Health is full, gain 4 Ward instead.

### Moonstone
"This unremarkable-looking rock emits a pleasant coolness."
- Whenever a Spell successfully resolves, heal 1 Stress.

### Duplication Potion
"In for a penny..."
- Once per combat, rechannel your entire Casting Queue after a Spell resolves or misfires.
- (The previous Spell still takes effect.)

### Golden Bracelet
"Abundance, greed, envy."
- Whenever you would gain Gold, gain one more.

### Tin Flute
"Despite your best efforts, it remains eerily silent."
- Once per combat, you may instantly draw and channel the top three cards from the Mana deck.

### Broken Oboe
"Broken, but still somehow melodic."
- Whenever you would take damage outside of combat, take one less.

### Vial of Snake Oil
"It is often the case that wanting is more desirable than having."
- Draw four additional cards at the beginning of combat.
- Lose 4 Health for each skill you play after the first each turn.

### Blighted Tome
"The dusty pages seem alive with a sinister energy."
- Gain a random Curse.
- Whenever you cast a Spell with a Curse in hand, gain one gold.

### Bloody Crown
"Power with a price."
- Draw two additional cards each turn.
- Lose 2 Health every time you play a Skill.

### Bone Kantele
"It sings wonderfully with every strum."
- At the start of combat, channel one Void mana.

### Bloodsoaked Pendant
"No matter how you clean it, blood keeps seeping out."
- Heal 2 health at the beginning of each combat.

### Dented Coin
"It bears the scars of countless transactions."
- Gain 15 Gold.

### Defender's Seal
"It looks like it could survive aeons."
- Whenever you would take more than 5 damage, reduce it to 5.

### Bloodstained Script
"The story of a life, now faded and torn."
- At the end of combat, heal one Health for each Curse in hand. If at full Health, or there no Curses in hand, heal two Stress instead.

### Bloody Dice
"Only a red kiss remains."
- Whenever you draw a Curse, heal two Health and draw another card.

### Sealed Vial
"The murky contents shift when you aren't looking."
- Gain 1 Cast Speed for each Curse in hand.

### Prophet's Eye
"Victory is decided before the battle even begins."
- At the start of combat, view the top 5 cards of your Combat deck.

### Molten Crown
"Wreathed in flames, your foes will burn in your glorious presence."
- Every time you channel a Fire mana, take two Fire damage and immediately deal one Fire damage to all enemies.
- Take no damage from Scorch hazards.

### Pocket Sundial
"A shadow looms on its face, unerring, regardless of the surrounding light."
- Once per combat, instantly Accumulate 2 Mana.

### The Storm's Wake
"Your power echoes like thunder after lightning."
- Whenever you successfully cast a Spell, deal 5 Lightning damage to all enemies.

### Voidstone
"A shining little paradox."
- Once per combat, you may ignore the effects of Curses for one turn.

### Ornate Medallion
"It bears a cryptic inscription you can't quite read."
- Whenever you channel Mana of three different types in a single turn, gain 1 Gold.

### Petrified Skull
"The weight of ages has turned it to stone."
- At the start of combat, deal 5 Damage to one enemy.





## Rare Relics (x14)

### Automaton's Soul
"Captivity breeds creativity."
- Whenever you have a selection of Relics, see one more option.

### Crystalised Heart
"A fragile core encased in unbreakable resolve."
- Whenever your Casting Queue has three or fewer Mana channelled, gain 2 Ward.
- Gain 4 Ward at the beginning of combat.

### The Overture
"Every masterpiece begins with a single note."
- Channel 1 additional Mana at the start of combat.
- The first Spell you cast each combat ignores all Resistances.

### Entropic Sigil
"The path of least resistance."
- Start each combat with two Void mana channelled.

### Roku's Basilisk
"Impossible escape."
- Whenever a Spell Misfires, instantly rechannel the last three Mana Accumulated by the Misfired Spell.

### Celestial Chains
"Disquieting whispers of writhing pain, tempered by steel."
- Draw two additional cards per turn.
- You can channel one additional Mana per turn.
- Take 1 damage every time you channel Mana.

### Soul Mantle
"While victory and defeat are decided by tacticians, living and dying will always lay in the realm of warriors."
- Gain 4 Ward whenever you kill an enemy.
- Whenever you kill an enemy, heal 4 Health and draw three Skill cards.

### Dawn's Embrace
"One loved by the Sun fears not the endless darkness."
- Gain 1 Phantasmal at the beginning of combat.
- Ignore the first instance of Stress gain each combat.
- While you have Ward, enemies are Vulnerable to Fire damage.

### The Hanged Man
"A perspective of sacrifice unveils untold wisdom."
- You may spend Health in place of Mana for skills, at a conversion rate of 10 Health per 1 Mana.
- At the start of combat, draw 1 additional card for each 10 Health missing.
- Whenever your hand is empty, draw 3 cards.

### Lightning Coil
"Embrace the storm, do not resist, and let it freely flow through you."
- Your Spell damage type is always Lightning.
- Become immune to Shock.
- Enemies cannot Resist Lightning damage.

### The Coming Storm
"Stand your ground and look in the eye of the coming storm."
- Become immune to Flood.
- Shatter and Shock your current tile upon taking damage.
- Once per combat, you may choose to spread a Shatter or Shock Hazard to an adjacent tile.

### The Divine Flame
"Cinders cling to your every step, leaving trails of destruction in your wake."
- Every time you cast a Spell, Scorch your current tile.
- Every time you Misfire, Scorch all adjacent tiles.
- Whenever you would take damage from a Scorched tile, redirect the damage to one enemy.

### Abyssal Pearl
"Stillness and flow converge in a balance of destruction and serenity."
- Whenever you channel Ice mana, heal 2 Health.
- Whenever you cast a Spell with Damage type Ice, lose 4 Health and Warp the current tile.
- Once per turn, you may convert two adjacent channelled Ice mana into one Void mana.

### Petrified Heart
"With a single strike, the ground quakes and crumbles beneath your enemies."
- Whenever you cast a Spell with Damage type Earth, Shatter the enemy's current tile.
- Gain 4 Ward whenever you enter a Shattered tile.






## Boss/Elite Relics (x10)

### Infinite Loop
"The end is never the end is never the end is never the end is..."
- Draw an additional card each turn.
- Gain +2 to maximum hand size.

### Langford's Fractal
"The raging storm of mana contained within lies nonetheless in perfect balance."
- Enemies gain the following effect:
  - Upon taking damage of type **X**, Resist **X** damage and become Vulnerable to non-**X** damage until next instance of damage.
- Spells of length 3 or less deal no damage.

### Warped Timepiece
"Despite the worn and twisted glass, the sand flows through with nervous regularity."
- At the beginning of combat, mark one Rune tile of your choice.
- Once per spell, you may teleport your Spell Pointer to the marked Rune tile.
- The first time you reach Death's Door each combat, heal to half Health and set Stress to 16.

### Sacrificial Heart
"The hunger only grows."
- At the beginning of combat, roll a D20 and delete a Rune tile.
- Enemy spells now Misfire from misnavigations into the missing tile.

### Gödelian Sigil
"Its cryptic inscriptions defy finite comprehension."
- At the beginning of combat, select two Rune tiles to quotient together. Spell pointers treat the two tiles as the same, and transitions out of either tile may be chosen at will.
- You may choose to change these connected tiles instead of rotating two tiles (as per normal rules).

### Möbius Chain
"A chain of infinite twists, trapping its bearer in paradoxical loops."
- At the beginning of combat, select an element. All Hazards of that element are quotiented together.
- At the end of your turn, you may select a new element. This ability has a cooldown of 2 turns.

### Pathfinder’s Compass
"Its needle never points north, only toward possibility."
- Once per turn, you may force an enemy to take a transition regardless of Mana type.
  Mana is still Accumulated when this ability is used.
- Whenever you activate this ability, you cannot move your Spell Pointer this turn.

### Eternity's End
"The cycle of endings begins anew."
- Whenever you gain Stress, heal 4 Health.
- Whenever you draw a Curse, gain 1 Resistance.

### Amulet of Yendor
"It is said to possess powers which mere mortals can scarcely comprehend, let alone utilize."
- Once per turn, you may decrease one enemy intent by up to 3.
- You cannot gain Block unless you consume Fire or Lightning Mana that turn.

### The Red Book
"The cursed grimoire seeks not to be understood, but obeyed."
- All Skill cards gain Exhaust.
- Each turn, the first Skill played activates twice.




