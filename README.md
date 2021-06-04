# algo1_exe1_MST

In this project I have implemented the Prim's Algorithm - finding a Minmum-Spanning-Tree given an Undirected-Weighted-Graph.

The Time-Complexity to find MST with Prim's Algorithm is : O(ELOGV).

Moreover, in this project you can find an O(V+E) solution to the problem: Update MST if edge is added.

In order to do so without running Prim's Algorithm again, I used DFS Algorithm to detect a cycle in the graph and removed the edge with the maximum weight from that cycle, thus updated the MST.

You can find here an example of an Undirected-Weighted-Graph that includes 22 vertices and 50 weighted-edges. First, I found the Minmum-Spanning-Tree and printed it. Second, I added an edge that doesn't effect the MST and printed it. Third, I added an edge that effects the MST and printed it.

For any questions, feel free to contact me through: lino1998y@gmail.com
