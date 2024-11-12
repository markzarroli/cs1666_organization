# AI Advanced Topic Presentations

Before your presentation, use this file to get your talk outline approved. Be
sure to provide an estimated time to spend on teach topic (totalling 45 minutes)
and be sure not to repeat any topics covered in previous presentations.

## Presentation 1
### Stragglers

- Introduction (3 minutes)
  - What is enemy AI?
  - What can/should enemy AI do?
  - Player Perception of AI
    - How does AI make the enemy seem intelligent?
    - What makes it fun to beat an enemy AI?
- Types of Enemy AI (7 minutes)
  - Decision Trees & Pathfinding (real time combat)
  - Turn-based (w/Pros & Cons)
    - Random
    - Conditional
    - Monte Carlo Tree Search
    - Goal Oriented Action Planning (GOAP)
  
- The GOAP Algorithm (15 minutes)
  - Why we chose this algorithm
  - Where did it come from?
  - Examples of the algorithm in games
  - Implementation
    - Finite State Machines
    - Priority Queues

- GOAP Implementation Specific to our Game (20 minutes)
  - Demonstration/examples
  - Stat equations and considerations related to the algorithm

## Presentation 2
### Fishing

- What is a Bayesian Network? (15 minutes):
  - Independence and Dependence
  - Calculating joint probabilities
  - Bayes Theorem
- Why We Chose the Bayesian Network Approach (5 minutes):
  - Logic behind our game probability
    - Collision model
    - Fish movement
- Fish types/models (5 minutes):
  - Individual fish stats
  - Fish species stats
- Uncertainties in the game and how they factor into probability calculations (15 minutes):
  - Weather
  - Time of Day
  - Items from the shop
    - Lures, lines, etc.
  - Collision items
- Fish spawning model and how that will affect probability (5 minutes)
