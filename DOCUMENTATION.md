# Assessment Task 2: Object-Oriented Design Project: Car Comparison Game
**By Arisa Komatsu**

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