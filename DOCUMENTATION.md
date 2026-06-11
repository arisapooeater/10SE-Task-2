# Assessment Task 2: Object-Oriented Design Project: Car Comparison Game
**By Arisa Komatsu**

## Process Planning
| Steps | Reasoning | Expected Result | Time |
|-|-|-|-|
| Part D | I believe it'd be difficult to start any other part of this task without having some kind of idea of what I want my game to be like. I will be doing Part D first so my game mechanics can guide how I design other aspects like the attributes and card design of this game. | A clear explanation of my game's mechanics, a structure representing the game's modules and overall design and an analysis into game balance and any possible improvements in terms of fairness. | 2 hours |
| Part A | Similar to my reasoning for Part D, identifying what attributes that will be in my game would be ideal before I start any class diagrams (which require us to know attributes for the card class), and I need to know the names of the attributes for when creating the wireframe-like design of my card for design clarity. | The list of 6 attributes that will feature on my top trumps cards and a comparison/explanation into their strengths and fairness. | 1 hour | 
| Part B | Working on the class diagram after figuring out attributes feels like the most logical process to me as any ideas/issues I had in Part D and A are still reasonably fresh in my mind and its not really something I need to keep for last. | A class diagram with attributes and methods for each of the required classes with an explanation of its role in our game. | 1.5 hours |
| Part E | Personally, Part E is the part of the project I like the most and therefore I'll be doing it after Part B as a sort of mind reset before I do the UML diagrams, which I'm dreading the most. Additionally, it's also the most distinct part of the project, so it helps putting it between Part B and C as it makes this task feel less grueling and repetitive. | An annotated Top Trumps style card design, an annotated basic game interface sketch and storyboards into the game process. | 2 hours | 
| Part C | I struggle a lot with UML diagrams and therefore think it would be better to do my UML diagram near the end of this design process as to make sure I have a clear understanding of all my classes, attributes and game mechanics before making my UML diagram. This will ensure it accurately represents my ideas| A UML diagram with 2-3 annotated design choices representing all the classes and relationships in my game. | 2 hours |
| Part F | I feel like its self-explanatory that I'll be doing Part F last as its ultimately an analysis into my overall game in realation to its impacts and implications, meaning it would be best to do when I have full understanding and clarity of what my game is like. | A critical analysis into the social, ethical and legal implications of my car comparison game. | 3 hours | 

## Part A - Data Selection and Game Attributes
using car listings as inspiration:
- select 6 attributes for your game(eg. price, km, power)
- rank them from most powerful to least powerful in the game mechanics
- explain why each attribute was chosen + what makes an attribute fair or unfair in gameplay

- price - higher is better
- year launched - older is better 
- top speed - higher is better
- total produced / rarity - lower is better
- curb weight - lower is better
- Cool Factor - higher is better

## Part B - Class Design
Design the object-oriented structure of your game

required classes
- car
- card
- deck
- player
- game

for each class
- list attributes, methods
- describe its role in the system

## Part C - Class Diagram
Create a UML class diagram including
- all classes
- attributes and methods
- relationships (association, aggregation, inheritance if used)

must include
- clear structure
- correct relationships
- at least 2 annotated design decisions

## Part D - Game Mechanics Design
My car comparison game is, in summary, a Stratego-esque Top Trumps board game. It is a two player game that is played on a 6 x 6 grid, where on each square is an attribute corresponding to the car cards (eg. top speed, cool factor). The game begins with both players being handed 10 cards each, which they should line on the outer squares of the 6x6 grid on their side of the grid. Cards should be oriented facing down towards your opponent as to not confuse player cards. 

Each round, each player is allowed to move one card orthogonically or diagonally by 1 square, with the knowledge that they cannot have 2 of their own cards on the same square. If two cards (both players' cards) occupy the same square, both players must flip their card over and compare the stats of the attribute written on the matched square. The player who wins the round will depend on the attribute:

- **price:** highest wins
- **year launched:** oldest wins 
- **top speed:** highest wins
- **total produced / rarity:** lowest wins
- **curb weight:** lowest wins
- **cool factor:** highest wins

The losing card is removed from the board, while the winning card remains, flipped face down again. In the instance that both players have equal stats, both cards must be removed from the board. The player who remains with cards on the board wins, and the game ends. If both players end up with matching stats on their last cards, the game concludes in a draw.

### How is this game fair?
The game balance is ensured by the random nature of each square's attribute and the attributes of the card you receive. Unlike a typical Top Trumps game, players don't get to have the advantage of choosing attributes to compare, which not only helps create anticipation/tension when flipping the cards, but also contributes to minimising any imbalances caused by this. Additionally, the board is 6 by 6 to ensure that there is an equal amount of squares for each attribute to prevent any advantages for specific attributes.  

However, one possible unfair advantage that may occur in this game is the fact that some specific types of cars, like large heavy duty vans are quite disadvantaged as none of the attributes are specifically favourable, while light luxury cars are quite advantageous cards. On the other hand, I feel having specific cars that are more advantageous as others is important for creating variation in gameplay, however a solution that could help make the game a little more fair is to rule out vans as they are not technically "cars", and to decrease the amount of these advantageous car cards in a deck to make sure any advantageous cards help make the game interesting while not greatly impacting the actual game's results.

### Structure Chart 
- insert structure chart

![Modelled Structure Chart of GAME](./images/)

## Part E - Interface and Card Design
Create
- a card design (top trumps style)
- a basic game interface sketch

Must include
- labels and annotations explaining design choices
- clear layout of information
- storyboards and/or walk through

## Part F - Social, Ethical and Legal Implications
### 1. Individual Impact
**How could your game influence user behaviour or decision-making?**

**Could it encourage bias (eg. favouring expensive or high-performance cars)?**

**What responsibilities do you have as a designer to present fair information?**

---
### 2. Social Impact
**How might your game reinforce stereotypes or inequalties(eg. wealth, status, access to vehicles)?**

**Does your system favour certain types of users or cars?**

**How could your design be made more inclusive or fair?**

---
### 3. Environmental Impact
**How could your game influence attitudes toward fuel use, emissions, or sustainability?**

**Does your attribute selection promote or ignore environmental considerations?**

**What changes would you make to encourage more environmentally responsible thinking?**

---
### 4. Legal Considerations
**What legal issues could arise from using real-world car data (eg. ownership, copyright, accuracy)?**

**What responsibilities do you have when displaying or using data inspired by platforms like carsales.com.au?**

**How would you ensure your system avoids misleading users?**