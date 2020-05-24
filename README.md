[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

# Vassal x Gloomhaven
How to set up a remote Gloomhaven (v2.2) game for free using Vassal (v3.2.17)  
[See here for v1.3 instructions](https://github.com/cannawen/vassal-gloomhaven-instructions/tree/v1.3)
[See here for v1.1 instructions](https://github.com/cannawen/vassal-gloomhaven-instructions/tree/v1.1)

# Getting Started
- [Download Vassal](https://www.vassalengine.org/index.php )  
- [Download Gloomhaven module and extensions](http://www.vassalengine.org/wiki/Module:Gloomhaven)  
  - `Gloomhaven_2.2.vmod`
  - `Gloomhaven_Heroes_2.0.vmdx`
  - `Gloomhaven_Scenarios_2.0.vmdx`
  - `Gloomhaven_Forgotten_Circles_2.0.vmdx` (optional)
- Move downloaded files into a folder
- Open Vassal and add Gloomhaven Module: `File -> Open Module -> Gloomhaven_2.2.vmod`  
- Close setup wizard if it opens up
- Add extensions: Right click `Gloomhaven Module -> Add Extension... -> (extension).mdx`  
- Double click Gloomhaven Module to open setup wizard, look for a game online
- Click third button with two arrows (or hit alt+s) to show Active Games
- Type name of your room under in "New Game" box
- Click `File -> New Game`  

Your friends can now join your room! Right click your room to lock it

# Game Setup
Once you are in a game, here is how to set it up (you only have to do this once)

## Character Setup
- Click `Hero -> Setup Hero` and right click the character to set it to P#
### Cards
- Click `P# Hand` and then `Spread all cards` (all your L1 cards are stacked in the first slot by default)
- Click `Hero -> Level Up` and select your class from the top
- Find your cards, drag and drop the images onto the whitespace on your `P# Hand` board
- The grey spaces represent the cards in your hand that you will bring to any scenario, so you can choose some of your "must have" cards to place here. Place the rest off to the side/bottom of the main 12 squares on this screen
- Right click to add enhancements
  - Each number (1, 2, 3, 4) represents an enhancement on the Bottom or Top of your card
  - Click "Next" to scroll through different kinds of enhancements
### Modifier Deck
- Click `P1 Board` and drag all of the facedown modifier cards out to the empty side of the board
- Looking at your perks, right click and remove all appropriate modifier cards
- Click `Hero -> Level Up` and select your class from the top
- Click `Battle Deck` and find the appropriate modifiers you need
- Drag and drop them onto your `P1 Board`
- Drag all modifier cards back on the modifier draw pile (they should stack neatly, facedown)
- If you want to draw a specific modifier card, right click the deck and select `Draw specific cards`
- If you need to find removed cards, go to `Hero -> Lost Battle Cards`. Each quadrent represents each player's lost modifier cards
### Items
Option 1 - Keep track of which items are available in your shop  
- Go to `Hero -> Item Deck`
- `Right Click -> Send to Available Items` all items your party has unlocked. 
- Click `Hero -> Available Items`  

Option 2 (easier) - Make all items available on Vassal
- `Hero -> Item Repo` and drag all items into first slot
- Click `Hero -> Item Deck`

With either option you choose
- Find the items you are looking for, right click `P# Item`
- Click `P# Board`
- All items will be stacked on top of the first slot. Drag them to other slots as appropriate

# Play a scenario
You will have to do this every time you start a scenario
## Scenario setup
- Click `Predefined Scenarios` to find the scenario you are doing
- Click `Setup Enemy Decks`
  - To set up enemies manually, go to `Dungeon -> Enemy Deck` and right click `Set up as Enemy #`
- Click `Dungeon -> Enemy Board` and `Change Enemy Level` to appropriate level
- You can play on the `Predefined Scenarios` page or on `Dungeon -> Dungeon Board` and create the rooms manually
- Click `Dungeon -> Dungeon Setup`
  - Click `Tiles` and drag the first room tile onto the `Main Board` if not playing with `Predefined Scenarios`
  - Click `Token` and drag the appropriate traps, etc. onto the room tile
  - Click `Enemy Token` or `Boss Token` and drag enemies on the room tile
  - Click `Hero Token` and drag your character tokens on the room tile
- Each player can click `Dungeon -> Battle Goals` and drag 2 battle goals to their player hand
  - Each player can return 1 to the Battle Goals stack
- Right click each monster to set an initiative & starting HP
## Character setup
- Click `P1 Hand` and choose which cards you want to bring on the scenario by placing them on the grey rectangles
- Click `Dungeon -> Dungeon Board` and move your character token to your starting position
- Right click and set your character's initial HP
## Play a turn
- Each player chooses two cards to play from their hand, and drags them onto their board
- Click `Dungeon -> Enemy Board` and drag a facedown enemy card to the discard pile
- Resolve turn in initiative order, dragging and dropping hexes on the room tile as appropriate
- Attacking
  - Drag a facedown attack modifier card to the discard pile to flip it over
  - Right Click and `Return to Battle Deck` to shuffle discards back into your deck
- Resting
  - Short rest: Right click Discard pile and `Shuffle`. Drag top card to Lost pile (or take 1 Damage to lose the 2nd card)
  - Long rest: Right click Discard pile and `Draw Specific Card` to bring it to the top. Drag card to Lost pile
  - Right click `Return to Hand` and then `Spread All Cards` to reset view of your remaining hand
- To add curses/bless/-1, click `Token -> Battle Deck Modifier`
- To add summons, click `Token -> Summon`
- When the turn is done, drag your two cards onto your Player Board (discard, persistent effect, or lost pile as appropriate)
- Click `Dungeon -> Element Board` to modify elements

Note: if you have a hard copy of the game, it may be easier to manage your cards IRL instead of using the player board/player hand

---

This information should be enough to get a basic game of Gloomhaven going on Vassal. See this [BGG thread](https://boardgamegeek.com/thread/2379085/gloomhaven-vassal-module/page/1) for more up-to-date info

GLHF and #staythefuckhome
