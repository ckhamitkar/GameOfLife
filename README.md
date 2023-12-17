Game of Life is a type of cellular automata deterministic model ideated by the English mathematician John Conway. In cellular automata models, you have a grid representing the state space and the simulation unfolds in discrete steps. Changes between the steps in the state of the individual cells composing the grids depend only on neighboring cell states at the previous step. The Game of Life is a zero players game, in the sense that a user can just at best define the initial configuration of the grid and then the game is going to evolve entirely on its own.

Each cell in the grid can either be alive (1) or dead (0) and which cells are classified as alive or dead is determined based on four possible conditions:

Stasis: Living cells with 2–3 living neighbors will continue living
Overpopulation: Living cells with more than 3 living neighbors will die
Underpopulation: Living cells with less than 2 living neighbors will die
Reproduction: Dead cells become alive if they have exactly 3 living cells as neighbors
One of the most common ways to treat the boundaries of a grid is to assume opposing edges are connected (e.g. the bottom row has as a neighbor the top row of the grid). Alternatively, it can be imagined as if the grid is padded with all dead cells around its border. States within the grid can be represented in two possible ways:

Dense representation
Sparse representation
Once a simulation in the Game of Life is started, different recurring patterns might come to life depending on the initial state of the board. Some examples are listed here:

Still Lifes are structures that reach a perfect equilibrium and do not change over time (e.g., Block, Loaf).
Oscillators are structures that have a recurrent pattern and do not change positions in the grid (e.g., Blinker, Beacon).
Spaceships are structures able to move across the grid while maintaining their integrity (e.g., Glider, Weekender).
