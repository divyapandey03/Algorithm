# **Introduction:** 

The breadth-first search or BFS algorithm is used to search a tree or graph data structure for a node that meets a set of criteria.
In BFS, we traverse one level at a time and then jump to the next level. The BFS algorithm makes use of the queue data structure for implementation.
In BFS, we always reach the final goal state

# **Design:**

- The ball can go through the empty spaces by rolling right, left, up, down
- It won't stop rolling until hitting a wall
- When the ball stops, it could choose the next direction.
- The Search Sequence is Right ==> Left ==> Top ==> Bottom


**Maze** =[[0,0,1,0,0],
      [0,0,0,0,0],
      [0,0,0, 1,0],
      [1, 1,0, 1, 1],
      [0,0,0,0,0]]


0→ Empty,  1→Wall
Start: [0,4]
Destination: [2,1]




<img width="356" alt="bfs3" src="https://user-images.githubusercontent.com/23255126/201551423-9fbe4362-4d2d-4f06-8ee4-95dd206caf62.png">

The ball can go through the empty spaces by rolling right, left, up, down.

<img width="395" alt="k1" src="https://user-images.githubusercontent.com/23255126/201551426-8b41f42e-b1c3-4f9a-86e5-4d791699d7fc.png">

<img width="464" alt="bfs1" src="https://user-images.githubusercontent.com/23255126/201551439-d741b600-3320-4dea-9bb0-5877768d9add.png">

<img width="455" alt="BFS2" src="https://user-images.githubusercontent.com/23255126/201551446-409babde-12eb-4172-af53-19c47123bdb2.png">

 # **Code:** https://github.com/divyapandey03/Algorithm/blob/main/Breadth%20First%20Search/bfsmaze.py
 
 # Run Program: 
 
### **On Ubuntu:**
- Download bfsmaze.py from the code link
- run python code: python3 bfsmaze.py

 ### **Visual Studio:**
- create bfsmaze.py project
- click the run button on the VSC

# **Output:**



<img width="794" alt="g9" src="https://user-images.githubusercontent.com/23255126/201551662-728791af-83e6-41e7-a38e-9ef1d9aeae5d.png">
