# mazes-for-programers

# These are the notes to go with the code I wrote while going through the book

# Algorithms used

## The Binary Tree Algorithm

zero, one or two child values per step\
values arrange hierachiaclly\
leaf node has no child value\
one parent node\
it is fast, efficient, simple\
it is O(n)\
Binary tree will bias an ubroken top and far right corridor texture

## Sidewinder Algorithm

similar to binary tree, but has less biases.\
it will carve a path between adjacent cells before going north\
favours starting in the western corner\
Sindewinder must visit every cell in the grid at least once\
Sidewinder can move to any row it likes, but must start each row at the beginning.\
Sidewinder will bias an unbroken top corridor texture

## Dijkstra's Algorithm

##

##

##

##

##

##

##

##

##

###

# Terms

Perfect Maze - where every cell can reach every other cell. there will be some dead-ends. there is exactly one path between any two cells.
\
Braid Maze - this will have a few/ to none dead-ends \
Multicursal Maze - mazes with branching passages \
Unicursal Maze - mazes with zero branching passages\
maize texture - refers to the style of the passage of the maze\
bias - refers to an algorithm's tendancy to produce mazes of certain textures. eliminating an alogrithm's bias is rarely simple, or even possible. If you can't use the texture that a given alogrithm produces, it's often easiest to look elsewhere.\
run - refers to a series of cells visited\
closing out the run -refers to moving on from a run, where no further changes are made to that run of cells\
