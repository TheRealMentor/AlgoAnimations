# Animation of Algorithms

This repository contains the animations of algorithms - BFS, DFS and Minimum Spanning Tree. All of the animations are done in JavaScript using a js framework - [Cytoscape.js](https://js.cytoscape.org/).

## Instructions

How to use these animations? It is simple. Follow the steps below:

### Use animation for BFS and DFS

* Enter the start vertex
* Click *'Run BFS'* or *'Run DFS'* to see the animation for the algorithm on the default graph.
* If you want to choose a different start vertex, click *'Clear'*. It will reload the page.

### Use animation for Minimum Spanning Tree

* Just click on *'Run Kruskal'*. It will show animation for minimum spanning tree using Kruskal's algorithm.

### Create new graphs

* To create new graphs, you need to enter new edges in the textarea provided.
* Click on *'Remove Graph'* to delete the default graph.
* After you have added the edges in the textarea. Click on *'Create Graph'*. It will create the graph for you.

### Format for entering edges

* Use the following format for entering edges in BFS or DFS. Example:
<p>a b</p>
<p>b c</p>
<p>c d</p>
<p>d a</p>
* This will create a new graph with following edges: *ab, bc, cd* and *da*.
* Use the following format for entering edges in MST. Example:
<p>a b 1</p>
<p>b c 2</p>
<p>c d 3</p>
<p>d a 4</p>
* This will create a new graph with following edges: *ab, bc, cd, da* with weights: *1, 2, 3, 4* respectively.
