# Algorithm-Best

The main idea is to solve the Gas station problem.
The problem goes as follows:

First to have a good intuition of the problem, let's imagine a graph with n vertices.
Each vertices is representing a gas station that has a certain amount of fuel.
The vertices are connected to each other such that the graph forms a circle. So for n vertices we have n edges.
On each edge we have a number representing the amount of fuel we need to travel from vertex a to vertex b.

To avoid using complex techniques to solve the problem, let's make it simpler by creating our inputs as two arrays.
The first one contains the amount of fuel we can get in each gas station. The second one contains the amount of fuel it takes to
travel from a vertex to another.

Then we have the first algorithm called "Best"
This algorithm will take as input 
