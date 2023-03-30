# Dynamically Change the Height of Each Bar
[link](https://www.freecodecamp.org/learn/data-visualization/data-visualization-with-d3/dynamically-change-the-height-of-each-bar) [solution](./solution.html)
<br>
The height of each bar can be set to the value of the data point in the array, similar to how the x value was set dynamically.
```
selection.attr("property", (d, i) => {

})
```
Here d would be the data point value, and i would be the index of the data point in the array.
Change the callback function for the height attribute to return the data value times 3.

Note: Remember that multiplying all data points by the same constant scales the data (like zooming in). It helps to see the differences between bar values in this example.

## Tests
Waiting: The first rect should have a height of 36.
Waiting: The second rect should have a height of 93.
Waiting: The third rect should have a height of 66.
Waiting: The fourth rect should have a height of 51.
Waiting: The fifth rect should have a height of 75.
Waiting: The sixth rect should have a height of 54.
Waiting: The seventh rect should have a height of 87.
Waiting: The eighth rect should have a height of 42.
Waiting: The ninth rect should have a height of 27.