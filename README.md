# 8-Puzzle-Problem

programming language used for this task is python(3.7) using google colab.

you can run the code on Jypiter notebook or google colab

1st run the code with class Agent which consist the code for all the searches asked in the assignment.
2nd run the below code where we initialize the start and goal state give in the assignment
3rd run the next code by calling the fuction with appropriate values.

after completing the run of above cells you can run remaining further cells of whichever search you would like to explore.

the output format-
gives each step of the iteration(1,2,3....).
and the changes made in the matrix.
followed by the action taken(left/right/up/down).
depth of every iteration.
step cost to go from one node to another.
total cost to reach the present node from the start node.
the above output is give after every iteration the final matrix will give you the overall value of the depth, step cost and total cost.
at the last it gives the total number of nodes poped.
maximum fringe size
and ends with the 'search complete'

EXAMPLE- 
step 11
[[1 2 3]
 [4 5 6]
 [7 0 8]]
action= left , depth= 11 , step cost= 7 , total_cost= 55 

step 12
[[1 2 3]
 [4 5 6]
 [7 8 0]]
action= left , depth= 12 , step cost= 8 , total_cost= 63 

Nodes Poped 2141
Max Fringe Size 1331
Search Complete


the above is the output format for all the searches.

for A* Search I have taken the relaxed version of the problem named 'fair_manhattan' and made I made all the step cost as 1 for my heuristic.
