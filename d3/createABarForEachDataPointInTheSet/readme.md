# Create a Bar for Each Data Point in the Set
[link](https://www.freecodecamp.org/learn/data-visualization/data-visualization-with-d3/create-a-bar-for-each-data-point-in-the-set) [solution](./solution.html)
<br>
The last challenge added only one rectangle to the svg element to represent a bar. Here, you'll combine what you've learned so far about data(), enter(), and SVG shapes to create and append a rectangle for each data point in dataset.

A previous challenge showed the format for how to create and append a div for each item in dataset:
```
d3.select("body").selectAll("div")
  .data(dataset)
  .enter()
  .append("div")
```
There are a few differences working with rect elements instead of div elements. The rect elements must be appended to an svg element, not directly to the body. Also, you need to tell D3 where to place each rect within the svg area. The bar placement will be covered in the next challenge.
Use the data(), enter(), and append() methods to create and append a rect for each item in dataset. The bars should display all on top of each other; this will be fixed in the next challenge.

## Tests
Waiting: Your document should have 9 rect elements.
Waiting: Your code should use the data() method.
Waiting: Your code should use the enter() method.
Waiting: Your code should use the append() method.