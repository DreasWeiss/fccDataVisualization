# Add Labels to D3 Elements
[link](https://www.freecodecamp.org/learn/data-visualization/data-visualization-with-d3/work-with-dynamic-data-in-d3) [solution](./solution.html)
<br>
D3 lets you label a graph element, such as a bar, using the SVG text element.

Like the rect element, a text element needs to have x and y attributes, to place it on the SVG. It also needs to access the data to display those values.

D3 gives you a high level of control over how you label your bars.
The code in the editor already binds the data to each new text element. First, append text nodes to the svg. Next, add attributes for the x and y coordinates. They should be calculated the same way as the rect ones, except the y value for the text should make the label sit 3 units higher than the bar. Finally, use the D3 text() method to set the label equal to the data point value.

Note: For the label to sit higher than the bar, decide if the y value for the text should be 3 greater or 3 less than the y value for the bar.

## Tests
The first text element should have a label of 12 and a y value of 61.
Waiting: The second text element should have a label of 31 and a y value of 4.
Waiting: The third text element should have a label of 22 and a y value of 31.
Waiting: The fourth text element should have a label of 17 and a y value of 46.
Waiting: The fifth text element should have a label of 25 and a y value of 22.
Waiting: The sixth text element should have a label of 18 and a y value of 43.
Waiting: The seventh text element should have a label of 29 and a y value of 10.
Waiting: The eighth text element should have a label of 14 and a y value of 55.
Waiting: The ninth text element should have a label of 9 and a y value of 70.