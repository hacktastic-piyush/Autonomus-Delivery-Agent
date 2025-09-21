<h1>🤖 Autonomous Delivery Agent: Pathfinding Simulator</h1> 🗺️<br>
This project simulates an autonomous delivery agent navigating a city grid to find the most efficient path from a start point to a destination. It implements and compares three popular pathfinding algorithms: A* Search, Breadth-First Search (BFS), and Depth-First Search (DFS).<br><br>

The core objective is to demonstrate how different algorithms solve the same problem, with a special focus on fuel optimization using the A* search algorithm.<br><br>

<h3>✨ Features</h3><br>
<h5>A* Search:</h5> Finds the optimal path with the least "fuel" consumption (least number of steps).<br>

<h5>Breadth-First Search (BFS):</h5> Guarantees finding the shortest path in an unweighted grid.<br>

<h5>Depth-First Search (DFS):</h5> Explores a valid path to the goal, but does not guarantee the shortest or most efficient route.<br>

<h5>Interactive Command-Line Interface:</h5> A simple menu allows you to choose which algorithm to run or to see all results at once.
<br>
<h5>Grid Visualization:</h5> The program outputs a clear, text-based visualization of the grid, highlighting the path found by the chosen algorithm.<br>

<h3>🚀 How to Run</h3><br>
<h5>Prerequisites:</h5> Ensure you have Python 3 installed on your system.<br>

<h5>Save the file:</h5> Save the autonom.py file to your local machine.<br>

<h5>Run from the terminal:</h5> Open your terminal or command prompt, navigate to the directory where you saved the file, and execute the following command:<br>

python autonom.py<br>

<h5>Follow the prompts:</h5> The program will present a menu. Simply enter the number corresponding to the algorithm you wish to run.<br>

<h3>🧠💡 Algorithms Explained</h3><br>
<h5>⭐ A* Search (Fuel Optimized)</h5><br>
A* is an intelligent pathfinding algorithm that uses a heuristic to guide its search. In this project, the heuristic is the Manhattan distance, which estimates the remaining distance to the goal. The algorithm prioritizes paths that have a low total cost, where the cost is the sum of fuel consumed and the estimated remaining fuel. This makes it ideal for finding the most fuel-efficient route.<br>

<h5>🔍 Breadth-First Search (BFS)</h5><br>
BFS explores the grid layer by layer, guaranteeing that it finds the shortest path in terms of steps. It is a simple and effective algorithm for unweighted grids but can be less efficient in large, complex environments compared to A*.<br>

<h5>🌳 Depth-First Search (DFS)</h5><br>
DFS explores as far as possible along each branch before backtracking. While it will find a valid path to the goal if one exists, it does not consider the path's length or cost. Therefore, the path found by DFS is often not the most efficient.<br>

<h5>⚖️ Comparison Summary</h5><br>
A* vs. BFS: In this grid, where each step has a uniform cost, both A* and BFS will find the shortest path, which also corresponds to the least fuel consumption.<br>

DFS: DFS is included for comparison to show a non-optimal pathfinding strategy. The path it finds will be valid but could be significantly longer than the one found by A* or BFS.<br>
