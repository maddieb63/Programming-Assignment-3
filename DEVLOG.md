DEVLOG

Entry #1:
The first problem that I ran into was how to go from the more conceptual ideas of DFS to actual code. I knew basic parameters given in the assignment, but had to then apply those to the concepts taught in class. I started by writing out a general plan based on the parameters, then came the harder part of the designing. I had to figure out generally which loops were needed. I knew definitely an if statement to break me out of the recursion once the exit was found. I need a loop to go in all directions of the current node to look for the next available one. And then I also need if statements to check the validity of each move based on my paramters which would be if the node was already visited or if it were out of bounds. Now that I have an outline I can transition from the pseudo code to actual code then test out what else is going to be needed. 


Entry #2:
The next part in development is how to actually do the maze traversing. I know I have to go in all 4 directions and the direction arrays already provide the like base moves, so this for loop is supposed to iterate through that array and change up the coordinates of the current node, finding the best next node in the maze solution. Now I will have to make sure none of the parameters are missed when checking the new nodes and add in recursion. Once I add the recursive step I can start testing out different scenarios. 
