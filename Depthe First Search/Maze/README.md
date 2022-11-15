# **Introduction:**

DFS Algorithm is used to generate the maze.It is graph/tree traversal algorithm that follows a path as far as it can until it either, reaches the goal.
It can start from a random point and keep digging paths in on.


# **Design:**

## **UnClear Route(Hotel, Hospital)-Matrix:**

The ball can go through the empty spaces by rolling right, left, up, down, but it won't stop rolling until hitting a wall.
When the ball stops, it could choose the next direction.

<img width="457" alt="g2" src="https://user-images.githubusercontent.com/23255126/201502579-142715c7-3576-4f42-a9a3-9aa66e11509b.png">



<img width="560" alt="g3" src="https://user-images.githubusercontent.com/23255126/201502610-b7a4eda0-5139-4ad8-ab32-711b9ed3e71e.png">


<img width="367" alt="g4" src="https://user-images.githubusercontent.com/23255126/201502624-64c54022-20e1-407d-a400-a27f9ddd81c3.png">


<img width="457" alt="g5" src="https://user-images.githubusercontent.com/23255126/201502629-f38c73c9-1c51-4861-ac2f-59c9bb6d25d6.png">

**Start:**
* 0:  right →hits wall
* A: left →hits wall
* H: down→ hits wall
* I: Destination


## **Clear Route(Street, Highway)-Tree:**

We'll choose a random cell to start from and traverse the grid using depth first search.
Whenever a new cell is visited, the wall between the new cell and the previous cell is knocked down.
The start cell (or root node) will always be the top-left most cell
The exit cell (or goal node) will always be the bottom-right most cell

<img width="154" alt="g1" src="https://user-images.githubusercontent.com/23255126/201502701-93abcd5b-c71d-4996-8475-90051c957bb3.png">


<img width="209" alt="d4" src="https://user-images.githubusercontent.com/23255126/201502706-5e432aa6-b828-47ee-90f4-a64814868673.png">

## **Code:**   https://github.com/divyapandey03/Algorithm/blob/main/Depthe%20First%20Search/Maze/dfsmaze.py

## **Run Program:**

### **On Ubuntu:**

* Download dfsmaze.py from the code link
* run python code: python3 dfsmaze.py

### **Visual Studio:**

* create dfsmaze.py project
* click the run button on the VSC

## **Output:**

<img width="794" alt="g9" src="https://user-images.githubusercontent.com/23255126/201502808-76066d28-b026-4041-9dd1-ea9a24296e56.png">


# Presentation Link:
- https://docs.google.com/presentation/d/1zpo2yfb6JjBoUw89pHixetzNvd9EyfNA/edit?usp=sharing&ouid=115854624782305611491&rtpof=true&sd=true
