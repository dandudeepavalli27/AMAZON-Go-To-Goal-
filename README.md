# AMAZON-Go-To-Goal
Aim
To compute the Euclidean distance between the robot’s current position and the goal.
General Objective
To understand go-to-goal navigation strategies and how distance calculation helps robots determine the shortest path.
Specific Objective
To compute distance using:
d
=
x
2
+
y
2
d= 
x 
2
 +y 
2
 
​	
 

-10
-8
-6
-4
-2
2
4
6
8
10
-10
-5
5
10
(6.0, 6.0)
(-6.0, -6.0)
d = 16.97
Given:
Start Position = (0, 0)
Goal Position = (6, 8)
Dataset
2D Navigation Dataset
Source: Navigation2 (Nav2)
Procedure
Input start coordinates
Input goal coordinates
Apply distance formula
Compute distance
Display result
Algorithm
Start
Input coordinates
Compute distance
Display result
Stop
Code Logic
distance = ((x2 - x1)**2 + (y2 - y1)**2) ** 0.5
Python Code
# SESSION 27 – Go-To-Goal (Distance Calculation)

import math

# Step 1: Input coordinates
x1, y1 = 0, 0
x2, y2 = 6, 8

# Step 2: Compute distance
distance = math.sqrt((x2 - x1)**2 + (y2 - y1)**2)

# Step 3: Display result
print("Distance =", int(distance), "m")

print("\nProgram Executed Successfully")
Output
Distance = 10 m

Program Executed Successfully
Result
The Euclidean distance between the start and goal is:
Distance = 10 m
Industry Application
Go-to-goal navigation is used in:
Mobile robots
Autonomous vehicles
Delivery robots
Warehouse automation
Companies like Amazon use this in:
Warehouse robotics
Path planning
Autonomous navigation systems
Conclusion
Euclidean distance helps robots determine the shortest path, making it essential for efficient navigation.
