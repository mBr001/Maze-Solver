# Maze Solver
Solves Mazes taking an image input, along with the starting and ending points.

There are two Algorithms here which solve mazes. One of them is a Shortest Path Algorithm, the other, Minimal Tree Algorithm along with dead end filling. Both written in Python. 

The Shortest Path Algorithm takes longer, infact 10 times longer than Minimal Tree - Dead Ending Filling Algorithm.
But, 
The Dead Ending filling part of the algorithm may not work for all mazes. 


## Module dependencies
It's important that the following Modules are installed. 
1. [Numpy](http://www.numpy.org/) and [Matplotlib](https://matplotlib.org/)
2. [OpenCV](http://docs.opencv.org/3.0-beta/doc/py_tutorials/py_tutorials.html)


## Process
Both the Algorithms take images as input. But, with certain necessary conditions. 
1) The Entrance and the Exit of the maze must be closed and marked.
2) The Co-ordinates of the Entrance and the Exit in the image must be noted.
3) The gap between the walls must also be noted, since it is an input into the algorithm. 
4) The Input image is "prefered" to be Black and White.


**Example :**  
  
**The Input Image**
![Input Image](https://github.com/prajwalsouza/Maze-Solver/blob/master/Images/InputImageCompressed.jpg)
  
  

**Tree Diagram**  
Both Algorithms draw a tree like graph.
  
![Input Image](https://github.com/prajwalsouza/Maze-Solver/blob/master/Images/TreeDataCompressed.png)
  
  
**The Solution**  
The Solution is then generated by Shortest Path tracing in Dijkstra Algorithm case and by Dead End Filling in the Minimal Tree Algorithm case.  
![Input Image](https://github.com/prajwalsouza/Maze-Solver/blob/master/Images/MazeSolutionCompressed.png)
  
  

For more details on how the algorithm proceeds refer the comments in the program files.  
  
Thank you.  
  
[Prajwal DSouza](https://prajwalsouza.github.io/)  
3rd July 2017

