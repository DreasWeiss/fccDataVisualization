# Update the Height of an Element Dynamically
[link](https://www.freecodecamp.org/learn/data-visualization/data-visualization-with-d3/update-the-height-of-an-element-dynamically) [solution](./solution.html)
<br>
The previous challenges covered how to display data from an array and how to add CSS classes. You can combine these lessons to create a simple bar chart. There are two steps to this:

Create a div for each data point in the array
Give each div a dynamic height, using a callback function in the style() method that sets height equal to the data value
Recall the format to set a style using a callback function:
```
selection.style("cssProperty", (d) => d)
```
Add the style() method to the code in the editor to set the height property for each element. Use a callback function to return the value of the data point with the string px added to it.

## Tests
Waiting: The first div should have a height of 12 pixels.
Waiting: The second div should have a height of 31 pixels.
Waiting: The third div should have a height of 22 pixels.
Waiting: The fourth div should have a height of 17 pixels.
Waiting: The fifth div should have a height of 25 pixels.
Waiting: The sixth div should have a height of 18 pixels.
Waiting: The seventh div should have a height of 29 pixels.
Waiting: The eighth div should have a height of 14 pixels.
Waiting: The ninth div should have a height of 9 pixels.