# Pyraminx-distribution
Distribution of a pyraminx Rubik's cube. Traverses the graph with BFS until all the states are explored.
Inspired from `Import Math` [video](https://www.youtube.com/watch?v=4mja0aMUX_Y).

## How to use:
$ python search.py > PyraminxAllStates.txt (or your file name)

## Contains:
- PyraminxAllStates.txt: number of states in each layer (generated with search.py)
- It adds the time it takes to generate them

## TODO:
- Document
- Optimize run-time
- Also generate the number of cases for each depth (now generated with $ cat PyraminxAllStates.txt | grep "Depth" > PyraminxDepths.txt )
- Use large files
