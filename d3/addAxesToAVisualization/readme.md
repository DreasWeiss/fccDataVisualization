# Add Axes to a Visualization
[link](https://www.freecodecamp.org/learn/data-visualization/data-visualization-with-d3/add-axes-to-a-visualization) [solution](./solution.html)
<br>
Another way to improve the scatter plot is to add an x-axis and a y-axis.

D3 has two methods, axisLeft() and axisBottom(), to render the y-axis and x-axis, respectively. Here's an example to create the x-axis based on the xScale in the previous challenges:
```
const xAxis = d3.axisBottom(xScale);
```
The next step is to render the axis on the SVG. To do so, you can use a general SVG component, the g element. The g stands for group. Unlike rect, circle, and text, an axis is just a straight line when it's rendered. Because it is a simple shape, using g works. The last step is to apply a transform attribute to position the axis on the SVG in the right place. Otherwise, the line would render along the border of the SVG and wouldn't be visible. SVG supports different types of transforms, but positioning an axis needs translate. When it's applied to the g element, it moves the whole group over and down by the given amounts. Here's an example:
```
const xAxis = d3.axisBottom(xScale);

svg.append("g")
   .attr("transform", "translate(0, " + (h - padding) + ")")
   .call(xAxis);
```
The above code places the x-axis at the bottom of the SVG. Then it's passed as an argument to the call() method. The y-axis works in the same way, except the translate argument is in the form (x, 0). Because translate is a string in the attr() method above, you can use concatenation to include variable values for its arguments.
The scatter plot now has an x-axis. Create a y-axis in a variable named yAxis using the axisLeft() method. Then render the axis using a g element. Make sure to use a transform attribute to translate the axis by the amount of padding units right, and 0 units down. Remember to call() the axis.

## Tests
Waiting: Your code should use the axisLeft() method with yScale passed as the argument.
Waiting: The y-axis g element should have a transform attribute to translate the axis by (60, 0).
Waiting: Your code should call the yAxis.