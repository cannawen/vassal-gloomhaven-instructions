[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

# Vassal x Gloomhaven
How to set up a remote Gloomhaven (v1.1) game for free using Vassal (v3.2.17)

# Getting Started
- Download Vassal https://www.vassalengine.org/index.php  
- Download Gloomhaven module and extensions http://www.vassalengine.org/wiki/Module:Gloomhaven  
- Open Vassal and add Gloomhaven Module: `File -> Open Module -> Gloomhaven 1.1.vmod`  
- Add extensions: Right click `Gloomhaven Module -> Add Extension... -> (extension).mdx`  
- Double click Gloomhaven Module, look for a game online
- Click third left/right arrow button to show Active Games
- Type name of your room under in "New Game" box
- Click `File -> New Game`  

Your friends can now join your room! Right click your room to lock it

# Game Setup
Once you are in a game, here is how to set it up (you only have to do this once)

## Character Setup
- Click `Hero -> Setup Hero` and right click the character to set it to P1
### Cards
- Click `P1 Hand` all level 1 cards are stacked in the top left corner of this page
- Drag them off the grey colour, onto the whitespace
- Click `Hero -> Level Up` and select your class from the top
- Find your cards, drag and drop the images onto the whitespace on your `P1 Hand` board
- The grey spaces represent the cards in your hand that you will bring to any scenario, so you can choose some of your "must have" cards to place here
### Modifier Deck
- Click `P1 Board` and drag all of the facedown modifier cards out to the empty side of the board
- Looking at your perks, right click and remove all appropriate modifier cards
- Click `Hero -> Level Up` and select your class from the top
- Click `Battle Deck` and find the appropriate modifiers you need
- Drag and drop them onto your `P1 Board`
- Drag all modifier cards back on the modifier draw pile (they should stack neatly, facedown)
### Items
- Click `Hero -> Item Deck`
- Find the items you are looking for, right click `P1 Item`
- Click `P1 Board`
- All items will be stacked on top of the first slot. Drag them to other slots as appropriate

# Play a scenario
You will have to do this every time you start a scenario
## Scenario setup
- Click `Predefined Scenarios` to find the scenario you are doing
- Click `Setup Enemy Decks`
  - To set up enemies manually, go to `Dungeon -> Enemy Deck` and right click `Set up as Enemy #`
- Click `Dungeon -> Enemy Board` and `Change Enemy Level` to appropriate level
- Close `Predefined Scenarios` or skip the next few steps and use it as your main play area if you don't mind behind-the-door spoilers
- Click `Dungeon -> Dungeon Board` to open Main Board
- Click `Dungeon -> Dungeon Setup`
  - Click `Tiles` and drag the first room tile onto the Main Board
  - Click `Token` and drag the appropriate traps, etc. onto the room tile
  - Click `Enemy Token` or `Boss Token` and drag enemies on the room tile
  - Click `Hero Token` and drag your character tokens on the room tile
  - Click `Enemy Sheet` or `Boss Sheet` and drag it to beside the room tile (right click to rotate it to the desired difficulty level)
- Click `Dungeon -> Battle Goals` and drag 2 battle goals to each player board
  - Player may return 1 to the Battle Goals stack
- Click `Token -> MonsterInitID`
  - Drag a random number to each visible monster
  - Also drag the same number to beside the Enemy/Boss Sheet to count damage
## Character setup
- Click `P1 Hand` and choose which cards you want to bring on the scenario by placing them on the grey rectangles
- Click `P1 Board` and set your appropriate HP
- Click `Dungeon -> Dungeon Board` and move your character token to your starting position
## Play a turn
- Each player chooses two cards to play from their hand, and drags them onto the Main Board
- Click `Dungeon -> Enemy Board` and drag a facedown enemy card to the discard pile
- Resolve turn in initiative order, dragging and dropping hexes on the room tile as appropriate
- Attacking
  - Drag a facedown attack modifier card to the discard pile to flip it over
  - Right Click and `Return to Battle Deck` to shuffle discards back into your deck
- Resting
  - Short rest: Right click Discard pile and `Shuffle`. Drag top card to Lost pile (or take 1 Damage to lose the 2nd card)
  - Long rest: Right click Discard pile and `Draw Specific Card` to bring it to the top. Drag card to Lost pile
  - Note: I have had very bad luck using `Return to Hand` where the cards just disappear instead, so I recommend dragging all the cards back to your hand
- To add curses/bless/-1, click `Token -> Battle Deck Modifier`
- When the turn is done, drag your two cards onto your Player Board (discard, persistent effect, or lost pile as appropriate)
- If you click on `Token` you can drag money, status effects, damage, and summons onto the board
- Click `Dungeon -> Element Board` to modify elements

# Troubleshooting
"My `P2/P4 Hand` button is greyed out"  
Click `Retire -> Join another side -> Solo` to enable all buttons, or upgrade to Version 1.2

---

This information should be enough to get a basic game of Gloomhaven going on Vassal. See this [BGG thread](https://boardgamegeek.com/thread/2379085/gloomhaven-vassal-module/page/1) for more up-to-date info

GLHF and #staythefuckhome
