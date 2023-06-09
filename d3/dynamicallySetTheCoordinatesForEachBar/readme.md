# Dynamically Set the Coordinates for Each Bar
[link](https://www.freecodecamp.org/learn/data-visualization/data-visualization-with-d3/dynamically-set-the-coordinates-for-each-bar) [solution](./solution.html)
<br>
The last challenge created and appended a rectangle to the svg element for each point in dataset to represent a bar. Unfortunately, they were all stacked on top of each other.

The placement of a rectangle is handled by the x and y attributes. They tell D3 where to start drawing the shape in the svg area. The last challenge set them each to 0, so every bar was placed in the upper-left corner.

For a bar chart, all of the bars should sit on the same vertical level, which means the y value stays the same (at 0) for all bars. The x value, however, needs to change as you add new bars. Remember that larger x values push items farther to the right. As you go through the array elements in dataset, the x value should increase.

The attr() method in D3 accepts a callback function to dynamically set that attribute. The callback function takes two arguments, one for the data point itself (usually d) and one for the index of the data point in the array. The second argument for the index is optional. Here's the format:
```
selection.attr("property", (d, i) => {

})
```
It's important to note that you do NOT need to write a for loop or use forEach() to iterate over the items in the data set. Recall that the data() method parses the data set, and any method that's chained after data() is run once for each item in the data set.
Change the x attribute callback function so it returns the index times 30.

Note: Each bar has a width of 25, so increasing each x value by 30 adds some space between the bars. Any value greater than 25 would work in this example.

## Tests
Waiting: The first rect should have an x value of 0.
Waiting: The second rect should have an x value of 30.
Waiting: The third rect should have an x value of 60.
Waiting: The fourth rect should have an x value of 90.
Waiting: The fifth rect should have an x value of 120.
Waiting: The sixth rect should have an x value of 150.
Waiting: The seventh rect should have an x value of 180.
Waiting: The eighth rect should have an x value of 210.
Waiting: The ninth rect should have an x value of 240.