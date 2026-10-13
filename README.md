# knights-travails

# Knights Travails ♞

A JavaScript project that finds the shortest path a knight can take between two squares on a chessboard.

## About

This project is part of [The Odin Project](https://www.theodinproject.com/lessons/javascript-knights-travails).

The goal is to use graph traversal algorithms to find the shortest path between two positions on a chessboard.

## How It Works

- The chessboard is represented by an 8×8 grid.
- Each square is represented by a pair of coordinates, ranging from `[0, 0]` to `[7, 7]`.
- The knight can move in an L-shape, with up to eight possible moves from each square.
- Invalid moves that go outside the board are ignored.
- Breadth-First Search (BFS) is used to find the shortest path.
- The function returns the sequence of positions from the starting square to the destination.

## Example

A knight moving from `[0, 0]` to `[3, 3]` can reach its destination in two moves.

The returned path may vary, as multiple shortest paths can exist.

## Concepts Practiced

- Graphs and graph traversal
- Breadth-First Search (BFS)
- Queues
- Arrays and coordinate manipulation
- Tracking visited positions
- Path reconstruction
- Algorithmic problem-solving

## Getting Started

1. Clone this repository.
2. Open the project in your code editor.
3. Implement the `knightMoves` function.
4. Run your tests to check that the function returns valid shortest paths.

## Testing

The function should be tested with:

- Positions reachable in a single move.
- Positions requiring multiple moves.
- The same starting and ending position.
- Positions near the edges and corners of the board.
- Different pairs of starting and ending positions.

## What I Learned

*This section can be updated after completing the project with the main concepts and challenges encountered during implementation.*

## Acknowledgements

Project assignment from [The Odin Project](https://www.theodinproject.com/), part of its JavaScript curriculum.
