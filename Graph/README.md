# Graph
  <pre>
  <b><a href="https://github.com/teja963/DSA-and-MYSQL/blob/master/Graph/1.%20Steps%20by%20Knight.cpp">Steps by Knight</a></b>
  Use bfs approach by making all possiblities frst
  dp intiliaze -1, if we moved to that mark it as 0
  
  <b><a href="https://github.com/teja963/Advanced-DSA/blob/master/Graph/9.%20Transitive%20closure%20of%20a%20graph.cpp">Transitive closure of a graph</a></b>
  frst track the all the destinations that particular node reaches(visited array)
  after that update adjacency list getting visited array
  
  <b><a href="https://github.com/teja963/Advanced-DSA/blob/master/Graph/10.%20Find%20whether%20path%20exist.cpp">Find whether path exist</a></b>
  after finding source or destination, go dfs approach (make sure all edge case implemented like)
  <b>i < 0 || i >= size || j < 0 || j >= size || grid[i][j] == 0</b> return false; 
  </pre>
# NOTE
  <pre>
  <b><a href="https://github.com/teja963/DSA-and-MYSQL/blob/master/Graph/2.%20Find%20the%20town%20judge.cpp">Find town Judge(Indeg and Outdeg Concept)</a></b>
  </pre>
# Theory
  <pre>
  <b><a href="https://github.com/teja963/Advanced-DSA/blob/master/Graph/8.%20Eulerian%20Path%20in%20Undirected%20path.cpp">Eulerian Path</a></b>
  	  number of vertices with an odd edges is > 2 then no path
  	  if it has even, then we start from any nodes (odd_vertices == 0)
  	  if it has 2, then we start from any 2 vertices (odd_vertices == 2)
  	  there will be no case where exactly one vertex has odd number of edges
  	  
  <b>A spanning tree of a connected graph is a subgraph that contains all of that graph’s
     vertices and is a single tree.</b>
  
  <b>In dfs approach make a visulization of passing and marking nodes for better</b>
  </pre>
