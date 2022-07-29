# JS-mini-Project-Maze-Generator-
Hosted on Netlify :  https://iridescent-lily-9a1a92.netlify.app
<ul>
   <li> This Maze Generator uses Depth First Search algorithm.</li>
   <li>The depth-first search algorithm of maze generation is frequently implemented using backtracking. This can be described with a following recursive routine</li>
      <ol>
        <li>Given a current cell as a parameter</li>
        <li>Mark the current cell as visited</li>
        <li>While the current cell has any unvisited neighbor cells</li>
      <ol>
            <li>Choose one of the unvisited neighbors</li>
            <li>Remove the wall between the current cell and the chosen cell</li>
            <li>Invoke the routine recursively for a chosen cell which is invoked once for any initial cell in the area.</li>
      </ol>
    </ol>
  <li>The default  Maze Size is 500  Square with maze rows/columns equal to 20.</li>
  <li>The Maximum allowed Maze size is set to 600  with rows/columns as 50.</li>
  <li>This project helps in learning/practicing the Data Structures like Stacks, Array Matrix and algorithms like Backtracking and Recursion.</li>
  <li>The HTML <canvas> element was used to draw graphics on a web page.</li>

</ul>
  <p>References: Wikipedia  https://en.wikipedia.org/wiki/Maze_generation_algorithm</p>
