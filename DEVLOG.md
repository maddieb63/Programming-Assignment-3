DEVLOG

Entry #1:
The first problem that I ran into was how to go from the more conceptual ideas of DFS to actual code. I knew basic parameters given in the assignment, but had to then apply those to the concepts taught in class. I started by writing out a general plan based on the parameters, then came the harder part of the designing. I had to figure out generally which loops were needed. I knew definitely an if statement to break me out of the recursion once the exit was found. I need a loop to go in all directions of the current node to look for the next available one. And then I also need if statements to check the validity of each move based on my paramters which would be if the node was already visited or if it were out of bounds. Now that I have an outline I can transition from the pseudo code to actual code then test out what else is going to be needed. 


Entry #2:
The next part in development is how to actually do the maze traversing. I know I have to go in all 4 directions and the direction arrays already provide the like base moves, so this for loop is supposed to iterate through that array and change up the coordinates of the current node, finding the best next node in the maze solution. Now I will have to make sure none of the parameters are missed when checking the new nodes and add in recursion. Once I add the recursive step I can start testing out different scenarios. 


Entry #3: 
I tried to run what I had to see if there were any syntax errors and I found many. There were a couple basic things like accidentally using "=" instead of "==" but I got more issues with the parameters from the method dfs. There were some problems with "invalid initialization" and then parameters not working correctly. The first thing I did was check to make sure the parameters were in the same order that I call them in later. I made the mistake that I used the automatic CLion AI thing that tries to fill in what you think it would say and so I had to add in additional paramters which made my program no execute. The code now runs with the little fixes although it does not yet give me the quickest path. 
