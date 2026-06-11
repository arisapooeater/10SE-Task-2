# Assessment Task 2: Object-Oriented Design Project: Car Comparison Game
**By Arisa Komatsu**

## Process Planning
| Steps | Reasoning | Expected Result | Time |
|-|-|-|-|
| Part D | I believe it'd be difficult to start any other part of this task without having some kind of idea of what I want my game to be like. I will be doing Part D first so my game mechanics can guide how I design other aspects like the attributes and card design of this game. | A clear explanation of my game's mechanics, a structure representing the game's modules and overall design and an analysis into game balance and any possible improvements in terms of fairness. | 2 hours |
| Part A | Similar to my reasoning for Part D, identifying what attributes that will be in my game would be ideal before I start any class diagrams (which require us to know attributes for the card class), and I need to know the names of the attributes for when creating the wireframe-like design of my card for design clarity. | The list of 6 attributes that will feature on my top trumps cards and a comparison/explanation into their strengths and fairness. | 1 hour | 
| Part B | Working on the class diagram after figuring out attributes feels like the most logical process to me as any ideas/issues I had in Part D and A are still reasonably fresh in my mind and its not really something I need to keep for last. | A class diagram with attributes and methods for each of the required classes with an explanation of its role in our game. | 1.5 hours |
| Part E | | An annotated Top Trumps style card design, an annotated basic game interface sketch and storyboards into the game process. | 2 hours | 
| Part C | I struggle a lot with UML diagrams and therefore think it would be better to do my UML diagram near the end of this design process as to make sure I have a clear understanding of all my classes, attributes and game mechanics before making my UML diagram. This will ensure it accurately represents my ideas| A UML diagram with 2-3 annotated design choices representing all the classes and relationships in my game. | 2 hours |
| Part F | | A critical analysis into the social, ethical and legal implications of my car comparison game. | 3 hours | 

## Part A - Data Selection and Game Attributes
using car listings as inspiration:
- select 6 attributes for your game(eg. price, km, power)
- rank them from most powerful to least powerful in the game mechanics
- explain why each attribute was chosen + what makes an attribute fair or unfair in gameplay

- price
- year launched
- top speed
- total produced / rarity 
- curb weight
- Cool Factor

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
2 Player Stratego x Top Trumps Board Game

Cards are oriented facing away from player to identify each players cards

Played on a 6 x 6 grid 
Game begins with players being handed 10 cards each. They should line the cards on the outer squares of the 6x6 grid on their side of the grid, all facing down toward their opponent. 
Each round, each player is allowed to move one card orthogonically or diagonally by 1 square, with the knowledge that they cannot have 2 of their own cards on the same square. If two cards occupy the same square, both players must flip their card over and compare the stats of the attribute written on the matched square. The person with the lower stats must then remove their card from the board, and the person with the higher stats keeps their card, but flips it back down. If both players have equal stats, both players must remove their cards. 

The player who remains with cards on the board wins. If both players end up with matching stats on their last cards, the game ends in a draw.

Explain how the game works:
- how a round is played
- how attributes are selected
- how winners are determined
- what happens in a draw
- how the game ends

must include
- explanation of game balance
- identification of at least one unfair advantage and a proposed solution to fix it
- a modelled structure chart

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