# Procedural Generation Advanced Topic Presentations

Before your presentation, use this file to get your talk outline approved. Be
sure to provide an estimated time to spend on teach topic (totaling 45 minutes)
and be sure not to repeat any topics covered in previous presentations.

## Presentation 1
### Pixel Stellar

- Topic 1: What is Noise? (05 minutes):
  - Different types of noise (white noise,  rigid fractal noise, cellular automata, etc.)
    - Perlin Noise as the main topic of the presentation.
  - Brief discussion on how pure randomness is different from perlin noise
- Topic 2: Perlin Noise (05 minutes):
  - Original function written by Ken Perlin
    - Brief information on Ken Perlin as a computer scientist
  - Created in 1983 for the CGI film *Tron (1982)*
  - Improvement to the algorithm in 2002
- Topic 3: Why Perlin Noise? (10 minutes):
  - In-depth comparison to pure randomness
    - White Noise is too rough for video games
    - Perlin Noise creates smooth transitions between random values (better for video games)
  - Spatial Coherence (smooth transitions)
    - Essential for natural looking generation in video games
  - Applications in video games
    - Terraria world generation
    - Minecraft world generation
    - (Possible) other world generation
- Topic 4: The Algorithm (25 minutes):
  - 1D generation
  - Start with array of randomly generated numbers
    - These can be viewed as the slope of a linear equation
  - Linear interpolation can be used to generate values between the slopes
    - This creates what looks like a smoother line of a function
  - Smooth step function can be used to further smooth the transition near the slopes
  - Octaves can be added to create more variation to the smooth curve
  - Extension into 2D
    - Grid of unit (directional) vectors instead of slopes
  

## Presentation 2
### Stragglers

- Topic 1: Introduction to maze generation using proc gen (5 mins)
  - Show different examples of procedural generation algorithms and what their mazes look like
  - Brief mention of minimum spanning trees (Prim’s and Kruscal’s) and depth-search algorithms
  - Problems with these algorithms when creating a maze → biased towards short dead ends/ long corridors
- Topic 2: Overview of Wilson’s Algorithm (10 mins)
  - Uniform spanning trees - what they are/why we would want to use this in our game
  - How Wilson’s Alg works
      - Series of random walks that add cells to the UST
      - After a walk is completed, it is stepped through again and loops are erased from the path
- Topic 3: Implementation (25 mins)
  - steps:
    1) Choose a random starting cell and add it to the uniform spanning tree
    2) Choose another cell that has not been added yet and do a random walk until reaching the UST
    3) Keep track of direction as each cell is added → will allow for removing loops 
        - Once a walk has been found, go through again following the directions and disregard any cells that are not needed
        - Add the remaining touched cells in the walk to the UST
    4) Repeat b and c until all cells have been added
  - Include examples/visuals of different ways the algorithm can play out with different-sized mazes
- Topic 4: Conclusion (5 mins)
  - Pros and cons of Wilson’s 


## Presentation 3
### Pirates

- Topic 1: Introduction + History (12 minutes):
  - Brief history of algorithm
    - Model synthesis (2007)
    - Wave function collapse (2016)
      - Evolution from model synthesis to WFC
    - Ties to quantum computing
      - Wave function collapse overview
      - How WFC models quantum particle behavior
    - Reasons for choosing algorithm
      - WFC vs perlin noise and the needs of our game
- Topic 2: Wave Function Collapse Example (15 minutes):
  - What is entropy in WFC
    - How we choose the next tile
    - Effects of collapsing a tile on entropy
  - Writing WFC rules
    - Hard-coded rules vs. dynamic sample
      - pros and cons of each approach
        - hard-coded is less flexible but simpler
        - dynamic sample is resuable, reduces rewriting code for new tilemap environments but more complex to implement
  - Animated example walkthrough of algorithm
    - entropy comparison at beginning, each step, and end state
- Topic 3: Code Explanation + Walkthrough (15 minutes):
  - Tailoring WFC
    - Weighing tiles, seeding pathways + fixed landmarks
- Topic 4: Conclusion (3 min)
  - Pros and cons

## Presentation 4
### Cuscuta

- Topic 1 ... (XX minutes):
  - ...
- ...
