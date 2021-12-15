# ShortestRoutingMap 🗺️

In wanting to learn more about the A* Search Algorithm, I decided to build a program that would allow me visualize the search algorithm as it works to try and find the end node from the starting node.


Many applications have been built like this showing sorting algorithms or pathfinding algorithms, however I wanted to make it more like a game. Something interactive that the user can change and try to see how the visualization changes as the walls and start/end nodes are adjusted. Therefore, I built this program to allow people to do that. Users can add the starting and end nodes, then adding the walls so that they can test how the A* search algorithm works when faced with walls that are blocking its path.


In introducing the interactivity for the user, pygame was used to create the environment for the routing map to occur. We can imagine this as a real-world type map where the walls are buildings that block the perfect route from the starting node to the end node. Of course, in real-life there will be weights to the nodes, however this is a good starting point for seeing how the A* Search Algorithm evaluates its route to reach the end node.

Here is a short video showing the functionality of the program:
<video src="https://user-images.githubusercontent.com/59411811/146115886-3415243c-62dc-4981-8eef-f47561b4e314.mov" width="400" height="400">

## Features:
• Implemented the A* Search Algorithm to find the shortest path while visualising the areas searched and highlighting the path once found.
• Introduced functionality allowing the user to add walls, remove walls, and choose the starting nodes and end nodes.

## Challenges:
- Previously, I did not have too much experience using pygame for visualizations. I had used pygame for making short games in the past, but using it to implement the A* search algorithm was a challenge at times.
- Additionally, this project was collaborative which created challenges in designating tasks and understanding how the project would come together.
  
## Languages and tools used:
Created with Python & pygame library.

------------------------------------
Date project started: 14th May 2021
  
Date project finished: 24th May 2021
